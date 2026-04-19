# Agricultural Marketing Service (agricultural-marketing-service)
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

### USDA AMS LMPRS API (Livestock Mandatory Price Reporting)
The Livestock Mandatory Price Reporting System (LMPRS) API provides programmatic access to federally mandated livestock price report data. No authentication is required. The LMPRS API covers cattle, hogs, lambs, and other livestock price reporting as required by the Livestock Mandatory Reporting Act.

**Human URL:** [https://mpr.datamart.ams.usda.gov/](https://mpr.datamart.ams.usda.gov/)

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
