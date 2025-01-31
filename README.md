# Mobile Network Scanning & OSINT Project

This project involves scanning networks and gathering open-source intelligence (OSINT) using Termux.

## Tools Used
- **Nmap**: Network scanning
- **Whois**: Domain information lookup
- **DNSUtils**: DNS record analysis

## Results
All scan results are stored in the `results/` folder.

## How to Run
1. Run `nmap -sS -Pn <target_ip>` to scan a network.
2. Use `whois <domain>` for OSINT.
3. Check `nslookup <domain>` for DNS records.
