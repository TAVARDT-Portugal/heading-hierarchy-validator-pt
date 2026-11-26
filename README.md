<p align="center">
  <a href="https://ag.tavardt.com/pt/">
    <img src="https://ag.tavardt.com/img/tavardt-banner.png" alt="TAVARDT" width="1024" />
  </a>
</p>

# Verificador de Estrutura de Titulos e Hierarquia H1-H6

[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Verificador Estrutura Titulos](https://img.shields.io/badge/TAVARDT-Heading%20Hierarchy-5b3cf5.svg)](https://tools.tavardt.com/pt/verificador-estrutura-titulos/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

Auditoria de tags de cabecalho HTML5 (H1-H6), unicidade de H1, deteccao de saltos de niveis e validacao da arvore semantica.

***

## Vetores de Risco e Impacto Operacional na Hierarquia de Titulos

A omissao ou multiplicidade de tags H1 fragmenta a compreensao tematica pelos motores de busca em Portugal, enfraquecendo o posicionamento. A desorganizacao dos cabecalhos confunde tecnologias assistivas e dificulta a leitura estruturada por leitores de ecra.

Saltar niveis hierarquicos na sequencia do documento viola diretamente as normas internacionais de acessibilidade W3C WCAG. Cabecalhos vazios criam marcadores fantasmas que prejudicam os indices tecnicos de auditoria semantica.

***

## Capacidades Centrais de Auditoria Tecnica

* **Verificacao de Tag H1 Principal**: Fiscaliza presenca e unicidade do titulo H1, deduzindo 40 pontos para ausencia e 15 pontos para declaracoes multiplas.
* **Deteccao de Saltos Hierarquicos**: Rastreia a progressao das tags identificando saltos que ultrapassem um nivel, com penalidade de ate 30 pontos.
* **Identificacao de Cabecalhos Vazios**: Mapeia tags de titulo desprovidas de texto interno, aplicando penalidade de ate 20 pontos.
* **Construcao da Arvore Estrutural**: Mapeia a hierarquia completa de H1 a H6 gerando a distribuicao quantitativa por nivel.
* **Pontuacao de Qualidade Semantica**: Computa uma nota tecnica de 0 a 100 categorizada em SATISFACTORY, ADVISORY ou UNSATISFACTORY.
* **Garantia de Acessibilidade Digital**: Valida marcos estruturais para conformidade com normas globais de inclusao digital.
* **Exportacao Automatizada em JSON**: Suporte a relatorios estruturados via flag curta para integracao direta em esteiras de CI/CD.

***

## Instalacao e Execucao

Requer Python 3.8 ou superior utilizando exclusivamente bibliotecas padrao.

```bash
git clone https://github.com/TAVARDT-Portugal/heading-hierarchy-validator-pt.git
cd heading-hierarchy-validator-pt
python heading_hierarchy_validator.py https://empresa.pt
```

Para gerar a saida em formato estruturado JSON em esteiras de integracao continua:

```bash
python heading_hierarchy_validator.py https://empresa.pt -j
```

***

## Perguntas Frequentes (FAQ Tecnico)

### 1. Como a ausencia ou multiplicidade de tags H1 prejudica o posicionamento organico?
Os motores de busca dependem da tag H1 como ancora semantica principal para compreender o assunto central do documento. A ausencia do H1 torna o contexto ambiguo, enquanto multiplas declaracoes diluem a forca das palavras-chave primarias.

### 2. Por que pular niveis de cabecalho como saltar de H1 direto para H3 viola a acessibilidade?
Os leitores de tela utilizam os cabecalhos para sintetizar um indice auditivo de navegacao para pessoas com deficiencia visual. Pular niveis desorienta a ordem logica de assimilacao e representa desconformidade com as diretrizes W3C WCAG.

### 3. Quais os riscos tecnicos de manter tags de cabecalho vazias no codigo HTML?
Titulos sem texto geram marcos fantasmas que confundem ferramentas assistivas e depreciam a nota de auditoria semantica. Os algoritmos de busca interpretam elementos vazios como falhas de desenvolvimento e reduzem a avaliacao tecnica da pagina.

### 4. Como uma estrutura de cabecalhos clara favorece a resposta de motores de IA?
Modelos de linguagem e sistemas de busca com IA analisam o documento em blocos hierarquicos para resumir conteudos e extrair respostas. Uma transicao logica de titulos permite identificar exatamente a secao de interesse e gerar citacoes precisas.

### 5. Qual a melhor pratica recomendada para ordenar secoes em paginas complexas?
Cada pagina deve possuir um unico H1 tematico, seguido por secoes demarcadas por H2 para cada topico principal. Subtopicos devem utilizar tags H3 e H4 sequencialmente, sem pular degraus, mantendo a coesao estrutural do conteudo.

***

## Consultoria em Arquitetura Semantica e Acessibilidade

Para projetos de grande porte e alinhamento com as diretrizes do W3C WCAG e de pesquisa, consulte a equipa da **TAVARDT**.

***

## Links Uteis

* **Portal Corporativo:** https://ag.tavardt.com/pt/
* **Suite de Diagnosticos:** https://tools.tavardt.com/pt/
* **Contacto Tecnico:** https://ag.tavardt.com/pt/contacto/

***

### Licenca
Distribuido sob a Licenca MIT. Consulte o arquivo LICENSE para termos completos.

***

© 2026 TAVARDT. Todos os direitos reservados.
