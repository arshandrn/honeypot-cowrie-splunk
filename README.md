# Honeypot Attack Detection using Cowrie and Splunk

## Overview
Deployed a Cowrie SSH/Telnet honeypot on Ubuntu VM and forwarded 
captured attack logs to Splunk Enterprise via Universal Forwarder 
for centralized SIEM analysis. Simulated full attacker workflow 
from Kali Linux — recon to intrusion — and validated detection.

## Architecture
Kali Linux (attacker) → Ubuntu Cowrie Honeypot → 
Splunk Universal Forwarder → Splunk Enterprise (Windows)

## Tools Used
Cowrie, Splunk Enterprise, Splunk Universal Forwarder,
Kali Linux, Nmap, Ubuntu 22.04, VirtualBox

## Key Results
- Captured 12 events including Nmap scan probes and SSH sessions
- Logged attacker source IP, username used, and session duration
- Validated full SOC workflow: recon → capture → forward → analyze

## Demo Video
Watch the full project demo: [Click here to view](https://1drv.ms/b/c/ca84ccba0e93da2d/IQAUs7R46A0xRYj6MxzKmnN2Aeian_GGc3Apc6JjFUxplcc?e=mbibC3)
