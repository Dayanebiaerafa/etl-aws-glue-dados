# Engenharia de Analytics: Implementando um Pipeline ETL com AWS Glue

## 📖 Storytelling
Este repositório faz parte do aprendizado para o cargo de **Engenheiro(a) de Analytics Júnior**. Durante o estudo, o **Head de Dados** disponibilizou três bases de dados, e o objetivo é utilizar serviços da **AWS** para analisá-los, gerando relatórios e dashboards.

O foco principal está na **ingestão de dados** e no processo de **ETL (Extração, Transformação e Carga)**, criando as camadas **bronze** e **silver**:

- **Camada Bronze**: Armazena os dados brutos, exatamente como foram recebidos.
- **Camada Silver**: Contém os dados tratados e refinados conforme os requisitos do Head de Dados.

## 📂 Base de Dados
Os arquivos disponibilizados para análise são:

- `vendas_dados_bronze.parquet`
- `estoques_dados_bronze.parquet`
- `redes_sociais_dados_bronze.parquet`

## 🎯 Objetivo
O aprendizado visa a criação de um **pipeline de ETL com AWS Glue**, desde a ingestão dos dados via **Amazon S3** até a organização desses dados em tabelas otimizadas para consultas no **AWS Athena** e geração de relatórios no **AWS QuickSight**.

O pipeline envolve as seguintes etapas:

1. **Upload** de dados em buckets **S3**
2. **Criação das camadas** bronze (dados brutos) e silver (dados transformados)
3. **Configuração do banco de dados e tabelas** no **AWS Glue Data Catalog**
4. **Construção do pipeline de ETL** com **AWS Glue Studio**
5. **Execução de consultas ad-hoc** no **AWS Athena**

## 🛠 Tech Stack
- **Amazon S3**
- **AWS Glue Crawler**
- **AWS Glue Data Catalog**
- **AWS Glue ETL Job (Studio)**
- **AWS Glue Data Quality**
- **Python**
- **Apache Spark**
- **Athena**
- **SQL**
- **Budgets**

## ⚠️ Alerta Importante
Dado que os serviços da AWS podem gerar **custos**, é fundamental **monitorar e otimizar os gastos**. Para isso, é recomendado seguir **práticas de FinOps**, garantindo um equilíbrio entre **eficiência e controle financeiro** durante o desenvolvimento do projeto.

---
📌 *Este repositório faz parte de um aprendizado prático e pode ser atualizado conforme novas necessidades surgirem.*

<p>
    <img 
      align=left 
      margin=10 
      width=80 
      src="![WhatsApp Image 2023-01-31 at 10 52 47 (1)](https://github.com/user-attachments/assets/430109f9-1127-4cf3-a823-c29d32ecea76)"
    />
    <p>&nbsp&nbsp&nbspDayane Teodoro<br>
    &nbsp&nbsp&nbsp
    <a href="https://github.com/Dayanebiaerafa">
    GitHub</a>&nbsp;|&nbsp;
    <a href="https://www.linkedin.com/in/dayaneteodoro/
felipe-exe">LinkedIn</a>
&nbsp;|&nbsp;
    <a href="https://www.instagram.com/dayane_cie/">
    Instagram</a>
&nbsp;|&nbsp;</p>
</p>
<br/><br/>
<p>


💞 Feito com amor por Dayane Teodoro⁉ 
