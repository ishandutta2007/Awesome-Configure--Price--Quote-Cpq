# Awesome-Configure,-Price,-Quote-Cpq

# Awesome-Configure,-Price,-Quote-Cpq

# Top Configure, Price, Quote (CPQ) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Sales Configuration, Pricing Rules & Quote Automation*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Configure, Price, Quote (CPQ)**. These tools enable sales teams to configure complex products, apply dynamic pricing rules, generate accurate quotes, and streamline the quote-to-cash process — reducing errors and accelerating deal cycles.

**Examples** include Salesforce CPQ, DealHub, PandaDoc CPQ, Oracle CPQ, SAP CPQ, Conga CPQ, PROS Smart CPQ, CloudSense, Tacton, and Subskribe (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom pricing engines, and open quote generation pipelines — ideal for manufacturers, SaaS companies, and developers seeking transparent, vendor-independent CPQ solutions.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Salesforce CPQ](https://www.salesforce.com/products/cpq/)**  
  Native Salesforce CPQ solution for configuring products, applying pricing rules, and generating quotes. Features bundle configuration, discount schedules, contract generation, and renewal management.

- **[DealHub](https://dealhub.io/)**  
  Unified CPQ and quote-to-revenue platform with guided selling, dynamic pricing, e-signatures, and CRM integrations. Supports multi-language and multi-currency quoting.

- **[PandaDoc CPQ](https://www.pandadoc.com/)**  
  Document automation and CPQ platform combining quote creation with e-signatures and payment collection. Features product catalogs, pricing tables, and approval workflows.

- **[Oracle CPQ](https://www.oracle.com/cx/cpq/)**  
  Enterprise CPQ solution supporting complex product configuration, multi-channel sales, and global pricing. Integrates with Oracle ERP and CRM ecosystems.

- **[SAP CPQ](https://www.sap.com/)**  
  CPQ solution integrated with SAP S/4HANA and SAP CRM. Supports configure-to-order, variant configuration, and subscription billing for manufacturing and high-tech industries.

- **[Conga CPQ](https://conga.com/)**  
  CPQ and document generation platform with Salesforce-native integration. Features guided selling, pricing optimization, and contract lifecycle management.

- **[PROS Smart CPQ](https://www.pros.com/)**  
  AI-powered CPQ for B2B enterprises with dynamic pricing optimization and real-time market data. Focused on airlines, manufacturing, and distribution.

- **[CloudSense](https://www.cloudsense.com/)**  
  CPQ and order management platform built on Salesforce. Designed for telecommunications, media, and utilities with complex product catalogs.

- **[Tacton](https://www.tacton.com/)**  
  CPQ solution for manufacturers with complex configurable products. Features 3D visualization, CAD integration, and sales configuration.

- **[Subskribe](https://www.subskribe.com/)**  
  Adaptive CPQ and subscription management platform for SaaS companies. Features usage-based pricing, revenue recognition, and billing automation.

## Open-Source GitHub Projects

- **[ERPNext](https://github.com/frappe/erpnext)**  
  Comprehensive open-source ERP (GPL-3.0) with integrated quotation management, product configuration, pricing rules, and sales order generation. Features item variants, pricing rules, and multi-currency support. 30k+ GitHub stars. The most complete open-source alternative to commercial CPQ for SMBs .

- **[Saleor](https://github.com/saleor/saleor)**  
  Open-source e-commerce platform (BSD-3-Clause) with a GraphQL API. Features product variants, dynamic pricing, checkout flows, and quotation generation for B2B commerce. 21k+ GitHub stars.

- **[Medusa](https://github.com/medusajs/medusa)**  
  Open-source headless commerce platform (MIT) with modular architecture. Supports product configuration, tiered pricing, and custom quote workflows via API-first design. 28k+ GitHub stars.

- **[OpenBoxes](https://github.com/openboxes/openboxes)**  
  Open-source supply chain and inventory management system (EPL-1.0) with purchase order and quotation capabilities. Used by hospitals and NGOs for procurement workflows.

- **[Odoo](https://github.com/odoo/odoo)**  
  Open-source business suite (LGPL-3.0) with integrated Sales, Purchase, and Inventory modules. Features quotation templates, pricelists, product configurator, and subscription management. 40k+ GitHub stars. Enterprise version adds advanced CPQ features.

- **[Dolibarr](https://github.com/Dolibarr/dolibarr)**  
  Open-source ERP/CRM (GPL-3.0) with quotation management, product catalogs, and pricing rules. Supports multi-company and multi-currency scenarios. 5k+ GitHub stars.

- **[Tryton](https://github.com/tryton/tryton)**  
  Modular open-source business framework (GPL-3.0) with sale, purchase, and product modules supporting quotation and pricing. Highly extensible for custom CPQ logic.

- **[QuoteFlow](https://github.com/quote-flow/quoteflow)**  
  Open-source CPQ prototype (license varies) exploring guided selling and quote generation. Early-stage but demonstrates core CPQ concepts.

- **[Strapi + Commerce](https://github.com/strapi/strapi)**  
  Open-source headless CMS (MIT) often combined with commerce plugins to build custom CPQ frontends. API-first architecture supports product catalogs and pricing rules.

### Additional Strong Open-Source Options

- **[Akeneo PIM](https://github.com/akeneo/pim-community-dev)** — Open-source Product Information Management (OSL-3.0) for managing complex product catalogs feeding CPQ systems.
- **[Pimcore](https://github.com/pimcore/pimcore)** — Open-source PIM/MDM platform (GPL-3.0) with product data management and pricing capabilities.
- **[Vtiger CRM](https://github.com/vtiger-crm/vtigercrm)** — Open-source CRM with Quotes module and product configuration.
- **[SuiteCRM Quotes](https://github.com/salesagility/SuiteCRM)** — Open-source CRM with Quotes module supporting line items and pricing.
- **[EspoCRM](https://github.com/espocrm/espocrm)** — Open-source CRM with Quote entity and product catalog support.
- Community **n8n** workflows for quote automation and approval routing.
- **Documenso** and **DocuSeal** for open-source e-signature integration with quotes.

**Frameworks for building custom systems**: Combine **ERPNext** or **Odoo** as the ERP/CPQ backend with **Saleor** or **Medusa** for B2B commerce frontends, **Akeneo PIM** for product data management, and **Documenso** for e-signature workflows — creating a fully self-hosted, enterprise-grade CPQ stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- CPQ systems processing pricing and customer data must comply with data protection regulations (GDPR, CCPA, etc.).
- Self-hosted open-source solutions require proper security hardening, pricing rule validation, and ongoing maintenance.

---

**Made for sales operations, revenue teams, manufacturers, and developers building transparent CPQ solutions.**  
Let's make Configure, Price, Quote more open, data-driven, and efficient.
