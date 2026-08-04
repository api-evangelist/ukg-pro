# UKG Pro (ukg-pro)

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

UKG Pro (formerly UltiPro) is an enterprise human capital management (HCM) suite from UKG that delivers payroll, core HR, benefits administration, talent management, recruiting, onboarding, performance, learning, and people analytics for mid-to-large organizations. The platform combines the legacy UltiPro HR/payroll product with UKG's workforce management capabilities and is positioned for HR teams that need a unified system of record. The UKG Pro REST API exposes HCM resources (people, benefits, payroll, talent) via tenant-specific endpoints authenticated with OAuth 2.0 Bearer tokens.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ukg-pro/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ukg-pro/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Human Capital Management
- HCM
- HR
- Payroll
- Benefits Administration
- Talent Management
- Workforce Management
- HRIS

## Timestamps

- **Created:** 2026-05-11
- **Modified:** 2026-05-11

## APIs

### UKG Pro HCM API

REST API for the UKG Pro HCM suite covering people, benefits, payroll, talent, recruiting, onboarding, and HR data. Hosted on tenant-specific hostnames with OAuth 2.0 Bearer token authentication obtained via the /api/authentication/access_token endpoint.

- **Human URL:** [https://developer.ukg.com/hcm/reference/welcome-to-the-ukg-pro-api](https://developer.ukg.com/hcm/reference/welcome-to-the-ukg-pro-api)
- **Base URL:** `https://<<tenantHostName>>/api`

#### Tags

- HCM
- HR
- Payroll
- Benefits
- Talent
- Recruiting

#### Properties

- [Documentation](https://developer.ukg.com/hcm)
- [API Reference](https://developer.ukg.com/hcm/reference/welcome-to-the-ukg-pro-api)
- [Authentication](https://developer.ukg.com/general/docs/authentication-and-authorization)
- [Postman Collection](collections/ukg-pro.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ukg-pro.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### UKG Pro WFM API

REST API for the UKG Pro Workforce Management product (Dimensions), covering punches, shifts, scheduling, accruals, timekeeping, attendance, and labor data.

- **Human URL:** [https://developer.ukg.com/wfm](https://developer.ukg.com/wfm)
- **Base URL:** `https://<<tenantHostName>>/api`

#### Tags

- Workforce Management
- Scheduling
- Time and Attendance
- Accruals

#### Properties

- [Documentation](https://developer.ukg.com/wfm)
- [API Reference](https://developer.ukg.com/wfm/reference)
- [Postman Collection](collections/ukg-pro.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ukg-pro.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### UKG People Fabric API

Unified data fabric API that exposes consolidated person, employment, and workforce data across UKG Pro and connected systems for analytics and integration use cases.

- **Human URL:** [https://developer.ukg.com/peoplefabric/reference/welcome-to-the-people-fabric-api](https://developer.ukg.com/peoplefabric/reference/welcome-to-the-people-fabric-api)
- **Base URL:** `https://<<tenantHostName>>/api`

#### Tags

- People Fabric
- Data Fabric
- Analytics

#### Properties

- [Documentation](https://developer.ukg.com/peoplefabric/reference/welcome-to-the-people-fabric-api)
- [Postman Collection](collections/ukg-pro.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ukg-pro.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/ultimatesoftware)
- [LinkedIn](https://www.linkedin.com/company/ukg)
- [Website](https://www.ukg.com/solutions/ukg-pro)
- [Developer  Portal](https://developer.ukg.com)
- [Documentation](https://developer.ukg.com)
- [Authentication](https://developer.ukg.com/general/docs/authentication-and-authorization)
- [Pricing](https://www.ukg.com/solutions/ukg-pro)
- [Support](https://www.ukg.com/support)
- [Community](https://community.ukg.com/)
- [Parent  Company](https://www.ukg.com/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
