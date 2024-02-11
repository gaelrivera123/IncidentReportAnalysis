# Incident Report Analysis
    An incident report analysis using NIST CSF

<h2>📝Incident Report Analyis Summary</h2>

An Incident Report Analysis involves documenting and reporting a recent security breach. Although a Incident Report Analysis can be written utilizing any framework or even no framework whatsoever, in cybersecurity the NIST CSF is becoming a much more widely used framework. It provides a strong guideline to conduct any investigation on an organizations cybersecurity and managing security risks. 

<h2>🛡️National Institute of Standards and Technology Cybersecurity Framework (NIST CSF)</h2>

The NIST CSF for short is a very popular cybersecurity framework created to provide organizations best practices, standards, and guidelines for managing cybersecurity risks and overall maintaining a higher level of cybersecurity posture. The NIST CSF is a great way to make it easier to understand and manage cybersecurity risks. The NIST CSF can be through 5 pillars: Identify, Protect, Detect, Respond, & Recover. 

- <b>Identify</b>
  - Perform routine security audits of your organization including ensuring internal networks, devices, systems, and certain access privileges are regularly checked to identify and mitigate potential security gaps.
  - Create an inventory and report of systems, assets, data, processes, people, and capabilities that need to be secured.
    - Core questions to ask yourself as you identify security risks:
      - Hardware/Asset management: Which software, systems, networks, or other key organizational assets were affected?
      - Business Processes: Which business processes, if any, were affected during the attack? Were non-critical and/or critical business procedures affected?
      - People: Which individuals need access to affected systems?

- <b>Protect</b>
  - Create a strategy/plan to better protect organizational assets through creating and implementing stronger policies, training, tools, and procedures that will help mitigate future potential security risks.
  - Implementing safeguards to protect important assets and ensure business services can be consistently delivered.
    - Core questions to ask yourself as you protect against security risks:
      - Access Control: Which individuals need access to affected artifacts. How can we ensure non-trusted sources do not have access to certain systems?
      - Training: Who needs to be aware of policies in the event a security breach occurs? How can we implement new training policies to ensure the breach has a very low likelihood of occurring again?
      - Data Security: Was there any data that had a lack of security? How can we improve on that security?
      - Maintenance and Updates: Were there any systems, software, or hardware that needed to be updated? If so, how we can develop a procedure to ensure all assets are kept up-to-date?
      - Protective Technologies: Were there any Intrusion Prevention Systems, Instrusion Detection Systems, firewalls, or any other protective technology that was implemented? If not, what systems should be implemented to have better security?

- <b>Detect</b>
  - Check for potential security vulnerabilities or possible previously existing attack vectors to mitigate attack surface and increase speed and efficiency of detections.
  - Design and implement a stronger system that utilizes security tools to help detect future threats and attacks:
    - Core questions to ask yourself when trying to detect security risks:
      - Anomaly and Event Detection: How can we implement tools designed to notify IT security staff of anomalies and security events, such as using Security Information and Event Management (SIEM) tools?
      - Continuous Security Monitoring: What tools or processes can we use to constantly monitor systems, softwares, or hardware without hindering business productivity?
      - Detection: What tools are used to detect security events? What tools need to be implemented to detect threats and security events?
     
- <b>Respond</b>
  - Ensure proper procedures, processes, tools, and guidelines are used in order to contain, neutralize, and examine security incidents
  - Design plans to respond to threats and attacks
    - Core questions to ask yourself when trying to detect security risks:
      - Planning: What plans need to be implemented to better efficiently respond to security threats and attacks?
      - Communication: How can IT security staff ensure the procedures on how to respond are communicated within the entire organization and with individuals directly affected by the attack, including staff and users?
      - Analysis: How we can effectively analyze the security incident to better handle a future situation?
      - Mitigation: What necessary steps used to respond can be taken to mitigate the impact of a security incident such as isolating resources or offlining affected systems?
      - Improvements: What improvements need to be impelemented in order to develop a more effective procedure for responding?
     
- <b>Recover</b>
  - Recover any affected systems, data, and assets that were targeted during the attack and restore them to normal operations
  - Construct a plan to recover an organization's assets in a timely, efficient manner after an attack
    - Core questions to ask yourself when trying to recover after an incident:
      - Recovery plan: How can we restore resources after an incident, such as using a backup?
      - Improvements for recovery: Do we need to improve on any current recovery systems or processes?
      - Communications: How we can communicate thoroughly throughout an organization to ensure we restore affected individuals, including staff and users.

<h2>Fictional Scenario</h2>

You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 

The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

<b>To address this security event, the network security team implemented:</b>
  - A new firewall rule to limit the rate of incoming ICMP packets
  - Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets
  - Network monitoring software to detect abnormal traffic patterns
  - An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics

<h2>Incident Report</h2>

Using the NIST CSF framework, along with current cybersecurity knowledge, we will construct an incident report analysis on the fictional scenario above.

[Fictional Incident Report Analysis](tinyurl.com/25ma6q38)
