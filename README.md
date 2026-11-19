# Awesome-AI-Cybersecurity-Automated-Threat-Defense

## Top AI Cybersecurity & Automated Threat Defense Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on AI-Driven Threat Detection, Autonomous SOC & Incident Response, Endpoint Detection & Response (EDR/XDR), AI Pentesting & Security Skills*  

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Cybersecurity & Automated Threat Defense**. These tools leverage machine learning, behavioral anomaly detection, and autonomous AI agents to detect zero-day intrusions, triage SOC alerts, automate incident response playbooks, scan vulnerabilities, and harden enterprise infrastructure.



**Examples** include Darktrace, CrowdStrike Falcon, SentinelOne Singularity, Palo Alto Cortex XDR, Vectra AI, Cybereason, Zscaler AI Security, Trellix, McAfee MVISION (Skyhigh Security), Deep Instinct, and mukul975/Anthropic-Cybersecurity-Skills (the category leaders). 



**Open-source emphasis**: This section is heavily expanded with every major active project for open-source XDR/SIEM platforms (`Wazuh`), SOAR incident-response automation (`Shuffle`, `TheHive`, `Tracecat`), autonomous AI pentesting and red/blue-team agents (`PentestGPT`, `CAI`, `Strix`, `CAI`), network intrusion detection (`Zeek`, `Suricata`), and AI cybersecurity agent skill packs — ideal for SOC analysts, SecOps engineers, threat hunters, and security researchers building sovereign defense pipelines.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)



## Sector Overview & Market Dynamics

The global AI in Cybersecurity and Automated Threat Defense market is estimated at approximately **$39B – $51B in 2026** (scaling past $180B+ by the mid-2030s at an estimated CAGR of ~22%). The sector exhibits a **moderately concentrated platform core with a fragmented innovation edge**: while dominant security titans (Palo Alto Networks, CrowdStrike, Zscaler) capture the lion's share of enterprise budgets via unified XDR and SASE ecosystems, niche domains (agentic red/blue teaming, DSPM, and LLM guardrails) remain highly fragmented with hundreds of emerging point startups that continuously get consolidated or acquired.



## SaaS/Hosted Platforms

| Company / Product | Company Size (Market Cap / Valuation / ARR) | Starting Pricing | Free Tier / Free Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Palo Alto Networks Cortex XDR & XSIAM](https://paloaltonetworks.com)** | ~$198B - $264B Market Cap (~$11.5B ARR) | $40 / endpoint / year (Cortex XDR Prevent tier; Pro tier starts at $70 / endpoint / year) | 30-day guided Proof of Concept (PoC) / evaluation upon enterprise request (no permanent free tier) | AI-driven security operations and extended detection and response platform correlating endpoint, network, and cloud telemetry to automate SOC investigations. |
| **[CrowdStrike Falcon (Charlotte AI)](https://crowdstrike.com)** | ~$230B - $235B Market Cap (~$5.4B ARR) | $59.99 / device / year ($7.99/mo, Falcon Go tier; Enterprise tier starts at $184.99 / device / year) | 15-day free trial (up to 100 endpoints with NGAV, device control, and Falcon Insight XDR modules; no permanent free tier) | Cloud-native endpoint detection and response (EDR/XDR) platform powered by Charlotte AI for autonomous alert triage, threat hunting, and real-time breach prevention. |
| **[Zscaler Zero Trust & AI Security](https://zscaler.com)** | ~$30B - $31B Market Cap (~$3.35B ARR) | ~$100 / user / year (ZIA/ZPA foundational business bundles; Advanced Transformation suites start at $300 - $375 / user / year) | 30-day proof-of-concept / guided enterprise trial with interactive live demo lab (no permanent free tier) | Cloud-native Zero Trust Exchange incorporating AI-powered threat prevention, inline data loss prevention (DLP), and generative AI traffic governance. |
| **[SentinelOne Singularity (Purple AI)](https://sentinelone.com)** | ~$7.7B Market Cap (~$1.0B - $1.1B ARR) | $69.99 / endpoint / year (Singularity Core; Complete EDR starts at $179.99 / endpoint / year) | 30-day guided enterprise Proof of Concept (POC) / trial via sales evaluation (no permanent free tier) | Autonomous XDR and endpoint protection platform featuring Purple AI security analyst capabilities for natural-language threat hunting and automated remediation. |
| **[Darktrace (ActiveAI Security Platform)](https://darktrace.com)** | $5.3B Acquisition Valuation (~$685M ARR) | ~$20,000 - $35,000 / year (Foundational entry-level network/cloud deployment; median contracts ~$55,200 / year) | 30-day Cyber Threat and Risk Mitigation Proof of Value (POV) deployment with dedicated appliance/cloud sensor (no permanent free tier) | Self-learning cyber AI platform utilizing behavioral anomaly detection and Autonomous Response to neutralize novel threats across cloud, network, email, and endpoints. |
| **[Trellix XDR](https://trellix.com)** | ~$5.2B Combined PE Valuation (~$940M - $1.1B ARR) | ~$2,000 / year base entry SKU / block (standard enterprise seats ~£20 - £35 / user / year) | 30-day evaluation / trial license via enterprise sales request or AWS Marketplace sandbox (no permanent free tier) | Adaptive extended detection and response platform combining machine-learning threat intelligence with automated security operations workflows across hybrid environments. |
| **[Vectra AI](https://vectra.ai)** | $1.2B Valuation (~$120M - $178M ARR) | ~$8 - $22 / IP / year (Network Detection & Response; baseline mid-market contracts start ~$150,000 / year) | 30-day guided Proof of Concept (POC) evaluating live network/M365 cloud traffic metadata (no permanent free tier) | AI-powered network detection and response (NDR) and attack-signal intelligence platform uncovering hybrid-cloud lateral movement, identity compromise, and C2 activity. |
| **[Cybereason Defense Platform](https://cybereason.com)** | ~$850M Valuation (~$120M - $200M ARR) | ~$40 / endpoint / year (Foundational NGAV/EDR tier; scaling to $70+ / endpoint / year for automated MalOp XDR) | 30-day guided enterprise Proof of Concept (POC) / evaluation (no permanent free tier) | Cloud EDR/XDR and MalOp (Malicious Operation) detection platform providing AI-assisted root-cause correlation and automated endpoint containment. |
| **[Deep Instinct](https://deepinstinct.com)** | ~$500M - $1.0B Valuation (~$10M - $60M ARR) | ~$40 / endpoint / year (Baseline predictive deep-learning prevention tier) | 30-day guided enterprise Proof of Concept (POC) / trial on test endpoints (no permanent free tier) | Deep-learning cybersecurity platform trained on raw binary data to predict and prevent zero-day malware and ransomware in sub-20 milliseconds prior to execution. |
| **[Skyhigh Security (formerly McAfee MVISION Cloud)](https://skyhighsecurity.com)** | ~$400M+ Segment Value (~$100M - $250M ARR) | ~£16.77 / user / month (~$215 / user / year on standard public procurement cloud frameworks) | 30-day enterprise Proof of Concept (PoC) / guided interactive online simulation demo (no permanent free tier) | Cloud-native Security Service Edge (SSE) and CASB platform offering AI-assisted data protection, shadow-AI discovery, and zero-trust cloud access control. |





## Open-Source GitHub Projects



- **[mukul975/Anthropic-Cybersecurity-Skills](https://github.com)**  

  Open-source collection of modular `SKILL.md` cybersecurity workflows for AI coding and security agents covering threat intelligence, vulnerability assessment, incident response, and defensive hardening.



- **[Wazuh (`wazuh/wazuh`)](https://github.com)**  

  Flagship open-source (`GPL-2.0`) unified XDR and SIEM platform providing endpoint monitoring, log data analysis, file integrity monitoring, vulnerability detection, and active threat response.



- **[Shuffle (`Shuffle/Shuffle`)](https://github.com)**  

  Open-source (`AGPL-3.0`) Security Orchestration, Automation, and Response (SOAR) platform enabling visual drag-and-drop incident response playbooks with native LLM/AI triage nodes.



- **[Tracecat (`TracecatHQ/tracecat`)](https://github.com)**  

  Modern open-source (`AGPL-3.0`) AI-native security automation and SOAR platform engineered for rapid alert enrichment, case management, and LLM-assisted threat triage.



- **[TheHive (`TheHive-Project/TheHive`) & Cortex (`TheHive-Project/Cortex`)](https://github.com)**  

  Scalable open-source (`AGPL-3.0`) Security Incident Response Platform (SIRP) paired with Cortex observable analysis and automated responder engines for SOC teams.



- **[Velociraptor (`Velocidex/velociraptor`)](https://github.com)**  

  High-performance open-source (`AGPL-3.0`) digital forensics and incident response (DFIR) endpoint visibility tool powered by VQL queries for fleet-wide threat hunting and containment.



- **[Suricata (`OISF/suricata`)](https://github.com)**  

  Industry-standard open-source (`GPL-2.0`) multi-threaded Network Intrusion Detection (IDS), Intrusion Prevention (IPS), and Network Security Monitoring (NSM) engine.



- **[Zeek (`zeek/zeek`)](https://github.com)**  

  Powerful open-source (`BSD-3-Clause`) network traffic analysis framework transforming live packet streams into rich, structured security logs ideal for ML anomaly detection.



- **[PentestGPT (`GreyDGL/PentestGPT`)](https://github.com)**  

  Popular open-source (`MIT`) LLM-powered penetration testing assistant that guides and automates reconnaissance, vulnerability exploitation, and privilege escalation workflows.



- **[CAI — Cybersecurity AI (`aliasrobotics/cai`)](https://github.com)**  

  Open-source (`AGPL-3.0`) modular AI framework for offensive and defensive security agents supporting automated red-teaming, blue-team defense, and CTF/vulnerability discovery.



- **[Nuclei (`projectdiscovery/nuclei`)](https://github.com)**  

  Blazing-fast open-source (`MIT`) YAML-template-based vulnerability scanner powered by a massive community rule library and AI-assisted template generation.



- **[CrowdSec (`crowdsecurity/crowdsec`)](https://github.com)**  

  Collaborative open-source (`MIT`) behavior-based Intrusion Prevention System (IPS) analyzing server/container logs to block malicious IPs and share real-time threat intelligence.



- **[OSQuery (`osquery/osquery`)](https://github.com)**  

  Open-source (`Apache-2.0` / `GPL-2.0`) SQL-powered operating system instrumentation and endpoint analytics agent for real-time security monitoring across Linux, macOS, and Windows.



- **[Sigma (`SigmaHQ/sigma`)](https://github.com)**  

  Generic open-source (`DRL-1.1`) signature format and rule converter enabling SOC teams and AI agents to translate threat detections across SIEM/XDR backends seamlessly.



- **[MISP (`MISP/MISP`)](https://github.com)**  

  Leading open-source (`AGPL-3.0`) Threat Intelligence Platform (TIP) for gathering, sharing, correlating, and automating Indicators of Compromise (IoCs) across security tools.



- **[Garry / Garak (`NVIDIA/garak`)](https://github.com)**  

  Open-source (`Apache-2.0`) LLM and AI agent vulnerability scanner from NVIDIA probing models for prompt injection, jailbreaks, data exfiltration, and adversarial exploits.



- **[NeMo Guardrails (`NVIDIA/NeMo-Guardrails`)](https://github.com)**  

  Open-source (`Apache-2.0`) programmable guardrail toolkit for securing LLM-based applications and autonomous agents against malicious inputs and unauthorized tool actions.



### Additional Strong Open-Source Options



- **[Falco (`falcosecurity/falco`)](https://github.com)** for cloud-native runtime security and eBPF-based anomaly detection across Kubernetes clusters, containers, and Linux hosts.

- **[Arkime (`arkime/arkime`)](https://github.com)** and **[Malcolm (`idaholab/Malcolm`)](https://github.com)** for open-source full-packet capture (`PCAP`) indexing, Zeek/Suricata correlation, and network threat-hunting suites.

- **[Purple Llama / CyberSecEval (`meta-llama/PurpleLlama`)](https://github.com)** for open-source cybersecurity benchmark suites and defensive code/prompt security evaluators.

- **[Caldera (`mitre/caldera`)](https://github.com)** and **[Atomic Red Team (`redcanaryco/atomic-red-team`)](https://github.com)** for automated MITRE ATT&CK adversary emulation to validate SOC and AI detection rules.

- **[Ghidra (`NationalSecurityAgency/ghidra`)](https://github.com)** (paired with MCP reverse-engineering bridges like `GhidraMCP`) for AI-assisted binary malware analysis and decompilation.
