![Terraform](https://img.shields.io/badge/terraform-%235835CC.svg?style=for-the-badge&logo=terraform&logoColor=white)

## What is Infrastructure as Code with Terraform?

Infrastructure as Code (IaC) tools allow you to manage infrastructure with configuration files rather than through a graphical user interface. IaC allows you to build, change, and manage your infrastructure in a safe, consistent, and repeatable way by defining resource configurations that you can version, reuse, and share.

<img src="https://developer.hashicorp.com/_next/image?url=https%3A%2F%2Fcontent.hashicorp.com%2Fapi%2Fassets%3Fproduct%3Dtutorials%26version%3Dmain%26asset%3Dpublic%252Fimg%252Fterraform%252Fterraform-iac.png%26width%3D2400%26height%3D870&w=3840&q=75" width="600">


### [How to install terraform](https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli)

## Terraform Commands

Terraform provides a set of commands that you can use to interact with your infrastructure code and manage your resources. Here is an introduction to some of the essential commands:

- `terraform init`: This command initializes a configuration directory. It downloads and installs the necessary providers defined in your configuration. In the case of the AWS provider, it prepares the environment for creating and managing AWS resources.

- `terraform plan`: The `plan` command creates an execution plan. It compares the current state of your infrastructure with the desired state defined in your configuration files. This allows you to preview the changes that Terraform will make before actually applying them.

- `terraform apply`: When you're satisfied with the execution plan, you can use the `apply` command to apply the changes and create/update the actual resources in your cloud environment.

- `terraform destroy`: This command is used to destroy the resources that were created by Terraform. It's important to use this command when you no longer need certain resources to avoid unnecessary charges.
