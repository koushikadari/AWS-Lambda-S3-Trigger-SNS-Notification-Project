# AWS-Lambda-S3-Trigger-SNS-Notification-Project

🚀 AWS Lambda | S3 Trigger | SNS Notification Project
I recently completed a hands-on project on AWS using the following services: Lambda, S3, and SNS.

🔹 Objective: Automate email notifications whenever a file is uploaded to an S3 bucket.
🔹 Setup:

Created an AWS Lambda function (my-first) triggered by S3 events (ObjectCreated:Put).

Integrated the Lambda with SNS (Simple Notification Service) to send email alerts.

Whenever a new file is uploaded to the specified S3 bucket, the Lambda function gets invoked and sends a message through an SNS topic to my email.

✅ Outcome: Successfully received real-time email notifications with object details like filename, size, and timestamp.

🧰 Skills Applied:

AWS Lambda (Python)

Amazon S3 event triggers

Amazon SNS for email notifications

IAM permissions and role-based access

Event-driven serverless architecture

🔗 This project helped me understand how to connect AWS services to create real-time workflows without provisioning servers.
