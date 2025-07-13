# modern-arch-aws-presentation

This is the aws presentation repo that will be used for all the archives

---

## Presentation Link

[ref](git@github.com:shadreza/modern-arch-aws-presentation.git)

---

### 📊 **Presentation Outline – "Modern Architecture & AWS"**

| Slide # | Title                                | Description                                                                                  |
| ------- | ------------------------------------ | -------------------------------------------------------------------------------------------- |
| 1       | Welcome & Introduction               | Brief intro, session goals, and why modern architecture matters in today’s development world |
| 2       | Why Architecture Has Evolved         | Shift from monoliths → microservices → serverless; problems this solves                      |
| 3       | What is Modern Architecture?         | Key principles: Microservices, Serverless, Event-Driven, DevOps/IaC — all explained simply   |
| 4       | AWS Services for Modern Architecture | Visual mapping of AWS services to these patterns (Lambda, API Gateway, S3, etc.)             |

---

### 🧑‍💻 **Case Study 1: Serverless Feedback App**

| Slide # | Title                    | Description                                                                             |
| ------- | ------------------------ | --------------------------------------------------------------------------------------- |
| 5       | Use Case Overview        | Users submit feedback via a form; app should be low-cost, serverless, and easy to scale |
| 6       | Architecture Walkthrough | Uses S3 + CloudFront (frontend), API Gateway + Lambda (backend), DynamoDB, SNS (alerts) |

---

### ⚙️ **Case Study 2: Async File Processor**

| Slide # | Title                    | Description                                                                        |
| ------- | ------------------------ | ---------------------------------------------------------------------------------- |
| 7       | Use Case Overview        | Users upload files; backend processes them asynchronously                          |
| 8       | Architecture Walkthrough | Uses S3 trigger → Lambda → SQS → Worker (Lambda/ECS) → Store → Notify (SNS or API) |

---

### 🧠 **Conceptual & Practical Guidance**

| Slide # | Title                                 | Description                                                        |
| ------- | ------------------------------------- | ------------------------------------------------------------------ |
| 9       | Choosing AWS Services Wisely          | Tips: Lambda vs ECS, DynamoDB vs RDS, EventBridge vs SQS           |
| 10      | Best Practices in AWS Architecture    | IAM, automation, observability, cost control, resilience           |
| 11      | Common Developer Mistakes to Avoid    | Real-world gotchas: cold starts, missing retries, bad IAM policies |
| 12      | What’s Next in Cloud Dev _(Optional)_ | Trends: AI-native apps, Graviton, edge computing, sustainability   |

---

### 🏁 **Wrap-Up**

| Slide # | Title            | Description                                                                   |
| ------- | ---------------- | ----------------------------------------------------------------------------- |
| 13      | Key Takeaways    | Recap: Modern ≠ Complex; it's about building smarter with the right AWS tools |
| 14      | Thank You & Q\&A | Invite questions, share contact info or resources                             |

---
