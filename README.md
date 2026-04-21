# Network Reconnaissance Lab

## Overview
Deployed an isolated virtual lab environment using VirtualBox to perform 
network reconnaissance on a vulnerable target machine.

## Tools Used
- Kali Linux
- Nmap
- VirtualBox
- Metasploitable2

## Lab Environment
- Attacker Machine: Kali Linux (192.168.56.101)
- Target Machine: Metasploitable2 (192.168.56.102)
- Network: Host-Only Adapter (isolated lab network)

## Steps Performed
1. Host Discovery - identified live hosts on the network
2. Port Scanning - identified open ports and running services
3. Service Version Detection - identified software versions
4. OS Fingerprinting - identified target operating system
5. Aggressive Scan - comprehensive scan combining all techniques
6. Saved scan output for documentation and analysis

## Key Findings
- FTP (Port 21) - Anonymous login enabled (critical vulnerability)
- SSH (Port 22) - OpenSSH 4.7p1 running
- Telnet (Port 23) - Unencrypted remote access enabled
- HTTP (Port 80) - Apache 2.2.8 web server running
- Samba (Port 139) - File sharing service detected

## Skills Demonstrated
- Network reconnaissance
- Vulnerability identification
- Linux command line
- Documentation of findings
