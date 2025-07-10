# 📁 Serverless Notification System using AWS Lambda and SNS

## ✅ Overview
This project demonstrates a **serverless event-driven notification system** using AWS Lambda and Amazon SNS. The system sends **automated email alerts** by publishing messages to an SNS topic, triggered directly through AWS Lambda.

---

## 🧱 Architecture

- **AWS SNS**: Topic created for sending notifications
- **Email Subscription**: User confirmed email subscription to the topic
- **AWS Lambda**: Python function written using Boto3 to publish messages
- **IAM Role**: Custom IAM role with SNS publish permissions
- **Trigger**: Lambda manually triggered to simulate automation

---

## 🖥️ Tech Stack & Tools
- AWS Lambda
- Amazon SNS
- IAM Roles & Policies
- Python (Boto3)
- Git + GitHub

---

## 📸 Screenshots Included
1. SNS Topic
2. Email Subscription (Confirmed)
3. Lambda Function Code
4. Lambda Test Execution
5. IAM Role with Policy
6. Email Notification Received

---

## 🔑 Key Learnings
- Serverless Architecture using AWS
- SNS Topic and Email Subscription setup
- IAM role creation and permission control
- Lambda to SNS integration via Python (Boto3)
- End-to-end testing of a notification workflow

---

## 📂 Project Status
✅ Completed and fully tested  
📧 Email alerts delivered successfully via SNS

---

## 📎 How to Use
1. Create an SNS topic and subscribe an email (confirm it)
2. Create a Lambda function and assign an IAM role with SNS publish permissions
3. Add Python code using Boto3 to publish to the topic
4. Test trigger the Lambda and check email

---

> 💡 This project is ideal for those starting with **AWS event-driven services** and understanding **serverless notification systems**.

---

## 👨‍💻 Author

**Chetan Likhitkar**  
[GitHub](https://github.com/LikhitkarChetan) | [LinkedIn](https://www.linkedin.com/in/likhitkarchetan)
