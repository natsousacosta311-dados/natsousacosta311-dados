<div align="center">

# 👋 Olá, eu sou Natasha de Sousa Costa

### AI Engineer · AI Analyst · Data & LLM Applications

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/seu-perfil)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/natsousacosta311-dados)
[![E-mail](https://img.shields.io/badge/E--mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:seu@email.com)

</div>

---

Formada em **Ciências Contábeis** pela UFPI e especialista em **Data Science e Analytics** pela USP/ESALQ.

Atualmente focada na construção de soluções com **Inteligência Artificial aplicada**, com ênfase em **LLMs, RAG e automação de processos inteligentes** — unindo minha base sólida em dados com o desenvolvimento de sistemas escaláveis orientados a IA.

---

## 🧠 Especialidades

- 🤖 Desenvolvimento de aplicações com **LLMs**
- 📚 Arquitetura de sistemas com **RAG** *(Retrieval-Augmented Generation)*
- 🔧 Processamento e preparação de dados para IA
- 🔁 Construção de **pipelines de dados** para suporte a modelos
- 📊 Análise de dados com foco em geração de **insights automatizados**

---

## 🛠️ Stack Tecnológica

### 🤖 IA & LLMs — Foco Atual

<p align="left">
  <img src="https://img.shields.io/badge/LangChain-000000?style=for-the-badge&logo=chainlink&logoColor=white"/>
  <img src="https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white"/>
  <img src="https://img.shields.io/badge/HuggingFace-FF9A00?style=for-the-badge&logo=huggingface&logoColor=white"/>
  <img src="https://img.shields.io/badge/RAG-FF6F00?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/FAISS-005571?style=for-the-badge"/>
</p>

### ⚙️ Engenharia de Dados & Cloud

<p align="left">
  <img src="https://img.shields.io/badge/Microsoft_Fabric-0078D4?style=for-the-badge&logo=microsoft&logoColor=white"/>
  <img src="https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white"/>
  <img src="https://img.shields.io/badge/Amazon_S3-569A31?style=for-the-badge&logo=amazons3&logoColor=white"/>
  <img src="https://img.shields.io/badge/Delta_Lake-00ADD8?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Databricks-FF3621?style=for-the-badge&logo=databricks&logoColor=white"/>
</p>

### 💻 Programação & Dados

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white"/>
</p>

---

## 🚀 Projetos em IA

### 🔹 Legal RAG Assistant — Análises Jurídicas 100% Open Source

[![Repositório](https://img.shields.io/badge/📁_Repositório-assistente--juridico--rag-181717?style=for-the-badge&logo=github)](https://github.com/natsousacosta311-dados/legal-rag-assistant)

> Sistema corporativo de análise e classificação de risco para contratos baseado em documentos (PDF), desenvolvido inteiramente com modelos gratuitos e locais (Zero-Cost API).

| Funcionalidade | Descrição Técnica |
|---|---|
| 📉 **Custo Zero (Open Source)** | Inferência rodando localmente com `TinyLlama` / Modelos do Hugging Face. |
| 🛡️ **Anti-Hallucination & Leakage** | Lógicas de segurança por expressões regulares mitigando vazamento de "system prompt" e invenções do LLM. |
| 📊 **Risk Engine Customizado** | Extração de variáveis baseadas em similaridade vetorial (`FAISS`) para inferir graus de risco financeiro (baixo, médio, alto). |

**Tecnologias:** `LangChain` · `Hugging Face (Transformers)` · `FAISS` · `Sentence-Transformers` · `PyPDF`


---

## 🏗️ Projetos em Engenharia de Dados

### 🔹 Pipeline de Clientes — Arquitetura Medalhão (Lakehouse)

[![Repositório](https://img.shields.io/badge/📁_Repositório-pipeline--clientes--medalhao-181717?style=for-the-badge&logo=github)](https://github.com/natsousacosta311-dados/pipeline-clientes-medalhao)

> Construção de pipeline de dados com arquitetura Medalhão em ambiente de Data Lake.

```
🟫 Bronze  →  Ingestão de dados brutos via Amazon S3
🥈 Silver  →  Limpeza, padronização e persistência em Delta Lake
🥇 Gold    →  Modelagem para consumo analítico e BI
```

**Tecnologias:** `PySpark` · `Spark SQL` · `OneLake` · `Delta Lake` · `Amazon S3`

---
### 🔹 AWS Glue Medallion Data Pipeline (🔥 Projeto Principal)

[![Repositório](https://img.shields.io/badge/📁_Repositório-aws--glue--medallion--pipeline-181717?style=for-the-badge&logo=github)](https://github.com/natsousacosta311-dados/aws-glue-medallion-data-pipeline)

 Pipeline de dados completo em ambiente AWS utilizando **Glue + S3 + Athena**, seguindo arquitetura Medalhão e práticas de engenharia de dados modernas.
 ### 🔍 Destaques técnicos

- ⚙️ **Orquestração de pipeline** com encadeamento de jobs (boto3)
- 🧪 **Data Quality na camada Silver**
  - Remoção de nulos e duplicados  
  - Validação de schema  
  - Logs de qualidade de dados  
- 🏗️ Arquitetura **Medallion (Bronze / Silver / Gold)**
- 📊 Camada Gold pronta para consumo via **Amazon Athena**
- 🔎 Consultas analíticas com SQL para geração de insights
- 
**Tecnologias:** `PySpark` · `Spark SQL` · `OneLake` · `Delta Lake` · `Amazon S3` · `AWS Glue`

### 📊 Exemplo de análise

```sql
SELECT 
    estado,
    COUNT(*) AS total_clientes
FROM gold_clientes
GROUP BY estado
ORDER BY total_clientes DESC;
```

### 🔹 Análise Escalável com Bike Sharing — Databricks

[![Repositório](https://img.shields.io/badge/📁_Repositório-analise--bike--sharing-181717?style=for-the-badge&logo=github)](https://github.com/natsousacosta311-dados/analise-bike-sharing-databricks)

> Processamento distribuído e análise de dados em larga escala.

- 🔄 ETL para análise de demanda histórica
- 📅 Identificação de padrões sazonais e climáticos
- ⚡ Processamento escalável com Spark

**Tecnologias:** `Databricks` · `PySpark` · `DBFS`

---

## 📈 Projetos de Data Science & Analytics

### 🔹 Marketplace Olist — Dashboard Analítico & NLP

[![Repositório](https://img.shields.io/badge/📁_Repositório-dashboard__olist-181717?style=for-the-badge&logo=github)](https://github.com/natsousacosta311-dados/dashboard_olist)

> Análise completa do marketplace com segmentação de clientes e análise de sentimentos.

- 👥 Segmentação de clientes com **RFV** *(Recência, Frequência e Valor)*
- 💬 Análise de sentimentos com **Machine Learning**
- 🎨 Interface desenvolvida no **Figma**

---

### 🔹 Clusterização com Microdados do ENEM

[![Repositório](https://img.shields.io/badge/📁_Repositório-analise--enem-181717?style=for-the-badge&logo=github)](https://github.com/natsousacosta311-dados/analise-enem)

> Análise socioeducacional com técnicas de redução de dimensionalidade e clusterização.

- 📉 Redução de dimensionalidade com **PCA**
- 🔵 Clusterização com **K-Means**
- 🏫 Análise socioeducacional dos perfis de candidatos

---

<div align="center">

## 📊 GitHub Stats

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=natsousacosta311-dados&show_icons=true&theme=tokyonight&hide_border=true)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=natsousacosta311-dados&layout=compact&theme=tokyonight&hide_border=true)

---

*"Dados têm um propósito. IA tem um potencial. Eu uno os dois."*

</div>

