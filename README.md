# Awesome-Universal-Request

# Top Universal Request Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Cross-Departmental Service Delivery, Unified Ticketing & Enterprise Request Management*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Universal Request**. These tools enable organizations to provide a single, unified request experience across departments—allowing employees or customers to submit a request once and have it routed, transferred, and resolved seamlessly across IT, HR, Facilities, Legal, and other business functions without losing visibility or context.

**Examples** include ServiceNow Universal Request, Jira Service Management, Freshservice, Zendesk, Salesforce Service Cloud, BMC Helix, Cherwell, SysAid, TOPdesk, and HaloITSM (the category leaders).

**Open-source emphasis**: This section is heavily expanded with active projects for self-hosted ticketing, cross-department workflow orchestration, and enterprise service management—ideal for organizations building sovereign request management infrastructure without per-agent licensing lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[ServiceNow Universal Request](https://www.servicenow.com/)**  
  Enterprise application that creates a connecting record across departmental tickets (IT Incident, HR Case, Workplace Case, etc.), enabling seamless transfer between business functions while maintaining a single request number and unified employee experience; includes cross-departmental SLAs, restricted record security, and AI-based routing in Pro editions .

- **[Jira Service Management](https://www.atlassian.com/software/jira/service-management)**  
  Atlassian's service management platform with request types, queues, SLAs, and cross-project linking; supports DevOps integration and is widely adopted for IT and enterprise service delivery.

- **[Freshservice](https://www.freshworks.com/freshservice/)**  
  Cloud ITSM platform with service catalog, workflow automation, multi-department support, and unified employee portal for request management.

- **[Zendesk](https://www.zendesk.com/)**  
  Customer service and ticketing platform with multi-channel support, macros, SLAs, and cross-department routing via triggers and automations.

- **[Salesforce Service Cloud](https://www.salesforce.com/service/)**  
  Enterprise service platform with case management, omni-channel routing, knowledge base, and cross-department case escalation within the Salesforce ecosystem.

- **[BMC Helix](https://www.bmc.com/it-solutions/bmc-helix.html)**  
  AI-driven ITSM and enterprise service management platform with cognitive automation, multi-cloud support, and unified request management.

- **[Cherwell](https://www.cherwell.com/)**  
  ITSM and enterprise service management platform (now part of Ivanti) with codeless workflow design and cross-department request handling.

- **[SysAid](https://www.sysaid.com/)**  
  ITSM platform with AI-powered ticketing, self-service portal, and multi-department request routing for mid-market organizations.

- **[TOPdesk](https://www.topdesk.com/)**  
  Service management platform with request management, self-service portal, and cross-team collaboration for IT and facilities services.

- **[HaloITSM](https://www.haloitsm.com/)**  
  ITSM platform with request types, approval workflows, SLAs, and multi-department support for service desks and MSPs.

## Open-Source GitHub Projects

- **[Znuny](https://github.com/znuny/Znuny)**  
  Leading open-source ITSM and helpdesk platform (formerly OTRS fork) with ticket management, SLA handling, customer portal, knowledge base, and extensive customization; GPL-3.0 licensed and actively maintained with 30K+ GitHub commits .

- **[Request Tracker (RT)](https://github.com/bestpractical/request-tracker)**  
  Enterprise-grade open-source ticketing system (GPL-2.0) with web, email, REST API, and CLI interfaces; supports ticket lifecycle management, prioritization, assignment, and asset management for help desks and NOC teams .

- **[ITSM (heidsoft)](https://github.com/heidsoft/itsm)**  
  AI-native open-source ITSM platform (Apache 2.0) with full ticket/incident/problem/change lifecycle, CMDB, service catalog, SLA management, knowledge base with RAG, BPMN workflow engine, and native LLM triage; fully self-hostable with Docker Compose .

- **[GoatFlow](https://github.com/goatkit/goatflow)**  
  Open-source ticketing and workflow platform (Go) with REST APIs, HTMX frontend, multi-provider authentication (LDAP, OIDC, SAML, WebAuthn), and OTRS-compatible attachment storage; designed for modern self-hosted service management .

- **[Free ITSM](https://github.com/edmozley/freeitsm)**  
  Completely free ITSM tool with ticket management, AI-powered ticket summaries and briefings (optional, using your own AI provider), command palette, and per-analyst customization; focused on simplicity and data ownership .

### Additional Strong Open-Source Options

- **OTRS (Community Edition)** — The original open-source ITSM platform from which Znuny was forked; provides ticket management, workflow automation, and customer interfaces.
- **osTicket** — Widely used open-source support ticket system with email piping, custom fields, and help desk features for smaller teams.
- **Helpy** — Open-source customer support platform with multi-channel ticketing, knowledge base, and community forums.
- **Faveo Helpdesk** — Open-source helpdesk and ticketing system with SLA management, workflow automation, and multi-channel support.

**Frameworks for building custom systems**: Combine **Znuny** for full ITSM ticketing and SLA management, **heidsoft ITSM** for AI-native triage and RAG-powered knowledge retrieval, **Request Tracker** for email-centric ticket workflows, and **GoatFlow** for modern API-first service delivery in a fully self-hosted universal request stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Universal request platforms handling employee and customer data must comply with applicable regulations (GDPR, CCPA, etc.) and organizational data governance policies.
- Self-hosted open-source solutions require proper security hardening, integration planning with existing identity providers, and workflow customization for cross-departmental routing.
- Verify license terms for commercial use; Znuny uses GPL-3.0, RT uses GPL-2.0, and heidsoft ITSM uses Apache 2.0.

---

**Made for IT service managers, enterprise architects, HR operations teams, and shared services leaders.**  
Let's make universal request management more open, seamless, and employee-centric.
