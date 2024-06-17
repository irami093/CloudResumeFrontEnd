# AWS Cloud Resume Challenge

The Cloud Resume Challenge is a multi-step cloud-hosted resume project which helps build and demonstrate fundamental skills required to pursue a career in the cloud. Career paths include Cloud Engineer, DevOps Engineer, and more. This project covers frontend development, backend development, app integration, infrastructure-as-code, CI/CD, and more.

## AWS Services used include:
- API Gateway
- CloudFront
- CloudWatch
- DynamoDB
- GitHub Actions
- Lambda
- Route 53
- S3
- Terraform

## Architectural Diagram

![Untitled Diagram drawio](https://github.com/irami093/CloudResumeFrontEnd/assets/156238516/45986f90-c44c-4c95-831c-fbf7e3ccf19b)


## Frontend
Front End Web Application contains HTML, CSS, and JavaScript.

## Backend
Back End contains a Lambda function based on boto3 Python. It is also provisioned using Infrastructure-as-Code (IaC) using Terraform.

## CI/CD
GitHub Actions enables a workflow that automates changes made to the Frontend and deploys them to S3 seamlessly.
