# 🚀 Matt's List of Ignite 2026 Announcements

> *The Ignite Book of News is great, but it doesn't include all the great work across the rest of the Microsoft products.*

This is a personal collection of announcements and updates from **Microsoft Ignite 2026**, organized by product area for navigation and reference.

**Last Updated:** November 21, 2026 at 6:27AM EST

**🎯 What's Inside:** 406 announcements across Infrastructure, Apps, Data, AI, Microsoft 365, Windows, GitHub, Security, and Research with direct links to official documentation and blog posts.

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
- [🔬 Science, Research & Quantum](#-science-research--quantum)

---

## 🏗️ Infrastructure & Cloud

> *Compute and silicon, storage, networking, operations, resiliency, hybrid and sovereign cloud*

### Key Announcements

- **Overview:**
    - [Microsoft Ignite 2026: What's new in Azure](https://azure.microsoft.com/en-us/blog/microsoft-ignite-2026-whats-new-in-azure-the-platform-purpose-built-for-ai/)  
      *Azure's Ignite roundup: Cobalt 200, Azure Catalyst, HorizonDB, Fabric apps, Microsoft IQ and a new Copilot Credits billing option for Fabric.*
    - [Azure Compute at Ignite 2026: silicon, efficiency, trust and resilience - GA + Preview](https://techcommunity.microsoft.com/blog/AzureCompute/ignite-2026-the-next-era-of-enterprise-ai-starts-with-the-infrastructure-beneath/4574943)  
      *Azure Compute's Ignite wrap-up: Cobalt 200 GA, Maia 300 plans, new DT VMs, Spot Plus, IBM Symphony and LSF bursting, confidential VMs and resiliency.*

- **Compute & silicon:**
    - [Azure Cobalt 200 VMs - GA](https://azure.microsoft.com/en-us/blog/azure-cobalt-200-vms-now-available-proven-on-real-workloads-and-built-for-the-agentic-era/) | [Azure Update](https://azure.microsoft.com/updates?id=581298)  
      *Second-gen Microsoft Arm VMs with up to 50% more CPU performance, new Mpsv4/Lpsv5 families and selectable processor modes.*
    - [Azure Maia 300 - Announced](https://blogs.microsoft.com/blog/2026/10/12/microsoft-to-expand-azure-maia-system-to-multi-gigawatt-deployments/)  
      *Third-generation Azure Maia inference system with 96-accelerator racks and an expected 40% more tokens per megawatt than GPU systems; production deployments start 2027.*
    - [Ebsv6 and Ebdsv6 VMs - GA](https://techcommunity.microsoft.com/blog/azurecompute/announcing-general-availability-of-azure-ebsv6-vms-powered-by-intel%C2%AE-xeon%C2%AE-proce/4573333) | [Azure Update](https://azure.microsoft.com/updates?id=581160)  
      *Intel Xeon 5th Gen VMs with Azure Boost, optimized for high remote storage throughput.*
    - [DHasv8, DHalsv8 and EHasv8 VMs (AMD EPYC "Venice") - Preview](https://techcommunity.microsoft.com/blog/AzureCompute/announcing-preview-of-new-azure-dhehasv8-vms-based-on-6th-gen-amd-epyc%E2%84%A2-%E2%80%9Cvenice%E2%80%9D/4573295) | [Azure Update](https://azure.microsoft.com/updates?id=581308)  
      *6th Gen AMD EPYC VMs up to 480 cores and 3.8 TiB memory for agentic AI and database workloads.*
    - [Mv4 with CXL memory, Mv4 Medium Memory and Mbv4 VMs - GA + Preview](https://techcommunity.microsoft.com/blog/sapapplications/azure-mv4-at-ignite-2026-advancing-performance-scalability-and-tco-with-cxl/4573907) | [Mv4 Medium Memory GA](https://techcommunity.microsoft.com/blog/SAPApplications/announcing-general-availability-of-new-mv4-medium-memory-virtual-machines/4574571)  
      *CXL-attached memory up to 8 TB (private preview), Mv4 Medium Memory GA and storage-optimized Mbv4 for SAP, SQL Server and Epic.*
    - [Next-gen confidential VMs on 5th Gen AMD EPYC - Gated Preview](https://techcommunity.microsoft.com/blog/AzureConfidentialComputingBlog/announcing-gated-preview-of-next-gen-azure-confidential-vms-with-5th-generation-/4570276) | [Azure Update](https://azure.microsoft.com/updates?id=581199)  
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
    - [Zone resilience for Azure VMs - Public Preview](https://techcommunity.microsoft.com/blog/AzureCompute/zone-resilience-for-azure-vms/4573176) | [Azure Update](https://azure.microsoft.com/updates?id=581254)  
      *Recover an eligible VM into another availability zone in the same region.*
    - [Guest RDMA for Azure Boost - Public Preview](https://techcommunity.microsoft.com/blog/AzureCompute/announcing-public-preview-of-guest-rdma-for-azure-boost/4573027)  
      *RDMA inside guest VMs through the Azure Boost NIC on standard Intel Emerald Rapids and AMD EPYC 9005 sizes.*

- **AI infrastructure for agents:**
    - [Azure Catalyst and new AI infrastructure: Agent Grid, Agent Sandbox, Flex nodes for AKS - GA + Preview](https://azure.microsoft.com/en-us/blog/introducing-azure-catalyst-agentic-modernization-and-new-ai-infrastructure-innovations/)  
      *Azure blog post introducing Catalyst plus agent networking, isolation and hybrid AKS capacity for production AI.*
    - [Agent Grid - Public Preview](https://aka.ms/AGIgniteBlog)  
      *Identity-based Zero Trust network security for agent, model and tool traffic on Azure.*
    - [Flex nodes for AKS - Public Preview](https://azure.microsoft.com/en-us/blog/introducing-azure-catalyst-agentic-modernization-and-new-ai-infrastructure-innovations/)  
      *Extends AKS node pools to supported GPU and server environments beyond Azure, governed through Azure Arc.*
    - [Direct virtualization in Azure VMs - Private Preview](https://techcommunity.microsoft.com/blog/AzureCompute/direct-virtualization-a-new-foundation-for-agentic-ai-in-azure/4573925)  
      *Host VM-grade isolated sandboxes with direct GPU access inside Azure VMs, without nested-hypervisor overhead.*
    - [Serverless sandboxes in Azure Container Instances for AI agents - Public Preview](https://techcommunity.microsoft.com/blog/AzureCompute/azure-infrastructure-for-agentic-ai/4574616) | [Docs](https://learn.microsoft.com/en-us/azure/container-instances/container-instances-ai-sandboxes)  
      *Hyper-V micro-VM sandboxes for agent-written code with snapshot, clone, pause and restore, Entra Agent ID and Agent Grid egress control.*

- **Storage & backup:**
    - [Azure Elastic SAN Next Generation - Public Preview](https://techcommunity.microsoft.com/blog/AzureStorageBlog/azure-elastic-san-next-generation-public-preview-mission-critical-performance--c/4573949)  
      *Next-gen Elastic SAN keeps the shared-performance SAN model while raising scale and performance.*
    - [Azure Blob Storage turbo tier - Public Preview](https://aka.ms/TurboTierPreviewBlog)  
      *SSD-backed tier for performance-sensitive blob data such as AI training, inference and analytics.*
    - [Session-based authentication for Blob and Data Lake Storage - Public Preview](https://aka.ms/sessionauthblog)  
      *Cuts per-request auth overhead for AI agents and apps while keeping existing security controls.*
    - [Azure Files NFS shares on HDD - Public Preview](https://azure.microsoft.com/updates?id=579369)  
      *Lower-cost HDD option for Linux NFS file shares alongside the existing SSD tier.*
    - [Immutable snapshots for Azure Disk Storage - Public Preview](https://azure.microsoft.com/updates?id=581503)  
      *Tamper-proof short-term disk snapshots that complement immutable Azure Backup vaults.*
    - [Quick Attach Detach (QAD) for managed disks - Limited Preview](https://techcommunity.microsoft.com/blog/AzureCompute/quick-attach-detach-limited-preview-bringing-faster-more-resilient-storage-mobil/4574172)  
      *Faster, more resilient managed-disk attach and detach operations, coming to AKS and more.*
    - [Azure Files NFS: petabyte-scale SSD shares](https://techcommunity.microsoft.com/blog/azurestorageblog/petabyte-scale-and-cost-flexibility-for-linux-workloads-with-azure-files-nfs/4573843)  
      *Single SSD NFS file shares scale to 1 PiB and 1M IOPS for large Linux workloads, alongside the new HDD tier.*
    - [Azure Native Commvault Cloud - GA](https://techcommunity.microsoft.com/blog/azurestorageblog/azure-native-commvault-cloud-is-now-generally-available/4573783)  
      *Commvault Cloud data protection is now generally available as an Azure Native ISV service.*
    - [Cross-subscription backup for Azure VMs - GA](https://azure.microsoft.com/updates?id=581048)  
      *Back up VMs to a Recovery Services vault in another subscription in the same tenant to centralize backup.*

- **Networking:**
    - [Azure Multicloud Interconnect - GA](https://aka.ms/Interconnect-Ignite)  
      *Managed private connectivity between Azure and other clouds (Google Cloud in preview).*
    - [ExpressRoute Direct link groups - Public Preview](https://azure.microsoft.com/updates?id=580926)  
      *Aggregate multiple ExpressRoute Direct links to scale throughput with less operational overhead.*
    - [Application Gateway v2 elastic architecture - Public Preview](https://azure.microsoft.com/updates?id=580428)  
      *Faster provisioning and autoscaling for Application Gateway under bursty traffic.*
    - [Application Gateway advanced load balancing - Public Preview](https://techcommunity.microsoft.com/blog/AzureNetworkingBlog/redefining-application-load-balancing-in-azure-application-gateway/4572687)  
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
    - [Azure Monitor health models - GA](https://techcommunity.microsoft.com/blog/AzureObservabilityBlog/azure-monitor-health-models-is-generally-available/4560478)  
      *Model workload health from metrics, logs and dependencies as a first-class, business-aware construct.*
    - [Azure Monitor Application Insights traces experience - Public Preview](https://techcommunity.microsoft.com/blog/azureobservabilityblog/see-the-patterns-then-the-trace-distributed-tracing-at-scale-with-azure-monitor/4573318)  
      *Compare thousands of distributed traces and drill from trends to root cause.*
    - [Azure Workload Center for SAP and Oracle - Preview](https://aka.ms/workloadcenterforsap-blog) | [Oracle](https://techcommunity.microsoft.com/blog/OracleonAzureBlog/announcing-azure-workload-center-for-oracle-and-azure-copilot-run-oracle-agent/4573276)  
      *Workload-aware health monitoring and configuration validation for SAP and Oracle, paired with Azure Copilot Run agents.*
    - [Azure Infrastructure Resiliency Manager - GA](https://techcommunity.microsoft.com/blog/reliability-and-resiliency-in-azure/azure-infrastructure-resiliency-manager-is-now-generally-available-with-ai-power/4573791)  
      *Goal-driven resiliency hub: zone-resilient templates, at-scale assessments, drills and recovery guidance.*
    - [Azure Chaos Studio workspaces and AKS extension - GA + Preview](https://techcommunity.microsoft.com/blog/reliability-and-resiliency-in-azure/introducing-the-next-chapter-of-azure-chaos-studio/4574151)  
      *Reusable disruption scenarios such as zone loss or database failover, plus lower-privilege fault injection into AKS pods.*
    - [What's new in Azure SRE Agent at Ignite 2026 - GA + Preview](https://techcommunity.microsoft.com/blog/appsonazureblog/what%E2%80%99s-new-in-azure-sre-agent-at-microsoft-ignite-2026/4573607)  
      *Teams and Slack, Entra Agent ID and Agent 365, AWS/Google Cloud connectors, A2A, Grafana, Azure CLI and connector triggers.*
    - [Azure SRE Agent in Microsoft Teams - Public Preview](https://azure.microsoft.com/updates?id=580753)  
      *Start and follow investigations with the SRE agent in Teams chats, channels and meetings.*
    - [Azure SRE Agent: AWS and Google Cloud connectors - Public Preview](https://techcommunity.microsoft.com/blog/AppsonAzureBlog/azure-sre-agent-now-natively-supports-aws-and-google-cloud/4569556)  
      *Investigate incidents across Azure, AWS and Google Cloud evidence from one agent.*
    - [Azure SRE Agent: Agent-to-Agent (A2A) protocol - Public Preview](https://azure.microsoft.com/updates?id=580758)  
      *SRE agents hand off and accept tasks from other agents while keeping each team's permissions.*
    - [Azure SRE Agent with Entra Agent ID and Agent 365 - Public Preview](https://azure.microsoft.com/updates?id=580763)  
      *Govern SRE agents alongside other enterprise agents with their own Agent IDs.*
    - [Azure SRE Agent in Slack - Private Preview (coming)](https://azure.microsoft.com/updates?id=580768)  
      *Work incident investigations with the SRE agent directly in Slack channels.*
    - [On-demand Azure SRE Agent debugging in Azure Container Apps - Public Preview](https://techcommunity.microsoft.com/blog/AppsonAzureBlog/azure-sre-agent-brings-on-demand-ai-powered-operations-to-your-aca-workloads/4573380)  
      *'Debug with SRE Agent' starts serverless, read-only troubleshooting sessions for any container app, nothing to deploy.*
    - [Azure SRE Agent in Azure Managed Grafana - Public Preview](https://techcommunity.microsoft.com/blog/AppsonAzureBlog/introducing-azure-sre-agent-in-azure-managed-grafana-the-dashboard-as-command-ce/4575039)  
      *Investigate incidents with the SRE agent in a pane beside your Grafana dashboards, using the same data sources and asking before it acts.*
    - [What's new in Azure Monitor at Ignite 2026 - GA + Preview](https://techcommunity.microsoft.com/blog/AzureObservabilityBlog/whats-new-in-azure-monitor-at-ignite-2026/4573974)  
      *Azure Monitor roundup: agent observability, OpenTelemetry onboarding GA, PII redaction, schemaless ingestion and a VM-hosted pipeline.*
    - [Agent observability in Azure Monitor - GA + Preview](https://techcommunity.microsoft.com/blog/azureobservabilityblog/agent-observability-in-azure-monitor-at-ignite-2026/4573966)  
      *Observe and evaluate agents built outside Foundry, including on AWS and Google Cloud, plus cross-agent debugging in preview.*
    - [Unified agent observability with end-to-end tracing - GA + Preview](https://techcommunity.microsoft.com/blog/azureobservabilityblog/unified-agent-observability-with-end-to-end-tracing-in-azure-monitor/4574276)  
      *Trace one request across agent platforms in Application Insights using OpenTelemetry GenAI conventions.*
    - [OpenTelemetry in Azure Monitor - GA](https://techcommunity.microsoft.com/blog/azureobservabilityblog/troubleshoot-with-opentelemetry-in-azure-monitor-%E2%80%93-now-generally-available/4573810)  
      *OpenTelemetry troubleshooting is GA, with automatic AKS onboarding and OTLP forwarding through the Azure Monitor Agent.*
    - [Monitoring Coverage for platform telemetry - Public Preview](https://techcommunity.microsoft.com/blog/AzureObservabilityBlog/find-and-fix-platform-telemetry-gaps-across-your-azure-estate-with-monitoring-co/4573903)  
      *Find resources missing platform logs or metrics and turn collection on in batches across the estate.*
    - [Azure Monitor pipeline on VMs - Public Preview](https://techcommunity.microsoft.com/blog/AzureObservabilityBlog/azure-monitor-pipeline-on-vms-zero-kubernetes-clusters-required/4573805)  
      *Run the Azure Monitor pipeline as an extension on Azure and Arc-enabled Linux VMs, no Kubernetes cluster required.*
    - [PII redaction in Azure Monitor logs - Public Preview](https://techcommunity.microsoft.com/blog/AzureObservabilityBlog/you-cant-code-review-a-prompt-redact-pii-in-azure-monitor-logs/4572693)  
      *Detect and mask emails, phone numbers, card numbers and other PII in logs during ingestion.*
    - [Schemaless log ingestion in Azure Monitor - Public Preview](https://techcommunity.microsoft.com/blog/AzureObservabilityBlog/schema-at-pr-speed-schemaless-log-ingestion-in-azure-monitor/4573008)  
      *Undeclared custom-log fields land in a dynamic overflow column, so schema changes no longer need DCR edits.*
    - [Regional resiliency in Resiliency Manager and Azure Backup region of choice - Preview](https://techcommunity.microsoft.com/blog/reliability-and-resiliency-in-azure/beyond-availability-zones---building-resilience-across-regions-with-azure/4573795)  
      *Gated preview of regional resiliency for 15 services with drills and orchestration, plus a preview to pick your Azure Backup region.*

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
    - [Production Touch Ledger assessment report - Announced](https://techcommunity.microsoft.com/blog/AzureInfrastructureBlog/production-touch-ledger-ptl-verifiable-records-for-operator-transparency-in-the-/4573858)  
      *Independent Capgemini validation of the tamper-evident ledger of production-access records.*
    - [Project NOVA - In Development](https://azure.microsoft.com/updates?id=581193)  
      *Zero-knowledge-style verification of specific claims without revealing underlying data.*
    - [Sovereign Private Cloud at Ignite 2026 - GA + Preview](https://techcommunity.microsoft.com/blog/azurearcblog/whats-new-with-sovereign-private-cloud-at-microsoft-ignite-2026/4573886)  
      *Foundry Local, GitHub Enterprise Local and AMD confidential VMs GA on Azure Local; DocumentDB and Blob Storage in preview.*
    - [Govern, secure and operate anywhere with Azure Arc - GA + Preview](https://techcommunity.microsoft.com/blog/AzureArcBlog/govern-secure-and-operate-anywhere-with-azure-arc/4573259)  
      *Arc roundup: Kubernetes onboarding, Machine Inventory, automatic agent upgrade GA, Upgrade Insights and STIG auditing.*
    - [Expanding multicloud management with Azure Arc - Preview](https://techcommunity.microsoft.com/blog/AzureArcBlog/expanding-multicloud-management-with-azure-arc/4571205)  
      *Onboard GKE and EKS clusters to Arc, with multicloud security baselines and power-cycle management.*
    - [Confidential computing on Azure Local - GA](https://techcommunity.microsoft.com/blog/AzureArcBlog/protect-your-ai-models-and-data-at-edge-confidential-computing-on-azure-local/4572241)  
      *AMD SEV-SNP confidential VMs on Azure Local 2610 with attestation-gated key release for edge AI models.*

- **Windows Server:**
    - [Windows Server 2028 - Public Preview](https://techcommunity.microsoft.com/blog/windowsservernewsandbestpractices/windows-server-2028-a-trusted-foundation-for-an-evolving-enterprise/4574112) | [What's new](https://learn.microsoft.com/en-us/windows-server/get-started/whats-new-windows-server-2028)  
      *Next LTSC release: hardened defaults, PQC, NVMe-oF, Arc/Intune management and hybrid AI inference.*
    - [Hardened Server Core for Windows Server Insiders - Announced](https://techcommunity.microsoft.com/blog/windowsservernewsandbestpractices/announcing-hardened-server-core-for-windows-server-insiders/4574239)  
      *Secure-by-default Server Core option that ships hardened instead of compatible-by-default, for Insiders.*
    - [Windows Admin Center Virtualization Mode - GA + Preview](https://techcommunity.microsoft.com/blog/Windows-Admin-Center-Blog/virtualization-mode-in-windows-admin-center-is-now-generally-available/4573651) | [Networking improvements](https://techcommunity.microsoft.com/blog/Windows-Admin-Center-Blog/networking-improvements-in-windows-admin-center-virtualization-mode-ga/4573448)  
      *vMode GA centrally manages up to 1,000 Hyper-V hosts and 25,000 VMs, with bulk Arc onboarding, backup and certificate management.*

- **Governance & management:**
    - [Machine Configuration at Ignite 2026 - GA + Preview](https://techcommunity.microsoft.com/blog/AzureGovernanceandManagementBlog/machine-configuration--ignite-2026/4573872)  
      *New portal hub, machine inventory, baseline remediation and new CIS Windows and STIG Linux baselines.*
    - [Machine Inventory - Public Preview](https://techcommunity.microsoft.com/blog/AzureGovernanceandManagementBlog/public-preview-see-whats-running-across-your-servers-with-machine-inventory/4573924)  
      *Query apps, certificates, services and local users inside Azure VMs and Arc servers through Resource Graph.*
    - [Security baseline remediation in Machine Configuration - Public Preview](https://techcommunity.microsoft.com/blog/AzureGovernanceandManagementBlog/public-preview-introducing-security-baseline-remediation-in-machine-configuratio/4573899)  
      *Fix drift from Azure security baselines, CIS Linux and STIG settings instead of only auditing it.*
    - [DISA STIG benchmarks and per-rule auto-remediation for Linux - Public Preview](https://techcommunity.microsoft.com/blog/LinuxandOpenSourceBlog/now-in-public-preview-disa-stig-benchmarks-and-per-rule-auto-remediation-for-lin/4570619)  
      *Audit Linux against DISA STIG benchmarks and auto-remediate individual rules on Azure and Arc machines.*
    - [What's new in the Azure Resource Manager MCP server](https://techcommunity.microsoft.com/blog/AzureGovernanceandManagementBlog/what%E2%80%99s-new-in-the-azure-resource-manager-mcp-server-at-ignite-2026/4571824)  
      *ARM MCP server adds create and update, resource actions, deployment and cost tools, plus experimental skills.*

- **Cost management & FinOps:**
    - [AI for FinOps - Announced](https://techcommunity.microsoft.com/blog/finopsblog/ai-for-finops-bringing-the-cost-answer-to-where-decisions-are-made/4571510)  
      *FinOps tools in the ARM MCP server, an Azure Cost plugin for GitHub Copilot and a cost optimization agent.*
    - [What's new in Cost Analysis and Azure Copilot - Available](https://techcommunity.microsoft.com/blog/FinOpsBlog/your-azure-costs-in-context-what%E2%80%99s-new-in-cost-analysis-and-azure-copilot/4568824)  
      *Contextual AI entry points in Cost Analysis and deeper cost-management expertise in Azure Copilot.*

- **Confidential computing:**
    - [What's new in Azure Confidential Computing at Ignite 2026 - GA + Preview](https://techcommunity.microsoft.com/blog/AzureConfidentialComputingBlog/what%E2%80%99s-new-in-azure-confidential-computing-%E2%80%94-ignite-2026/4573909)  
      *Azure Local confidential VMs GA, confidential VM backup preview, Clean Rooms limited preview and enclaves in development.*
    - [Confidential enclaves and pod-level confidential containers - In Development](https://techcommunity.microsoft.com/blog/azureconfidentialcomputingblog/shrinking-the-trusted-computing-base-for-sensitive-cloud-workloads/4573926)  
      *Roadmap for child-capable VMs, confidential enclaves and pod-level confidential containers on AKS.*
    - [Intel TDX confidential VM advances - Preview](https://techcommunity.microsoft.com/blog/azureconfidentialcomputingblog/advancing-confidential-computing-with-intel-tdx-more-performance-more-resiliency/4572307)  
      *NVMe remote storage, MANA networking and local sealing for TDX confidential VMs, plus a TDISP demo.*

- **IoT & physical AI:**
    - [Azure IoT at Ignite 2026: Device Registry, Fabric Eventstream and MCP tools - GA + Preview](https://techcommunity.microsoft.com/blog/IoTBlog/from-connected-devices-to-ai-ready-operations/4572614) | [Physical AI roundup](https://techcommunity.microsoft.com/blog/IoTBlog/put-your-industrial-data-to-work-with-new-azure-capabilities/4572221)  
      *Device Registry with X.509 certificates and a Fabric Eventstream endpoint reach GA for IoT Hub; MQTT v5 and MCP tools enter preview.*
    - [Azure IoT Operations 2610 - GA + Preview](https://techcommunity.microsoft.com/blog/IoTBlog/azure-iot-operations-2610-is-now-available-scaling-the-foundation-for-physical-a/4572675)  
      *Essentials SKU, SQL Server connector and lakehouse writes GA; an MCP server and Foundry Local inference connector in preview.*

- **SAP & Oracle on Azure:**
    - [Microsoft and SAP at Ignite 2026 - GA + Preview](https://techcommunity.microsoft.com/blog/SAPApplications/microsoft-and-sap-at-ignite-2026-connecting-sap-customers-to-ai-agents-data-and-/4573931)  
      *SAP roundup: Mv4 Medium Memory GA, Mbv4 preview, Workload Center for SAP and SAP HANA scale-out backup preview.*

### Notable Updates

- **Compute & silicon:**
    - [Azure Linux 4.0 for VMs and VM Scale Sets - GA](https://aka.ms/azurelinux-blog)  
      *Microsoft's first-party Linux distribution built for Azure, now generally available for IaaS.*
    - [IBM Spectrum LSF with Azure Compute Fleet - GA](https://azure.microsoft.com/updates?id=581259)  
      *LSF resource connector bursts HPC jobs into Azure Compute Fleet capacity on demand.*
    - [Azure Boost observability for NVMe disks - Announced](https://techcommunity.microsoft.com/blog/AzureCompute/introducing-azure-boost-observability-for-nvme%E2%84%A2-disks/4572188)  
      *Open-source in-VM tool exposing remote disk I/O and latency metrics mapped to each managed disk.*
    - [Soft delete in Azure Compute Gallery - GA](https://techcommunity.microsoft.com/blog/AzureCompute/soft-delete-in-azure-compute-gallery-is-now-generally-available/4568500)  
      *Recover deleted gallery images with configurable 7-365 day retention and up to 90-day grace periods.*
    - [HDv2-series VMs (AMD EPYC "Venice")](https://techcommunity.microsoft.com/blog/AzureInfrastructureBlog/visit-azure-and-amd-at-microsoft-ignite-and-sc26/4570345)  
      *500+ core, 3.8 TB memory VMs for AI data preparation and HPC, previewed for Ignite and SC26.*

- **Storage & backup:**
    - [Snapshot-based backup for SQL Server on Azure VMs - GA](https://azure.microsoft.com/updates?id=564668)  
      *Azure Backup combines disk snapshots with SQL log backups for fast, low-impact full backups.*
    - [Azure Managed Lustre in-place capacity expansion - GA + Preview](https://techcommunity.microsoft.com/blog/AzureHighPerformanceComputingBlog/scale-azure-managed-lustre-as-your-ai-and-hpc-workloads-grow/4573518) | [Docs](https://learn.microsoft.com/en-us/azure/azure-managed-lustre/expand-file-system-portal)  
      *Grow a Managed Lustre file system while it stays online and mounted; optional rebalancing across the new storage is in public preview.*

- **Operations, observability & resiliency:**
    - [Protected Gen AI content in Application Insights and Foundry](https://techcommunity.microsoft.com/blog/AzureObservabilityBlog/announcing-protected-gen-ai-content-in-azure-monitor-application-insights-and-mi/4572729)  
      *Prompts and responses go to a separate table that can be locked down with its own access controls.*
    - [Azure Observability skills plugin for coding agents - Available](https://techcommunity.microsoft.com/blog/appsonazureblog/announcing-azure-observability-skills-plugin-at-ignite-2026/4573940)  
      *Lets GitHub Copilot detect, investigate and fix issues using Azure Monitor data and MCP servers.*

- **Governance & management:**
    - [Essential Machine Management dashboard](https://techcommunity.microsoft.com/blog/azuregovernanceandmanagementblog/simplify-server-management-at-scale-with-the-new-essential-machine-management-da/4573934)  
      *One dashboard for extension failures, policy compliance and management coverage across Azure VMs and Arc servers.*

- **IoT & physical AI:**
    - [Firmware analysis: fleet insights, latest CVEs and unsafe function calls - Preview](https://techcommunity.microsoft.com/blog/IoTBlog/advancing-device-firmware-security-with-fleet-insights-and-continuous-vulnerabil/4572076)  
      *Firmware security summaries in Azure Device Registry, refreshed CVE views, unsafe-function detection and 70 more SBOM detectors.*

- **Windows Server:**
    - [VM Conversion from VMware ESXi to Hyper-V in Windows Admin Center - Private Preview](https://techcommunity.microsoft.com/blog/Windows-Admin-Center-Blog/vm-conversion-is-now-in-windows-admin-center-virtualization-mode/4573880)  
      *Appliance-based tool in vMode moves ESXi VMs to Hyper-V with prechecks, delta sync and batches of up to ten.*
    - [Trusted Launch VMs in Windows Admin Center Virtualization Mode - Private Preview](https://techcommunity.microsoft.com/blog/Windows-Admin-Center-Blog/tvm-in-windows-admin-center-vmode-is-in-private-preview/4574161)  
      *Create Trusted Launch Hyper-V VMs from vMode and check their boot integrity with Microsoft Azure Attestation.*
    - [Network HUD for Windows Server 2025 - GA](https://techcommunity.microsoft.com/blog/NetworkingBlog/announcing-general-availability-for-network-hud-on-windows-server-2025/4534181)  
      *Arc-delivered Network HUD detects VLAN, driver, PCIe and adapter problems on Windows Server 2025 Datacenter clusters.*
    - [AMD Instinct MI350P GPU support on Windows Server - In Development](https://techcommunity.microsoft.com/blog/WindowsServerNewsandBestPractices/expanding-ai-silicon-capabilities-on-windows-server-with-amd/4574513)  
      *Upcoming MI350P PCIe GPU support so Windows Server can run local AI inference for RAG, coding assistants and agents beside existing apps.*

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
    - [Azure Red Hat OpenShift with hosted control planes - GA](https://techcommunity.microsoft.com/blog/AppsonAzureBlog/azure-red-hat-openshift-with-hosted-control-planes-is-now-generally-available/4574192)  
      *Separates the OpenShift control plane from worker nodes for faster, lower-cost clusters.*
    - [New experiences in Kubernetes Center](https://techcommunity.microsoft.com/blog/AzureInfrastructureBlog/introducing-new-experiences-in-kubernetes-center-at-microsoft-ignite-2026/4569688)  
      *Kubernetes portal hub adds multicluster updates, Fleet resource placement, monitoring insights and AI Manager.*
    - [Fleet Manager Upgrade Insights and Flux GitOps - Public Preview](https://techcommunity.microsoft.com/blog/AzureArcBlog/simplify-kubernetes-operations-with-upgrade-insights-and-gitops-with-azure-kuber/4569134)  
      *Plan Kubernetes upgrades with Upgrade Insights and keep multi-cluster configuration consistent with Flux GitOps.*
    - [AKS platform-initiated upgrades - Announced](https://blog.aks.azure.com/2026/11/17/platform-initiated-upgrades)  
      *From June 1, 2027, AKS will upgrade clusters left on unsupported Kubernetes versions, rolling out in waves.*
    - [Azure Container Apps at Ignite 2026: Sandboxes and Express GA - GA + Preview](https://techcommunity.microsoft.com/blog/AppsonAzureBlog/whats-new-in-azure-container-apps-at-ignite26/4573042)  
      *Container Apps Sandboxes and Express reach GA, Container Apps becomes an Azure Migrate target, and six more regions arrive.*

- **App Service & Azure Functions:**
    - [App Service Ignite 2026 updates - GA + Preview](https://techcommunity.microsoft.com/blog/AppsonAzureBlog/app-service-ignite-2026-updates/4572673)  
      *.NET 11 and Python 3.15 GA, Markdown for Agents, post-quantum TLS, Grafana dashboards, plan start/stop and a refreshed portal.*
    - [Azure App Service Builder - Public Preview](https://techcommunity.microsoft.com/blog/AppsonAzureBlog/introducing-azure-app-service-builder-public-preview/4572180)  
      *Source-connected way to build, deploy and host apps without hand-built pipelines.*
    - [Geo-redundancy in Azure App Service - Public Preview](https://techcommunity.microsoft.com/blog/AppsonAzureBlog/introducing-geo-redundancy-in-azure-app-service-simplify-multi-region-applicatio/4573896)  
      *Run web apps across Azure regions for higher resilience.*
    - [What's new in Azure Functions and Durable Task Scheduler - GA + Preview](https://techcommunity.microsoft.com/blog/AppsonAzureBlog/whats-new-in-azure-functions-and-durable-task-scheduler-at-microsoft-ignite-2026/4573933)  
      *Managed connectors, agent bindings, Functions Canvas and Skills, Durable Task for LangGraph and Pydantic AI, CLI v5 and new runtimes.*
    - [Managed connectors in Azure Functions - GA](https://techcommunity.microsoft.com/blog/AppsonAzureBlog/managed-connectors-in-azure-functions-are-now-generally-available/4574143)  
      *Trigger on and act across Microsoft 365, SaaS and business systems using the Functions model.*
    - [Azure Functions hosted skill and agent bindings - Public Preview](https://azure.microsoft.com/updates?id=578845)  
      *Add agents and skills to Functions apps through bindings instead of custom plumbing.*
    - [Durable Task extension for Microsoft Agent Framework - GA](https://azure.microsoft.com/updates?id=578829)  
      *Durable, resumable agents and multi-agent workflows in C# and Python.*
    - [Go on Azure Functions Flex Consumption - GA](https://azure.microsoft.com/updates?id=578812)  
      *First-class, code-first Go worker for Flex Consumption apps.*
    - [OS-level dependencies via containers on Flex Consumption - Public Preview](https://techcommunity.microsoft.com/blog/AppsonAzureBlog/public-preview-os-level-dependency-support-via-containers-for-azure-functions-fl/4572085)  
      *Bring native OS dependencies to Flex Consumption apps through containers.*
    - [Azure Functions Network Troubleshooter v2 - Public Preview](https://techcommunity.microsoft.com/blog/AppsonAzureBlog/azure-functions-network-troubleshooter-and-connectivity-checks/4573917)  
      *Top-down view of a function app's network dependencies across Storage, Service Bus and more.*
    - [Azure Functions: Node.js 26 and Python 3.15 - Public Preview](https://azure.microsoft.com/updates?id=578807) | [Python 3.15](https://azure.microsoft.com/updates?id=578802)  
      *Early runtime support to validate JavaScript/TypeScript and Python apps.*
    - [Durable Task Scheduler: task queues, DR, private endpoints, CMK and Go SDK - GA + Preview](https://techcommunity.microsoft.com/blog/AppsonAzureBlog/whats-new-in-azure-functions-durable-task-scheduler-durable-agents-disaster-reco/4573351) | [Disaster recovery](https://azure.microsoft.com/updates?id=578762) | [Private endpoints](https://azure.microsoft.com/updates?id=578824) | [Customer-managed keys](https://azure.microsoft.com/updates?id=578768) | [Go SDK](https://azure.microsoft.com/updates?id=578748)  
      *Named task queues and disaster recovery in preview; private endpoints and CMK GA; Go SDK preview.*
    - [Azure Functions Canvas - Preview](https://techcommunity.microsoft.com/blog/appsonazureblog/azure-functions-canvas-preview-build-run-and-modernize-function-apps-with-github/4573929)  
      *Scaffold, run, deploy and modernize Function Apps from a canvas in the GitHub Copilot app and VS Code.*
    - [Azure Durable Task for LangGraph and Pydantic AI agents - Public Preview](https://techcommunity.microsoft.com/blog/AppsonAzureBlog/introducing-azure-durable-task-for-langgraph-agents/4574019) | [Pydantic AI](https://techcommunity.microsoft.com/blog/AppsonAzureBlog/introducing-azure-durable-task-for-pydantic-ai-agents/4571024)  
      *Durable execution, per-tool retries and human-approval pauses for LangGraph, Deep Agents and Pydantic AI agents.*

- **Integration, APIs & connectors:**
    - [Azure AI Gateway - GA](https://techcommunity.microsoft.com/blog/IntegrationsonAzureBlog/azure-ai-gateway-is-now-generally-available-ship-faster-stay-in-control/4572644)  
      *Former APIM AI Gateway tier becomes a standalone managed service for models and MCP tools.*
    - [Agent 365 + Azure API Management integration - GA](https://azure.microsoft.com/updates?id=580055)  
      *Centrally govern agents and MCP tools with APIM runtime policy enforcement.*
    - [API Management Unified Model API - GA](https://techcommunity.microsoft.com/blog/IntegrationsonAzureBlog/generally-available-unified-model-api-in-azure-api-management-v2-tiers/4573991)  
      *One standardized API surface to reach models from multiple providers.*
    - [Azure API Management Applications - Public Preview](https://techcommunity.microsoft.com/blog/integrationsonazureblog/azure-api-management-applications-feature-now-available-in-public-preview-to-all/4573993) | [Azure Update](https://azure.microsoft.com/updates?id=581277)  
      *APIM Applications preview now open to all customers with no sign-up required.*
    - [Azure Connector Namespace - GA](https://techcommunity.microsoft.com/blog/IntegrationsonAzureBlog/connector-namespace-is-generally-available/4573019)  
      *Managed service exposing hundreds of prebuilt connectors to apps and AI agents.*
    - [Connector Namespace hosted MCP: bring-your-own images and a Cosmos DB MCP server - Public Preview](https://techcommunity.microsoft.com/blog/integrationsonazureblog/bring-your-own-image-and-azure-cosmos-db-mcp-server-in-connector-namespace-hoste/4574177)  
      *Run custom container images as hosted MCP servers, plus a ready-made Azure Cosmos DB MCP server.*
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
    - [What's new in Azure API Management at Ignite 2026 - GA + Preview](https://techcommunity.microsoft.com/blog/integrationsonazureblog/whats-new-in-azure-api-management-at-microsoft-ignite-2026/4574194)  
      *APIM roundup: Azure AI Gateway GA as a standalone service, Model Router preview, Agent 365 integration and Unified Model API.*
    - [What's new in Azure Logic Apps at Ignite 2026 - GA + Preview](https://techcommunity.microsoft.com/blog/IntegrationsonAzureBlog/whats-new-in-azure-logic-apps-at-microsoft-ignite-2026/4574191)  
      *Logic Apps roundup: HL7 GA, MLLP and MSMQ connectors, a unified dashboard, plus hybrid and Data Mapper updates.*

- **Migration & modernization:**
    - [Azure Catalyst: one agent-led modernization experience - GA](https://techcommunity.microsoft.com/blog/AppsonAzureBlog/azure-catalyst-one-connected-agent-led-modernization-experience-across-apps-data/4573988) | [Azure Catalyst agent docs](https://learn.microsoft.com/en-us/azure/migrate/azure-copilot-migration-agent?view=migrate)  
      *Unifies discovery, planning, migration and modernization across Azure and GitHub, with rulebooks, bring-your-own-model and BizTalk-to-Logic Apps.*
    - [Modernize applications and databases together with the Modernize CLI - Public Preview](https://techcommunity.microsoft.com/blog/microsoftdatamigration/modernize-applications-and-databases-together-with-the-modernize-cli/4574244) | [Azure Update](https://azure.microsoft.com/updates?id=579943)  
      *One agentic CLI that assesses an app and its databases together, then uses GitHub Copilot to remediate both.*

### Notable Updates

- **Azure Kubernetes Service & containers:**
    - [What's new in AKS networking - GA + Preview](https://techcommunity.microsoft.com/blog/AzureNetworkingBlog/what%E2%80%99s-new-in-aks-networking-connectivity-performance-and-observability/4571806) | [Managed DRANET deep dive](https://blog.aks.azure.com/2026/11/18/managed-support-for-dranet)  
      *Managed DRANET and cross-cluster networking in Fleet GA, plus multi-NIC pods in preview.*
    - [Gateway API management in the AKS portal](https://techcommunity.microsoft.com/blog/AppsonAzureBlog/enable-and-manage-gateway-api-on-azure-portal/4574567)  
      *Turn on App Routing Gateway API or Application Gateway for Containers from a new AKS ingress profile.*
    - [Azure Container Registry keys in Managed HSM](https://techcommunity.microsoft.com/blog/AppsonAzureBlog/azure-container-registry-now-supports-keys-in-managed-hsm/4572984)  
      *Keep Azure Container Registry customer-managed encryption keys in single-tenant Key Vault Managed HSM.*

- **App Service & Azure Functions:**
    - [Managed Instance on Azure App Service: Catalyst, Premium v3 and Isolated v4](https://techcommunity.microsoft.com/blog/AppsonAzureBlog/modernize-more-windows-applications-with-managed-instance-on-azure-app-service/4573885)  
      *Managed Instance adds Azure Catalyst assessment support, Premium v3 and memory-optimized plans, and Isolated v4 in App Service Environment v3.*

- **Integration, APIs & connectors:**
    - [On-behalf-of authentication for MCP tools in Connector Namespace](https://techcommunity.microsoft.com/blog/IntegrationsonAzureBlog/run-mcp-tools-as-the-signed-in-user-on-behalf-of-authentication-in-connector-nam/4573040)  
      *Connector Namespace MCP tools can act as the signed-in user through Entra on-behalf-of token exchange.*
    - [Workflow runtime settings tab for Logic Apps Standard - GA](https://techcommunity.microsoft.com/blog/IntegrationsonAzureBlog/tune-your-logic-apps-standard-runtime-from-the-portal/4573619)  
      *Tune Logic Apps Standard runtime settings through portal forms with defaults instead of editing host.json.*
    - [Polling triggers in Connector Namespace](https://techcommunity.microsoft.com/blog/IntegrationsonAzureBlog/polling-triggers-in-connector-namespace-let-your-code-pull-connector-events/4573529)  
      *Azure Functions can pull connector events from Connector Namespace instead of exposing a webhook, using managed identity and backlog-based scaling.*
    - [SQL as a storage provider for Hybrid Logic Apps - GA](https://techcommunity.microsoft.com/blog/IntegrationsonAzureBlog/announcing-general-availability-of-sql-as-a-storage-provider-for-hybrid-logic-ap/4574517)  
      *Hybrid Logic Apps keep workflow run state in your own SQL Server, so runtime data stays inside customer-managed datacenter or edge infrastructure.*
    - [Semi-connected Integration Account support for Hybrid Logic Apps](https://techcommunity.microsoft.com/blog/IntegrationsonAzureBlog/announcing-semi-connected-integration-account-support-for-hybrid-logic-apps/4573784)  
      *Hybrid Logic Apps cache Integration Account schemas, maps, partners and agreements in local SQL, so EDI and XML workflows keep running during Azure outages.*
    - [MSMQ built-in connector for Azure Logic Apps Standard - Public Preview](https://techcommunity.microsoft.com/blog/IntegrationsonAzureBlog/announcing-the-msmq-built-in-connector-for-azure-logic-apps-standard/4574215)  
      *Send messages to and trigger workflows from MSMQ queues through a customer-hosted broker, easing BizTalk Server modernization.*

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
    - [Microsoft Fabric is fueling Frontier Transformation - GA + Preview](https://community.fabric.microsoft.com/blog/fbc_fabricupdatesblogs/microsoft-fabric-is-fueling-frontier-transformation/5422989)  
      *Main Fabric Ignite post: Fabric IQ, Fabric apps GA, Fabric HorizonDB, Database Hub and agent observability.*
    - [Build governed data apps with Fabric apps - GA](https://community.fabric.microsoft.com/blog/fbc_fabricupdatesblogs/build-governed-data-apps-with-microsoft-fabric-apps-generally-available/5423011)  
      *Dedicated GA post: PostgreSQL and OneLake storage for apps, an admin Apps view, Secure Embed and item identity.*
    - [Build and operate intelligent apps with Microsoft Fabric - GA + Preview](https://community.fabric.microsoft.com/blog/fbc_fabricupdatesblogs/build-and-operate-intelligent-apps-with-microsoft-fabric-new-capabilities-at-ign/5423020)  
      *Fabric databases roundup: Fabric apps GA, Fabric HorizonDB preview with translytical queries, Database Hub GA.*
    - [Real-Time Intelligence in Fabric at Ignite 2026 - GA + Preview](https://community.fabric.microsoft.com/blog/fbc_fabricupdatesblogs/run-proactive-operations-with-real-time-intelligence-in-microsoft-fabric/5414256)  
      *IoT Hub routing to Eventstream, Eventhouse CMK and outbound protection, Operations Agent observability GA.*
    - [Fabric Data Warehouse at Ignite 2026 - GA + Preview](https://community.fabric.microsoft.com/blog/fbc_fabricupdatesblogs/fabric-data-warehouse-at-ignite-built-for-ai-era-analytics/5414274)  
      *Warehouse roundup: SQL analytics endpoint metadata sync and custom SQL pools GA, on-demand billing preview, a Data Warehouse MCP server and new T-SQL features.*

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
    - [Database Agent for Azure Database for PostgreSQL - Public Preview](https://azure.microsoft.com/updates?id=579579)  
      *Watches PostgreSQL server health, correlates metrics, logs and query plans to find likely root causes, and suggests fixes for you to review.*
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
    - [Azure Database for PostgreSQL at Ignite 2026 - GA + Preview](https://techcommunity.microsoft.com/blog/adforpostgresql/more-power-more-resilience-better-value-azure-database-for-postgresql-at-ignite-/4573613)  
      *Burstable v2, diskless and confidential v6 compute, Ultra Disk GA, immutable backups preview and PostgreSQL 19 day-zero preview.*
    - [Microsoft Fabric HorizonDB: serverless PostgreSQL in Fabric - Preview](https://techcommunity.microsoft.com/blog/ADforPostgreSQL/introducing-microsoft-fabric-horizondb-serverless-postgresql-for-applications-an/4572455)  
      *Auto-pausing serverless Postgres with AI and vector extensions, OneLake mirroring, Fabric foreign tables and reverse ETL.*

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
    - [SQL Managed Instance Next-gen GP zone redundancy - GA](https://techcommunity.microsoft.com/blog/AzureSQLBlog/zone-redundant-next-gen-general-purpose-for-azure-sql-managed-instance/4547525)  
      *Spread Next-gen General Purpose instances across availability zones.*
    - [Azure SQL Managed Instance mid-November updates - GA](https://techcommunity.microsoft.com/blog/azuresqlblog/azure-sql-managed-instance-gets-a-boost-new-capabilities-in-next-gen-general-pur/4573761)  
      *Higher log throughput for Next-gen General Purpose and other MI improvements.*
    - [Flexible Memory in Azure SQL Managed Instance](https://techcommunity.microsoft.com/blog/azuresqlblog/unlocking-more-power-with-flexible-memory-in-azure-sql-managed-instance/4425054)  
      *Customize the memory-to-vCore ratio in your SQL Managed Instance*
    - [Fuzzy string matching across Microsoft SQL - GA](https://devblogs.microsoft.com/azure-sql/fuzzy-string-matching-is-now-generally-available-across-microsoft-sql/)  
      *Built-in similarity functions across Azure SQL, SQL MI, Fabric SQL and SQL Server 2025.*
    - [AES-256 TDE protectors in Key Vault Premium / Managed HSM - GA](https://azure.microsoft.com/updates?id=579531)  
      *Symmetric AES-256 keys as TDE protectors, an alternative to RSA for quantum readiness.*
    - [SQL Server Management Studio 22.12.1 - Preview](https://techcommunity.microsoft.com/blog/sqlserver/announcing-sql-server-management-studio-22-12-1/4574204)  
      *SSMS release with Copilot SDK-based chat, bring-your-own-model, local Azure SQL containers and session restore previews.*
    - [SQL Server on Azure Local confidential VMs - Preview](https://techcommunity.microsoft.com/blog/sqlserver/strengthen-sql-server-security-on-azure-local-with-confidential-vms-in-preview/4573821)  
      *Run SQL Server 2025 on Ubuntu inside hardware-encrypted confidential VMs on Azure Local to protect data in use.*
    - [Immutable backups for Azure SQL Database and Managed Instance](https://techcommunity.microsoft.com/blog/AzureSQLBlog/strengthening-ransomware-resilience-with-immutable-backups-in-azure-sql-db-and-a/4574176)  
      *Seven-day immutable point-in-time backups by default at no charge, lockable to 35 days, plus LTR immutability and legal holds.*

- **Cosmos DB & DocumentDB:**
    - [What's new in Azure Cosmos DB at Ignite 2026 - GA + Preview](https://devblogs.microsoft.com/cosmosdb/whats-new-azure-cosmos-db-ignite-2026/)  
      *Azure Backup for Cosmos DB GA and Azure RBAC integration for data-plane access.*
    - [Azure Backup for Azure Cosmos DB - GA](https://techcommunity.microsoft.com/blog/reliability-and-resiliency-in-azure/strengthen-data-protection-with-azure-backup-for-azure-cosmos-db/4573659) | [Azure Update](https://azure.microsoft.com/updates?id=579147)  
      *Vaulted, immutable Cosmos DB backups in an air-gapped vault with up to 10-year retention, 1-day RPO and cross-region restore.*
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
    - [DocumentDB for VS Code - GA](https://devblogs.microsoft.com/documentdb/vscode-extension-ga/) | [Docs](https://microsoft.github.io/vscode-documentdb/)  
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
    - [Azure DocumentDB full-text search - Public Preview](https://devblogs.microsoft.com/documentdb/fts-azure-documentdb/)  
      *BM25 relevance ranking with fuzzy, phrase and proximity matching, custom analyzers, structured filters and hybrid vector search.*

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
    - [Azure Databricks on Azure Government - Beta](https://techcommunity.microsoft.com/blog/azure-databricks/introducing-the-new-azure-databricks-on-microsoft-azure-government-now-in-beta/4573667) | [Azure Update](https://azure.microsoft.com/updates?id=581645)  
      *New first-party Azure Databricks environment in Azure Government with Unity Catalog, Databricks SQL and serverless compute, for non-production use.*

### Notable Updates

- **PostgreSQL & HorizonDB:**
    - [Azure HorizonDB Apache AGE performance improvements - GA](https://azure.microsoft.com/updates?id=579660)  
      *Faster graph queries and builds through better planning and graph joins.*
    - [PostgreSQL 19 on Azure Database for PostgreSQL - Public Preview](https://techcommunity.microsoft.com/blog/ADforPostgreSQL/postgresql-19-on-day-one-new-capabilities-a-managed-path-forward/4572732) | [Azure Update](https://azure.microsoft.com/updates?id=574587)  
      *Try PostgreSQL 19 on flexible server on release day, with in-place major version upgrades, pre-upgrade checks and key extensions; East Asia first.*

- **Azure SQL & SQL Server:**
    - [SQL Server 2025 on Ubuntu 26.04 LTS - Public Preview](https://techcommunity.microsoft.com/blog/sqlserver/announcing-sql-server-2025-preview-support-on-ubuntu-26-04-lts/4547833)  
      *Evaluate SQL Server 2025 on the latest Ubuntu LTS.*
    - [Azure SQL mid-November tooling updates (SSMS) - Public Preview](https://devblogs.microsoft.com/azure-sql/new-create-and-apply-wizards-in-ssms-preview) | [Azure Update](https://azure.microsoft.com/updates?id=579359)  
      *New SSMS Create and Apply wizards for .dacpac/.bacpac and other tooling refinements.*
    - [SqlPackage deployment history and fast comparison - Preview](https://devblogs.microsoft.com/azure-sql/sqlpackage-deployment-history-and-fast-comparison-preview/)  
      *SqlPackage 170.6 preview records each deployment in the target database and can skip a full schema comparison when a repeat publish matches the last one.*
    - [Suspend and resume TDE encryption scans in Azure SQL Database - Public Preview](https://techcommunity.microsoft.com/blog/azuresqlblog/take-control-of-transparent-data-encryption-scans-suspend-and-resume-now-in-prev/4571096)  
      *Pause a transparent data encryption scan during busy hours and resume it later from the portal or T-SQL.*

- **Redis & MySQL:**
    - [Azure Database for MySQL server rename - GA](https://techcommunity.microsoft.com/blog/ADforMySQL/introducing-server-rename-for-azure-database-for-mysql/4573066)  
      *Rename an existing server without recreating it or migrating data.*
    - [Azure Database for MySQL on Premium SSD v2 - Public Preview](https://techcommunity.microsoft.com/blog/ADforMySQL/announcing-premium-ssd-v2-for-azure-database-for-mysql---public-preview-at-ignit/4567119)  
      *Higher performance and independent IOPS/throughput tuning for MySQL storage.*

---

## 🤖 AI, Agents & Copilot

> *Microsoft Foundry, models, Microsoft IQ, and the agent-building platform*

### Key Announcements

- **Microsoft Foundry:**
    - [Continuous improvement comes to Microsoft Foundry - GA + Preview](https://azure.microsoft.com/en-us/blog/continuous-improvement-comes-to-microsoft-foundry/) | [Multi-turn evaluation](https://azure.microsoft.com/updates?id=581746)  
      *Insights for agents GA, agent optimizer, safety rubric evaluators, trace annotations, Programmed Training and hosted/voice agent updates.*
    - [From model choice to durable advantage: new models and routing in Foundry - GA + Preview](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/from-model-choice-to-your-durable-advantage-build-ai-that-keeps-improving/4573609) | [Managed Compute GA](https://devblogs.microsoft.com/foundry/managed-compute-ga/)  
      *Model router expands to 44 models, Baseten and fal models, Meta Muse coming, and Managed Compute GA.*
    - [Microsoft-Decision-1.1 - GA](https://commandline.microsoft.com/microsoft-decision-model-ga/) | [Deep dive](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/introducing-microsoft-decision-1-1-build-faster-more-efficient-ai-applications-w/4573877)  
      *Low-cost decision model for routing, classification and tool choice: over twice as fast as Decision-1, adds image inputs, also on OpenRouter and Vercel.*
    - [GPT-6.2 Astra and GPT-6.2 Sol in Microsoft Foundry - GA](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/gpt-6-2-astra-and-gpt-6-2-sol-now-generally-available-in-microsoft-foundry/4574122)  
      *OpenAI's GPT-6.2 Astra reasoning model and GPT-6.2 Sol are generally available in Foundry from launch.*
    - [Content Understanding skill in Azure AI Search - GA](https://azure.microsoft.com/updates?id=563661)  
      *Semantic chunking and AI image descriptions for Foundry IQ and AI Search ingestion.*
    - [What's new in Foundry Agent Service at Ignite 2026 - GA + Preview](https://devblogs.microsoft.com/foundry/whats-new-in-foundry-agent-service-at-ignite-2026/)  
      *Agent Service roundup: voice agents, A2A tool, computer use and browser automation GA, plus Copilot harness and IQ previews.*
    - [Microsoft Copilot harness support in Foundry Toolkit for VS Code - Public Preview](https://azure.microsoft.com/updates?id=581468)  
      *Agent Builder in the Foundry Toolkit for VS Code creates, deploys and runs prompt agents on the Copilot harness, with tools and skills.*
    - [Hosted agents in Foundry Agent Service: Ignite updates - GA + Preview](https://devblogs.microsoft.com/foundry/hosted-agents-foundry-agent-service-ignite-2026/)  
      *Shared subnet IPs, egress controls and resilient execution GA; private CA trust, egress policy and memory snapshots in preview.*
    - [External agents in Microsoft Foundry - GA](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/external-agents-in-microsoft-foundry-are-now-generally-available/4572630) | [Observe and improve them](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/observe-and-improve-agents-built-outside-foundry/4574508)  
      *Register agents running outside Foundry through OpenTelemetry traces to get insights and continuous evaluation.*
    - [Foundry Dev Pack - GA](https://devblogs.microsoft.com/foundry/the-foundry-dev-pack-is-here-build-foundry-agents-your-way/)  
      *One install sets up the Foundry CLI, Foundry skill, VS Code toolkit and GitHub Copilot app plugin.*
    - [Tools and toolboxes in Foundry - GA + Preview](https://devblogs.microsoft.com/foundry/build-once-reuse-across-your-agent-fleet-tools-and-toolboxes-in-foundry/)  
      *A2A tool and computer use GA, Snowflake, MongoDB and Databricks catalog partners, toolboxes in GitHub Copilot.*
    - [Browser Automation tool in Foundry: Ignite updates - GA + Preview](https://devblogs.microsoft.com/foundry/browser-automation-tool-ignite/)  
      *Action batching, Live View and session recording GA; browser proxy, secrets and Web Bot Auth in preview.*
    - [Model router: auto mode, per-request steering and AI Gateway - GA + Preview](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/model-router-in-foundry-models-start-in-one-line-route-intelligently-evaluate-co/4573543)  
      *Deployment-free auto routing, per-request routing controls, session affinity and a 45-model pool.*
    - [FinOps in Microsoft Foundry - Public Preview](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/finops-in-microsoft-foundry-see-your-token-spend-hit-your-quality-bar-for-less-a/4570010)  
      *See token spend by project, agent and model, find cost drivers and set dollar or token budgets.*
    - [Human-in-the-loop evaluation in Microsoft Foundry - Public Preview](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/turn-human-feedback-into-a-reusable-quality-bar-for-ai-agents/4574554)  
      *Turn trace annotations into golden datasets and task-level rubrics that re-test future agent versions.*
    - [Quality, safety and task-level rubric evaluators - Preview](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/evaluate-ai-agents-in-microsoft-foundry-with-quality-safety-and-task-level-rubri/4572665)  
      *Generate LLM-judge rubrics from specs and policies; safety rubrics score violations and over-refusal separately.*
    - [Foundry IQ managed in every Foundry project - Limited Preview](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/foundry-iq-now-managed-for-you-in-every-foundry-project/4573316)  
      *Projects get a Foundry-managed knowledge resource, so agents can be grounded without a separate search service.*
    - [GPT-image-2.6 Flare and Sunburst in Microsoft Foundry - Rolling Out](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/introducing-gpt-image-2-6-flare-and-sunburst-in-microsoft-foundry/4573002)  
      *OpenAI's newest image models arrive in Foundry: Flare for speed, Sunburst for quality, with GIF and SVG output.*
    - [Foundry Manage experience: fleet governance and Compliance view](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/govern-your-ai-fleet-with-confidence-on-microsoft-foundry/4573980) | [Compliance view](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/your-agents-are-running-but-are-they-safe-and-compliant/4573617)  
      *Cross-project Manage views for fleet, cost, operations, quota and gateways, plus a Compliance view with Policy, Defender and Purview signals.*
    - [Governance policy guidance in Foundry Canvas and VS Code - GA](https://azure.microsoft.com/updates?id=581463)  
      *Developers see the Foundry policies that apply to agent types, models, toolboxes and guardrails, with warnings and fixes, while they build.*
    - [Skill Optimization: learn agent skills from production traces - Public Preview](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/learning-agent-skills-from-production-traces/4573041)  
      *Turns production traces and feedback into reviewable, versioned agent skills; Microsoft reports a 9.2-point average quality gain.*
    - [Programmed Training in Microsoft Foundry - Public Preview](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/programmed-training-you-write-the-loop-foundry-runs-the-gpus/4573299) | [Azure Update](https://azure.microsoft.com/updates?id=581713)  
      *Write your own post-training loop in Python while Foundry runs the GPUs; LoRA on four open models, RL environments in private preview.*
    - [Microsoft-Decision-1 as a judge in Foundry Evaluations - Public Preview](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/microsoft-decision-1-as-a-judge-in-foundry-evaluations/4572676)  
      *Use Decision-1 as a fast, low-cost judge for 19 built-in evaluators, with tunable pass/fail probability thresholds.*
    - [Audio evaluators for voice agents](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/audio-evaluation-for-voice-agents/4573373)  
      *Four evaluators score call recordings directly for task completion, groundedness, customer satisfaction and coherence.*

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
    - [How Work IQ helps Copilot understand you and your work - GA + Frontier](https://techcommunity.microsoft.com/blog/microsoft-copilot-blog/the-end-of-starting-over-how-work-iq-helps-copilot-understand-you-and-your-work/4571169)  
      *Work IQ memory adds cross-app learning, citations, email writing style and MCP access; org context expands.*
    - [People and org context in Work IQ - GA + Frontier](https://techcommunity.microsoft.com/blog/microsoft-copilot-blog/copilot-that-understands-your-organization-introducing-people-and-org-context-in/4573356)  
      *Copilot answers org questions from authoritative people data (GA); Workforce Intelligence plugin in Frontier.*
    - [Foundry IQ SharePoint (indexed) knowledge source - GA + Preview](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/foundry-iq-sharepoint-indexed-knowledge-source-is-now-generally-available/4573317)  
      *SharePoint indexed knowledge source GA with permission trimming, plus Azure SQL and File sources and private ingestion GA.*

- **Speech & voice:**
    - [Voice agents GA in Foundry Agent Service, plus Speech updates - GA + Preview](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/voice-agents-in-microsoft-foundry-agent-service-now-generally-available/4573013)  
      *Voice agents with telephony GA; Realtime Flash 1 and VASA-2 photo avatars preview; multilingual STT and Live Interpreter updates.*

- **Agent governance & controls:**
    - [Agent controls: an enterprise control plane for agent behavior - Public Preview](https://commandline.microsoft.com/introducing-agent-controls-an-enterprise-control-plane-for-agent-behavior/)  
      *Centrally allow, deny or transform agent actions at runtime across frameworks, built on an open Agent Control Specification.*

- **Healthcare & life sciences:**
    - [Microsoft Dragon Copilot brings AI to more nurses - GA + Preview](https://techcommunity.microsoft.com/blog/HealthcareAndLifeSciencesBlog/microsoft-dragon-copilot-brings-ai-to-more-nurses/4574232)  
      *Ambient nursing documentation expands to more care settings, adds an MAI Realtime 1 simulation mode and Fabric data export.*
    - [Work IQ in Dragon Copilot - GA](https://techcommunity.microsoft.com/blog/HealthcareAndLifeSciencesBlog/work-iq-now-generally-available-in-dragon-copilot/4573674)  
      *Clinicians bring Microsoft 365 email, Teams and file content into Dragon Copilot Chat, with sources and existing permissions.*

### Notable Updates

- **Microsoft Foundry:**
    - [Content Understanding adds GPT-5.6, GPT-6 and GPT-6.1 - Announced](https://devblogs.microsoft.com/foundry/content-understanding-adds-gpt-5-6-gpt-6-and-gpt-6-1-choose-the-right-model-for-your-workload/)  
      *Content Understanding analyzers can now use GPT-5.6, GPT-6 and GPT-6.1 models, with new selection guidance.*
    - [Hermes Enterprise on Microsoft Foundry - Coming Soon](https://devblogs.microsoft.com/foundry/build-trusted-autonomous-agents-for-your-team-with-microsoft-foundry/)  
      *Nous Research's open-source Hermes agent as a Foundry hosted-agent blueprint, each instance with its own Microsoft 365 account and identity.*

- **Microsoft IQ:**
    - [SharePoint tools in Work IQ - Public Preview](https://techcommunity.microsoft.com/blog/spblog/introducing-sharepoint-tools-in-work-iq/4569917)  
      *60+ native SharePoint operations for any agent via the Work IQ MCP server, scoped by new WorkIQ.Read/Act permissions.*
    - [Starter Pack for Work IQ - Available](https://devblogs.microsoft.com/microsoft365dev/introducing-the-starter-pack-for-work-iq/) | [GitHub repo](https://github.com/microsoft/Work-IQ-Starter-Pack)  
      *Open-source scripts fill a demo or developer tenant with fictitious users, mail, Teams, SharePoint and Dynamics 365 data, plus four Work IQ labs.*

---

## 💼 Microsoft 365 & Business Applications

> *Microsoft Copilot, Copilot Studio, Agent 365 value, Microsoft 365 apps, Power Platform and Dynamics 365*

### Key Announcements

- **Microsoft Copilot:**
    - [Copilot at Microsoft Ignite: Expanding what's possible - GA + Preview](https://www.microsoft.com/en-us/copilot/blog/2026/11/17/copilot-at-microsoft-ignite-expanding-whats-possible-with-intelligence-built-for-work/)  
      *Home and Office in Copilot GA, a unified plugin catalog, and new finance and legal skills.*
    - [Home in the Microsoft Copilot app - GA + Frontier](https://techcommunity.microsoft.com/blog/microsoft-copilot-blog/home-your-starting-place-for-work-in-the-microsoft-copilot-app/4573945)  
      *Home brings Chat and Cowork together with Projects and Automations now GA; Today and Workspaces stay in Frontier.*
    - [Office at Ignite 2026: from apps to an agentic system of work - GA + Preview](https://techcommunity.microsoft.com/blog/microsoft-copilot-blog/office-at-ignite-2026-from-apps-to-agentic-system-of-work/4572226)  
      *Word, Excel and PowerPoint inside the Copilot app (GA), plus Workspaces, Today, Pages and OneNote conversions.*
    - [Copilot Workspaces - Frontier](https://techcommunity.microsoft.com/blog/microsoft-copilot-blog/office-at-ignite-2026-from-apps-to-agentic-system-of-work/4572226)  
      *Shared spaces where teams and their agents work from the same context.*
    - [Today in Copilot and Outlook - Private Preview](https://techcommunity.microsoft.com/blog/microsoft-copilot-blog/office-at-ignite-2026-from-apps-to-agentic-system-of-work/4572226)  
      *A prioritized daily view that updates as new information arrives.*
    - [Autopilot: your trusted personal teammate - Frontier](https://techcommunity.microsoft.com/blog/microsoft-copilot-blog/autopilot-meet-your-trusted-personal-teammate/4572611) | [Mechanics walkthrough](https://techcommunity.microsoft.com/blog/MicrosoftMechanicsBlog/introducing-autopilot-your-personal-and-proactive-agent/4575030)  
      *Always-on cloud personal agent with its own identity, mailbox, memory and remote computer, working in Teams and Outlook.*
    - [Copilot Code - Frontier](https://learn.microsoft.com/en-us/copilot/code/overview) | [Mechanics walkthrough](https://techcommunity.microsoft.com/blog/MicrosoftMechanicsBlog/build-apps-by-describing-what-you-want-with-copilot%C2%A0code/4575026)  
      *Code tab turns plain-language requests into apps, dashboards and scripts; GA planned in the coming weeks.*
    - [Copilot Managed Runtime - GA + Preview](https://techcommunity.microsoft.com/blog/copilot-managed-runtime-blog/copilot-managed-runtime-is-now-generally-available-with-additional-new-preview-f/4571846)  
      *Securely host and manage Copilot-built apps in your tenant (GA), with Fabric integration and local agent development in preview.*
    - [What's new in Copilot Cowork at Ignite 2026 - GA + Preview](https://techcommunity.microsoft.com/blog/microsoft-copilot-blog/whats-new-in-copilot-cowork-at-ignite-2026/4572242)  
      *Auto effort levels with parallel subagents, Brand Kit, app building, Planner, Viva Engage and Sales plugins, and Cowork in Edge.*
    - [Plugins at Ignite 2026: a public Plugin Catalog - Announced](https://techcommunity.microsoft.com/blog/microsoft-copilot-blog/plugins-at-microsoft-ignite-2026/4569951)  
      *Plugins show up in Copilot Home navigation and a public Plugin Catalog launches on microsoft.com.*
    - [Learning Agent: build AI skills through everyday work - Announced](https://techcommunity.microsoft.com/blog/microsoft-copilot-blog/learning-agent-build-ai-and-copilot-skills-through-everyday-work/4573000)  
      *Adds an AI upskilling tab, AI Skills Navigator playlists, guided starter prompts and prompt coaching.*
    - [Frontier Tuning opens to more customers - Private Preview](https://devblogs.microsoft.com/microsoft365dev/frontier-tuning-opens-to-more-customers-with-new-tools-for-your-teams/)  
      *Frontier Tuning private preview expands with a GitHub Copilot plugin, CLI and APIs, and Cowork plugin publishing.*
    - [Copilot Cowork in GCC - GA](https://techcommunity.microsoft.com/blog/PublicSectorBlog/copilot-cowork-is-now-generally-available-in-gcc-delegate-multi-step-work-inside/4574184)  
      *Cowork reaches GCC tenants on Azure Government-hosted models with Purview controls; GCC High support is planned next.*
    - [Compliant web search for Copilot in GCC and GCC High - In Development](https://techcommunity.microsoft.com/blog/PublicSectorBlog/mission-forward-take-another-look-at-copilot-for-government/4574881)  
      *Copilot in GCC and GCC High will ground answers in a regionally hosted web index inside the compliance boundary; GA targeted for Q2 2027.*
    - [OpenAI's GPT-6.2 Sol and GPT-6.2 Astra in Microsoft Copilot - Rolling Out](https://techcommunity.microsoft.com/blog/microsoft-copilot-blog/available-today-openais-gpt-6-2-sol-and-gpt-6-2-astra-in-microsoft-copilot/4574229)  
      *GPT-6.2 Sol rolls out to Copilot Chat, Cowork, Copilot Studio and Word, Excel and PowerPoint; Astra to Cowork and Copilot Studio, plus Frontier users.*

- **Agent 365 value & FinOps:**
    - [Agent 365 Business Analytics - Frontier](https://techcommunity.microsoft.com/blog/ai-finops-blog/introducing-microsoft-agent-365-business-analytics-turn-ai-investment-into-busin/4574149)  
      *Connects AI spend, usage and estimated value such as assisted hours, with forecasting and plain-language insights.*
    - [Agent 365 Cost Management - GA + Preview](https://www.microsoft.com/en-us/dynamics-365/blog/business-leader/2026/11/17/microsoft-ignite-2026-introducing-dynamics-365-in-copilot/)  
      *Central place for usage-based Copilot and agent costs, limits and alerts, with Frontier spend additions.*

- **Teams & Microsoft 365 platform:**
    - [New capabilities for building digital teammates in Microsoft Teams - GA + Preview](https://devblogs.microsoft.com/microsoft365dev/new-capabilities-for-building-digital-teammates-in-microsoft-teams)  
      *Agentic Users, threaded agent chats, plans and steps, streaming, HTML widgets and socket mode for Teams agent developers.*
    - [Multi-tenant management in the Microsoft 365 admin center - GA + Preview](https://techcommunity.microsoft.com/blog/microsoft_365blog/multi-tenant-management-tenants-agents-and-ai-spend-in-one-place/4573372)  
      *Tenant switching GA; cross-tenant agent management, desired-state configuration and AI cost management in preview.*

- **Dynamics 365:**
    - [Introducing Dynamics 365 in Copilot - GA + Preview](https://www.microsoft.com/en-us/dynamics-365/blog/business-leader/2026/11/17/microsoft-ignite-2026-introducing-dynamics-365-in-copilot/)  
      *Updated Sales, Customer Service and ERP plugins for Copilot and Excel, Work IQ integration and Contact Center Intelligence GA.*
    - [Dynamics 365 Activate for CRM and ERP migrations - GA + Preview](https://www.microsoft.com/en-us/dynamics-365/blog/it-professional/2026/11/19/dynamics-365-activate-erp-crm-migration/) | [Ignite roundup](https://www.microsoft.com/en-us/dynamics-365/blog/business-leader/2026/11/17/microsoft-ignite-2026-introducing-dynamics-365-in-copilot/)  
      *Salesforce-to-Dynamics 365 migration is GA; agentic ERP migration from SAP ECC enters private preview.*
    - [Business Applications in Work IQ - GA + Preview](https://www.microsoft.com/en-us/dynamics-365/blog/it-professional/2026/11/18/business-applications-work-iq-generally-available/) | [ERP in Work IQ](https://www.microsoft.com/en-us/dynamics-365/blog/it-professional/2026/11/19/unlock-new-possibilities-for-dynamics-365-erp-with-work-iq-and-business-skills/)  
      *Dynamics 365 and Power Platform context GA in Copilot Chat, Agent Builder and Copilot Studio; ERP and Cowork in preview.*
    - [Microsoft Contact Center Intelligence - GA](https://www.microsoft.com/en-us/dynamics-365/blog/it-professional/2026/11/18/microsoft-contact-center-intelligence-now-generally-available-transform-customer-interactions/)  
      *Contact Center Intelligence GA with Avaya, Cisco and Five9 connectors, voice biometrics and a QA agent.*

- **Salesforce partnership:**
    - [Copilotforce: Salesforce in Copilot, Teams and Fabric - GA + Preview](https://news.microsoft.com/source/2026/11/17/microsoft-and-salesforce-announce-copilotforce-bringing-trusted-customer-context-and-action-into-microsoft-ai-experiences/)  
      *Salesforce plugin with prebuilt sales skills (preview), Sales Cloud in Teams and Data 360 federation with Fabric.*

- **Copilot Studio & Power Platform:**
    - [Build and manage business processes with Copilot Studio - GA + Preview](https://www.microsoft.com/en-us/copilot/blog/copilot-studio/build-and-manage-business-processes-with-microsoft-copilot-studio/)  
      *Customer conversation harness, apps and agent sharing GA; Cowork and Code authoring plus CLI and MCP in preview.*
    - [Turn AI ambition into business value with Power Platform - GA](https://www.microsoft.com/en-us/power-platform/blog/2026/11/18/turn-ai-ambition-into-real-business-value-with-power-platform/)  
      *Copilot in canvas apps GA this month, hybrid human-agent authoring through MCP and apps exposed to agents.*

- **SharePoint, OneDrive & Viva:**
    - [SharePoint and OneDrive at Ignite 2026 - GA + Preview](https://techcommunity.microsoft.com/blog/spblog/sharepoint-and-onedrive-at-microsoft-ignite-2026-putting-ai-powered-content-to-w/4535416)  
      *Work IQ context enhancements preview, Copilot in OneDrive GA, Hero Links, a Libraries view and governance updates.*
    - [Copilot and agent readiness with SharePoint content governance - GA + Preview](https://techcommunity.microsoft.com/blog/spblog/microsoft-365-copilot-and-ai-agent-readiness-and-resiliency-with-sharepoint-cont/4573034)  
      *SharePoint Admin Agent GA with new skills, a Governance Hub, an agent access heatmap and agentic-user sharing controls.*
    - [What's new for Viva Engage at Ignite 2026 - GA + Preview](https://techcommunity.microsoft.com/blog/Viva_Engage_Blog/from-conversations-to-intelligence-whats-new-for-viva-engage-at-microsoft-ignite/4572999)  
      *Engage skills for Cowork, upgraded Community Agent, communication plans preview and Communities in Teams GA.*
    - [The enhanced Microsoft Copilot in Viva Engage - Rolling Out](https://techcommunity.microsoft.com/blog/viva_engage_blog/introducing-the-enhanced-microsoft-copilot-in-viva-engage/4574225)  
      *Copilot in Engage analyzes conversations, builds reports and decks, and brings in Work IQ, agents and Cowork.*

- **Partners & Marketplace:**
    - [Partner program and Marketplace news at Ignite 2026 - Announced](https://partner.microsoft.com/en-us/blog/article/microsoft-ignite-2026) | [Partner benefits](https://partner.microsoft.com/en-us/blog/article/ignite-2026-benefits-blog)  
      *New benefits package, an E7 AI Activation offer, an Agentic Partner Capability Score and Marketplace bundling and co-sell tools.*
    - [Microsoft Marketplace private offer updates and multiparty expansion - Available](https://partner.microsoft.com/en-us/blog/article/marketplace-post-ignite-2026)  
      *Multiparty private offers reach Saudi Arabia and Malaysia, buyers can request private offers from listings with one-step purchase, and 16-currency pricing is coming.*

### Notable Updates

- **Teams & Microsoft 365 platform:**
    - [Unified tasks and plans for Copilot and Microsoft 365 - Rolling Out](https://techcommunity.microsoft.com/blog/PlannerBlog/introducing-unified-tasks-and-plans-for-copilot-and-microsoft-365/4573958)  
      *One plan model replaces separate To Do and Planner plan types across Microsoft 365; To Do apps retire June 2027.*

- **Copilot Studio & Power Platform:**
    - [Power Pages sites in Power Platform inventory - Public Preview](https://www.microsoft.com/en-us/power-platform/blog/2026/11/19/discover-and-review-power-pages-sites-with-power-platform-inventory-public-preview/)  
      *Find, filter and export Power Pages sites across environments in the Power Platform admin center inventory, or query them through Azure Resource Graph.*

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
    - [RDMA over USB4 on Windows for multi-PC local AI - Developer Preview](https://techcommunity.microsoft.com/blog/MicrosoftUSBBlog/introducing-rdma-over-usb4%C2%AE-on-windows-run-larger-local-ai-models-across-pcs/4574602)  
      *Link Windows PCs over USB4 with RDMA so one local AI model can span their combined memory and GPUs; the Insider build is coming soon.*
    - [Windows ML on the MLIR-based DirectX Compute Graph Compiler - Experimental](https://devblogs.microsoft.com/foundry-on-windows/winml-cgc/)  
      *Windows ML 2.9.42 adds an MLIR-based DirectX compiler backend built with AMD, Intel, NVIDIA and Qualcomm, plus GGUF and SafeTensors Task APIs.*

- **Windows 365 & Azure Virtual Desktop:**
    - [Windows 365 at Ignite 2026: Cloud PCs for people and agents - GA + Preview](https://techcommunity.microsoft.com/blog/windows-itpro-blog/windows-365-at-ignite-2026-introducing-new-cloud-pc-capabilities-for-people-agen/4570006)  
      *Direct Stream, Windows 365 admin assistant, monitoring platform GA, context-based redirections and Cloud PC protections.*
    - [Windows 365 for Agents - GA + Preview](https://techcommunity.microsoft.com/blog/windows-itpro-blog/windows-365-at-ignite-2026-introducing-new-cloud-pc-capabilities-for-people-agen/4570006)  
      *Copilot Credits eligibility, Foundry integration, persistent agent Cloud PCs (Frontier) and on-premises app access.*

- **Microsoft Edge:**
    - [Edge for Business Ignite 2026 innovations - GA + Preview](https://blogs.windows.com/msedgedev/2026/11/17/edge-for-business-ignite-2026-innovations/)  
      *Cowork agentic browsing GA, managed agent browsing, extension risk scores, leak controls, Sentinel connector and private app access.*
    - [Aion Instruct, Prompt API origin trial and Decisions API in Microsoft Edge - GA + Preview](https://blogs.windows.com/msedgedev/2026/11/19/hybrid-intelligence-on-the-web-introducing-aion-instruct-and-prompt-api-in-microsoft-edge/)  
      *Edge's built-in on-device model becomes the open-weight Aion Instruct; the Prompt API enters an origin trial and a Decisions API reaches developer preview.*

- **Windows security & management:**
    - [Windows endpoint security platform and Driver Quality Initiative - GA](https://techcommunity.microsoft.com/blog/Windows-ITPro-blog/whats-next-windows-endpoint-security-platform-and-driver-quality/4572663)  
      *User-mode APIs let security vendors protect Windows without kernel drivers, plus partner timelines and driver quality plans.*
    - [Windows baseline protection - Preview](https://techcommunity.microsoft.com/blog/windows-itpro-blog/a-verifiable-security-state-with-windows-baseline-protection/4572654)  
      *One versioned, attestable device security state with a Settings page, Intune reporting and a developer API.*
    - [Windows passwordless and sign-in updates - Preview](https://techcommunity.microsoft.com/blog/Windows-ITPro-blog/expand-passwordless-access-with-confidence/4572666)  
      *Windows Hello reliability, hybrid-join web sign-in, IAKerb, remote lock and BitLocker PIN changes for standard users.*
    - [Post-quantum TLS in Windows](https://techcommunity.microsoft.com/blog/microsoft-security-blog/preparing-for-a-post-quantum-future-with-tls-in-windows/4572619)  
      *Windows TLS adds pure ML-KEM key exchange and ML-DSA certificate authentication, with a crypto-agility roadmap.*
    - [Manage Windows Server alongside PCs in Intune - Preview](https://techcommunity.microsoft.com/blog/IntuneCustomerSuccess/manage-windows-servers-alongside-pcs-with-microsoft-intune/4572643)  
      *Enroll Windows Server Insider builds in Intune for configuration, compliance, apps, Autopatch updates and Conditional Access.*

---

## 🐙 GitHub & Developer Tools

> *GitHub Copilot, the Microsoft Copilot SDK, Visual Studio, VS Code and .NET*

### Key Announcements

- **GitHub Copilot:**
    - [Microsoft Copilot SDK 2.0 - GA](https://commandline.microsoft.com/microsoft-copilot-sdk-2-0-github/)  
      *Multi-tenant Rust runtime with per-session identity, host-owned tools and durable sessions; SDKs in six languages.*
    - [GitHub Copilot app: Microsoft Ignite releases - GA + Preview](https://github.blog/changelog/2026-11-17-github-copilot-app-microsoft-ignite-releases/) | [Azure DevOps integration](https://devblogs.microsoft.com/devops/azure-devops-integration-with-the-github-copilot-app-public-preview/)  
      *Azure DevOps repos from clone to merge and browser use in your signed-in browser (preview), plus GHES support GA.*
    - [Copilot code review: adaptive effort, secret detection and more - Announced](https://github.blog/changelog/2026-11-17-copilot-code-review-adaptive-effort-secret-detection-and-more/)  
      *Review depth adapts to each pull request, and reviews can flag secrets on added lines.*
    - [Secret scanning on demand for developers and agents - Public Preview](https://github.blog/changelog/2026-11-17-secret-scanning-on-demand-for-developers-and-agents/)  
      *Copilot's security-review specialist runs GitHub's 500+ secret detectors on changes in CLI, app, SDK and code review.*
    - [MAI Code 2 and MAI Code 2 Flash in GitHub Copilot - Announced](https://github.blog/changelog/2026-11-17-mai-code-2-and-mai-code-2-flash-in-github-copilot/)  
      *Next-gen Microsoft coding models for agentic engineering, selectable across VS Code, VS, CLI, app, JetBrains and more.*
    - [GitHub Copilot Fusion updates - Announced](https://github.blog/changelog/2026-11-17-github-copilot-fusion-updates-more-availability-benchmarks-and-models/)  
      *Fusion model-routing reaches github.com, Visual Studio and Mobile betas, adds MAI-Code-2 and other models.*
    - [Stream GitHub Copilot agent activity to Agent 365 - Public Preview](https://github.blog/changelog/2026-11-17-monitor-github-copilot-activity-through-microsoft-agent-365)  
      *Enterprises send Copilot agent audit data from all clients into Agent 365's control plane.*
    - [GitHub Event Streams - Public Preview](https://github.blog/changelog/2026-11-17-github-event-streams-is-now-in-preview)  
      *Agents and integrations subscribe to resource changes instead of polling, waking only when work arrives.*
    - [Browser use for GitHub Copilot across CLI, app, VS Code and JetBrains - Public Preview](https://github.blog/changelog/2026-11-17-let-github-copilot-interact-with-your-browser/)  
      *With the Copilot Chrome extension, Copilot drives your signed-in browser to debug web apps, run tests and finish tasks.*
    - [GitHub Copilot Evals - Public Preview](https://github.blog/changelog/2026-11-17-github-copilot-evals-is-now-in-public-preview/)  
      *Build and rerun repeatable evals for skills, custom agents and MCP tools in VS Code, the CLI and the app.*
    - [GitHub Copilot in JetBrains: Ignite releases - Public Preview](https://github.blog/changelog/2026-11-17-github-copilot-in-jetbrains-ignite-releases/)  
      *Cloud sandbox, remote access, browser use and on-device voice dictation previews come to the JetBrains plugin.*
    - [GitHub Copilot CLI sign-in with Microsoft Entra - Public Preview](https://github.blog/changelog/2026-11-17-github-copilot-cli-adds-microsoft-entra-sign-in-as-a-preview/)  
      *Sign in to Copilot CLI with Entra for silent EMU SSO or to use a Microsoft 365 Copilot license.*
    - [Track Copilot code review outcomes in Repository insights](https://github.blog/changelog/2026-11-17-track-copilot-code-review-outcomes-in-repository-insights/)  
      *A new Repository insights page shows how Copilot review comments get addressed and which merged PRs skipped review.*
    - [Gemini 4 Neon in GitHub Copilot - GA](https://github.blog/changelog/2026-11-18-gemini-4-neon-in-github-copilot)  
      *Google's Gemini 4 Neon is GA in Copilot for agentic coding and tool use, near Gemini 4 Carbon quality at a lower token cost.*
    - [OpenAI's GPT-6.2 Astra and GPT-6.2 Sol in GitHub Copilot - GA](https://github.blog/changelog/2026-11-17-openais-gpt-6-2-astra-and-gpt-6-2-sol-now-available)  
      *Both models are GA in Copilot for agentic coding and code review, catching more real issues than earlier GPT-6 models.*

- **Azure DevOps & .NET:**
    - [Azure DevOps Sprint 282: Cowork plugin and Agentic Autofix - GA + Preview](https://learn.microsoft.com/en-us/azure/devops/release-notes/2026/sprint-282-update)  
      *Azure DevOps plugin for Copilot Cowork and Copilot-drafted fixes for GitHub Advanced Security for Azure DevOps alerts.*
    - [Copilot Code Review for Azure DevOps - GA + Preview](https://devblogs.microsoft.com/devops/azure-devops-and-github-start-your-agentic-journey-where-you-are/) | [GA details](https://devblogs.microsoft.com/devops/copilot-code-reviews-for-azure-repos-is-generally-available/)  
      *Copilot reviews Azure Repos pull requests through branch policies with per-review billing; Autofix and Azure Repos in the Copilot app are in preview.*
    - [Aspire 17 - Available](https://devblogs.microsoft.com/aspire/whats-new-aspire-17/) | [What's new](https://aspire.dev/whats-new/aspire-17/)  
      *Major Aspire release: redesigned dashboard with tags, team config sources for templates and skills, Go AppHosts in preview, and stable Kubernetes and AKS deployment.*

- **Azure CLI & PowerShell:**
    - [Next generation of Azure CLI and Azure PowerShell - Public Preview](https://techcommunity.microsoft.com/blog/AzureToolsBlog/announcing-public-preview-of-the-next-generation-of-azure-cli-and-azure-powershe/4573824)  
      *A shared command engine with named sign-in profiles, better command help and optional AI troubleshooting for failed CLI commands.*
    - [PowerShell 7 coming to Windows - Announced](https://devblogs.microsoft.com/powershell/powershell-7-coming-to-windows/) | [Windows Insider build](https://learn.microsoft.com/en-us/windows-insider/release-notes/experimental-future-platforms/preview-build-29712-1000)  
      *The next Windows release ships PowerShell 7 in the box next to Windows PowerShell 5.1, so existing scripts keep running; it installs as MSIX.*

### Notable Updates

- **Azure DevOps & .NET:**
    - [.NET 11 - GA](https://devblogs.microsoft.com/dotnet/announcing-dotnet-11/)  
      *Annual .NET release shipped at .NET Conf the week before Ignite; .NET 8 and .NET 9 left support the same day.*
    - [Enterprise Live Migrations from Azure DevOps to GitHub Enterprise Cloud - GA](https://github.blog/changelog/2026-11-19-enterprise-live-migrations-from-azure-devops-generally-available/)  
      *Move Azure DevOps repos, history and pull requests to GHE.com with data residency while teams keep working, then cut over.*
    - [Staged publishing on NuGet.org - Available](https://devblogs.microsoft.com/dotnet/nuget-staged-publishing/)  
      *Stage packages privately on NuGet.org through full validation, then an authorized maintainer promotes them; staging-only API keys keep pipelines from publishing directly.*

- **GitHub Copilot:**
    - [Customize GitHub Copilot for your team - GA](https://github.blog/changelog/2026-11-18-customize-github-copilot-for-your-team/)  
      *Team maintainers set approved agent plugins as team defaults across VS Code, the Copilot app and CLI.*
    - [More Copilot connectors: Supabase, Box, Calendly and others - Public Preview](https://github.blog/changelog/2026-11-18-connect-supabase-box-calendly-and-more-to-copilot/)  
      *Eight more GitHub-verified MCP connectors including Box, Buildkite, ClickUp, Mixpanel, Supabase, Webflow and Wix.*
    - [Wait for pull request events with GitHub CLI - Preview](https://github.blog/changelog/2026-11-18-wait-for-pull-request-events-with-github-cli/)  
      *gh event listen lets agents and scripts wait for pull request events instead of polling.*
    - [Agent Host Protocol for sessions that continue across devices](https://github.blog/engineering/engineering-principles/building-the-agent-host-protocol-for-sessions-that-continue-across-devices/)  
      *Open protocol behind Copilot session continuity across VS Code, the app, mobile and cloud, with libraries in six languages.*
    - [GitHub Copilot benchmarks: harness comparisons and Terminal-Bench-Science - Public Preview](https://github.blog/changelog/2026-11-17-github-copilot-benchmarks-site-adds-harness-comparisons)  
      *The Copilot benchmarks site adds Terminal-Bench-Science 0.1 and a view that compares agent harnesses.*
    - [Plugin-only controls for GitHub Copilot customizations](https://github.blog/changelog/2026-11-16-control-where-github-copilot-customizations-come-from/)  
      *Enterprise admins can require skills, agents, hooks, MCP servers or extensions to come only from plugins or managed settings.*

- **GitHub security & administration:**
    - [Security risk assessments run automatically on GitHub Team - Available](https://github.blog/changelog/2026-11-18-security-risk-assessments-run-automatically-on-github-team)  
      *Free code and secret risk assessments now run automatically for GitHub Team organizations, surfacing exposed credentials and vulnerabilities.*
    - [S3 audit log streaming with OpenID Connect on GHE.com - Available](https://github.blog/changelog/2026-11-19-s3-audit-log-streaming-with-openid-connect-expands-to-ghe-com)  
      *Stream enterprise audit logs to Amazon S3 with OIDC on GitHub Enterprise Cloud with data residency, without long-lived AWS keys.*
    - [Bulk start for AI Scan for repositories - Public Preview](https://github.blog/changelog/2026-11-16-bulk-start-ai-scan-for-repositories/)  
      *Start AI vulnerability scans on up to 20 repositories at once from org settings or code scanning alerts, with no Copilot license needed.*

- **VS Code:**
    - [Skills over MCP in VS Code - Available](https://techcommunity.microsoft.com/blog/AzureDevCommunityBlog/skills-over-mcp-are-now-available-in-vs-code/4574580)  
      *VS Code 1.147 and later can load agent skills served by MCP servers, sharing authentication and versioning with tools.*
    - [Copilot harness is now the default in VS Code](https://code.visualstudio.com/blogs/2026/11/18/copilot-harness) | [Release notes](https://code.visualstudio.com/updates/v1_147)  
      *New agent sessions use the Copilot SDK-based harness shared with Copilot CLI and app; the Local harness is deprecated, with removal in February 2027.*

- **GitHub Actions:**
    - [Red Hat Enterprise Linux images for GitHub-hosted larger runners - GA](https://github.blog/changelog/2026-11-19-red-hat-enterprise-linux-runner-images-now-generally-available/)  
      *RHEL 9 and RHEL 10 images for GitHub-hosted larger runners leave preview and are supported for production Actions workflows.*

- **GitHub apps & clients:**
    - [GitHub Desktop multiple accounts per host](https://github.blog/changelog/2026-11-19-github-desktop-now-supports-multiple-accounts-per-host/)  
      *Sign in to several accounts on one host (GitHub.com, GHES or GHE.com) and tie each repository to the right account in Desktop 3.7.0.*

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
    - [What's new with Microsoft Perception at Ignite 2026 - GA + Preview](https://techcommunity.microsoft.com/blog/perception-blog/whats-new-with-microsoft-perception-at-ignite-2026/4571834) | [Third-party data](https://techcommunity.microsoft.com/blog/perception-blog/more-signals-stronger-defense-microsoft-perception-expands-to-third-party-data/4573037)  
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
    - [Zero-day and emerging threat insights in Microsoft Defender threat intelligence - Public Preview](https://techcommunity.microsoft.com/blog/microsoft-security-blog/threat-intelligence-that-moves-at-the-speed-of-the-threat-what%E2%80%99s-new-at-microsof/4573823)  
      *Zero-day tags, region and industry filters and email alerts, plus Perception playbooks launched from threat articles.*

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
    - [Azure Adaptive Virtual Patching - Public Preview](https://techcommunity.microsoft.com/blog/AzureNetworkingBlog/the-patch-window-is-closing-put-time-back-on-the-defender%E2%80%99s-side-/4573402)  
      *AI-orchestrated shield that reduces zero-day exposure while patches are tested and rolled out.*
    - [AI Security add-on for Azure Firewall Premium - Public Preview](https://techcommunity.microsoft.com/blog/AzureNetworkingBlog/secure-ai-secure-with-ai-introducing-the-next-chapter-of-azure-firewall-/4573399)  
      *Five capabilities to protect AI apps, sensitive data and app traffic at the firewall.*
    - [Azure Firewall for Containers - Public Preview](https://azure.microsoft.com/updates?id=581963)  
      *Extends Azure Firewall protection and centralized traffic control to containerized workloads as part of your container networking design.*
    - [Azure Bastion RDP and SSH vision - Public Preview](https://techcommunity.microsoft.com/blog/AzureNetworkingBlog/from-recordings-to-insights-azure-bastion-brings-ai-to-privileged-session-review/4573409)  
      *AI summaries and risky-activity insights over recorded privileged sessions.*
    - [Azure DDoS Protection custom policy - GA](https://techcommunity.microsoft.com/blog/AzureNetworkSecurityBlog/azure-ddos-custom-policy-ga/4573866)  
      *Override auto-tuned detection thresholds per protected resource.*
    - [Azure DDoS Protection peacetime telemetry and NAT Gateway coverage - Public Preview](https://techcommunity.microsoft.com/blog/AzureNetworkingBlog/announcing-public-preview-of-azure-ddos-protection-peacetime-telemetry/4574781) | [NAT Gateway StandardV2 coverage](https://techcommunity.microsoft.com/blog/AzureNetworkSecurityBlog/ddos-support-for-natgwv2-ip---public-preview/4573913)  
      *See traffic outside active attacks and protect NAT Gateway StandardV2 outbound IPs.*
    - [Azure Key Vault Premium symmetric (oct-HSM, AES) keys - GA](https://azure.microsoft.com/updates?id=579374)  
      *Symmetric AES encryption directly in Key Vault Premium, after a July preview.*
    - [Azure Baseline Security Mode - Public Preview](https://techcommunity.microsoft.com/blog/AzureGovernanceandManagementBlog/introducing-azure-baseline-security-mode-a-simpler-path-to-secure-by-default-azu/4573056)  
      *Guided experience that applies curated Azure Policy controls for Storage and Key Vault to reach secure-by-default baselines.*
    - [AI bot ruleset for Azure Front Door Premium WAF - Public Preview](https://azure.microsoft.com/updates?id=581604)  
      *Sort AI crawlers and agents into four groups and allow, block, log or challenge each at the edge.*

- **Agent 365 governance:**
    - [What's new in Microsoft Agent 365 at Ignite 2026 - GA + Preview](https://techcommunity.microsoft.com/blog/agent-365-blog/whats-new-in-microsoft-agent-365-ignite-2026/4571753)  
      *Agent ID for connected platforms, shadow agent discovery, tools registry GA, multi-tenant management, and usage insights for Microsoft agents now included.*

- **Email security:**
    - [Reject Direct Send in Exchange Online - GA](https://techcommunity.microsoft.com/blog/Exchange/reject-direct-send-now-generally-available-in-exchange-online/4573787)  
      *Block unauthenticated Direct Send mail that spoofs your own domains; on by default for new tenants, opt-in for existing ones.*

- **Supply chain & Zero Trust:**
    - [Artifact Signing with Signing Transparency - Private Preview](https://techcommunity.microsoft.com/blog/microsoft-security-blog/artifact-signing-with-signing-transparency-private-preview/4572667)  
      *SCITT-based transparency ledger for Artifact Signing gives verifiable software, firmware and hardware supply-chain evidence.*

### Notable Updates

- **Identity, data & endpoint:**
    - [Faster Intune device management - Rolling Out](https://techcommunity.microsoft.com/blog/microsoftintuneblog/intune%E2%80%99s-journey-to-faster-device-management/4574234)  
      *Push notifications for app and script deployments, a unified Sync action, faster reporting and delta app inventory cut Intune delays.*
    - [Diagnostic Data Reports in Remote Help for Windows - Rolling Out](https://techcommunity.microsoft.com/blog/IntuneCustomerSuccess/build-faster-trusted-remote-support-with-diagnostic-data-reports-in-remote-help/4573942)  
      *Helpdesk staff can request a user-approved diagnostic snapshot of the device during attended Remote Help sessions.*

- **Supply chain & Zero Trust:**
    - [Zero Trust Assessment: SecOps checks and Workshop import](https://techcommunity.microsoft.com/blog/microsoft-security-blog/accelerate-zero-trust-for-ai-expanded-secops-coverage-and-new-guides-to-turn-ins/4573339)  
      *26 new security operations checks, scheduled enterprise runs and direct import into the Zero Trust Workshop.*

---

## 🔬 Science, Research & Quantum

> *Microsoft Research, scientific discovery and quantum*

### Key Announcements

- **Microsoft Planetary Computer:**
    - [GeoStats in Microsoft Planetary Computer Pro - Preview](https://techcommunity.microsoft.com/blog/microsoft-planetary-computer-blog/join-us-for-the-geostats-preview-in-microsoft-planetary-computer-pro/4573856)  
      *Compute zonal statistics such as NDVI from satellite imagery over your own boundaries as analysis-ready tables.*
    - [AI Workflow in Microsoft Planetary Computer Pro - Private Preview](https://techcommunity.microsoft.com/blog/microsoft-planetary-computer-blog/join-us-in-using-ai-workflow-preview-feature-in-microsoft-planetary-computer-pro/4571817)  
      *Run Foundry-hosted geospatial AI models over GeoCatalog imagery and catalog the outputs; access by request.*

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

*Last updated: November 21, 2026*
