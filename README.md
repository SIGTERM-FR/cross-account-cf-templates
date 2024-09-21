# Cross Account CloudFormation Templates

This repository contains CloudFormation templates for provisioning cross-account IAM roles. These roles enable secure access between AWS accounts, following best practices for least privilege and permissions boundary management.

Usage
Deploy the templates to allow trusted entities from one AWS account to assume roles in another, facilitating cross-account access and resource management.

### Pre-built links (eu-west-3)

- Read-only: https://console.aws.amazon.com/cloudformation/home?region=eu-west-3#/stacks/create/review?stackName=SIGTERM-IAM-role-readonly&templateURL=https://sigterm-public.s3.amazonaws.com/sigterm-iam-role-readonly.yml
- Admin: https://console.aws.amazon.com/cloudformation/home?region=eu-west-3#/stacks/create/review?stackName=SIGTERM-IAM-role-admin&templateURL=https://sigterm-public.s3.amazonaws.com/sigterm-iam-role-admin.yml
