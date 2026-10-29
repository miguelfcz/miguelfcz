# Miguel Fonseca

**Analista de Dados @AeC · Engenharia de IA**
LLM • RAG • GraphRAG • MCP • Agentes • Fine-Tuning

[![LinkedIn](https://img.shields.io/badge/LinkedIn-miguelfcz-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/miguelfcz/)
[![Email](https://img.shields.io/badge/Email-miguelcf2006@gmail.com-D14836?style=flat&logo=gmail&logoColor=white)](mailto:miguelcf2006@gmail.com)

---

## Sobre

Estudante de Ciência da Computação (Unipê, conclusão em 2027) e Analista de Dados na AeC.
Construo sistemas de IA generativa de ponta a ponta: RAG híbrido, GraphRAG, orquestração de agentes com tool calling/MCP e guardrails, conectados a bancos relacionais, vetoriais e de grafos.

Na AeC, trabalho com ETL (SSIS + SQL Server) e Power BI, refatorando dashboards e adicionando insights interativos aos indicadores.

---

## Projetos em destaque

### [RAG Jurídico](https://github.com/miguelfcz/rag-juridico)
Hybrid RAG + GraphRAG com agente e guardrails para análise de contratos e processos.
- Busca híbrida no **Qdrant** (embeddings densos Vertex AI + BM25 esparso, fusão RRF)
- Grafo de conhecimento no **FalkorDB**, extraído por LLM a partir de PDF/MD/TXT
- Agente com function calling que orquestra SQL (**PostgreSQL via MCP**), grafo e busca híbrida
- Guardrails de entrada e saída: mascaramento de CPF/CNPJ e verificação de citações

`Python` `Streamlit` `Qdrant` `FalkorDB` `PostgreSQL` `Gemini` `MCP`

### [YouTube Data Pipeline & AI Copilot](https://github.com/miguelfcz/Youtube-API-Data-Project)
Pipeline ELT com qualidade de dados e camada de IA.
- ETL orquestrado com **Airflow**, Data Warehouse em PostgreSQL, tudo em **Docker Compose**
- Validação com **Soda Core**; o Gemini gera relatório executivo ou explica anomalias
- Chatbot RAG (FastAPI) sobre o código e os relatórios do projeto
- CI com **GitHub Actions** + testes com Pytest

`Python` `Airflow` `PostgreSQL` `Soda Core` `Docker` `FastAPI` `Gemini`

---

## Stack

| Área | Tecnologias |
|---|---|
| IA e LLMs | RAG híbrido, GraphRAG, agentes e orquestração multiagente, MCP, guardrails, Fine-Tuning (LoRA/PEFT), Gemini/Vertex AI, LangChain, Ollama |
| Dados e bancos | Python, SQL, PostgreSQL, SQL Server, SSIS, Airflow, Qdrant, FalkorDB, Power BI |
| Engenharia | Docker, Git, GitHub Actions, Pytest, FastAPI, Streamlit, Java/Spring, Azure |

**Certificação:** Microsoft Certified: Azure Data Fundamentals (DP-900)
