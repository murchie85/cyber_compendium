# CYBER SECURITY COMPENDIUM

| Topic | Quick NAVIGATION |
| ------------- | ------------- |
| FRAMEWORKS   | [Frameworks](#FRAMEWORKS)  |
| CYBER TOOLS  | [Cyber](#CYBER-TOOLS)  |
| KT RESOURCES  | [Knowledge Resources](#KNOWLEDGE-RESOURCES)  |
| NEXT-GEN   | [INTELLIGENT INTELLIGENCE](#NEXT-GEN-INTELLIGENT-INTELLIGENCE)  |

  
  
![TITLE IMAGE](head.jpg)
<br />

# FRAMEWORKS 

| Topic | Quick Jump |
| ------------- | ------------- |
| NIST FRAMEWORK   | [NIST](#NIST-FRAMEWORK)  |
| Open Web Application Security Project  | [OWASP](#Open-Web-Application-Security-Project-(OWASP))  |

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

## Open Web Application Security Project (OWASP) 

- OWASP  [OWASP](https://www.owasp.org/index.php/Main_Page)

  
<br />
<br />
<br />
<br />

# CYBER TOOLS 

| Topic | Quick Jump |
| ------------- | ------------- |
| Hack the Box   | [HTB](#Hack-The-Box)  |


  
<br />
<br />

## Hack The Box
- Hack the Box [here](https://www.hackthebox.eu/)
- Hack the Box tutorial [here](https://0xrick.github.io/hack-the-box/teacher/)

  
<br />
<br />
<br />
  
# KNOWLEDGE RESOURCES 
  
| Topic | Quick Jump |
| ------------- | ------------- |
| Signature Wrapping  | [SIGNATURE WRAPPING ATTACK](#SIGNATURE-WRAPPING-ATTACK)  |
| AWESOME PENTEST  | [AWESOME PENTEST](#AWESOME-PENTEST)  |
| How to NMAP   | [MAPPING PORTS](#HOW-TO-NMAP)  |

<br />
<br />
<br />


## SIGNATURE WRAPPING ATTACK
- Signature Wrapping [Here](https://www.ws-attacks.org/XML_Signature_Wrapping) 
  

## AWESOME PENTEST
    
- AWESOME-PENTEST  [PENTEST](https://github.com/enaqx/awesome-pentest)

  
## HOW TO NMAP
  

  
- NMAP How to [NMAP](https://hackertarget.com/nmap-tutorial/)




<br />
<br />
<br />
  
# NEXT-GEN INTELLIGENT INTELLIGENCE  

| Topic | Quick Jump |
| ------------- | ------------- |
| Next Gen Architectures  | [ROBUST AI FRAUD ARCHITECTURES](#ROBUST-AI-FRAUD-ARCHITECTURES)  |
| Dynamic GCP  | [GCP RECOMMENDATIONS](#GCP-RECOMMENDATIONS)  |
| ML INJECTION  | [NEURALNET INJECTION](#ML-INJECTION )  |
| ML N-MAP   | [ML N-MAP ](#ML-N-MAP  )  |
| TURBOCHARGED SQL INJECTION  | [SQL-INJECTION-TURBOCHARGING ](#SQL-INJECTION-TURBOCHARGING )  |





<br />
<br />

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


## AI FOR DEFENCE

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
