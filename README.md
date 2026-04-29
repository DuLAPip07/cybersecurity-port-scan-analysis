# Nmap Network Scan Report

## Overview
This project demonstrates network scanning and service enumeration using Nmap.

## Tools Used
- Nmap
- Command Line Interface

## Scan Results
Identified open ports and services including:
- Port 115 (MSRPC)
- Port 445 (SMB)
- Port 3306 (MySQL)
- Port 5000 (HTTP - Node.js)

## Key Findings
- Presence of database service (MySQL) may expose sensitive data
- SMB service may be vulnerable if not properly secured
- HTTP service could be entry point for web-based attacks

## Recommendation
- Disable unnecessary ports
- Apply firewall rules
- Regular vulnerability scanning

## Report
Download the full report here: [Network Scan Report](./Kevwe_Nmap_Network_Scan_Report.pdf)
