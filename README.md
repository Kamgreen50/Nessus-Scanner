# Nessus-Scanner

## Vulnerability Scanner Deployment

Configure Nessus &amp; Vulnerability Assessment Lab (Nessus Scanner)

## Introduction

Here is a comprehensive tutorial on how I installed and ran Nessus. This tutorial covers the procedures for installing Nessus in the environment, setting it up to search for vulnerabilities, and effectively interpreting the scan findings. Nessus is designed to identify weak points and possible threats in systems, applications, and network architecture. I can strengthen my cybersecurity posture by proactively identifying and fixing vulnerabilities through regular vulnerability scanning and deploying Nessus. During this presentation, I will walk through each stage of the Nessus configuration procedure and explain how this scanner works. After completing this training, I will have the skills and knowledge to use this powerful tool effectively.

Let's examine the tutorial's structure and the topics addressed at each stage.

## Prepare for Deployment

Before deploying Nessus, I understood everything about it, including how it works with vulnerability management. Info security teams can use Nessus to identify and categorize security flaws in the company's network infrastructure, apps, and systems.
  
### Assess System Requirements

I evaluated system requirements before Nessus's final deployment, allowing me to determine whether the infrastructure could support this service. The network size, the number of assets to be examined, and the frequency of scans are a few variables affecting the minimal requirements for Nessus. By default, Nessus needs a server or virtual machine (VM) with specific amounts of RAM, CPU, and storage space. Nessus implementation may also require initial software dependencies or other compatibility requirements to be met. By assessing the system needs in advance, I ensured Nessus would operate efficiently and identified any potential issues during deployment.

### Install Nessus
I obtained the Nessus software from the Tenable website. The website offers installation instructions that walked me through installing Nessus on a server or virtual machine. I used the link provided to access the software.

- Nessus Web Interface
<br>

![image](https://github.com/Kamgreen50/Nessus-Scanner/assets/148400787/58ac15e3-4e2a-49b2-9984-56d268a1ba34)

## Configuration Phase

After installing Nessus, I accessed the web interface to configure it. I created new scanning policies that met our organizational requirements, ensuring in-depth investigations and reducing false positives. I fine-tuned the IP addresses and domain names to serve as the scan targets for Nessus, producing a targeted vulnerability assessment. I set up scans as recurring jobs and schedules to streamline the scanning process to ensure regular assessments and stay ahead of new hazards.

- Configure Nessus for scanning
<br>

![image](https://github.com/Kamgreen50/Nessus-Scanner/assets/148400787/0af3dfe1-371b-4059-8acb-3de248562116)


## Conducting Scans and analyzing results

During the scanning and analysis process, I conducted task vulnerability scans using the default parameters and designated targets, examining events in real-time. Analyzing the scan findings was particularly rewarding, as it allowed me to identify and prioritise vulnerabilities based on severity and urgency. Comprehensive reports, scan results, and security recommendations helped us better understand our network's security posture, prioritize remediation efforts, and communicate effectively with stakeholders.

- Nessus initial scan
<br>

![image](https://github.com/Kamgreen50/Nessus-Scanner/assets/148400787/b2d2ef50-5ab7-470b-b9dd-76ab87d2c17d)

![image](https://github.com/Kamgreen50/Nessus-Scanner/assets/148400787/6fc4bd6e-8c66-480f-8614-4623e6535034)

![image](https://github.com/Kamgreen50/Nessus-Scanner/assets/148400787/7d5f6c4a-6ea0-4ff8-8873-212f8afa44eb)

![image](https://github.com/Kamgreen50/Nessus-Scanner/assets/148400787/f2d699c6-9c65-4648-9ee0-2931b26061cf)


- Configuration of Credentials for Credential scan
<br>

![image](https://github.com/Kamgreen50/Nessus-Scanner/assets/148400787/c4757733-c571-4950-bb42-99d062a10724)

- Remote registry
<br>

![image](https://github.com/Kamgreen50/Nessus-Scanner/assets/148400787/5c7220d2-7c7b-414c-b788-cc6f6dc28b5b)

- I changed the status type to automatic, which allows you to connect remotely to the system registry database to perform different operations.
<br>

![image](https://github.com/Kamgreen50/Nessus-Scanner/assets/148400787/d284de17-5ea5-476f-8ccb-c8b2e3031f62)

- User account control settings are dragged to the bottom to prevent notifications from disrupting the scans.
<br>

![image](https://github.com/Kamgreen50/Nessus-Scanner/assets/148400787/25574006-3515-46d1-9b00-35528ea2dea5)

![image](https://github.com/Kamgreen50/Nessus-Scanner/assets/148400787/f3cf732b-79ec-4c09-8a87-80c60d08823a)


## Registry Editor
I opened the registry editor, navigated to "HKEY_LOCAL_MACHINE," then to "SOFTWARE," "Microsoft," and finally to the "Windows" directory. Here, I reviewed and modified the Local Account Token Filter Policy, making exceptions for administrator accounts to bypass restrictions on remote procedure access. These improvements allowed Nessus to perform more complex system scans, increasing its capacity to find vulnerabilities.
<br>

![image](https://github.com/Kamgreen50/Nessus-Scanner/assets/148400787/de030734-3e10-4d3d-8905-0ebf9b600ae7)

- Nessus Credential and Advanced Nessus Scan
<br>

![image](https://github.com/Kamgreen50/Nessus-Scanner/assets/148400787/2f19c35f-d5e9-4001-b95f-1be8c4b3b6f5)


## Conclusion
I successfully deployed Nessus and obtained the appropriate cues and inputs to identify network vulnerabilities through meticulous coordination, astute design, and thorough inspection. Custom scanning policies, asset personalization, and automated scanning schedules greatly aided in identifying, ranking, and addressing security threats promptly. Using Nessus's report creation feature, I conveyed results clearly and prioritized remediation based on the severity of the security incident. Nessus has strengthened our defences, improved communication security, and shielded data systems from online attacks.

### HappyLearning
