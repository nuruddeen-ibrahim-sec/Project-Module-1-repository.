============================================================
        CYBERSECURITY RECONNAISSANCE & INFORMATION
                     GATHERING PROJECT
============================================================

                    NETWORKWALKS
                  PROJECT MODULE 1

Author: Muhammad Ibrahim
GitHub Username: nuruddeen-ibrahim-sec
Training: NetworkWalks Cybersecurity Training
Platform: Kali Linux
Target: networkwalks.com
Project Type: Authorized Educational Cybersecurity Training


============================================================
1. PROJECT OVERVIEW
============================================================

This repository contains my practical cybersecurity work for
Module 1 of the NetworkWalks cybersecurity training.

The purpose of this project is to practice fundamental
reconnaissance and information-gathering techniques used
during the early stages of a cybersecurity assessment.

The module focuses on collecting publicly observable
information, performing basic DNS reconnaissance, identifying
web technologies, inspecting HTTP responses, detecting
possible Web Application Firewalls, and documenting the
results professionally.

Each task contains:

1. A TXT file containing the command output.
2. A PNG file containing screenshot evidence.
3. A dedicated folder for organized documentation.


============================================================
2. AUTHORIZED TARGET
============================================================

Target:

    networkwalks.com

Purpose:

    Authorized educational cybersecurity reconnaissance.

All activities documented in this repository are intended for
authorized training and educational purposes.


============================================================
3. PROJECT OBJECTIVES
============================================================

The objectives of this module are to develop practical
experience with:

- Domain reconnaissance
- WHOIS information gathering
- Web technology identification
- DNS investigation
- DNS enumeration
- HTTP response inspection
- HTTP header analysis
- WAF detection
- Evidence collection
- Technical documentation
- GitHub project organization
- Professional cybersecurity reporting


============================================================
4. PROJECT STRUCTURE
============================================================

Project Module 1 Repository
|
|-- README.md
|
|-- Task-1-WHOIS/
|   |-- whois.txt
|   `-- whois.png
|
|-- Task-2-WhatWeb/
|   |-- whatweb.txt
|   `-- whatweb.png
|
|-- Task-3-NSLookup/
|   |-- nslookup.txt
|   `-- nslookup.png
|
|-- Task-4-CURL/
|   |-- curl.txt
|   `-- curl.png
|
|-- Task-5-WAFW00F/
|   |-- wafw00f.txt
|   `-- wafw00f.png
|
`-- Task-6-DNSRecon/
    |-- dnsrecon.txt
    `-- dnsrecon.png


============================================================
5. RECONNAISSANCE WORKFLOW
============================================================

                    AUTHORIZED TARGET
                           |
                           v
                    +-------------+
                    |    WHOIS    |
                    +------+------+
                           |
                           v
                    +-------------+
                    |   WhatWeb   |
                    +------+------+
                           |
                           v
                    +-------------+
                    |  NSLookup   |
                    +------+------+
                           |
                           v
                    +-------------+
                    |    CURL     |
                    +------+------+
                           |
                           v
                    +-------------+
                    |  WAFW00F    |
                    +------+------+
                           |
                           v
                    +-------------+
                    |  DNSRecon   |
                    +------+------+
                           |
                           v
                  EVIDENCE COLLECTION
                           |
                           v
                    GITHUB REPORTING


============================================================
6. TASK 1 - WHOIS RECONNAISSANCE
============================================================

Objective:

WHOIS reconnaissance was performed to collect publicly
available registration and domain information associated with
the authorized target.

Evidence files:

Text Output:
Task-1-WHOIS/whois.txt

Screenshot:
Task-1-WHOIS/whois.png


GitHub Links:

[WHOIS Command Output](Task-1-WHOIS/whois.txt)

[WHOIS Screenshot](Task-1-WHOIS/whois.png)


Screenshot:

![WHOIS Reconnaissance](Task-1-WHOIS/whois.png)


Purpose:

WHOIS can provide publicly available information such as:

- Domain registration information
- Registrar information
- Domain status
- Registration dates
- Expiration information
- Name servers
- Registry information


Expected Learning:

This task demonstrates how publicly available domain
registration information can contribute to the initial
reconnaissance phase of a security assessment.


============================================================
7. TASK 2 - WHATWEB
============================================================

Objective:

WhatWeb was used to identify technologies and web-related
information exposed by the authorized website.

Evidence files:

Text Output:
Task-2-WhatWeb/whatweb.txt

Screenshot:
Task-2-WhatWeb/whatweb.png


GitHub Links:

[WhatWeb Command Output](Task-2-WhatWeb/whatweb.txt)

[WhatWeb Screenshot](Task-2-WhatWeb/whatweb.png)


Screenshot:

![WhatWeb Technology Detection](Task-2-WhatWeb/whatweb.png)


Purpose:

WhatWeb can help identify technologies such as:

- Web servers
- Web frameworks
- Content Management Systems
- JavaScript libraries
- Web application technologies
- HTTP headers
- Other technology fingerprints


Expected Learning:

This task demonstrates how technology fingerprinting can help
a security professional understand the publicly observable
technology stack of a web application.


============================================================
8. TASK 3 - NSLOOKUP
============================================================

Objective:

NSLookup was used to investigate DNS information associated
with the authorized target.

Evidence files:

Text Output:
Task-3-NSLookup/nslookup.txt

Screenshot:
Task-3-NSLookup/nslookup.png


GitHub Links:

[NSLookup Command Output](Task-3-NSLookup/nslookup.txt)

[NSLookup Screenshot](Task-3-NSLookup/nslookup.png)


Screenshot:

![NSLookup DNS Reconnaissance](Task-3-NSLookup/nslookup.png)


Purpose:

DNS reconnaissance can help identify publicly observable
information such as:

- IP addresses
- DNS records
- Name servers
- Domain resolution
- Other DNS-related information


Expected Learning:

This task demonstrates the importance of DNS information
during the reconnaissance phase of a cybersecurity assessment.


============================================================
9. TASK 4 - CURL
============================================================

Objective:

CURL was used to make an HTTP/HTTPS request to the authorized
target and inspect the server response.

Evidence files:

Text Output:
Task-4-CURL/curl.txt

Screenshot:
Task-4-CURL/curl.png


GitHub Links:

[CURL Command Output](Task-4-CURL/curl.txt)

[CURL Screenshot](Task-4-CURL/curl.png)


Screenshot:

![CURL HTTP Reconnaissance](Task-4-CURL/curl.png)


Purpose:

CURL can be used to inspect information including:

- HTTP status codes
- Response headers
- Redirect behavior
- Server responses
- Security-related HTTP headers
- Basic web server behavior


Expected Learning:

This task demonstrates how HTTP responses can provide useful
information during web reconnaissance.


============================================================
10. TASK 5 - WAFW00F
============================================================

Objective:

WAFW00F was used to determine whether a Web Application
Firewall could be detected in front of the authorized target.

Evidence files:

Text Output:
Task-5-WAFW00F/wafw00f.txt

Screenshot:
Task-5-WAFW00F/wafw00f.png


GitHub Links:

[WAFW00F Command Output](Task-5-WAFW00F/wafw00f.txt)

[WAFW00F Screenshot](Task-5-WAFW00F/wafw00f.png)


Screenshot:

![WAFW00F Detection](Task-5-WAFW00F/wafw00f.png)


Purpose:

WAFW00F can help security professionals determine whether
a Web Application Firewall may be protecting a web application.

Where possible, it can also help identify the WAF technology.


Expected Learning:

This task demonstrates how defensive technologies can be
identified during reconnaissance without attempting to bypass
or defeat the security control.


============================================================
11. TASK 6 - DNSRECON
============================================================

Objective:

DNSRecon was used to perform DNS reconnaissance against the
authorized target.

Evidence files:

Text Output:
Task-6-DNSRecon/dnsrecon.txt

Screenshot:
Task-6-DNSRecon/dnsrecon.png


GitHub Links:

[DNSRecon Command Output](Task-6-DNSRecon/dnsrecon.txt)

[DNSRecon Screenshot](Task-6-DNSRecon/dnsrecon.png)


Screenshot:

![DNSRecon Enumeration](Task-6-DNSRecon/dnsrecon.png)


Purpose:

DNSRecon can assist with identifying publicly observable
DNS information including:

- DNS records
- Name servers
- Address records
- Mail servers
- Other DNS-related information


Expected Learning:

This task demonstrates how DNS information can be collected
and documented as part of the reconnaissance process.


============================================================
12. COMPLETE EVIDENCE TABLE
============================================================

| Task | Tool      | TXT Evidence | PNG Evidence |
|------|-----------|--------------|--------------|
| 1    | WHOIS     | whois.txt    | whois.png    |
| 2    | WhatWeb   | whatweb.txt  | whatweb.png  |
| 3    | NSLookup  | nslookup.txt | nslookup.png |
| 4    | CURL      | curl.txt     | curl.png     |
| 5    | WAFW00F   | wafw00f.txt  | wafw00f.png  |
| 6    | DNSRecon  | dnsrecon.txt | dnsrecon.png |


============================================================
13. DIRECT EVIDENCE LINKS
============================================================

TASK 1 - WHOIS

Text:
Task-1-WHOIS/whois.txt

Image:
Task-1-WHOIS/whois.png


TASK 2 - WHATWEB

Text:
Task-2-WhatWeb/whatweb.txt

Image:
Task-2-WhatWeb/whatweb.png


TASK 3 - NSLOOKUP

Text:
Task-3-NSLookup/nslookup.txt

Image:
Task-3-NSLookup/nslookup.png


TASK 4 - CURL

Text:
Task-4-CURL/curl.txt

Image:
Task-4-CURL/curl.png


TASK 5 - WAFW00F

Text:
Task-5-WAFW00F/wafw00f.txt

Image:
Task-5-WAFW00F/wafw00f.png


TASK 6 - DNSRECON

Text:
Task-6-DNSRecon/dnsrecon.txt

Image:
Task-6-DNSRecon/dnsrecon.png


============================================================
14. TOOLS USED
============================================================

WHOIS
Purpose:
Domain registration and publicly available domain
information gathering.

WhatWeb
Purpose:
Web technology and application fingerprinting.

NSLookup
Purpose:
DNS lookup and domain resolution.

CURL
Purpose:
HTTP/HTTPS request and response inspection.

WAFW00F
Purpose:
Web Application Firewall detection.

DNSRecon
Purpose:
DNS reconnaissance and enumeration.

Kali Linux
Purpose:
Cybersecurity testing and training environment.

GitHub
Purpose:
Project documentation, evidence organization, and
cybersecurity portfolio development.


============================================================
15. EVIDENCE DOCUMENTATION
============================================================

Each task contains two primary evidence files.

TXT FILE:

The TXT file contains the command-line output collected during
the practical exercise.

PNG FILE:

The PNG file contains a screenshot showing the command
execution and/or results.

This approach provides both textual and visual evidence for
each practical task.


============================================================
16. LEARNING OUTCOMES
============================================================

After completing this module, I practiced the following
cybersecurity skills:

1. Understanding the reconnaissance phase of a security
   assessment.

2. Collecting publicly available domain information.

3. Performing basic DNS reconnaissance.

4. Identifying web technologies.

5. Inspecting HTTP responses and headers.

6. Understanding DNS information.

7. Identifying potential WAF technologies.

8. Organizing cybersecurity evidence.

9. Documenting technical activities professionally.

10. Using GitHub to organize and present cybersecurity work.

11. Developing a structured approach to information gathering.

12. Practicing responsible and authorized security testing.


============================================================
17. METHODOLOGY
============================================================

The project followed a structured reconnaissance methodology.

STEP 1:
Identify the authorized target.

STEP 2:
Collect publicly available domain information using WHOIS.

STEP 3:
Identify publicly observable web technologies using WhatWeb.

STEP 4:
Investigate DNS resolution using NSLookup.

STEP 5:
Inspect HTTP/HTTPS responses using CURL.

STEP 6:
Check for possible Web Application Firewall technology using
WAFW00F.

STEP 7:
Perform DNS reconnaissance using DNSRecon.

STEP 8:
Save command results as TXT evidence.

STEP 9:
Capture screenshots as PNG evidence.

STEP 10:
Organize all evidence into separate GitHub directories.

STEP 11:
Document the complete project in README.md.


============================================================
18. PROFESSIONAL EVIDENCE STANDARD
============================================================

For every task, the repository maintains:

[✓] Correct task directory

[✓] Command output

[✓] Screenshot evidence

[✓] Descriptive filename

[✓] README link

[✓] Organized documentation

This structure makes the project easier for an instructor,
reviewer, or cybersecurity professional to understand.


============================================================
19. ETHICAL AND LEGAL CONSIDERATIONS
============================================================

Cybersecurity reconnaissance must always be performed
responsibly and within an authorized scope.

The activities documented in this repository are intended for
authorized educational cybersecurity training.

The techniques demonstrated should only be used against:

- Systems owned by the tester
- Authorized training environments
- Cybersecurity laboratories
- CTF environments
- Systems where explicit permission has been provided


Unauthorized scanning, enumeration, exploitation, or testing
may violate laws, organizational policies, or terms of service.

No attempt should be made to bypass security controls or gain
unauthorized access.


============================================================
20. PROJECT STATUS
============================================================

PROJECT MODULE 1

Repository:
[✓] Created

README:
[✓] Documentation prepared

Task 1 - WHOIS:
[✓] Evidence structure prepared

Task 2 - WhatWeb:
[✓] Evidence structure prepared

Task 3 - NSLookup:
[✓] Evidence structure prepared

Task 4 - CURL:
[✓] Evidence structure prepared

Task 5 - WAFW00F:
[✓] Evidence structure prepared

Task 6 - DNSRecon:
[✓] Evidence structure prepared

Screenshots:
[✓] Prepared for upload

Command Outputs:
[✓] Prepared for upload

GitHub Documentation:
[✓] Completed


============================================================
21. FINAL REPOSITORY CHECKLIST
============================================================

Before submitting the project, verify that the repository
contains the following:

[ ] README.md

[ ] Task-1-WHOIS/whois.txt
[ ] Task-1-WHOIS/whois.png

[ ] Task-2-WhatWeb/whatweb.txt
[ ] Task-2-WhatWeb/whatweb.png

[ ] Task-3-NSLookup/nslookup.txt
[ ] Task-3-NSLookup/nslookup.png

[ ] Task-4-CURL/curl.txt
[ ] Task-4-CURL/curl.png

[ ] Task-5-WAFW00F/wafw00f.txt
[ ] Task-5-WAFW00F/wafw00f.png

[ ] Task-6-DNSRecon/dnsrecon.txt
[ ] Task-6-DNSRecon/dnsrecon.png


============================================================
22. IMPORTANT FILE-NAMING RULE
============================================================

DO NOT change the following image names.

WHOIS:
whois.png

WhatWeb:
whatweb.png

NSLookup:
nslookup.png

CURL:
curl.png

WAFW00F:
wafw00f.png

DNSRecon:
dnsrecon.png


DO NOT change the task folder names.

Task-1-WHOIS

Task-2-WhatWeb

Task-3-NSLookup

Task-4-CURL

Task-5-WAFW00F

Task-6-DNSRecon


The README uses these exact paths so that GitHub can display
the screenshots automatically.


============================================================
23. FINAL PROJECT SUMMARY
============================================================

This Module 1 project demonstrates practical experience with
the information-gathering stage of cybersecurity.

The project combines six reconnaissance techniques:

    WHOIS
       +
    WhatWeb
       +
    NSLookup
       +
    CURL
       +
    WAFW00F
       +
    DNSRecon
       =
    RECONNAISSANCE EVIDENCE


The results are organized into individual task folders,
with command output and screenshot evidence for each task.

The project also demonstrates the ability to document
technical cybersecurity activities in a structured GitHub
repository.


============================================================
24. AUTHOR
============================================================

Muhammad Ibrahim

Cybersecurity Student

NetworkWalks Cybersecurity Training

GitHub Username:
nuruddeen-ibrahim-sec


============================================================
25. MODULE 1 COMPLETION
============================================================

                    MODULE 1

        RECONNAISSANCE & INFORMATION GATHERING

                     COMPLETED


Target:
networkwalks.com

Environment:
Kali Linux

Tools:
WHOIS
WhatWeb
NSLookup
CURL
WAFW00F
DNSRecon

Evidence:
TXT command outputs
PNG screenshots

Documentation:
GitHub README.md


============================================================
                    END OF PROJECT
============================================================

"Cybersecurity is not only about finding vulnerabilities.
It is also about understanding systems, collecting evidence,
documenting your work, and operating responsibly within an
authorized scope."

============================================================
