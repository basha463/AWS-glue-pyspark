# AWS-glue-pyspark-ETL pipeline 
This project is a serverless data processing pipeline that transforms raw music streaming data into actionable business insights.
It ingests artist, album, and track data from multiple sources, processes it through AWS Glue ETL jobs, and delivers real-time analytics and interactive dashboards via Amazon Athena and Amazon QuickSight.

🗝️ Key Features
✅ Automated ETL

Fully serverless data transformation using AWS Glue jobs and triggers.

✅ Scalable Storage

Amazon S3-based data lake with clearly defined staging and processed data layers.

✅ Real-time Analytics

Perform ad-hoc SQL queries on processed data using Amazon Athena.

✅ Interactive Dashboards

Visualize streaming metrics, artist performance, and album trends in Amazon QuickSight.

✅ Schema Management

Automated schema discovery and catalog updates using AWS Glue Crawlers.

![Screenshot 2025-06-27 103209](https://github.com/user-attachments/assets/5133a000-30b4-49db-9423-1b931393f9f8)
![Screenshot 2025-06-27 110838](https://github.com/user-attachments/assets/0a3ce44d-c7e0-462d-ac4c-57d09e364e36)
![Screenshot 2025-06-27 111255](https://github.com/user-attachments/assets/61d5f492-95da-473f-91d9-086d3f39991d)



![Screenshot 2025-07-03 104209](https://github.com/user-attachments/assets/a2d5cbdb-60d4-45c3-b808-e9aa29158733)

Deployment Steps
Set up the S3 Data Lake

Create staging/ and processed/ buckets.

Configure AWS Glue Crawlers

Point them to the S3 staging bucket to populate the Glue Data Catalog.

Create and Schedule AWS Glue ETL Jobs

Define transformations to clean and enrich the raw data.

Run Queries with Athena

Connect Athena to the Glue Data Catalog and run SQL for ad-hoc analysis.

Visualize with QuickSight

Connect QuickSight to Athena and build interactive dashboards.



