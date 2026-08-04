# National Bank of Canada (national-bank-of-canada)

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

National Bank of Canada (Banque Nationale du Canada, TSX: NA) is a Schedule I chartered bank headquartered in Montreal, Quebec, founded in 1859. It is the sixth-largest of Canada's Big Six banks and the leading bank in Quebec, serving personal, commercial, wealth-management, and financial-markets clients. On open finance, National Bank is a first-mover — the first major Canadian bank to launch a secure, consent-based data-sharing API for retail customers — but it does **not** operate a public self-serve first-party developer portal.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/national-bank-of-canada/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/national-bank-of-canada/refs/heads/main/apis.yml)

## Open-Finance Posture (Honest Assessment)

Canada has **no operational open-banking mandate**. The federal Consumer-Driven Banking framework (Budget 2024 / Fall Economic Statement 2024, with FCAC oversight) is legislated but not yet live, so access today is voluntary and fragmented.

For National Bank specifically:

- **No first-party public developer portal.** `developer.nbc.ca`, `api.nbc.ca`, and similar hosts do not resolve. There is no public self-serve API console or downloadable OpenAPI/Swagger.
- **Aggregator-mediated data access.** Consumer financial-data sharing is consent-based and delivered through aggregators, principally **Flinks** — the Montreal aggregator in which National Bank holds an ~80% stake — via its **Open Banking Environment (OBE)**, and also through **Plaid**. Customers are redirected to National Bank to authenticate and grant consent; data is then shared over a secure, FDX-aligned feed. Fintechs onboard through the aggregator's accreditation process, not a National Bank developer console.
- **FDX participant.** National Bank and Flinks are founding participants of the FDX Canada working group, aligning data-sharing on the FDX technical standard.
- **Consumer-Driven Banking (CDB).** National Bank has publicly positioned itself ahead of Canada's forthcoming consumer-driven banking framework. No framework endpoint exists yet — the framework is not operational.

## Tags

- Financial Services
- Banking
- Canada
- Big Six
- Open Banking
- Consumer-Driven Banking
- FDX
- Data Aggregation
- Payments

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

### National Bank Consumer Data Access (Aggregator-Mediated)

National Bank of Canada exposes no public, self-serve first-party developer API. Consumer financial-data access is consent-based and aggregator-mediated (Flinks OBE and Plaid), with fintech onboarding handled through the aggregator's accreditation process. No National Bank OpenAPI/Swagger is publicly downloadable.

- **Human URL:** [https://www.flinks.com/go/open-banking-api](https://www.flinks.com/go/open-banking-api)

#### Tags

- Open Banking
- Data Aggregation
- FDX
- Consumer-Driven Banking
- Flinks

#### Properties

- [Documentation](https://www.flinks.com/go/open-banking-api)
- [Data Access](https://docs.flinks.com)

## Common Properties

- [Website](https://www.nbc.ca/)
- [About](https://www.nbc.ca/about-us.html)
- [LinkedIn](https://www.linkedin.com/company/national-bank-of-canada)
- [Investor Relations](https://www.nbc.ca/about-us/investors.html)
- [Newsroom](https://www.nbc.ca/about-us/news-media/press-release.html)
- [Careers](https://emplois.bnc.ca/en_CA/careers)
- [Privacy Policy](https://www.nbc.ca/privacy-policy.html)
- [Terms of Service](https://www.nbc.ca/terms-of-use.html)
- [Data Access (Flinks Open Banking)](https://www.flinks.com/go/open-banking-api)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
