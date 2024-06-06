# Nessus-Scanner

## Vulnerability Scanner Deployment

Configure Nessus &amp; Vulnerability Assessment Lab (Nessus Scanner)

## Introduction

Here is a comprehensive tutorial on how to install and run Nessus. This tutorial covers the procedures for installing Nessus in the environment, setting it up to search for vulnerabilities, and effectively interpreting the scan findings. Nessus is an acronym for an attack point designed to identify weak points and possible threats in your system, applications, and network architecture. By proactively identifying and fixing vulnerabilities through the regular use of individual vulnerability scanning and the staffed deployment of Nessus, you can strengthen your cybersecurity posture. During my presentation, I will walk through each stage of the Nessus configuration procedure and explain how this scanner works. After completing our training, you will acquire the skills and information needed to use this potent instrument effectively.

- Let's examine the tutorial's structure and the topics that will be addressed at each stage.

## Prepare for Deployment

Before deploying Nessus, please make sure that you understand everything you need to know about it, including how it works with vulnerability management. Info security teams may use Nessus to identify and categorize security flaws in the entire company's network infrastructure, apps, and systems. 
  
### Assess System Requirements

System requirements are evaluated prior to Nessus's final deployment, allowing you to quickly determine whether your infrastructure is capable of supporting this service. The size of your network, the number of assets to be examined at once, and the frequency of the scans are only a few of the numerous variables that might affect the minimal requirements for the Nessus program. Hard memory tracker Nessus, by default, needs a server or virtual machine (VM) with a specific amount of RAM, CPU, and storage space. Nessus implementation may also require initial software dependencies or other compatibility requirements to be met. By assessing the system needs in advance, you can ensure that Nessus will operate constantly at peak efficiency and identify any potential issues during deployment.

### Install Nessus
I obtained the Nessus software from the Tenable website. The website offers software installation instructions that will walk you through installing Nessus on a server or virtual machine, if necessary after you've downloaded it. I used this link to access the software. 

- Nessus Web Interface


## Configuration Phase

After installing Nessus, my next assignment, among many other things, is to access the web interface and configure it, create new scanning policies that will satisfy our organizational requirements, and unquestionably increase the effectiveness of vulnerability scanning by guaranteeing in-depth investigations and concurrently reducing false positives. After the previous phase, which preceded the identification of the target asset, I was eager to fine-tune the IP addresses and domain names to serve as the ransomware scan for Nessus and produce a targeted exposure to vulnerability assessment. To streamline the scanning process, I ultimately introduced sets for scans as recurring jobs and schedules that can significantly increase vulnerability assessment accuracy to guarantee regular assessments and be ahead of new hazards.

- Configure Nessus for scanning


## Conducting Scans and analyzing results

The scanning and analysis process constitutes the second part of the transition; I examined events in real time while doing task vulnerability scans using the default parameters and designated targets. The scan findings evaluation was my favorite task since it allowed me to carefully identify the vulnerabilities and prioritize them based on secession and priority. We were able to prioritize the remediation efforts and communicate with stakeholders more effectively because of the comprehensive reports, cybersecurity scan results, and security recommendations that helped us better understand the security posture of our network.

- Nessus initial scan

- Configuration of Credentials for Credential scan

- Remote registry


- I changed the status type to automatic, which allows you to connect remotely to the system registry database to perform different operations.

- User account control settings are dragged to the bottom to disable notifications from disrupting the scans being conducted.




For the next exercise, I open the registry editor by clicking on the "HKEY_LOCAL_MACCHINE" key, then clicking "SOFTWARE," then "Microsoft," and lastly, I get to the "Windows" directory. The Local Account Token Filter Policy is reviewed and modified here, and exceptions are made for free administrator accounts that are not subject to the restrictions on distant procedure core cognitive access. As a result, the improvements enable Nessus to perform more complex system scans, increasing its capacity to find an excessive number of vulnerabilities.


- Nessus Credential and Advanced Nessus Scan

## Conclusion
I successfully deployed Nessus and obtained the appropriate cues and inputs that enabled the identification of network vulnerabilities and insecurities through meticulous coordination, astute design, and thorough inspection. Custom scanning policies, asset personalization, and automated scanning schedules have all greatly aided in our ability to identify, rank, and promptly address any security threats that may be lurking around the corner. I managed to convey results clearly and prioritize remediation based on the severity of the security incident by using Nessus's report creation feature. In general, Nessus will strengthen the defense, improve the security of communications, and shield data systems from online attacks.

### HappyLearning
