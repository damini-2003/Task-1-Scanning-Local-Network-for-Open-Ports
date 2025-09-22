# Task-1-Scanning-Local-Network-for-Open-Ports
scanning local network using nmap in linux
Used linux in VMware
found the local ip range (192.168.126.0/24)
nmap -sS 192.168.126.0/24 - to perform TCP SYN scan
IP addresses and open ports found:
1. Nmap scan report for 192.168.126.2
2. Host is up (0.0069s latency).
3. PORT   STATE SERVICE
4. 53/tcp open  domain
5. MAC Address: 00:50:56:F9:8D:5D (VMware)
common services running on those ports:
1. IP Address: 192.168.126.2
2. Open Port: 53/tcp
3. Service: DNS
pontential risks identifided for the open port
1. VM exposure
2. DNS amplification attacks
