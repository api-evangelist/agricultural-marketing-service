# Agricultural Marketing Service (agricultural-marketing-service)

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

The Agricultural Marketing Service (AMS), an agency of the United States Department of Agriculture (USDA), oversees programs in five commodity areas: cotton and tobacco, dairy, fruits and vegetables, livestock and seeds, and poultry. AMS provides testing, standardization, grading, and market news services. AMS operates several public APIs for agricultural market data including the Market Analysis Reporting System (MARS) API for real-time commodity market news and the Livestock Mandatory Price Reporting System (LMPRS) API for livestock price data.

**URL:** [https://www.ams.usda.gov/](https://www.ams.usda.gov/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Agriculture, Federal Government, Market News, Livestock, Dairy, Fruits And Vegetables, Cotton, Tobacco

## Timestamps

- **Created:** 2024-11-21
- **Modified:** 2026-04-19

## APIs

### USDA AMS MARS API (MyMarketNews)
The Market Analysis Reporting System (MARS) API provides programmatic access to USDA AMS agricultural market news data. The API allows users to automatically pull raw market news data including commodity prices, volume, and trade reports across livestock, dairy, fruits, vegetables, grains, and other agricultural commodities. No API key is required for basic access; registered users can obtain an API key for higher rate limits.

**Human URL:** [https://mymarketnews.ams.usda.gov/mymarketnews-api](https://mymarketnews.ams.usda.gov/mymarketnews-api)

#### Tags:

 - Market News, Commodity Prices, Agriculture, Livestock, Dairy, Fruits And Vegetables

#### Properties

- [Documentation](https://mymarketnews.ams.usda.gov/mymarketnews-api)
- [Getting Started](https://mymarketnews.ams.usda.gov/mars-api/getting-started)
- [Authentication](https://mymarketnews.ams.usda.gov/mymarketnews-api/authentication)
- [OpenAPI](openapi/agricultural-marketing-service-mars-api.yaml)
- [Report Schema](json-schema/mars-api-report-schema.json)
- [Report Data Schema](json-schema/mars-api-report-data-schema.json)
- [Office Schema](json-schema/mars-api-office-schema.json)
- [Report Structure](json-structure/mars-api-report-structure.json)
- [Report Data Structure](json-structure/mars-api-report-data-structure.json)
- [JSON-LD Context](json-ld/agricultural-marketing-service-mars-api-context.jsonld)


#### Tags:

 - Livestock, Price Reporting, Cattle, Hogs, Agriculture

#### Properties

- [LMPRS API User Guide](https://www.ams.usda.gov/sites/default/files/media/USDA_LMPRS_API_User_Guide.pdf)
- [Data API](https://mpr.datamart.ams.usda.gov/)

### USDA Local Food Directories API
The USDA Local Food Directories API provides data sharing access to directory information for farmers markets, food hubs, on-farm markets, community supported agriculture (CSA) operations, and food cooperatives across the United States.

**Human URL:** [https://www.usdalocalfoodportal.com/fe/datasharing/](https://www.usdalocalfoodportal.com/fe/datasharing/)

#### Tags:

 - Local Food, Farmers Markets, Food Hubs, CSA, Agriculture

#### Properties

- [Documentation](https://www.usdalocalfoodportal.com/fe/datasharing/)
- [Data API](https://www.usdalocalfoodportal.com/api/)

## Common Properties

- [Website](https://www.ams.usda.gov/)
- [APIs and Open Data Portal](https://www.ams.usda.gov/resources/apis-open-data)
- [GitHub Organization](https://github.com/usda)
- [Terms of Service](https://www.usda.gov/policies-and-links)
- [Privacy Policy](https://www.usda.gov/privacy-policy)

## Features

| Name | Description |
|------|-------------|
| No Authentication Required | The MARS and LMPRS APIs are publicly accessible without authentication; registered users can obtain API keys for higher rate limits. |
| JSON Data Format | All API responses are returned in JSON format including errors and paginated results. |
| Real-Time Market News | MARS API provides up-to-date commodity price and volume data as reports are released by AMS market reporters. |
| Historical Data Access | Access up to 180 days of historical market data per request with up to 100,000 records returned per call. |
| Commodity Coverage | Market data covers livestock, dairy, fruits, vegetables, grains, cotton, tobacco, poultry, and other agricultural commodities. |
| Mandatory Price Reporting | LMPRS API provides federally mandated livestock price data under the Livestock Mandatory Reporting Act. |

## Use Cases

| Name | Description |
|------|-------------|
| Agricultural Price Monitoring | Track commodity prices across livestock, dairy, fruits, and vegetables to support trading, purchasing, and production decisions. |
| Market Analysis and Research | Pull historical and current market news data for academic research, economic analysis, and policy work. |
| Supply Chain Integration | Integrate USDA market news data into supply chain management and procurement systems for real-time pricing. |
| Local Food System Mapping | Use the Local Food Directories API to locate and integrate data about farmers markets, CSAs, and food hubs. |
| Commodity Price Alerts | Build automated price monitoring systems using the MARS API to trigger alerts when prices cross defined thresholds. |

## Integrations

| Name | Description |
|------|-------------|
| Microsoft Excel | USDA AMS provides guides for integrating MARS API data directly into Microsoft Excel for market analysis. |
| api.data.gov | AMS APIs are accessible through the federal api.data.gov gateway for consistent API key management. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [USDA AMS MARS API](openapi/agricultural-marketing-service-mars-api.yaml)

### JSON Schema

- [Report Schema](json-schema/mars-api-report-schema.json)
- [Reports List Response Schema](json-schema/mars-api-reports-list-response-schema.json)
- [Report Data Schema](json-schema/mars-api-report-data-schema.json)
- [Report Data Response Schema](json-schema/mars-api-report-data-response-schema.json)
- [Office Schema](json-schema/mars-api-office-schema.json)
- [Offices List Response Schema](json-schema/mars-api-offices-list-response-schema.json)
- [Pagination Stats Schema](json-schema/mars-api-pagination-stats-schema.json)
- [Error Response Schema](json-schema/mars-api-error-response-schema.json)

### JSON Structure

- [Report Structure](json-structure/mars-api-report-structure.json)
- [Report Data Structure](json-structure/mars-api-report-data-structure.json)
- [Office Structure](json-structure/mars-api-office-structure.json)
- [Error Response Structure](json-structure/mars-api-error-response-structure.json)

### JSON-LD

- [MARS API Context](json-ld/agricultural-marketing-service-mars-api-context.jsonld)

## Vocabulary

- [Agricultural Marketing Service Vocabulary](vocabulary/agricultural-marketing-service-vocabulary.yaml) — Unified taxonomy mapping 2 resources, 2 actions, 0 workflows, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Agricultural Marketing Service Spectral Rules](rules/agricultural-marketing-service-spectral-rules.yml) — 22 rules across 9 categories enforcing USDA AMS API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
