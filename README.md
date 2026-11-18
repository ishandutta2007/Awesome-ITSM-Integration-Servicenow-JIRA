# Awesome-ITSM-Integration-Servicenow-JIRA

## Top ITSM Integration (ServiceNow / Jira) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on ITSM Connectors, Bidirectional Ticket Syncing, Workflow Automation, DevOps-to-ITSM Bridges & Open-Source ITSM/Issue Trackers*  

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **ITSM Integration (ServiceNow / Jira)**. These tools synchronize tickets, incidents, change requests, CMDB assets, and alert events bidirectionally between enterprise ITSM systems (like ServiceNow and Jira Service Management) and monitoring, backup, DevOps, and open-source service desk platforms.



**Examples** include Druva Service Management, ServiceNow ITSM, Jira Service Management, Freshservice, Zendesk Support, Cherwell, Ivanti Neurons for ITSM, BMC Helix ITSM, SolarWinds Service Desk, SysAid, and HaloITSM (the category leaders). 



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, ITSM/Jira workflow automation, monitoring-to-ticket bridges, bidirectional issue sync, and open-source ServiceNow/Jira alternatives — ideal for ITSM architects, DevOps engineers, SREs, and enterprise integration developers.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global IT Service Management (ITSM) software market is estimated at approximately **$14.8 billion to $17.4 billion in 2026** (growing toward $30B+ by the early 2030s at ~13–14% CAGR). The sector exhibits a **hybrid market structure**: it is **highly concentrated at the enterprise tier** dominated by platform ecosystems (notably ServiceNow, followed by Atlassian and BMC in a near winner-take-most dynamic for unified IT/ESM operations), yet **moderately fragmented in the mid-market and SMB tiers** where agile challengers compete aggressively on deployment speed and cost.

## SaaS/Hosted Platforms

| Platform | Company Valuation / Revenue | Pricing | Free Tier Limits | Key ITSM & Integration Capabilities |
| :--- | :--- | :--- | :--- | :--- |
| **[ServiceNow ITSM & Integration Hub](https://servicenow.com)** | ~$130B Market Cap / ~$13.3B FY2025 Revenue | Starts at ~$70 - $100/fulfiller/month (Foundation tier, billed annually) | No production free tier or commercial free trial; non-production Personal Developer Instance (PDI) available free for learning (auto-reclaimed after 10 days of inactivity) | Enterprise ITSM suite with Integration Hub spokes for bidirectional synchronization with Jira, Slack, Azure DevOps, monitoring, and backup platforms. |
| **[Jira Service Management](https://atlassian.com)** (Atlassian) | ~$38B Market Cap / ~$5.2B FY2025 Revenue | Starts at $20 - $23.80/agent/month (Standard tier) | Free forever plan available: strictly limited to **up to 3 agents**, 2 GB file storage, 100 email notifications/day, and unlimited customer requestors | Collaborative ITSM platform bridging development and operations with native Jira Software linking, Opsgenie alerting, and REST/webhook integrations. |
| **[Zendesk Support](https://zendesk.com)** | ~$10.2B Acquisition Valuation / ~$1.7B ARR | Starts at $19/agent/month (Support Team, billed annually) | No permanent free plan; offers a **14-day free trial** with full access to Zendesk Suite Professional features (no credit card required) | Omnichannel support and helpdesk suite with dedicated Jira and ServiceNow marketplace apps for escalating customer issues into engineering tickets. |
| **[BMC Helix ITSM](https://bmc.com)** | ~$8.3B Buyout Valuation / ~$2.3B Revenue | Starts at ~$115 - $130/user/month (estimated list pricing for named agents, annual contracts) | No self-service free tier or public trial; enterprise proof-of-concept (PoC) sandboxes available upon sales consultation | Enterprise multi-cloud service management providing automated ticket brokering across Jira, ServiceNow, AWS, and Salesforce ecosystems. |
| **[Freshservice](https://freshworks.com)** (Freshworks) | ~$3.3B Market Cap / ~$930M ARR | Starts at $19/agent/month (Starter tier, billed annually) | No permanent free plan; provides a **14-day free trial** with enterprise-tier feature access and trial agent day passes (no credit card required) | Cloud-native ITSM suite with an App Marketplace featuring turnkey connectors for Jira, ServiceNow orchestration, Azure AD, and DevOps pipelines. |
| **[SolarWinds Service Desk](https://solarwinds.com)** | ~$3.2B Market Cap / ~$797M Revenue | Starts at $39/technician/month (Essentials tier, billed annually) | No permanent free plan; offers a **30-day fully functional free trial** with complete access to Premier-tier AI, automation, and asset features | Cloud ITSM platform featuring built-in integrations for Jira issue tracking, Orion monitoring alerts, and automated change workflows. |
| **[Ivanti Neurons for ITSM](https://ivanti.com)** | ~$2.0B Valuation / ~$1.2B - $1.5B Revenue | Starts at ~$25 - $59/user/year (baseline editions) to ~$95/analyst/month (advanced modules) | No self-service free tier or open trial; custom-guided enterprise demonstrations and sales-led evaluation sandboxes only | Enterprise service management offering bidirectional connectors for Jira, ServiceNow, endpoint management, and self-healing automation bots. |
| **[HaloITSM](https://haloitsm.com)** | ~$2.0B Valuation / ~$100M ARR | Starts at £65 - £69/agent/month (approx. $49 - $99/agent/month depending on team volume) | No permanent free plan; offers an unrestricted **30-day free trial** with all ITSM modules and integrations included (no credit card required) | Modern ITIL service desk providing two-way Jira and Azure DevOps synchronization, webhook automation, asset management, and custom REST API integrations. |
| **[Druva Service Management](https://druva.com)** | ~$2.0B Valuation / ~$200M+ ARR | Starts at $8/user/month (SaaS/endpoint backup) or custom TB/month consumption for cloud infrastructure | No permanent free plan; offers a **30-day free trial** for cloud and SaaS workload data protection (no credit card required) | Cloud data resiliency platform with native ServiceNow and Jira integrations to automate backup failure ticketing, cyber recovery, and legal hold workflows. |
| **[SysAid](https://sysaid.com)** | ~$30M Raised / ~$30M - $37M Revenue | Starts at $89/agent/month (Professional AI plan, billed annually) | No permanent free plan; offers a **14-day free trial** with access to core ITSM, AI Copilot, and asset management modules (no credit card required) | Service management platform featuring native Jira integration, automated alert-to-ticket creation, and IT asset synchronization. |



## Open-Source GitHub Projects



- **[n8n](https://github.com)**  

  Leading open-source workflow automation platform with native ServiceNow, Jira, Zendesk, Freshdesk, and webhook nodes for building bidirectional ITSM sync pipelines.



- **[Keep](https://github.com)**  

  Open-source AIOps and alert management platform offering two-way integrations with ServiceNow, Jira, and monitoring tools to auto-create and close tickets.



- **[GLPI (with ITSM & DevOps Plugins)](https://github.com)**  

  Flagship open-source ITSM and CMDB platform featuring REST APIs, webhooks, and community connectors for syncing tickets and assets with external trackers.



- **[iTop (IT Operational Portal)](https://github.com)**  

  Comprehensive open-source ITIL ITSM and CMDB system with extensible webhook triggers, REST/JSON APIs, and extensions for external issue tracker synchronization.



- **[Zammad](https://github.com)**  

  Modern open-source helpdesk and ticketing platform providing native Jira, GitLab, GitHub, and Monitoring (Nagios/Icinga/Checkmk) integrations out of the box.



- **[Znuny (OTRS Community Fork)](https://github.com)**  

  Enterprise open-source service desk featuring a Generic Interface (REST/SOAP web services) purpose-built for bidirectional ServiceNow and Jira ticket integration.



- **[OTOBO](https://github.com)**  

  Modernized open-source OTRS-based ITSM suite with native REST/SOAP connectors for synchronizing incidents and changes with external enterprise platforms.



- **[Plane](https://github.com)**  

  Open-source project and issue tracking alternative to Jira featuring webhooks, REST APIs, and modular workflows for engineering and IT operations teams.



- **[OpenProject](https://github.com)**  

  Enterprise open-source project and issue management software supporting agile boards, ITIL change tracking, GitHub/GitLab links, and API integrations.



- **[Redmine](https://github.com)**  

  Battle-tested open-source issue tracking and project management platform widely extended with plugins for ServiceNow/Jira migration and helpdesk ticketing.



- **[Taiga](https://github.com)**  

  Open-source agile project management and issue tracking platform with webhooks and APIs for bridging support desks and development sprints.



- **[Huly](https://github.com)**  

  All-in-one open-source workspace combining Jira-style issue tracking, knowledge base, and team chat with extensible APIs.



- **[Apache DevLake](https://github.com)**  

  Open-source DevOps data lake that ingests, normalizes, and correlates data from Jira, ServiceNow/incident tools, GitHub, and Jenkins into unified metrics.



- **[Prometheus Alertmanager](https://github.com)**  

  Core open-source alert router capable of forwarding infrastructure alerts directly into ServiceNow, Jira Service Management, and Zammad via webhook receivers.



- **[Grafana OnCall](https://github.com)**  

  Open-source on-call and incident response tool featuring native outgoing webhooks and integrations to automatically open and update Jira and ServiceNow tickets.



- **[Dispatch (by Netflix)](https://github.com)**  

  Open-source crisis and incident management orchestration framework that automatically creates Jira tickets, Slack channels, and incident timelines.



- **[Rundeck](https://github.com)**  

  Open-source runbook automation platform frequently integrated with ServiceNow and Jira to execute automated remediation jobs directly from approved change tickets.



- **[StackStorm](https://github.com)**  

  Event-driven open-source automation platform ("IFTTT for Ops") with dedicated ServiceNow and Jira packs for auto-remediation and ticket enrichment.



- **[Activepieces](https://github.com)**  

  Open-source no-code/low-code automation tool providing visual triggers and actions for Jira, Zendesk, Freshdesk, Slack, and custom REST APIs.



- **[Windmill](https://github.com)**  

  Open-source developer platform for building script-driven Python/TypeScript workflows that sync records between ServiceNow, Jira, and internal databases.



### Additional Strong Open-Source Options



- **[Python & Node.js ServiceNow/Jira SDKs (`pysnow`, `jira.js`, `atlassian-python-api`)](https://github.com)** for writing custom bidirectional ticket sync microservices and CMDB importers.

- **[Alert-to-Ticket Webhook Bridges (`prometheus-servicenow-webhook`, `jira-alertmanager`)](https://github.com)** for translating monitoring alerts into structured ITSM incidents.

- **[Backstage ServiceNow & Jira Plugins](https://github.com)** for surfacing live ITSM change requests, incidents, and Jira boards inside internal developer portals.

- **[Ansible ServiceNow ITSM Collection (`servicenow.itsm`)](https://github.com)** for automating CMDB updates, incident creation, and change approvals inside Infrastructure-as-Code playbooks.

- Many community **Docker Compose integration stacks** combining **n8n**, **Keep**, and **Zammad / GLPI** for automated, self-hosted ITSM orchestration.



**Frameworks for building custom systems**: Combine **n8n** or **StackStorm** with **Keep**, **Zammad / GLPI** (or **Plane** for Jira workflows), and **Rundeck** alongside **Ansible** for automated, bidirectional ITSM integration pipelines.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.
