# BigQuery-U.S.-Consumer-Complaints-2026
Within GCP BigQuery, I've Extracted a sample dataset from the Consumer Financial Protection Bureau and the Consumer Complaint Database. Utilized Data Manipulation, Data Validation, and performed this project to display ETL data pipeline through a cloud-based, Hyperscaler SQL Analytics AI platform

#Description
This is a sample batch dataset from the CFPB and the Consumer Complaint Database. This dataset is for anyone trying to understand the relational aspects of submission type, products, and issues (facts tables) affect dates received and resolved attributes (dimension tables). Utilizing BigQuery, we've extracted the data from consumerfinance.gov. Once extracted and loaded into a CSV file, we created a U.S. Consumer Complaint Dataset, and then a U.S. Consumer Complaint DataFrame to represent the sameple batch data for processing. 

#The SQL Query to process this table data is displayed down below: 

SELECT *
FROM `us-consumer-finance-complaints.US_Consumer_Compliants_Finance.US
Consumer Complaints`
LIMIT 14


#Installation
Steps to get the project running locally:

curl https://sdk.cloud.google.com | bash
exec -l $SHELL


