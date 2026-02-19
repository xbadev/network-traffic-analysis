# Network Traffic Analysis Lab

Hands-on network traffic analysis using Wireshark in a virtualized lab environment. Each section captures, filters, and analyzes different types of network traffic to understand how protocols behave on the wire and why encryption matters.

## Lab Environment

| Machine | OS | IP Address |
|---|---|---|
| Kali Linux | Kali 2024+ | `192.168.56.30` |
| Ubuntu Server | Ubuntu 24.04.4 LTS | `192.168.56.20` |

VirtualBox host-only network (`192.168.56.0/24`).

## Sections

| # | Lab | Description |
|---|-----|-------------|
| 1 | [Telnet vs SSH](telnet-vs-ssh/) | Captured and compared cleartext Telnet traffic against encrypted SSH traffic. Demonstrated full credential exposure over Telnet using Wireshark TCP stream analysis. |

## Up Next

**FTP vs SFTP** — Capturing file transfer traffic to compare cleartext FTP credentials and file contents against encrypted SFTP.
