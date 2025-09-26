This is a Packet Tracer project I did as part of my uni course. 

It uses VLSM for addressing, RIPv2 for routing, and DHCP so PCs get IPs automatically.  

The full write-up is in `report/Network_Design_Report.pdf`.

<img width="1707" height="1065" alt="image" src="https://github.com/user-attachments/assets/abc3da77-c7d6-4439-b079-dd9de7ba8c3e" />

## Why I built this
I wanted to practice the basics and be able to explain them.  
Plan the IPs. Set the routes. Give out addresses. Test with pings.  
Small on purpose. I understand each step and can fix it when it breaks.

## What’s in the report

Link -> https://github.com/einsstark/Network-Design-Packettracer/tree/main/report

The address plan, the subnets I made from the given block, the gateways, and the tests.  
It’s written so someone else can follow the same steps and get the same result.

## What I learned
Start with the IP plan on paper.  
Configure slowly and test as you go.  
/30 for links keeps things tidy.  
Exclude gateway/infra IPs from DHCP.  

## How to open
1) Install Cisco Packet Tracer  
2) Download this repo (Code → Download ZIP) or clone it  
3) Open `FinalNetworkProject.pkt`

## Verify
Ping across subnets.  
First ping may miss (ARP). Next pings should pass.  
Use Simulation Mode to watch ARP/ICMP.



Cisco and Packet Tracer are trademarks of Cisco Systems, Inc.
