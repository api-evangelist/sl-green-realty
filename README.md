# SL Green Realty Corp.

SL Green Realty Corp. (NYSE: **SLG**) is, in the company's own words on
[slgreen.com](https://slgreen.com), *"Manhattan's largest office landlord, a
fully integrated real estate investment trust, or REIT, that is focused
primarily on acquiring, managing and maximizing the value of Manhattan
commercial properties."* Founded in 1997 by **Stephen L. Green** as the
successor to S.L. Green Properties (established 1980) and headquartered in
New York City, SL Green is led by Chairman & CEO **Marc Holliday**.

As of fiscal year-end 2024 the company reported **39 properties** totaling
approximately **25.3 million square feet**, **US$886M** in revenue, **US$10.47B**
in total assets, and **1,221 employees**.

This repository is an API Evangelist profile of the company. **SL Green
publishes no public developer APIs, OpenAPI specs, SDKs, developer portal,
GitHub organization, or sandbox.** Its tenant-facing technology surface is
delivered through third-party platforms — the *"My Building"* tenant portal,
RequestCom for building services, and ADP Workforce for recruitment. This
profile documents the REIT, its portfolio, leadership, and verified absence
of a public API footprint.

## Corporate Facts

| Fact | Value |
|---|---|
| Legal name | SL Green Realty Corp. |
| Founded | 1997 (successor to S.L. Green Properties, est. 1980) |
| Founder | Stephen L. Green |
| Chairman & CEO | Marc Holliday |
| Headquarters | New York, NY, USA |
| Stock exchange / ticker | NYSE: SLG |
| SEC CIK | 0001040971 |
| Entity type | Real Estate Investment Trust (REIT) |
| Geographic focus | Manhattan, New York City |
| Properties (FY 2024) | 39 |
| Portfolio square footage (FY 2024) | 25,297,353 sq ft |
| 2024 revenue | US$886 million |
| 2024 net income | US$30 million |
| 2024 total assets | US$10.470 billion |
| 2024 total equity | US$3.951 billion |
| Employees (2024) | 1,221 |

## Flagship & Notable Properties

| Property | Address | Notes |
|---|---|---|
| **One Vanderbilt** | 1 Vanderbilt Avenue (42nd & Vanderbilt) | 1,401 ft, 62 stories, 1.75M sq ft, opened 2020-09-14, cost US$3.31B. Anchor tenant TD Bank. Home to **Summit One Vanderbilt** observation deck (1,020 ft) and Daniel Boulud's Le Pavillon. Co-owned with National Pension Service of Korea, Hines, Mori Building Co. Fully leased late 2024. |
| **One Madison Avenue** | Madison Square Park | Winner of the **2026 ULI Award for Excellence in Office Development**. |
| 1515 Broadway | Times Square | Site of proposed Caesars Palace Times Square casino-hotel-entertainment complex. |
| 1185 Avenue of the Americas | Midtown | Included in the Caesars Palace Times Square redevelopment scope. |
| 420 Lexington Avenue (Graybar Building) | Midtown East / Grand Central | |
| 800 Third Avenue | Midtown East | |
| 825 Eighth Avenue (Worldwide Plaza) | Midtown West / Times Square | |
| 1350 Avenue of the Americas | Midtown | |
| 15 Laight Street | Tribeca | |
| Pershing Square Building | 125 Park Avenue | |
| 461 Fifth Avenue | Midtown | |
| 810 Seventh Avenue | Midtown West | |
| 919 Third Avenue | Midtown East | |
| Random House Tower | 1745 Broadway | |

## Manhattan Submarkets Covered

Grand Central · Midtown South / Chelsea · Plaza District · Downtown ·
Westside · Midtown West · Times Square · Park Avenue South / Flatiron ·
Penn Station.

## Caesars Palace Times Square Joint Venture

SL Green leads the joint venture proposing **Caesars Palace Times Square**,
a casino-hotel-entertainment complex at 1515 Broadway with adjacent
1185 Avenue of the Americas redevelopment, in partnership with **Caesars
Entertainment** and **Roc Nation**. The proposal is pending issuance of one
of three downstate commercial gaming licenses by the **New York State
Gaming Facility Location Board** (status as of May 2026).

## Business Divisions

Leasing · Finance · Investments · Construction · Development · Hospitality ·
Property Management · Security & Life Safety · Sustainability · Technology.

## API Surface Assessment

| Surface | Status |
|---|---|
| Public developer portal | None |
| Public OpenAPI / AsyncAPI specs | None |
| Public REST / GraphQL APIs | None |
| SDKs / CLIs | None |
| GitHub public repositories | No SL Green GitHub organization found |
| Status page / changelog | None public |
| Sandbox / Console | None |
| Tenant technology surface | Vendor-mediated (*"My Building"* portal, RequestCom, ADP Workforce) |
| API Evangelist tier | **Tier 3 — no-apis**; REIT with no programmable public surface |

## Artifacts in this Repository

| Path | Description |
|---|---|
| [`apis.yml`](./apis.yml) | apis.yml 0.19 index — corporate facts, flagship properties, divisions, submarkets, Caesars JV, API-surface assessment |
| [`vocabulary/sl-green-realty-vocabulary.yml`](./vocabulary/sl-green-realty-vocabulary.yml) | Domain vocabulary covering the REIT, portfolio, divisions, partners, regulators, scale metrics |
| [`json-ld/sl-green-realty-context.jsonld`](./json-ld/sl-green-realty-context.jsonld) | JSON-LD context modelling SL Green as `schema:Corporation` / `slg:REIT` with properties, divisions, and the Caesars JV |

No `openapi/`, `asyncapi/`, `capabilities/`, `rules/`, `json-schema/`,
`examples/`, `plans/`, `rate-limits/`, or `finops/` artifacts are produced
for this repository — there is no API surface to back them, and the
pipeline rule is to avoid empty/placeholder specs.

## Key Sources

- Corporate site: <https://slgreen.com>
- About: <https://slgreen.com/about/>
- Properties: <https://slgreen.com/properties/>
- Investor relations: <https://slgreen.com/investors/>
- SEC EDGAR (CIK 0001040971): <https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0001040971&type=10-K>
- Wikipedia: SL Green Realty: <https://en.wikipedia.org/wiki/SL_Green_Realty>
- Wikipedia: One Vanderbilt: <https://en.wikipedia.org/wiki/One_Vanderbilt>

## Maintainer

[Kin Lane](mailto:kin@apievangelist.com) — [API Evangelist](https://apievangelist.com).
