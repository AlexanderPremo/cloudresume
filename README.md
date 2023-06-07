Cloud Resume Challenge
This project is my submission for the Cloud Resume Challenge. The challenge is to create a cloud-based resume website using various AWS services and infrastructure-as-code tools. The primary technologies used in this project are AWS CloudFormation, AWS SAM, Terraform, Python, AWS S3, AWS Route 53, AWS CloudFront, and AWS Lambda.

Technologies Used
AWS CloudFormation
AWS CloudFormation is a service that enables us to define and provision AWS infrastructure resources in a declarative manner. In this project, CloudFormation is used to define and deploy the AWS resources required for hosting the resume website, including the S3 bucket, Route 53 records, CloudFront distribution, and Lambda functions.

AWS SAM (Serverless Application Model)
AWS SAM is an extension of AWS CloudFormation specifically designed for serverless applications. It simplifies the deployment and management of serverless applications by providing a higher-level abstraction. In this project, AWS SAM is used to define the serverless application resources, including API Gateway endpoints and AWS Lambda functions for handling website requests.

Terraform
Terraform is an open-source infrastructure-as-code tool that allows us to provision and manage infrastructure resources across multiple cloud providers. In this project, Terraform is used to define and deploy AWS resources that are not covered by AWS CloudFormation or AWS SAM, such as IAM roles and policies.

Python
Python is a popular programming language used for various purposes, including web development. In this project, Python is used to write the Lambda function code that powers the dynamic parts of the resume website. Python frameworks like Flask or Django can be used to build the serverless API endpoints and handle website requests.

AWS S3
Amazon S3 (Simple Storage Service) is an object storage service provided by AWS. In this project, an S3 bucket is used to store the static website files, including HTML, CSS, and images. The website files are then served through AWS CloudFront for fast and reliable content delivery.

AWS Route 53
AWS Route 53 is a scalable and highly available domain name system (DNS) web service. In this project, Route 53 is used to configure the domain name for the resume website and manage the DNS records required for routing traffic to the CloudFront distribution.

AWS CloudFront
Amazon CloudFront is a fast content delivery network (CDN) service provided by AWS. It accelerates the distribution of the resume website's static files and improves the website's performance by caching content at edge locations worldwide.

AWS Lambda
AWS Lambda is a serverless compute service that allows you to run your code without provisioning or managing servers. In this project, Lambda functions are used to handle the website requests and serve dynamic content. These functions are triggered by API Gateway endpoints defined in AWS SAM.