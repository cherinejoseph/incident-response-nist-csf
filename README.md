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

1. **[Incident Report Analysis Template](https://github.com/cherinejoseph/incident-response-nist-csf/blob/main/Incident-report-analysis-template.pdf)**  
    Template to document the analysis and response actions in detail. This template can also be used to practice applying the NIST framework to different situations you encounter.

   
3. **[NIST CSF Framework](https://github.com/cherinejoseph/incident-response-nist-csf/blob/main/Applying-the-NIST-CSF-.pdf)**  
   This will guide the organization through all stages of responding to and managing the security incident.



---

## Steps

## **Identify**
- **Attack Type**: **ICMP Flood (DDoS attack)**.
- **Target**: The **entire internal network** was affected, including all critical network resources.
- **Impact**: All critical network resources needed to be secured and restored to ensure functionality.

## **Protect**
The cybersecurity team implemented several protective measures to mitigate the impact of future incidents:
- **New Firewall Rule**: Rate-limiting for **incoming ICMP packets** to avoid overwhelming the network.
- **IDS/IPS System**: Deployed to filter out malicious ICMP traffic based on suspicious characteristics.

---

## **Detect**
To enhance detection capabilities and prevent future attacks:
- **Source IP Address Verification**: Configured on the firewall to check for **spoofed IP addresses**.
- **Network Monitoring**: Implemented monitoring software to detect **abnormal traffic patterns** and identify any unusual activity early.

---

## **Respond**
The cybersecurity team established a response plan for handling future incidents:
- **Isolation of Affected Systems**: Systems that are affected will be isolated to prevent further disruption.
- **Restoration of Critical Systems**: Critical systems will be restored first to minimize business disruption.
- **Log Analysis**: The team will analyze **network logs** to identify suspicious or abnormal activities.
- **Incident Reporting**: All incidents will be reported to **upper management** and **legal authorities** if needed.

---

## **Recover**
Recovery steps to restore the organization’s network after an ICMP flood attack:
- **Restoring Network Services**: Access to network services will be restored to a functioning state once the attack is mitigated.
- **Blocking Future Attacks**: External **ICMP flood attacks** can be blocked at the firewall level.
- **Managing Internal Traffic**: Non-critical network services will be stopped temporarily to reduce internal traffic, ensuring the restoration of critical systems first.
- **Service Restoration**: Once the attack subsides, all non-critical systems and services will be brought back online.

---

This incident report outlines the critical steps the cybersecurity team took to protect, detect, respond to, and recover from the DDoS attack. It also sets the foundation for improving network security and preparedness for future cybersecurity events.

You can view the completed incident report template here:

[Completed Incident Report Template](https://github.com/cherinejoseph/incident-response-nist-csf/blob/main/Completed-Incident-report-analysis.pdf)

## **Acknowledgements**

This project was completed as part of the **Google Cybersecurity Professional Certificate** on **Coursera**. The insights gained in this course informed the process reviews and improvements presented here.

For more information about the **Google Cybersecurity Professional Certificate**, please visit [Coursera](https://www.coursera.org/professional-certificates/google-cybersecurity).








