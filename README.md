# CYBER SECURITY COMPENDIUM

![TITLE IMAGE](head.jpg)

### NAVIGATION
<br />	
<br />

- [Detailed Content Breakdown ](#FULL-CONTENTS) 
<br />	
<br />

| SECTION | TOPICS|
| ------------- | ------------- |
| CHAPTER 0   | [Introduction & the Basics](#INTRODUCTION)  |
| CHAPTER 1   | [Frameworks](#FRAMEWORKS)  |
| CHAPTER 2  | [Cyber Tools](#CYBER-TOOLS)  |
| CHAPTER 3  | [Knowledge Resources](#KNOWLEDGE-RESOURCES)  |
| CHAPTER 4   | [Next-Gen Cyber Intelligence](#NEXT-GEN-INTELLIGENT-INTELLIGENCE)  |
| CHAPTER 5   | [DevSecOps](#DevSecOps)  |
| CHAPTER 6   | [Compliance Frameworks](#COMPLIANCE)  |


<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />

# FULL CONTENTS

<br />	
<br />


| SECTION | TOPICS|
| ------------- | ------------- |
| **CHAPTER 1**   | [Frameworks](#FRAMEWORKS)  |
| *NIST FRAMEWORK*   | [NIST](#NIST-FRAMEWORK)  |
| Open Web Application Security Project  | [OWASP](#Resource-Link)  |
| Zero Trust Security  | [ZEROTRUST](#Zero-Trust-Security)  |
| OSINT  | [OSINT](#Open-Source-Intelligence)  |
| **CHAPTER 2**  | [Cyber Tools](#CYBER-TOOLS)  |
| AWS Guard​Duty   | [Guard​Duty](#Guard-Duty)  |
| Crowd Strike   | [Crowd Strike](#Crowd-Strike)  |
| ThreatConnect  | [ThreatConnect](#ThreatConnect)  |
| Bloodhound  | [Bloodhound](#Bloodhound)  |
| MISP  | [MISP](#MISP)  |
| Cyber Chef  | [Cyber Chef](#Cyber-Chef)  |
| **OPEN SOURCE** | **FREE-EASY** |
| Hack the Box   | [HTB](#Hack-The-Box)  |
| Pwned  | [PWNED](#PWNED-PASSWORDS)  |
| Threat Crowd  | [Threat-Crowd](#Threat-Crowd)  |
| Cybercrime Feeds  | [Cybercrime Feeds](#Cybercrime-Feeds)  |
| **CHAPTER 3**  | [Knowledge Resources](#KNOWLEDGE-RESOURCES)  |
| Signature Wrapping  | [SIGNATURE WRAPPING ATTACK](#SIGNATURE-WRAPPING-ATTACK)  |
| AWESOME PENTEST  | [AWESOME PENTEST](#AWESOME-PENTEST)  |
| How to NMAP   | [MAPPING PORTS](#HOW-TO-NMAP)  |
| Intelligence Feeds   | [Open Source Threat Intelligence Feeds](#Open-Source-Threat-Intelligence-Feeds)  |
| zero trust security model  | [Google BeyondCorp](#BeyondCorp)  |
| **CHAPTER 4**   | [Next-Gen Cyber Intelligence](#NEXT-GEN-INTELLIGENT-INTELLIGENCE)  |
| AI FOR OFFENCE | [DARKTRACE WHITEPAPER](#DARKTRACE-WHITEPAPER)  |
|   | [NEURALNET INJECTION](#ML-INJECTION )  |
|    | [ML N-MAP ](#ML-N-MAP  )  |
|  | [SQL-INJECTION-TURBOCHARGING ](#SQL-INJECTION-TURBOCHARGING )  |
| AI FOR DEFENCE | [AI FOR DEFENCE](#AI-FOR-DEFENCE)  |
|  | [BEST PRACTICES](#BEST-PRACTICES)  |
|   | [ROBUST AI FRAUD ARCHITECTURES](#ROBUST-AI-FRAUD-ARCHITECTURES)  |
|  | [Dynamic GCP ](#GCP-RECOMMENDATIONS)  |
| CHAPTER 5   | [DevSecOps](#DevSecOps)  |
| Intro | [DevSecOps Overview](#DEVSECOPS-OVERVIEW)  |
| Misconceptions | [DevSecOps Misconceptions](#DEVSECOPS-MISCONCEPTIONS)  |
| Scaling | [DEVSECOPS at Scale](#DEVOPS-AT-SCALE)  |
| CHAPTER 6   | [Compliance Frameworks](#COMPLIANCE)  |
| CSA STAR  | [Cloud Auditing](#CSA-STAR)  |
| ISO 27001 | [Policy Auditing](#AISO-27001)  |
| Leidos   | [Accredited Testing](#LEIDOS)  |
| PCI 3.2   | [Data Security Standard](#PCI-DSS)  |
| PCI HIPAA   | [HIPAA](#PCI-HIPAA)  |
  

<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />

# INTRODUCTION 

This CyberCompendium can be treated as a quick-ref guide for anyone wanting to build their knowledge of cyber security, tools, popular frameworks and more.  


## SIDE NOTE 
 This CyberCompendium is a living breathing document and is changing overtime; you can feel free to fork or make update requests if changes, errors or omissions are spotted. In this section we will cover some basics of cyber security. 

 - [Terminology](#Terminology)
 - [CVECybersecurity Vulnerabilities and Exposures](#CVE-Cybersecurity-Vulnerabilities-and-Exposures)
  

<br />
<br />
<br />
<br />

## Terminology 


1. **Cloud**
A technology that allows us to access our files and/or services through the internet from anywhere in the world. Technically speaking, it’s a collection of computers with large storage capabilities that remotely serve requests.

2. **Software**
A set of programs that tell a computer to perform a task. These instructions are compiled into a package that users can install and use. For example, Microsoft Office is an application software.

3. **Domain**
A group of computers, printers and devices that are interconnected and governed as a whole. For example, your computer is usually part of a domain at your workplace.

4. **Virtual Private Network (VPN)**
A tool that allows the user to remain anonymous while using the internet by masking the location and encrypting traffic.

5. **IP Address**
An internet version of a home address for your computer, which is identified when it communicates over a network; For example, connecting to the internet (a network of networks).

6. **Exploit**
A malicious application or script that can be used to take advantage of a computer’s vulnerability.

7. **Breach**
The moment a hacker successfully exploits a vulnerability in a computer or device, and gains access to its files and network.

8. **Firewall**
A defensive technology designed to keep the bad guys out. Firewalls can be hardware or software-based.

9. **Malware “the bad guy”**
An umbrella term that describes all forms of malicious software designed to wreak havoc on a computer. Common forms include: viruses, trojans, worms and ransomware.

10. **Virus**
A type of malware aimed to corrupt, erase or modify information on a computer before spreading to others. However, in more recent years, viruses like Stuxnet have caused physical damage.

11. **Ransomware**
A form of malware that deliberately prevents you from accessing files on your computer – holding your data hostage. It will typically encrypt files and request that a ransom be paid in order to have them decrypted or recovered. For example, WannaCry Ransomware. For more information on Ransomware, check out our free Ransomware Guide.

12. **Trojan horse**
A piece of malware that often allows a hacker to gain remote access to a computer through a “back door”.

13. **Worm**
A piece of malware that can replicate itself in order to spread the infection to other connected computers.

14. **Bot/Botnet**
A type of software application or script that performs tasks on command, allowing an attacker to take complete control remotely of an affected computer. A collection of these infected computers is known as a “botnet” and is controlled by the hacker or “bot-herder”.

15. **DDoS**
An acronym that stands for distributed denial of service – a form of cyber attack. This attack aims to make a service such as a website unusable by “flooding” it with malicious traffic or data from multiple sources (often botnets).

16. **Phishing or Spear Phishing**
A technique used by hackers to obtain sensitive information. For example, using hand-crafted email messages designed to trick people into divulging personal or confidential data such as passwords and bank account information.

17. **Encryption**
The process of encoding data to prevent theft by ensuring the data can only be accessed with a key.

18. **BYOD (Bring Your Own Device)**
Refers to a company security policy that allows for employees’ personal devices to be used in business. A BYOD policy sets limitations and restrictions on whether or not a personal phone or laptop can be connected over the corporate network.

19. **Pen-testing**
Short for “penetration testing,” this practice is a means of evaluating security using hacker tools and techniques with the aim of discovering vulnerabilities and evaluating security flaws.

20. **Clickjacking**
A hacking attack that tricks victims into clicking on an unintended link or button, usually disguised as a harmless element.

 Information sourced from the great article by Devon Milkovich [here](https://www.cybintsolutions.com/20-cyber-security-terms-that-you-should-know/)

## CVE Cybersecurity Vulnerabilities and Exposures

![CVE](IMAGES/CVE.png)
  

CVE is a dictionary that provides definitions for publicly disclosed cybersecurity vulnerabilities and exposures. The goal of CVE is to make it easier to share data across separate vulnerability capabilities (tools, databases, and services) with these definitions. CVE Entries are comprised of an identification number, a description, and at least one public reference.   
[CVE HOME](https://cve.mitre.org/about/faqs.html#what_is_cve)
[CVE origins from here](https://nvd.nist.gov/vuln/search)
[A good compendium for all CVEs here](https://www.cvedetails.com/)

<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />

# FRAMEWORKS 


### [JUMP TO TOP](#NAVIGATION) 

| Topic | Quick Jump |
| ------------- | ------------- |
| NIST FRAMEWORK   | [NIST](#NIST-FRAMEWORK)  |
| Open Web Application Security Project  | [OWASP](#Resource-Link)  |
| Zero Trust Security  | [ZEROTRUST](#Zero-Trust-Security)  |
| OSINT  | [OSINT](#Open-Source-Intelligence)  |

<br />


## NIST FRAMEWORK 

On February 12th 2013, president Obama issued executive order **13636** to improve **critical infrastructure cyber security**. One year later NIST released a voluntary framework, which can be considered as a living/evolving document.
This differs from other compliance such as PCI, HIPAA - this is a general overview framework that is relevant hierarchically for all people form all backgrounds. The idea is to help people organize their thoughts and strategies to better improve communication and cyber security posture. 

<br />

![NIST](https://www.identitymaestro.com/wp-content/uploads/2019/03/NIST-Framework-Visual-with-Functions-and-Categories.png)
<br />

NIST FRAMEWORK  [NIST](https://www.nist.gov/cyberframework) 

<br />

This innovation behind the strategy is broken down into few core pillars, **identify**, **protect**, **detect**, **respond** and **recover**.  

**Identification**. is highly important in areas such as mergers, new onboarding and acquisitions when you don’t know what you are getting.  We spend a lot of time inside our own networks  scanning and discovering new devices, not just assets under our management but also assets that don’t belong on our network.

<br />

# Open Web Application Security Project (OWASP) 


### Resource Link
- [OWASP](https://www.owasp.org/index.php/Main_Page)


![OWASP IMAGE](https://images.techhive.com/images/article/2017/02/owasp-100709974-large.jpg)
  


The Open Web Application Security Project (OWASP) is an online community that produces freely-available articles, methodologies, documentation, tools, and technologies in the field of web application security

<br />
<br />

## OWASP TOP 10

![TOP10](IMAGES/TOP10.png)
[download the guide](https://www.owasp.org/images/7/72/OWASP_Top_10-2017_%28en%29.pdf.pdf)

The goal of **OWASP TOP 10** is to educate developers, architects, managers, organizations, and designers about the consequences of the most common and most important web application security weakness. OWASP TOP 10 provides **basics techniques** to protect against these high-risk problems and give guidance what to do next


<br />
<br />


## Zero Trust Security

`"The perimeter is dead: Long live the micro perimeter."`


![zt image](https://www.travelers.com/iw-images/resources/Business/Large/NetworkSecurity_large.jpg)



It's time to abandon the caslte and mote analogy for security. 

The Zero Trust model is primarily concerned around network security, the old way of doing things was that you focused on securing your network from external actors - however internal comunicaiton was relatively unrestricted *(the thinking being, that if you are inside the perimiter then you are a good actor)*. However, this means like the story of Troy, once the attackers made it passed the castle wall, they were free to cause unfettered dmage. 
  
  
In a Zero Trust model, you cannot trust anything in or out of your network: creating a new type of data-centric perimeter around information and protecting it with strong encryption techniques tied to intelligent authentication is the best security approach. Blindly allowing users to access the data without checking their identity negates the entire security stack.

**Implementations** 

- [Zscaler](https://www.zscaler.com/mission-possible-zero-trust-security)
- [Gitlab main](https://about.gitlab.com/2019/08/21/zero-trust-at-gitlab-the-data-classification-and-infrastructure-challenge/)
- [Gitlab 1](https://about.gitlab.com/2019/04/01/evolution-of-zero-trust/)
- [Gitlab 2](https://about.gitlab.com/2019/08/09/zero-trust-at-gitlab-problems-goals-challenges/)
- [Cisco](https://www.cisco.com/c/en/us/products/security/zero-trust.html)
- [Akami](https://www.akamai.com/uk/en/solutions/security/zero-trust-security-model.jsp)
- [Symantec](https://www.symantec.com/en/uk/solutions/zero-trust-ecosystem)

**Mechanism** 

Example 1 - use **Bastion hosts** .

A bastion host is a special-purpose computer on a network specifically designed and configured to withstand attacks. The computer generally hosts a single application, for example a proxy server, and all other services are removed or limited to reduce the threat to the computer

<br />
<br />
<br />

## Open Source Intelligence

![OSINT](https://miro.medium.com/max/2636/1*Dpf3zGMTvMZ94ydA2qIYmA.png)

OSINT differs largely from the other frameworks, in that it is primarily a hackers framework *(but lies in a grey area)*, but can also be used for defence by 'knowing the enemy' and understanding common attack surfaces. OSINT framework focused on gathering information from free tools or resources. The intention is to help people find free OSINT resources.

**Resources**

- [OSINT Compendium](https://osintframework.com/)  
- [Top 10 OSINT tools](https://www.greycampus.com/blog/information-security/top-open-source-intelligence-tools)

<br />
<br />
<br />
<br />

# CYBER TOOLS 

### [JUMP TO TOP](#NAVIGATION) 

| Topic | Quick Jump |
| ------------- | ------------- |
| AWS Guard​Duty   | [Guard​Duty](#Guard-Duty)  |
| Crowd Strike   | [Crowd Strike](#Crowd-Strike)  |
| ThreatConnect  | [ThreatConnect](#ThreatConnect)  |
| Bloodhound  | [Bloodhound](#Bloodhound)  |
| MISP  | [MISP](#MISP)  |
| Cyber Chef  | [Cyber Chef](#Cyber-Chef)  |
| **OPEN SOURCE** | **FREE-EASY** |
| Hack the Box   | [HTB](#Hack-The-Box)  |
| Pwned  | [PWNED](#PWNED-PASSWORDS)  |
| Threat Crowd  | [Threat-Crowd](#Threat-Crowd)  |
| Cybercrime Feeds  | [Cybercrime Feeds](#Cybercrime-Feeds)  |

<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />

# Guard Duty

![Guard​Duty](https://d1.awsstatic.com/Products/product-name/diagrams/product-page-diagram-Amazon-GuardDuty_how-it-works.4370200b49eddc34d3a55c52c584484ceb2d532b.png)

- Home[here](https://aws.amazon.com/guardduty/)
- Info [here](https://searchaws.techtarget.com/definition/Amazon-GuardDuty)

Amazon GuardDuty is a threat detection service that continuously monitors for malicious activity and unauthorized behavior to protect your AWS accounts and workloads. With the cloud, the collection and aggregation of account and network activities is simplified, but it can be time consuming for security teams to continuously analyze event log data for potential threats. With GuardDuty, you now have an intelligent and cost-effective option for continuous threat detection in the AWS Cloud. The service uses machine learning, anomaly detection, and integrated threat intelligence to identify and prioritize potential threats. GuardDuty analyzes tens of billions of events across multiple AWS data sources, such as AWS CloudTrail, Amazon VPC Flow Logs, and DNS logs.


<br />
<br />
<br />
<br />


## Crowd Strike

![Crowd Strike](https://solutionsreview.com/endpoint-security/files/2019/03/crowdstrike-modified.jpg)


- EndPoint Protection[here](https://www.crunchbase.com/organization/crowdstrike)
- Case Study [here](https://aws.amazon.com/solutions/case-studies/crowdstrike/)


CrowdStrike is a leader in cloud-delivered, next-generation services for endpoint protection, threat intelligence, and response. The CrowdStrike Falcon platform stops breaches by preventing and responding to all types of attacks—both malware and malware-free. The company has revolutionized endpoint protection by combining next-generation anti-virus technology with endpoint detection and response, coupled with a 24/7 managed hunting service, all delivered via the cloud in a single integrated solution. Falcon uses the patented CrowdStrike Threat Graph™ to analyze and correlate billions of events in real time, providing complete protection and five-second visibility across all endpoints. CrowdStrike Falcon is currently deployed in more than 170 countries. 




<br />
<br />
<br />
<br />

## Hack The Box

![hack the box](https://tech.eu/wp-content/uploads/2019/04/Hack-The-Box-logo.png)

- Hack the Box [here](https://www.hackthebox.eu/)
- Hack the Box tutorial [here](https://0xrick.github.io/hack-the-box/teacher/)


<br />
<br />

## ThreatConnect

![ThreatConnect](https://mms.businesswire.com/media/20190305005177/en/707340/23/ThreatConnect_Logo_-_Logo_CMYK_%281%29.jpg)

- Home Site [here](https://threatconnect.com)


  
<br />
<br />


## Bloodhound

![Bloodhound](https://camo.githubusercontent.com/bcbb9550b8c6a48223efb5a83273cdcc162b3626/687474703a2f2f692e696d6775722e636f6d2f5365336175484e2e706e67)

- Wiki Site [here](https://github.com/BloodHoundAD/Bloodhound/wiki)

- [The Dog Whisperer’s Handbook](https://insinuator.net/2018/11/the-dog-whisperers-handbook/)
  
<br />
<br />

## MISP

![MISP](https://securitymadein.lu/assets/media/logo-circl-MISP.png)

- Home Site [here](https://www.misp-project.org/)


  
<br />
<br />

## Cyber Chef

![CYBERCHEF](https://pbs.twimg.com/media/DUTU8GAW4AEhq7c.jpg)


- CyberChef [here](https://github.com/gchq/CyberChef)
- CyberSaucier [here](https://github.com/DBHeise/CyberSaucier)

<br />
<br />


# PWNED PASSWORDS

![PWNED](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRDEYvr4H5xDdaw1RHWgC_NN1RyPYLUzWaPMqDyPkbwM1ke7w8r)

[Have you been pwned?](https://haveibeenpwned.com)

Have I Been Pwned? is a website that allows internet users to check if their personal data has been compromised by data breaches.


<br />
<br />


# Threat Crowd 

![Threat-Crowd](https://1.bp.blogspot.com/-k7CQUS6t3nY/VtOJQzCErpI/AAAAAAAAANo/maNxj1K4S8Q/s1600/Overall.png)

- [Threat Crowd Home](https://www.threatcrowd.org/)
- [Tutorial](http://threatcrowd.blogspot.com/2015/03/tutorial.html)
- [Tutorial2](html)


ThreatCrowd is a system for finding and researching artefacts relating to cyber threats. 	


<br />
<br />
<br />

# Cybercrime Feeds

![Cybercrime image](https://www.google.com/url?sa=i&source=images&cd=&ved=2ahUKEwjEg8rYndbkAhXD2eAKHbGWCqwQjRx6BAgBEAQ&url=http%3A%2F%2Fiplists.firehol.org%2F&psig=AOvVaw334ynMeqAXt-s9FoCfLAtS&ust=1568753862911768)

This site analyses all available security IP Feeds, mainly related to on-line **attacks**, on-line service **abuse**, **malwares**, **botnets**, **command and control** servers and other cybercrime activities.


This IP list is a composition of other IP lists.
**The objective is to create a blacklist that can be safe enough to be used on all systems, with a firewall, to block access entirely, from and to its listed IPs.**
The key prerequisite for this cause, is to have no false positives. All IPs listed should be bad and should be blocked, without exceptions.

<br />
<br />
<br />
<br />
<br />
<br />
  
# KNOWLEDGE RESOURCES 
  
### [JUMP TO TOP](#NAVIGATION) 

| Topic | Quick Jump |
| ------------- | ------------- |
| ACTIVE DIRECTORY SECURITY ASSESSMENT  | [LINKEDIN DOC](#ACTIVE-DIRECTORY-SECURITY-ASSESSMENT)
| Signature Wrapping  | [SIGNATURE WRAPPING ATTACK](#SIGNATURE-WRAPPING-ATTACK)  |
| AWESOME PENTEST  | [AWESOME PENTEST](#AWESOME-PENTEST)  |
| How to NMAP   | [MAPPING PORTS](#HOW-TO-NMAP)  |
| Intelligence Feeds   | [Open Source Threat Intelligence Feeds](#Open-Source-Threat-Intelligence-Feeds)  |
| zero trust security model  | [Google BeyondCorp](#BeyondCorp)  |

<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />

## ACTIVE DIRECTORY SECURITY ASSESSMENT 

- FULL TUTORIAL [AD](https://www.linkedin.com/posts/the-cyber-security-hub_active-directory-security-assessment-adsa-ugcPost-6637332733641261056-_vkQ/?fbclid=IwAR3l5GGu4iAdIDP7YEYnQ9xdLJShAmIvWUblDsVn3rK-sx4hJ3u2zBj0anQ)


<br />
<br />
<br />
<br />



## SIGNATURE WRAPPING ATTACK
- Signature Wrapping [Here](https://www.ws-attacks.org/XML_Signature_Wrapping) 
  
<br />
<br />

## AWESOME PENTEST

A collection of awesome penetration testing resources.

Penetration testing is the practice of launching authorized, simulated attacks against computer systems and their physical infrastructure to expose potential security weaknesses and vulnerabilities.

    
- AWESOME-PENTEST  [PENTEST](https://github.com/enaqx/awesome-pentest)

<br />
<br />


## HOW TO NMAP
  

  
- NMAP How to [NMAP](https://hackertarget.com/nmap-tutorial/)

<br />
<br />

## Open Source Threat Intelligence Feeds

The following list of open source threat intelligence feeds is maintained for the participants of the Operator’s Security Toolkit program. It provides a list of the resources, activities, groups, and organizations. The links and data can be used in many ways. The most obvious is to “check the credibility” of any security vendor that claims “special security data” and then offer it to the Operator at a special price. We have found cases where people have taken open source community data provided for the best interest of the Internet and then sold it to governments who paid a huge sum. This resource is one tool to prevent this type of abuse. 

- [source](https://www.senki.org/operators-security-toolkit/open-source-threat-intelligence-feeds/)

<br />
<br />

## BeyondCorp

BeyondCorp is Google's implementation of the zero trust security model that builds upon eight years of building zero trust networks at Google, combined with ideas and best practices from the community. By shifting access controls from the network perimeter to individual users and devices, BeyondCorp allows employees, contractors, and other users to work more securely from virtually any location without the need for a traditional VPN.

- [source](https://cloud.google.com/beyondcorp/#researchPapers)


<br />
<br />
<br />
  
# NEXT-GEN INTELLIGENT INTELLIGENCE  

### [JUMP TO TOP](#NAVIGATION) 

| Topic | Quick Jump |
| ------------- | ------------- |
| AI FOR OFFENCE | [DARKTRACE WHITEPAPER](#DARKTRACE-WHITEPAPER)  |
|   | [NEURALNET INJECTION](#ML-INJECTION )  |
|    | [ML N-MAP ](#ML-N-MAP  )  |
|  | [SQL-INJECTION-TURBOCHARGING ](#SQL-INJECTION-TURBOCHARGING )  |
| AI FOR DEFENCE | [AI FOR DEFENCE](#AI-FOR-DEFENCE)  |
|  | [BEST PRACTICES](#BEST-PRACTICES)  |
|   | [ROBUST AI FRAUD ARCHITECTURES](#ROBUST-AI-FRAUD-ARCHITECTURES)  |
|  | [Dynamic GCP ](#GCP-RECOMMENDATIONS)  |





<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />



# AI FOR OFFENCE

## DARKTRACE WHITEPAPER

![DARKTRACE](https://www.darktrace.com/en/img/cards/552x309.jpg)

### The Next Paradigm Shift 

**AI-Driven Cyber-Attacks**

[LINK](https://www.darktrace.com/en/resources/wp-ai-driven-cyber-attacks.pdf)


This report exampines the present state of the threatlandscape and explore the role narrow artificial intelligence (AI) will play in cyber-offense.
It presents three scenarios where advanced threats have achieved high levels of sophistication for specific, isolated characteristics. 

1. Autonomous malware
2. Intelligent evasion techniques
3. Low-and-slow data exfiltration 


Each threat covers a different phase of the attack lifecycle:

- Lateral movement
- Command & control traffic
- Data exfiltration

## SQL INJECTION TURBOCHARGING

- OBTAIN LIST OF 1000+ SQL INJECTION METHODS
- LABEL BASED ON TARGET OS, TARGET APPLICATION ETC
- CLASSIFY (SUCCESS/FAILURE/NA)
- PRODUCE MODEL THAT OFFERS THE BEST ATTACK VECTOR FOR A GIVEN TARGET


## ML INJECTION 

The ultimate attack profile. 

1. Decimenate payload on target machine 
2. Payload acts as intelligent trojan, using client side training or federated learning. 
3. Probing and moving itself reactively, not based on static if/or statements, but actually adapting to anti-virus software.


## ML N-MAP 

Consider a network trained to detect running ports, vulnerabilities etc. 

[REF](https://www.researchgate.net/publication/327786263_Using_Deep_Learning_Model_for_Network_Scanning_Detection)

<br />
<br />
<br />
<br />


# AI FOR DEFENCE

## BEST PRACTICES 

**Machine Learning In Cyber Threat Detection**

```
LEARN ATTACK PROFILES
```

**AI, Password Protection and Authentication**

```
Biometrics are easily circumvented

AI can enhanced FACE ID tampering
```


**AI-ML In Phishing Detection And Prevention Control**

**Usage of AI-ML In Vulnerability Management**

```
Detect open ports
Detect Unpatched servers, botched patches, patch clashes 
Detect AD hijacking
```

**Behavioral Analytics with AI**

```
Profile malicious users based on activities that haven’t quite crossed the line.	

```


# ROBUST AI FRAUD ARCHITECTURES

Many compnaies are now building end to end machine learning pipelines to lock down services instead of hiring humans to do the analytics and prevention. 
  

### SETBACKS   

These models use hundreds if not thousands of data points to accurately classify a transaction as valid or not. Even the most sophisticated methods are unable to correctly identify a lot of fraudulent transactions.

- Biggest issues with A.I fraud engines is that they quickly become irrelevant.
- This is because fraud tactics change in real time. 
- Customer data used to predict fraud today, becomes irrelevant tomorrow.
  
  
### AI ARCHITECTURE

![arch](https://i0.wp.com/opentechai.blog/wp-content/uploads/2017/10/opentechai-flower.png?resize=498%2C364&ssl=1)  

Example of a new scalable Fraud prevention architecture.

*"An app which organisations can embedd into their product, so that they generate realtime fraud metrics that act as a quality gate on transactions"*


- APP hosted on cloud (GCP, AWS etc)
- Client side, they implement some js or trigger to A.I cloud hosted service 
- On the checkout page (Say as a customer busy/sells something) the snippet is added
- USER META data is sent (Time on page, IP address, The web browser they are using) automatically
- Standard google analytics process (they make their clients do it too )
- API call will need to be implemented to send sensitive user purchase data (card details) and encrypt it.
- Sensitive and User meta data is concatinated into the machine learning model 
- A score is produce (how likely the transaction is to be fraud based on score)

### 2020 AI ARCHITECTURE

This is so 2019 

Weaknesses include `non gdpr compliant` because data is encrypted, but shared without permission. So information is secure, but not compliant. 

We need to ...

```
Modify architecture to preserve privacy and learn from User data 
```

1. First encrypt User data 
2. Then perform CLIENT side machine learning from it.
3. So we send to the server, not the **RAW DATA** but what it has **LEARNED** from the data.
4. This is in the form of an encrypted weights file 
5. 

### KEY FEATURES

1. Continuous Training
2. Federated Learning (Client Side)
3. Model Encryption, Share only the encrypted weights back to server
4. Secure Multi-party compliant communication 

### KEY STRATEGIES

- Utilize cloud 
**LAMBDA KINESIS S3 ATHENA**
- Make responsive just in time triggers (serverless)
- Streat data in real time 

### INFRASTRUCTURE STRATEGY 

Request to API is initiated 
AWS app passes request to Lambda (event driven compute)
Feeds into kinesis an AWS tool capable of processing hundreds of terrabytes of data per hour 
Operating laws, social media feeds, our case fin tranactions
Kinesis helps us avoid heavy queuing by creating a scalable datastream and sharding
Then we use firehose functionality to write functionality to S3 
Then we query S3 database using Athena so we can immediately display it in analytics dashboards

<br />
<br />
<br />


## GCP RECOMMENDATIONS

![recommendation engine](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQL0Ru00Bavpcv4I9ll5nYE6x54LF5QMb3PnHNdnBZESloJpjttMQ)

Recommenders automatically analyze usage patterns to help determine if resources and policies within Google Cloud are optimally configured. Data usage information is not shared in the process.

With the **Cloud Identity and Access Management (Cloud IAM) Recommender**, you can automatically detect weak access policies and adjust them based on the access patterns of similar users in your organization. This is a follow up to the Alpha launch at Cloud Next this past April.

The Google Compute Engine Rightsizing Recommender helps you choose the optimal virtual machine size for your workload. Our experience working with customers shows that they often initially provision machines that are too small or too large.

<br />
<br />
<br />
<br />
<br />
<br />



# DEVSECOPS 

![DEVSECOPS](https://130e178e8f8ba617604b-8aedd782b7d22cfe0d1146da69a52436.ssl.cf1.rackcdn.com/devsecops-keys-to-success-showcase_image-1-a-11299.jpg)

### [JUMP TO TOP](#NAVIGATION) 

| Topic | Quick Jump |
| ------------- | ------------- |
| Intro | [DevSecOps Overview](#DEVSECOPS-OVERVIEW)  |
| Misconceptions | [DevSecOps Misconceptions](#DEVSECOPS-MISCONCEPTIONS)  |
| Scaling | [DEVSECOPS at Scale](#DEVOPS-AT-SCALE)  |

<br />
<br />
<br />
<br />
<br />
<br />

## DEVSECOPS OVERVIEW

DevSecOps is the philosophy of integrating security practices within the DevOps process. DevSecOps involves creating a 'Security as Code' culture with ongoing, flexible collaboration between release engineers and security teams.


![DEVSECOPS IMAGE](IMAGES/DS1.png)

<br />
<br />
<br />
<br />
<br />
<br />
<br />


## DEVSECOPS MISCONCEPTIONS


![DEVSECOPS IMAGE](IMAGES/DS2.png)

<br />
<br />
<br />
<br />
<br />
<br />
<br />

## DEVOPS AT SCALE
![DEVSECOPS IMAGE](IMAGES/DS3.png)


<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />
<br />

# COMPLIANCE 


### [JUMP TO TOP](#NAVIGATION) 

| Topic | Quick Jump |
| ------------- | ------------- |
| CSA STAR  | [Cloud Auditing](#CSA-STAR)  |
| ISO 27001 | [Policy Auditing](#AISO-27001)  |
| Leidos   | [Accredited Testing](#LEIDOS)  |
| PCI 3.2   | [Data Security Standard](#PCI-DSS)  |
| PCI HIPAA   | [HIPAA](#PCI-HIPAA)  |

<br />
<br />
<br />
<br />


## CSA STAR 

![STAR IMAGE](IMAGES/star.png)
  
[Testing Overview](https://cloudsecurityalliance.org/star/levels/) 


CSA star is a **Open Certification Framework** for an organisations cloud controls.

CSA STAR Self-Assessment is a complimentary offering that documents the security controls provided by various cloud computing offerings, thereby helping users assess the security of cloud providers they currently use or are considering using. Cloud providers either submit a completed Consensus Assessments Initiative Questionnaire (CAIQ), or submit a report documenting compliance with the Cloud Controls Matrix (CCM). This information then becomes publicly available, promoting industry transparency and providing customer visibility into specific provider security practices.

Three main levels:

1. Self Assesment 
2. Third Party Audit
3. Continuous Audit


**Level one** organizations can submit one or both of the security and privacy self-assessments. **Level two** Organizations looking for a third-party audit can choose from one or more of the security and privacy audits and certifications. An organization’s location, along with the regulations and standards it is subject to will have the greatest factor in determining which ones are appropriate to pursue.

<br />
<br />

## ISO 27001 


![ISO IMAGE](https://images.squarespace-cdn.com/content/v1/5bfda3a52714e561f6834c22/1557497262455-PTEX1JT48SQHD5CHHBF3/ke17ZwdGBToddI8pDm48kNBhxsR5AixTPaSt36FQjZRZw-zPPgdn4jUwVcJE1ZvWQUxwkmyExglNqGp0IvTJZamWLI2zvYWH8K3-s_4yszcp2ryTI0HqTOaaUohrI8PIGWonAD8CCw7nDqU_Mkbm1m15vfiG_IfUBAoG80XVMVo/Blog-Product+Uopdates-ISO27001-Cover.png)

[ISO DEFINITION](https://whatis.techtarget.com/definition/ISO-27001)

ISO 27001 is a specification for an information security management system (ISMS). An ISMS is a framework of policies and procedures that includes all legal, physical and technical controls involved in an organisation's information risk management processes.

ISO 27001 uses a topdown, risk-based approach and is technology-neutral. The specification defines a six-part planning process:

1. Define a security policy.
2. Define the scope of the ISMS.
3. Conduct a risk assessment.
4. Manage identified risks.
5. Select control objectives and controls to be implemented.
6. Prepare a statement of applicability.


ISO 27002 contains 12 main sections:

1. Risk assessment
2. Security policy
3. Organization of information security
4. Asset management
5. Human resources security
6. Physical and environmental security
7. Communications and operations management
8. Access control
9. Information systems acquisition, development and maintenance
10. Information security incident management
11. Business continuity management
12. Compliance


<br />
<br />

## LEIDOS

![LEIDOS](http://www.asdnews.com/NewsImages/b/35929/37176_O.jpg)

[Testing Overview](https://www.leidos.com/competencies/cyber/accredited-testing-evaluation)


- Common Criteria
- FIPS 140-2
- GSA FIPS 201& NIST PIV
- SCAP
- TWIC
- CONSULTING
- SCAP
- TWIC 

The Leidos Accredited Testing & Evaluation Laboratory is comprised of two industry leading laboratories: Common Criteria and FIPS 140-2. Both are accredited by the National Voluntary Laboratory Accreditation Program (NVLAP Lab Code: 200427-0) and provide IT security evaluation and testing services for commercial companies to meet their federal and international sales acquisition requirements. Our labs have in aggregate certified more than 1,000 commercial products.

<br />
<br />

## PCI DSS
### PCI 3.2

The Payment Card Industry Security Standards Council (PCI SSC) has published a
new version of the industry standard that businesses use to safeguard payment data
before, during and after purchase. 

![PCI 3.2](https://www.pcicomplianceguide.org/wp-content/uploads/2014/03/pci-dss-compliant.jpg)

[Resource Guide](https://www.pcisecuritystandards.org/pdfs/PCI_DSS_Resource_Guide_(003).pdf)


PCI DSS requirements apply to all organizations that store, process, or transmit cardholder data. PCI HIPAA compliance is about addressing specific, finite requirements to safeguard the integrity of financial information. PCI HIPAA compliance focuses heavily on network and data security.


## PCI HIPAA 

![PCI HIPAA](https://ix-cdn.brightedge.com/images/32040/32040_e6d1ac6290d74318b79b8f902c272beb_1521135571.png)

[Home Page](https://pcihipaa.com/)


PCI DSS requirements apply to all organizations that store, process, or transmit cardholder data. PCI HIPAA compliance is about addressing specific, finite requirements to safeguard the integrity of financial information. PCI HIPAA compliance focuses heavily on network and data security.