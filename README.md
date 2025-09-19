Detailed Description:
This repository contains a structured vulnerability assessment conducted as part of the Security Officer Trainee assignment. The assessment focuses on evaluating the security posture of www.itsecgames.com through multiple stages:

a.Information Gathering: DNS resolution, server IP identification, and metadata collection.
b.Port & Service Scanning: Identification of open ports, running services, and version detection using Nmap.
c.Web Application Security Analysis: Detection of web vulnerabilities, misconfigurations, and missing security headers using Nikto and cURL.
d.SSL/TLS Assessment: Evaluation of certificate health, protocol support, and cipher strength using SSLScan.
e.Technology & Version Enumeration: Identification of CMS, frameworks, and software versions with WhatWeb to cross-check for known CVEs.
f.Evidence & Screenshots: Screenshots and tool outputs documenting findings.
g.Prioritized Findings & Recommendations: Vulnerabilities ranked by risk level with actionable mitigation steps.

Repository Contents:

/scans      -> Tool outputs (Nmap, Nikto, SSLScan, WhatWeb)
/screenshots -> Screenshots of web application, banners, headers, and tools
/report     -> Markdown vulnerability report summarizing findings and recommendations
metadata.txt -> Pre-scan information (target, IP, DNS)


Objective:
To demonstrate a hands-on approach to vulnerability assessment, providing a structured report suitable for management review and actionable remediation.

Tools Used:
1.nslookup
2.Nmap
3.Nikto
4.SSLScan
5.WhatWeb
6.OWASP Zap


Outcome:
1.Identification of outdated software, CVEs, misconfigurations, and SSL/TLS weaknesses
2.Prioritized vulnerability list with mitigation recommendations
3.Professional report ready for submission and GitHub portfolio
