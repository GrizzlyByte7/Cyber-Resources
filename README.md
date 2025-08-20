## Table of Contents  
- [Forensics & Imaging](#forensics-imaging)  
- [Hex Editors](#hex-editors)  
- [Malware Analysis](#malware-analysis)  
- [Memory Forensics](#memory-forensics)  
- [OSINT](#osint)  
- [Windows Artifact Analysis](#windows-artifact-analysis)  
- [Attack Simulation & Offense](#attack-simulation--offense)  
  - [Reconnaissance](#reconnaissance-information-gathering)  
  - [Scanning & Enumeration](#scanning--enumeration)  
  - [Vulnerability Assessment](#vulnerability-assessment)  
  - [Exploitation Frameworks](#exploitation-frameworks)  
  - [Password Cracking](#password-cracking)  
  - [Network & IDS Tools](#network--ids-tools)  
- [Logging & SIEM](#logging--siem)  
- [Threat Hunting & Detection Engineering](#threat-hunting--detection-engineering)  
- [Purple-Team Collaboration](#purple-team-collaboration)  
- [DFIR Case Management & Automation](#dfir-case-management--automation)  
- [Cloud Security & CSPM](#cloud-security--cspm)  
- [Endpoint Telemetry & EDR](#endpoint-telemetry--edr)  
- [Configuration Management & Automation](#configuration-management--automation)  
- [Deployment & Self-Hosting](#deployment-self-hosting)  

---

<!-- Forensics & Imaging -->  
<a name="forensics-imaging"></a>  
# Forensics & Imaging  
**Purpose:** Disk and memory acquisition, file carving, artifact parsing, and image analysis.

<details>  
<summary>Tools & Frameworks</summary>

- **Aorimn/Dislocker**  
  Access BitLocker-encrypted volumes by mounting or decrypting them.  
  [Aorimn/dislocker](https://github.com/Aorimn/dislocker)

- **Autopsy**  
  Graphical interface for The Sleuth Kit, full case management.  
  [Autopsy](https://www.autopsy.com/)

- **BulkExtractor**  
  Extract emails, URLs, credit-card numbers from disk images without mounting.  
  [bulk_extractor](https://github.com/simsong/bulk_extractor)

- **CAINE**  
  Linux live distro preconfigured with forensic tools.  
  [CAINE Live USB/DVD](https://www.caine-live.net/)

- **Deftlinux**  
  Live forensic distro focusing on incident response.  
  [Deftlinux](http://www.deftlinux.net/)

- **Extundelete**  
  Recover deleted files from ext3/ext4 filesystems.  
  [extundelete](http://extundelete.sourceforge.net/)

- **EnCase**  
  Comprehensive forensic platform for acquisition, analysis, evidence management.  
  [EnCase](https://www.opentext.com/products-and-solutions/products/software/encase-platform)

- **Exterro**  
  Forensics & e-discovery suite for collection, analysis, compliance.  
  [Exterro](https://accessdata.com/product-download)

- **Foremost**  
  Recover files based on headers/footers.  
  [Foremost](https://foremost.sourceforge.net/)

- **Guymager**  
  Fast, free forensic imager for media acquisition.  
  [Guymager](https://guymager.sourceforge.io/)

- **Magnet AXIOM**  
  Acquire & analyze forensic data from multiple sources.  
  [Magnet AXIOM](https://www.magnetforensics.com/products/magnet-axiom/)

- **MITRE D3FEND**  
  Countermeasure knowledge base linking security concepts.  
  [MITRE D3FEND](https://d3fend.mitre.org/)

- **NSRLLookup**  
  Check file hashes against NSRL to filter benign files.  
  [nsrllookup](https://github.com/rjhansen/nsrllookup)

- **PhotoRec**  
  Recover lost files (videos, docs, archives) from disks, CDs.  
  [PhotoRec](https://www.cgsecurity.org/wiki/PhotoRec_Data_Carving)

- **Scalpel**  
  Fork of Foremost with improved performance and indexing.  
  [Scalpel](https://github.com/sleuthkit/scalpel)

- **SIFT Workstation**  
  SANS VM preconfigured with forensic & IR tools.  
  [SIFT Workstation](https://digital-forensics.sans.org/community/downloads)

- **The Sleuth Kit (TSK)**  
  CLI tools & C library for disk image analysis and file recovery.  
  [The Sleuth Kit](https://www.sleuthkit.org/)

- **WinHex**  
  Hex & disk editor used for forensics & low-level operations.  
  [WinHex](https://www.x-ways.net/winhex/)

- **X-Ways Forensics**  
  Advanced environment for disk cloning & imaging.  
  [X-Ways Forensics](https://www.x-ways.net/forensics/)

- **Xplico**  
  Reconstruct emails, web pages, VoIP from packet captures.  
  [Xplico](http://www.xplico.org/)

</details>  

---

<!-- Hex Editors -->  
<a name="hex-editors"></a>  
# Hex Editors  
**Purpose:** Binary and disk editing at the byte level.

<details>  
<summary>List of Hex Editors</summary>

- **010 Editor**  
  Pro hex editor with Binary Templates for structured parsing.  
  [010 Editor](https://www.sweetscape.com/010editor/)

- **HexEd.it**  
  Browser-based online/offline hex editor.  
  [HexEd.it](https://hexed.it/)

- **Hex Fiend**  
  Fast macOS hex editor for large files.  
  [Hex Fiend](https://hexfiend.com/)

- **HxD**  
  Free, fast Windows hex & disk editor handling huge files.  
  [HxD](https://mh-nexus.de/en/hxd/)

</details>  

---

<!-- Malware Analysis -->  
<a name="malware-analysis"></a>  
# Malware Analysis  
**Purpose:** Disassembly, sandboxing, and metadata extraction.

<details>  
<summary>Core Tools</summary>

- **Any.Run**  
  Interactive online malware sandbox.  
  [ANY.RUN](https://any.run/)

- **Bazaar**  
  Repository of malware samples with hashes & metadata.  
  [Bazaar](https://bazaar.abuse.ch/browse/)

- **CAPA**  
  Automated capability matcher from FLARE to identify techniques.  
  [capa Explorer](https://mandiant.github.io/capa/explorer/)

- **Cutter**  
  GUI for Radare2 in Qt/C++.  
  [Cutter](https://cutter.re/)

- **DC3-MWCP**  
  Config extractor from DoD Cyber Crime Center.  
  [DC3-MWCP](https://github.com/dod-cyber-crime-center/DC3-MWCP)

- **FLARE-VM**  
  Windows VM preloaded with reverse-engineering tools.  
  [FLARE-VM](https://github.com/mandiant/flare-vm)

- **Ghidra**  
  NSA-developed software reverse engineering suite.  
  [Ghidra](https://ghidra-sre.org/)

- **Hybrid Analysis**  
  Free malware analysis powered by Falcon Sandbox.  
  [Hybrid Analysis](https://www.hybrid-analysis.com/)

- **IDA Free**  
  Disassembler & debugger for binary analysis.  
  [IDA Free](https://hex-rays.com/ida-free)

- **Intezer Analyze**  
  Code-reuse detection via binary similarity.  
  [Intezer Analyze](https://analyze.intezer.com/)

- **Malpedia**  
  Malware identification & context database.  
  [Malpedia](https://malpedia.caad.fkie.fraunhofer.de/)

- **MalShare**  
  Community malware sample repository.  
  [MalShare](https://malshare.com/)

- **Malware Archaeology Cheat-Sheets**  
  Summaries of logging & detection strategies.  
  [Cheat-Sheets](https://www.malwarearchaeology.com/cheat-sheets)

- **Malware-Traffic-Analysis.net**  
  Free PCAPs & network traffic tutorials.  
  [malware-traffic-analysis.net](https://malware-traffic-analysis.net/)

- **MetaDefender Cloud OPSWAT**  
  Multi-engine file/URL/hash scanning.  
  [MetaDefender](https://metadefender.com/)

- **Radare2**  
  Open-source reverse engineering framework.  
  [Radare2](https://github.com/radareorg/radare2)

- **REMnux**  
  Linux distro for malware analysis.  
  [REMnux](https://remnux.org/)

- **VirusTotal**  
  Multi-AV file/URL/hash scanning.  
  [VirusTotal](https://www.virustotal.com/)

</details>  

---

<!-- Memory Forensics -->  
<a name="memory-forensics"></a>  
# Memory Forensics  
**Purpose:** Acquire & analyze volatile memory images.

<details>  
<summary>Memory Tools</summary>

- **FireEye Freeware Apps**  
  Tools like Redline for memory & host analysis.  
  [FireEye Freeware Apps](https://fireeye.market/apps?types=freeware_apps)

- **LiME**  
  Linux memory extractor.  
  [LiME](https://github.com/504ensicsLabs/LiME)

- **Rekall**  
  Fast, modular memory analysis framework.  
  [Rekall](https://github.com/google/rekall)

- **Volatility**  
  Advanced memory forensics.  
  [Volatility](https://www.volatilityfoundation.org/)

- **VolDiff**  
  Compare memory images to find anomalies.  
  [VolDiff](https://github.com/aim4r/VolDiff)

</details>  

---

<!-- OSINT -->  
<a name="osint"></a>  
# OSINT  
**Purpose:** Open-source intelligence gathering & link analysis.

<details>  
<summary>OSINT Frameworks & Tools</summary>

- **IntelTechniques Search Tool**  
  Automated public data collection suite.  
  [IntelTechniques](https://inteltechniques.com/tools/Business.html)

- **Maltego**  
  Interactive graph-based data mining.  
  [Maltego](https://www.maltego.com/)

- **OSINT Framework**  
  Curated directory of OSINT links.  
  [OSINT Framework](https://osintframework.com/)

- **Recon-ng**  
  Python web recon framework.  
  [Recon-ng](https://github.com/lanmaster53/recon-ng)

- **ReconSpider**  
  Social media, DNS, subdomain recon.  
  [ReconSpider](https://github.com/bhavsec/reconspider)

- **Sherlock**  
  Username enumeration across sites.  
  [Sherlock](https://github.com/sherlock-project/sherlock)

- **Shodan**  
  Search engine for Internet-connected devices.  
  [Shodan](https://www.shodan.io/)

- **SpiderFoot**  
  Automated surface-attacks intelligence.  
  [SpiderFoot](https://www.spiderfoot.net/)

- **theHarvester**  
  Domain, email, and username collector.  
  [theHarvester](https://github.com/laramies/theHarvester)

</details>  

---

<!-- Windows Artifact Analysis -->  
<a name="windows-artifact-analysis"></a>  
# Windows Artifact Analysis  
**Purpose:** Extract & parse Windows-specific forensic artifacts.

<details>  
<summary>Windows Artifact Tools</summary>

- **KAPE**  
  Collect & process forensic artifacts for triage.  
  [KAPE](https://www.kroll.com/en/services/cyber-risk/incident-response-litigation-support/kape)

- **Log2Timeline (Plaso)**  
  Super-timeline creation from multiple sources.  
  [Plaso](https://plaso.readthedocs.io/en/latest/)

- **PECmd**  
  Parse Windows Prefetch files.  
  [Eric Zimmerman’s MDb](https://ericzimmerman.github.io/)

- **Registry Explorer**  
  Interactive Registry viewer & parser.  
  [Eric Zimmerman’s MDb](https://ericzimmerman.github.io/)

- **RegRipper 3.0**  
  Registry parsing & reporting framework.  
  [RegRipper 3.0](https://github.com/keydet89/RegRipper3.0)

</details>  

---

<!-- Attack Simulation & Offense -->  
<a name="attack-simulation--offense"></a>  
# Attack Simulation & Offense  
**Purpose:** Recon, scanning, exploitation, and red-team training platforms.

<!-- Reconnaissance -->  
<a name="reconnaissance-information-gathering"></a>  
## Reconnaissance (Information Gathering)

<details>  
<summary>Reconnaissance Tools</summary>

- **Amass**  
  DNS enumeration & OSINT.  
  [OWASP Amass](https://owasp.org/www-project-amass/)

- **Aquatone**  
  Visual domain reconnaissance.  
  [Aquatone](https://github.com/michenriksen/aquatone)

- **Assetfinder**  
  Subdomain discovery.  
  [Assetfinder](https://github.com/tomnomnom/assetfinder)

- **crt.sh**  
  Certificate transparency log lookup.  
  [crt.sh](https://crt.sh/)

- **CloudSploit**  
  AWS misconfiguration scanner.  
  [CloudSploit](https://github.com/aquasecurity/cloudsploit)

- **Fierce**  
  DNS & directory brute-forcing.  
  [Fierce](https://github.com/mschwager/fierce)

- **Maltego**  
  Link-analysis graphing.  
  [Maltego](https://www.maltego.com/)

- **Shodan**  
  Device & service discovery.  
  [Shodan](https://www.shodan.io/)

- **SpiderFoot**  
  Automated threat surface scanning.  
  [SpiderFoot](https://www.spiderfoot.net/)

- **theHarvester**  
  Email & domain harvesting.  
  [theHarvester](https://github.com/laramies/theHarvester)

- **WhereToGo**  
  Curated list of popular corporate services to test for compromised-account pivot points.  
  [valeriyshevchenko90/WhereToGo](https://github.com/valeriyshevchenko90/WhereToGo)

</details>  

<!-- Scanning & Enumeration -->  
<a name="scanning--enumeration"></a>  
## Scanning & Enumeration

<details>  
<summary>Port & Service Scanners</summary>

- **enum4linux-ng**  
  SMB/NetBIOS enumeration on Linux.  
  [enum4linux-ng](https://github.com/cddmp/enum4linux-ng)

- **LDAPDomainDump**  
  Dump Active Directory via LDAP.  
  [LDAPDomainDump](https://github.com/dirkjanm/ldapdomaindump)

- **Masscan**  
  Internet-wide SYN scanner.  
  [Masscan](https://github.com/robertdavidgraham/masscan)

- **Netdiscover**  
  Passive ARP-based host discovery.  
  [Netdiscover](https://github.com/alexxy/netdiscover)

- **Nmap**  
  Host discovery & port scanning.  
  [Nmap](https://nmap.org/)

- **RustScan**  
  Fast port scanning with Nmap integration.  
  [RustScan](https://github.com/RustScan/RustScan)

</details>  

<!-- Vulnerability Assessment -->  
<a name="vulnerability-assessment"></a>  
## Vulnerability Assessment

<details>  
<summary>Vulnerability Scanners</summary>

- **CloudSploit**  
  AWS config scanning.  
  [CloudSploit](https://github.com/aquasecurity/cloudsploit)

- **Nuclei**  
  Fast templated vulnerability scanner.  
  [Nuclei](https://nuclei.projectdiscovery.io/)

- **Sn1per**  
  Automated pentest scanner.  
  [Sn1per](https://github.com/1N3/Sn1per)

</details>  

<!-- Exploitation Frameworks -->  
<a name="exploitation-frameworks"></a>  
## Exploitation Frameworks

<details>  
<summary>Penetration Test Suites</summary>

- **Cobalt Strike**  
  Commercial red-team & adversary simulation tool.  
  [Cobalt Strike](https://www.cobaltstrike.com/)

- **Impacket**  
  Python network protocols for pentesting.  
  [Impacket](https://github.com/SecureAuthCorp/impacket)

- **Metasploit**  
  Exploit development & execution framework.  
  [Metasploit](https://www.metasploit.com/)

</details>  

<!-- Password Cracking -->  
<a name="password-cracking"></a>  
## Password Cracking

<details>  
<summary>Cracking & Hash Tools</summary>

- **CredMaster**  
  AWS-based password spraying tool with dynamic proxy rotation (FireProx) to evade throttling.  
  [knavesec/CredMaster](https://github.com/knavesec/CredMaster)

- **Hashcat**  
  GPU-accelerated password cracker.  
  [Hashcat](https://hashcat.net/hashcat/)

- **John the Ripper**  
  Fast CPU-based password cracker.  
  [John the Ripper](https://www.openwall.com/john/)

- **Medusa**  
  Parallel login brute-forcer.  
  [Medusa](https://github.com/jmk-foofus/medusa)

</details>  

<!-- Network & IDS Tools -->  
<a name="network--ids-tools"></a>  
## Network & IDS Tools

<details>  
<summary>Network Detection & Simulation</summary>

- **Metron**  
  Open-source network security analytics platform (Kafka + Storm + HBase).  
  [apache/metron](https://github.com/apache/metron)

- **Snort**  
  High-performance network IDS/IPS, also used in red-team labs.  
  [SnortOrg/snort3](https://github.com/SnortOrg/snort3)

- **Suricata**  
  Next-generation network IDS/IPS and network security monitoring.  
  [OISF/suricata](https://github.com/OISF/suricata)

</details>  

---

<!-- Logging & SIEM -->  
<a name="logging--siem"></a>  
# Logging & SIEM  
**Purpose:** Centralized log analysis, intrusion detection, and alerting.

<details>  
<summary>Open-Source SIEM & IDS</summary>

- **Elasticsearch**  
  Distributed search & analytics engine, core of the ELK stack.  
  [elastic/elasticsearch](https://github.com/elastic/elasticsearch)

- **Falco**  
  Cloud-native runtime security engine for intrusion & anomaly detection.  
  [falcosecurity/falco](https://github.com/falcosecurity/falco)

- **Grafana**  
  Visualization & dashboarding for metrics & logs.  
  [grafana/grafana](https://github.com/grafana/grafana)

- **Graylog**  
  Log management platform built on Elasticsearch, MongoDB, and Kafka.  
  [Graylog2/graylog2-server](https://github.com/Graylog2/graylog2-server)

- **Logstash**  
  Pipeline for ingesting, transforming, and shipping logs.  
  [elastic/logstash](https://github.com/elastic/logstash)

- **Loki**  
  Multi-tenant log aggregation system inspired by Prometheus.  
  [grafana/loki](https://github.com/grafana/loki)

- **Prometheus**  
  Metrics-focused time-series database with PromQL.  
  [prometheus/prometheus](https://github.com/prometheus/prometheus)

- **Security Onion**  
  All-in-one distro for IDS (Zeek, Suricata), log management, and more.  
  [Security-Onion-Solutions/security-onion](https://github.com/Security-Onion-Solutions/security-onion)

- **Zeek**  
  Powerful network traffic analysis framework.  
  [zeek/zeek](https://github.com/zeek/zeek)

</details>  

---

<!-- Threat Hunting & Detection Engineering -->  
<a name="threat-hunting--detection-engineering"></a>  
# Threat Hunting & Detection Engineering  
**Purpose:** Hunt for anomalies, author detection rules, automate alerting.

<details>  
<summary>Hunting Frameworks & Rule Engines</summary>

- **BLTools**  
  Collection of blue-team utilities for log parsing, threat hunting, and incident-response automation.  
  [KingYawnus/BLTools](https://github.com/KingYawnus/BLTools)

- **ElastAlert**  
  Alerting on Elasticsearch query results, pipeline detections.  
  [Yelp/elastalert](https://github.com/Yelp/elastalert)

- **Merlin**  
  In-memory command and control detection framework.  
  [Ne0nd0g/merlin](https://github.com/Ne0nd0g/merlin)

- **OpenSOC**  
  Automated streaming analytics for large-scale hunting.  
  [OpenSOC](https://github.com/OpenSOC/OpenSOC)

- **Sigma**  
  Generic YAML-based detection rule format, convert to any SIEM.  
  [SigmaHQ/sigma](https://github.com/SigmaHQ/sigma)

- **Wazuh Ruleset**  
  Open-source HIDS with built-in rules for Windows/Linux logs.  
  [wazuh/wazuh](https://github.com/wazuh/wazuh)

</details>  

---

<!-- Purple-Team Collaboration -->  
<a name="purple-team-collaboration"></a>  
# Purple-Team Collaboration  
**Purpose:** Share detections, adversary emulations, exercises.

<details>  
<summary>Purple Team Tooling</summary>

- **AttackIQ**  
  Commercial breach-and-attack emulation with reporting.  
  [AttackIQ](https://www.attackiq.com/)

- **Atomic Red Team**  
  Library of small, scriptable tests mapped to MITRE ATT&CK.  
  [RedCanaryLabs/atomic-red-team](https://github.com/redcanarylabs/atomic-red-team)

- **Caldera**  
  Automated adversary emulation platform by MITRE.  
  [mitre/caldera](https://github.com/mitre/caldera)

- **PurpleSharp**  
  .NET red-blue operations framework for Windows environments.  
  [flanglet/PurpleSharp](https://github.com/flanglet/PurpleSharp)

</details>  

---

<!-- DFIR Case Management & Automation -->  
<a name="dfir-case-management--automation"></a>  
# DFIR Case Management & Automation  
**Purpose:** Track investigations, share IOCs, automate repetitive tasks.

<details>  
<summary>Case & IOC Platforms</summary>

- **AutoIR**  
  Playbook-driven automation for containment & evidence collection.  
  [AutoIR](https://github.com/COOLSec/AutoIR)

- **Cortex**  
  TheHive’s analysis engine for tasks (VirusTotal, MISP lookups, etc.).  
  [TheHive-Project/Cortex](https://github.com/TheHive-Project/Cortex)

- **MISP**  
  Threat-sharing platform for IOCs, campaigns, sightings.  
  [MISP/MISP](https://github.com/MISP/MISP)

- **TheHive**  
  Scalable, open-source incident response platform.  
  [TheHive-Project/TheHive](https://github.com/TheHive-Project/TheHive)

- **Timesketch**  
  Collaborative forensic timeline analysis.  
  [google/timesketch](https://github.com/google/timesketch)

</details>  

---

<!-- Cloud Security & CSPM -->  
<a name="cloud-security--cspm"></a>  
# Cloud Security & CSPM  
**Purpose:** Discover misconfigs, monitor cloud activity, enforce posture.

<details>  
<summary>Cloud Detection & Posture Tools</summary>

- **Cartography**  
  Graph-based inventory of cloud assets & relationships.  
  [lyft/cartography](https://github.com/lyft/cartography)

- **Cloud Custodian**  
  Rule engine to remediate cloud resources.  
  [cloud-custodian/cloud-custodian](https://github.com/cloud-custodian/cloud-custodian)

- **KICS**  
  Infrastructure-as-code scanning for security issues.  
  [Checkmarx/kics](https://github.com/Checkmarx/kics)

- **Prowler**  
  AWS CIS-benchmark checks & threat detections.  
  [toniblyx/prowler](https://github.com/toniblyx/prowler)

- **ScoutSuite**  
  Multi-cloud security auditor for AWS, GCP, Azure.  
  [nccgroup/ScoutSuite](https://github.com/nccgroup/ScoutSuite)

</details>  

---

<!-- Endpoint Telemetry & EDR -->  
<a name="endpoint-telemetry--edr"></a>  
# Endpoint Telemetry & EDR  
**Purpose:** Collect detailed host data, hunt across endpoints.

<details>  
<summary>EDR & Telemetry Tools</summary>

- **FleetDM**  
  osquery fleet management, query scheduling & reporting.  
  [fleetdm/fleet](https://github.com/fleetdm/fleet)

- **GRR Rapid Response**  
  Enterprise-scale remote live forensics & triage.  
  [google/grr](https://github.com/google/grr)

- **Osquery**  
  SQL interface for live endpoint state and drift detection.  
  [osquery/osquery](https://github.com/osquery/osquery)

- **OSSEC**  
  Host-based intrusion detection system (HIDS) for log analysis & file integrity.  
  [ossec/ossec-hids](https://github.com/ossec/ossec-hids)

- **Security Onion**  
  Bundles host sensors (Wazuh/OSSEC agents) plus network IDS.  
  [Security-Onion-Solutions/security-onion](https://github.com/Security-Onion-Solutions/security-onion)

- **Sysmon**  
  Windows system monitor for detailed process & network logs.  
  [SwiftOnSecurity/sysmon-config](https://github.com/SwiftOnSecurity/sysmon-config)

- **Velociraptor**  
  Endpoint monitoring & collection, custom hunts via VQL.  
  [Velocidex/velociraptor](https://github.com/Velocidex/velociraptor)

</details>  

---

<!-- Configuration Management & Automation -->  
<a name="configuration-management--automation"></a>  
# Configuration Management & Automation  
**Purpose:** Infrastructure-as-code and orchestration for security deployments.

<details>  
<summary>Infra-as-Code & Orchestration</summary>

- **Ansible**  
  Agentless automation & orchestration.  
  [ansible/ansible](https://github.com/ansible/ansible)

- **Pulumi**  
  Code-based infra-as-code using familiar programming languages.  
  [pulumi/pulumi](https://github.com/pulumi/pulumi)

- **Terraform**  
  Infrastructure as code across cloud & on-prem.  
  [hashicorp/terraform](https://github.com/hashicorp/terraform)

</details>  

---

<!-- Deployment & Self-Hosting -->  
<a name="deployment-self-hosting"></a>  
# Deployment & Self-Hosting  
**Purpose:** Guides and best practices for self-hosting security tools and related services.

<details>  
<summary>Guides & Repositories</summary>

- **Self-Hosting-Guide**  
  Comprehensive community-curated guide to self-host popular web applications and services, including security platforms.  
  [mikeroyal/Self-Hosting-Guide](https://github.com/mikeroyal/Self-Hosting-Guide)

</details>

