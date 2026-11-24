# Network Configuration Handbook

A 39-page, side-by-side command reference for **Cisco IOS**, **Huawei VRP** and **MikroTik RouterOS**, from first-time setup to a worked small-office project.

Written by **Samiru Ninduwara**, NVQ Level 4 Network Technician student.

<p align="center">
  <a href="https://github.com/SamiruNinduwara/Network-Configuration-Handbook/releases/download/handbook/Network-Configuration-Handbook.pdf">
     <img src="https://img.shields.io/badge/Download%20PDF-Network%20Configuration%20Handbook-1B998B?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="Download the PDF"
      <img src="https://img.shields.io/badge/Download%20PDF-...&logoColor=white" alt="Download the PDF" width="480"/>
  </a>
</p>

---

## Why this handbook

Most guides cover one vendor at a time. In real work you meet all three, and the same task is typed very differently on each. This handbook shows **the same task on all three platforms next to each other**, so you can compare, learn and look things up quickly.

## What is inside

| # | Chapter |
|---|---------|
| 1 | IP Addressing and Subnetting |
| 2 | First-Time Device Setup |
| 3 | Interfaces and IP Configuration |
| 4 | Switching: VLANs, Trunks, STP, LACP and Port Security |
| 5 | Inter-VLAN Routing |
| 6 | Routing: Static, Floating and OSPF |
| 7 | Network Services: DHCP, NAT, DNS and NTP |
| 8 | Access Control and Firewall |
| 9 | Monitoring: Syslog and SNMP |
| 10 | Firmware Upgrade and Password Recovery |
| 11 | IPv6 Basics |
| 12 | PC-Side Network Commands (Windows and Linux) |
| 13 | Troubleshooting Method and Symptom Guide |
| 14 | Verification Commands Cheat Sheet |
| 15 | Worked Project: A Small Office Network |
| 16 | Gateway Redundancy (HSRP and VRRP) *(advanced)* |
| 17 | DHCP Snooping and ARP Inspection *(advanced)* |
| 18 | Site-to-Site IPsec VPN *(advanced, lab use)* |
| A | Quick Reference: The Same Task on Each Vendor |
| B | Glossary and Where to Practise |
| C | References and Further Reading |

## Highlights

- Every topic shown on **Cisco, Huawei and MikroTik** side by side
- A **subnetting** chapter with worked examples and practice questions
- A **bottom-up troubleshooting** method and a symptom table
- A **worked project** (router + switch, staff, guest and management VLANs, DHCP, NAT, guest isolation) with full configs for all three vendors
- A **verification cheat sheet** and a one-page quick reference

## Who it is for

Network technician students, helpdesk and junior network staff, and anyone building a home or small-office lab.

## Testing status

The commands are written from standard vendor syntax and **have not yet been fully tested on real devices**. Syntax differs between models and software versions, especially on Huawei VRP and between MikroTik RouterOS v6 and v7. Always test in a lab first:

- Cisco: Packet Tracer or GNS3
- Huawei: eNSP
- MikroTik: a free RouterOS CHR virtual machine

Always confirm a command against the vendor's own documentation for your device (see Appendix C in the PDF).

Found a mistake or a command that does not work on your version? Please open an **Issue** with the chapter number, your device and software version, and the error you saw.

## Disclaimer

This handbook is for learning and lab use. Example passwords, IP addresses and keys are placeholders, so never copy them to a real device. Use it on equipment you own or are authorized to manage.

## Author

**Samiru Ninduwara** | NVQ Level 4 Network Technician student, Sri Lanka

Also see: [Network Troubleshooting Handbook](https://github.com/SamiruNinduwara/Network-Troubleshooting-Handbook)
