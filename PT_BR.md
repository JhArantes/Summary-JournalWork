# 🧠 Ciclo Completo de Ciência de Dados — Jornal O+ Positivo (2022–2024)

## 🎯 Visão Geral do Projeto

Como **Cientista de Dados** no Jornal **O+ Positivo**, fui responsável por estruturar e operacionalizar todo o ciclo de vida dos dados — da coleta em campo até a entrega estratégica de insights para gestores públicos e stakeholders políticos. Esse processo foi fundamental para subsidiar a criação de políticas públicas baseadas em evidências, apoiar estratégias eleitorais e fortalecer a governança pública com inteligência territorial e populacional.

---

## 📥 1. Coleta de Dados em Campo

### 🔐 Software Proprietário do Jornal

- Desenvolvemos um **aplicativo móvel próprio** utilizado por coletores em campo, com foco em **segurança, usabilidade e validação em tempo real**.
- Cada pesquisador era equipado com um **dispositivo móvel com GPS**, coleta offline e sincronização segura com os servidores centrais.
- O app aplicava regras de validação e formatos padronizados para garantir **qualidade, integridade e confiabilidade** dos dados desde a origem.

---

## ☁️ 2. Armazenamento e Governança de Dados

### 🔸 Armazenamento em Nuvem (AWS)

- **Amazon S3**: Armazenamento de dados brutos e intermediários em formatos como JSON e CSV.
- **Amazon RDS**: Utilização de bancos relacionais (PostgreSQL, MySQL e Oracle) para dados estruturados e análises SQL.
- **AWS Lambda**: Execução de funções automáticas em resposta a eventos (ex: ingestão de novos dados).
- **AWS Backup**: Backups automáticos e versionados, com monitoramento periódico.

### 🔒 Segurança e Auditoria

- **IAM (Identity & Access Management)**: Controle fino de permissões e acesso baseado em papéis.
- **AWS KMS (Key Management Service)**: Criptografia de dados em repouso e em trânsito.
- **AWS CloudTrail**: Auditoria de todas as ações realizadas na infraestrutura de dados.

### 💽 Armazenamento Local (Complementar)

- **Oracle (PL/SQL)**: Modelagem relacional com procedures, triggers e pacotes para tratamento e enriquecimento de dados.
- **MongoDB**: Armazenamento de dados semi-estruturados (ex: respostas abertas e registros com formatos flexíveis).
- **MySQL**: Utilizado em algumas APIs internas e integrações de aplicações legadas.

---

## ⚙️ 3. Pipeline de ETL (Extração, Transformação e Carga)

- **AWS Glue**: Automatização de ETLs, criação de catálogos de dados e orquestração de transformações.
- **Apache Airflow**: Agendamento de tarefas complexas, controle de dependências e monitoramento de workflows.
- **Apache Spark (via AWS EMR)**: Processamento distribuído de grandes volumes de dados com alta performance.

---

## 📊 4. Análise de Dados e Modelagem

### 🔬 Análise Estatística e Machine Learning (Python)

- **pandas**: Estruturação e manipulação de dados tabulares.
- **numpy**: Cálculos matriciais e operações vetoriais.
- **scipy**: Análises estatísticas avançadas, testes de hipóteses e regressões.
- **statsmodels**: Modelagem clássica — séries temporais, regressões múltiplas, inferência estatística.
- **scikit-learn**: Modelos preditivos (classificação, regressão, clustering) com pipelines reutilizáveis.

### 📉 Visualização de Dados

- **matplotlib** e **seaborn**: Geração de gráficos descritivos e exploratórios.
- **plotly**: Gráficos interativos utilizados nos dashboards web e apresentações.
- **Power BI**: Construção de dashboards dinâmicos e intuitivos voltados para tomadores de decisão, com foco em:
  - Análises por município
  - Segmentação populacional e intenção de voto
  - Acompanhamento de políticas públicas
  - Riscos e oportunidades regionais

---

## 🚀 5. Entrega de Valor e Tomada de Decisão

- Todos os dados processados eram apresentados em **dashboards interativos no Power BI**, permitindo a visualização de padrões e tendências críticas.
- Realizamos **briefings estratégicos** com gestores municipais, vereadores e candidatos, explicando os **insights com linguagem acessível e orientada à ação**.
- Os modelos preditivos auxiliaram na **antecipação de rejeição de políticas públicas**, **alocação de recursos** e **planejamento de campanhas eleitorais** com base em dados concretos.

---

## 🧰 Ferramentas Complementares e Cultura Dev

| Categoria             | Ferramentas Utilizadas                             |
|-----------------------|----------------------------------------------------|
| Notebooks             | Jupyter Notebooks                                  |
| Gestão de Projetos    | Trello, Notion                                     |
| Versionamento         | Git + GitHub                                       |
| Ambientes             | Docker, VS Code, PyCharm                           |
| Documentação Técnica  | Notion + README interativos                        |

---

## 📤 Entregas Estratégicas para Stakeholders

> “Dados são o novo petróleo — mas só quando refinados.”

- **Dashboards de alto impacto** desenvolvidos no Power BI, com visão municipal, regional e temática.
- Relatórios preditivos sobre **aceitação de políticas públicas** e análise de **sentimentos populacionais**.
- Painéis de controle personalizados para **prefeitos, secretários e assessores políticos**.
- Briefings com recomendações práticas extraídas de modelagem estatística e machine learning.
- Acesso interativo e responsivo para análises em tempo real, em ambiente seguro e escalável na AWS.

---

## 📊 Resultados Concretos

✅ **Redução de 30% no tempo de tomada de decisão** por secretarias municipais  
✅ **Previsibilidade de 70% em ações de políticas públicas** com base em dados reais  
✅ **Cobertura de +60 municípios**, com +7.000 cidadãos entrevistados presencialmente  
✅ **Adoção de dados como pilar estratégico** em 4 campanhas eleitorais municipais  
✅ Consolidação de **governança de dados** no nível local com foco em ética e transparência

---

## ⚙️ Tecnologias e Stack

<div style="display: flex; flex-wrap: wrap; gap: 10px;">

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="Python"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/oracle/oracle-original.svg" height="40" alt="Oracle"/>
<img height="44" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" />
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" height="40" alt="MySQL"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mongodb/mongodb-original.svg" height="40" alt="MongoDB"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" height="40" alt="Docker"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" height="40" alt="GitHub"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg" height="40" alt="Jupyter"/>
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/trello/trello-plain.svg" height="40" alt="Trello"/>

</div>

**Ferramentas Complementares:**
- 🔸 AWS Glue · Lambda · S3 · RDS · Backup · IAM · CloudTrail
- 🔸 Apache Airflow · Apache Spark via EMR
- 🔸 Python: `pandas`, `scikit-learn`, `statsmodels`, `matplotlib`, `plotly`, `seaborn`
- 🔸 Power BI para dashboards e relatórios dinâmicos
- 🔸 Notion, Trello, VS Code, Git & Docker para organização e CI/CD

---

## 🌍 Localização Estratégica

📍 **Goiás, Brasil**  
🛰️ Atendimento de municípios em toda a **região Centro-Oeste**
🔁 Atuação híbrida 

---

## 📬 Contato Profissional

👤 **João Henrique Arantes**  
🎓 Cientista de Dados | Futuro Engenheiro de Dados  
📧 joaoharv@email.com  
🔗 [linkedin.com/in/joaoharv](https://www.linkedin.com/in/joaoharv)  

---

> “Transformar dados em inteligência é transformar realidades.”