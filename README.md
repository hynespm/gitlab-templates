# Description: Repository of gitlab templates for deploying infrastructure to AWS using Terraform

## Purpose: This repository is for educational purposes.


### Repository Structure

* [infrastructure](infrastructure) - Collection of templates for gitlab jobs which repeat when deploying infrastructure to AWS via Terraform
* [.gitlab-ci-tf-aws-all-env-deploy.yml](.gitlab-ci-tf-aws-all-env-deploy.yml) - Sample template to deploy to 3 AWS accounts (dev, stag, prod). This would be incorporated into a repository of terraform resource definitions.



### Assumptions

* Gitlab is used to store AWS account numbers (dev,stag and prod)
* Role assumption from root to environment accounts (dev, stag, prod) via the Control Tower IAM roles is used prior to Terraform cli execution