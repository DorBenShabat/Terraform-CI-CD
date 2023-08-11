# Terraform CI/CD

This repository contains Terraform configurations for provisioning infrastructure on AWS, and it uses GitHub Actions for continuous integration and deployment.

## Project Structure

- `main.tf`: This is the main Terraform configuration file.
- `.github/workflows/terraform.yml`: This file contains the GitHub Actions workflow definition for automating Terraform commands.

## How to Use

1. Clone the repository.
2. Navigate to the root directory.
3. Use Terraform commands as usual (e.g., `terraform init`, `terraform apply`, etc.).
4. When you push to the `master` branch, the GitHub Actions workflow will automatically run `terraform init` and `terraform apply` to provision/update the infrastructure.

## Note

Ensure you've set up the required secrets in the GitHub repository for authenticating with your Terraform backend and AWS (if necessary).

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.
