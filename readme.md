# Fortigate-Project
Docummention installation et configuration fortigate
Architecture de mon lab


Internet
    |
[FortiGate]
Port1-WAN: 192.168.1.200
Port2-LAN: 10.10.10.1
    |
[Switch VMnet1]
    |_______________|_______________|_______________|
    |               |               |               |
[Windows Server]  [Windows 11-1]  [Windows 11-2]  [Kali]
DC/AD/DNS         10.10.10.102    10.10.10.103    10.10.10.101
10.10.10.100