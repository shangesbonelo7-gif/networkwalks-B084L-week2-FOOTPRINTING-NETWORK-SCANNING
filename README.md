# Week 2: Footprinting, Reconnaissance & Network Scanning
# Overview
This repository documents my Week 2 cybersecurity learning activities, focusing on footprinting, reconnaissance, DNS enumeration, website technology identification, and local network discovery.
The practical involved using Kali Linux tools to gather publicly available information about networkwalks.com and using Zenmap on Windows to discover active devices on a local network.
# Objectives
•	Understand the importance of footprinting and reconnaissance in cybersecurity.
•	Retrieve domain registration information using WHOIS.
•	Identify website technologies using WhatWeb.
•	Perform domain name and IP address resolution using Nslookup.
•	Examine HTTP response headers using cURL.
•	Identify Web Application Firewall (WAF) protection using Wafw00f.
•	Enumerate DNS records using DNSRecon.
•	Install and use Zenmap for local network discovery.
•	Identify live hosts, IP addresses, and MAC addresses.
•	Generate and save a visual network topology in PDF format.
Tools Used
# Tool	Purpose
Kali Linux	Cybersecurity testing environment
WHOIS	Domain registration lookup
WhatWeb	Website technology fingerprinting
Nslookup	DNS and IP address resolution
cURL	HTTP response header analysis
Wafw00f	WAF detection
DNSRecon	DNS enumeration
Zenmap	Graphical network scanning
Nmap	Network discovery and scanning
Windows Command Prompt	Local IP and subnet identification

# Activities Performed
1. Footprinting & Reconnaissance
Conducted reconnaissance on networkwalks.com using six Kali Linux tools.
•	WHOIS: Retrieved domain registration information.
•	WhatWeb: Identified website technologies and frameworks.
•	Nslookup: Resolved the domain name to its associated IP address.
•	cURL: Retrieved and examined HTTP response headers.
•	Wafw00f: Checked for the presence of a Web Application Firewall.
•	DNSRecon: Enumerated publicly available DNS records, including A, AAAA, MX, NS, and TXT records.

# 2. Network Scanning with Zenmap
Installed Zenmap on a Windows PC and used it to discover devices connected to the local area network (LAN).
Activities included:
•	Identifying the local IPv4 address and subnet using ipconfig.
•	Scanning the local subnet for active hosts.
•	Determining the total number of live hosts.
•	Identifying discovered devices' IP addresses and MAC addresses, where available.
•	Viewing the discovered network topology.
•	Saving the network topology as a PDF document.
Example Nmap host discovery command:
nmap -sn 192.168.1.0/24
Note: The subnet above is an example and should be replaced with the actual LAN subnet.
Key Learning Outcomes

# Through this practical, I developed a better understanding of:
•	How reconnaissance helps cybersecurity professionals understand a target's digital infrastructure.
•	How DNS records provide information about domain infrastructure.
•	How website technologies and HTTP headers can reveal useful technical information.
•	How Web Application Firewalls contribute to website security.
•	How Nmap and Zenmap identify active devices on a network.
•	The relationship between IP addresses, MAC addresses, and local network communication.
•	How network topology visualisation helps understand connected devices.

# Ethical Considerations
All activities were conducted for educational purposes. Website reconnaissance focused on publicly available information, while network discovery was limited to networks where scanning was authorised.
No unauthorised access, exploitation, or disruption of services was attempted.

# Conclusion
This week's practical provided hands-on experience with fundamental reconnaissance and network discovery techniques.
I gained practical exposure to Kali Linux reconnaissance tools and Zenmap, strengthening my understanding of domain information gathering, DNS enumeration, website fingerprinting, IP addressing, host discovery, and network topology.
These skills provide a foundation for progressing towards more advanced topics such as Nmap scanning, network security assessment, vulnerability identification, and ethical penetration testing.
Learning Journey: Cybersecurity Fundamentals

Week: 02
Focus: Footprinting, Reconnaissance & Network Scanning

