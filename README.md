CICD
Objective

Build a basic CI/CD pipeline using GitHub Actions and Docker.

Tools Used
GitHub Actions
Docker
GitHub
Workflow File
name: CI Pipeline

on:
  push:
    branches:
      - main

jobs:
  docker:
    runs-on: ubuntu-latest

    steps:
      - uses: actions/checkout@v3

      - name: Build Docker Image
        run: docker build -t cicd-app .
Commands Used
git init
git add .
git commit -m "CI/CD setup"
git push
Skills Learned
Git workflows
Docker containerization
Linux command line
Cloud deployment
CI/CD pipelines
Monitoring systems
AWS EC2 basics
Folder Structure
devops-projects/
│
├── project1-github-actions/
├── project2-docker-app/
├── project3-grafana-monitoring/
├── project4-aws-deployment/
├── project5-cicd-pipeline/
└── README.md
Requirements

Install the following tools:

VS Code
Git
Docker Desktop
AWS Account
Conclusion

These projects helped me understand the fundamentals of DevOps, including automation, deployment, monitoring, Docker, and cloud infrastructure.

