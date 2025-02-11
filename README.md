# 📌 Serverless API & Web Hosting with AWS
Overview

This project demonstrates how to build and deploy a serverless API and host a static website using AWS services. It leverages AWS Lambda, API Gateway, DynamoDB, S3, and CloudFront to create a fully serverless web application.

The goal of this project is to showcase cloud architecture skills by setting up a scalable, cost-efficient web application that can handle API requests, store user data, and serve static content globally.

Features

Serverless API: Built with AWS Lambda and API Gateway to handle user requests.

Database Integration: Uses DynamoDB to store and retrieve user data.

Static Website Hosting: Hosted on S3 with global distribution via CloudFront.

Security & IAM: Implements IAM roles and policies to secure API and database access.

Scalability & Performance: Utilizes AWS services for automatic scaling and global content delivery.

JSON API Responses: Provides structured API responses for easy integration.

CI/CD Ready: Can be extended with AWS CodePipeline for continuous deployment.

🚀 How to Deploy
1️⃣ Clone the GitHub Repo
sh
Copy
Edit
git clone https://github.com/yourusername/aws-serverless-project.git
cd aws-serverless-project
2️⃣ Deploy the Lambda Function
sh
Copy
Edit
aws lambda create-function --function-name MyFunction \
--runtime python3.8 \
--role arn:aws:iam::123456789012:role/MyLambdaRole \
--handler lambda_function.lambda_handler \
--zip-file fileb://function.zip
