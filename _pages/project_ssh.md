---
layout: single
title: SSH-Hack-Lab
permalink: projects/ssh
---


<style>body {text-align: justify}</style>

This project focuses on simulating and testing three different SSH attack techniques in a lab environment. The goal is to demonstrate common vulnerabilities in SSH protocols and showcase potential security risks that attackers might exploit. Each attack scenario is carefully documented, providing insights into the mechanics of the attack, its impact, and possible mitigation strategies. This project serves as an educational resource for understanding SSH-based threats and improving overall security practices.


**Phase 1: Needs Assessment and Analysis**

**Phase 2: Risk Analysis and Assessment**

Threats and Vulnerabilities:

- DDoS (Distributed Denial of Service) attack
- Port scanning
- Exploit attack / Software vulnerabilities

**Phase 3: Infrastucture**

3.1. Planned Modification of the Current Architecture
![Architecture](/assets/images/architecture.jpg)


Steps:
- Creation of isolated network
- Real network: "Erika" network
- A Linux VM on the isolated network for honeypot
- Attacker uses the Kali
- 4 port forwards on OPNsense to Honeypot (3 Honeypot + 1 real SSH)

3.2. Creation of different Honeypots
- Endlessh - tarpit
- SSH Auth Logger - Low interaction
- Cowrie - High interaction

**Phase 4: Monitoring and alerting**

4.1. Attack - simulation

- Port scanning
- Brute force
- Lateral movement
- Cyber kill chain

4.2. Monitoring of low and hign interaction

- Firewall Logging
- Log Analytics

**Phase 5: Monitoring and maintenance**

5.1. Vulnerability Assessment

5.2. Updates

**Phase 6: Project Closure and Evaluation**

6.1. Creation of the [Documentation](/assets/docs/SSH_docs.pdf){:target="_blank"}.

6.2. Final Project Evaluation and Lessons Learned

Here you can check the [Attacks](/assets/docs/prezi.pdf){:target="_blank"}.

**Next steps / opportunities:**
- Ansible for automation
- Dockerize the services
- Allow outgoing trafﬁc for more insights
- New kind of honeypots



