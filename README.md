# python-port-scanner

A command-line port scanner I built with in Python as part of my cybersecurity journey.

## What it does
Scans a target IP address for open ports in the range 1–1024 and prints any open ports to the terminal.
Performs banner grabbing on open ports to identify running services and versions.
## How to use it
```bash
python3 port_scanner.py
```
Then enter a target IP address when prompted.

## Example output
```
Enter target IP: scanme.nmap.org

Scanning scanme.nmap.org...

Port 22: OPEN - SSH-2.0-OpenSSH_6.6.1p1 Ubuntu-2ubuntu2.13
Port 80: OPEN - HTTP/1.1 200 OK
```

## Tools & Languages
- Python 3
- socket module

## ⚠️ Disclaimer
This tool is intended for educational purposes and authorized testing only.
Do not scan targets without explicit permission.
