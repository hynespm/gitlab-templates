## Descripotion: This folder contains a set of reuseable gitlab template files for Terraform deployments

* [.gitlab-ci-tag-version.yml](.gitlab-ci-tag-version.yml) - Automatically Tag the repository based on a major, minor and patch number
* [.gitlab-ci-tf-plan.yml](.gitlab-ci-tf-plan.yml) - Reusable Terraform plan job which creates an artifact
* [.gitlab-ci-tf-plan-apply.yml](.gitlab-ci-tf-plan-apply.yml) - Reusable Terraform plan and apply job