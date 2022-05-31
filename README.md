# AWS Services

### Analytics:
- **Amazon Athena**
    - interactive query service that makes it easy to analyze data in Amazon S3 using standard SQL
    - serverless, so there is no infrastructure to manage, and you pay only for the queries that you run
    - Athena is out-of-the-box integrated with AWS Glue Data Catalog, allowing you to create a unified metadata repository across various services, crawl data sources to discover schemas and populate your Catalog with new and modified table and partition definitions, and maintain schema versioning.
- **Amazon Elasticsearch Service (Amazon ES)**
    - Amazon OpenSearch Service makes it easy for you to perform interactive log analytics, real-time application monitoring, website search, and more
    - OpenSearch is an open source, distributed search and analytics suite derived from Elasticsearch.
    - Amazon OpenSearch Service is the successor to Amazon Elasticsearch Service, and offers the latest versions of OpenSearch, support for 19 versions of Elasticsearch (1.5 to 7.10 versions), as well as visualization capabilities powered by OpenSearch Dashboards and Kibana (1.5 to 7.10 versions).
- **Amazon EMR**
    - Amazon EMR (previously called Amazon Elastic MapReduce) is a cloud big data platform for running large-scale distributed data processing jobs, interactive SQL queries, and machine learning (ML) applications using open-source analytics frameworks such as Apache Spark, Apache Hive, and Presto.
    - Amazon EMR is a web service that makes it easy to process vast amounts of data efficiently using Apache Hadoop and services offered by Amazon Web Services.
- **AWS Glue**
    - AWS Glue is a fully managed ETL (extract, transform, and load) service that makes it simple and cost-effective to categorize your data, clean it, enrich it, and move it reliably between various data stores and data streams. 
    - AWS Glue consists of a central metadata repository known as the AWS Glue Data Catalog, an ETL engine that automatically generates Python or Scala code, and a flexible scheduler that handles dependency resolution, job monitoring, and retries. 
    - AWS Glue is serverless, so there’s no infrastructure to set up or manage.
    - You can use AWS Glue to organize, cleanse, validate, and format data for storage in a data warehouse or data lake.
- **Amazon Kinesis**
    - Amazon Kinesis makes it easy to collect, process, and analyze video and data streams in real time.
- **Amazon QuickSight**
    - Amazon QuickSight is a cloud-scale business intelligence (BI) service that you can use to deliver easy-to-understand insights to the people who you work with, wherever they are.
    - Amazon QuickSight connects to your data in the cloud and combines data from many different sources
    - In a single data dashboard, QuickSight can include AWS data, third-party data, big data, spreadsheet data, SaaS data, B2B data, and more. As a fully managed cloud-based service, Amazon QuickSight provides enterprise-grade security, global availability, and built-in redundancy.
    - It also provides the user-management tools that you need to scale from 10 users to 10,000, all with no infrastructure to deploy or manage.
### AWS Billing and Cost Management:
- AWS Budgets
- Cost Explorer
### Application Integration:
- Amazon Simple Notification Service (Amazon SNS)
- Amazon Simple Queue Service (Amazon SQS)

### Compute:
- Amazon EC2
- AWS Elastic Beanstalk
- Amazon Elastic Container Service (Amazon ECS)
- Amazon Elastic Kubernetes Service (Amazon EKS)
- Elastic Load Balancing
- AWS Fargate
- AWS Lambda
### Database:
- Amazon Aurora
- Amazon DynamoDB
- Amazon ElastiCache
- Amazon RDS
- Amazon Redshift
### Management and Governance:
- AWS Auto Scaling
- AWS Backup
- AWS CloudFormation
- AWS CloudTrail
- Amazon CloudWatch
- AWS Config
- Amazon EventBridge (Amazon CloudWatch Events)
- AWS Organizations
- AWS Resource Access Manager
- AWS Systems Manager
- AWS Trusted Advisor
Migration and Transfer:
- AWS Database Migration Service (AWS DMS)
- AWS DataSync
- AWS Migration Hub
- AWS Server Migration Service (AWS SMS)
- AWS Snowball
- AWS Transfer Family
Networking and Content Delivery:
- Amazon API Gateway
- Amazon CloudFront
- AWS Direct Connect
- AWS Global Accelerator
- Amazon Route 53
- AWS Transit Gateway
- Amazon VPC (and associated features)

### Security, Identity, and Compliance:
- AWS Certificate Manager (ACM)
- AWS Directory Service
- Amazon GuardDuty
- AWS Identity and Access Management (IAM)
- Amazon Inspector
- AWS Key Management Service (AWS KMS)
- Amazon Macie
- AWS Secrets Manager
- AWS Shield
- AWS Single Sign-On
- AWS WAF
### Storage:
- Amazon Elastic Block Store (Amazon EBS)
- Amazon Elastic File System (Amazon EFS)
- Amazon FSx
- Amazon S3
- Amazon S3 Glacier
- AWS Storage Gateway
