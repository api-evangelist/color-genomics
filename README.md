# Color Health (color-genomics)

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

Color Health (founded as **Color Genomics** in 2015, Burlingame, CA) is a population
health technology company that operates a nationwide, oncologist-led **Virtual Cancer
Clinic** and delivers population-scale precision health programs - hereditary cancer
and cardiovascular genetic testing, pharmacogenomics, cancer early detection and
screening, and clinical care management - for **employers, labor unions, health plans,
governments, and public health institutions**.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/color-genomics/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/color-genomics/refs/heads/main/apis.yml)

## Access model - no public developer API

> **Important:** Color Health does **not** publish a public, self-service developer
> API. There is no developer portal, no `api.color.com` / `developers.color.com`, no
> published REST/GraphQL reference, and no SDKs. This entry documents the provider
> honestly as an **enterprise/partner-gated** platform.

- **Gated / contracted.** Color contracts programs directly with sponsoring
  organizations (B2B and B2G). There is no public sign-up for API credentials.
- **Pricing is contact-sales.** No pricing is published; it is negotiated per program
  with the sponsoring organization. There is no self-service plan, rate-limit, or
  FinOps surface to document, so none was fabricated.
- **Interoperability via partners.** Clinical data exchange with health systems and
  EHRs is brokered through interoperability partners such as
  [Redox](https://www.redoxengine.com/healthcare-product/color/) using **FHIR/HL7**,
  not an open Color endpoint.
- **Open source is tooling only.** Color's GitHub org ([github.com/color](https://github.com/color),
  ~41 repos) holds bioinformatics/genomics tools (`cnvkit`, `clrsvsim`,
  `hisat-genotype`, `aldy`, `risk-models`) and internal utilities - not a product API,
  SDK, or client library. Most are archived.

## Modeled APIs

The APIs below are **logical, honestly-modeled surfaces** (`endpointsModeled: true`)
describing how a Color population health program is typically integrated. They are
**not confirmed public endpoints**, and no OpenAPI, Postman, plans, rate-limit, or
FinOps artifacts were fabricated for them.

- **Color Orders & Kits API (Modeled)** - place and track genetic test orders and
  sample-collection kits for participants.
- **Color Results API (Modeled)** - retrieve clinical genetic test results and reports
  (hereditary cancer, cardiovascular, pharmacogenomics).
- **Color Members & Participants API (Modeled)** - enroll and manage the members of an
  employer, union, or public-health population.
- **Color Programs API (Modeled)** - configure and report on population health programs
  (screening campaigns, risk-based care pathways, aggregate outcomes).
- **Color Clinical Data API (Modeled)** - exchange clinical data with a health system's
  EHR; in practice handled via FHIR/HL7 through Redox.

## Tags

- Health
- Genomics
- Genetic Testing
- Precision Health
- Population Health
- Cancer Screening
- Clinical
- Enterprise
- Gated

## Timestamps

- **Created:** 2026-07-05
- **Modified:** 2026-07-05

## Common Properties

- [Website](https://www.color.com/)
- [LinkedIn](https://www.linkedin.com/company/color)
- [GitHub Organization](https://github.com/color)
- [Interoperability (Redox)](https://www.redoxengine.com/healthcare-product/color/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
