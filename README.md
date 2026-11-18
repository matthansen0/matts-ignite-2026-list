# 🚀 Matt's List of Ignite 2026 Announcements

> *The Ignite Book of News is great, but it doesn't include all the great work across the rest of the Microsoft products.*

This is a personal collection of announcements and updates from **Microsoft Ignite 2026**, organized by product area for navigation and reference.

**Last Updated:** November 18, 2026 at 6:25AM EST

**🎯 What's Inside:** 232 announcements across Infrastructure, Apps, Data, AI, Microsoft 365, Windows, GitHub, and Security with direct links to official documentation and blog posts.

---

## 📋 Table of Contents

- [🏗️ Infrastructure & Cloud](#️-infrastructure--cloud)
- [🔧 Apps & Developer Platform](#-apps--developer-platform)
- [📊 Data & Fabric](#-data--fabric)
- [🤖 AI, Agents & Copilot](#-ai-agents--copilot)
- [💼 Microsoft 365 & Business Applications](#-microsoft-365--business-applications)
- [🪟 Windows, Devices & Edge](#-windows-devices--edge)
- [🐙 GitHub & Developer Tools](#-github--developer-tools)
- [🔒 Security & Governance](#-security--governance)

---

## 🏗️ Infrastructure & Cloud

> *Compute and silicon, storage, networking, operations, resiliency, hybrid and sovereign cloud*

### Key Announcements

- **Overview:**
    - [Microsoft Ignite 2026: What's new in Azure](https://azure.microsoft.com/en-us/blog/microsoft-ignite-2026-whats-new-in-azure-the-platform-purpose-built-for-ai/)  
      *Azure's Ignite roundup: Cobalt 200, Azure Catalyst, HorizonDB, Fabric apps, Microsoft IQ and a new Copilot Credits billing option for Fabric.*

- **Compute & silicon:**
    - [Azure Cobalt 200 VMs - GA](https://azure.microsoft.com/en-us/blog/azure-cobalt-200-vms-now-available-proven-on-real-workloads-and-built-for-the-agentic-era/) | [Azure Update](https://azure.microsoft.com/updates?id=581298)  
      *Second-gen Microsoft Arm VMs with up to 50% more CPU performance, new Mpsv4/Lpsv5 families and selectable processor modes.*
    - [Ebsv6 and Ebdsv6 VMs - GA](https://techcommunity.microsoft.com/blog/azurecompute/announcing-general-availability-of-azure-ebsv6-vms-powered-by-intel%C2%AE-xeon%C2%AE-proce/4573333) | [Azure Update](https://azure.microsoft.com/updates?id=581160)  
      *Intel Xeon 5th Gen VMs with Azure Boost, optimized for high remote storage throughput.*
    - [DHasv8, DHalsv8 and EHasv8 VMs (AMD EPYC "Venice") - Preview](https://techcommunity.microsoft.com/blog/AzureCompute/announcing-preview-of-new-azure-dhehasv8-vms-based-on-6th-gen-amd-epyc%E2%84%A2-%E2%80%9Cvenice%E2%80%9D/4573295) | [Azure Update](https://azure.microsoft.com/updates?id=581308)  
      *6th Gen AMD EPYC VMs up to 480 cores and 3.8 TiB memory for agentic AI and database workloads.*
    - [Mv4 with CXL memory, Mv4 Medium Memory and Mbv4 VMs - GA + Preview](https://techcommunity.microsoft.com/blog/sapapplications/azure-mv4-at-ignite-2026-advancing-performance-scalability-and-tco-with-cxl/4573907)  
      *CXL-attached memory up to 8 TB (private preview), Mv4 Medium Memory GA and storage-optimized Mbv4 for SAP, SQL Server and Epic.*
    - [Next-gen confidential VMs on 5th Gen AMD EPYC - Private Preview](https://techcommunity.microsoft.com/blog/AzureConfidentialComputingBlog/announcing-gated-preview-of-next-gen-azure-confidential-vms-with-5th-generation-/4570276) | [Azure Update](https://azure.microsoft.com/updates?id=581199)  
      *Gated preview of DCasv7/ECasv7-family AMD SEV-SNP confidential VMs.*
    - [Confidential AI at rack scale on NVIDIA Vera Rubin NVL72 - Technology Preview](https://techcommunity.microsoft.com/blog/AzureConfidentialComputingBlog/confidential-ai-at-rack-scale-introducing-azure%E2%80%99s-vera-rubin-nvl72-technology-pr/4570354)  
      *Multi-GPU confidential computing to protect large models that span a full rack.*
    - [Azure Compute Spot plus - Public Preview](https://techcommunity.microsoft.com/blog/AzureCompute/public-preview-azure-compute--spot-plus/4573059) | [Azure Update](https://azure.microsoft.com/updates?id=581145)  
      *Premium Spot tier targeting 60+ minute runtime, no charge for early eviction, and up to 2-minute notices.*
    - [Compute templates - Limited Preview](https://techcommunity.microsoft.com/blog/AzureCompute/announcing-preview-of-compute-templates-in-azure/4570751) | [Azure Update](https://azure.microsoft.com/updates?id=580624)  
      *Reusable, versioned VM configurations stored in Azure Compute Gallery and referenced at VM create time.*
    - [VM adaptive placement - Public Preview](https://techcommunity.microsoft.com/blog/AzureCompute/announcing-public-preview-of-vm-adaptive-placement/4572196) | [Azure Update](https://azure.microsoft.com/updates?id=581244)  
      *Name a preferred VM size; Azure falls back to a compatible same-vCPU size when capacity is tight.*
    - [Azure Artifact Validation for VM images - Public Preview](https://techcommunity.microsoft.com/blog/AzureCompute/public-preview-azure-artifact-validation-%E2%80%93-self-serve-validation-for-vm-images/4573178) | [Azure Update](https://azure.microsoft.com/updates?id=581249)  
      *Self-serve service letting image publishers and platform teams run Azure's VM image validation checks.*
    - [Azure Compute Fleet single-instance launch and vCPU-based capacity - GA](https://techcommunity.microsoft.com/blog/AzureCompute/generally-available-single-instance-launch-mode-and-vcpu-based-capacity-for-azur/4570380)  
      *Compute Fleet adds one-time single-instance launches and capacity requests expressed in vCPUs.*
    - [Zone resilience for Azure VMs](https://techcommunity.microsoft.com/blog/AzureCompute/zone-resilience-for-azure-vms/4573176)  
      *Recover an eligible VM into another availability zone in the same region.*

- **AI infrastructure for agents:**
    - [Azure Catalyst and new AI infrastructure: Agent Grid, Agent Sandbox, Flex nodes for AKS - GA + Preview](https://azure.microsoft.com/en-us/blog/introducing-azure-catalyst-agentic-modernization-and-new-ai-infrastructure-innovations/)  
      *Azure blog post introducing Catalyst plus agent networking, isolation and hybrid AKS capacity for production AI.*
    - [Agent Grid - Public Preview](https://azure.microsoft.com/updates?id=580684)  
      *Identity-based Zero Trust network security for agent, model and tool traffic on Azure.*
    - [Flex nodes for AKS - Public Preview](https://azure.microsoft.com/en-us/blog/introducing-azure-catalyst-agentic-modernization-and-new-ai-infrastructure-innovations/)  
      *Extends AKS node pools to supported GPU and server environments beyond Azure, governed through Azure Arc.*

- **Storage & backup:**
    - [Azure Elastic SAN Next Generation - Public Preview](https://azure.microsoft.com/updates?id=581634)  
      *Next-gen Elastic SAN keeps the shared-performance SAN model while raising scale and performance.*
    - [Azure Blob Storage turbo tier - Public Preview](https://azure.microsoft.com/updates?id=579031)  
      *SSD-backed tier for performance-sensitive blob data such as AI training, inference and analytics.*
    - [Session-based authentication for Blob and Data Lake Storage - Public Preview](https://azure.microsoft.com/updates?id=580306)  
      *Cuts per-request auth overhead for AI agents and apps while keeping existing security controls.*
    - [Azure Files NFS shares on HDD - Public Preview](https://azure.microsoft.com/updates?id=579369)  
      *Lower-cost HDD option for Linux NFS file shares alongside the existing SSD tier.*
    - [Immutable snapshots for Azure Disk Storage - Public Preview](https://azure.microsoft.com/updates?id=581503)  
      *Tamper-proof short-term disk snapshots that complement immutable Azure Backup vaults.*
    - [Quick Attach Detach (QAD) for managed disks - Limited Preview](https://techcommunity.microsoft.com/blog/AzureCompute/quick-attach-detach-limited-preview-bringing-faster-more-resilient-storage-mobil/4574172)  
      *Faster, more resilient managed-disk attach and detach operations, coming to AKS and more.*

- **Networking:**
    - [Azure Multicloud Interconnect - GA](https://azure.microsoft.com/updates?id=579766)  
      *Managed private connectivity between Azure and other clouds (Google Cloud in preview).*
    - [ExpressRoute Direct link groups - Public Preview](https://azure.microsoft.com/updates?id=580926)  
      *Aggregate multiple ExpressRoute Direct links to scale throughput with less operational overhead.*
    - [Application Gateway v2 elastic architecture - Public Preview](https://azure.microsoft.com/updates?id=580428)  
      *Faster provisioning and autoscaling for Application Gateway under bursty traffic.*
    - [Application Gateway advanced load balancing - Public Preview](https://azure.microsoft.com/updates?id=580423)  
      *Finer traffic distribution controls across backends, including AI application traffic.*
    - [Application Gateway centralized user authentication and JWT validation - Public Preview](https://azure.microsoft.com/updates?id=580418)  
      *Gateway signs users in with OpenID Connect and validates tokens before traffic hits apps.*
    - [Application Gateway advanced routing rules - Public Preview](https://azure.microsoft.com/updates?id=579324)  
      *Route on richer request attributes beyond traditional path and host rules.*
    - [Application Gateway confidential compute - Public Preview](https://azure.microsoft.com/updates?id=579649)  
      *Runs the gateway data plane in a TEE so decrypted traffic stays protected while processed.*
    - [Network security perimeter: service tags as inbound rules - Public Preview](https://azure.microsoft.com/updates?id=579201)  
      *Allow inbound access to perimeter-protected resources by service tag.*
    - [Network security perimeter: cross-perimeter connectivity - Public Preview](https://azure.microsoft.com/updates?id=579206)  
      *Securely connect resources that sit in different network security perimeters.*
    - [Network Watcher AI-assisted diagnostics - Public Preview](https://azure.microsoft.com/updates?id=578602) | [Packet capture insights](https://azure.microsoft.com/updates?id=578172) | [ExpressRoute connection analyzer](https://azure.microsoft.com/updates?id=578617) | [Auto-create connection monitor](https://azure.microsoft.com/updates?id=578611)  
      *AI summaries for connection troubleshoot, packet capture insights, ExpressRoute loss analysis and auto-created monitors.*
    - [Network Watcher rule recommendations and flow log enrichments - Public Preview](https://azure.microsoft.com/updates?id=578797) | [Connection monitor health metrics](https://azure.microsoft.com/updates?id=578623) | [Private Link flow log enrichment](https://azure.microsoft.com/updates?id=578792) | [NIC IP flow log context](https://azure.microsoft.com/updates?id=578787)  
      *Rule recommendations, connection-monitor health metrics and richer VNet flow log context.*

- **Operations, observability & resiliency:**
    - [Advancing agentic operations: Azure Copilot deployment agent, spaces and custom skills - GA + Preview](https://techcommunity.microsoft.com/blog/azureinfrastructureblog/advancing-agentic-operations-on-azure-at-ignite-2026/4573831)  
      *Deployment agent GA, Azure Copilot spaces and custom skills, ARM MCP Server write actions, Workload Center and SRE Agent customer-managed keys.*
    - [Azure Monitor health models - GA](https://azure.microsoft.com/updates?id=580261)  
      *Model workload health from metrics, logs and dependencies as a first-class, business-aware construct.*
    - [Azure Monitor Application Insights traces experience - Public Preview](https://azure.microsoft.com/updates?id=580184)  
      *Compare thousands of distributed traces and drill from trends to root cause.*
    - [Azure Workload Center for SAP and Oracle - Preview](https://azure.microsoft.com/updates?id=581209) | [Oracle](https://azure.microsoft.com/updates?id=581214)  
      *Workload-aware health monitoring and configuration validation for SAP and Oracle, paired with Azure Copilot Run agents.*
    - [Azure Infrastructure Resiliency Manager - GA](https://azure.microsoft.com/updates?id=580748)  
      *Goal-driven resiliency hub: zone-resilient templates, at-scale assessments, drills and recovery guidance.*
    - [Azure Chaos Studio workspaces and AKS extension - GA](https://techcommunity.microsoft.com/blog/appsonazureblog/run-models-and-agents-on-your-own-kubernetes-clusters-aks-at-microsoft-ignite-20/4573912)  
      *Reusable disruption scenarios such as zone loss or database failover, plus lower-privilege fault injection into AKS pods.*
    - [What's new in Azure SRE Agent at Ignite 2026 - GA + Preview](https://techcommunity.microsoft.com/blog/appsonazureblog/what%E2%80%99s-new-in-azure-sre-agent-at-microsoft-ignite-2026/4573607)  
      *Teams and Slack, Entra Agent ID and Agent 365, AWS/Google Cloud connectors, A2A, Grafana, Azure CLI and connector triggers.*
    - [Azure SRE Agent in Microsoft Teams - Public Preview](https://azure.microsoft.com/updates?id=580753)  
      *Start and follow investigations with the SRE agent in Teams chats, channels and meetings.*
    - [Azure SRE Agent: AWS and Google Cloud connectors - Public Preview](https://azure.microsoft.com/updates?id=580975)  
      *Investigate incidents across Azure, AWS and Google Cloud evidence from one agent.*
    - [Azure SRE Agent: Agent-to-Agent (A2A) protocol - Public Preview](https://azure.microsoft.com/updates?id=580758)  
      *SRE agents hand off and accept tasks from other agents while keeping each team's permissions.*
    - [Azure SRE Agent with Entra Agent ID and Agent 365 - Public Preview](https://azure.microsoft.com/updates?id=580763)  
      *Govern SRE agents alongside other enterprise agents with their own Agent IDs.*
    - [Azure SRE Agent in Slack - Private Preview (coming)](https://azure.microsoft.com/updates?id=580768)  
      *Work incident investigations with the SRE agent directly in Slack channels.*
    - [On-demand Azure SRE Agent debugging in Azure Container Apps - Public Preview](https://techcommunity.microsoft.com/blog/AppsonAzureBlog/azure-sre-agent-brings-on-demand-ai-powered-operations-to-your-aca-workloads/4573380)  
      *'Debug with SRE Agent' starts serverless, read-only troubleshooting sessions for any container app, nothing to deploy.*

- **Hybrid, edge & sovereign cloud:**
    - [GCP support in the Azure Arc Multicloud Connector - GA](https://techcommunity.microsoft.com/blog/AzureArcBlog/announcing-general-availability-of-gcp-support-in-the-azure-arc-multicloud-conne/4571208)  
      *Inventory and manage Google Cloud resources from Azure through the Arc Multicloud Connector.*
    - [Azure VM Applications for Arc-enabled servers - Public Preview](https://techcommunity.microsoft.com/blog/AzureArcBlog/azure-vm-applications-for-azure-arc-enabled-servers-now-in-public-preview/4574065)  
      *Package, version and deploy apps to Arc-enabled servers via Azure Compute Gallery VM Applications.*
    - [Configuration Manager connector for Azure Arc - Public Preview](https://techcommunity.microsoft.com/blog/AzureArcBlog/announcing-the-configuration-manager-connector-for-azure-arc-preview/4569994)  
      *Brings Configuration Manager server inventory, roles and installed apps into Azure via Arc.*
    - [Windows Recovery Environment for Arc-enabled Windows servers - Public Preview](https://techcommunity.microsoft.com/blog/AzureArcBlog/get-your-arc-enabled-windows-servers-back-online-faster-with-windows-recovery-en/4572573)  
      *Remote recovery path to bring crashed Arc-enabled Windows servers back online faster.*
    - [TPM-backed and user-assigned identities for Arc-enabled servers - Public Preview](https://techcommunity.microsoft.com/blog/AzureArcBlog/securing-azure-arc-enabled-servers-with-tpm-backed-identity-and-user-assigned-id/4570025)  
      *Hardware-rooted TPM identity and user-assigned managed identities to protect Arc server identities.*
    - [Azure Local on NVIDIA Jetson Thor - Public Preview](https://techcommunity.microsoft.com/blog/AzureArcBlog/build-intelligent-physical-systems-with-azure-local-preview-on-nvidia-jetson/4574150)  
      *Run Azure Local on NVIDIA Jetson for robotics and intelligent physical systems at the edge.*
    - [Sovereign Control Panel - Public Preview](https://azure.microsoft.com/updates?id=581220)  
      *Azure portal view to assess and continuously monitor sovereignty posture and evidence.*
    - [Data Guardian in the Sovereign Control Panel - Available](https://azure.microsoft.com/updates?id=581226)  
      *Surface Data Guardian oversight of Microsoft engineer access to EU production systems from the panel.*
    - [Production Touch Ledger assessment report - Announced](https://azure.microsoft.com/updates?id=581221)  
      *Independent Capgemini validation of the tamper-evident ledger of production-access records.*
    - [Project NOVA - In Development](https://azure.microsoft.com/updates?id=581193)  
      *Zero-knowledge-style verification of specific claims without revealing underlying data.*

- **Windows Server:**
    - [Windows Server 2028 - Public Preview](https://azure.microsoft.com/updates?id=581135) | [Windows blog](https://blogs.windows.com/windowsexperience/2026/11/17/microsoft-ignite-2026-building-windows-for-the-next-era-of-work/)  
      *Next LTSC release: hardened defaults, PQC, NVMe-oF, Arc/Intune management and hybrid AI inference.*
    - [Hardened Server Core for Windows Server Insiders - Announced](https://techcommunity.microsoft.com/blog/windowsservernewsandbestpractices/announcing-hardened-server-core-for-windows-server-insiders/4574239)  
      *Secure-by-default Server Core option that ships hardened instead of compatible-by-default, for Insiders.*

### Notable Updates

- **Compute & silicon:**
    - [Azure Linux 4.0 for VMs and VM Scale Sets - GA](https://azure.microsoft.com/updates?id=581165)  
      *Microsoft's first-party Linux distribution built for Azure, now generally available for IaaS.*
    - [IBM Spectrum LSF with Azure Compute Fleet - GA](https://azure.microsoft.com/updates?id=581259)  
      *LSF resource connector bursts HPC jobs into Azure Compute Fleet capacity on demand.*
    - [Azure Boost observability for NVMe disks - Announced](https://azure.microsoft.com/updates?id=581227)  
      *Open-source in-VM tool exposing remote disk I/O and latency metrics mapped to each managed disk.*
    - [Soft delete in Azure Compute Gallery - GA](https://techcommunity.microsoft.com/blog/AzureCompute/soft-delete-in-azure-compute-gallery-is-now-generally-available/4568500)  
      *Recover deleted gallery images with configurable 7-365 day retention and up to 90-day grace periods.*
    - [HDv2-series VMs (AMD EPYC "Venice")](https://techcommunity.microsoft.com/blog/AzureInfrastructureBlog/visit-azure-and-amd-at-microsoft-ignite-and-sc26/4570345)  
      *500+ core, 3.8 TB memory VMs for AI data preparation and HPC, previewed for Ignite and SC26.*

- **Storage & backup:**
    - [Snapshot-based backup for SQL Server on Azure VMs - GA](https://azure.microsoft.com/updates?id=564668)  
      *Azure Backup combines disk snapshots with SQL log backups for fast, low-impact full backups.*

---

## 🔧 Apps & Developer Platform

> *Containers, serverless, app hosting, integration, APIs and modernization*

### Key Announcements

- **Azure Kubernetes Service & containers:**
    - [AKS at Ignite 2026: run Foundry models and agents on your own clusters - GA + Preview](https://techcommunity.microsoft.com/blog/appsonazureblog/run-models-and-agents-on-your-own-kubernetes-clusters-aks-at-microsoft-ignite-20/4573912)  
      *AKS AI Manager for Foundry, hosted agents on AKS, managed GPU node pools, GB200/GB300 sizes, node hardening and Fleet Manager updates.*
    - [AKS managed agent sandboxes - Public Preview](https://azure.microsoft.com/updates?id=580916)  
      *Per-session isolated sandboxes on AKS for agents that run untrusted, model-generated code.*
    - [AKS sandbox snapshot and restore - Public Preview](https://azure.microsoft.com/updates?id=580921)  
      *Resume sandboxed workloads with in-memory state instead of repeating costly warm-up.*
    - [AKS faster Kata VM-isolated pods - Public Preview](https://azure.microsoft.com/updates?id=581120)  
      *New kata-vm-isolation flow reduces cold-start latency and memory overhead for sandboxed pods.*
    - [AKS Confidential VM node pools with Intel TDX - GA](https://azure.microsoft.com/updates?id=581130)  
      *Run TDX-attested confidential workloads on AKS, not just AMD SEV-SNP.*
    - [AKS Ubuntu 26.04 Confidential VM node pools with OS disk encryption - Public Preview](https://azure.microsoft.com/updates?id=581125)  
      *Closes the data-at-rest gap for confidential node pools.*
    - [Trusted Launch for AKS Windows node pools - Public Preview](https://azure.microsoft.com/updates?id=572591)  
      *Boot-chain protection for Windows Server 2025 node pools on AKS.*
    - [Azure Red Hat OpenShift with hosted control planes - GA](https://azure.microsoft.com/updates?id=580136)  
      *Separates the OpenShift control plane from worker nodes for faster, lower-cost clusters.*

- **App Service & Azure Functions:**
    - [App Service Ignite 2026 updates - GA + Preview](https://techcommunity.microsoft.com/blog/AppsonAzureBlog/app-service-ignite-2026-updates/4572673)  
      *.NET 11 and Python 3.15 GA, Markdown for Agents, post-quantum TLS, Grafana dashboards, plan start/stop and a refreshed portal.*
    - [Azure App Service Builder - Public Preview](https://azure.microsoft.com/updates?id=578817)  
      *Source-connected way to build, deploy and host apps without hand-built pipelines.*
    - [Geo-redundancy in Azure App Service - Public Preview](https://azure.microsoft.com/updates?id=578839)  
      *Run web apps across Azure regions for higher resilience.*
    - [What's new in Azure Functions and Durable Task Scheduler - GA + Preview](https://techcommunity.microsoft.com/blog/AppsonAzureBlog/whats-new-in-azure-functions-and-durable-task-scheduler-at-microsoft-ignite-2026/4573933)  
      *Managed connectors, agent bindings, Functions Canvas and Skills, Durable Task for LangGraph and Pydantic AI, CLI v5 and new runtimes.*
    - [Managed connectors in Azure Functions - GA](https://azure.microsoft.com/updates?id=579440)  
      *Trigger on and act across Microsoft 365, SaaS and business systems using the Functions model.*
    - [Azure Functions hosted skill and agent bindings - Public Preview](https://azure.microsoft.com/updates?id=578845)  
      *Add agents and skills to Functions apps through bindings instead of custom plumbing.*
    - [Durable Task extension for Microsoft Agent Framework - GA](https://azure.microsoft.com/updates?id=578829)  
      *Durable, resumable agents and multi-agent workflows in C# and Python.*
    - [Go on Azure Functions Flex Consumption - GA](https://azure.microsoft.com/updates?id=578812)  
      *First-class, code-first Go worker for Flex Consumption apps.*
    - [OS-level dependencies via containers on Flex Consumption - Public Preview](https://azure.microsoft.com/updates?id=578975)  
      *Bring native OS dependencies to Flex Consumption apps through containers.*
    - [Azure Functions Network Troubleshooter v2 - Public Preview](https://azure.microsoft.com/updates?id=578980)  
      *Top-down view of a function app's network dependencies across Storage, Service Bus and more.*
    - [Azure Functions: Node.js 26 and Python 3.15 - Public Preview](https://azure.microsoft.com/updates?id=578807) | [Python 3.15](https://azure.microsoft.com/updates?id=578802)  
      *Early runtime support to validate JavaScript/TypeScript and Python apps.*
    - [Durable Task Scheduler: task queues, DR, private endpoints, CMK and Go SDK - GA + Preview](https://azure.microsoft.com/updates?id=578989) | [Disaster recovery](https://azure.microsoft.com/updates?id=578762) | [Private endpoints](https://azure.microsoft.com/updates?id=578824) | [Customer-managed keys](https://azure.microsoft.com/updates?id=578768) | [Go SDK](https://azure.microsoft.com/updates?id=578748)  
      *Named task queues and disaster recovery in preview; private endpoints and CMK GA; Go SDK preview.*

- **Integration, APIs & connectors:**
    - [Azure AI Gateway - GA](https://azure.microsoft.com/updates?id=580080)  
      *Former APIM AI Gateway tier becomes a standalone managed service for models and MCP tools.*
    - [Agent 365 + Azure API Management integration - GA](https://azure.microsoft.com/updates?id=580055)  
      *Centrally govern agents and MCP tools with APIM runtime policy enforcement.*
    - [API Management Unified Model API - GA](https://azure.microsoft.com/updates?id=580036)  
      *One standardized API surface to reach models from multiple providers.*
    - [Azure API Management Applications - Public Preview](https://techcommunity.microsoft.com/blog/integrationsonazureblog/azure-api-management-applications-feature-now-available-in-public-preview-to-all/4573993) | [Azure Update](https://azure.microsoft.com/updates?id=581277)  
      *APIM Applications preview now open to all customers with no sign-up required.*
    - [Azure Connector Namespace - GA](https://azure.microsoft.com/updates?id=580041)  
      *Managed service exposing hundreds of prebuilt connectors to apps and AI agents.*
    - [Connector Namespace hosted MCP servers - Public Preview](https://azure.microsoft.com/updates?id=579435)  
      *Give agents tool access without building and running your own MCP hosting stack.*
    - [What's new in Logic Apps Automation at Ignite 2026 - Public Preview](https://techcommunity.microsoft.com/blog/IntegrationsonAzureBlog/what%E2%80%99s-new-in-logic-apps-automation-at-ignite-2026/4573645) | [Azure Update](https://azure.microsoft.com/updates?id=580559)  
      *Ignite refresh of the Logic Apps Automation preview for building agentic business processes.*
    - [Decision APIs as actions in Azure Logic Apps - Public Preview](https://techcommunity.microsoft.com/blog/integrationsonazureblog/announcing-decision-apis-as-actions-in-azure-logic-apps/4573643) | [Azure Update](https://azure.microsoft.com/updates?id=580539)  
      *Built-in actions powered by decision models add AI-driven branching to Logic Apps Automation workflows.*
    - [Logic Apps Automation: managed AI models, VNet integration and Azure connectors - Public Preview](https://azure.microsoft.com/updates?id=580554) | [VNet integration](https://azure.microsoft.com/updates?id=580549) | [Azure automation connectors](https://azure.microsoft.com/updates?id=580544)  
      *Built-in managed models, VNet integration and connectors for GitHub, Azure DevOps and Azure management.*
    - [Azure Logic Apps enterprise integration updates - Public Preview](https://azure.microsoft.com/updates?id=580589)  
      *Expanded connectivity, legacy integration modernization and hybrid workflow capabilities.*
    - [HL7 GA and MLLP connector for Azure Logic Apps - GA + Preview](https://techcommunity.microsoft.com/blog/integrationsonazureblog/announcing-hl7-general-availability-and-mllp-connector-public-preview-in-azure-l/4574174)  
      *HL7 message handling is GA and an MLLP connector enters preview for healthcare integration.*

- **Migration & modernization:**
    - [Azure Catalyst: one agent-led modernization experience - GA](https://techcommunity.microsoft.com/blog/AppsonAzureBlog/azure-catalyst-one-connected-agent-led-modernization-experience-across-apps-data/4573988) | [Azure Catalyst agent docs](https://learn.microsoft.com/en-us/azure/migrate/azure-copilot-migration-agent?view=migrate)  
      *Unifies discovery, planning, migration and modernization across Azure and GitHub, with rulebooks, bring-your-own-model and BizTalk-to-Logic Apps.*

---

## 📊 Data & Fabric

> *Microsoft Fabric, Power BI, and the operational database portfolio*

### Key Announcements

- **Microsoft Fabric & OneLake:**
    - [Fabric November 2026 feature summary: Fabric apps and Rayfin GA - GA + Preview](https://community.fabric.microsoft.com/blog/fbc_fabricupdatesblogs/fabric-november-2026-feature-summary/5414311)  
      *Fabric apps and Rayfin reach GA with OneLake governance, plus data agent, Eventhouse, Activator and Dataflow Gen2 updates.*
    - [Bringing trusted Fabric IQ context to wherever people work - GA + Preview](https://community.fabric.microsoft.com/blog/fbc_fabricupdatesblogs/bringing-trusted-fabric-iq-context-to-wherever-people-and-agents-work/5423049)  
      *Fabric data agents in Copilot, Fabric IQ MCP server GA, plugins for ChatGPT and Claude, semantic views and ontology upgrades.*
    - [OneLake: the unified foundation for data, context and governance - GA + Preview](https://community.fabric.microsoft.com/blog/fbc_fabricupdatesblogs/onelake-the-unified-foundation-for-data-context-governance-and-ai/5423035)  
      *OneLake catalog becomes Microsoft's data governance product, IQ sharing, Atlan partnership, Table APIs and catalog federation GA.*
    - [Fabric apps observability through coding agents - Public Preview](https://techcommunity.microsoft.com/blog/AzureObservabilityBlog/introducing-observability-in-your-coding-agent-for-fabric-apps/4573853)  
      *Built-in app health metrics plus telemetry developers can query through their coding agent.*

- **Power BI:**
    - [Power BI at Ignite: Desktop for Apps and apps for Power BI Pro - Public Preview](https://community.fabric.microsoft.com/blog/fbc_pbiupdatesblog/power-bi-at-ignite-building-on-the-momentum/5422974)  
      *Turn semantic models into interactive apps from Power BI Desktop, apps for Pro users, and semantic views on Apache Ossie.*
    - [Power BI November 2026 feature summary - GA + Preview](https://community.fabric.microsoft.com/blog/fbc_pbiupdatesblog/power-bi-november-2026-feature-summary/5414287)  
      *OneDrive and SharePoint integration GA, Fabric apps in Power BI Mobile and M parameters for Direct Lake on OneLake.*

- **Database Hub & database agents:**
    - [Database Hub in Microsoft Fabric GA, plus database agents - GA + Preview](https://techcommunity.microsoft.com/blog/azuresqlblog/database-hub-in-microsoft-fabric-is-generally-available-your-entire-database-est/4574212) | [Azure Update](https://azure.microsoft.com/updates?id=579216)  
      *Single estate view across SQL, PostgreSQL and Cosmos DB, with preview agents that explain issues and recommend fixes.*
    - [Database Hub performance dashboards - GA](https://azure.microsoft.com/updates?id=579644)  
      *Real-time CPU, memory, storage and IO dashboards across database engines.*
    - [Database Agent recommendations - Public Preview](https://azure.microsoft.com/updates?id=580091)  
      *Evidence-grounded diagnoses and next steps for detected database issues.*
    - [What's new in databases at Microsoft Ignite 2026 - GA + Preview](https://techcommunity.microsoft.com/blog/AzureSQLBlog/whats-new-in-databases-at-microsoft-ignite-2026-ai-ready-data-for-apps-and-agent/4570764)  
      *Databases roundup with AI-assisted Oracle application conversion and a relational-to-Cosmos DB modernization assistant.*

- **PostgreSQL & HorizonDB:**
    - [Azure HorizonDB GA and Microsoft Fabric HorizonDB preview - GA + Preview](https://techcommunity.microsoft.com/blog/adforpostgresql/horizondb-postgresql-for-enterprises-developers-and-agents-on-azure-and-fabric/4573498) | [Azure Update](https://azure.microsoft.com/updates?id=579388)  
      *PostgreSQL-compatible HorizonDB is GA for mission-critical apps; serverless Fabric HorizonDB previews inside Fabric.*
    - [Azure HorizonDB: data, transactions and AI in one Postgres database - GA + Preview](https://techcommunity.microsoft.com/blog/adforpostgresql/azure-horizondb-data-transactions-and-ai-in-one-postgres-database/4573614)  
      *AI model management, openCypher knowledge graphs and a PostgreSQL database agent (limited preview).*
    - [Azure HorizonDB AI model management - Limited Preview](https://azure.microsoft.com/updates?id=563097)  
      *Provision managed embedding, ranking and generation models from inside the database.*
    - [Azure HorizonDB AI pipelines for knowledge graphs - Public Preview](https://azure.microsoft.com/updates?id=579602)  
      *AI extracts entities and relationships from PostgreSQL data into a queryable graph.*
    - [Azure HorizonDB security and identity (Entra auth, managed identity, CMK, Private Link) - GA + Preview](https://azure.microsoft.com/updates?id=575111) | [Managed identity](https://azure.microsoft.com/updates?id=575069) | [CMK](https://azure.microsoft.com/updates?id=579540) | [Private Link](https://azure.microsoft.com/updates?id=574153)  
      *Entra auth and user-assigned identity GA; customer-managed keys and Private Link in preview.*
    - [Azure HorizonDB operations (pgAudit, Monitor, Advisor, Policy, maintenance) - GA + Preview](https://azure.microsoft.com/updates?id=579928) | [Diagnostic settings](https://azure.microsoft.com/updates?id=579574) | [Monitor alerts](https://azure.microsoft.com/updates?id=579933) | [Advisor](https://azure.microsoft.com/updates?id=579938) | [Maintenance](https://azure.microsoft.com/updates?id=581170) | [Azure Policy](https://azure.microsoft.com/updates?id=581180)  
      *Auditing, diagnostics, alerts, Advisor recommendations, system-managed maintenance and Azure Policy support.*
    - [Azure HorizonDB backup: geo-redundant restore and 1–35 day retention - GA + Preview](https://azure.microsoft.com/updates?id=574168) | [Backup retention](https://azure.microsoft.com/updates?id=574163)  
      *Restore to another region and tune backup retention windows.*
    - [Complete Oracle-to-PostgreSQL migration in Azure DMS - Public Preview](https://techcommunity.microsoft.com/blog/ADforPostgreSQL/complete-oracle-to-postgresql-migration-move-your-schema-data-and-application-co/4573626) | [DMS update](https://azure.microsoft.com/updates?id=579607) | [Code conversion plugin](https://azure.microsoft.com/updates?id=579231)  
      *Offline Oracle 19c+ data migrations into Azure Database for PostgreSQL and HorizonDB, with AI-assisted code conversion.*
    - [Azure DMS: migrate to Azure HorizonDB (from PostgreSQL and Oracle) - Public Preview](https://azure.microsoft.com/updates?id=579612) | [DMS to HorizonDB](https://azure.microsoft.com/updates?id=579564) | [Oracle to HorizonDB](https://azure.microsoft.com/updates?id=579226)  
      *Managed online/offline moves from Azure Database for PostgreSQL and Oracle into HorizonDB.*
    - [Azure Database for PostgreSQL compute: Cobalt 200, v6 with local disk, v5 diskless - GA](https://azure.microsoft.com/updates?id=579585) | [v6 with local disk](https://azure.microsoft.com/updates?id=579590) | [v5 diskless](https://azure.microsoft.com/updates?id=579595)  
      *More compute choices for flexible server, including Microsoft Arm64 Cobalt 200.*

- **Azure SQL & SQL Server:**
    - [What's new across Microsoft SQL at Ignite 2026 - GA + Preview](https://devblogs.microsoft.com/azure-sql/whats-new-across-microsoft-sql-at-microsoft-ignite-2026/)  
      *Next-gen GP Managed Instance updates, regex dynamic data masking, AES TDE keys, database-level managed identity and SSMS improvements.*
    - [Azure SQL Database container - Public Preview](https://devblogs.microsoft.com/azure-sql/build-locally-with-azure-sql-database-container-now-in-public-preview/) | [Azure Update](https://azure.microsoft.com/updates?id=579525)  
      *Runs the Azure SQL Database engine locally in a container for development without a subscription.*
    - [Azure SQL Database container from SSMS and the MSSQL extension - Public Preview](https://azure.microsoft.com/updates?id=579665) | [MSSQL container support](https://azure.microsoft.com/updates?id=579009) | [Local-to-cloud deployment](https://azure.microsoft.com/updates?id=579014)  
      *Provision local containers from SSMS or VS Code and deploy them to the cloud with a wizard.*
    - [MSSQL extension for VS Code: November 2026 updates - Public Preview](https://devblogs.microsoft.com/azure-sql/vscode-mssql-november2026/) | [Azure Update](https://azure.microsoft.com/updates?id=579004)  
      *Local-to-cloud deployment wizard, Query Performance Dashboard and multi-results grid with live query progress.*
    - [Azure SQL Hyperscale cross-database queries - Limited Preview](https://techcommunity.microsoft.com/blog/AzureSQLBlog/azure-sql-hyperscale-cross-database-querying-now-in-limited-preview/4573935) | [Azure Update](https://azure.microsoft.com/updates?id=579221)  
      *Query across databases in the same Hyperscale elastic pool with three-part T-SQL names.*
    - [Managed Instance link for multi-database availability groups - GA](https://techcommunity.microsoft.com/blog/azuresqlblog/mi-link-support-for-multiple-databases-in-an-always-on-availability-group-is-now/4571052) | [Azure Update](https://azure.microsoft.com/updates?id=578028)  
      *Managed Instance link now replicates Always On availability groups containing multiple databases.*
    - [SQL Managed Instance Next-gen GP zone redundancy - GA](https://azure.microsoft.com/updates?id=578033)  
      *Spread Next-gen General Purpose instances across availability zones.*
    - [Azure SQL Managed Instance mid-November updates - GA](https://azure.microsoft.com/updates?id=578465) | [Azure SQL Database updates](https://azure.microsoft.com/updates?id=578471)  
      *Higher log throughput for Next-gen General Purpose and other MI improvements.*
    - [Fuzzy string matching across Microsoft SQL - GA](https://azure.microsoft.com/updates?id=578998)  
      *Built-in similarity functions across Azure SQL, SQL MI, Fabric SQL and SQL Server 2025.*
    - [AES-256 TDE protectors in Key Vault Premium / Managed HSM - GA](https://azure.microsoft.com/updates?id=579531)  
      *Symmetric AES-256 keys as TDE protectors, an alternative to RSA for quantum readiness.*

- **Cosmos DB & DocumentDB:**
    - [What's new in Azure Cosmos DB at Ignite 2026 - GA + Preview](https://devblogs.microsoft.com/cosmosdb/whats-new-azure-cosmos-db-ignite-2026/) | [Azure Backup update](https://azure.microsoft.com/updates?id=579147)  
      *Azure Backup for Cosmos DB GA and Azure RBAC integration for data-plane access.*
    - [Azure Cosmos DB tools for AI agent developers - GA + Preview](https://devblogs.microsoft.com/cosmosdb/azure-cosmos-db-ai-agent-developer-tools/) | [Shell](https://azure.microsoft.com/updates?id=578439) | [Data modeler](https://azure.microsoft.com/updates?id=578444) | [Hosted MCP](https://azure.microsoft.com/updates?id=578434)  
      *Cosmos DB Shell GA, AI-assisted data modeler in VS Code and a managed MCP server preview.*
    - [Semantic reranking and BM25 score projection in Azure Cosmos DB - GA](https://devblogs.microsoft.com/cosmosdb/improve-search-relevance-with-semantic-reranking-and-bm25-score-projection-in-azure-cosmos-db/) | [Reranker](https://azure.microsoft.com/updates?id=577520) | [BM25](https://azure.microsoft.com/updates?id=577531)  
      *AI reranking by meaning plus exposed BM25 relevance scores for search, RAG and agents.*
    - [Microsoft.Embedding-1 and automatic embedding generation in Cosmos DB - GA + Preview](https://devblogs.microsoft.com/cosmosdb/microsoft-embedding-one/) | [Azure Update](https://azure.microsoft.com/updates?id=578049)  
      *Generate embeddings where the data lives with a new multimodal embedding model from Cosmos DB and Microsoft Research.*
    - [Azure Cosmos DB SDK for Rust - GA](https://devblogs.microsoft.com/cosmosdb/announcing-the-general-availability-of-the-azure-cosmos-db-sdk-for-rust/) | [Azure Update](https://azure.microsoft.com/updates?id=578054)  
      *Native Rust client for Cosmos DB for NoSQL with retries, partition failover and binary encoding.*
    - [Azure Cosmos DB throughput buckets - GA](https://devblogs.microsoft.com/cosmosdb/generally-available-control-shared-workloads-with-throughput-buckets-in-azure-cosmos-db/) | [Azure Update](https://azure.microsoft.com/updates?id=571488)  
      *Cap RU/s per workload inside a shared container to stop noisy neighbors.*
    - [What's new in Azure DocumentDB at Ignite 2026 - GA + Preview](https://devblogs.microsoft.com/documentdb/whats-new-azure-documentdb-ignite-2026/)  
      *VS Code extension and near-instant clusters GA; full-text search, fine-grained RBAC, Azure Arc and Azure Local in preview.*
    - [DocumentDB for VS Code - GA](https://azure.microsoft.com/updates?id=578237)  
      *Free, open-source extension to connect, browse and query DocumentDB clusters.*
    - [Azure DocumentDB near-instant provisioning (M10–M30) - GA](https://azure.microsoft.com/updates?id=579349)  
      *Spin up paid tiers in moments for testing and agent-driven workflows.*
    - [Azure DocumentDB query routing from any node - GA](https://azure.microsoft.com/updates?id=579354)  
      *Every node in a multi-shard cluster can accept and route queries.*
    - [DocumentDB enabled by Azure Arc - Public Preview](https://azure.microsoft.com/updates?id=578242)  
      *Run MongoDB-compatible DocumentDB on Arc-enabled Kubernetes across hybrid and multicloud.*
    - [DocumentDB on Azure Local - Public Preview](https://azure.microsoft.com/updates?id=578255)  
      *Keep MongoDB-compatible workloads on your own Azure Local infrastructure for sovereignty.*
    - [Azure DocumentDB granular RBAC - Public Preview](https://azure.microsoft.com/updates?id=578262)  
      *Scope roles and permissions to individual databases and collections.*
    - [Azure DocumentDB full-text search - Public Preview](https://azure.microsoft.com/updates?id=578232)  
      *BM25 indexing with relevance-ranked results.*

- **Redis & MySQL:**
    - [What's new in Azure Managed Redis at Ignite 2026 - GA + Preview](https://techcommunity.microsoft.com/blog/azure-managed-redis/what%E2%80%99s-new-in-azure-managed-redis-at-microsoft-ignite-2026/4574168)  
      *Migration tooling from Azure Cache for Redis, keyspace notifications, shard metrics, IP filtering and database caching guidance.*
    - [Redis 8 on Azure Managed Redis - Public Preview](https://techcommunity.microsoft.com/blog/azure-managed-redis/build-faster-applications-with-redis-8-now-in-preview-on-azure-managed-redis/4572690) | [Azure Update](https://azure.microsoft.com/updates?id=577594)  
      *Redis 8 brings new vector capabilities for semantic search, RAG and agent memory to Azure Managed Redis.*
    - [Azure Managed Redis agent kit - Public Preview](https://techcommunity.microsoft.com/blog/azure-managed-redis/go-beyond-%E2%80%9Cit-works%E2%80%9D-and-build-better-apps-with-the-azure-managed-redis-agent-ki/4573032) | [Azure Update](https://azure.microsoft.com/updates?id=577568)  
      *Brings Redis and Azure best-practice guidance into AI-assisted coding workflows.*
    - [Azure Managed Redis keyspace notifications - GA](https://azure.microsoft.com/updates?id=577558)  
      *Apps receive events when keys change.*
    - [Azure Managed Redis shard-level metrics and firewall rules - Public Preview](https://azure.microsoft.com/updates?id=577599) | [Firewall rules](https://azure.microsoft.com/updates?id=577589)  
      *Per-shard performance visibility and firewall-based network access control.*
    - [DNS migration tooling: Azure Cache for Redis to Azure Managed Redis - GA](https://azure.microsoft.com/updates?id=577579)  
      *Keep the existing hostname while moving off Basic/Standard/Premium cache tiers.*

- **Partner data platforms:**
    - [Azure Databricks integrations with Microsoft 365 Copilot, Teams and Microsoft IQ - Announced](https://techcommunity.microsoft.com/blog/azure-databricks/azure-databricks-delivers-new-integrations-for-enterprise-intelligence-to-use-bu/4574157)  
      *Genie One plugin for Copilot, Genie Ontology alongside Microsoft IQ and a Genie app in Teams.*
    - [Microsoft and Oracle bring agentic AI into the flow of work - Announced](https://azure.microsoft.com/en-us/blog/microsoft-and-oracle-bring-agentic-ai-into-flow-of-enterprise-work/)  
      *Foundry agents reach Oracle AI Database through managed MCP servers and A2A for knowledge and memory.*

### Notable Updates

- **PostgreSQL & HorizonDB:**
    - [Azure HorizonDB Apache AGE performance improvements - GA](https://azure.microsoft.com/updates?id=579660)  
      *Faster graph queries and builds through better planning and graph joins.*

- **Azure SQL & SQL Server:**
    - [SQL Server 2025 on Ubuntu 26.04 LTS - Public Preview](https://azure.microsoft.com/updates?id=578579)  
      *Evaluate SQL Server 2025 on the latest Ubuntu LTS.*
    - [Azure SQL mid-November tooling updates (SSMS) - Public Preview](https://azure.microsoft.com/updates?id=579359)  
      *New SSMS Create and Apply wizards for .dacpac/.bacpac and other tooling refinements.*

- **Redis & MySQL:**
    - [Azure Database for MySQL server rename - GA](https://azure.microsoft.com/updates?id=581140)  
      *Rename an existing server without recreating it or migrating data.*
    - [Azure Database for MySQL on Premium SSD v2 - Public Preview](https://azure.microsoft.com/updates?id=577515)  
      *Higher performance and independent IOPS/throughput tuning for MySQL storage.*

---

## 🤖 AI, Agents & Copilot

> *Microsoft Foundry, models, Microsoft IQ, and the agent-building platform*

### Key Announcements

- **Microsoft Foundry:**
    - [Continuous improvement comes to Microsoft Foundry - GA + Preview](https://azure.microsoft.com/en-us/blog/continuous-improvement-comes-to-microsoft-foundry/)  
      *Insights for agents GA, agent optimizer, safety rubric evaluators, trace annotations, Programmed Training and hosted/voice agent updates.*
    - [From model choice to durable advantage: new models and routing in Foundry - GA + Preview](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/from-model-choice-to-your-durable-advantage-build-ai-that-keeps-improving/4573609)  
      *Model router expands to 44 models, Baseten and fal models, Meta Muse coming, and Managed Compute GA.*
    - [Microsoft-Decision-1.1 - GA](https://azure.microsoft.com/en-us/blog/continuous-improvement-comes-to-microsoft-foundry/)  
      *Microsoft-Decision-1.1 can serve as a judge model in Foundry Evaluations for quality and safety.*
    - [GPT-6.2 Astra and GPT-6.2 Sol in Microsoft Foundry - GA](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/gpt-6-2-astra-and-gpt-6-2-sol-now-generally-available-in-microsoft-foundry/4574122)  
      *OpenAI's GPT-6.2 Astra reasoning model and GPT-6.2 Sol are generally available in Foundry from launch.*
    - [Content Understanding skill in Azure AI Search - GA](https://azure.microsoft.com/updates?id=563661)  
      *Semantic chunking and AI image descriptions for Foundry IQ and AI Search ingestion.*

- **Microsoft AI (MAI) models:**
    - [MAI model family at Ignite 2026 - Announced](https://microsoft.ai/news/microsoft-ignite-2026/)  
      *Seven lower-cost MAI models spanning coding, cyber, image, voice and transcription; Dragon Copilot Transcribe now runs on MAI-Transcribe-2.*
    - [MAI Code 2 and MAI Code 2 Flash - Announced](https://microsoft.ai/news/introducing-mai-code-2-and-mai-code-2-flash/)  
      *Two cost-efficient MAI coding models for everyday enterprise development, available in GitHub Copilot.*
    - [MAI Realtime 1 - Limited Preview](https://microsoft.ai/news/introducing-mai-realtime-1/)  
      *First MAI live speech-to-speech model for low-latency voice conversations, priced from $0.01 per audio minute.*
    - [MAI Image 2.7 and MAI Image 2.7 Flash - Public Preview](https://microsoft.ai/news/introducing-mai-image-2-7/)  
      *New MAI image generation and editing models, in public preview on Foundry and partner platforms.*
    - [MAI Cyber 2 Flash - Announced](https://microsoft.ai/news/introducing-mai-cyber-2-flash/)  
      *Specialist security model with a 1M-token context, coming to Microsoft security products including Codename MDASH.*
    - [MAI Licensed Weights - Announced](https://microsoft.ai/news/introducing-mai-licensed-weights/)  
      *Organizations can deploy and customize MAI model weights inside their own Azure environments.*

- **Microsoft IQ:**
    - [Introducing the new Microsoft IQ - GA + Preview](https://azure.microsoft.com/en-us/blog/introducing-the-new-microsoft-iq-putting-your-organizations-intelligence-to-work-in-every-agent/)  
      *Enterprise context management platform with business plugins, Work IQ memory and Listen, and Fabric IQ in Excel.*
    - [What's new in Work IQ at Ignite 2026 - GA + Preview](https://techcommunity.microsoft.com/blog/microsoft_365blog/whats-new-in-work-iq-at-ignite-2026-agents-that-get-work-done/4572219)  
      *Work IQ GA in Foundry and Copilot Studio, Engage people insights and agent action ceilings.*
    - [Business Applications in Work IQ for Foundry - GA](https://azure.microsoft.com/updates?id=579680)  
      *Build business-system-connected agents in Foundry with less custom integration.*
    - [Foundry IQ: knowledge graphs engineered for agents - GA + Preview](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/foundry-iq-introducing-knowledge-graphs-engineered-for-agents/4572683)  
      *SharePoint, Azure SQL and Fabric IQ knowledge sources, permission and sensitivity-label enforcement, and Foundry IQ Serverless.*
    - [Knowledge graphs in Foundry IQ - Public Preview](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/knowledge-graphs-in-foundry-iq-improve-evidence-recall-with-fewer-tokens/4573663)  
      *Foundry IQ extracts ontology-based entities and topic hierarchies so agents can query relationships with citations.*
    - [Microsoft Retriever 1 - Public Preview](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/microsoft-retriever-1-brings-sub-second-agentic-retrieval-to-foundry-iq/4573431)  
      *Microsoft-trained agentic search model in Foundry IQ that plans queries, cutting retrieval latency and tokens.*
    - [Foundry IQ: MCP servers as knowledge sources - GA](https://azure.microsoft.com/updates?id=563411)  
      *Register MCP servers as read-only federated knowledge sources for agentic retrieval.*
    - [Web IQ broadly available to all Azure customers - GA](https://blogs.bing.com/webiq/2026/11/web-iq-is-now-broadly-available-build-better-agents-that-keep-up-with-the-world/)  
      *Web IQ web grounding for agents opens to every Azure customer with no waitlist and lower pricing.*
    - [What's new with Web IQ: Ignite 2026 edition - GA + Preview](https://techcommunity.microsoft.com/blog/azuredevcommunityblog/whats-new-with-web-iq-ignite-2026-edition/4574183)  
      *Web IQ Auto and Auto Advanced, Weather, Places and Health scenarios GA, Commerce in private preview.*

### Notable Updates

- **Microsoft Foundry:**
    - [Content Understanding adds GPT-5.6, GPT-6 and GPT-6.1 - Announced](https://devblogs.microsoft.com/foundry/content-understanding-adds-gpt-5-6-gpt-6-and-gpt-6-1-choose-the-right-model-for-your-workload/)  
      *Content Understanding analyzers can now use GPT-5.6, GPT-6 and GPT-6.1 models, with new selection guidance.*

- **Microsoft IQ:**
    - [SharePoint tools in Work IQ - Public Preview](https://techcommunity.microsoft.com/blog/spblog/introducing-sharepoint-tools-in-work-iq/4569917)  
      *60+ native SharePoint operations for any agent via the Work IQ MCP server, scoped by new WorkIQ.Read/Act permissions.*

---

## 💼 Microsoft 365 & Business Applications

> *Microsoft Copilot, Copilot Studio, Agent 365 value, Microsoft 365 apps, Power Platform and Dynamics 365*

### Key Announcements

- **Microsoft Copilot:**
    - [Copilot at Microsoft Ignite: Expanding what's possible - GA + Preview](https://www.microsoft.com/en-us/copilot/blog/2026/11/17/copilot-at-microsoft-ignite-expanding-whats-possible-with-intelligence-built-for-work/)  
      *Home and Office in Copilot GA, a unified plugin catalog, and new finance and legal skills.*
    - [Home in the Microsoft Copilot app - GA](https://www.microsoft.com/en-us/copilot/blog/2026/11/17/copilot-at-microsoft-ignite-expanding-whats-possible-with-intelligence-built-for-work/)  
      *A new starting point where Chat and Cowork come together in one experience.*
    - [Office at Ignite 2026: from apps to an agentic system of work - GA + Preview](https://techcommunity.microsoft.com/blog/microsoft-copilot-blog/office-at-ignite-2026-from-apps-to-agentic-system-of-work/4572226)  
      *Word, Excel and PowerPoint inside the Copilot app (GA), plus Workspaces, Today, Pages and OneNote conversions.*
    - [Copilot Workspaces - Frontier](https://techcommunity.microsoft.com/blog/microsoft-copilot-blog/office-at-ignite-2026-from-apps-to-agentic-system-of-work/4572226)  
      *Shared spaces where teams and their agents work from the same context.*
    - [Today in Copilot and Outlook - Private Preview](https://techcommunity.microsoft.com/blog/microsoft-copilot-blog/office-at-ignite-2026-from-apps-to-agentic-system-of-work/4572226)  
      *A prioritized daily view that updates as new information arrives.*
    - [Autopilot: your trusted personal teammate - Frontier](https://techcommunity.microsoft.com/blog/microsoft-copilot-blog/autopilot-meet-your-trusted-personal-teammate/4572611)  
      *Always-on cloud personal agent with its own identity, mailbox, memory and remote computer, working in Teams and Outlook.*
    - [Copilot Code - Frontier](https://learn.microsoft.com/en-us/copilot/code/overview)  
      *Code tab turns plain-language requests into apps, dashboards and scripts; GA planned in the coming weeks.*
    - [Copilot Managed Runtime - GA + Preview](https://techcommunity.microsoft.com/blog/copilot-managed-runtime-blog/copilot-managed-runtime-is-now-generally-available-with-additional-new-preview-f/4571846)  
      *Securely host and manage Copilot-built apps in your tenant (GA), with Fabric integration and local agent development in preview.*
    - [What's new in Copilot Cowork at Ignite 2026 - GA + Preview](https://techcommunity.microsoft.com/blog/microsoft-copilot-blog/whats-new-in-copilot-cowork-at-ignite-2026/4572242)  
      *Auto effort levels with parallel subagents, Brand Kit, app building, Planner, Viva Engage and Sales plugins, and Cowork in Edge.*

- **Agent 365 value & FinOps:**
    - [Agent 365 Business Analytics - Frontier](https://techcommunity.microsoft.com/blog/ai-finops-blog/introducing-microsoft-agent-365-business-analytics-turn-ai-investment-into-busin/4574149)  
      *Connects AI spend, usage and estimated value such as assisted hours, with forecasting and plain-language insights.*
    - [Agent 365 Cost Management - GA + Preview](https://www.microsoft.com/en-us/dynamics-365/blog/business-leader/2026/11/17/microsoft-ignite-2026-introducing-dynamics-365-in-copilot/)  
      *Central place for usage-based Copilot and agent costs, limits and alerts, with Frontier spend additions.*

- **Teams & Microsoft 365 platform:**
    - [New capabilities for building digital teammates in Microsoft Teams - GA + Preview](https://devblogs.microsoft.com/microsoft365dev/new-capabilities-for-building-digital-teammates-in-microsoft-teams)  
      *Agentic Users, threaded agent chats, plans and steps, streaming, HTML widgets and socket mode for Teams agent developers.*

- **Dynamics 365:**
    - [Introducing Dynamics 365 in Copilot - GA + Preview](https://www.microsoft.com/en-us/dynamics-365/blog/business-leader/2026/11/17/microsoft-ignite-2026-introducing-dynamics-365-in-copilot/)  
      *Updated Sales, Customer Service and ERP plugins for Copilot and Excel, Work IQ integration and Contact Center Intelligence GA.*
    - [Dynamics 365 Activate for CRM and ERP migrations - GA + Preview](https://www.microsoft.com/en-us/dynamics-365/blog/business-leader/2026/11/17/microsoft-ignite-2026-introducing-dynamics-365-in-copilot/)  
      *Salesforce-to-Dynamics 365 migration is GA; agentic ERP migration from SAP ECC enters private preview.*

- **Salesforce partnership:**
    - [Copilotforce: Salesforce in Copilot, Teams and Fabric - GA + Preview](https://news.microsoft.com/source/2026/11/17/microsoft-and-salesforce-announce-copilotforce-bringing-trusted-customer-context-and-action-into-microsoft-ai-experiences/)  
      *Salesforce plugin with prebuilt sales skills (preview), Sales Cloud in Teams and Data 360 federation with Fabric.*

---

## 🪟 Windows, Devices & Edge

> *Windows, Windows 365, agents on the PC, devices and Microsoft Edge*

### Key Announcements

- **Windows:**
    - [Microsoft Ignite 2026: Building Windows for the next era of work - GA + Preview](https://blogs.windows.com/windowsexperience/2026/11/17/microsoft-ignite-2026-building-windows-for-the-next-era-of-work/)  
      *Administrator protection GA, agent containment updates, local Copilot on Copilot+ PCs and hybrid intelligence.*
    - [Microsoft Execution Containers updates for AI agents - GA + Preview](https://blogs.windows.com/windowsexperience/2026/11/17/microsoft-ignite-2026-building-windows-for-the-next-era-of-work/)  
      *Process container improvements (preview), learning and permissive modes (GA) and Local Micro VMs in development.*
    - [Copilot on Windows: local context, file actions and PC diagnostics - Announced](https://blogs.windows.com/windowsexperience/2026/11/17/microsoft-ignite-2026-building-windows-for-the-next-era-of-work/)  
      *Local context, actions and models coming to Copilot on Copilot+ PCs, plus file actions and PC diagnostics.*
    - [Windows security at Ignite 2026 - GA + Preview](https://blogs.windows.com/windowsexperience/2026/11/17/windows-security-at-ignite-2026-start-secure-protect-what-matters-prepare-for-ai/)  
      *Windows endpoint security platform GA, Windows baseline protection preview, post-quantum TLS and passwordless improvements.*
    - [Rethinking Windows management for modern IT - GA + Preview](https://techcommunity.microsoft.com/blog/windows-itpro-blog/rethinking-windows-management-for-modern-it/4572664)  
      *Autopatch hotpatch and maintenance windows, OS reliability report in Intune, declarative management and quick machine recovery.*

- **Windows 365 & Azure Virtual Desktop:**
    - [Windows 365 at Ignite 2026: Cloud PCs for people and agents - GA + Preview](https://techcommunity.microsoft.com/blog/windows-itpro-blog/windows-365-at-ignite-2026-introducing-new-cloud-pc-capabilities-for-people-agen/4570006)  
      *Direct Stream, Windows 365 admin assistant, monitoring platform GA, context-based redirections and Cloud PC protections.*
    - [Windows 365 for Agents - GA + Preview](https://techcommunity.microsoft.com/blog/windows-itpro-blog/windows-365-at-ignite-2026-introducing-new-cloud-pc-capabilities-for-people-agen/4570006)  
      *Copilot Credits eligibility, Foundry integration, persistent agent Cloud PCs (Frontier) and on-premises app access.*

- **Microsoft Edge:**
    - [Edge for Business Ignite 2026 innovations - GA + Preview](https://blogs.windows.com/msedgedev/2026/11/17/edge-for-business-ignite-2026-innovations/)  
      *Cowork agentic browsing GA, managed agent browsing, extension risk scores, leak controls, Sentinel connector and private app access.*

---

## 🐙 GitHub & Developer Tools

> *GitHub Copilot, the Microsoft Copilot SDK, Visual Studio, VS Code and .NET*

### Key Announcements

- **GitHub Copilot:**
    - [Microsoft Copilot SDK 2.0 - GA](https://commandline.microsoft.com/microsoft-copilot-sdk-2-0-github/)  
      *Multi-tenant Rust runtime with per-session identity, host-owned tools and durable sessions; SDKs in six languages.*
    - [GitHub Copilot app: Microsoft Ignite releases - GA + Preview](https://github.blog/changelog/2026-11-17-github-copilot-app-microsoft-ignite-releases/)  
      *Azure DevOps repos from clone to merge and browser use in your signed-in browser (preview), plus GHES support GA.*
    - [Copilot code review: adaptive effort, secret detection and more - Announced](https://github.blog/changelog/2026-11-17-copilot-code-review-adaptive-effort-secret-detection-and-more/)  
      *Review depth adapts to each pull request, and reviews can flag secrets on added lines.*
    - [Secret scanning on demand for developers and agents - Public Preview](https://github.blog/changelog/2026-11-17-secret-scanning-on-demand-for-developers-and-agents/)  
      *Copilot's security-review specialist runs GitHub's 500+ secret detectors on changes in CLI, app, SDK and code review.*
    - [MAI Code 2 and MAI Code 2 Flash in GitHub Copilot - Announced](https://github.blog/changelog/2026-11-17-mai-code-2-and-mai-code-2-flash-in-github-copilot/)  
      *Next-gen Microsoft coding models for agentic engineering, selectable across VS Code, VS, CLI, app, JetBrains and more.*
    - [GitHub Copilot Fusion updates - Announced](https://github.blog/changelog/2026-11-17-github-copilot-fusion-updates-more-availability-benchmarks-and-models/)  
      *Fusion model-routing reaches github.com, Visual Studio and Mobile betas, adds MAI-Code-2 and other models.*
    - [Stream GitHub Copilot agent activity to Agent 365 - Public Preview](https://docs.github.com/en/copilot/how-tos/administer-copilot/manage-for-enterprise/manage-agents/monitor-agentic-activity)  
      *Enterprises send Copilot agent audit data from all clients into Agent 365's control plane.*
    - [GitHub Event Streams - Public Preview](https://docs.github.com/en/integrations/how-tos/using-github-event-streams)  
      *Agents and integrations subscribe to resource changes instead of polling, waking only when work arrives.*

- **Azure DevOps & .NET:**
    - [Azure DevOps Sprint 282: Cowork plugin and Agentic Autofix - GA + Preview](https://learn.microsoft.com/en-us/azure/devops/release-notes/2026/sprint-282-update)  
      *Azure DevOps plugin for Copilot Cowork and Copilot-drafted fixes for GitHub Advanced Security for Azure DevOps alerts.*

### Notable Updates

- **Azure DevOps & .NET:**
    - [.NET 11 - GA](https://devblogs.microsoft.com/dotnet/announcing-dotnet-11/)  
      *Annual .NET release shipped at .NET Conf the week before Ignite; .NET 8 and .NET 9 left support the same day.*

---

## 🔒 Security & Governance

> *Agent 365 governance, Defender, Perception, Entra, Purview, Intune and Azure platform security*

### Key Announcements

- **Microsoft Perception & Codename MDASH:**
    - [Security for the agentic era, powered by Microsoft Perception - GA + Preview](https://www.microsoft.com/en-us/security/blog/2026/11/17/security-for-the-agentic-era-powered-by-microsoft-perception/)  
      *Perception GA with blue and red team agents, MCP playbooks, MDASH expansion, MAI-Cyber models and agent discovery.*
    - [Codename MDASH agentic code scanner - Public Preview](https://www.microsoft.com/en-us/security/blog/2026/11/17/security-for-the-agentic-era-powered-by-microsoft-perception/)  
      *Expanded preview of Microsoft's multi-model agentic code security system, now with MAI-Cyber models.*
    - [GitHub and Codename MDASH: fixes, not bug reports, for maintainers - Announced](https://github.blog/open-source/maintainers/maintainers-dont-need-more-ai-bug-reports-they-need-fixes/)  
      *MDASH plus GitHub triage turned AI findings into 99 verified private reports with fixes for six OSS projects.*
    - [What's new with Microsoft Perception at Ignite 2026 - GA + Preview](https://techcommunity.microsoft.com/blog/perception-blog/whats-new-with-microsoft-perception-at-ignite-2026/4571834)  
      *Agents reason over Okta, AWS and Salesforce signals, a detect-emerging-threats playbook and usage and cost dashboards.*
    - [New exposure management capabilities in Microsoft Perception - GA + Preview](https://techcommunity.microsoft.com/blog/securityexposuremanagement/introducing-new-exposure-management-capabilities-in-microsoft-perception/4569977)  
      *Posture Prioritization Agent GA, Risk Reduction Agent preview and outcome-based AI Readiness Initiatives.*
    - [Microsoft AI Transparency Initiative - Announced](https://news.microsoft.com/source/2026/11/17/microsoft-and-organizations-across-industries-launch-ai-transparency-initiative-to-strengthen-enterprise-trust-in-ai-models-and-agents/)  
      *Cross-industry initiative to strengthen enterprise trust in AI models and agents through shared transparency.*

- **Microsoft Defender & Sentinel:**
    - [Ignite 2026: What's new in Microsoft Defender and Sentinel - GA + Preview](https://techcommunity.microsoft.com/blog/microsoftthreatprotectionblog/ignite-2026-whats-new-in-microsoft-defender--sentinel/4569975)  
      *Integrated Security Operations Center core GA, full-SIEM preview, agent posture on Bedrock, QR-code and deepfake protections.*
    - [Vulnerability shielding in Microsoft Defender - Public Preview](https://techcommunity.microsoft.com/blog/microsoftthreatprotectionblog/vulnerability-shielding-protect-the-time-before-the-patch/4572135)  
      *AI-chosen, temporary, reversible protections for unpatched systems, applied proactively via Perception or autonomously during attacks.*
    - [Defender runtime protection for local AI agents on Windows - GA](https://techcommunity.microsoft.com/blog/microsoftthreatprotectionblog/ignite-2026-whats-new-in-microsoft-defender--sentinel/4569975)  
      *Runtime controls in Audit or Block mode for local agents, configurable through Defender or Intune.*
    - [What's new in endpoint security - GA + Preview](https://techcommunity.microsoft.com/blog/microsoftthreatprotectionblog/ignite-2026-what%E2%80%99s-new-in-endpoint-security/4573835)  
      *ClickFix clipboard protection, endpoint health dashboard, safe deployment channels and shared mobile device support.*
    - [Ignite 2026: What's new in Microsoft Sentinel - GA + Preview](https://techcommunity.microsoft.com/blog/microsoftsentinelblog/ignite-2026-whats-new-in-microsoft-sentinel/4571174)  
      *Ingest-time normalization, automation audit logs, UEBA for AWS GuardDuty and a Connector Builder Agent in VS Code.*
    - [New Microsoft Sentinel connectors and Unified Data Management - GA + Preview](https://techcommunity.microsoft.com/blog/MicrosoftSentinelBlog/microsoft-ignite-2026-new-sentinel-connectors-announcement/4565258)  
      *New partner and Microsoft connectors plus one place to manage Sentinel data, tables and ingestion health.*
    - [New investments to reduce on-premises security risk - Announced](https://techcommunity.microsoft.com/blog/microsoft-security-blog/new-investments-to-reduce-on-premises-security-risk/4570381)  
      *On-premises baseline hardening guidance and Emergency Mitigation Service 2.0 for Exchange, Skype and SharePoint Server.*

- **Identity, data & endpoint:**
    - [Microsoft Entra: identity and access for the agentic era - GA + Preview](https://techcommunity.microsoft.com/blog/microsoft-entra-blog/ai-is-changing-access-see-how-microsoft-entra-helps-you-stay-ahead-/4556456)  
      *Agent ID for local agents and digital teammates, MCP Server for IT Admins GA, MCP firewall, PIM, passkeys and backup.*
    - [Dynamic Agent Risk in Microsoft Agent 365 - Public Preview](https://techcommunity.microsoft.com/blog/microsoft-entra-blog/ai-is-changing-access-see-how-microsoft-entra-helps-you-stay-ahead-/4556456)  
      *Risk-adaptive controls that adjust what an agent can do based on its live risk signals.*
    - [Secure the data that fuels AI with Microsoft Purview - GA + Preview](https://techcommunity.microsoft.com/blog/microsoft-security-blog/secure-the-data-that-fuels-ai-with-microsoft-purview/4573266)  
      *DLP for Copilot-used data and local agents, agent signals for Unified Agent Risk, classification and auto-labeling upgrades.*
    - [Microsoft Baseline security mode 2026 - GA + Preview](https://techcommunity.microsoft.com/blog/microsoft_365blog/ignite%E2%80%9926-spotlight-announcing-microsoft-baseline-security-mode-2026-general-ava/4572694)  
      *Adds 24 secure-by-default settings with Intune, Purview and Dynamics 365 coverage; Azure and Windows settings in private preview.*
    - [What's new in Microsoft Intune at Ignite - GA + Preview](https://techcommunity.microsoft.com/blog/microsoftintuneblog/what%E2%80%99s-new-in-microsoft-intune-at-ignite/4570003)  
      *Policies for Execution Containers, Vulnerability Remediation Agent, AI app protection, Windows Server management and CIS auditing.*

- **Azure platform security:**
    - [Azure Adaptive Virtual Patching - Public Preview](https://azure.microsoft.com/updates?id=580689)  
      *AI-orchestrated shield that reduces zero-day exposure while patches are tested and rolled out.*
    - [AI Security add-on for Azure Firewall Premium - Public Preview](https://azure.microsoft.com/updates?id=580694)  
      *Five capabilities to protect AI apps, sensitive data and app traffic at the firewall.*
    - [Azure Bastion RDP and SSH vision - Public Preview](https://azure.microsoft.com/updates?id=580699)  
      *AI summaries and risky-activity insights over recorded privileged sessions.*
    - [Azure DDoS Protection custom policy - GA](https://azure.microsoft.com/updates?id=580852)  
      *Override auto-tuned detection thresholds per protected resource.*
    - [Azure DDoS Protection peacetime telemetry and NAT Gateway coverage - Public Preview](https://azure.microsoft.com/updates?id=581175) | [NAT Gateway StandardV2 coverage](https://azure.microsoft.com/updates?id=580862)  
      *See traffic outside active attacks and protect NAT Gateway StandardV2 outbound IPs.*
    - [Azure Key Vault Premium symmetric (oct-HSM, AES) keys - GA](https://azure.microsoft.com/updates?id=579374)  
      *Symmetric AES encryption directly in Key Vault Premium, after a July preview.*

---

## 📅 Event Information

**Microsoft Ignite 2026**  
*November 17–20, 2026*  
*Moscone Center, San Francisco, CA & online*  
*Format: Hybrid Experience*

### Summary

Microsoft Ignite 2026 framed AI around three pillars: human ambition, intelligence and trust. Highlights included the new Copilot experience (Workspaces, Autopilot, Copilot Code and Office in Copilot), Microsoft IQ as an enterprise context platform, continuous improvement and new models in Microsoft Foundry, Agent 365 Business Analytics and governance, Microsoft Perception reaching general availability, Azure Cobalt 200 VMs and Azure HorizonDB going GA, and Windows Server 2028 entering preview.

---

## 📝 Contributing

This list is maintained by Matt Hansen. Feel free to suggest additions or corrections!

---

## 🔗 Resources

- [Official Ignite 2026 Book of News](https://news.microsoft.com/events/ignite/2026/book-of-news/)
- [Microsoft Ignite 2026 live news](https://news.microsoft.com/events/ignite/2026/live-news/)
- [Satya Nadella's Ignite 2026 keynote remarks](https://blogs.microsoft.com/blog/2026/11/17/ignite-2026-building-the-frontier-ecosystem/)
- [Microsoft Ignite 2026 news roundup (Microsoft Source)](https://news.microsoft.com/source/2026/11/17/microsoft-ignite-2026-empowering-human-ambition-intelligence-and-trust/)
- [Azure Updates](https://azure.microsoft.com/updates/)
- [Microsoft Tech Community](https://techcommunity.microsoft.com/)

---

*Last updated: November 18, 2026*
