# Awesome-People-Analytics-Reporting

# Top People Analytics & Reporting Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Workforce Intelligence, HR Reporting & Data-Driven People Decisions*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **People Analytics & Reporting**. These tools enable HR and business leaders to transform workforce data into actionable insights—analyzing attrition drivers, compensation equity, performance trends, and organizational health—to make evidence-based people decisions.

**Examples** include Workday Analytics and Reporting, Visier, One Model, Crunchr, Orgnostic, ChartHop, SplashBI, Tableau, Microsoft Power BI, and Orgvue (the category leaders).

**Open-source emphasis**: People Analytics is a domain where open-source tooling is **fragmented and largely immature**. Unlike BI platforms (Superset, Metabase) which are mature, purpose-built people analytics solutions are rare. The strongest open-source options are **general HRIS platforms with built-in reporting** (Frappe HR, OrangeHRM, Horilla) and **custom dashboard projects** built on Power BI or Tableau. Organizations seeking dedicated people analytics should plan for commercial platforms or significant custom development.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Workday Analytics and Reporting](https://www.workday.com/)**  
  Built-in analytics and reporting within Workday's HCM suite, providing workforce metrics, dashboards, and delivered reports across core HR, talent, and compensation data.

- **[Visier](https://www.visier.com/)**  
  Purpose-built people analytics platform with pre-built workforce intelligence models, attrition analysis, compensation equity, and planning capabilities.

- **[One Model](https://www.onemodel.co/)**  
  People analytics platform with a data warehouse-native approach, enabling custom analytics and machine learning on workforce data.

- **[Crunchr](https://www.crunchr.com/)**  
  People analytics platform for HR and business leaders, with dashboards for workforce composition, attrition, and diversity metrics.

- **[Orgnostic](https://orgnostic.com/)**  
  People analytics platform connecting data from HRIS, ATS, and surveys to provide insights on attrition, performance, and organizational health.

- **[ChartHop](https://www.charthop.com/)**  
  People operations platform combining org chart visualization, headcount planning, and analytics for growing companies.

- **[SplashBI](https://www.splashbi.com/)**  
  BI and analytics platform with pre-built HR analytics apps for Oracle, SAP, Workday, and other enterprise systems.

- **[Tableau](https://www.tableau.com/)**  
  Visual analytics platform widely used for HR dashboards when connected to HRIS exports or data warehouses; requires analyst resources for custom people analytics builds.

- **[Microsoft Power BI](https://powerbi.microsoft.com/)**  
  Microsoft's BI platform commonly used for HR reporting and dashboards; accessible entry point for teams already in the Microsoft ecosystem.

- **[Orgvue](https://www.orgvue.com/)**  
  Organizational design and workforce planning platform with analytics for span of control, cost modeling, and org structure visualization.

## Open-Source GitHub Projects

- **[Frappe HR](https://github.com/frappe/hrms)**  
  Comprehensive open-source HRMS (AGPL-3.0) with built-in **reporting and analytics** across employee lifecycle, leave, attendance, payroll, and performance; includes customizable reports and dashboards; integrates naturally with ERPNext for cross-functional analytics; Docker-deployable and actively maintained . **The strongest open-source HR foundation with native reporting**, though analytics depth is operational rather than strategic people analytics.

- **[OrangeHRM](https://github.com/orangehrm/orangehrm)**  
  Veteran open-source HRM system (GPL, since 2005) with a **reporting and analytics module** providing insights into key HR metrics; covers personnel, leave, time/attendance, performance, and recruitment; available as self-hosted Starter edition or paid Advanced/Enterprise tiers . Mature and widely deployed, though UI is dated compared to newer options.

- **[Horilla](https://github.com/horilla/horilla-hr)**  
  Free and open-source HRMS (LGPL-2.1, 1,332 GitHub stars) with modules spanning recruitment, attendance, leave, payroll, and performance; includes reporting capabilities and a modern UI; Docker-deployable and actively developed (last commit within 24 hours as of listing) . Strong modern alternative to OrangeHRM for teams wanting a cleaner interface.

- **[Farik](https://github.com/SamoTech/Farik)**  
  Open-source HR platform (MIT) for small teams with **dashboard analytics** from live data; free tier includes people directory, recruitment pipeline, helpdesk, attendance/leave, and real authentication; Pro tier adds AI-powered attrition prediction, burnout heatmaps, and 90-day flight risk forecasting . **Early-stage but explicitly includes people analytics features** (Pro), with a clear roadmap toward AI analytics.

- **[Luminus.ai](https://github.com/caphefalumi/Luminus.ai)**  
  Open-source AI-powered HR analytics platform (Next.js/MongoDB) with **burnout detection**, performance analytics, network visualization of team relationships, and AI-driven insights; CSV upload for employee data; JWT authentication with RBAC . **Analytics-focused**—provides visualization and prediction capabilities but not a full HRIS.

- **[People Analytics Dashboard (MohammedSaihan)](https://github.com/MohammedSaihan/People-Analytics-Dashboard-Workforce-Intelligence-for-Leadership)**  
  Open-source end-to-end people analytics project combining **MySQL + Python (Pandas) + Power BI + DAX**; includes executive workforce overview, attrition risk analysis, compensation/performance trends, and workforce planning dashboards . **Project-based**—demonstrates a complete analytics pipeline but requires Power BI licensing and is not a production platform.

- **[PeopleAnalytics_Turnover (brunokatekawa)](https://github.com/brunokatekawa/PeopleAnalytics_Turnover)**  
  Open-source web application for predicting employee turnover (Jupyter Notebook, 30 GitHub stars); identifies employees most likely to leave with department, education, job satisfaction, and role context; includes an Employee Experience article . **Turnover prediction-focused**—a specific people analytics use case, not a general reporting platform.

### Additional Strong Open-Source Options

- **MintHCM** — Free open-source Human Capital Management system (AGPL) with **customizable reports and analytics** for workforce trends, employee performance, and HR metrics . Provides operational HR analytics within a full HRMS.
- **Frappe Insights** — 100% open-source BI platform (Frappe Framework) that can connect to HR data sources (MySQL, PostgreSQL, etc.) for custom people analytics dashboards; no SQL required with visual query builder . **General BI tool**—useful for building custom HR dashboards but not people-analytics-specific.
- **Apache Superset / Metabase** — Mature open-source BI platforms that can be connected to HRIS exports or data warehouses for custom people analytics dashboards; require data modeling and analyst involvement.

**Frameworks for building custom systems**: No open-source platform provides dedicated people analytics comparable to Visier or One Model. **Frappe HR** and **Horilla** provide HR data foundations with operational reporting. **Luminus.ai** and **Farik** (Pro) offer AI-driven analytics features but are early-stage. **Frappe Insights** or **Superset** can serve as BI layers on top of HRIS data for custom dashboards. A complete people analytics solution would require integrating HRIS data (Frappe HR/OrangeHRM), a BI layer (Frappe Insights/Superset), and custom development for strategic analytics—a substantial effort with no ready-made starting point.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- People analytics platforms handling employee data must comply with applicable privacy regulations (GDPR, CCPA) and organizational data governance policies; analytics on attrition, performance, and compensation can create legal and ethical risks if not managed responsibly.
- **Open-source people analytics remains underdeveloped**—Frappe HR, OrangeHRM, and Horilla provide HRIS with operational reporting; Luminus.ai and Farik (Pro) offer early-stage AI analytics; no open-source platform matches Visier or One Model's strategic analytics depth. Organizations requiring dedicated people analytics should budget for commercial platforms.
- Verify license terms for commercial use; Frappe HR uses AGPL-3.0, OrangeHRM Starter uses GPL, Horilla uses LGPL-2.1, Farik uses MIT, and Luminus.ai is open-source (check repository).

---

**Made for HR analytics leaders, people operations teams, workforce planners, and data-driven HR practitioners.**  
Let's make people analytics more open, but with clear eyes about what open-source can currently deliver in this domain.
