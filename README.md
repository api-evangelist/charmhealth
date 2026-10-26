# CharmHealth (charmhealth)

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

CharmHealth is a healthcare technology platform offering Electronic Health Records (EHR), Practice Management, Revenue Cycle Management, Patient Engagement, and TeleHealth tooling. CharmHealth exposes an HL7 FHIR R4 API conformant to the US Core Implementation Guide that lets third-party applications query patient medical records, manage clinical resources, and integrate with the EHR using SMART on FHIR OAuth 2.0 authorization.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/charmhealth/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/charmhealth/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- EHR
- EMR
- FHIR
- Healthcare
- HL7
- Patient Engagement
- Patients
- SMART on FHIR
- US Core

## Timestamps

- **Created:** 2025-02-21
- **Modified:** 2026-05-19

## APIs

### CharmHealth FHIR API

CharmHealth EHR FHIR API conforms to FHIR R4 (4.0.1) and the US Core STU 3.1.1 Implementation Guide. It supports 30+ FHIR resources covering clinical (AllergyIntolerance, Condition, Procedure, Immunization, MedicationRequest), care coordination (CarePlan, CareTeam, Goal, Encounter), administrative (Patient, Practitioner, Organization, Location, Appointment), diagnostic (DiagnosticReport, Observation), and documentation resources (DocumentReference, QuestionnaireResponse, Provenance). Authentication uses SMART on FHIR with OAuth 2.0 authorization code flow, PKCE for public clients, and JWT-assertion backend services authorization for system access.

- **Human URL:** [https://www.charmhealth.com/resources/fhir/index.html](https://www.charmhealth.com/resources/fhir/index.html)
- **Base URL:** `https://ehr2.charmtracker.com/api/ehr/v2/fhir`

#### Tags

- FHIR
- HL7
- Healthcare
- SMART on FHIR
- US Core

#### Properties

- [Documentation](https://www.charmhealth.com/resources/fhir/index.html)
- [Authentication](https://www.charmhealth.com/resources/fhir/authorization.html)
- [S M A R T On F H I R](https://www.charmhealth.com/resources/fhir/smart-on-fhir.html)
- [Bulk Export](https://www.charmhealth.com/resources/fhir/bulk-data.html)
- [U S Core](https://www.hl7.org/fhir/us/core/)
- [OpenAPI](openapi/charmhealth-fhir-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/charmhealth-fhir-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/charmhealth-fhir-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Spectral Rules](spectral/charmhealth-spectral.yml) — [Spectral](https://docs.stoplight.io/docs/spectral)

## Common Properties

- [GitHub Organization](https://github.com/CharmHealth)
- [LinkedIn](https://www.linkedin.com/company/charmhealth)
- [Website](https://www.charmhealth.com/)
- [Documentation](https://www.charmhealth.com/resources/fhir/index.html)
- [Developer](https://www.charmhealth.com/developer/)
- [News](https://www.charmhealth.com/ehr/ehr-trade-shows.html)
- [Press Releases](https://www.charmhealth.com/ehr/press-release.html)
- [Case Studies](https://casestudy.charmhealth.com/charmhealth-case-study-landing-page/)
- [Blog](https://www.charmhealth.com/blog/)
- [Newsletter](https://www.charmhealth.com/newsletter/)
- [Webinars](https://www.charmhealth.com/ehr/webinar.html)
- [Pricing](https://www.charmhealth.com/ehr/ehr-pricing.html)
- [Support](https://www.charmhealth.com/support/)
- [Terms of Service](https://www.charmhealth.com/ehr/termsofservice.html)
- [Privacy Policy](https://www.charmhealth.com/privacy-policy.html)
- [JSON-LD](json-ld/charmhealth-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/charmhealth-patient-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/charmhealth-observation-schema.json) — [JSON Schema](https://json-schema.org/specification)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
