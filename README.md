# nmap-Scan-
nmap local IP Scan for open ports 
C:\Users\mkarun>nmap -sS 10.92.112.229 -oN scan_results.txt
Starting Nmap 7.98 ( https://nmap.org ) at 2025-09-22 14:42 +0530
Nmap scan report for 10.92.112.229
Host is up (0.00043s latency).
Not shown: 995 closed tcp ports (reset)
PORT     STATE SERVICE
135/tcp  open  msrpc
139/tcp  open  netbios-ssn
445/tcp  open  microsoft-ds
4343/tcp open  unicall
4449/tcp open  privatewire
