# Kevin Lin

**Aspiring Backend Engineer | Data Engineering Background**
(準後端工程師 | 具備資料工程實戰經驗)

I have a background in **Finance & Law**, which trained me to prioritize rigorous logic and business efficiency. After independently building high-throughput data pipelines with **Python** on GCP, I discovered my passion for system architecture.

Currently, I am leveraging these engineering principles—such as Containerization, Cloud Infrastructure, and Database Design—to transition into enterprise backend development.

我是 Kevin，擁有金融與法律背景。在獨立建構雲端資料管線的過程中，確立了對系統架構的熱情。目前正將在高流量系統的實戰經驗（Docker, GCP, ETL），轉化為後端開發能力。

---

## Featured Projects

### 1. YouBike Traffic Prediction System
**Solo Project** | *System Architecture, ETL, & Backend AI Integration*
(全端資料工程與流量預測系統)

> Designed and deployed an end-to-end system on GCP to address the "supply-demand mismatch" in urban bike-sharing networks, processing over 4 million records.

**Infrastructure & Stability**
* Built a containerized environment on **GCP Compute Engine** using **Docker Compose**.
* Orchestrated **Airflow** workflows with a **10-minute micro-batch strategy** and auto-retry mechanisms, ensuring high availability for continuous data ingestion.

**Statistical & AI Analysis**
* Validated "resource misallocation" (CV=0.78 during peak hours) as the root cause using **ANOVA & T-tests**, moving beyond simple shortage assumptions.
* Developed a **Multi-Station LSTM model** with **Entity Embeddings** to capture spatial dependencies, achieving an MSE Loss of 0.0071.
* Deployed the model via **FastAPI** to serve real-time predictions.

### 2. Carbon Footprint Calculator
**Core Contributor** | *High-Performance Crawling & Data Cleaning*
(食譜碳排計算引擎)

> Engineered the data ingestion layer for a carbon footprint analysis platform, solving complex unstructured data challenges.

**Performance Optimization**
* Developed an asynchronous spider using **Scrapy**, achieving a **10x speedup** compared to synchronous Selenium crawlers for processing 10,000+ recipes.

**AI-Driven Pipeline**
* Designed a "Lookup First, Ask AI Later" strategy: combining a local dictionary with **Google Gemini API** to normalize ambiguous units (e.g., "1 spoon" → "15g") efficiently.
* Implemented **Fuzzy Matching algorithms** (difflib) to map heterogeneous data sources across Recipe and Carbon Emission databases.

---

## Technical Skills

* **Current Focus:** Java (Spring Boot), RESTful APIs, OOP Principles
* **Proficient In:** Python, Apache Airflow, ETL Pipelines, Scrapy
* **Infrastructure:** GCP (Compute Engine), Docker, Docker Compose, Linux, Git
* **Data Science:** PyTorch (LSTM), Pandas, Statistical Analysis

---

## About Me

* **Why Engineering?** I enjoy the structure of code and the satisfaction of solving real-world problems. My legal training helps me write clean, compliant logic, while my finance background keeps me focused on efficiency.
* **Goal:** To join a backend team where I can contribute my cloud/data expertise while growing into a senior Java developer.
