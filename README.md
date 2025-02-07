# Terraform S3 Static Website

This project demonstrates how to use Terraform to deploy a static website to Amazon S3, utilizing AWS's static website hosting feature. The project includes the creation of an S3 bucket, configuration for static hosting, and basic HTML pages (`index.html` and `error.html`).

## Requirements:
- Terraform
- AWS CLI configured with your AWS credentials
- An AWS account

## Steps:
1. Clone this repository to your local machine.
2. Run `terraform init` to initialize Terraform.
3. Modify `main.tf` if necessary (e.g., bucket name, region).
4. Run `terraform plan` to see the execution plan.
5. Run `terraform apply` to create the S3 bucket and deploy the website.
6. Access your website using the provided S3 bucket endpoint URL.

## Files:
- **main.tf**: Terraform configuration for creating the S3 bucket and setting up static hosting.
- **index.html**: The homepage of the static website.
- **error.html**: Custom error page.
- **.gitignore**: Ignores Terraform state and other unnecessary files.

## Documentation:
The setup and configuration of the AWS S3 bucket and static hosting were guided by the official AWS Terraform documentation.

## Future Enhancements:
- Custom domain support with Route 53.
