# Amazon Keyspaces (amazon-keyspaces)
Amazon Keyspaces (for Apache Cassandra) is a scalable, highly available, and managed Apache Cassandra-compatible database service that lets you run Cassandra workloads on AWS without managing servers or software.

**URL:** [https://aws.amazon.com/keyspaces/](https://aws.amazon.com/keyspaces/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - AWS, Cassandra, Database, Managed Database, NoSQL, Wide Column

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Amazon Keyspaces API
The Amazon Keyspaces API provides programmatic access to manage Cassandra-compatible keyspaces and tables, configure capacity modes, encryption, and point-in-time recovery for serverless Cassandra workloads.

**Human URL:** [https://aws.amazon.com/keyspaces/](https://aws.amazon.com/keyspaces/)

#### Tags:

 - Cassandra, NoSQL Database, Serverless

#### Properties

- [Documentation](https://docs.aws.amazon.com/keyspaces/latest/devguide/what-is-keyspaces.html)
- [OpenAPI](https://api.apis.guru/v2/specs/amazonaws.com/keyspaces/2022-02-10/openapi.yaml)
- [Pricing](https://aws.amazon.com/keyspaces/pricing/)
- [GettingStarted](https://aws.amazon.com/keyspaces/getting-started/)
- [FAQ](https://aws.amazon.com/keyspaces/faqs/)
- [APIReference](https://docs.aws.amazon.com/keyspaces/latest/APIReference/Welcome.html)
- [OpenAPI](openapi/amazon-keyspaces-openapi.yml)
- [JSONSchema](json-schema/amazon-keyspaces-keyspace-schema.json)
- [JSONSchema](json-schema/amazon-keyspaces-table-schema.json)
- [JSONLD](json-ld/amazon-keyspaces-context.jsonld)

## Common Properties

- [Blog](https://aws.amazon.com/blogs/database/category/database/amazon-keyspaces/)
- [Support](https://aws.amazon.com/premiumsupport/)
- [Console](https://console.aws.amazon.com/keyspaces/home)
- [CLI](https://docs.aws.amazon.com/cli/latest/reference/keyspaces/)
- [SDK](https://aws.amazon.com/tools/)
- [StatusPage](https://status.aws.amazon.com/)
- [Compliance](https://aws.amazon.com/compliance/)
- [TermsOfService](https://aws.amazon.com/service-terms/)
- [Portal](https://aws.amazon.com/keyspaces/)
- [Documentation](https://docs.aws.amazon.com/keyspaces/)
- [Pricing](https://aws.amazon.com/keyspaces/pricing/)
- [GettingStarted](https://aws.amazon.com/keyspaces/getting-started/)
- [FAQ](https://aws.amazon.com/keyspaces/faqs/)
- [PrivacyPolicy](https://aws.amazon.com/privacy/)
- [SignUp](https://portal.aws.amazon.com/billing/signup)
- [GitHubOrganization](https://github.com/aws)
- [SpectralRules](rules/amazon-keyspaces-spectral-rules.yml)
- [NaftikoCapability](capabilities/amazon-keyspaces-workflow.yaml)
- [Vocabulary](vocabulary/amazon-keyspaces-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Cassandra Compatibility | Fully compatible with Apache Cassandra drivers, tools, and applications with no code changes required. |
| Serverless Scaling | Automatically scales table throughput and storage up and down based on application traffic. |
| Point-in-Time Recovery | Continuous backup with PITR enables restoration of tables to any second within the last 35 days. |
| Encryption at Rest | Data is encrypted at rest by default using AWS managed keys or customer-managed keys via AWS KMS. |
| VPC Support | Access Amazon Keyspaces from within VPCs using VPC endpoints for enhanced network security. |
| Capacity Modes | Choose on-demand or provisioned capacity mode with auto scaling for predictable workloads. |

## Use Cases

| Name | Description |
|------|-------------|
| IoT Data Storage | Store high-volume sensor data and telemetry from IoT devices with wide-column schema. |
| User Activity Tracking | Track user events, clickstreams, and behavioral data at massive scale. |
| Time-Series Data | Manage time-series data for monitoring, metrics, and log aggregation. |
| Migrate Cassandra Workloads | Lift and shift existing Cassandra applications to a fully managed cloud service. |

## Integrations

| Name | Description |
|------|-------------|
| AWS KMS | Use customer-managed keys for encryption with AWS Key Management Service. |
| AWS CloudTrail | Audit all API calls to Amazon Keyspaces for security and compliance. |
| Amazon VPC | Access Keyspaces securely from within your VPC using VPC endpoints. |
| AWS IAM | Control access to Keyspaces resources using IAM policies and roles. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Amazon Keyspaces API](openapi/amazon-keyspaces-openapi.yml)

### JSON Schema

- [Keyspace](json-schema/amazon-keyspaces-keyspace-schema.json)
- [Table](json-schema/amazon-keyspaces-table-schema.json)

### JSON Structure

- [Keyspace](json-structure/amazon-keyspaces-keyspace-structure.json)
- [Table](json-structure/amazon-keyspaces-table-structure.json)

### JSON-LD

- [Amazon Keyspaces Context](json-ld/amazon-keyspaces-context.jsonld)

### Examples

- [Keyspace Example](examples/amazon-keyspaces-keyspace-example.json)
- [Table Example](examples/amazon-keyspaces-table-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Amazon Keyspaces](capabilities/shared/keyspaces.yaml) — 6 operations for Cassandra-compatible database management

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Amazon Keyspaces Workflow](capabilities/amazon-keyspaces-workflow.yaml) | Keyspaces | 6 | Developer, Administrator |

## Vocabulary

- [Amazon Keyspaces Vocabulary](vocabulary/amazon-keyspaces-vocabulary.yaml) — Unified taxonomy mapping 2 resources, 5 actions, 1 workflow, and 2 personas

## Rules

- [Amazon Keyspaces Spectral Rules](rules/amazon-keyspaces-spectral-rules.yml) — 16 rules across 8 categories enforcing Amazon Keyspaces API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
