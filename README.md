# CharmHealth (charmhealth)

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
