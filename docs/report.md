# Task 1: Local Network Open Ports Scan

## Scan Summary
- Subnet scanned: 192.168.126.0/24  
- Nmap scan type: TCP SYN scan (-sS)  
- Open ports found: 53/tcp on 192.168.126.2

## Detailed Findings

| IP Address      | Open Ports | Service | Device Type | Risk Level | Recommendation |
|-----------------|------------|---------|-------------|------------|----------------|
| 192.168.126.2   | 53/tcp     | DNS     | VMware VM   | Low-Med    | Restrict DNS to LAN, patch VM regularly |
