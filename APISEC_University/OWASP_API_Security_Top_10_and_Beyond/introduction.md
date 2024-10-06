# What is OWASP API Security Top 10?

The OWASP API Security Top 10 was originally released in Decemeber 2019 and was driven by several key factors:

1. The Rapid Rise of APIs

* A business no longe needs to specialize in all aspects of creating software, instead, they can use the features of software shared by other companies;
* It doesn't matter what programming languages is used in the application, since communications is done through universal protocols;
* Coupling new features is much faster.

2. A Mahor Gap in Security

* The tools and techniques that were used for enterprise vulnerability management programs, web application scanners, and traditional network security monitoring tools were not designed to handle the unique challenges posed by APIs. 

3. A New Leading Attack Vector

* Often, when it comes to the rapid adoption of new technologies, security is an afterthought;
* The rapid adoption of APIs led to a new attack vector that exposes data application functionality;
* Public, Internet-facing, APIs often bypassed all of the security measures that had grown with business over the past decade;
* An attacker no longer needs to go through the classic MITRE cyber kill chain (bypass the firewall, gain entry to the network, pivot to a system containing data, and then exfiltrate that data). Instead, an attacker can use an insecure API and have direct access to sensitive data.

## How is the Top 10 Compiled?

An attacker no longer needs to go through the classic MITRE cyber kill chain (bypass the firewall, gain entry to the network, pivot to a system containing data, and then exfiltrate that data). Instead, an attacker can use an insecure API and have direct access to sensitive data.

* Bug bounty programs incentivize certain types of findings over others
* Bug bounty programs attract participant that represents a small sample of the APIs out in the wild
* Newsworthy incidents often leave security researchers without specific technical details
* Obviously, newsworthy incidents do not include all of the breaches and security incidents that are not reported or publicized

List of bug bounty writeups:
* [PentesterLand Writeups Compilation](https://pentester.land/writeups/)
* [HackerOne Hacktivity](https://hackerone.com/hacktivity) 
* [Awesome Bugbounty Writeups](https://github.com/devanshbatham/Awesome-Bugbounty-Writeups) 

## Mapped to External Sources

The OWASP API Security risks are associated with references to external sources. These sources include Common Weakness Enumeration (CWE), other OWASP projects, and National Institute of Standards and Technology (NIST) guidance. Most of the references involve CWEs. CWEs are a list of common software and hardware vulnerabilities developed by the community and hosted by MITRE. Each CWE is identified by a unique identifier or CWE-ID. This identifier can be used to refer back to a specific vulnerability.

 
| OWASP Top 10                                              | External Reference                                                                          |
| --------------------------------------------------------- | ------------------------------------------------------------------------------------------- |                                 
| API1:2023 Broken Object Level Authorization               | * CWE-285: Improper Authorization                                                           |
|                                                           | * CWE-639: Authorization Bypass Through User-Controlled Key                                 |
| API2:2023 Broken Authentication                           | * CWE-204: Observable Response Discrepancy                                                  |
|                                                           | * CWE-307: Improper Restriction of Excessive Authentication Attempts                        |
| API3:2023 Broken Object Property Level Authorization      | * CWE-213: Exposure of Sensitive Information Due to Incompatible Policies                   |
|                                                           | * CWE-915: Improperly Controlled Modification of Dynamically-Determined Object Attributes   |
|                                                           | * API3:2019 Excessive Data Exposure - OWASP API Security Top 10 2019                        |
|                                                           | * API6:2019 - Mass Assignment - OWASP API Security Top 10 2019                              |           
| API4:2023 Unrestricted Resource Consumption               | * CWE-770: Allocation of Resources Without Limits or Throttling                             |
|                                                           | * CWE-400: Uncontrolled Resource Consumption                                                |
|                                                           | * CWE-799: Improper Control of Interaction Frequency                                        |
|                                                           | * NIST Security Strategies for Microservices-based Application                              |  
| API5:2023 Broken Function Level Authorization             | * CWE-285: Improper Authorization                                                           |
|                                                           | * OWASP Top 10 2013: A7: Missing Function Level Access Control                              |
|                                                           | * OWASP Guidance: Forced Browsing                                                           |
|                                                           | * OWASP Guidance: Access Control                                                            |  
| API6:2023 Unrestricted Access to Sensitive Business Flows | * API10:2019 Insufficient Logging & Monitoring                                              |
|                                                           | * OWASP Automated Threats to Web Applications                                               |  
| API6:2023 Server Side Request Forgery                     | * CWE-918: Server-Side Request Forgery (SSRF)                                               |
|                                                           | * URL confusion vulnerabilities in the wild: Exploring parser inconsistencies, Snyk         |
|                                                           | * Server Side Request Forgery                                                               |
|                                                           | * Server-Side Request Forgery Prevention Cheat Sheet                                        |  
| API8:2023 Security Misconfiguration                       | * CWE-2: Environmental Security Flaws                                                       |    
|                                                           | * CWE-16: Configuration                                                                     |             
|                                                           | * CWE-209: Generation of Error Message Containing Sensitive Information                     |
|                                                           | * CWE-319: Cleartext Transmission of Sensitive Information                                  |
|                                                           | * CWE-388: Error Handling                                                                   |
|                                                           | * CWE-444: Inconsistent Interpretation of HTTP Requests ('HTTP Request/Response Smuggling') |
|                                                           | * CWE-942: Permissive Cross-domain Policy with Untrusted Domains                            |
|                                                           | * NIST Guide to General Server Security                                                     |
|                                                           | * Let's Encrypt: a free, automated, and open Certificate Authority                          |
|                                                           | * OWASP Secure Headers Project                                                              |
|                                                           | * Configuration and Deployment Management Testing - Web Security Testing Guide              |
|                                                           | * Testing for Error Handling - Web Security                                                 |  
| API9:2023 Improper Inventory Management                   | * CWE-1059: Incomplete Documentation                                                        |  
| API10:2023 Unsafe Consumption of APIs                     | * CWE-285: Improper Authorization                                                           |
|                                                           | * CWE-639: Authorization Bypass Through User-Controlled                                     |  
