# Ex.4b-Working-with-network-commands

# AIM :Use of Network commands in Real Time environment
# Software : Command Prompt And Network Protocol Analyzer
# Procedure: To do this EXPERIMENT- follows these steps:
In this EXPERIMENT- students have to understand basic networking commands e.g cpdump, netstat, ifconfig, nslookup ,traceroute and also Capture ping and traceroute PDUs using a network protocol analyzer

All commands related to Network configuration which includes how to switch to privilege mode
and normal mode and how to configure router interface and how to save this configuration to
flash memory or permanent memory.

This commands includes
• Configuring the Router commands
• General Commands to configure network
• Privileged Mode commands of a router
• Router Processes & Statistics
• IP Commands
• Other IP Commands e.g. show ip route etc.

# Program
```
from scapy.all import*
target = ["www.saveeth.ac.in"]
result, unans = traceroute(target,maxttl=32)
print(result,unans)

```
# Output
![Screenshot 2025-04-17 140750](https://github.com/user-attachments/assets/b290dafa-133f-47c2-a7a0-e2664bd42203)

# Result
Thus Execution of Network commands Performed
