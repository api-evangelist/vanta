# Vanta

Vanta is a trust management platform that automates security compliance for frameworks including SOC 2, ISO 27001, HIPAA, PCI DSS, and GDPR. The Vanta API enables organizations to programmatically manage their compliance posture, automate security monitoring, manage vulnerabilities, track controls, manage vendors, and integrate with existing tools and workflows.

**Website:** [https://www.vanta.com](https://www.vanta.com)
**Developer Portal:** [https://developer.vanta.com](https://developer.vanta.com)
**API Base URL:** `https://api.vanta.com`

## APIs

### Vanta API
The Vanta REST API enables programmatic access to compliance, security monitoring, vulnerability management, personnel management, vendor management, and custom integration capabilities.

- **Documentation:** [https://developer.vanta.com/docs/vanta-api-overview](https://developer.vanta.com/docs/vanta-api-overview)
- **Authentication:** [https://developer.vanta.com/docs/api-access-setup](https://developer.vanta.com/docs/api-access-setup)
- **OpenAPI Spec:** [openapi/vanta-openapi.yml](openapi/vanta-openapi.yml)

### Vanta Auditor API
The Vanta Auditor API provides external audit firms programmatic access to customer compliance data during audit engagements.

- **OpenAPI Spec:** [openapi/vanta-auditor-openapi.yml](openapi/vanta-auditor-openapi.yml)

## Authentication

Vanta uses **OAuth 2.0 Client Credentials** flow:

```
POST https://api.vanta.com/oauth/token
```

Rate limits: 5-250 requests/minute depending on endpoint category.

## SDKs and Tools

| Resource | Language | URL |
|---|---|---|
| Auditor API SDK | TypeScript | [VantaInc/vanta-auditor-api-sdk-typescript](https://github.com/VantaInc/vanta-auditor-api-sdk-typescript) |
| Auditor API SDK | Java | [VantaInc/vanta-auditor-api-sdk-java](https://github.com/VantaInc/vanta-auditor-api-sdk-java) |
| MCP Server | Node.js | [VantaInc/vanta-mcp-server](https://github.com/VantaInc/vanta-mcp-server) |

## Artifacts

### OpenAPI Specifications

- [openapi/vanta-openapi.yml](openapi/vanta-openapi.yml) - Vanta Management API (users, vulnerabilities, controls, vendors, resources, integrations)
- [openapi/vanta-auditor-openapi.yml](openapi/vanta-auditor-openapi.yml) - Vanta Auditor API (audit data access for audit firms)

### Spectral Rules

- [rules/vanta-rules.yml](rules/vanta-rules.yml) - API linting rules enforcing Vanta conventions

### Naftiko Capabilities

- [capabilities/shared/vanta-api.yaml](capabilities/shared/vanta-api.yaml) - Shared per-API capability definition
- [capabilities/compliance-management.yaml](capabilities/compliance-management.yaml) - Compliance management workflow (14 tools)

### JSON Schema

- [json-schema/vanta-vulnerability-schema.json](json-schema/vanta-vulnerability-schema.json)
- [json-schema/vanta-vendor-schema.json](json-schema/vanta-vendor-schema.json)
- [json-schema/vanta-control-schema.json](json-schema/vanta-control-schema.json)

### JSON Structure

- [json-structure/vanta-vulnerability-structure.json](json-structure/vanta-vulnerability-structure.json)
- [json-structure/vanta-vendor-structure.json](json-structure/vanta-vendor-structure.json)

### JSON-LD Context

- [json-ld/vanta-context.jsonld](json-ld/vanta-context.jsonld)

### Examples

- [examples/vanta-list-vulnerabilities-example.json](examples/vanta-list-vulnerabilities-example.json)
- [examples/vanta-list-controls-example.json](examples/vanta-list-controls-example.json)
- [examples/vanta-create-vendor-example.json](examples/vanta-create-vendor-example.json)
- [examples/vanta-list-computers-example.json](examples/vanta-list-computers-example.json)

### Vocabulary

- [vocabulary/vanta-vocabulary.yml](vocabulary/vanta-vocabulary.yml)

## Key Concepts

- **Frameworks**: SOC 2, ISO 27001, HIPAA, PCI DSS, GDPR compliance standards
- **Controls**: Security requirements within frameworks, automatically tested
- **Vulnerabilities**: Security weaknesses tracked with CVSS severity and SLA deadlines
- **Vendors**: Third-party security reviews with risk levels and DPA tracking
- **Connectors**: Custom integrations pushing data from external systems

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com

---
*Profiled: 2026-05*
