# Elevate Labs Task 1 – Nmap Local Network Port Scan

## Objective
Scan the local network to identify active hosts and open ports using Nmap.

## Tool Used
- Nmap

## Network Scanned
- Local network: 192.168.1.0/24

## Command Used
```bash
sudo /Applications/Nmap.app/Contents/Resources/bin/nmap -sS 192.168.1.0/24
## Scan Results

| Port | State | Service |
|------|-------|---------|
| 23/tcp | filtered | telnet |
| 53/tcp | open | domain |
| 80/tcp | open | http |
| 443/tcp | open | https |

## Scan Summary
- IP addresses scanned: 256
- Hosts up: 7

## Security Notes
Open ports indicate network services that may be accessible. Services should be exposed only when required and properly secured.

## Evidence
Screenshots of the Nmap scan results are included in this repository.

## Conclusion
This task provided practical experience with basic network reconnaissance and identifying network service exposure using Nmap.
