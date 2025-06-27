# **Incident Report Analysis using NIST CSF - DDoS Attack on Multimedia Company**. 

# **Scenario**

You are a **cybersecurity analyst** working for a multimedia company that offers **web design services**, **graphic design**, and **social media marketing solutions** to small businesses. Your organization recently experienced a **DDoS attack**, which compromised the internal network for **two hours** until it was resolved.

During the attack, the organization’s **network services** suddenly stopped responding due to an incoming flood of **ICMP packets**. As a result, normal internal network traffic could not access any network resources. The **incident management team** responded by:
- **Blocking incoming ICMP packets**,
- Stopping all **non-critical network services**,
- Restoring **critical network services**.

The company’s **cybersecurity team** then investigated the security event and found that a **malicious actor** had sent a flood of **ICMP pings** into the company’s network through an **unconfigured firewall**. This vulnerability allowed the attacker to overwhelm the company’s network through a **distributed denial of service (DDoS)** attack.

To address this security event, the **network security team** implemented the following measures:
- A **new firewall rule** to limit the rate of incoming ICMP packets.
- **Source IP address verification** on the firewall to check for **spoofed IP addresses** on incoming ICMP packets.
- **Network monitoring software** to detect abnormal traffic patterns.
- An **IDS/IPS system** to filter out some ICMP traffic based on suspicious characteristics.

As a **cybersecurity analyst**, you are tasked with using this security event to create a plan to improve your company’s network security, following the **National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF)**. You will use the CSF to help you navigate through the different steps of analyzing this cybersecurity event and integrate your analysis into a general security strategy.

The analysis is broken down into the following steps:

- **Identify** security risks through regular audits of internal networks, systems, devices, and access privileges to identify potential gaps in security.
- **Protect** internal assets through the implementation of policies, procedures, training, and tools that help mitigate cybersecurity threats.
- **Detect** potential security incidents and improve monitoring capabilities to increase the speed and efficiency of detections.
- **Respond** to contain, neutralize, and analyze security incidents; implement improvements to the security process.
- **Recover** affected systems to normal operation and restore systems, data, and/or assets that have been affected by an incident.

---

## **Supporting Documents**

1. **[Incident Report Analysis Template](https://github.com/cherinejoseph/incident-response-nist-csf/blob/main/Incident-report-analysis.pdf)**  
  template to document the analysis and response actions in detail.
   
2. **[NIST CSF Framework](https://github.com/cherinejoseph/incident-response-nist-csf/blob/main/Applying-the-NIST-CSF-.pdf)**  
   This will guide the organization through all stages of responding to and managing the security incident.












