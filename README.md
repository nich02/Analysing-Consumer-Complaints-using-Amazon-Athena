# Analysing-Consumer-Complaints-using-Amazon-Athena

## Business Use Case (Situation)
In this project I case of a customer support working in a multinational company which offer services to different states and countries. To improve customer engagements, enhance consumer trust and minimize customer churn, the head of data analytics asks me to perform SQL Query analysis on consumer_complaints data archived in Amazon S3. 

In the project I assumed the role of a Data Scientist, Business Intelligence Analyst or even a Data Analyst. The business question was to answer 6 questions using Amazon Athena query editor using the US_consumer_complaints data which is available at Kaggle. 

## Task (What I did)
I decided to perform few SQL Queries in Amazon Athena query editor. The first step was to load data from Amazon S3 to Athena for querying. The process involved use of Amazon Glue (which is an ETL tool for data transfer). With Amazon Glue I was able to load US_consumer_complaints data from S3 to Amazon Athena for analysis. 

Data Architecture (Data flow)







![image](https://user-images.githubusercontent.com/29160965/123593604-5ea99c80-d7f7-11eb-938a-f2550f4d5d4f.png)








## Results of Analysis 

The analysis of the data helped me to extract sensible insights for business decisions within a short period of time. Athena allowed me to run complex and sophisticated querries to extract data insights in resonably short period of time. I liked the amazing performance improvement in system performance when compared to my personal computer. 
Using Athena helped me to improve resiliency and business continuity. 

Generaly, Amazon Athena is an interactive query service that makes it easy to analyze data in Amazon S3 using standard SQL. It's a serverless service, and easy to use. I used Amazon Glue to an ETL tool to crawl data from Amazon S3 to Athena for analysis. I was able to point to my data in Amazon S3, define the schema, and start querying using standard SQL. Results were delivered within seconds. Amazon Glue reduced the complex ETL jobs while preparing the data for analysis. Such capability made it easy to quickly analyze large-scale consumer complaints dataset.

