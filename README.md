✅ Overview
This solution leverages AWS Lambda for event-driven monitoring, ensuring continuous surveillance of AWS resources. When an anomaly is detected, it triggers AWS SES to send email notifications and AWS SNS to broadcast alerts via multiple channels like SMS and push notifications.

🚀 Key Features
🔹 Event-Driven Monitoring: AWS Lambda automatically triggers based on defined events.
🔹 Customizable Email Alerts: AWS SES sends detailed alerts to stakeholders.
🔹 Multi-Channel Notifications: AWS SNS allows alerts via SMS, push notifications, and HTTP endpoints.
🔹 Scalable & Serverless: Fully managed AWS services ensure efficiency and scalability.

🔧 Architecture & Workflow
1️⃣ AWS Lambda monitors predefined metrics or events.
2️⃣ On detecting anomalies, Lambda invokes SES to send email alerts.
3️⃣ SNS broadcasts alerts via multiple communication channels.

📌 Prerequisites
Ensure the following before deploying this solution:
✅ AWS Account with SES, SNS, and Lambda permissions
✅ AWS CLI Installed & Configured (aws configure)
✅ IAM Role with necessary policies for Lambda to access SES and SNS
