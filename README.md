# port-scan-task1
TCP SYN scan of local network using Nmap
# Task 1 – Port Scanning with Nmap

## Objective
Performed a TCP SYN scan on my local network using Nmap to identify open ports and understand network exposure.

## Network Details
- IP: 192.168.0.103  
- Range: 192.168.0.0/24

## Command Used
ipconfig
nmap -sS 192.168.0.0/24
nmap -sS 192.168.0.0/24 > scan_results.txt


## Output
Scan results saved in `scan_results.txt` showing active devices and open ports.

## Learnings
- Used Nmap for reconnaissance
- Found common open ports (e.g., 80, 443, 22)
- Understood the risks of exposed services

## Tools
- Nmap
- CMD (Windows)

## Files
- `scan_results.txt`
- `README.md`
