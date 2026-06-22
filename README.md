# AWS S3 Cloud Project

A hands-on AWS project demonstrating real-world cloud engineering skills using Amazon S3, CloudFront, and Lambda.

---

## What I Built

### Phase 1 — S3 Versioning + Lifecycle Rules
- Enabled versioning on an S3 bucket to protect files from accidental overwrites
- Simulated file updates and verified multiple versions are saved
- Created a lifecycle rule to automatically transition old versions to S3 Standard-IA after 30 days and permanently delete them after 90 days

### Phase 2 — S3 + CloudFront CDN
- Created a CloudFront distribution connected to the S3 bucket
- Configured private bucket access so only CloudFront can access S3
- Set default root object to serve index.html
- Website is now delivered globally with HTTPS

### Phase 3 — S3 + Lambda Event Notifications
- Created a Lambda function using Python 3.12
- Connected S3 bucket as a trigger for the Lambda function
- When a file is uploaded to S3, Lambda automatically logs the bucket name and file name
- Verified logs in Amazon CloudWatch

---

## Services Used
- Amazon S3
- Amazon CloudFront
- AWS Lambda
- Amazon CloudWatch

---

## Live Website
https://dlr5tygmmutur.cloudfront.net

---

## Key Concepts Learned
- S3 Versioning and Lifecycle Management
- Content Delivery Networks (CDN)
- Event Driven Architecture
- Serverless Computing with Lambda
- IAM Bucket Policies and Origin Access Control
