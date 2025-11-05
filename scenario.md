# Scenario

You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. 

Recently, the organization experienced a **Distributed Denial of Service (DDoS)** attack that compromised the internal network for two hours until it was resolved.

During the attack, the company’s network services suddenly stopped responding due to an incoming flood of **ICMP packets**. Normal internal network traffic could not access any network resources.

The **incident management team** responded by:
- Blocking incoming ICMP packets
- Stopping all non-critical network services
- Restoring critical network services

Upon investigation, the **cybersecurity team** found that a malicious actor had sent a flood of ICMP pings into the company’s network through an **unconfigured firewall**, allowing the attack to overwhelm the network.

To address this, the team implemented:
- A new firewall rule to limit the rate of incoming ICMP packets  
- Source IP address verification to check for spoofed IPs  
- Network monitoring software to detect abnormal traffic patterns  
- An IDS/IPS system to filter out ICMP traffic with suspicious characteristics

This report analyzes the incident and applies the **NIST Cybersecurity Framework (CSF)** to strengthen the organization’s network security posture.
