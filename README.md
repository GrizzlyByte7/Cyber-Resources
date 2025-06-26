*This is a working list. I add to it as I find new tools and resources.*  
<br/>

## 📑 Table of Contents  
- [Forensics & Imaging](#🕵️-forensics--imaging)  
- [Hex Editors](#🔢-hex-editors)  
- [Malware Analysis](#🦠-malware-analysis)  
- [Memory Forensics](#🧠-memory-forensics)  
- [OSINT](#🕸️-osint)  
- [Windows Artifact Analysis](#📂-windows-artifact-analysis)  
- [Attack Simulation & Offense](#🚩-attack-simulation--offense)  
  - [Reconnaissance](#reconnaissance-information-gathering)  
  - [Scanning & Enumeration](#scanning--enumeration)  
  - [Vulnerability Assessment](#vulnerability-assessment)  
  - [Exploitation Frameworks](#exploitation-frameworks)  
  - [Password Cracking](#password-cracking)  
- [Logging & SIEM](#📊-logging--siem)  
  - [Splunk Queries](#splunk-queries)  
  - [Sysmon Logging](#sysmon-logging)  
  - [Other SIEM & Rule Conversion](#other-siem--rule-conversion)  
- [Threat Hunting & Detection Engineering](#🔍-threat-hunting--detection-engineering)  
- [Purple-Team Collaboration](#🎭-purple-team-collaboration)  
- [DFIR Case Management & Automation](#🗂️-dfir-case-management--automation)  
- [Cloud Security & CSPM](#☁️-cloud-security--cspm)  
- [Endpoint Telemetry & EDR](#⚙️-endpoint-telemetry--edr)  

---

# 🕵️ Forensics & Imaging  
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

# 🔢 Hex Editors  
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

# 🦠 Malware Analysis  
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
  [malware-traffic-analysis.net](https://www.malware-traffic-analysis.net/)

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

# 🧠 Memory Forensics  
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

# 🕸️ OSINT  
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

# 📂 Windows Artifact Analysis  
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

# 🚩 Attack Simulation & Offense 🚩  
**Purpose:** Recon, scanning, exploitation, and red-team training platforms.

### Reconnaissance (Information Gathering)  
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

- **WhereToGo**  
  Curated list of popular corporate services to test for compromised-account pivot points.  
  [valeriyshevchenko90/WhereToGo](https://github.com/valeriyshevchenko90/WhereToGo)

- **crt.sh**  
  Certificate transparency log lookup.  
  [crt.sh](https://crt.sh/)

- **CloudSploit**  
  AWS misconfiguration scanner.  
  [CloudSploit](https://github.com/aquasecurity/cloudsploit)

- **Fierce**  
  DNS & directory brute‐forcing.  
  [Fierce](https://github.com/mschwager/fierce)

- **Maltego**  
  Link‐analysis graphing.  
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

</details>

---

</details>

### Scanning & Enumeration  
<details>
<summary>Port & Service Scanners</summary>

- **Masscan**  
  Internet-wide SYN scanner.  
  [Masscan](https://github.com/robertdavidgraham/masscan)

- **Nmap**  
  Host discovery & port scanning.  
  [Nmap](https://nmap.org/)

- **RustScan**  
  Fast port scanning with Nmap integration.  
  [RustScan](https://github.com/RustScan/RustScan)

- **Netdiscover**  
  Passive ARP-based host discovery.  
  [Netdiscover](https://github.com/alexxy/netdiscover)

- **LDAPDomainDump**  
  Dump Active Directory via LDAP.  
  [LDAPDomainDump](https://github.com/dirkjanm/ldapdomaindump)

- **enum4linux-ng**  
  SMB/NetBIOS enumeration on Linux.  
  [enum4linux-ng](https://github.com/cddmp/enum4linux-ng)

</details>

### Vulnerability Assessment  
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

### Exploitation Frameworks  
<details>
<summary>Penetration Test Suites</summary>

- **Metasploit**  
  Exploit development & execution framework.  
  [Metasploit](https://www.metasploit.com/)

- **Cobalt Strike**  
  Commercial red-team & adversary simulation tool.  
  [Cobalt Strike](https://www.cobaltstrike.com/)

- **Impacket**  
  Python network protocols for pentesting.  
  [Impacket](https://github.com/SecureAuthCorp/impacket)

</details>

### Password Cracking  
<details>
<summary>Cracking & Brute‐Force Tools</summary>

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

---

# 📊 Logging & SIEM  
**Purpose:** Centralized log analysis and detection content.

### Splunk Queries  
<details>
<summary>Community & Official Queries</summary>

- **GoSplunk**  
  Community-posted Splunk queries.  
  [GoSplunk](https://gosplunk.com/)

- **shauntdergrigorian/splunkqueries**  
  Curated threat-hunting queries.  
  [splunkqueries](https://github.com/shauntdergrigorian/splunkqueries)

- **Splunk Security Content**  
  Official detection searches & dashboards.  
  [Splunk Security Content](https://research.splunk.com/)

- **Splunk Security Essentials**  
  App with guided detections & searches.  
  [Security Essentials](https://splunkbase.splunk.com/app/3435/)

</details>

### Sysmon Logging  
<details>
<summary>Sysmon Configurations</summary>

- **SwiftOnSecurity/sysmon-config**  
  High-signal Sysmon configuration.  
  [SwiftOnSecurity](https://github.com/SwiftOnSecurity/sysmon-config)

- **olafhartong/sysmon-modular**  
  Modular Sysmon ruleset.  
  [sysmon-modular](https://github.com/olafhartong/sysmon-modular)

</details>

### Other SIEM & Rule Conversion  
<details>
<summary>Rule Conversion & Helpers</summary>

- **Uncoder.IO**  
  Convert Sigma rules to SIEM query languages.  
  [Uncoder.IO](https://uncoder.io/)

</details>

---

# 🔍 Threat Hunting & Detection Engineering  
**Purpose:** Hunt for anomalies, author detection rules, automate alerting.

<details>
<summary>Hunting Frameworks & Rule Engines</summary>

- **Sigma**  
  Generic YAML-based detection rule format, convert to any SIEM.  
  [SigmaHQ/sigma](https://github.com/SigmaHQ/sigma)

- **ElastAlert**  
  Alerting on Elasticsearch query results, pipeline detections.  
  [Yelp/elastalert](https://github.com/Yelp/elastalert)

- **Wazuh Ruleset**  
  Open-source HIDS with built-in rules for Windows/Linux logs.  
  [wazuh/wazuh](https://github.com/wazuh/wazuh)

- **OpenSOC**  
  Automated streaming analytics for large-scale hunting.  
  [OpenSOC](https://github.com/OpenSOC/OpenSOC)

- **Merlin**  
  In-memory command and control detection framework.  
  [Ne0nd0g/merlin](https://github.com/Ne0nd0g/merlin)
</details>

---

# 🎭 Purple-Team Collaboration  
**Purpose:** Share detections, adversary emulations, exercises.

<details>
<summary>Purple Team Tooling</summary>

- **Atomic Red Team**  
  Library of small, scriptable tests mapped to MITRE ATT&CK.  
  [RedCanaryLabs/atomic-red-team](https://github.com/redcanarylabs/atomic-red-team)

- **Caldera**  
  Automated adversary emulation platform by MITRE.  
  [mitre/caldera](https://github.com/mitre/caldera)

- **PurpleSharp**  
  .NET red-blue operations framework for Windows environments.  
  [flanglet/PurpleSharp](https://github.com/flanglet/PurpleSharp)

- **AttackIQ**  
  Commercial breach-and-attack emulation with reporting.  
  [AttackIQ](https://www.attackiq.com/)
</details>

---

# 🗂️ DFIR Case Management & Automation  
**Purpose:** Track investigations, share IOCs, automate repetitive tasks.

<details>
<summary>Case & IOC Platforms</summary>

- **TheHive**  
  Scalable, open-source incident response platform.  
  [TheHive-Project/TheHive](https://github.com/TheHive-Project/TheHive)

- **Cortex**  
  TheHive’s analysis engine for tasks (VirusTotal, MISP lookups, etc.).  
  [TheHive-Project/Cortex](https://github.com/TheHive-Project/Cortex)

- **MISP**  
  Threat-sharing platform for IOCs, campaigns, sightings.  
  [MISP/MISP](https://github.com/MISP/MISP)

- **Timesketch**  
  Collaborative forensic timeline analysis.  
  [google/timesketch](https://github.com/google/timesketch)

- **AutoIR**  
  Playbook-driven automation for containment & evidence collection.  
  [AutoIR](https://github.com/COOLSec/AutoIR)
</details>

---

# ☁️ Cloud Security & CSPM  
**Purpose:** Discover misconfigs, monitor cloud activity, enforce posture.

<details>
<summary>Cloud Detection & Posture Tools</summary>

- **ScoutSuite**  
  Multi-cloud security auditor for AWS, GCP, Azure.  
  [nccgroup/ScoutSuite](https://github.com/nccgroup/ScoutSuite)

- **Prowler**  
  AWS CIS-benchmark checks & threat detections.  
  [toniblyx/prowler](https://github.com/toniblyx/prowler)

- **Cartography**  
  Graph-based inventory of cloud assets & relationships.  
  [lyft/cartography](https://github.com/lyft/cartography)

- **Cloud Custodian**  
  Rule engine to remediate cloud resources.  
  [cloud-custodian/cloud-custodian](https://github.com/cloud-custodian/cloud-custodian)

- **KICS**  
  Infrastructure-as-code scanning for security issues.  
  [Checkmarx/kics](https://github.com/Checkmarx/kics)
</details>

---

# ⚙️ Endpoint Telemetry & EDR  
**Purpose:** Collect detailed host data, hunt across endpoints.

<details>
<summary>EDR & Telemetry Tools</summary>

- **Velociraptor**  
  Endpoint monitoring & collection, custom hunts via VQL.  
  [Velocidex/velociraptor](https://github.com/Velocidex/velociraptor)

- **Osquery**  
  SQL interface for live endpoint state and drift detection.  
  [osquery/osquery](https://github.com/osquery/osquery)

- **GRR Rapid Response**  
  Enterprise-scale remote live forensics & triage.  
  [google/grr](https://github.com/google/grr)

- **FleetDM**  
  osquery fleet management, query scheduling & reporting.  
  [fleetdm/fleet](https://github.com/fleetdm/fleet)

- **Sysmon**  
  Windows system monitor for detailed process & network logs.  
  [SwiftOnSecurity/sysmon-config](https://github.com/SwiftOnSecurity/sysmon-config)
</details>
