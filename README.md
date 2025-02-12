# AWS Serverless Web Application 🚀  
<img width="990" alt="three-tier-arch" src="https://github.com/user-attachments/assets/8ada5e38-619a-4b54-adef-3c1b9cffc4fd" />
This project sets up a fully serverless web application using AWS services, including S3, CloudFront, API Gateway, Lambda, and DynamoDB.  

---

## 📌 Features  
- 🪣 **S3** – Stores static website files  
- 🌎 **CloudFront** – Distributes content globally  
- 🔑 **IAM** – Manages permissions for security  
- ⚙️ **Lambda** – Handles backend logic  
- 🚪 **API Gateway** – Routes API requests  
- 💾 **DynamoDB** – Stores user data  
- 📝 **Testing** – Ensures API functionality  
- 🔐 **Security** – Implements permissions for resources  

---
## 🚀 Setup Instructions  
### 1️⃣ Deploy Website Storage (S3)  
- Create an S3 bucket  
- Enable static website hosting  
- Upload website files  

### 2️⃣ Configure Global Distribution (CloudFront)  
- Set up a CloudFront distribution  
- Link it to the S3 bucket  

### 3️⃣ Build Backend Logic (Lambda & API Gateway)  
- Create a Lambda function  
- Set up an API Gateway  
- Connect API Gateway to Lambda  

### 4️⃣ Store & Secure Data (DynamoDB)  
- Create a DynamoDB table  
- Grant Lambda access to read/write data  

### 5️⃣ Secure the Infrastructure  
- Apply IAM policies for security  
- Restrict access to sensitive resources  

---

## 📊 Hosting Methods Comparison  
| Method        | Pros | Cons |
|--------------|------|------|
| S3 + CloudFront | Fast, scalable | No server-side processing |
| Lambda + API Gateway | Serverless, low-cost | Cold start latency |
| EC2 | Full control | Higher maintenance |

---

## 🛠️ Technologies Used  
- **AWS S3** – Static file hosting  
- **AWS CloudFront** – Content delivery  
- **AWS Lambda** – Serverless backend  
- **AWS API Gateway** – API management  
- **AWS DynamoDB** – NoSQL database  
- **AWS IAM** – Security and permissions  

---

## 🔗 Resources  
- [AWS S3 Documentation](https://docs.aws.amazon.com/s3/index.html)  
- [AWS CloudFront Documentation](https://docs.aws.amazon.com/cloudfront/index.html)  
- [AWS Lambda Documentation](https://docs.aws.amazon.com/lambda/index.html)  
- [AWS API Gateway Documentation](https://docs.aws.amazon.com/apigateway/index.html)
- [AWS DynamoDB Documentation](https://docs.aws.amazon.com/dynamodb/index.html)  
