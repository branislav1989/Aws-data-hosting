# 🔧 Common AWS SNS Issues & Troubleshooting Guide

### 1. [Troubleshooting Amazon SNS topics using AWS X-Ray](https://docs.aws.amazon.com/sns/latest/dg/sns-troubleshooting.html)  
**Overview:** Use AWS X-Ray tracing to troubleshoot delayed or failed SNS message deliveries and visualize service interactions.  
**Why include:** Official AWS guide, ideal for diagnosing complex event-flow issues. 

---

### 2. [Troubleshooting Amazon SNS identity and access issues](https://docs.aws.amazon.com/sns/latest/dg/security_iam_troubleshoot.html)  
**Overview:** Covers common IAM errors like `NotAuthorized`, `PassRole`, and cross-account access problems.  
**Why include:** Security and permission issues are the #1 cause of SNS failures. 

---

### 3. [Troubleshooting message filtering issues in Amazon SNS](https://repost.aws/knowledge-center/sns-troubleshoot-message-filtering)  
**Overview:** Helps diagnose why some subscribers receive no messages due to filter policies or delivery delays.  
**Why include:** Great for real-world issues when filtering topics or debugging missing deliveries. 

---

### 4. [AWS SNS is not sending SMS anymore](https://stackoverflow.com/questions/54242154/aws-sns-is-not-sending-sms-anymore)  
**Overview:** Common reason: default monthly SMS spend limit (e.g., USD 1/month) causes delivery to stop unexpectedly.  
**Why include:** Highly-viewed Stack Overflow thread with actionable steps to fix SMS quotas. 

---

### 5. [AWS SNS Failed Notifications logging](https://serverfault.com/questions/998626/aws-sns-failed-notifications-logging)  
**Overview:** Guides configuring SNS to log failed delivery attempts to CloudWatch, helpful for debugging HTTP/HTTPS endpoints.  
**Why include:** Practical community solution popular among developers troubleshooting notification issues. 

---
**Keywords**: aws sns troubleshooting, sns delivery failure, sns not sending messages, sns sms issue, sns topic filter not working, troubleshoot aws sns
---

