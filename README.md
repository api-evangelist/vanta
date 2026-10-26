# Vanta (vanta)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Vanta is a trust management platform that automates security compliance for frameworks including SOC 2, ISO 27001, HIPAA, PCI DSS, and GDPR. The Vanta API enables organizations to programmatically manage their compliance posture, automate security monitoring, manage vulnerabilities, track controls, manage vendors, and integrate with existing tools and workflows.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/vanta/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/vanta/refs/heads/main/apis.yml)

## Scope

- **Access:** 3rd-Party

## Tags

- Cybersecurity
- Compliance
- Security
- Governance
- Risk Management

## Timestamps

- **Created:** 2024-11-14
- **Modified:** 2026-05-19

## APIs

### Vanta API

The Vanta REST API enables programmatic access to compliance, security monitoring, vulnerability management, personnel management, vendor management, and custom integration capabilities. The API uses OAuth 2.0 authentication and returns JSON responses. Rate limits range from 5 to 250 requests per minute depending on endpoint category.

- **Human URL:** [https://developer.vanta.com/docs/vanta-api-overview](https://developer.vanta.com/docs/vanta-api-overview)
- **Base URL:** `https://api.vanta.com`

#### Tags

- Cybersecurity
- Compliance
- Security
- Governance
- Risk Management

#### Properties

- [Documentation](https://developer.vanta.com/docs/vanta-api-overview)
- [Authentication](https://developer.vanta.com/docs/api-access-setup)
- [F A Q](https://developer.vanta.com/docs/faq)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/vanta/refs/heads/main/openapi/vanta-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vanta-auditor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vanta-auditor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/vanta.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vanta.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Vanta Auditor API

The Vanta Auditor API provides external audit firms programmatic access to customer compliance data. Auditors can query audits, vendors, monitored computers, people, vulnerabilities, evidence, controls, and comments during audit engagements.

- **Human URL:** [https://developer.vanta.com/docs/vanta-api-overview](https://developer.vanta.com/docs/vanta-api-overview)
- **Base URL:** `https://api.vanta.com`

#### Tags

- Cybersecurity
- Compliance
- Audit
- Security

#### Properties

- [Documentation](https://developer.vanta.com/docs/vanta-api-overview)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/vanta/refs/heads/main/openapi/vanta-auditor-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/vanta-auditor.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vanta-auditor.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/vanta.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vanta.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/vanta-security)
- [Portal](https://developer.vanta.com/docs/vanta-api-overview)
- [Authentication](https://developer.vanta.com/docs/api-access-setup)
- [Getting Started](https://developer.vanta.com/docs/vanta-first-api-request)
- [Postman Collection](https://developer.vanta.com/docs/vanta-postman-setup) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [F A Q](https://developer.vanta.com/docs/faq)
- [Documentation](https://developer.vanta.com/docs/build-integrations)
- [Documentation](https://developer.vanta.com/docs/manage-vendors)
- [Blog](https://www.vanta.com/resources/introducing-vantas-connectors-api)
- [Product](https://www.vanta.com/products/vanta-api)
- [SDK](https://github.com/VantaInc/vanta-auditor-api-sdk-typescript)
- [SDK](https://github.com/VantaInc/vanta-auditor-api-sdk-java)
- [SDK](https://github.com/VantaInc/vanta-mcp-server)
- [SDK](https://github.com/VantaInc/eslint-plugin-vanta)
- [Schema](https://github.com/VantaInc/vanta-control-set)
- [Integration](https://www.vanta.com/integrations/github)
- [Changelog](https://www.vanta.com/resources/new-in-vanta-april-2026)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/vanta/refs/heads/main/openapi/vanta-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/vanta/refs/heads/main/openapi/vanta-auditor-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [L L Ms Txt](https://developer.vanta.com/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
