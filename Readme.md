# Qualidade de Fornecimento de Energia Elétrica — Análise e Auditoria com IA

Este repositório contém o relatório técnico e os materiais didáticos desenvolvidos para a disciplina de **Sistemas de Distribuição de Energia Elétrica** do curso de Engenharia Elétrica no **CEFET/RJ - Campus Nova Friburgo**. 

O objetivo do projeto é analisar a aplicação prática dos indicadores de continuidade regulados pela ANEEL, utilizando Inteligência Artificial (IA) integrada a fontes controladas para otimizar o aprendizado técnico.

---

## 🎯 Escopo do Projeto

O foco principal deste trabalho está na **criação e auditoria crítica de um podcast técnico** gerado através da plataforma **NotebookLM**. O áudio correlaciona os fundamentos regulatórios com um estudo de caso real focado no cenário do município de Nova Friburgo baseado nos dados de **2025**.

Como materiais complementares para suporte ao estudo, o repositório também inclui:
*   📜 Resumo Dinâmico dos conceitos.
*   🧠 Mapa Mental estrutural dos indicadores.
*   📊 Infográfico Técnico de apoio visual.

---

## 📚 Fontes Controladas Utilizadas

Para mitigar o risco de alucinações da IA, o ambiente de consulta do NotebookLM foi restrito estritamente às seguintes fontes:

1.  **PRODIST Módulo 8 (ANEEL):** Regulação dos indicadores de continuidade.
2.  **Literatura de Referência:** *Introdução aos Sistemas de Distribuição de Energia Elétrica* (Nelson Kagan, Carlos César Barioni de Oliveira, Ernesto João Robba — 2ª Edição, Blucher, 2010).
3.  **Material Didático:** Slides da *Aula 4 - Qualidade de Fornecimento* do Prof. Paulo Victor de Souza Borges (CEFET/RJ).
4.  **Estudo de Caso:** Base de dados oficiais dos indicadores de Nova Friburgo (Ano de referência: 2025).

---

## 🛠️ Tecnologias e Ferramentas

*   **NotebookLM:** Geração do podcast técnico via IA com ancoragem de dados (*grounding*).
*   **Python / Pandas:** Manipulação preliminar e estudo dos dados do cenário de 2025.
*   **VS Code + Quarto:** Ambiente de desenvolvimento e sistema de publicação técnica utilizado para documentar o relatório final em PDF com formatação científica.

---

## 📁 Estrutura do Repositório

```text
├── Trabalho_3.qmd          # Arquivo fonte do relatório no Quarto
├── Trabalho_3.pdf          # Relatório técnico final gerado
├── Fontes/                 # PDFs e dados brutos utilizados como input da IA
├── Data/                   # Artefatos complementares (mapa mental, infográfico, etc.)
└── Readme.md               # Documentação principal do repositório