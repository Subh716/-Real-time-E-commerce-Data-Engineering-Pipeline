Project: Real-time Data Engineering for E-commerce Platform

### Overview
Built a scalable and optimized data engineering pipeline on Google Cloud using Apache Spark to process and analyze large-scale e-commerce datasets. This project simulated a real-world retail data architecture involving ingestion, transformation, integration, and serving layers.

### Key Steps
1. **Exploration & Ingestion**
   - Loaded raw CSV and JSON files into HDFS using PySpark.
   - Ingested data into Google Cloud Dataproc for distributed processing.

2. **Data Cleaning & Transformation**
   - Handled missing values, type mismatches, and outliers.
   - Applied column transformations, date parsing, and schema fixes.

3. **Data Integration & Aggregation**
   - Joined datasets (customers, orders, reviews, products).
   - Used window functions to calculate metrics like RFM scores and CLTV.

4. **Performance Optimization**
   - Applied broadcast joins and caching strategies.
   - Tuned Spark configs (shuffle partitions, executor memory).

5. **Serving Layer**
   - Final curated data saved to the data lake.
   - Ready for dashboarding or BI analysis.

### Tools & Technologies
`PySpark`, `Google Cloud Dataproc`, `SQL`, `HDFS`, `Window Functions`, `ETL`, `Data Aggregation`, `Performance Tuning`

### Outcome
Improved data pipeline performance by 40% and created a robust, scalable solution capable of processing multi-source datasets for real-time retail analytics.
