# Adobe Lightroom (lightroom)

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

APIs for Adobe Lightroom cloud services, enabling developers to access and manipulate photos, albums, and metadata programmatically. The Lightroom APIs are also available as part of Adobe Firefly Services for AI-powered image editing operations such as auto tone, auto straighten, and preset application.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/lightroom/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/lightroom/refs/heads/main/apis.yml)

## Tags

- Cloud Storage
- Image Editing
- Metadata
- Photo Management
- Photography

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Lightroom Services API

Core partner API for accessing Lightroom cloud catalog data, albums, and assets. Partner applications authenticate Lightroom customers through Adobe Identity Management System using a standard OAuth 2.0 workflow.

- **Human URL:** [https://developer.adobe.com/lightroom/lightroom-api-docs/](https://developer.adobe.com/lightroom/lightroom-api-docs/)

#### Tags

- Albums
- Assets
- Catalogs
- Photos

#### Properties

- [Documentation](https://developer.adobe.com/lightroom/lightroom-api-docs/api/)
- [Authentication](https://developer.adobe.com/developer-console/docs/guides/authentication/)
- [Getting Started](https://developer.adobe.com/lightroom/lightroom-api-docs/getting-started/)
- [Changelog](https://developer.adobe.com/lightroom/lightroom-api-docs/release-notes/)
- [OpenAPI](openapi/lightroom-services-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lightroom-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lightroom-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Adobe Lightroom API (Firefly Services)

AI-powered image editing API available through Adobe Firefly Services. Provides auto tone, auto straighten, preset application, and programmatic editing capabilities using REST endpoints.

- **Human URL:** [https://developer.adobe.com/firefly-services/docs/lightroom/](https://developer.adobe.com/firefly-services/docs/lightroom/)

#### Tags

- AI
- Auto Tone
- Image Editing
- Presets

#### Properties

- [Documentation](https://developer.adobe.com/firefly-services/docs/lightroom/)
- [Getting Started](https://developer.adobe.com/firefly-services/docs/lightroom/getting_started/)
- [OpenAPI](openapi/lightroom-firefly-services-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lightroom-firefly-services.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lightroom-firefly-services.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Features](https://developer.adobe.com/firefly-services/docs/lightroom/)
- [Use Cases](https://developer.adobe.com/lightroom/lightroom-api-docs/)
- [Integrations](https://developer.adobe.com/firefly-services/docs/lightroom/)
- [Documentation](https://developer.adobe.com/lightroom/lightroom-api-docs/)
- [Authentication](https://developer.adobe.com/developer-console/docs/guides/authentication/)
- [Console](https://developer.adobe.com/console)
- [Sign Up](https://developer.adobe.com/console)
- [Status Page](https://status.adobe.com/)
- [Blog](https://blog.developer.adobe.com/)
- [Changelog](https://developer.adobe.com/lightroom/lightroom-api-docs/release-notes/)
- [Terms of Service](https://www.adobe.com/legal/terms.html)
- [Privacy Policy](https://www.adobe.com/privacy/policy.html)
- [GitHub Repository](https://github.com/AdobeDocs/lightroom-public-apis)
- [GitHub Organization](https://github.com/AdobeDocs)
- [SDK](https://developer.adobe.com/firefly-services/docs/lightroom/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
