# Awesome-Cash-Management

# Awesome-Cash-Management
**Top Cash Management (Opensource) 🌟 Star if you like it! 🌟**

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Cash Positioning, Liquidity Forecasting, Bank Reconciliation & Treasury Operations*
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cash Management**. These tools enable finance and treasury teams to consolidate bank balances, forecast cash flows, reconcile statements, manage liquidity, and automate payments—from fully managed enterprise treasury suites with AI-powered forecasting and bank connectivity to self-hosted packages and ERP modules that give organizations complete control over their cash data and infrastructure.

**Examples** include Kyriba, GTreasury, Coupa Treasury, FIS Quantum, TIS, HighRadius, Serrala, Nomentia, Agicap, and Workday Cash Management (the category leaders in commercial space).

**Open-source emphasis**: This section is expanded with every relevant project for self-hosting, cash positioning, reconciliation, and open treasury infrastructure—ideal for developers, finance teams, and organizations seeking transparent, vendor-independent cash management. **Note**: True open-source enterprise cash management is rare; most results are ERP modules, packages, or adjacent tools.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Kyriba](https://www.kyriba.com/)**
  **Enterprise treasury and cash management platform** with real-time cash positioning, forecasting, payments, and AI (Trusted Agentic AI). Recognized as a Leader in IDC MarketScape for AI-Enabled Midmarket Treasury 2025–2026 . **Pricing**: Quote-only; Kyriba Essentials for Mid-Market offers curated packages based on banking footprint . **Free tier**: None. **Best for**: mid-market to enterprise organizations wanting a unified, AI-enhanced treasury platform with bank connectivity and fraud controls.

- **[GTreasury](https://www.gtreasury.com/)**
  **Adaptive treasury and cash management solutions** covering cash visibility, forecasting, risk, debt, investments, and payments. Emphasizes rapid implementations (weeks) and agent-driven insights . **Pricing**: Quote-only. **Free tier**: None. **Best for**: CFOs and treasurers wanting modular, scalable treasury solutions that grow with complexity.

- **[Coupa Treasury](https://www.coupa.com/)**
  **Treasury management within the Coupa business spend management suite**. Provides Treasury REST API for cash flow and account balance data . **Pricing**: Quote-only; bundled with Coupa platform. **Free tier**: None. **Best for**: organizations already on Coupa wanting treasury visibility integrated with procurement and spend data.

- **[FIS Quantum](https://www.fisglobal.com/)**
  **Enterprise treasury and risk management platform** (Treasury and Risk Manager – Quantum Cloud Edition). Cloud-native with a Liquidity Hub module for real-time cash management across ERP and bank APIs . **Pricing**: Quote-only. **Free tier**: None. **Best for**: large enterprises needing scalable, cloud-based treasury with real-time cash visibility and risk analytics.

- **[TIS (Treasury Intelligence Solutions)](https://www.tis.com/)**
  **Cloud-based cash visibility and liquidity management** via CashOptix suite—bank account management, cash forecasting, and liquidity solutions connecting global banks and systems . **Pricing**: Quote-only. **Free tier**: None. **Best for**: enterprises needing multi-bank cash visibility and liquidity planning across entities and currencies.

- **[HighRadius](https://www.highradius.com/)**
  **AI-powered cash flow management** with autonomous forecasting, variance analysis, and cash operations. Uses agentic AI to continuously learn from cash behavior and auto-explain variances . **Pricing**: Quote-only. **Free tier**: None. **Best for**: finance teams wanting AI-driven forecasting and touchless cash operations within an Order-to-Cash/AP ecosystem.

- **[Serrala](https://www.serrala.com/)**
  **Unified payments, cash visibility, and treasury** platform. AI agents for fraud prevention and cash application; deployment cloud or embedded in SAP S/4HANA . **Pricing**: Quote-only. **Free tier**: None. **Best for**: SAP-centric enterprises wanting payments and cash visibility in a single command center.

- **[Nomentia](https://www.nomentia.com/)**
  **Treasury and cash management** with deal handling, payments oversight, and bank connectivity. Recent releases add internal FX deal requests, commercial paper deal types, and VoP visibility across payment batches . **Pricing**: Quote-only. **Free tier**: None. **Best for**: European mid-market companies needing structured treasury workflows and payment controls.

- **[Agicap](https://agicap.com/)**
  **Cash flow management for SMBs** with bank connections, short-term forecasting, and visual dashboards. Users report clear cash visibility and improved planning versus spreadsheets . **Pricing**: Tiered plans; quote-based. **Free tier**: None. **Best for**: SMBs and scale-ups wanting straightforward cash flow visibility without enterprise TMS complexity.

- **[Workday Cash Management](https://www.workday.com/)**
  **Cash management within Workday Financials**. **Pricing**: Quote-only; bundled with Workday Financial Management. **Free tier**: None. **Best for**: organizations already on Workday wanting cash positioning integrated with accounting and financial data.

## Open-Source GitHub Projects

- **[Nexus\CashManagement](https://github.com/azaharizaman/nexus-cash-management)**
  **Atomic, stateless PHP package for bank account management, statement import, cash reconciliation, and liquidity forecasting** — **the closest to a dedicated open-source cash management component** in this list. **Features**: Multi-currency bank accounts, CSV statement import with duplicate detection, AI-assisted reconciliation matching, deterministic and AI-powered forecasting, and real-time cash position . **Tech stack**: Pure PHP, framework-agnostic. **Deploy**: Embedded via Composer into Nexus ERP ecosystem. **Trade-off**: A package, not a standalone application—requires integration effort. **Best for**: PHP developers building or extending ERP systems needing modular cash management logic.

- **[Nexus\Treasury](https://github.com/azaharizaman/nexus-treasury)**
  **Treasury management package for policies, authorization limits, and approval workflows** — companion to Nexus\CashManagement. **Features**: Treasury policies with thresholds, per-user/role spending limits, multi-currency approval workflows, and status tracking . **Tech stack**: PHP. **Deploy**: Composer package. **Trade-off**: Focused on policy and approval orchestration, not cash positioning or forecasting. **Best for**: developers needing treasury governance logic within a PHP application.

- **[Odoo `treasury_forecast`](https://apps.odoo.com/apps/modules/13.0/treasury_forecast)**
  **Treasury forecasting and cash flow management module for Odoo** (OPL-1) — **the most accessible Odoo-based cash planning add-on**. **Features**: Forecasting windows, daily cash flow from bank moves and planned payments, Excel export, and Bokeh chart views . **Tech stack**: Python (Odoo). **Deploy**: Odoo Community or Enterprise. **Trade-off**: OPL-1 license (not OSI open source); limited to Odoo 13. **Best for**: organizations already on Odoo wanting treasury planning without building custom modules.

- **[Odoo `finance_treasury`](https://apps.odoo.com/apps/modules/18.0/finance_treasury)**
  **Universal treasury management for Odoo 18** (LGPL-3) — **a more comprehensive and current Odoo treasury module**. **Features**: Cash/bank/card/wallet accounts, income/expense/transfer/exchange transactions, automatic journal entries, multi-currency, and cash flow reports . **Tech stack**: Python (Odoo). **Deploy**: Odoo 18 (Community & Enterprise). **Trade-off**: Focused on transaction recording and accounting integration, not external bank connectivity or advanced forecasting. **Best for**: Odoo users wanting structured treasury account management with automatic accounting entries.

- **[Odoo `treasury_cash_management`](https://apps.odoo.com/apps/modules/19.0/treasury_cash_management)**
  **Cash management add-on with 13-month rolling forecast, daily snapshots, and quick reconciliation** (OPL-1). **Features**: Rolling monthly forecast from invoices/orders/manual adjustments, forecast-vs-actual variance, daily cash position snapshots, and bank reconciliation wizard . **Tech stack**: Python (Odoo). **Deploy**: Odoo 18/19. **Trade-off**: OPL-1 license; Odoo-specific. **Best for**: Odoo users prioritizing forward-looking cash forecasting and reconciliation over transaction recording.

- **[Gantry Financial Suite (Treasury module)](https://github.com/braedonsaunders/com.flux.gantry)**
  **Open-source financial analytics SuiteApp for NetSuite** (MIT) — **includes a Treasury (Cashflow) dashboard**. **Features**: Weekly cash flow forecasting from GL history and vendor patterns, AP/AR aging, payment category management, and bank account balancing . **Tech stack**: SuiteScript 2.1 (NetSuite). **Deploy**: NetSuite via SDF. **Trade-off**: NetSuite-dependent; not a standalone cash management system. **Best for**: NetSuite users wanting open-source cash flow analytics without additional SaaS subscriptions.

- **[Eclipse Tradista](https://projects.eclipse.org/proposals/eclipse-tradista)**
  **Open-source trade and treasury software for financial institutions** (Apache 2.0) — **covers cashflows forecast and position keeping** for securities, derivatives, and FX . **Tech stack**: Java, Jakarta EE. **Deploy**: Self-hosted. **Trade-off**: Front/middle office focus for capital markets, **not corporate cash management** (bank balance consolidation, payment workflows, liquidity planning). **Best for**: banks and financial institutions needing open-source trade treasury operations—not corporate treasury teams.

- **[FrontAccounting](https://frontaccounting.com/)**
  **Open-source web-based accounting and ERP** (GPL) — **includes cash and bank management** for multiple accounts, petty cash, and bank reconciliation . **Tech stack**: PHP, MySQL. **Deploy**: Self-hosted. **Trade-off**: Cash management is part of general accounting, not a dedicated treasury system—no forecasting or multi-bank consolidation. **Best for**: SMBs wanting basic cash account tracking within a free accounting system.

- **[Moneta](https://github.com/revoltify/moneta)**
  **AI-powered, self-hosted money management for small businesses and freelancers** — **lightweight cash tracking with an MCP server for AI agents**. **Features**: Multi-wallet balance tracking, income/expense/transfer flows, cash flow reports, and 26 MCP tools for AI access . **Tech stack**: PHP (Laravel). **Deploy**: Docker or shared hosting. **Trade-off**: Personal/small-business money management, not enterprise treasury—no bank statement reconciliation or multi-entity consolidation. **Best for**: freelancers and micro-businesses wanting self-hosted cash visibility with AI query capabilities.

### Additional Strong Open-Source Options

- **Apache Fineract** — Open-source core banking platform (Apache 2.0). Includes teller/cashier management for daily cash-in/cash-out tracking within banking operations. **Note**: Banking teller cash management, not corporate treasury. **Best for**: microfinance institutions and banks needing teller cash tracking .
- **cfo-cli** — Open-source CLI for freelancers (MIT). Includes cash flow forecasting with scenarios and multi-currency. **Note**: Command-line tool for solo operators, not a treasury system. **Best for**: developers and freelancers wanting scriptable cash forecasting .
- **AFIS** — Open-source AI financial intelligence for SMEs (license per repo). Includes ML-based 12-month cash flow forecasting with confidence intervals. **Note**: Analytics/forecasting layer, not cash positioning or reconciliation. **Best for**: SMEs wanting ML forecasting on CSV ledger exports .

**Frameworks for building custom systems**: Combine **Nexus\CashManagement** for reconciliation and positioning logic with **Nexus\Treasury** for policy/approval governance, **Odoo `finance_treasury`** for accounting-integrated transaction recording, and **Gantry** for NetSuite analytics—creating a cash management stack matched to each organization's ERP and technical constraints.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, license (for open-source), and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Cash management platforms handling bank account data and financial transactions must comply with data protection regulations (GDPR, CCPA, etc.) and implement appropriate access controls and audit trails.
- **The "corporate cash management vs. adjacent tooling" distinction is critical.** **Kyriba, GTreasury, Coupa Treasury, FIS Quantum, TIS, and Nomentia** are purpose-built treasury/cash management platforms. **Nexus packages** are components for building systems. **Odoo modules** are ERP add-ons. **Gantry** is NetSuite analytics. **Tradista** is capital markets treasury. **Moneta and cfo-cli** are small-business tools. **Do not confuse a forecasting script or an accounting module with a full cash management system.**
- **True open-source enterprise cash management is essentially nonexistent.** No mature open-source project matches Kyriba or FIS Quantum in scope (multi-bank connectivity, real-time positioning, payment workflows, fraud controls, compliance). **Nexus\CashManagement** is the closest dedicated component, but it is a PHP package requiring integration—not a deployable application . **Organizations needing full cash management will likely require SaaS or significant custom development.**
- **Odoo treasury modules are ERP-specific and license-varied.** `finance_treasury` is LGPL-3 (OSI open source) , but `treasury_forecast` and `treasury_cash_management` are OPL-1 (proprietary) . **Check licenses carefully before adopting Odoo modules for open-source projects.**
- **Pricing transparency is poor across commercial vendors.** All listed SaaS platforms require sales contact for quotes. **Validate with direct vendor conversations against your banking footprint and entity structure.**
- Self-hosted open-source solutions require proper server setup, backup configuration, and ongoing maintenance. **Cash and bank data is highly sensitive**—ensure your hosting meets your organization's security and compliance requirements before deploying.

---

**Made for developers, finance teams, and organizations building transparent cash management solutions.**
Let's make Cash Management more open, data-driven, and treasury-friendly.
