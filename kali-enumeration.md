## Kali Linux Enumeration Cheat Sheet


Nmap: 
``` 
nmap -sS -sV -O -A -T4 <target IP or hostname> 
```
Netdiscover: 
```
netdiscover -r <IP range>
```
Nbtscan:
```
nbtscan <target IP or hostname>
```
DNSenum:
```
dnsenum <target domain>
```
Whois:
```
whois <target domain or IP>
```
SMBMap:
```
smbmap -H <target IP>
```
SNMPWalk:
```
snmpwalk -c public -v1 <target IP>
```
TheHarvester:
```
theharvester -d <target domain> -l 500 -b all
```
Please note that using these tools without permission on a system or network that you do not own is illegal. 
The usage and the output can vary based on the target machine's OS and configurations also these are just a 
basic commands for each tool, you can use different options and flags for more specific tasks.
