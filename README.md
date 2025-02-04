**General Setup**
- In this lab we needed to edit our cloud-config.yaml to include nginx, nmap. To do this, we added the 2 packages in the cloud.yaml file
- We followed website links included in the starter file to fill out the information needed to create an instance.

**Command used to create new SSH Key Pair**
> ssh-keygen -t rsa -b 4096 aws

**How to create an AWS instance with Terraform**
> Terraform init
  - Allows you to use other terraform commands within the directory
> Terraform Validate
  - Checks the syntax of your terraform file and outputs errors when there are issues
> Terraform plan
  - Shows changes required by the current configuration
> Terraform Apply
  - Create or update infrastructure
> Terraform Destroy
  - This will delete the infrastructure that was built from terraform apply

Note:
> I added a variables.tf, you will be prompted to paste your public key when you use terraform apply
> I did this to avoid hard coding my ssh key and pushing to github.

