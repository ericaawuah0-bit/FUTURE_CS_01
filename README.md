# FUTURE_CS_01

## Cybersecurity Web Scan Project

This project demonstrates basic cybersecurity reconnaissance techniques using Nmap and browser developer tools.

### Tools Used
- Nmap
- Google Chrome Developer Tools
- GitHub

### Step 1: Nmap Scan
A service version scan was performed on the test site:

testphp.vulnweb.com

Command used:
nmap -sV testphp.vulnweb.com

Result:
The scan identified that port 80 is open and the server is running nginx version 1.19.0.

### Step 2: Web Application Analysis
Using Chrome Developer Tools, the Network tab was inspected to view HTTP headers and server responses.

Findings:
The server header confirms the web server is nginx/1.19.0.

### Purpose
This project demonstrates how security analysts gather information about web servers during the reconnaissance phase of a security assessment.

### Screenshots
Screenshots of the scan results and HTTP header analysis are stored in the screenshots folder.
