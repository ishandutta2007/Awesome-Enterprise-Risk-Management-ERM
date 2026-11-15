# Awesome-Enterprise-Risk-Management-ERM

## Top Enterprise Risk Management (ERM) Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on Risk Registers, Control Mapping & Self-Hosted GRC Platforms*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Enterprise Risk Management (ERM)**. These tools help organizations identify, assess, and mitigate risks across the enterprise—covering everything from risk registers and heat maps to compliance frameworks, audit workflows, and vendor risk management.

**Examples** include ServiceNow GRC, MetricStream, LogicManager, AuditBoard, Resolver, Riskonnect, RSA Archer, Diligent HighBond, SimpleRisk, and Eramba (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted risk management, open-source GRC platforms, and community-driven compliance tooling—ideal for organizations seeking data sovereignty and avoiding six-figure enterprise licensing. The open-source landscape is genuinely functional: **SimpleRisk** provides a mature PHP-based ERM platform with a Docker deployment , **Eramba** offers comprehensive GRC with evidence management , and **CISO Assistant** delivers modern cybersecurity risk and compliance management with a free tier .

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global Enterprise Risk Management (ERM) software market is estimated at approximately **$6.0B to $7.0B** (expanding to over **$20B–$40B** across the broader enterprise GRC ecosystem) and growing at a ~14–15% CAGR driven by tightening regulations, cyber threats, and AI governance. The market is **highly fragmented** rather than winner-take-all: traditional enterprise heavyweights (e.g., ServiceNow, RSA Archer, MetricStream) anchor Fortune 500 deployments, while a diverse array of specialized mid-market suites, agile compliance automation vendors, and open-source self-hosted solutions thrive across distinct industry niches and regulatory tiers.

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[LogicManager](https://www.logicmanager.com/)** | **ERM platform with transparent "Job-to-be-Done" pricing and a 90-day money-back guarantee.** **Unlimited users** (internal and external) at a fixed all-inclusive price covering licensing, advisory service, and onboarding. Guided onboarding with dedicated specialist across eight sessions . Software Advice lists starting price at **$10,000/year** . | **$10,000/year** (Software Advice listing); fixed all-inclusive pricing via sales | **90-day unconditional money-back guarantee** ; no free tier |
| **[RSA Archer](https://www.archerirm.com/)** | **Enterprise GRC fixture in banking, insurance, and regulated sectors.** Seven solution areas: audit management, business resiliency, IT/security risk, enterprise/operational risk, third-party governance, regulatory compliance, and public sector. **CDW-G lists a 1-month subscription license at $671.31** (indicative per-user monthly cost) . | ~**$671.31/month** per license (CDW-G) | No free tier; demo via sales |
| **[Diligent HighBond](https://www.diligent.com/)** | GRC platform with Enterprise Risk Management, Audit Management, and Vendor Risk modules. **No published pricing—quote only.** Median contract **$23,488/year** (4 buyer reports). **Annual price increases of 5%**; auto-renewal 30 days prior to expiration. **4 documented hidden costs** including implementation and training . | Median **$23,488/year** (quote-only) | No free tier or trial |
| **[Riskonnect Active Risk Manager](https://www.riskonnect.com/)** | Enterprise risk management platform. Software Advice lists starting price at **$20,000 one-time** . Positioned for organizations needing integrated risk analytics. | **$20,000 one-time** (Software Advice) | Free trial available |
| **[MetricStream](https://www.metricstream.com/)** | Enterprise GRC suite for large regulated organizations. SelectHub lists starting price at **$75,000/year** (quote-based), with free trial available. Small-enterprise deployments **$75K–$150K**, scaling to **$750K–$1M** for large enterprises | **$75,000/year** (SelectHub) | **Free trial** (request via SelectHub) |
| **[ServiceNow GRC (IRM)](https://www.servicenow.com/)** | Enterprise Integrated Risk Management sold as tiered bundles. **IRM Standard ($125/operator/month), Professional ($250), Enterprise ($375)**. **IRM Lite operators (~$75/month)** can respond to attestations and questionnaires at lower cost | Standard: **$125/operator/month**; Enterprise: $375 | No free tier; demo via sales |
| **[AuditBoard](https://www.auditboard.com/)** | Category leader for internal audit, SOX compliance, and controls management. Vendr benchmark shows typical annual contract around **$45,947**. Implementation adds **10–25%** to first-year cost; renewal escalations typically **3–7%/year** | ~**$45,947/year** (Vendr median) | No free tier; demo via sales |
| **[Resolver](https://www.resolver.com/)** | Risk intelligence platform covering enterprise risk, compliance, and security. Positioned for organizations needing integrated risk analytics | Quote-only | No free tier; demo via sales |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[SimpleRisk](https://github.com/simplerisk/code)** | [![Stars](https://img.shields.io/github/stars/simplerisk/code?style=social&color=white)](https://github.com/simplerisk/code/stargazers) | **The most established open-source ERM platform with the simplest deployment path.** PHP/MySQL, **Docker repository available** for one-command deployment . **Enterprise Risk Management Simplified**—core features cover risk register, risk assessment, mitigation planning, and reporting. **Trusted by hundreds of companies** across healthcare, government, and technology . **Active development** (updated November 2026) with a **Secure Controls Framework (SCF) integration** . **Free and open-source** (check repository license) . **Best for small-to-mid organizations** wanting a proven, straightforward risk management platform without per-user fees . |
| **[Eramba](https://github.com/eramba/eramba)** | [![Stars](https://img.shields.io/github/stars/eramba/eramba?style=social&color=white)](https://github.com/eramba/eramba/stargazers) | **Comprehensive open-source GRC with strong evidence management.** **3,689+ downloads last year, 10 releases in the past year**—actively maintained . Best for organizations tackling **multiple frameworks simultaneously**. Includes risk management, compliance, policy management, and audit capabilities . **Best for teams needing broader GRC coverage** beyond pure ERM—especially those managing ISO 27001, SOC 2, and similar frameworks alongside enterprise risk . |
| **[CISO Assistant](https://github.com/intuitem/ciso-assistant-community)** | [![Stars](https://img.shields.io/github/stars/intuitem/ciso-assistant-community?style=social&color=white)](https://github.com/intuitem/ciso-assistant-community/stargazers) | **Modern open-source GRC for cybersecurity risk and compliance.** **30+ ready frameworks** including ISO 27001, NIST CSF, SOC 2, and custom controls. Controls are reusable objects connecting risks to frameworks. **Microservices-based architecture** (backend, frontend, dispatcher) ideal for AI integration. **API, n8n, MCP, and Kafka integration options** . **Free plan available; paid access from €39/month** (annual) with 30-day trial . **Best for cybersecurity-focused risk teams** wanting modern tooling with framework mapping . |
| **[Probo](https://github.com/getprobo/probo)** | [![Stars](https://img.shields.io/github/stars/getprobo/probo?style=social&color=white)](https://github.com/getprobo/probo/stargazers) | **Full-lifecycle open-source GRC covering risk management, controls, vendor risk, and audit programs.** ISC licensed, Go/PostgreSQL, self-hostable via Docker. Features: **risk register with scoring and treatment strategies**, **controls and frameworks** with maturity levels, **vendor risk** with automated assessment, **data privacy** (DPIA, TIA), **access reviews**, and **document management** with e-signatures. **270+ MCP tools** expose every entity to AI agents . **Best for teams wanting a complete GRC platform** with modern architecture and AI-agent integration . |
| **[ComplianceForge](https://github.com/jamesboamah/complianceforge)** | [![Stars](https://img.shields.io/github/stars/jamesboamah/complianceforge?style=social&color=white)](https://github.com/jamesboamah/complianceforge/stargazers) | **Enterprise Security Governance, Risk, Compliance & AI Assurance platform.** Open-source with **Governance & Policy Management, ERM, RCSA, Vendor Risk Management, Compliance Framework Mapping, Audit & Evidence Tracking, Security KPI/KRI Reporting, and AI Governance**. Covers **ISO 27001, NIST CSF, CIS Controls, SOC 2, GDPR, PCI DSS, ISO 42001, NIST AI RMF, and EU AI Act** . **Best for organizations wanting an all-in-one GRC demonstration platform** with broad framework coverage and AI governance readiness . |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[OpenGRC](https://github.com/topics/grc)** | — | Open-source GRC web application with API and self-hosting **for small and midsized teams**. **Starting from $4,500/month** (commercial support tier) with a free open-source option . **Best for SMBs wanting a lightweight GRC starting point** . |
| **[ComplianceOS](https://pypi.org/project/autoai-complianceos/)** | — | **Open-core GRC for the web with API and self-hosting.** Supports compliance frameworks and AI policy generation. **From $149/month** . **Best for teams wanting AI-assisted compliance** with a lower entry point . |

**Frameworks for building custom systems**: Choose **SimpleRisk** for the simplest path to a working ERM register with Docker deployment , **Eramba** for comprehensive multi-framework GRC with evidence management , or **Probo** for a full-lifecycle modern platform with AI-agent access —all without per-user or six-figure enterprise licensing.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- ERM platforms handle sensitive risk assessments and potentially privileged audit findings; enforce role-based access, audit logging, and compliance with applicable regulations.
- **Enterprise ERM pricing is opaque and varies dramatically.** **LogicManager publishes a transparent all-inclusive model** with unlimited users and a **90-day money-back guarantee**—the most buyer-friendly terms in the category . **RSA Archer and Diligent HighBond are quote-only**; HighBond's median contract is **$23,488/year** with **5% annual increases** and auto-renewal terms that require 30-day notice to cancel . **ServiceNow GRC charges per-operator** ($125–$375/month), but **Lite operators (~$75/month)** for attestation-only users can cut costs significantly . **AuditBoard's median is ~$45,947/year**, but buyers who evaluate alternatives secure **15–30% lower pricing** . **Open-source ERM is genuinely viable**: SimpleRisk is the simplest Docker-deployed option , Eramba provides multi-framework coverage , and Probo offers modern architecture with AI-agent integration . **Validate whether you need a pure risk register (SimpleRisk), multi-framework GRC (Eramba), or a full platform with vendor risk and privacy (Probo)** before committing.

---

**Made for risk managers, compliance officers, and organizations building governance infrastructure.**  
Let's make enterprise risk management more open, transparent, and actionable.
