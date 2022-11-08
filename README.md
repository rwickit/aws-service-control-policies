# AWS Service Control Policies (SCP)s

Collection of AWS Organization Service Control Policies

## Account Level

These SCPs are designed to be applied for individual account protections.

Examples include:

- prevent the use of the root user to any account
- protect CORE account permission modification in AWS IAM IC (formerly SSO)
- protect specifically named resources in accounts

## Organization Level

These SCPs prevent operations done on accounts regarding the AWS Organizations Service itself.

Examples include:

- Letting an Account Leave the organization
- Allowing all services (Default SCP required for all services to work)
- Denying all services (can be applied to archived account and prevent the deployment of new services)

## Service Level

Service level SCPs can allow or deny access to specific services.
