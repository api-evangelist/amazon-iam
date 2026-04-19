# Amazon IAM (amazon-iam)
Amazon Identity and Access Management (IAM) enables you to manage access to AWS services and resources securely. Using IAM, you can create and manage AWS users, groups, roles, and policies, and use permissions to allow and deny their access to AWS resources. IAM is a feature of your AWS account offered at no additional charge.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/amazon-iam/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Access Management, Authentication, Authorization, AWS, Identity, Security

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-04-19

## APIs

### AWS IAM API
The AWS IAM API provides programmatic access to manage users, groups, roles, policies, and access keys for securing access to AWS services and resources.

**Human URL:** [https://aws.amazon.com/iam/](https://aws.amazon.com/iam/)

#### Tags:

 - Access Management, Authentication, Authorization, Identity, Security

#### Properties

- [Documentation](https://docs.aws.amazon.com/IAM/latest/APIReference/)
- [OpenAPI](openapi/amazon-iam-openapi.yml)
- [APIReference](https://docs.aws.amazon.com/IAM/latest/APIReference/)
- [GettingStarted](https://docs.aws.amazon.com/IAM/latest/UserGuide/getting-started.html)
- [Pricing](https://aws.amazon.com/iam/pricing/)
- [FAQ](https://aws.amazon.com/iam/faqs/)
- [JSONSchema](json-schema/amazon-iam-user-schema.json)
- [JSONStructure](json-structure/amazon-iam-user-structure.json)
- [Example](examples/amazon-iam-user-example.json)

## Common Properties

- [Portal](https://aws.amazon.com/iam/)
- [Website](https://aws.amazon.com/iam/)
- [Documentation](https://docs.aws.amazon.com/IAM/latest/UserGuide/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [Support](https://aws.amazon.com/support/)
- [Blog](https://aws.amazon.com/blogs/security/)
- [GitHubOrganization](https://github.com/aws)
- [Console](https://console.aws.amazon.com/iam/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [Login](https://signin.aws.amazon.com/)
- [StatusPage](https://health.aws.amazon.com/health/status)
- [YouTube](https://www.youtube.com/user/AmazonWebServices)
- [StackOverflow](https://stackoverflow.com/questions/tagged/amazon-iam)
- [Contact](https://aws.amazon.com/contact-us/)
- [JSONLD](json-ld/amazon-iam-context.jsonld)

## Features

| Name | Description |
|------|-------------|
| User Management | Create, manage, and delete IAM users with fine-grained permissions. |
| Role-Based Access Control | Define IAM roles that can be assumed by users, services, or applications. |
| Policy Management | Create and attach identity-based and resource-based policies to control access. |
| Multi-Factor Authentication | Enable MFA for IAM users to add an extra layer of security. |
| Access Key Management | Programmatically manage AWS access keys for long-term credentials. |
| Permission Boundaries | Use permission boundaries to define the maximum permissions an entity can have. |
| Service Control Policies | Centrally control the maximum available permissions across AWS accounts. |

## Use Cases

| Name | Description |
|------|-------------|
| Least Privilege Access | Grant only the permissions required for specific tasks to reduce the attack surface. |
| Cross-Account Access | Enable users in one AWS account to assume roles in another account. |
| Service-to-Service Authorization | Allow AWS services to access other services on your behalf through service roles. |
| Temporary Credentials | Use STS to issue temporary security credentials for short-lived access. |
| Security Compliance | Audit IAM configurations to ensure compliance with security policies and regulations. |

## Integrations

| Name | Description |
|------|-------------|
| AWS Organizations | Apply Service Control Policies across multiple AWS accounts in an organization. |
| AWS CloudTrail | Log all IAM API calls for auditing and compliance tracking. |
| AWS Config | Monitor IAM configuration changes and evaluate compliance with rules. |
| AWS Security Hub | Centralize IAM security findings with other AWS security services. |
| Amazon Cognito | Federate Cognito user pool identities with IAM roles for application access. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [AWS IAM API](openapi/amazon-iam-openapi.yml)

### JSON Schema

20 schema files covering users, roles, groups, policies, and access keys.

### JSON Structure

20 JSON Structure files converted from JSON Schema.

### JSON-LD

- [Amazon IAM Context](json-ld/amazon-iam-context.jsonld)

### Examples

20 example JSON files generated from schemas.

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [AWS IAM API](capabilities/shared/iam.yaml) — operations for users, roles, and policies

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [IAM Access Management](capabilities/iam-access-management.yaml) | IAM | 10 | Cloud Administrator, Security Engineer |

## Vocabulary

- [Amazon IAM Vocabulary](vocabulary/amazon-iam-vocabulary.yaml) — Unified taxonomy mapping 7 resources, 9 actions, 1 workflow, and 2 personas

## Rules

- [Amazon IAM Spectral Rules](rules/amazon-iam-spectral-rules.yml) — 20 rules across 8 categories enforcing Amazon IAM API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
