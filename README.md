<h1 align="center">João</h1>

<p align="center">
  <a href="https://github.com/jpalmda">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1200&color=38BDF8&center=true&vCenter=true&width=640&lines=Engenharia+de+Dados;Python+%C2%B7+SQL+%C2%B7+Airflow+%C2%B7+dbt+%C2%B7+Spark;Pipelines+confi%C3%A1veis%2C+test%C3%A1veis+e+reprodut%C3%ADveis" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  Analista de Suporte Jr II na Linx/Totvs · Estudante de Sistemas de Informação na Unifafibe
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/joaoppalmda/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:joaoppalmda@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

---

## Sobre

Trabalho no dia a dia com sistemas, bancos de dados e infraestrutura, investigando a causa raiz de problemas técnicos e entregando soluções. Essa rotina me deu o olhar que levo para dados: **um pipeline só vale se for confiável quando algo dá errado.**

Estou migrando para Engenharia de Dados, construindo projetos ponta a ponta com foco em orquestração, transformação, qualidade de dados e ambientes reproduzíveis com Docker.

## Projetos

| Projeto | O que faz | Stack |
|---|---|---|
| [**etl-bcb-airflow-dbt**](https://github.com/jpalmda/etl-bcb-airflow-dbt) | Ingere SELIC, IPCA e dólar da API do Banco Central, transforma com dbt e valida com testes de qualidade. Orquestrado com Airflow. | `Python` `Airflow` `dbt` `Docker` |
| [**spark-multas-sp**](https://github.com/jpalmda/spark-multas-sp) | Processa e analisa ~1 milhão de registros reais de multas do DETRAN-SP com agregações e window functions. | `PySpark` `Parquet` `Matplotlib` |
| [**airflow-etl-dolar**](https://github.com/jpalmda/airflow-etl-dolar) | Pipeline agendado no Airflow que extrai a cotação do dólar e persiste em PostgreSQL. | `Python` `Airflow` `PostgreSQL` `Docker` |
| [**etl-cotacao-dolar**](https://github.com/jpalmda/etl-cotacao-dolar) | ETL da cotação do dólar com tratamento em Pandas e carga em PostgreSQL via Docker Compose. | `Python` `Pandas` `PostgreSQL` `Docker` |

## Stack

| | |
|---|---|
| **Linguagens** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white) |
| **Orquestração e transformação** | ![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white) ![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white) ![Spark](https://img.shields.io/badge/Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) |
| **Armazenamento** | ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white) ![Parquet](https://img.shields.io/badge/Parquet-50ABF1?style=flat-square&logo=apache&logoColor=white) |
| **Infra e ferramentas** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |

## Minha carreira como pipeline

```mermaid
flowchart LR
    A["<b>EXTRACT</b><br/>Suporte técnico<br/>sistemas, bancos e infra"] --> B["<b>TRANSFORM</b><br/>Análise de causa raiz<br/>+ projetos de dados"]
    B --> C["<b>VALIDATE</b><br/>Testes de qualidade<br/>e ambientes em Docker"]
    C --> D[("<b>LOAD</b><br/>Engenharia de Dados")]
```

Quem passa o dia investigando por que algo quebrou aprende cedo que dado ruim e sistema instável têm a mesma origem: falta de observabilidade. É essa mentalidade que levo para os pipelines.

```sql
SELECT nome, cargo_atual, formacao, foco, stack
FROM   joao.perfil
WHERE  aberto_a_oportunidades = TRUE;

-- nome         | João
-- cargo_atual  | Analista de Suporte Jr II
-- formacao     | Sistemas de Informação
-- foco         | Engenharia de Dados
-- stack        | {Python, SQL, Airflow, dbt, Spark, Docker}
```

---

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/jpalmda/jpalmda/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/jpalmda/jpalmda/output/github-contribution-grid-snake.svg" />
  <img alt="Gráfico de contribuições" src="https://raw.githubusercontent.com/jpalmda/jpalmda/output/github-contribution-grid-snake.svg" />
</picture>

<p align="center">
  Aberto a conversar sobre dados, projetos e oportunidades na área.
</p>
