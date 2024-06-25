# Deploying and Managing a T-Pot Honeypot

## Objective

I set up a T-Pot honeypot to detect and analyze malicious activities by simulating vulnerable systems. T-Pot, developed by the Deutsche Telekom Security Team, integrates several honeypots and analysis tools, making it a comprehensive solution for cybersecurity research and threat intelligence. 

* Detect and log various types of cyber attacks in real-time.
* Analyze attack patterns and techniques used by adversaries.
* Enhance my understanding of honeypot deployment and management.

### Skills Learned

* **Network Security and Monitoring:** Understanding of how to monitor and secure networks, detecting and analyzing malicious activities in real-time.
* **Vulnerability Assessment and Management:** Ability to identify and assess vulnerabilities using various honeypot tools, and implementing remediation strategies.
* **Incident Response and Threat Analysis:** Skills in responding to security incidents and analyzing threats through forensic analysis of captured data.
* **Data Analysis and Visualization:** Proficiency in collecting, analyzing, and visualizing security data using tools like Kibana and Elasticsearch.
* **System Administration and Automation:** Enhanced skills in deploying and managing virtual machines, configuring network settings, and automating maintenance tasks.

### Tools Used

- [Vultr](https://www.vultr.com)
- [T-Pot Version 24.04](https://github.security.telekom.com/2024/04/honeypot-tpot-24.04-released.html#user-types)

## Step 1: Set up VM

* Go to Vultr and sign up (There should be a $100 credit for the cloud provider) and start to configure the VM. Out of the 4 options, the Cloud Compute - Shared CPU was the cheapest. For the location of where the VM will deploy, pick the one closest to your location. 

![cloud config 1](https://github.com/Xmick01/Deploying-and-Managing-a-T-Pot-Honeypot/assets/130627895/aa634a41-07bb-4a06-9eb2-091ce4c5c397)

* Name the server hostname and make sure that the cost is acceptable.

![honeypot deploy](https://github.com/Xmick01/Deploying-and-Managing-a-T-Pot-Honeypot/assets/130627895/2ca1bc9a-6581-4ab4-9b0f-3132abe134de)

