
NetworkWalks Cybersecurity Internship – Week 2
A practical portfolio of five cybersecurity exercises completed as part of the NetworkWalks internship. The work introduces domain and website reconnaissance, search-engine OSINT, graphical OSINT, public information gathering, and basic network discovery.

Each module has its own README with the exercise workflow, tools, evidence, observations, and limitations. Screenshots and the network topology PDF are stored in their corresponding module folders.

Project overview
Module	Topic	Main tools	Documentation
1	Website and domain reconnaissance	WHOIS, WhatWeb, nslookup, curl, wafw00f, DNSRecon	Module 1 README
2	Search-engine reconnaissance	Google Search operators, Google Hacking Database (GHDB)	Module 2 README
3	Graph-based OSINT	Maltego	Module 3 README
4	Domain information gathering	theHarvester	Module 4 README
5	Network discovery and topology	Zenmap, Nmap, Windows Command Prompt	Module 5 README
Flagship module: Website and domain reconnaissance
Module 1 is the flagship exercise because it combines six tools to examine different aspects of a domain's publicly observable footprint: registration information, DNS, web technologies, HTTP responses, and possible web application firewall detection.

Key skills: domain reconnaissance, DNS enumeration, web technology fingerprinting, HTTP inspection, and introductory attack-surface discovery.

WHOIS reconnaissance evidence

See the complete Module 1 walkthrough.

Mandatory capstone: Network discovery
Module 5 applies basic networking knowledge to host discovery. The workflow uses ipconfig to inspect local network configuration, then Zenmap/Nmap to perform a ping scan and visualise responsive hosts.

Zenmap network discovery evidence

The exercise material includes nmap -sn 10.0.0.0/24 as an example. The subnet must be confirmed against the network being tested and should only be scanned with authorisation. Host counts and scan results vary by environment.

See the complete Module 5 walkthrough and the Zenmap network scanning PDF.

Skills covered
Domain and DNS reconnaissance
OSINT and search-engine reconnaissance
Web technology fingerprinting
HTTP response inspection
Email and DNS information gathering
Basic IPv4 addressing and subnet awareness
Host discovery and scan-output interpretation
Network topology visualisation
Technical documentation and evidence handling
Repository structure
.
├── README.md
├── project-module-1/
│   ├── README.md
│   └── reconnaissance screenshots
├── project-module-2/
│   └── README.md
├── project-module-3/
│   ├── README.md
│   └── Maltego screenshots
├── project-module-4/
│   ├── README.md
│   └── theHarvester screenshots
└── project-module-5/
    ├── README.md
    ├── Zenmap screenshots
    └── zenmap_network_scanning.pdf
Responsible use
These exercises are for education and authorised security work. Only investigate domains, systems, and networks for which permission has been granted. Publicly indexed information does not grant permission to access or test a resource.

