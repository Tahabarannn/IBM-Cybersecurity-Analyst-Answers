Quiz 01 – Vulnerability Tools
Q1. Which component of a vulnerability scanner would perform security checks according to its installed plug-ins?

Engine Scanner

Q2. Which component of a vulnerability scanner stores vulnerability information and scan results?

Database

Q3. How does a vulnerability scanner detect internal threats?

By scanning hosts

Q4. In which component of a Common Vulnerability Score (CVSS) would the attack vector be reflected?

Base-Exploitability Subscore

Q5. In which component of a Common Vulnerability Score (CVSS) would confidentiality be reflected?

Base-Impact Subscore
Ezoic

Q6. In which component of a Common Vulnerability Score (CVSS) would exploit code maturity be reflected?

Ezoic
Temporal Score

Q7. In which component of a Common Vulnerability Score (CVSS) would security requirements subscore be reflected?

Environmental Score

Q8. True or False. The US Dept of Defense has produced a number of Security Technical Implementation Guides to show the most secure ways to deploy common software packages such as operation systems, open source software, and network devices. These guides are available to the public and can be freely downloaded.

True

Q9). The Center for Internet Security (CIS) has implementation groups that rank from the least secure to the most secure. Which of these has the least stringent security requirements?

CIS Sub-Controls for small, commercial off-the-shelf or home office software environments.
Port Scanning

Q1. Which three (3) of these is identified by a basic port scanner? (Select 3)

Available services provided by the target system
A list of Open ports on a target system
Active hosts using TCP

Q2. Port numbers 49151 through 65536 are known as what?

Dynamic and Private Ports

Q3. What are the three (3) responses a port scanner might receive when it is scanning a system for open ports? (Select 3)

Closed
Filtered (or blocked)
Open

Q4. Which type of scan is commonly used to check if a working system is at the address indicated and that it is responding?

Ping (ICMP Echo Request)

Q5. Which type of scan sends an empty packet or packet with a different payload for each port scanned. A response is received only for closed ports?

UDP port scan
Ezoic
Network Protocol Analyzers

Q1. Which two (2) of these are other names for a protocol analyzer? (Select 2)

Network analyzer
Packet analyzer

Q2. Which is the most popular packet sniffer used?

WireShark
Vulnerability Assessment Tools Graded Assessment

Q1. Which of these is identified by a basic port scanner?

Ezoic
Open ports

Q2. Port numbers 0 through 1023 are known as what?

Well known ports

Q3. If a port is blocked, what response will be sent to the port scanner?

There will be no response

Q4. Which type of scan notes the connection but leaves the target hanging, i.e. does not reveal any information to the target about the host that initiated the scan?

TCP/Half Open Scan (aka a SYN scan)

Q5. Which two (2) of these are other names for a protocol analyzer? (Select 2)

Sniffer
Traffic analyzer

Q6. True or False. Packet sniffers are used by hackers but have no legitimate place in legitimate network management.

False

Q7. Which component of a vulnerability scanner provides high-level graphs and trend reports for executive leadership?

Report Module

Q8. How does a vulnerability scanner detect external threats?

By scanning internet facing hosts from the Internet

Q9. What are the three (3) components that make up the overall Common Vulnerability Score (CVSS)? (Select 3)

Base
Environmental
Temporal

Q10. In which component of a Common Vulnerability Score (CVSS) would attack complexity be reflected?

Base-Exploitability Subscore

Q11. In which component of a Common Vulnerability Score (CVSS) would integrity be reflected?

Base-Impact Subscore

Q12. In which component of a Common Vulnerability Score (CVSS) would remediation level be reflected?

Temporal Score

Q13. In which component of a Common Vulnerability Score (CVSS) would impact subscore be reflected?

Environmental Score

Q14. True or False. The US Dept of Defense has produced a number of Security Technical Implementation Guides to show the most secure ways to deploy common software packages such as operation systems, open source software, and network devices. These guides are restricted to use by US military agencies only.

False

Q15. The Center for Internet Security (CIS) has implementation groups that rank from the least secure to the most secure. Which of these are required to meet the middle level of security?

“a” and “b” only
Security Architecture Considerations

Q1. True or False. A security architect’s job is to make sure that security considerations dominate other design aspects such as usability, resilience and cost.

False

Q2. Which of these is an aspect of an Enterprise Architecture?

Considers the needs of the entire organization

Q3. Which of these is an aspect of Solution Architecture?

Describes how specific products or technologies are used

Q4. Which three (3) of these are general features of Building Blocks? (Select 3)

Could be an actor, business service, application or data
Package of function defined to meet a business need
Defined boundary, but can work with other building blocks

Q5. Which three (3) of these are Architecture Building Blocks (ABBs)? (Select 3)

Identity and Access Management
Application Security
Data Security

Q6. Which three (3) of these are Solution Building Blocks (SBBs)? (Select 3)

HSM
Certificate Authority
Key Security Manager

Q7. The diagram below shows which type of architecture?

Enterprise Security Architecture

Q8. Solution architectures often contain diagrams like the one below. What does this diagram show?

Architecture overview

Q9. Insecurity architecture, a reusable solution to a commonly recurring problem is known as what?

A pattern
Ezoic
Application Security Techniques and Risks

Q1. Which of these is an application security threat?

Malware

Q2. Failure to use input validation in your application introduces what?

A vulnerability

Q3. Which software development lifecycle is characterized as a top-down approach where one stage of the project is completed before the next stage begins?

Waterfall

Q4. Which form of penetration testing allows the testers complete knowledge of the systems they are trying to penetrate in advance of their attack to simulate an internal attack from a knowledgeable insider?

White Box testing

Q5. Which application testing method requires access to the original application source code?

SAST: Static Application Security Testing

Q6. Which three (3) steps are part of a Supplier Risk Assessment? (Select 3)

Determine the likelihood the risk would interrupt the business
Identify how any risks would impact your organization’s business
Identify how the risk would impact the business

Q7. What type of firewall should you install to protect applications used by your organization from hacking?

A web application firewall (WAF)

Q8. Which type of application attack would include Elevation of privilege, data tampering and luring attacks?

Authorization

Q9. Which type of application attack would include information disclosure and denial of service?

Exception management

Q10. Which one of the OWASP Top 10 Application Security Risks would be occur when untrusted data is sent to an interpreter as part of a command or query?

Injection

Q11. Which one of the OWASP Top 10 Application Security Risks would occur when a poorly configured XML processor evaluates an external entity reference within an XML document allowing the external entity to expose internal files?

XML external entities (XXE)

Q12. Which of these threat modeling methodologies was introduced in 1999 at Microsoft to provide their developer’s a mnemonic that would help them find security vulnerabilities in their products?

STRIDE

Q13. Security standards do not have the force of law but security regulations do. Which one of these is a security regulation?

Gramm-Leach-Bliley Act
Ezoic
DevSecOps & Security Automation

Q1. Which phase of DevSecOps would contain the activities Threat modeling & risk analysis, Security backlog and Architecture & design?

Plan

Q2. Which phase of DevSecOps would contain the activities Continuous component control, Application and infrastructure orchestration, and Data cleansing & retention?

Release, deploy & decommission

Q3. The Release step in the DevSecOps Release, Deploy & Decommission phase contains which of these activities?

Versioning of infrastructure

Q4. The Detect & Visualize step in the DevSecOps Operate & Monitor phase contains which of these activities?

Inventory

Ezoic
Deep Dive into Cross-Scripting

Q1. True or False. Finding a bug in a software product from a major vendor can be very profitable for a security researcher.

True

Q2. Which is the top vulnerability found in common security products?

Cross-site scripting

Q3. True or False. Building software defenses into your software includes: input validation, output sensitization, strong encryption, strong authentication and authorization.

True

Q4. Complete the following statement. Cross-site scripting ____

allows attackers to inject client-side scripts into a web page.

Q5. True or False. A Stored XSS attack is potentially far more dangerous than a Reflected XSS attack.

True

Q6. Cross-site scripting attacks can be minimized by using HTML and URL Encoding. How would a browser display this string?: &lt;b&gt;Test&lt;/b&gt;

<b>Test</b>

Q7. Which is the most effective means of validating user input?

Whitelisting
Ezoic

Quiz 02 – Application Testing Graded Assessment 
Q1. True or False. A security architect’s job is to make sure that security considerations are balanced against other design aspects such as usability, resilience, and cost.

True

Q2. Which of these is an aspect of an Enterprise Architecture?

Maps the main components of a problem space and solution at a very high level.

Q3. Which of these is an aspect of a Solution Architecture?

Shows the internal data and use of reusable or off-the-shelf components

Q4. Which three (3) of these are features of Architecture Building Blocks (ABBs) ? (Select 3)

Product and vendor neutral
Guides the development of a Solution Architecture
Captures and defines requirements such as function, data, and application

Q5. Which three (3) of these are Architecture Building Blocks (ABBs)? (Select 3)

Detect and Respond
Infrastructure and Endpoint Security
Identity and Access Management
Ezoic

Q6. Which three (3) of these are Solution Building Blocks (SBBs) ? (Select 3)

Hardware Token
Privilege Access Manager
Web Application Firewall (WAF)

Q7. The diagram below shows which level of architecture?

Enterprise Security Architecture

Q8. Solution architectures often contain diagrams like the one below. What does this diagram show?

Solution architecture overview

Q9. Solution architectures often contain diagrams like the one below. What does this diagram show?

External context and boundary diagram

Q10. What is lacking in a security architecture pattern that prevents it from being used as a finished design?

The context of the project at hand

Q11. What are the possible consequences if a bug in your application becomes known?

All of the above

Q12. What was the ultimate consequence to Target Stores in the United States from their 2013 data breach in which over 100M records were stolen?

Costs and fines estimated at $1B.

Q13. Select the two (2) top vulnerabilities found in common security products. (Select 2)

Cross-site scripting
Cross-site request forgery

Q14. True or False. If you can isolate your product from the Internet, it is safe from being hacked.

False

Q15. Which three (3) things can Cross-site scripting be used for? (Select 3)

Steal cookies
Harvest credentials
Take over sessions

Q16. True or False. Commonly a Reflect XSS attack is sent as part of an Email or a malicious link and affects only the the user who receives the email or link.

True

Q17. Cross-site scripting attacks can be minimized by using HTML and URL Encoding. How would a browser display this string?

<b>Password</b>

Q18. Which three (3) statements about whitelisting user input are true? (Select 3)

Whenever possible, input should be whitelisted to alphanumeric values to prevent XSS
Whitelisting reduces the attack surface to a known quantity
Special characters should only be allowed on an exception basis

Q19. Which two (2) statements are considered good practice for avoiding XSS attacks (Select 2)

Encode all data output as part of HTML and JavaScript
Use strict whitelists on accepting input
Ezoic

Q20. How would you classify a hactivist group who thinks that your company’s stance on climate change threatens the survival of the planet?

A threat

Q21. Which software development lifecycle is characterized by short bursts of analysis, design, coding and testing during a series of 1 to 4 week sprints?

Agile and Scrum

Q22. Which software development lifecycle is characterized by a series of cycles and an emphasis on security?

Spiral

Q23. Which form of penetration testing allows the testers no knowledge of the systems they are trying to penetrate in advance of their attack to simulate an external attack by hackers with no knowledge of an organizations systems?

Black Box Testing

Q24. Which application testing method requires a URL to the application, is quick and cheap but also produces the most false-positive results?

DAST: Dynamic Security Application Testing

Q25. Which type of application attack would include buffer overflow, cross-site scripting, and SQL injection?

Input validation

Q26. Which type of application attack would include unauthorized access to configuration stores, unauthorized access to administration interfaces and over-privileged process and service accounts?

Configuration management

Q27. Which one of the OWASP Top 10 Application Security Risks would be occur when authentication and session management functions are implemented incorrectly allowing attackers to compromise passwords, keys or session tokens.

Broken authentication

Q28. Which one of the OWASP Top 10 Application Security Risks would be occur when restrictions on what a user is allowed to do is not properly enforced?

Broken access control

Q29. Which of these threat modeling methodologies is integrated seamlessly into an Agile development methodology?

VAST

Q30. Security standards do not have the force of law but security regulations do. Which one of these is a security regulation?

HIPAA

Q31. Which phase of DevSecOps would contain the activities Secure application code, Secure infrastructure configuration, and OSS/COTS validation?

Code & build

Q32. Which phase of DevSecOps would contain the activities Detect & Visualize, Respond, and Recover?

Operate & monitor

Q33. The Deploy step in the DevSecOps Release, Deploy & Decommission phase contains which of these activities?

Creation of Immutable images

Q34. The Respond step in the DevSecOps Operate & Monitor phase contains which of these activities?

Virtual Patching
