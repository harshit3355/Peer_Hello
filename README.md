# CI/CD Pipeline for NestJS Application 🚀

This repository contains the CI/CD pipeline configuration for a NestJS application using GitHub Actions. The pipeline automates the deployment process and allows manual stopping of the application.

## Workflows

### CI Workflow ⚙️

Automatically builds, tests, and deploys the application to an EC2 instance when changes are pushed to the `main` branch or manually triggered.

### Stop Application Workflow 🛑

Manually stops the application running on the EC2 instance using `pm2`.

## Setup Instructions

1. **Add Secrets** 🔑
   - `EC2_HOST`: Public IP address of your EC2 instance.
   - `EC2_USER`: SSH username (e.g., `ubuntu`).
   - `EC2_KEY`: Private key for SSH access (contents of the `.pem` file).

2. **Trigger Workflows** 🚀
   - **CI Workflow**: Push changes to `main` or trigger manually.
   - **Stop Application Workflow**: Trigger manually to stop the application.

## Resources 📚

- **Screencast**: [Video Link](https://www.loom.com/share/9b32f2b8157d46168b3cdc2ab3dcbb98?sid=15fffbb4-035d-4599-bf35-0b1a71fe91db)

Feel free to contribute or raise issues if you encounter any problems! 😊
