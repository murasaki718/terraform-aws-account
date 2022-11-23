# terraform-aws-account

![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/tedilabs/terraform-aws-account?color=blue&sort=semver&style=flat-square)
![GitHub](https://img.shields.io/github/license/tedilabs/terraform-aws-account?color=blue&style=flat-square)
[![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&logoColor=white&style=flat-square)](https://github.com/pre-commit/pre-commit)

Terraform module which creates Account and IAM related resources on AWS.


## Target AWS Services

Terraform Modules from [this package](https://github.com/tedilabs/terraform-aws-account) were written to manage the following AWS Services with Terraform.

- **AWS Account**
  - Account Settings
  - Region Settings
- **AWS IAM**
  - User
  - Group
  - Role
  - Service-linked Role
  - Policy
  - OpenID Connect Identity Provider
  - SAML Identity Provider
- **AWS IAM Identity Center (AWS SSO)**
  - Account Assignment
  - Permission Set
- **AWS Organization**
  - Organization
  - Organization Unit
  - Account


## Examples

### IAM

- [OIDC Identity Providers](./examples/iam-oidc-identity-providers)
- [SAML Identity Providers](./examples/iam-saml-identity-providers)


## Other Terraform Modules from Tedilabs

Enjoying [terraform-aws-account](https://github.com/tedilabs/terraform-aws-account)? Check out some of our other modules:

- [AWS Container](https://github.com/tedilabs/terraform-aws-container) - A package of Terraform Modules to manage AWS Container resources.
- [AWS Domain](https://github.com/tedilabs/terraform-aws-domain) - A package of Terraform Modules to manage AWS Domain resources.
- [AWS Load Balancer](https://github.com/tedilabs/terraform-aws-load-balancer) - A package of Terraform Modules to manage AWS Load Balancer resources.
- [AWS Network](https://github.com/tedilabs/terraform-aws-network) - A package of Terraform Modules to manage AWS Network resources.
- [AWS Security](https://github.com/tedilabs/terraform-aws-security) - A package of Terraform Modules to manage AWS Security resources.

Or check out [the full list](https://github.com/search?q=org%3Atedilabs+topic%3Aterraform-module&type=repositories)


## Self Promotion

Like this project? Follow the repository on [GitHub](https://github.com/tedilabs/terraform-aws-account). And if you're feeling especially charitable, follow **[posquit0](https://github.com/posquit0)** on GitHub.


## License

Provided under the terms of the [Apache License](LICENSE).

Copyright © 2021-2022, [Byungjin Park](https://www.posquit0.com).
