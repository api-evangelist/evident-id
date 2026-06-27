# Evident (evident-id)

Evident (Evident ID) is an identity and credential verification platform that lets businesses verify identity, background, certifications, licenses, and insurance (Certificate of Insurance / COI) on third parties through a single REST API. Its VerifyAPI and SubmitAPI orchestrate verification requests across thousands of attributes and authoritative data sources, returning fact-checked results with webhook notifications.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/evident-id/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/evident-id/refs/heads/main/apis.yml)

## Tags

- Identity Verification
- Credential Verification
- Background Check
- Insurance Verification
- COI

## Timestamps

- **Created:** 2026-06-25
- **Modified:** 2026-06-25

## APIs

### Evident Verification Requests API

VerifyAPI is a RESTful JSON API for creating a verification request and retrieving information about an existing request. A request is composed of one or more requested attributes describing what should be verified about an individual or business.

- **Human URL:** [https://www.evidentid.com/api-documentation-developers/](https://www.evidentid.com/api-documentation-developers/)
- **Base URL:** `https://verify.api.evidentid.com/api/v1`

#### Tags

- Verification
- Requests
- VerifyAPI

#### Properties

- [Documentation](https://www.evidentid.com/api-documentation-developers/)
- [API Reference](https://docs.evidentid.com/v1)
- [OpenAPI](openapi/evident-id-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/evident-id.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/evident-id.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Evident Attributes & Credentials API

SubmitAPI accepts the personal data and credentials needed to satisfy a verification request (for example name and certificate number for a certification attribute), authenticated with the userIdentityToken bearer token returned by VerifyAPI.

- **Human URL:** [https://www.evidentid.com/api-documentation-developers/](https://www.evidentid.com/api-documentation-developers/)
- **Base URL:** `https://submit.api.evidentid.com/api/v1`

#### Tags

- Attributes
- Credentials
- Submission

#### Properties

- [Documentation](https://www.evidentid.com/api-documentation-developers/)
- [API Reference](https://docs.evidentid.com/v1)
- [OpenAPI](openapi/evident-id-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/evident-id.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/evident-id.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Evident Identity Assurance API

Identity, background, and credential assurance expressed as verifiable attributes - the platform can verify thousands of attributes about an individual drawn from authoritative data sources through a single API.

- **Human URL:** [https://www.evidentid.com/api-documentation-developers/](https://www.evidentid.com/api-documentation-developers/)
- **Base URL:** `https://verify.api.evidentid.com/api/v1`

#### Tags

- Identity
- Assurance
- Background Check

#### Properties

- [Documentation](https://www.evidentid.com/api-documentation-developers/)
- [API Reference](https://docs.evidentid.com/v1)
- [OpenAPI](openapi/evident-id-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/evident-id.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/evident-id.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Evident Insurance & COI Verification API

Insurance, contract, and Certificate of Insurance (COI) verification modeled as verification-request attributes, enabling automated checks of coverage and credentials on suppliers and third parties.

- **Human URL:** [https://www.evidentid.com/api-documentation-developers/](https://www.evidentid.com/api-documentation-developers/)
- **Base URL:** `https://verify.api.evidentid.com/api/v1`

#### Tags

- Insurance
- COI
- Certificate of Insurance

#### Properties

- [Documentation](https://www.evidentid.com/api-documentation-developers/)
- [API Reference](https://docs.evidentid.com/v1)
- [OpenAPI](openapi/evident-id-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/evident-id.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/evident-id.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Evident Results API

Retrieve the status and results of a verification request. Each requested attribute is paired with a result object carrying a status, type, and a values array whose first value reflects the most recent fact-checked submission.

- **Human URL:** [https://www.evidentid.com/api-documentation-developers/](https://www.evidentid.com/api-documentation-developers/)
- **Base URL:** `https://verify.api.evidentid.com/api/v1`

#### Tags

- Results
- Status
- Reports

#### Properties

- [Documentation](https://www.evidentid.com/api-documentation-developers/)
- [API Reference](https://docs.evidentid.com/v1)
- [OpenAPI](openapi/evident-id-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/evident-id.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/evident-id.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Evident Webhooks API

Webhook callbacks notify your server of request lifecycle events - rpRequestCreated, rpRequestSubmissionCompleted, rpRequestCompleted, rpRequestTimeout, and notificationFailure - each payload carrying an eventType and the rpRequestId.

- **Human URL:** [https://www.evidentid.com/api-documentation-developers/](https://www.evidentid.com/api-documentation-developers/)
- **Base URL:** `https://verify.api.evidentid.com/api/v1`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://www.evidentid.com/api-documentation-developers/)
- [API Reference](https://docs.evidentid.com/v1)
- [OpenAPI](openapi/evident-id-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/evident-id.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/evident-id.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/evidentid)
- [LinkedIn](https://www.linkedin.com/company/evident-id)
- [Website](https://www.evidentid.com)
- [Documentation](https://docs.evidentid.com/v1)
- [Plans](plans/evident-id-plans-pricing.yml)
- [Rate Limits](rate-limits/evident-id-rate-limits.yml)
- [Fin Ops](finops/evident-id-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
