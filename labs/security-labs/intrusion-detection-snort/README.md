# Intrusion Detection Lab – SNORT

## Overview
This lab explores the configuration and use of the SNORT Intrusion Detection System (IDS) within a simulated enterprise environment using the SimSpace Cyber Range.

## Objectives
- Configure and validate SNORT on a Windows VM
- Analyze network traffic using Wireshark
- Detect suspicious activity and reconnaissance attempts
- Write and deploy custom SNORT rules for known CVEs

## Environment
- Windows VM (Win-Hunt)
- Kali Linux VM
- SimSpace Cyber Range
- Wireshark

## Key Activities
- Located and launched SNORT with the correct network interface
- Generated ICMP, TCP, FTP, Telnet, HTTP, and Nmap traffic
- Captured and analyzed packets using Wireshark
- Created and validated custom SNORT rules for:
  - CVE-2017-5638 (Apache Struts2 RCE)
  - CVE-2021-44228 (Log4Shell)

## Skills Demonstrated
- Intrusion Detection Systems (IDS)
- Network traffic analysis
- Threat detection and alerting
- CVE research and rule creation
- Blue team defensive security
