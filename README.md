Azure Cloud SOC Project 
- This group project was done to emulate a SOC composed of several analysts with various different skillsets responding to a ransomeware incident on a VM on the Azure Cloud.

Tools utilized: Aactive Directory, Entra, Yara, Volatility, Snort, LimaCharlie, Wireshark, Velociraptor, Sysmon, Defender for Identity, Sentinel

Our project consisted of implementing detection rules, setting up monitoring infrastructure on an Active Directory Domain Controller, and conducting an incident response, adhering to a tiered system, using the NIST incident response lifecycle as our guideline. 
Our team consisted of 5 analysts with the following roles and responsibilities:

Andy Voong - Configured Yara Rules to detect the malware sample on impact and conducted memory forensics on the infected domain controller for the purposes of malware analysis.

Jake Ludlow - Configured Snort Rules for network detection and deployed LimaCarlie EDR for the purposes of providing network visibility and system health monitoring.

Manuel Castaneda - Deployed and Configured Velociraptor and conducted remote forensic analysis of the registry hive. In charge of containment and quarantine efforts.

Keenan Johnson - Deployed and configured Sysmon on our domain controller. Fed data provided by Defender for Identity and others into Microsoft Sentinel. In charge of implementing playbooks and configuring runbooks for dahboard visibility and automated response.

Norberto Limon - Set up the AAD infrastructure and domain controller in accordace with the principle of least privilege, as well as Defender for Identity and its accompanying service account to obtain greater visibility into Active Directory. 

Digest:
- Screenshots
- Powerpoint
- Video Presentation: 
- Volatility Malware Analysis Resport
- Setup Instructions
