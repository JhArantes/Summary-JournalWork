# 📰 Data Science Project — Jornal O+ Positivo (2022–2024)

## 👨‍💼 About the Project

I worked as a **Data Scientist** at *Jornal O+ Positivo*, leading initiatives in data modeling, governance, and strategic analysis to support **public policy decisions and electoral strategies** in the Central-West region of Brazil, particularly in **municipalities of Goiás**.

> 🎯 **Mission**: Convert raw and decentralized data into **actionable strategic insights**, supporting public officials, political analysts, and electoral campaigns.

---

## ☁️ Part 1 — Data Storage Infrastructure

### 🔹 AWS Cloud

We chose **Amazon Web Services (AWS)** for its **scalability, security, flexibility**, and native integration with data pipelines. Key services used:

| AWS Service       | Role in the Project                                               |
|-------------------|-------------------------------------------------------------------|
| Amazon S3         | Storage of raw and intermediate data (JSON, CSV)                 |
| AWS Glue          | Data cataloging and automated ETL job orchestration              |
| Amazon RDS        | Relational storage for structured and cleaned data               |
| AWS Lambda        | Event-triggered automation tasks                                 |
| AWS Backup        | Scheduled, versioned backups                                      |

#### 📌 Why Cloud?

- **Hybrid accessibility** for remote and on-site work
- **Secure versioned backup**
- **Cost efficiency**
- **Smooth ETL integration**

---

### 🔹 Oracle SQL

We used **Oracle Database with PL/SQL** for robust data structuring and transactional modeling. Reasons include:

- **High performance and reliability**
- **Advanced procedures and data integrity**
- **Robust data governance with constraints and triggers**
- **Seamless BI tool compatibility**

---

## 📊 Part 2 — Analysis and Visualization

### 🔹 Tools Used

| Tool               | Project Use Case                                                 |
|--------------------|------------------------------------------------------------------|
| Python (Pandas, NumPy, Scikit-Learn) | Data wrangling, exploratory analysis, predictive modeling   |
| Power BI           | Interactive dashboards for political stakeholders               |
| Jupyter Notebooks  | Technical reporting with interpretable code and visual output   |
| Trello             | Agile project management for task alignment with stakeholders   |

### 🔹 Key Analytical Outcomes

- Population and electoral profile segmentation
- Regional trend analysis on public opinion
- Classifiers to predict voting intention
- Time series forecasting on public engagement metrics

---

## 🔁 Full ETL Pipeline Overview

### 🔍 1. Data Collection

- **Field researchers** conducted in-person interviews and data gathering using tools like Google Forms and KoboToolbox.
- Real-time data synced to **Google Sheets**.

### ☁️ 2. Cloud Ingestion

- Automated Python scripts (with `pandas` + `gspread`) fetched and uploaded data to **Amazon S3**.
- Versioned storage and event triggers using AWS Lambda.

### 🛠️ 3. Cleaning & Processing

- Data transformation handled by **AWS Glue**.
- Validated and enriched data moved to **Oracle RDS** using custom PL/SQL procedures.
- Temporary audit logs maintained for transparency.

### 📈 4. Analysis & Visualization

- Analytical models and statistical insights built using Python in Jupyter.
- Dashboards generated in Power BI, focusing on:
  - Municipality-level metrics
  - Public sentiment clusters
  - Policy acceptance forecasts

### 📤 5. Delivery to Stakeholders

- Visual dashboards shared with mayors, secretaries, and political advisors.
- Strategic briefings with insights and recommended actions.
- Interactive sessions with stakeholders to explore data-driven policies.

---

## 💥 Results

- Achieved **70% accuracy** in public policy acceptance forecasts
- **30% reduction in decision-making time** for municipal departments
- Enabled **strategic alignment** between population data and campaign targets
- Supported **territory-based intelligence** for electoral strategies

---

## 👨‍🔧 Technologies & Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![PL/SQL](https://img.shields.io/badge/PL%2FSQL-306998?style=for-the-badge)
![Trello](https://img.shields.io/badge/Trello-0052CC?style=for-the-badge&logo=trello&logoColor=white)

---

## 📍 Location

📍 **Goiânia, Goiás — Brazil**  
🔄 **Hybrid Work Model** (field + remote)

---

## 📫 Contact

For more information or to discuss data-driven public policy applications:

**João Henrique Arantes**  
📧 [joaoharv@email.com]  
🔗 [linkedin.com/in/joaoharv](https://www.linkedin.com/in/joaoharv/)
