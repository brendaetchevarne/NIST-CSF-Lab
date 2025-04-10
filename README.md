# 🛡️ DDoS Attack Incident Report – Applying the NIST Cybersecurity Framework

## 📝 Project Description

In this project, I created a cybersecurity incident report analyzing a Distributed Denial of Service (DDoS) attack that targeted a company’s internal network. The main objective was to apply the NIST Cybersecurity Framework (CSF) to assess and respond to the incident. This involved identifying vulnerabilities, recommending protective measures, improving detection capabilities, planning an appropriate incident response, and outlining recovery strategies. The exercise demonstrated my ability to apply structured security frameworks in real-world scenarios and propose actionable solutions to strengthen network defenses.

## 🧠 Skills Learned

- Cybersecurity incident analysis  
- Application of the NIST Cybersecurity Framework (CSF)  
- Network security strategy development  
- Risk identification and mitigation  
- Technical reporting and documentation

> *Note: The analysis was theoretical, but based on real-world cybersecurity practices.*

## 📄 Incident Report – Analysis Table

| **NIST CSF Function** | **Analysis** |
|-----------------------|--------------|
| **Summary** | The company experienced a security event when all network services suddenly stopped responding. The cybersecurity team found the disruption was caused by a Distributed Denial of Service (DDoS) attack through a flood of incoming ICMP packets. The team responded by blocking the attack and stopping all non-critical network services, so that critical services could be restored. |
| **Identify** | A malicious actor targeted the company with an ICMP flood attack. The internal network was affected, and all critical network resources needed to be secured and restored. |
| **Protect** | The cybersecurity team implemented a new firewall rule to limit incoming ICMP packets and an IDS/IPS system to filter ICMP traffic based on suspicious characteristics. |
| **Detect** | The team configured source IP address verification on the firewall to identify spoofed IPs and deployed network monitoring software to detect abnormal traffic. |
| **Respond** | For future incidents, the team plans to isolate affected systems, restore critical services, analyze network logs for suspicious activity, and report incidents to upper management and legal authorities. |
| **Recover** | Recovery involves restoring access to network services. The plan includes blocking ICMP floods at the firewall, stopping non-critical services, restoring critical services first, and bringing systems back online once the attack has subsided. |

## 💡 Reflections / Lessons Learned

This exercise helped reinforce the importance of applying structured frameworks like the NIST CSF when responding to cybersecurity incidents. I learned how each phase (Identify, Protect, Detect, Respond, Recover) contributes to building a strong incident response strategy. It also highlighted the need for proactive security measures, such as firewall configurations and network monitoring, to minimize the impact of DDoS attacks. Documenting and analyzing incidents is essential not only for learning from past events but also for strengthening future response capabilities.
