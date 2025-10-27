# 🧩 Common CI/CD Workflow for MuleSoft Deployments

## 📖 Description
This repository contains **centralized reusable GitHub Actions workflows** designed to automate the **CI/CD process for MuleSoft applications** across multiple repositories.  
By maintaining common workflows here, teams can ensure consistency, reduce duplication, and simplify deployment to **Anypoint Exchange** and **CloudHub 2.0**.

Other project repositories can easily reference these workflows using the `workflow_call` event in their pipeline definitions.  
This approach enables a unified CI/CD strategy while keeping environment-specific secrets and configurations in individual project repos.


## 🚀 Key Features
- **Reusable Workflows:** Define once, use across multiple MuleSoft projects.
- **Automated Build & Deploy:** Build, package, and deploy Mule applications seamlessly.
- **Exchange Publishing:** Publish artifacts to Anypoint Exchange automatically.
- **CloudHub 2.0 Ready:** Supports environment-based deployments (Dev/UAT/Prod).
- **Secure Secrets Management:** Uses GitHub secrets inheritance for safe credential handling.
- **Version Control:** Auto-increment or manually control versions for release management.
