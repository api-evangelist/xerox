# Xerox (xerox)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Xerox is a global technology company and document management leader providing printing, digital document management, and business process solutions. Xerox offers the Xerox Developer Program providing open, standards-based APIs for integration with ConnectKey multifunction printers, FreeFlow production printing, Managed Print Services (MPS), and the Xerox Public Print Service. The program provides SDKs, APIs, and tools for building custom printing applications, workflow integrations, and enterprise print management solutions.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/xerox/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/xerox/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Document Management
- Enterprise
- Fortune 500
- Managed Print Services
- Print Services
- Printing

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Xerox Public Print API

REST API for managing print jobs through the Xerox Public Print Service. Provides endpoints for job creation, status monitoring, site discovery, provider management, EULA handling, and print history. Requires authentication via xrxauth header, user-email, and appid for all secure calls. Supports location-based site search for finding nearby printers.

- **Human URL:** [https://publicprintapi.services.xerox.com/](https://publicprintapi.services.xerox.com/)
- **Base URL:** `https://publicprintapi.services.xerox.com/api/v1`

#### Tags

- Print Jobs
- Print Management
- Printing
- REST

#### Properties

- [Documentation](https://publicprintapi.services.xerox.com/)
- [OpenAPI](openapi/xerox-public-print-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/xerox-public-print.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/xerox-public-print.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Xerox Managed Print Services API

The Xerox MPS-API and Support Assistant API (SA-API) provide a secure common interface allowing third parties to access features in the Xerox hosted technology suite for managed print services. Based on standard Web Service technologies supporting fleet management, device monitoring, supply replenishment, and service request automation.

- **Human URL:** [https://www.xerox.com/en-us/about/developer-program](https://www.xerox.com/en-us/about/developer-program)

#### Tags

- Fleet Management
- Managed Print Services
- Monitoring
- Print Management

#### Properties

- [Documentation](https://www.xerox.com/en-us/about/developer-program)
- [Postman Collection](collections/xerox-public-print.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/xerox-public-print.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Xerox Extensible Interface Platform (EIP)

SDK and API framework for building custom applications that run directly on Xerox ConnectKey-enabled multifunction printers and compatible devices. Apps are deployed through the Xerox App Gallery and can integrate device capabilities including scanning, printing, and workflow automation. Includes the Xerox App Developer Kit for ConnectKey applications.

- **Human URL:** [https://www.xerox.com/en-us/about/developer-program](https://www.xerox.com/en-us/about/developer-program)

#### Tags

- App Development
- ConnectKey
- Multifunction Printer
- SDK

#### Properties

- [Documentation](https://www.xerox.com/en-us/about/developer-program)
- [App Gallery](https://appgallery.services.xerox.com)
- [Postman Collection](collections/xerox-public-print.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/xerox-public-print.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Xerox FreeFlow SDK

Software development kit for integrating with the Xerox FreeFlow production printing platform. Includes interfaces for Prepress, Press, Variable Information (VIPP), and Photo modules enabling custom workflow automation for high-volume production printing environments.

- **Human URL:** [https://www.xerox.com/en-us/about/developer-program](https://www.xerox.com/en-us/about/developer-program)

#### Tags

- FreeFlow
- Production Printing
- SDK
- VIPP

#### Properties

- [Documentation](https://www.xerox.com/en-us/about/developer-program)
- [Postman Collection](collections/xerox-public-print.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/xerox-public-print.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/xerox)
- [Website](https://www.xerox.com)
- [Developer Program](https://www.xerox.com/en-us/about/developer-program)
- [App Gallery](https://appgallery.services.xerox.com)
- [Developer Portal](https://developers.xerox-solutions.net)
- [Public Print A P I](https://publicprintapi.services.xerox.com/)
- [Terms of Service](https://www.xerox.com/en-us/about/legal)
- [Privacy Policy](https://www.xerox.com/en-us/about/privacy)
- [Contact](mailto:xerox.global.developer.program@xerox.com)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
