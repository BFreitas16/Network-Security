# Network-Security
These projects where made in Network Advanced Security and Architecture class. The main goal was to study the principles and techniques for the design and management of secure network infrastructures in heterogeneous environments.

------------------------------
# Table of Contents
- [Network Attacks & Mitigations](#project-1-network-attacks-and-mitigations)
- [Firewalls & AAA](#project-2-firewalls-and-aaa)
- [IPSec and VPNs](#project-3-ipsec-and-vpns)

------------------------------
# Project 1 Network Attacks and Mitigations
Report: [`Network Attacks & Mitigations`](network_attacks_report.pdf)  
Config File: Configurations inside the report in Annex  
  
This report addresses some network vulnerabilities and countermeasures. It is also explained the steps to reproduce the attacks, the steps to prevent it and some theoretical concepts necessary for its understanding.  
Topics covered:
* CAM table overflow
* DHCP attacks
  * DHCP spoofing
  * DHCP starvation
* ARP poisoning (MitM)
* STP manipulation
* VLAN attacks
  * DTP attack
  * Double-tagging attack
* DNS spoofing
* RIP poisoning
* Idle Scan
* ICMP redirect (MitM)

------------------------------
# Project 2 Firewalls and AAA
Report: [`Firewalls & AAA`](firewalls_and_aaa_report.pdf)  
Config file: [`Firewalls & AAA Configuration`](firewalls_and_aaa_configs.txt)  
  
This report addresses Firewalls and AAA which stands for Authentication, Authorization and Accounting (basically, is a framework used to control who is permitted to use the network resources - authentication - what they are authorized to do - authorization - and capture the actions performed while accessing the network - accounting).  
Topics covered:
* Classical Firewalls
* Zone Based Policy Firewalls
* Defense agains DoS attacks
* AAA
  * TACACS+
  * RADIUS
* 802.1X authentication
* ASA firewall

------------------------------
# Project 3 IPSec and VPNs
Report: [`IPSec & VPNs`](ipsec_and_vpns_report.pdf)  
Config File: Configurations inside the report in Annex  
  
This report addresses IPSec and VPNs, where it is analyzed different VPNs and their configurations.  
Topics covered:
* Tunneling
  * GRE
  * IPv6 tunneling over IPv4
* IPSec
  * IPSec using ESP in tunnel mode & AH in tunnel mode
  * IPSec with NAT traversal
  * GRE over IPSec
* DMVPN
  * DMVPN over IPSec
* GETVPN
* Load balancing and redundancy
  * HSRP
  * HSRP with object tracking
  * Attacking HSRP
  * GLBP
* VRFs and MPLS VPNs
