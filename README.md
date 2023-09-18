# My Portfolio Terminal

Welcome to my portfolio repository  
[Click here to checkout my Portfolio!](https://samanxsaybani.s3.eu-central-1.amazonaws.com/index.html)


## Table of Contents
- About
- Features
- Serverless frontend with Amazon S3
- Infrastructure as Code with Terraform
- Continuous Integration and Deployment with GitHub Actions
- License


### About
This repository houses the source code and the infrastructure of my portfolio, and it's designed to resemble a Linux terminal. You can use the terminal interface to connect to my various online profiles and portfolios.  

The code is hosted and served by an Amazon S3 bucket and it's infrastructure is managed as code Terraform. New updates and versions of the code is managed by GitHub Actions CI/CD pipline

### Features
- Amazon S3 static web hosting
- Infrastructure managed as code using Terraform
- Continuous Integration and Deployment using GitHub Actions
- Reusable S3 module (For Web Hosting purposes)

### Serverless frontend with Amazon S3
To host the code for this portfolio interface, I leveraged Amazon S3 static website hosting abilities to ensure a scale-able and cloud native solution  
( xx So I'll be safe in case of an insane demand for my portfolio xx)

### Infrastructure as Code with Terraform
I manage the infrastructure for this project using Terraform, enabling easy and consistent provisioning and management of AWS resources. The S3 bucket module of this repository is perfect for reusing in case you need a similar S3 web hosting ability

### Continuous Integration and Deployment with GitHub Actions
I've implemented a CI/CD pipeline using GitHub Actions to automate the deployment process of the code and it's infrastructure. GitHub Actions automates the testing, building, and deployment of changes, ensuring that updates to my portfolio are delivered to S3 seamlessly

### License
This project is licensed under the **[MIT License](https://opensource.org/license/mit/)**
