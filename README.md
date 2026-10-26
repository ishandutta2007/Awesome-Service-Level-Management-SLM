# Awesome-Service-Level-Management-SLM

# Top Service Level Management (SLM) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on SLA Definition, Escalation Automation & Service Performance Monitoring*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Service Level Management (SLM)**. These tools enable organizations to define, track, and enforce service level agreements (SLAs)—monitoring response and resolution targets, automating escalations, and providing real-time visibility into whether IT and business services are meeting their commitments to customers and employees.

**Examples** include ServiceNow Service Level Management, Freshservice, Jira Service Management, BMC Helix ITSM, Ivanti Neurons for ITSM, ManageEngine ServiceDesk Plus, HaloITSM, TOPdesk, SysAid, and SolarWinds Service Desk (the category leaders).

**Open-source emphasis**: This section is expanded with active projects for self-hosted ITSM with SLA tracking and dedicated SLA monitoring platforms—ideal for organizations building sovereign service level management infrastructure without per-agent licensing lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[ServiceNow Service Level Management](https://www.servicenow.com/)**  
  Enterprise SLM on the Now Platform with SLA definitions applied to any task table (Incident, Incident Task, etc.), configurable start/pause/stop/reset conditions, workflow-driven escalation, Performance Analytics dashboards for predictive breach detection, and SLA Breakdowns to analyze time spent across assignment groups .

- **[Freshservice](https://www.freshworks.com/freshservice/)**  
  SLA and OLA policy management with global and workspace-level policies, priority-driven due-by matrices, business/calendar hour calculation, up to four escalation levels for resolution and one for response, and automatic escalation emails for at-risk tickets .

- **[Jira Service Management](https://www.atlassian.com/software/jira/service-management)**  
  Project-level SLA goals for response and resolution targets, agent-view and customer-portal SLA display, and configurable permissions for SLA visibility; native SLA tracking covers the basics, with marketplace apps available for advanced business-hours accuracy and cross-project reporting .

- **[BMC Helix ITSM](https://www.bmc.com/)**  
  Service Level Management module for defining and enforcing service targets and agreements, with automatic notifications for approaching or breaching targets; offered as a configured service through BMC's Success Catalog covering up to 8 out-of-box service targets and 1 agreement .

- **[Ivanti Neurons for ITSM](https://www.ivanti.com/)**  
  Service Level Package (SLP) model with out-of-box support for tiered SLAs (Platinum/Gold/Silver/Bronze) mapped to Organization + Service combinations, priority-based overrides, and the ability to extend with custom lookup tables for more granular SLA determination (e.g., adding Application as a third matching variable) .

- **[ManageEngine ServiceDesk Plus](https://www.manageengine.com/products/service-desk/)**  
  Site-specific SLAs, separate SLA configurations for incidents and service requests, automatic SLA assignment based on priority/impact/urgency/department/requester/category, SLA timer suspension while awaiting end-user response, and multi-level proactive/reactive escalations with custom email templates .

- **[HaloITSM](https://www.haloitsm.com/)**  
  Configurable SLA definitions with Respond-by and Resolution targets per priority level, working-days/hours scoping, automatic resolution target extension to end of working day, prompt-for-reason on breach, delay-start option for after-hours requests, and override fix-by-date with Start Date or Target Date fields .

- **[TOPdesk](https://www.topdesk.com/)**  
  Service level management for tracking throughput times and SLAs, with overview of all customer contracts and agreements covering availability, response times, and processing times per customer; combines SLA and XLA (experience level agreement) metrics with feedback collection and BI-tool reporting integration .

- **[SysAid](https://www.sysaid.com/)**  
  AI-assisted SLA management with rules by user/group/category/time, customizable thresholds and priorities, real-time color-coded SLA dashboards with 60-day trend monitoring, automatic alerts before targets slip, and SysAid Copilot AI Agents for smart prioritization and proactive escalation .

- **[SolarWinds Service Desk](https://www.solarwinds.com/service-desk)**  
  SLA rule creation with target definition, timer indication thresholds, scope settings, and automated actions on breach; color-coded timers (green/orange/red) in incident lists for at-a-glance breach risk, next-breach countdown for queue prioritization, and comprehensive SLA reporting for vendor and service quality decisions .

## Open-Source GitHub Projects

- **[iTop](https://github.com/Combodo/iTop)**  
  Complete open-source, web-based IT service management platform (ITIL-compliant) with fully configurable CMDB, helpdesk and incident management, service and contract management, and **configurable SLA management**; includes graphical impact analysis and CSV import tools for data synchronization; AGPL-3.0 licensed and extensible via add-ons and web services .

- **[Pulse](https://github.com/Erchoc/pulse)**  
  Lightweight, self-hosted **SLA monitoring platform** built with Go and React; deploys global probes for multi-protocol monitoring (HTTP, TCP, WebSocket, DNS, ICMP, client heartbeat), provides real-time SLA dashboards with live availability percentages and latency percentiles, supports service-level SLA targets with configurable reporting windows (rolling 7D–365D), maintenance windows that exclude downtime from SLA calculations, incident tracking with status transitions, and webhook alerts to Slack/DingTalk/Feishu; single-binary deployment with Docker support .

### Additional Strong Open-Source Options

- **Znuny** — Open-source ITSM platform (OTRS fork) with SLA handling, escalation workflows, and ticket lifecycle management; suitable for organizations needing ITIL-aligned ticketing with SLA tracking.
- **osTicket** — Widely used open-source support ticket system with basic SLA and due-date tracking for smaller teams.
- **FreeITSM** — Open-source ITSM tool with focus on simplicity and data ownership; provides foundational ticket management that can be extended with SLA tracking logic.

**Frameworks for building custom systems**: Combine **iTop** for ITIL-aligned ITSM with native SLA management, **Pulse** for dedicated uptime and availability SLA monitoring, and **Znuny** for ticket-level SLA escalation workflows in a self-hosted service level management stack; integrate with existing monitoring tools for comprehensive service performance visibility.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- SLM platforms handling service and customer data must comply with applicable regulations and contractual obligations; SLA definitions should align with actual service capabilities and legal commitments.
- Self-hosted open-source solutions require proper security hardening, business-hours calendar configuration, and escalation workflow customization.
- Verify license terms for commercial use; iTop uses AGPL-3.0, Pulse uses a permissive open-source license, and Znuny uses GPL-3.0.

---

**Made for IT service managers, SLA analysts, help desk administrators, and service delivery teams.**  
Let's make service level management more open, measurable, and accountable.
