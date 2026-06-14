# SL Green Realty — GraphQL Schema

## Description

SL Green Realty Corp. (NYSE: SLG) is Manhattan's largest office landlord and a fully integrated real estate investment trust (REIT) focused on acquiring, managing, and maximizing the value of Manhattan commercial properties. The company operates approximately 39 properties totaling 25.3 million square feet as of fiscal year-end 2024.

SL Green publishes no public GraphQL API, no REST API, no developer portal, and no publicly documented programmable interface. Tenant-facing technology is delivered through third-party platforms (the "My Building" tenant portal, RequestCom, and ADP Workforce), none of which expose a programmable interface attributable to SL Green directly.

## Endpoint / Documentation URL

- No public GraphQL endpoint exists.
- Investor relations: https://slgreen.com/investors/
- Tenant portal: https://slgreen.com/my-building/
- Properties listing: https://slgreen.com/properties/

## GraphQL Support Notes

SL Green does not support GraphQL. This schema is a **conceptual data model** representing the core domain entities and relationships that would underpin a GraphQL API for a commercial REIT of this type. It is derived from:

- SL Green's public property and leasing data (slgreen.com)
- Standard commercial real estate (CRE) and REIT data models
- SEC 10-K filings (CIK 0001040971) disclosing portfolio, financial, and occupancy data
- LEED and sustainability certification structures common to Class A Manhattan office towers

The schema covers: property and building hierarchies, floor and suite layouts, leasing and tenant relationships, occupancy metrics, transaction records, amenity classifications, green certifications, investor relations data, financial summaries (NOI, cap rate, dividends), portfolio and market/submarket structures.

## Key Domain Concepts

| Type | Description |
|------|-------------|
| Property | A discrete real estate asset in the SL Green portfolio |
| Building | Physical building structure within or comprising a property |
| Floor | Individual floor within a building |
| Suite | Leasable unit on a floor |
| Lease | Legal agreement between SL Green and a tenant |
| Tenant | Commercial tenant occupying one or more suites |
| Occupancy | Point-in-time occupancy metric for a building or portfolio |
| Transaction | Acquisition, disposition, or joint-venture transaction |
| Contact | Named contact (leasing broker, property manager, IR contact) |
| AmenityLevel | Classification of building amenity tier |
| CertificationLevel | Sustainability/energy certification level (e.g., LEED Platinum) |
| GreenInitiative | ESG or sustainability program element |
| InvestorRelations | IR events, filings, and communications |
| FinancialSummary | Period financial roll-up for the portfolio or a property |
| Dividend | Quarterly or special dividend declaration |
| NOI | Net Operating Income figure for a property or portfolio |
| CapRate | Capitalization rate for a property or transaction |
| Portfolio | Aggregated view of the full SL Green asset base |
| Market | Top-level geographic market (e.g., Manhattan) |
| Submarket | Manhattan submarket (e.g., Grand Central, Times Square, Plaza) |
