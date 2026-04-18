# Adobe Lightroom (lightroom)

APIs for Adobe Lightroom cloud services, enabling developers to access and manipulate photos, albums, and metadata programmatically. The Lightroom APIs are also available as part of Adobe Firefly Services for AI-powered image editing operations such as auto tone, auto straighten, and preset application.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/lightroom/refs/heads/main/apis.yml)

## Tags:

 - Cloud Storage, Image Editing, Metadata, Photo Management, Photography

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-04-18

## APIs

### Lightroom Services API
Core partner API for accessing Lightroom cloud catalog data, albums, and assets. Partner applications authenticate Lightroom customers through Adobe Identity Management System using a standard OAuth 2.0 workflow.

**Human URL:** [https://developer.adobe.com/lightroom/lightroom-api-docs/](https://developer.adobe.com/lightroom/lightroom-api-docs/)

#### Tags:

 - Albums, Assets, Catalogs, Photos

#### Properties

- [Documentation](https://developer.adobe.com/lightroom/lightroom-api-docs/api/)
- [Authentication](https://developer.adobe.com/developer-console/docs/guides/authentication/)
- [GettingStarted](https://developer.adobe.com/lightroom/lightroom-api-docs/getting-started/)
- [ChangeLog](https://developer.adobe.com/lightroom/lightroom-api-docs/release-notes/)
- [OpenAPI](openapi/lightroom-services-openapi.yml)

### Adobe Lightroom API (Firefly Services)
AI-powered image editing API available through Adobe Firefly Services. Provides auto tone, auto straighten, preset application, and programmatic editing capabilities using REST endpoints.

**Human URL:** [https://developer.adobe.com/firefly-services/docs/lightroom/](https://developer.adobe.com/firefly-services/docs/lightroom/)

#### Tags:

 - AI, Auto Tone, Image Editing, Presets

#### Properties

- [Documentation](https://developer.adobe.com/firefly-services/docs/lightroom/)
- [GettingStarted](https://developer.adobe.com/firefly-services/docs/lightroom/getting_started/)
- [OpenAPI](openapi/lightroom-firefly-services-openapi.yml)

## Common Properties

- [Features](https://developer.adobe.com/firefly-services/docs/lightroom/)
- [UseCases](https://developer.adobe.com/lightroom/lightroom-api-docs/)
- [Integrations](https://developer.adobe.com/firefly-services/docs/lightroom/)
- [Documentation](https://developer.adobe.com/lightroom/lightroom-api-docs/)
- [Authentication](https://developer.adobe.com/developer-console/docs/guides/authentication/)
- [Console](https://developer.adobe.com/console)
- [SignUp](https://developer.adobe.com/console)
- [StatusPage](https://status.adobe.com/)
- [Blog](https://blog.developer.adobe.com/)
- [ChangeLog](https://developer.adobe.com/lightroom/lightroom-api-docs/release-notes/)
- [TermsOfService](https://www.adobe.com/legal/terms.html)
- [PrivacyPolicy](https://www.adobe.com/privacy/policy.html)
- [GitHubRepository](https://github.com/AdobeDocs/lightroom-public-apis)
- [GitHubOrganization](https://github.com/AdobeDocs)
- [SDK](https://developer.adobe.com/firefly-services/docs/lightroom/)

## OpenAPI

- [Lightroom Services OpenAPI](openapi/lightroom-services-openapi.yml)
- [Lightroom Albums OpenAPI](openapi/lightroom-albums-openapi.yml)
- [Lightroom Assets OpenAPI](openapi/lightroom-assets-openapi.yml)
- [Lightroom Catalog OpenAPI](openapi/lightroom-catalog-openapi.yml)
- [Lightroom Firefly Services OpenAPI](openapi/lightroom-firefly-services-openapi.yml)

## JSON Schema

| Schema | File |
|---|---|
| Album Schema | [json-schema/lightroom-album-schema.json](json-schema/lightroom-album-schema.json) |
| Asset Schema | [json-schema/lightroom-asset-schema.json](json-schema/lightroom-asset-schema.json) |
| Catalog Schema | [json-schema/lightroom-catalog-schema.json](json-schema/lightroom-catalog-schema.json) |
| Rendition Schema | [json-schema/lightroom-rendition-schema.json](json-schema/lightroom-rendition-schema.json) |
| Firefly Job Response Schema | [json-schema/lightroom-firefly-services-job-response-schema.json](json-schema/lightroom-firefly-services-job-response-schema.json) |
| Firefly Auto Tone Request Schema | [json-schema/lightroom-firefly-services-auto-tone-request-schema.json](json-schema/lightroom-firefly-services-auto-tone-request-schema.json) |

## JSON-LD

- [Lightroom Context](json-ld/lightroom-context.jsonld)
- [Albums Context](json-ld/lightroom-albums-context.jsonld)
- [Assets Context](json-ld/lightroom-assets-context.jsonld)
- [Catalog Context](json-ld/lightroom-catalog-context.jsonld)
- [Firefly Services Context](json-ld/lightroom-firefly-services-context.jsonld)
- [Services Context](json-ld/lightroom-services-context.jsonld)

## Vocabulary

- [Lightroom Vocabulary](vocabulary/lightroom-vocabulary.yaml)

## Rules

- [Spectral Rules](rules/lightroom-spectral-rules.yml)

## Capabilities

| Capability | Type | File |
|---|---|---|
| Photo Management | Workflow | [capabilities/photo-management.yaml](capabilities/photo-management.yaml) |
| Lightroom Services | Shared | [capabilities/shared/lightroom-services.yaml](capabilities/shared/lightroom-services.yaml) |
| Firefly Services | Shared | [capabilities/shared/firefly-services.yaml](capabilities/shared/firefly-services.yaml) |

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
