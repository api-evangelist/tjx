# TJX Companies (tjx)

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

The TJX Companies, Inc. is an American multinational off-price department store corporation headquartered in Framingham, Massachusetts, ranked No. 80 on the 2024 Fortune 500 list. Operating over 4,800 stores across nine countries and three continents under brands including T.J. Maxx, Marshalls, HomeGoods, Sierra, HomeSense (US), and Winners, HomeSense, Marshalls (Canada), TJX provides supplier and vendor integration through EDI and web-based portal platforms. Supplier connectivity is handled via Oracle iSupplier, SupplierOne, and the DiCentral ASN Vendor Portal, supporting purchase orders, advanced shipping notices, invoicing, and payment tracking.

**URL:** [https://www.tjx.com/](https://www.tjx.com/)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Retail, Off-Price, Fortune 100, Supply Chain, EDI

## Timestamps

- **Created:** 2024-11-27
- **Modified:** 2026-05-03

## APIs


#### Tags:

 - Supplier Portal, Oracle, Invoicing, Purchase Orders

#### Properties

- [Documentation](https://www.tjx.com/mytjx/supplier/files/iSupplier-User-Guide-EN.pdf)

### TJX EDI Integration
TJX Companies requires EDI compliance for all resale vendors, supporting purchase orders (850), purchase order acknowledgements (855), advanced shipping notices (856), invoices (810), motor carrier load tender (204), response to load tender (990), and transportation carrier shipment status (214). Integration is available through approved EDI service providers including SPS Commerce, DiCentral, Zenbridge, and others.

**Human URL:** [https://www.spscommerce.com/network/find-a-partner/view/the-tjx-companies-inc/](https://www.spscommerce.com/network/find-a-partner/view/the-tjx-companies-inc/)

#### Tags:

 - EDI, Supply Chain, Vendors

#### Properties

- [Documentation](https://www.spscommerce.com/network/find-a-partner/view/the-tjx-companies-inc/)


#### Tags:

 - ASN, Shipping, Vendors, DiCentral

#### Properties

- [Documentation](https://diweb.dicentral.com/tjx/SignUp/GetStarted.aspx)


#### Tags:

 - Supplier Diversity, Vendors, Registration

#### Properties

- [Documentation](https://tjx.supplierone.co/)

## Common Properties

- [Website](https://www.tjx.com/)
- [Documentation](https://www.tjx.com/mytjx/supplier/supplier.html)
- [Portal](https://www.mytjx.com/mytjx/supplier.html)
- [GitHubOrganization](https://github.com/TJX)

## Features

| Name | Description |
|------|-------------|
| Oracle iSupplier Portal | Web-based supplier self-service for invoice tracking, payment status, deduction management, and purchase order visibility. |
| EDI Vendor Integration | Electronic Data Interchange compliance for purchase orders (850), ASNs (856), invoices (810), and related transactions for resale suppliers. |
| ASN Vendor Portal | DiCentral-powered portal for creating and submitting advance shipping notices and managing compliance. |
| SupplierOne Diversity Registration | Supplier diversity portal for diverse supplier registration, certification, and Tier II reporting. |
| Transcepta Electronic Invoicing | Digital invoice submission via Transcepta integration, reducing paperwork and expediting payment cycles. |
| Multi-Brand Vendor Support | Vendor integration covering all TJX banners including T.J. Maxx, Marshalls, HomeGoods, Sierra, HomeSense, Winners, and TK Maxx. |

## Use Cases

| Name | Description |
|------|-------------|
| Supplier Invoice Submission | Suppliers electronically submit invoices through iSupplier or Transcepta and track payment status in real time. |
| Purchase Order Management | Suppliers receive and acknowledge purchase orders from TJX banners via EDI 850/855 transactions. |
| Advance Shipping Notice | Vendors create and submit ASNs (EDI 856) to notify TJX distribution centers of incoming shipments. |
| Deduction Dispute Automation | Suppliers manage and dispute payment deductions through the Oracle iSupplier portal. |
| Supplier Diversity Reporting | Diverse suppliers register, maintain certifications, and submit quarterly Tier II reports through SupplierOne. |
| EDI Compliance Onboarding | New vendors establish EDI connectivity via approved service providers and complete TJX's testing requirements. |

## Integrations

| Name | Description |
|------|-------------|
| SPS Commerce | EDI integration and compliance platform for TJX vendor connectivity. |
| DiCentral | ASN Vendor Portal and EDI integration provider powering TJX's vendor shipping notice system. |
| Zenbridge | EDI integration platform supporting TJX vendor compliance requirements. |
| Pipe17 | Order management and EDI integration connector for TJX Companies. |
| Transcepta | Electronic invoicing platform for TJX supplier invoice submission. |
| Oracle iSupplier | Oracle-based supplier portal for invoice management and purchase order tracking. |
| Cleo | EDI integration solution for TJX trading partner compliance. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
