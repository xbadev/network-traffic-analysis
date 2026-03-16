# Network Traffic Analysis Lab
Hands-on network traffic analysis using Wireshark in a virtualized lab environment. Each section captures, filters, and analyzes different types of network traffic to understand how protocols behave on the wire and why encryption matters.
## Labs
| # | Lab | Description |
|---|-----|-------------|
| 1 | [Telnet vs SSH](telnet-vs-ssh/) | Captured and compared cleartext Telnet traffic against encrypted SSH traffic. Demonstrated full credential exposure over Telnet using Wireshark TCP stream analysis. |
| 2 | [FTP vs SFTP](ftp-vs-sftp/) | Captured and compared cleartext FTP traffic against encrypted SFTP. Demonstrated credential and file content exposure over FTP using Wireshark display filters and TCP stream analysis. |
| 3 | [HTTP vs HTTPS](http-vs-https/) | Captured and compared cleartext HTTP form submissions against encrypted HTTPS traffic. Demonstrated credential exposure in HTTP POST requests and full TLS encryption with HTTPS. |
| 4 | [Suspicious Traffic Detection](suspicious-traffic-detection/) | Generated and analyzed malicious network patterns including Nmap SYN scans, aggressive scans, and ARP spoofing. Identified attack signatures using Wireshark display filters. |
## Up Next
**Simulated Attack Analysis** — Performing a full attack chain (reconnaissance → access → exfiltration) in one continuous capture and analyzing the timeline in Wireshark.
