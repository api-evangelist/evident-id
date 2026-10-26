# Evident (evident-id)

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
