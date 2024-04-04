# Provision a WebSite on AWS Using Terraform

This repository contains Terraform code to set up a basic infrastructure for hosting a website on **Amazon Web Services (AWS)**. The infrastructure includes an **EC2** for hosting website and an **Elastic IP** to access the website

## Getting Started

1. **Prerequisites**:

   - Configure your AWS credentials using `aws configure`.

2. **Clone the Repository**:
   
-  git clone <MY_REPO_URL>
-  cd CI-CD-pipeline-project
3. **Initialize Terraform**:
   terraform init


4. **Customize Variables**:
- Open `variables.tf` and modify any relevant variables (e.g., bucket name, region).

5. **Deploy Infrastructure**:

terraform apply


6. **Access Your Website**:
- After successful deployment, your website will be available at `http://your_eip`.

## Contributing

Feel free to contribute by opening issues or submitting pull requests. Let's make this project even better!
