# Scalr (scalr)

Scalr is an enterprise-grade, drop-in replacement for Terraform Cloud and a remote Terraform operations backend that provides cost estimation, policy enforcement, and collaborative infrastructure management. Scalr features a hierarchical account-environment-workspace model, full compatibility with the TFC API and Terraform/OpenTofu CLI, OIDC authentication, GitOps workflows, OPA policy enforcement, and a comprehensive REST API for managing infrastructure as code operations at scale.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- FinOps
- GitOps
- Infrastructure as Code
- Kubernetes
- OPA
- OpenTofu
- Policy
- Terraform

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-19

## APIs

### Scalr User API

The Scalr User API provides programmatic access to user-level resources including farms, farm roles, servers, events, cloud locations, cost centers, and scaling metrics. This is the legacy cloud management API (v1beta0) for managing cloud infrastructure resources across multiple cloud providers.

- **Human URL:** [https://api-explorer.scalr.com/](https://api-explorer.scalr.com/)

#### Tags

- Cloud Management
- Farms
- Infrastructure
- Scalr
- Servers

#### Properties

- [Documentation](https://api-explorer.scalr.com/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/openapi/scalr-user-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/scalr-account.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalr-account.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/scalr-global.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalr-global.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/scalr-user.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalr-user.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Scalr Account API

The Scalr Account API provides programmatic access to account-level resources including environments, roles, images, orchestration rules, and account-wide configuration. This is the legacy cloud management API (v1beta0).

- **Human URL:** [https://api-explorer.scalr.com/](https://api-explorer.scalr.com/)

#### Tags

- Account Management
- Cloud Management
- Environments
- Roles
- Scalr

#### Properties

- [Documentation](https://api-explorer.scalr.com/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/openapi/scalr-account-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/scalr-account.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalr-account.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/scalr-global.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalr-global.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/scalr-user.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalr-user.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Scalr Global API

The Scalr Global API provides programmatic access to global-level resources including images and roles that span the entire Scalr installation.

- **Human URL:** [https://api-explorer.scalr.com/](https://api-explorer.scalr.com/)

#### Tags

- Cloud Management
- Global
- Images
- Roles
- Scalr

#### Properties

- [Documentation](https://api-explorer.scalr.com/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/openapi/scalr-global-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/scalr-account.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalr-account.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/scalr-global.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalr-global.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/scalr-user.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalr-user.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Scalr IaC Management API

The Scalr IaC Management API (TFC-compatible) provides programmatic control over workspaces, environments, runs, state, variables, policies, and provider configurations. Fully compatible with Terraform Cloud API and Terraform/OpenTofu CLI. Authenticates using Bearer tokens (personal or service account). Supports OIDC for GitHub, GitLab, AWS, Azure, and other identity providers.

- **Human URL:** [https://docs.scalr.io/reference/overview-1](https://docs.scalr.io/reference/overview-1)

#### Tags

- Infrastructure as Code
- OpenTofu
- Policy
- Runs
- Scalr
- Terraform
- Workspaces

#### Properties

- [Documentation](https://docs.scalr.io/reference/overview-1)
- [Getting Started](https://docs.scalr.io/docs/introduction)
- [Authentication](https://docs.scalr.io/reference/api-tokens)
- [Postman Collection](collections/scalr-account.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalr-account.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/scalr-global.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalr-global.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/scalr-user.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/scalr-user.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/scalr)
- [Website](https://scalr.com/)
- [Documentation](https://docs.scalr.io/)
- [API Reference](https://docs.scalr.io/reference/overview-1)
- [A P I  Explorer](https://api-explorer.scalr.com/)
- [Git Hub](https://github.com/scalr)
- [Blog](https://scalr.com/blog/)
- [Changelog](https://updates.scalr.io/)
- [M C P  Server](https://docs.scalr.io/docs/mcp-server)
- [Terraform  Provider](https://registry.terraform.io/providers/Scalr/scalr/latest/docs)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/vocabulary/scalr-vocabulary.yml)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/json-schema/scalr-workspace-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/json-schema/scalr-run-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/json-ld/scalr-context.jsonld)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/rules/scalr-rules.yml)
- [L L Ms Txt](https://docs.scalr.io/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
