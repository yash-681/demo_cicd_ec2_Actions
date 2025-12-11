# GitHub Actions CI Pipeline — demo_cicd_ec2_AWS

This document describes the **GitHub Actions CI pipeline** used in the project to validate the application before it is deployed through AWS CodePipeline.

The GitHub Actions workflow ensures:
- Code is valid before entering AWS
- Automatic CI checks run on every commit
- Faster feedback for developers
- Improved reliability of AWS deployments

---

# 🚀 What This GitHub Actions Pipeline Does

### ✔ Runs automatically on every push to `main`  
### ✔ Checks out the repo  
### ✔ Performs basic build/validation steps  
### ✔ Acts as the **first quality gate** before AWS CI/CD

You can expand it later to include:
- Unit tests  
- Linting  
- Docker build checks  
- Security scans  

---

<img width="1438" height="655" alt="image" src="https://github.com/user-attachments/assets/2c5c8fec-c16d-4fdb-baf0-281cea03f1ed" />
