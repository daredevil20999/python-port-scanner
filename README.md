# python-port-scanner

A command-line port scanner I built with in Python as part of my cybersecurity journey.

## What it does
Scans a target IP address for open ports in the range 1–1024 and prints any open ports to the terminal.

## How to use it
```bash
python3 port_scanner.py
```
Then enter a target IP address when prompted.

## Example output
```
Scanning 192.168.64.12...

Port 22: OPEN
Port 80: OPEN
```

## Tools & Languages
- Python 3
- socket module
