# Linux-Network-Monitoring-Script project
A lightweight Python-based tool to monitor network connectivity and bandwidth usage on Linux systems.
# Linux Network Monitoring Script

A simple Python-based network monitoring tool for Linux.

## Features
- Pings a target host (default: Google DNS `8.8.8.8`) to check connectivity
- Monitors bandwidth usage of a chosen network interface
- Logs results with timestamps into `network_log.txt`
- Generates alerts for:
  - Unreachable host
  - High bandwidth usage (> 5MB/s)

## Usage
```bash
python3 network_monitor.py
