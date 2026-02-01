# Portfolio
## Skills
- **Programming Languages**: Python, SQL, Java, JavaScript
- **Machine Learning**: Pandas, NumPy, Scikit-learn, Matplotlib, SciPy, Keras, TensorFlow, PyTorch, OpenCV
- **Other**: PowerBI, MS-Excel (Power Query, Pivot-table), Alteryx, Apache Airflow, MySQL, DBeaver, Firebase, MongoDB, PostgreSQL, N8N, dbt, HTML, CSS, 
React, Tailwind, Docker, Git, FastAPI, Spring Boot, Microsoft Fabric (Data flow, Pipeline, Lakehouse, Notebook)

## Work Experience
### Internship Trainee at Bangchak Corporation Public Company Limited
Jun 2025 - Nov 2025 (6 months)
I was responsible in 3 in-house projects in the Department of Accounting and Finance.

Accomplishments:

- **Designed and developed a Power BI dashboard** to monitor employee expense reimbursements.
- Prevent financial leakage, such as reusing invoices, slightly altering invoice numbers and human entry errors which traditional rules failed to catch. 
- Built an end-to-end pipeline using Microsoft Fabric (Dataflows, Pipeline, Lakehouse, Notebook) and implemented Fuzzy Logic algorithms to score similarity between records, detecting patterns of manipulation and typo errors before visualizing suspicious cases on Power BI dashboard. 
- Delivered Fraud Detection & Audit System which can successfully identify potential fraud cases and erroneous claims for accountants. 
- **Developed a Financial Assistant Chatbot using the N8N workflow automation platform** to answer questions about financial reports. 
- Eliminated the technical bottleneck of CFO and CFA which are required to manually write SQL queries or filter on MS-Excel just to retrieve specific financial figures. 
- Experimented with Hybrid Retrieval-Augmented Generation (Hybrid RAG) approach, combining Qdrant Vector Store and SQL querying technique retrieved from PostgreSQL database. 
- Achieved 78% accuracy in response reliability through manual qualitative assessment (Human-in-the-loop) of LLM outputs. 
- Developed a **Python-based desktop application to extract multi-format invoice PDFs into structured data**. 
- Replaced manual data entry process where accountants had to visually read invoices and type data into specific Excel columns for SAP ingestion and eliminate the dependency on a third-party vendor, which required a 24-hour waiting period for results and posed potential data privacy risks. 
- Integrated open-source Large Language Model (Typhoon) with OCR capabilities to accurately parse multi-format PDFs and convert unstructured content 
into SAP-ready tabular formats. 
- **Reduced data processing turnaround time from 1 day to under 30 minutes** while ensuring sensitive financial data remains secure internally.

### Intern Data Scientist Fresh Commerce (Talaadthai Online)
Jun 2024 - Jul 2024 (2 months)
- **Developed a Time-series model to forecast Gross Merchandise Value (GMV) using CRISP-DM methodology**. 
- Addressed revenue uncertainty and support strategic marketing planning, enabling the business to allocate resources effectively based on predicted sales trends. 
- Experimented multiple forecasting algorithms, such as Linear Regression, ARIMA, and LSTM (TensorFlow), to predict Gross Merchandise Value (GMV). 
- Achieved a 19.24% MAPE with the Linear Regression.

## Projects
### Senior Project – RainCast - Predicting Rainfall with Data-Driven Models
- Proposed a deep learning model for short-term rainfall nowcasting (0-30 mins) using Himawari-8 satellite imagery and radar data and an architecture 
combining ConvLSTM and U-Net for semantic segmentation to classify rainfall intensity into 4 levels (Non-rain, Light, Moderate, Heavy).

#### Tools and Technologies
- Deep Learning Framework: Pytorch
- Architecture: LSTM, U-Net

![senior_method](/assets/senior_method.png)

### Practical Data Science Project - Analysis of International Classification of Diseases (ICD) Codes Between Emergency Department and Inpatient Department
- Conducted statistical analysis on the MIMIC-IV dataset (2008-2019) to evaluate diagnostic coding discrepancies between Emergency department and 
Inpatient department using Chi-Square tests and Cramer’s V as effect size measurement. 
- Implemented data mining with Association Rule Mining technique (Apriori and FP-Growth) to discover hidden diagnostic patterns and correlations across 
hospital departments. 
- Proposed a novel "Interestingness Score" to identify clinically significant cross-departmental diagnostic trajectories, validated by medical literature.
#### Tools and Technologies
- Data Preparation: Pandas
- Data Mining: Apriori, FP-Growth
- Visualization: Matplotlib

![icd_method](/assets/icd_method.png)

### Data Engineering and Infrastructure Project
This project is a part of third year Data Engineer course in the Faculty of Information and Communication at Mahidol university. The objective is to optimize energy usage in the Faculty of Information and Communication Technology(MUICT) building. We use data collected from three sources including: the MUICT building room reservation API, MUICT IoT sensors, and the TMD Weather API. We also use ETL as data integration process.
- Built an end-to-end ETL Data Pipeline for a Smart Building Energy Optimization System to monitor and analyze utility usage at the MUICT faculty. 
- Addressed inefficiencies in building energy consumption by correlating diverse datasets, room reservation schedules, IoT sensor readings, and real-time 
TMD weather data for precise usage optimization.
- Orchestrated the workflow using Apache Airflow within Docker, performing raw data extraction via Python and loading it into PostgreSQL and implemented 
dbt for data transformation using the Medallion Architecture (Bronze, Silver, Gold) to ensure data quality.
- Established a comprehensive monitoring ecosystem with Power BI dashboards and LINE Notify real-time alerts, enabling facility staff to identify anomalies and potentially reduce energy waste.

#### Tools and Technologies
- DBT: Handles data transformation and modeling using Medallion Architecture (Bronze, Silver and Gold)
- Airflow: Orchestrates ELT workflow
- PostgreSQL: Stores data as Data Lake and Data Warehouse
- Docker: Container service
- Python: Conducts Data extraction, Airflow script and Line Notify for alert system
- Power BI: Visualizes data for monitoring

![de_workflow](/assets/de.png)
