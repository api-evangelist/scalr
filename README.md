# Scalr

Scalr is an enterprise-grade, drop-in replacement for Terraform Cloud and a remote Terraform operations backend that provides cost estimation, policy enforcement, and collaborative infrastructure management. Scalr features a hierarchical account-environment-workspace model, full compatibility with the TFC API and Terraform/OpenTofu CLI, OIDC authentication, GitOps workflows, OPA policy enforcement, and a comprehensive REST API for managing infrastructure as code operations at scale.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/scalr/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

FinOps, GitOps, Infrastructure as Code, Kubernetes, OPA, OpenTofu, Policy, Terraform

## Timestamps

- **Created:** 2026-05-02
- **Modified:** 2026-05-02

## APIs

### Scalr User API
The Scalr User API provides programmatic access to user-level resources including farms, farm roles, servers, events, and cloud locations. This is the legacy cloud management API (v1beta0).

**Human URL:** [https://api-explorer.scalr.com/](https://api-explorer.scalr.com/)

#### Tags
Cloud Management, Farms, Infrastructure, Scalr, Servers

#### Properties
- [Documentation](https://api-explorer.scalr.com/)
- [OpenAPI](openapi/scalr-user-openapi.yml)

### Scalr Account API
Account-level resources including environments, roles, images, and orchestration rules (legacy v1beta0 API).

**Human URL:** [https://api-explorer.scalr.com/](https://api-explorer.scalr.com/)

#### Tags
Account Management, Cloud Management, Environments, Roles, Scalr

#### Properties
- [Documentation](https://api-explorer.scalr.com/)
- [OpenAPI](openapi/scalr-account-openapi.yml)

### Scalr Global API
Global resources including images and roles spanning the entire Scalr installation (legacy v1beta0 API).

**Human URL:** [https://api-explorer.scalr.com/](https://api-explorer.scalr.com/)

#### Tags
Cloud Management, Global, Images, Roles, Scalr

#### Properties
- [Documentation](https://api-explorer.scalr.com/)
- [OpenAPI](openapi/scalr-global-openapi.yml)

### Scalr IaC Management API
TFC-compatible API providing programmatic control over workspaces, environments, runs, state, variables, and policies. Authenticates with Bearer tokens and supports OIDC.

**Human URL:** [https://docs.scalr.io/reference/overview-1](https://docs.scalr.io/reference/overview-1)

#### Tags
Infrastructure as Code, OpenTofu, Policy, Runs, Scalr, Terraform, Workspaces

#### Properties
- [Documentation](https://docs.scalr.io/reference/overview-1)
- [Getting Started](https://docs.scalr.io/docs/introduction)
- [Authentication](https://docs.scalr.io/reference/api-tokens)

## Capabilities

Naftiko capability definitions for AI-assisted Terraform infrastructure management:

**Shared Definitions:**
- [capabilities/shared/user-api.yaml](capabilities/shared/user-api.yaml) — Scalr User API consumer (legacy cloud management)

**Workflow Capabilities:**
- [capabilities/infrastructure-as-code.yaml](capabilities/infrastructure-as-code.yaml) — Unified IaC workflow (4 tools) for DevOps teams managing Terraform workspaces and infrastructure

## Rules

- [rules/scalr-rules.yml](rules/scalr-rules.yml) — Spectral ruleset enforcing Scalr API conventions

## Schemas

- [json-schema/scalr-workspace-schema.json](json-schema/scalr-workspace-schema.json) — Workspace resource schema
- [json-schema/scalr-run-schema.json](json-schema/scalr-run-schema.json) — Run execution schema

## JSON Structures

- [json-structure/scalr-workspace-structure.json](json-structure/scalr-workspace-structure.json) — Workspace structure documentation

## JSON-LD

- [json-ld/scalr-context.jsonld](json-ld/scalr-context.jsonld) — JSON-LD context mapping Scalr vocabulary to schema.org

## Examples

- [examples/scalr-list-workspaces-example.json](examples/scalr-list-workspaces-example.json) — List workspaces example
- [examples/scalr-create-run-example.json](examples/scalr-create-run-example.json) — Create Terraform run example

## Vocabulary

- [vocabulary/scalr-vocabulary.yml](vocabulary/scalr-vocabulary.yml) — Scalr terminology and domain vocabulary (16 terms)

## Common Properties

- [Website](https://scalr.com/)
- [Documentation](https://docs.scalr.io/)
- [API Reference](https://docs.scalr.io/reference/overview-1)
- [API Explorer](https://api-explorer.scalr.com/)
- [GitHub](https://github.com/scalr)
- [MCP Server](https://docs.scalr.io/docs/mcp-server)
- [Terraform Provider](https://registry.terraform.io/providers/Scalr/scalr/latest/docs)
- [Changelog](https://updates.scalr.io/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
