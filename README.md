# Verificador de Estrutura de Titulos e Hierarquia H1-H6

[![Verificador Estrutura Titulos](https://img.shields.io/badge/TAVARDT-Heading%20Hierarchy-5b3cf5.svg)](https://tools.tavardt.com/pt/verificador-estrutura-titulos/)
[![Jurisdicao](https://img.shields.io/badge/Jurisdicao-Portugal-00C853.svg)](https://ag.tavardt.com/pt/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

Inspecao da arquitetura de cabecalhos HTML, prevencao de descontinuidades de niveis e conformidade W3C.

Desenvolvido e mantido pela equipa de acessibilidade e semantica web da **[TAVARDT Portugal](https://ag.tavardt.com/pt/)**.

---

## Capacidades de Inspecao de Estrutura de Titulos

* **Auditoria de Unicidade H1**: Confirmacao de apenas uma balisa `<h1>` representativa do tema principal do documento.
* **Detecao de Saltos Hierarquicos**: Identificacao de progressoes irregulares de niveis que desorientam utilizadores de leitores de ecra.
* **Controlo de Conteudo dos Titulos**: Deteccao de cabecalhos em branco ou com extensao excessiva.
* **Visualizacao da Estrutura de Seccoes**: Representacao linear indentada da organizacao semantica de conteudos.
* **Indice de Qualidade Semantica**: Avaliacao quantitativa de 0 a 100 com recomendacoes de correcao W3C.

---

## Instalacao e Execucao

Requer Python 3.8 ou superior recorrendo exclusivamente a biblioteca padrao.

```bash
git clone https://github.com/TAVARDT-Portugal/heading-hierarchy-validator-pt.git
cd heading-hierarchy-validator-pt
python heading_hierarchy_validator.py https://empresa.pt
```

Exportacao em formato estruturado JSON:

```bash
python heading_hierarchy_validator.py https://empresa.pt --json
```

---

## Ferramenta Oficial na Web

Aceda a plataforma online para diagnosticos completos:

* **[Verificador de Estrutura de Titulos Oficial](https://tools.tavardt.com/pt/verificador-estrutura-titulos/)**
* **[Portal TAVARDT Portugal](https://ag.tavardt.com/pt/)**

---

## Apoio Tecnico e Consultoria

Para alinhamento estrutural com Normas Europeias de Acessibilidade Web e W3C, contacte os consultores da **[TAVARDT Portugal](https://ag.tavardt.com/pt/contato/)**.
