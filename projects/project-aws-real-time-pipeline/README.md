
# Real-Time Data Pipeline — AWS

**Goal:** Build a serverless pipeline to process real-time data and load it into Redshift for analytics.  
**Tools:** AWS Lambda, Kinesis, Glue (PySpark), Redshift, CloudWatch

## What I Did
- Used AWS Lambda and Kinesis to capture streaming data events.
- ETL job in AWS Glue (PySpark) to transform JSON → Parquet.
- Loaded data into Redshift tables for reporting.
- Used CloudWatch for monitoring pipeline latency and errors.

## Architecture
Lambda → Kinesis → S3 → Glue → Redshift → QuickSight  

## Results
✅ Reduced data ingestion latency by 80%  
✅ Automated error monitoring and alerts  
✅ Scalable design for 100K+ daily events
