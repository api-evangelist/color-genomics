# Color Health (color-genomics)

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
