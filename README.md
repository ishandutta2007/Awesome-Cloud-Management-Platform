# Awesome-Cloud-Management-Platform



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Cloud Orchestration, Infrastructure Automation & Multi-Cloud Management*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud Management Platforms (CMP)**. These tools help organizations orchestrate virtual machines, automate infrastructure provisioning, manage multi-cloud resources, and enforce governance across hybrid environments.



**Examples** include Microsoft Azure Portal, AWS Management Console, Google Cloud Console, VMware Aria Cost, Flexera Cloud Management, Morpheus Data, Terraform Cloud, Apptio Cloudability, CloudHealth, and Spot by NetApp (the category leaders).



**Open-source emphasis**: Cloud management has a **mature open-source ecosystem** led by **Apache CloudStack**, **OpenNebula**, and **OpenStack** — all production-grade CMPs used by service providers and enterprises worldwide . **Terraform** and **Crossplane** provide infrastructure-as-code and Kubernetes-native control planes, while **OpenCost** delivers free Kubernetes cost visibility . However, **no open-source alternative matches the unified multi-cloud governance** of Morpheus Data or Flexera.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## 📖 Table of Contents


- [☁️ SaaS/Hosted Platforms](#-saas-hosted-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🤝 How to Contribute](#-how-to-contribute)
- [⚠️ Disclaimer](#-disclaimer)


## ☁️ SaaS/Hosted Platforms



> **📊 Market Context**: The global cloud management platform market is estimated at **~$18B in 2026**, growing toward **~$45B by 2032** at a **~16% CAGR**. The sector is **moderately fragmented** — hyperscalers bundle native consoles (Azure Portal, AWS Console, GCP Console) as free value-adds, while specialized FinOps and orchestration vendors compete on multi-cloud governance. **Pricing models vary dramatically**: CloudHealth charges **1.85%–4% of tracked cloud spend** with a **$45,000/year minimum** for the CH150K tier , Cloudability uses a **percentage-of-spend model starting at ~$30,000/year** for $1M cloud spend , and Apptio enterprise contracts range from **under $100K to $1M+ annually** with services often representing **30–50% of first-year costs** . No single vendor holds a winner-take-all position; enterprises typically run multi-vendor stacks.



| Platform | Description | Pricing (Starting Tier) | Free Tier Limits | Company Size |
|----------|-------------|------------------------|------------------|--------------|
| **[Microsoft Azure Portal](https://azure.microsoft.com/)** | Microsoft's web-based unified console for managing Azure resources. Integrated Copilot assistance. | **Free** — Azure Portal itself costs nothing. You pay for Azure resources consumed. | **Azure free account**: **$200 credit for 30 days** + **55+ always-free services** + 12 months of popular free services. | **~$281B revenue (Microsoft FY2025)** |
| **[AWS Management Console](https://aws.amazon.com/console/)** | AWS's web-based console for managing all AWS services. | **Free** — Console itself costs nothing. You pay for AWS resources consumed. | **AWS Free Tier**: **$100 sign-up credits** + up to **$100 additional** through activities. **Free plan**: 6 months or until credits exhausted. | **~$638B revenue (Amazon FY2025)** |
| **[Google Cloud Console](https://console.cloud.google.com/)** | Google's web-based console for managing GCP resources. Integrated Gemini assistance. | **Free** — Console itself costs nothing. You pay for GCP resources consumed. | **Google Cloud Free Tier**: **$300 credit for 90 days** + **20+ always-free products**. | **~$350B revenue (Alphabet FY2025)** |
| **[Morpheus Data](https://morpheusdata.com/)** | Hybrid cloud management with self-service provisioning, orchestration, and cost optimization across on-premises and public cloud. | **Custom pricing** — sales-led only. No self-serve tiers published . Entry contracts typically start at **~$50K/year** for mid-size deployments. | **None** — sales contact required. Free trial may be available on request . | **Private (~$50M+ raised est.)** |
| **[VMware Aria Cost](https://www.vmware.com/)** | Multi-cloud cost analysis and governance (formerly CloudHealth). Transitioning to subscription-only. | **Subscription-only** — no perpetual licences. Frequently bundled into broader Aria/VMware deals . | **None** — enterprise demo required. | **Part of Broadcom (~$51B revenue)** |
| **[Flexera Cloud Management](https://www.flexera.com/)** | Cloud cost management and IT asset management (formerly RightScale). Usage-based pricing. | **Usage-based**: **$1.42/100 vCPU hours** (Spot/Preemptible). **$50,000/year** package covers up to **$1M annual cloud spend** . | **Free tier**: Covers up to **20 virtual machines** . No perpetual free tier beyond that. | **Private (~$300M+ revenue est.)** |
| **[Terraform Cloud (HCP Terraform)](https://www.hashicorp.com/)** | Managed Terraform service for infrastructure-as-code collaboration, policy enforcement, and state management. | **Essentials**: **$0.10/resource/month**; **Standard**: **$0.47/resource/month**; **Premium**: **$0.99/resource/month** . | **Free tier**: Up to **500 managed resources** with unlimited users (legacy unlimited free tier discontinued March 31, 2026) . | **Private (~$500M+ revenue est.)** |
| **[Apptio Cloudability](https://www.apptio.com/)** | Enterprise FinOps platform for cloud cost management, optimization, and governance. | **Percentage-of-spend model**: Starts at approximately **$30,000/year** for $1M cloud spend; **$76K–$132K** for $3M–$6M spend . Overage rates **$1,650–$4,410** per unit . | **None** — enterprise demo required. | **Part of IBM (~$63B revenue)** |
| **[CloudHealth](https://www.vmware.com/)** | Multi-cloud management platform with cost optimization, governance, and security (now Broadcom). | **1.85%** (Advanced), **2.5%** (Enterprise), **4%** (Enterprise Plus) of total public cloud spend . **CH150K tier**: **$45,000/year** for up to **$150K/month** cloud spend . | **None** — free trial available but no perpetual free tier . | **Part of Broadcom (~$51B revenue)** |
| **[Spot by NetApp](https://spot.io/)** | Optimization-led cloud cost platform automating infrastructure scaling and spot instance management. | **Quote-based** or tied to a share of savings. No general free tier . | **None** — premium tier, no free tier . | **Part of NetApp (~$6B revenue)** |



## 🔓 Open-Source GitHub Projects



Sorted by star count (descending). Star badge links to each repo's stargazers page.



| Repo | Description | Stars |
|---|---|---|
| **[Apache CloudStack](https://github.com/apache/cloudstack)** — **High-availability, scalable IaaS cloud computing platform** for public and private clouds. NFV orchestration, multi-hypervisor (KVM, VMware, XenServer), multi-tenancy, self-service portals. **Recommended as lower-complexity alternative to OpenStack** for service providers . Apache-2.0. | [![Stars](https://img.shields.io/github/stars/apache/cloudstack?style=social&color=white)](https://github.com/apache/cloudstack/stargazers) | ~1,800 |
| **[OpenNebula](https://github.com/OpenNebula/one)** — **Open-source cloud and virtualization management platform** unifying KVM VMs and Kubernetes clusters. **Lightweight, simple administration** for private and hybrid clouds. Vendor freedom, no lock-in . Apache-2.0. | [![Stars](https://img.shields.io/github/stars/OpenNebula/one?style=social&color=white)](https://github.com/OpenNebula/one/stargazers) | ~1,200 |
| **[Terraform](https://github.com/hashicorp/terraform)** — **Infrastructure as Code for provisioning cloud resources** across providers. HCL declarative configuration. BSL 1.1 (converted to OpenTofu fork). | [![Stars](https://img.shields.io/github/stars/hashicorp/terraform?style=social&color=white)](https://github.com/hashicorp/terraform/stargazers) | ~44,000 |
| **[Crossplane](https://github.com/crossplane/crossplane)** — **CNCF-graduated Kubernetes-native control plane** for provisioning and managing cloud infrastructure. API-first reconciliation, continuous drift correction . Apache-2.0. | [![Stars](https://img.shields.io/github/stars/crossplane/crossplane?style=social&color=white)](https://github.com/crossplane/crossplane/stargazers) | ~10,000 |
| **[OpenCost](https://github.com/opencost/opencost)** — **CNCF Incubating open-source cost monitoring for Kubernetes and cloud spend.** Real-time cost allocation, multi-cloud support, GPU costs, carbon costs, MCP server for AI agents . Apache-2.0. | [![Stars](https://img.shields.io/github/stars/opencost/opencost?style=social&color=white)](https://github.com/opencost/opencost/stargazers) | ~4,500 |
| **[OpenTofu](https://github.com/opentofu/opentofu)** — **Open-source Terraform fork under Linux Foundation governance.** Apache-2.0. | [![Stars](https://img.shields.io/github/stars/opentofu/opentofu?style=social&color=white)](https://github.com/opentofu/opentofu/stargazers) | ~25,000 |



**Additional open-source options worth exploring:**



| Repo | Description |
|---|---|
| **[c3x](https://pkg.go.dev/github.com/c3xdev/c3x)** — **Cloud cost estimation for Terraform, Terragrunt, and CloudFormation.** Optimization recommendations, budget guardrails, what-if analysis, fully offline mode. No API key required . | [![Go](https://img.shields.io/badge/Go-Package-blue)](https://pkg.go.dev/github.com/c3xdev/c3x) |
| **[ONAP](https://github.com/onap)** — **Open Network Automation Platform** for closed-loop automation in telecom/5G. Resource-intensive but mature . | [![ONAP](https://img.shields.io/badge/ONAP-Project-blue)](https://github.com/onap) |
| **[OSM](https://github.com/opensourceMANO)** — **Open Source MANO** — lightweight, ETSI-compliant NFV orchestration for constrained deployments . | [![OSM](https://img.shields.io/badge/OSM-Project-blue)](https://github.com/opensourceMANO) |



## 🤝 How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## ⚠️ Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Cloud management platforms handle sensitive infrastructure credentials and configuration; ensure proper access controls and compliance with organizational security policies.

- **Open-source reality**: The open-source ecosystem for cloud management is **mature and production-proven** at the **IaaS orchestration layer** (**CloudStack**, **OpenNebula**, **OpenStack**) and **infrastructure-as-code layer** (**Terraform**, **Crossplane**) . **OpenCost** provides free Kubernetes and cloud cost visibility with MCP support for AI agents . **c3x** offers offline cloud cost estimation for Terraform . However, **no open-source alternative matches the unified multi-cloud governance, FinOps intelligence, and enterprise support** of Morpheus Data, Flexera, CloudHealth, or Cloudability. The open-source path is **genuinely viable** for IaaS platforms, self-service portals, and infrastructure automation — but FinOps and cost management remain dominated by commercial vendors.

- **Pricing caveat**: All pricing figures above are **verified against cited search results** but may change without notice. Enterprise contracts typically involve volume discounts, multi-year commitments, and bundled pricing. **Percentage-of-spend models (Cloudability, CloudHealth) scale with your cloud bill** — forecast both feature needs and spend growth trajectory before committing .



---



**Made for cloud architects, platform engineers, DevOps teams, and FinOps practitioners.**

Let's make cloud management more open, transparent, and vendor-neutral.
