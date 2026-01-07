# $\color{orange}{\text{Forensic and Cyber Toolset Master List}}$

*This is a working list. I add to it as I find new tools and resources.* <br/>

## $\color{orange}{\text{Table of Contents}}$
- [Forensics and Imaging](#forensics-imaging)  
- [Hex Editors](#hex-editors)  
- [Malware Analysis](#malware-analysis)  
- [Memory Forensics](#memory-forensics)  
- [OSINT](#osint)  
- [Windows Artifact Analysis](#windows-artifact-analysis)  
- [Attack Simulation and Offense](#attack-simulation-offense)  
  - [Reconnaissance](#reconnaissance-information-gathering)  
  - [Scanning and Enumeration](#scanning-enumeration)  
  - [Vulnerability Assessment](#vulnerability-assessment)  
  - [Exploitation Frameworks](#exploitation-frameworks)  
  - [Password Cracking](#password-cracking)  
  - [Network and IDS Tools](#network-ids-tools)  
- [Logging and SIEM](#logging-siem)  
- [Threat Hunting and Detection Engineering](#threat-hunting-detection-engineering)  
- [Purple-Team Collaboration](#purple-team-collaboration)  
- [DFIR Case Management and Automation](#dfir-case-management-automation)  
- [SOC Analyst Platforms](#soc-analyst-platforms)
- [Cloud Security and CSPM](#cloud-security-cspm)  
- [Endpoint Telemetry and EDR](#endpoint-telemetry-edr)  
- [Configuration Management and Automation](#configuration-management-automation)  
- [Deployment and Self-Hosting](#deployment-self-hosting)  

---

<a name="forensics-imaging"></a>  
# $\color{orange}{\text{Forensics and Imaging}}$
**Purpose:** Disk and memory acquisition, file carving, artifact parsing, and image analysis.

<details>  
<summary>Tools and Frameworks</summary>

- **SUMURI PALADIN**
  A bootable Linux-based forensic suite designed for forensically sound imaging, triage, and data recovery through a simplified GUI toolbox.
  [SUMURI PALADIN](https://sumuri.com/software/paladin/)

- **Cyber Triage**
  An automated incident response tool that simplifies endpoint data collection and analyzes artifacts for fast intrusion triage and timeline building.
  [Cyber Triage](https://www.cybertriage.com/)

- **UAC (Unix-like Artifact Collector)**
  A Live Response collection tool for Linux, macOS, and BSD systems that automates the collection of forensic artifacts similar to KAPE for Windows.
  [UAC on GitHub](https://github.com/tclahr/uac)

- **Aorimn/Dislocker** Access BitLocker-encrypted volumes by mounting or decrypting them.  
  [Aorimn/dislocker](https://github.com/Aorimn/dislocker)

- **Autopsy** Graphical interface for The Sleuth Kit, full case management.  
  [Autopsy](https://www.autopsy.com/)

- **BulkExtractor** Extract emails, URLs, credit-card numbers from disk images without mounting.  
  [bulk_extractor](https://github.com/simsong/bulk_extractor)

- **CAINE** Linux live distro preconfigured with forensic tools.  
  [CAINE Live USB/DVD](https://www.caine-live.net/)

- **Deftlinux** Live forensic distro focusing on incident response.  
  [Deftlinux](http://www.deftlinux.net/)

- **Extundelete** Recover deleted files from ext3/ext4 filesystems.  
  [extundelete](http://extundelete.sourceforge.net/)

- **EnCase** Comprehensive forensic platform for acquisition, analysis, evidence management.  
  [EnCase](https://www.opentext.com/products-and-solutions/products/software/encase-platform)

- **Exterro** Forensics and e-discovery suite for collection, analysis, compliance.  
  [Exterro](https://accessdata.com/product-download)

- **FileInfo — File Types Reference** Extensive, searchable database of file extensions and type descriptions — handy for carving and triage.  
  [FileInfo: File Types](https://fileinfo.com/filetypes/)

- **Foremost** Recover files based on headers/footers.  
  [Foremost](https://foremost.sourceforge.net/)

- **Guymager** Fast, free forensic imager for media acquisition.  
  [Guymager](https://guymager.sourceforge.io/)

- **Magnet AXIOM** Acquire and analyze forensic data from multiple sources.  
  [Magnet AXIOM](https://www.magnetforensics.com/products/magnet-axiom/)

- **MITRE D3FEND** Countermeasure knowledge base linking security concepts.  
  [MITRE D3FEND](https://d3fend.mitre.org/)

- **NSRLLookup** Check file hashes against NSRL to filter benign files.  
  [nsrllookup](https://github.com/rjhansen/nsrllookup)

- **PhotoRec** Recover lost files (videos, docs, archives) from disks, CDs.  
  [PhotoRec](https://www.cgsecurity.org/wiki/PhotoRec_Data_Carving)

- **Scalpel** Fork of Foremost with improved performance and indexing.  
  [Scalpel](https://github.com/sleuthkit/scalpel)

- **SIFT Workstation** SANS VM preconfigured with forensic and IR tools.  
  [SIFT Workstation](https://digital-forensics.sans.org/community/downloads)

- **The Sleuth Kit (TSK)** CLI tools and C library for disk image analysis and file recovery.  
  [The Sleuth Kit](https://www.sleuthkit.org/)

- **WinHex** Hex and disk editor used for forensics and low-level operations.  
  [WinHex](https://www.x-ways.net/winhex/)

- **X-Ways Forensics** Advanced environment for disk cloning and imaging.  
  [X-Ways Forensics](https://www.x-ways.net/forensics/)

- **Xplico** Reconstruct emails, web pages, VoIP from packet captures.  
  [Xplico](http://www.xplico.org/)

</details>  

---

<a name="hex-editors"></a>  
# $\color{orange}{\text{Hex Editors}}$
**Purpose:** Binary and disk editing at the byte level.

<details>  
<summary>List of Hex Editors</summary>

- **010 Editor** Pro hex editor with Binary Templates for structured parsing.  
  [010 Editor](https://www.sweetscape.com/010editor/)

- **HexEd.it** Browser-based online/offline hex editor.  
  [HexEd.it](https://hexed.it/)

- **Hex Fiend** Fast macOS hex editor for large files.  
  [Hex Fiend](https://hexfiend.com/)

- **HxD** Free, fast Windows hex and disk editor handling huge files.  
  [HxD](https://mh-nexus.de/en/hxd/)

</details>  

---

<a name="malware-analysis"></a>  
# $\color{orange}{\text{Malware Analysis}}$
**Purpose:** Disassembly, sandboxing, and metadata extraction.

<details>  
<summary>Core Tools</summary>

- **Malpedia**
  A comprehensive resource for malware identification that provides curated intelligence and code sharing across hundreds of malware families.
  [Malpedia](https://malpedia.caad.fkie.fraunhofer.de/)

- **Any.Run** Interactive online malware sandbox.  
  [ANY.RUN](https://any.run/)

- **Bazaar** Repository of malware samples with hashes and metadata.  
  [Bazaar](https://bazaar.abuse.ch/browse/)

- **CAPA** Automated capability matcher from FLARE to identify techniques.  
  [capa Explorer](https://mandiant.github.io/capa/explorer/)

- **Cutter** GUI for Radare2 in Qt/C++.  
  [Cutter](https://cutter.re/)

- **DC3-MWCP** Config extractor from DoD Cyber Crime Center.  
  [DC3-MWCP](https://github.com/dod-cyber-crime-center/DC3-MWCP)

- **FLARE-VM** Windows VM preloaded with reverse-engineering tools.  
  [FLARE-VM](https://github.com/mandiant/flare-vm)

- **Ghidra** NSA-developed software reverse engineering suite.  
  [Ghidra](https://ghidra-sre.org/)

- **Hybrid Analysis** Free malware analysis powered by Falcon Sandbox.  
  [Hybrid Analysis](https://www.hybrid-analysis.com/)

- **IDA Free** Disassembler and debugger for binary analysis.  
  [IDA Free](https://hex-rays.com/ida-free)

- **Intezer Analyze** Code-reuse detection via binary similarity.  
  [Intezer Analyze](https://analyze.intezer.com/)

- **MalShare** Community malware sample repository.  
  [MalShare](https://malshare.com/)

- **Malware Archaeology Cheat-Sheets** Summaries of logging and detection strategies.  
  [Cheat-Sheets](https://www.malwarearchaeology.com/cheat-sheets)

- **Malware-Traffic-Analysis.net** Free PCAPs and network traffic tutorials.  
  [malware-traffic-analysis.net](https://malware-traffic-analysis.net/)

- **MetaDefender Cloud OPSWAT** Multi-engine file/URL/hash scanning.  
  [MetaDefender](https://metadefender.com/)

- **Radare2** Open-source reverse engineering framework.  
  [Radare2](https://github.com/radareorg/radare2)

- **REMnux** Linux distro for malware analysis.  
  [REMnux](https://remnux.org/)

- **VirusTotal** Multi-AV file/URL/hash scanning.  
  [VirusTotal](https://www.virustotal.com/)

</details>  

---

<a name="memory-forensics"></a>  
# $\color{orange}{\text{Memory Forensics}}$
**Purpose:** Acquire and analyze volatile memory images.

<details>  
<summary>Memory Tools</summary>

- **FireEye Freeware Apps** Tools like Redline for memory and host analysis.  
  [FireEye Freeware Apps](https://fireeye.market/apps?types=freeware_apps)

- **LiME** Linux memory extractor.  
  [LiME](https://github.com/504ensicsLabs/LiME)

- **Rekall** Modular memory analysis framework (unmaintained, use with caution).  
  [Rekall](https://github.com/google/rekall)

- **Volatility** Advanced memory forensics framework.  
  [Volatility](https://www.volatilityfoundation.org/)

- **VolDiff** Compare memory images to find anomalies.  
  [VolDiff](https://github.com/aim4r/VolDiff)

</details>  

---

<a name="osint"></a>  
# $\color{orange}{\text{OSINT}}$
**Purpose:** Open-source intelligence gathering and link analysis.

<details>  
<summary>OSINT Frameworks and Tools</summary>

- **ShadowDragon**
  A comprehensive OSINT platform focused on real-time data collection, link analysis, and investigative monitoring.
  [ShadowDragon](https://shadowdragon.io/)

- **Babel X**
  An AI-powered OSINT platform that analyzes social media, blogs, and the dark web in over 200 languages.
  [Babel Street Babel X](https://www.babelstreet.com/babel-x)

- **DarkSearch.io**
  A search engine for collecting dark web intelligence from data dumps and forums.
  [DarkSearch](https://darksearch.io/)

- **FOCA**
  Gather hidden metadata from publicly available documents to uncover internal network paths.
  [FOCA on GitHub](https://github.com/ElevenPaths/FOCA)

- **Censys**
  Search engine for Internet-connected devices that provides visibility into a target's attack surface.
  [Censys](https://censys.io/)

- **IntelTechniques Search Tool** Automated public data collection suite.  
  [IntelTechniques](https://inteltechniques.com/tools/Business.html)

- **Maltego** Interactive graph-based data mining.  
  [Maltego](https://www.maltego.com/)

- **OSINT Framework** Curated directory of OSINT links.  
  [OSINT Framework](https://osintframework.com/)

- **Recon-ng** Python web recon framework.  
  [Recon-ng](https://github.com/lanmaster53/recon-ng)

- **ReconSpider** Social media, DNS, and subdomain recon.  
  [ReconSpider](https://github.com/bhavsec/reconspider)

- **Sherlock** Username enumeration across sites.  
  [Sherlock](https://github.com/sherlock-project/sherlock)

- **Shodan** Search engine for Internet-connected devices.  
  [Shodan](https://www.shodan.io/)

- **SpiderFoot** Automated surface-attacks intelligence.  
  [SpiderFoot](https://www.spiderfoot.net/)

- **theHarvester** Domain, email, and username collector.  
  [theHarvester](https://github.com/laramies/theHarvester)

</details>  

---

<a name="windows-artifact-analysis"></a>  
# $\color{orange}{\text{Windows Artifact Analysis}}$
**Purpose:** Extract and parse Windows-specific forensic artifacts.

<details>  
<summary>Windows Artifact Tools</summary>

- **Hayabusa**
  A lightning-fast Windows event log hunter that uses Sigma rules to detect threats and generate high-fidelity timelines.
  [Hayabusa on GitHub](https://github.com/Yamato-Security/hayabusa)

- **Chainsaw**
  A powerful command-line tool designed for rapid searching and hunting through Windows event logs.
  [Chainsaw on GitHub](https://github.com/WithSecureLabs/chainsaw)

- **KAPE** Collect and process forensic artifacts for triage.  
  [KAPE](https://www.kroll.com/en/services/cyber-risk/incident-response-litigation-support/kape)

- **Log2Timeline (Plaso)** Super-timeline creation from multiple sources.  
  [Plaso](https://plaso.readthedocs.io/en/latest/)

- **PECmd** Parse Windows Prefetch files.  
  [Eric Zimmerman’s PECmd](https://ericzimmerman.github.io/)

- **Registry Explorer** Interactive Registry viewer and parser.  
  [Eric Zimmerman’s Registry Explorer](https://ericzimmerman.github.io/)

- **RegRipper 3.0** Registry parsing and reporting framework.  
  [RegRipper 3.0](https://github.com/keydet89/RegRipper3.0)

</details>  

---

<a name="attack-simulation-offense"></a>  
# $\color{orange}{\text{Attack Simulation and Offense}}$
**Purpose:** Recon, scanning, exploitation, and red-team training platforms.

<a name="reconnaissance-information-gathering"></a>  
## $\color{orange}{\text{Reconnaissance (Information Gathering)}}$

<details>  
<summary>Reconnaissance Tools</summary>

- **Amass** DNS enumeration and OSINT.  
  [OWASP Amass](https://owasp.org/www-project-amass/)

- **Aquatone** Visual domain reconnaissance.  
  [Aquatone](https://github.com/michenriksen/aquatone)

- **Assetfinder** Subdomain discovery.  
  [Assetfinder](https://github.com/tomnomnom/assetfinder)

- **crt.sh** Certificate transparency log lookup.  
  [crt.sh](https://crt.sh/)

- **CloudSploit** AWS misconfiguration scanner.  
  [CloudSploit](https://github.com/aquasecurity/cloudsploit)

- **Fierce** DNS and directory brute-forcing.  
  [Fierce](https://github.com/mschwager/fierce)

- **WhereToGo** Curated list of corporate services to test for pivot points.  
  [WhereToGo](https://github.com/valeriyshevchenko90/WhereToGo)

</details>  

<a name="scanning-enumeration"></a>  
## $\color{orange}{\text{Scanning and Enumeration}}$

<details>  
<summary>Port and Service Scanners</summary>

- **enum4linux-ng** SMB/NetBIOS enumeration on Linux.  
  [enum4linux-ng](https://github.com/cddmp/enum4linux-ng)

- **LDAPDomainDump** Dump Active Directory via LDAP.  
  [LDAPDomainDump](https://github.com/dirkjanm/ldapdomaindump)

- **Masscan** Internet-wide SYN scanner.  
  [Masscan](https://github.com/robertdavidgraham/masscan)

- **Nmap** Host discovery and port scanning.  
  [Nmap](https://nmap.org/)

- **RustScan** Fast port scanning with Nmap integration.  
  [RustScan](https://github.com/RustScan/RustScan)

</details>  

<a name="vulnerability-assessment"></a>  
## $\color{orange}{\text{Vulnerability Assessment}}$

<details>  
<summary>Vulnerability Scanners</summary>

- **Nuclei** Fast templated vulnerability scanner.  
  [Nuclei](https://nuclei.projectdiscovery.io/)

- **Sn1per** Automated pentest scanner.  
  [Sn1per](https://github.com/1N3/Sn1per)

</details>  

<a name="exploitation-frameworks"></a>  
## $\color{orange}{\text{Exploitation Frameworks}}$

<details>  
<summary>Penetration Test Suites</summary>

- **Cobalt Strike** Commercial red-team and adversary simulation tool.  
  [Cobalt Strike](https://www.cobaltstrike.com/)

- **Impacket** Python network protocols for pentesting.  
  [Impacket](https://github.com/SecureAuthCorp/impacket)

- **Metasploit** Exploit development and execution framework.  
  [Metasploit](https://www.metasploit.com/)

</details>  

<a name="password-cracking"></a>  
## $\color{orange}{\text{Password Cracking}}$

<details>  
<summary>Cracking and Hash Tools</summary>

- **CredMaster** AWS-based password spraying with proxy rotation.  
  [CredMaster](https://github.com/knavesec/CredMaster)

- **Hashcat** GPU-accelerated password cracker.  
  [Hashcat](https://hashcat.net/hashcat/)

- **John the Ripper** Fast CPU-based password cracker.  
  [John the Ripper](https://www.openwall.com/john/)

</details>  

<a name="network-ids-tools"></a>  
## $\color{orange}{\text{Network and IDS Tools}}$

<details>  
<summary>Network Detection and Simulation</summary>

- **Snort** High-performance network IDS/IPS.  
  [Snort](https://github.com/SnortOrg/snort3)

- **Suricata** Next-generation network IDS/IPS and monitoring.  
  [Suricata](https://github.com/OISF/suricata)

</details>  

---

<a name="logging-siem"></a>  
# $\color{orange}{\text{Logging and SIEM}}$
**Purpose:** Centralized log analysis, intrusion detection, and alerting.

<details>  
<summary>Open-Source SIEM and IDS</summary>

- **Elasticsearch** Distributed search engine, core of the ELK stack.  
  [Elasticsearch](https://github.com/elastic/elasticsearch)

- **Security Onion** All-in-one distro for IDS and log management.  
  [Security Onion](https://github.com/Security-Onion-Solutions/security-onion)

- **Zeek** Powerful network traffic analysis framework.  
  [Zeek](https://github.com/zeek/zeek)

</details>  

---

<a name="threat-hunting-detection-engineering"></a>  
# $\color{orange}{\text{Threat Hunting and Detection Engineering}}$
**Purpose:** Hunt for anomalies, author detection rules, automate alerting.

<details>  
<summary>Hunting Frameworks and Rule Engines</summary>

- **APT-Hunter**
  A tool designed to track advanced persistent threats specifically through the analysis of Windows event logs.
  [APT-Hunter on GitHub](https://github.com/ahmedkhlief/APT-Hunter)

- **OpenCTI**
  An open-source threat intelligence platform designed to centralize and operationalize intelligence.
  [OpenCTI](https://github.com/OpenCTI-Platform/opencti)

- **UniqueSignal**
  A malware-centric threat intelligence feed that delivers high-context indicators.
  [VMRay UniqueSignal](https://www.vmray.com/uniquesignal/)

- **Sigma** Generic YAML-based detection rule format.  
  [SigmaHQ/sigma](https://github.com/SigmaHQ/sigma)

</details>  

---

<a name="purple-team-collaboration"></a>  
# $\color{orange}{\text{Purple Team}}$
**Purpose:** Share detections, adversary emulations, exercises.

<details>  
<summary>Purple Team Tooling</summary>

- **AttackIQ** Commercial breach-and-attack emulation with reporting.  
  [AttackIQ](https://www.attackiq.com/)

- **Atomic Red Team** Library of small, scriptable tests mapped to MITRE ATT&CK.  
  [RedCanaryLabs/atomic-red-team](https://github.com/redcanarylabs/atomic-red-team)

- **Caldera** Automated adversary emulation platform by MITRE.  
  [mitre/caldera](https://github.com/mitre/caldera)

- **PurpleSharp** .NET red-blue operations framework for Windows environments.  
  [flanglet/PurpleSharp](https://github.com/flanglet/PurpleSharp)

</details>  

---

<a name="dfir-case-management-automation"></a>  
# $\color{orange}{\text{DFIR Case Management and Automation}}$
**Purpose:** Track investigations, share IOCs, automate repetitive tasks.

<details>  
<summary>Case and IOC Platforms</summary>

- **TheHive** Scalable, open-source incident response platform.  
  [TheHive Project](https://thehive-project.org/)

- **Iris** Collaborative IR platform for technical data and timelines.  
  [Iris on GitHub](https://github.com/dfir-iris/iris-web)

- **MISP** Threat-sharing platform for IOCs and campaigns.  
  [MISP](https://github.com/MISP/MISP)

</details>  

---

<a name="soc-analyst-platforms"></a>
# $\color{orange}{\text{SOC Analyst Platforms}}$
**Purpose:** AI-driven triage and autonomous investigation.

<details>  
<summary>Automation and Triage Tools</summary>

- **Prophet AI**
  An AI SOC platform that autonomously triages and responds to alerts with cited evidence.
  [Prophet Security](https://www.prophetsecurity.ai/)

- **Swimlane Turbine**
  A low-code automation studio that uses AI to design SOC workflows.
  [Swimlane Turbine](https://swimlane.com/platform/turbine/)

</details>

---

<a name="cloud-security-cspm"></a>  
# $\color{orange}{\text{Cloud Security and CSPM}}$
**Purpose:** Discover misconfigs, monitor cloud activity, and enforce posture.

<details>  
<summary>Cloud Detection and Posture Tools</summary>

- **Prowler** AWS CIS-benchmark checks and threat detections.  
  [Prowler on GitHub](https://github.com/prowler-cloud/prowler)

- **ScoutSuite** Multi-cloud security auditor for AWS, GCP, Azure.  
  [ScoutSuite](https://github.com/nccgroup/ScoutSuite)

</details>

---

<a name="endpoint-telemetry-edr"></a>  
# $\color{orange}{\text{Endpoint Telemetry and EDR}}$
**Purpose:** Collect detailed host data, hunt across endpoints.

<details>  
<summary>EDR and Telemetry Tools</summary>

- **Velociraptor** Endpoint monitoring and hunting platform via VQL.  
  [Velociraptor](https://github.com/Velocidex/velociraptor)

- **Sysmon** Windows system monitor for detailed process logs.  
  [SwiftOnSecurity Sysmon-Config](https://github.com/SwiftOnSecurity/sysmon-config)

</details>  

---

<a name="configuration-management-automation"></a>  
# $\color{orange}{\text{Configuration Management and Automation}}$
**Purpose:** Infrastructure as code and orchestration.

<details>  
<summary>Automation Tools</summary>

- **Ansible** Agentless automation and orchestration.  
  [Ansible](https://github.com/ansible/ansible)

- **Terraform** Infrastructure as code across cloud and on-prem.  
  [Terraform](https://github.com/hashicorp/terraform)

</details>

---

<a name="deployment-self-hosting"></a>  
# $\color{orange}{\text{Deployment and Self-Hosting}}$
**Purpose:** Guides for self-hosting security tools.

<details>  
<summary>Guides and Repositories</summary>

- **Self-Hosting-Guide** Comprehensive guide to self-hosting security platforms.  
  [Self-Hosting-Guide](https://github.com/mikeroyal/Self-Hosting-Guide)

</details>
