# Cloud-Security-Automation-with-AWS-Guardrails-Autoremediation
Cloud Security Automation in AWS: From broken policies to resilient guardrails.

# Cloud Security Automation with AWS – Guardrails & Autoremediation

This project is a consolidated showcase of my learning journey through the [Securosis Security Lab a Week (S.L.A.W.)](https://slaw.securosis.com/) series.  

Instead of step-by-step instructions, this repository highlights the **objectives, goals, and final outcomes** of building automated cloud security guardrails in AWS.

---

## 🎯 Objective
Explore how cloud security automation can replace brittle static controls with **event-driven guardrails** that adapt to real-world misconfigurations and threats.

---

## 🚀 Goals
- Understand the risks of relying on manual enforcement or static policies (like Resource Control Policies).  
- Centralize security events across multiple AWS accounts.  
- Deploy **cross-account roles** and **serverless remediation** patterns securely.  
- Validate automation through testing and event simulations.  
- Apply scalable architectures like **CloudFormation StackSets** and **serverless fan-out patterns** to distribute security controls.  

---

## ✅ Final Result
By the end of this project, I built a **cloud security automation framework** that:  

- **Detects misconfigurations** (e.g., overly permissive S3 bucket policies).  
- **Aggregates events** from all accounts into a central EventBridge bus.  
- **Automatically remediates risks** with Lambda functions (e.g., fixing non-compliant resource configurations).  
- **Secures cross-account role usage** with proper trust chaining.  
- **Schedules recurring scans** using serverless fan-out patterns.  

---

## 🏗️ High-Level Architecture

