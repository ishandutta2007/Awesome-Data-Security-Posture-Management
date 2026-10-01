# Awesome-Data-Security-Posture-Management

## Top Data Security Posture Management (DSPM) Platforms Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Sensitive Data Discovery, Classification, Access Governance & Data Risk Prioritization*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Data Security Posture Management (DSPM)**. These tools help security teams discover and classify sensitive data, identify excessive access, detect data leakage risks, and continuously monitor data security posture across cloud environments.



**Examples** include Cyera, BigID, Varonis, Sentra, Laminar, Rubrik DSPM, Normalyze, Securiti, Dig Security, Wiz DSPM, Microsoft Purview DSPM, Symmetry Systems, and Concentric AI (the category leaders).



**Open-source emphasis**: DSPM is a **commercially dominated category**—Cyera, BigID, and Varonis lead the market. However, the **open-source foundation is maturing rapidly**, particularly for **cloud security posture** and **data discovery/classification**. **Prowler** provides 800+ security checks across AWS, Azure, GCP, and Kubernetes with compliance frameworks . **OpenKAT** is a mature, government-backed vulnerability analysis tool integrating 50+ security scanners . **cnspec** delivers cross-cloud policy checks for cloud, Kubernetes, APIs, and endpoints . **data-boar** focuses on personal and sensitive data discovery with compliance-aware scanning for LGPD, GDPR, and CCPA . **Meta's Automated Sensitive Document Classification** uses LLMs to automatically classify and label sensitive documents . This section documents these production-grade and emerging solutions.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents



- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Cyera](https://www.cyera.com/)**

  AI-powered DSPM leader. Automatically discovers, classifies, and protects sensitive data across multi-cloud environments, with data risk prioritization and access governance.



- **[BigID](https://bigid.com/)**

  Data intelligence platform focused on data discovery, classification, and privacy compliance. Provides sensitive data discovery, access intelligence, and risk monitoring for GDPR, CCPA, and more.



- **[Varonis](https://www.varonis.com/)**

  Data security platform focused on data access governance and threat detection. Analyzes file activity, permissions, and user behavior to detect insider threats, ransomware, and data exfiltration.



- **[Sentra](https://www.sentra.io/)**

  Cloud-native DSPM platform focused on **Data Detection & Response (DDR)** and **Data Access Governance (DAG)**. Provides automated data discovery, classification, risk prioritization, and remediation across IaaS, PaaS, SaaS, and on-premises environments . Supports 20+ prebuilt or custom integrations including Datadog and Trellix, serving finance, healthcare, and retail industries .



- **[Laminar (Rubrik)](https://www.rubrik.com/)**

  Cloud data security platform (acquired by Rubrik in 2023) focused on DSPM. Provides cloud data discovery and classification, data risk prioritization, cloud data protection, and continuous data monitoring . Key metrics include data classification accuracy (false positive rate), cloud storage cost reduction (by eliminating shadow data), and scan time .



- **[Securiti](https://securiti.ai/)**

  Unified Data + AI Security platform, ranked #1 in GigaOm's DSPM Radar for three consecutive years . The **DataAI Command Graph** provides centralized insight across data security, access governance, compliance, AI security, ROT data reduction, and breach management . **Classification Tuning Agent** automatically adjusts classification models without re-scanning data. Supports **LLM Firewall** to protect AI systems by monitoring prompts, data retrieval, and responses . Named a Customers' Choice for DSPM in Gartner Peer Insights .



- **[Normalyze](https://normalyze.com/)**

  DSPM platform focused on cloud data security and compliance. Provides data discovery, classification, access analysis, and risk prioritization.



- **[Dig Security](https://www.dig.security/)**

  Cloud data security platform (acquired by Palo Alto Networks). Provides DSPM and DDR capabilities protecting data across cloud environments.



- **[Wiz DSPM](https://www.wiz.io/)**

  Data security module within Wiz's CNAPP platform. Correlates data context through the Security Graph, identifying sensitive data exposure and excessive access.



- **[Microsoft Purview DSPM](https://www.microsoft.com/en-us/security/business/microsoft-purview)**

  Data security posture management capabilities within Microsoft Purview. Provides sensitive data discovery, classification, and risk monitoring across Microsoft 365, Azure, and third-party data sources.



- **[Symmetry Systems](https://symmetry-systems.com/)**

  Data security platform focused on data access governance and DSPM. Provides data discovery, classification, and permission analysis.



- **[Concentric AI](https://concentric.ai/)**

  AI-powered data security platform focused on unstructured data discovery, classification, and protection. Provides semantic understanding to automatically identify sensitive content.



## Open-Source GitHub Projects



### Cloud Security & Compliance Platforms



- **[Prowler](https://github.com/prowler-cloud/prowler)**

  **The most widely used open-source cloud security posture and compliance platform.** **Apache-2.0 licensed**. Provides **800+ security checks** across **AWS, Azure, GCP, Kubernetes, Microsoft 365, GitHub, Okta, Alibaba Cloud, Cloudflare**, and more . **Compliance frameworks**: CIS, NIST, PCI DSS, HIPAA, GDPR, ISO 27001, SOC 2, and DORA . **Attack Paths** feature enables visualization of attack vectors based on actual exploitability. **Lighthouse AI** provides agentic cloud defense with natural language remediation driven by GPT models. **Key capabilities**: Automated security assessments; multi-cloud support; custom check development; HTML, JSON, CSV, and JUnit output; integration with AWS Security Hub, Azure Defender, and GCP Security Command Center .



- **[OpenKAT](https://github.com/minvws/nl-kat-coordination)**

  **Mature open-source vulnerability analysis tool developed by the Dutch Ministry of Health (MinVWS).** Originally built to secure COVID-19 systems and now widely used . **Core capability**: Scans networks, analyzes vulnerabilities, and generates accessible reports; **integrates 50+ high-quality scanning tools** into a modular framework; queries external databases and combines information into **facts with forensic guarantees** . **Key features**: Multi-tenancy (fully isolated organizations); scalable to hundreds of organizations with 20k+ assets each; **bitemporal storage** (view historical state of networks); **forensic guarantees** (timestamps on operations and results); business rules based on own policies; API connections . **Deployment**: Free, open-source, self-hosted. Governed by the **Stichting LibreKAT Foundation** .



- **[cnspec](https://github.com/mondoohq/cnspec)**

  **Open-source security and policy checker across cloud, containers, APIs, and endpoints.** Finds vulnerabilities and misconfigurations across public and private cloud environments, Kubernetes clusters, containers, container registries, servers, endpoints, SaaS products, infrastructure-as-code, and APIs . **Scan targets**: AWS, Google Cloud, Azure, Kubernetes, container images, Linux/macOS/Windows endpoints, Microsoft 365, Atlassian, Okta, Terraform HCL, GitHub/GitLab, IoT/OPC-UA devices, VMware, and more . Policy-as-code engine based on a **security data mesh**. Default policies work out of the box and are extendable and customizable .



### Data Discovery & Classification



- **[data-boar](https://socket.dev/pypi/package/data-boar)**

  **Compliance-aware personal and sensitive data discovery and mapping tool (LGPD, GDPR, CCPA, and configurable frameworks).** **Core design**: Ingests from multiple sources (files, SQL, NoSQL, APIs, Power BI, Dataverse, SharePoint, SMB/NFS) **without storing or leaking PII — only metadata** (where it was found, pattern type, sensitivity), providing actionable visibility without data movement . **Framework support**: Baseline patterns cover LGPD, GDPR, CCPA, GLBA; example configurations extend to UK GDPR, EU GDPR, PIPEDA, POPIA, APPI, PCI-DSS, US healthcare vocabularies, and more . **Outputs**: Excel reports, heatmaps, cross-session trends; API allows scheduled scans . **Security features**: Validation, headers, auditing; in-archive scanning (zip, tar, gz, 7z); content-type detection to identify renamed files; early encryption/transport visibility (TLS vs plaintext). **Deployment**: Docker Hub image `fabioleitao/data_boar` .



- **[Meta Automated Sensitive Document Classification](https://github.com/facebook/automated-sensitive-document-classification)**

  **Meta's open-source AI data leak prevention tool using LLMs to automatically classify and label sensitive documents.** **Core innovation**: Unlike traditional rule-based or RegEx approaches, uses **Large Language Model (LLM) technology** as the core engine for higher accuracy and extensibility . **Features**: Identifies sensitive content and automatically adds labels; integrates directly with Google Docs, Sheets, and Slides via Google Drive API; supports Apache Tika for document text parsing; records classification results, MD5 checksums, and processing status in SQLite database, exporting CSV reports for auditing . **Customization**: Supports multi-level classification policies configurable to enterprise security policies . **Deployment**: Docker container or Python module, local or cloud . **Native support**: Llama models and Google Drive integration; future plans for Office 365 sensitivity labels and local inference platforms like Ollama .



### Data Governance & Access Control



- **[Apache Ranger](https://github.com/apache/ranger)**

  **Open-source data security framework providing centralized access control and auditing.** **Core capabilities**: Enable, monitor, and manage comprehensive data security across Hadoop ecosystem and beyond; **centralized security administration with access control and auditing** . **Access policies**: Support rule definitions at file, folder, database, table, and column levels; policies can be defined per user, role, or group . **Auditing**: Centralized user access and administrative action auditing, compatible with Elasticsearch and Solr audit stores . **Integration**: Widely accepted across AWS, Azure, GCP, and major cloud providers . **Use cases**: Data access governance and compliance auditing for big data platforms .



### Additional Strong Open-Source Options



- **Cloud Security & Compliance**: **Prowler** (800+ checks, multi-cloud), **OpenKAT** (Dutch Ministry of Health, 50+ scanners), **cnspec** (cross-cloud policy checks) .

- **Data Discovery & Classification**: **data-boar** (compliance-aware, metadata only), **Meta Sensitive Document Classification** (LLM-powered, auto-labeling) .

- **Data Governance**: **Apache Ranger** (centralized access control and auditing) .

- **SIEM/HIDS**: **Wazuh** (HIDS/SIEM with data security monitoring and compliance checks for CMMC, GDPR, PCI DSS, HIPAA) .



**Frameworks for building custom systems**: Combine **Prowler** or **cnspec** for cloud security posture and compliance checks, **OpenKAT** for vulnerability analysis and asset monitoring, **data-boar** or **Meta Sensitive Document Classification** for data discovery and classification, and **Apache Ranger** for data access governance. Add **PostgreSQL** for persistence and **Docker/Kubernetes** for deployment.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- DSPM platforms handle sensitive cloud data and access permission information; ensure compliance with GDPR, CCPA, HIPAA, and relevant data protection regulations.

- **Open-source reality**: The open-source ecosystem for DSPM is **mature at the cloud security posture layer** (**Prowler**, **cnspec**), **vulnerability analysis layer** (**OpenKAT**), and **data discovery/classification layer** (**data-boar**, **Meta Sensitive Document Classification**) . **Apache Ranger** provides a mature data access governance framework . However, **commercial platforms** (Cyera, BigID, Varonis, Securiti, Sentra) provide **AI-driven data classification precision, cross-cloud data correlation, automated remediation, and compliance reporting** that open-source alternatives require significant assembly and engineering investment to match. The open-source path is most viable for **cloud security posture, vulnerability analysis, or specific data discovery use cases**, rather than full DSPM platform replacement.



---



**Made for security engineers, data security officers, compliance teams, and cloud security architects.**

Let's make data security posture management more open, transparent, and actionable.
