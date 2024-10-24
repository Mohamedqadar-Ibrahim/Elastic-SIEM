# ElasticSIEM Project: Monitoring and Detecting Security Events

🚀 **Project Goal:**  
This project demonstrates how I used **ElasticSIEM** to detect and log specific security events from a Windows virtual machine (VM) using the **Elastic Agent**. By configuring integrations, custom rules, and triggering security events, I show my ability to use SIEM tools to monitor and manage security logs efficiently.

## 📑 **Table of Contents**
1. [Project Overview](#project-overview)
2. [Technologies Used](#technologies-used)
3. [Setup Steps](#setup-steps)
4. [Key Screenshots](#key-screenshots)
5. [Results & Analysis](#results-and-analysis)
6. [Conclusion](#conclusion)

---

## 🎯 **Project Overview**
In this project, I configured a Security Information and Event Management (SIEM) environment using **ElasticSIEM** to monitor security events on a Windows VM. I achieved this by deploying an Elastic Agent, creating custom integration policies, setting up a detection rule, and successfully logging and analyzing triggered security events.

This project highlights my skills in:
- **SIEM implementation** for threat detection and incident response.
- **Monitoring security events** through custom rules.
- **Handling event escalation** as a part of security operations.

---

## 🛠 **Technologies Used**
- **ElasticSIEM**: Security Information and Event Management tool.
- **Elastic Agent**: Lightweight agent to collect security logs from the host.
- **Windows 10 VM**: Host for testing and triggering security events.
- **PowerShell**: Used to simulate security incidents.

---

## ⚙️ **Setup Steps**

### 1. **ElasticSIEM Account Creation**
I created an ElasticSIEM account and accessed the dashboard for monitoring events.

### 2. **Adding Elastic Agent to the Windows Host**
The Elastic Agent was installed on a Windows virtual machine to enable real-time log collection and threat detection.  

![Elastic Agent Installed](screenshots/Step%202.PNG)

### 3. **Configuring Integration and Security Policies**
- Added the `ElasticDefendAgent` integration for monitoring Windows events.
- Set up two integration policies: one for system events and one for Windows-specific security events.

![Windows Machine Connected](screenshots/Step%203.PNG)

### 4. **Creating a Custom Detection Rule**
A new rule called `Test Rule 2` was created to detect specific security incidents, including firewall changes or unauthorized script execution.  

![Creating Custom Rule](screenshots/Step%204.PNG)

### 5. **Triggering Security Events**
A PowerShell command was executed on the Windows VM to simulate a security event (`Set-NetFirewallProfile -All -Enabled True`).

---

## 📸 **Key Screenshots**

| Screenshot | Description |
|------------|--------------|
| ![Elastic Agent Installed](screenshots/Step%202.PNG) | Elastic Agent successfully installed on the Windows VM. |
| ![Windows Machine Connected](screenshots/Step%203.PNG) | The Windows VM is now connected to ElasticSIEM, ready for monitoring. |
| ![Creating Custom Rule](screenshots/Step%204.PNG) | Creating a custom rule (`Test Rule 2`) to monitor specific security events. |
| ![Rule Triggered](screenshots/Step%205.PNG) | The custom rule was triggered by a security event, logging the incident successfully. |
| ![Event Details](screenshots/Step%206.PNG) | Details of the security event that triggered the rule. |
| ![Trends Tab for Escalation](screenshots/Step%207.PNG) | Display of security event trends, highlighting potential areas for tuning and escalation. |

---

## 📊 **Results & Analysis**

### 🚨 **Triggering Events and Logs**
Once the PowerShell command was executed, the rule (`Test Rule 2`) successfully detected the firewall change and logged the event as `event.code : "4104"`. This was visible in the ElasticSIEM summary, demonstrating the effectiveness of the SIEM setup.  
![Rule Triggered](screenshots/Step%205.PNG)
![Event Details](screenshots/Step%206.PNG)

### 🔍 **Event Investigation and Escalation**
In a real-world scenario, an analyst would escalate this event for further investigation, ensuring it wasn’t part of an unauthorized breach attempt. Using the **Trends Tab**, we can analyze the frequency of similar events and escalate them as necessary.  
![Trends Tab for Escalation](screenshots/Step%207.PNG)

---

## 🎉 **Conclusion**
This project showcases my ability to set up and manage **ElasticSIEM** for detecting and analyzing security incidents. By monitoring real-time events on a Windows host, creating custom rules, and simulating security threats, I’ve demonstrated my expertise in:
- **SIEM implementation** and configuration.
- **Log monitoring** and detection of security anomalies.
- **Real-world incident response** techniques.

---

### 💼 **Ready for Hire!**
With this project and others in my portfolio, I am ready to take on my first role in **cybersecurity**. I’m passionate about defending systems from cyber threats and excited to contribute to a security operations team.

---

### 👀 **Check Out My Other Projects:**
- [Wazuh SIEM Project](link)
- [WannaCry Simulation](link)

---

## 🚀 **Let's Connect:**
Feel free to reach out if you’d like to discuss my projects or opportunities:
- **Email**: [YourEmail@example.com]
- **LinkedIn**: [YourLinkedInProfile]

