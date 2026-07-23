# National Bank of Canada (national-bank-of-canada)

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
