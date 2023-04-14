# Tutorials Point Online Python Compiler Remote Code Execution (RCE) Vulnerability
This repository contains a proof-of-concept (PoC) script that demonstrates a remote code execution (RCE) vulnerability in the Tutorials Point Online Python Compiler.

## CVE Fields
CVE ID
```
TBD
```
### Description
The Tutorials Point Online Python Compiler is vulnerable to a remote code execution attack. An attacker can exploit this vulnerability by submitting a Python script that contains malicious code. The vulnerability exists because the compiler does not properly sanitize user input, allowing an attacker to execute arbitrary commands on the server where the compiler is hosted.

### CVSS Score
The Common Vulnerability Scoring System (CVSS) score for this vulnerability is currently being calculated and will be updated in this README when it is available.

### CWE ID
CWE-78: Improper Neutralization of Special Elements used in an OS Command ('OS Command Injection')

### Affected Software
Tutorials Point Online Python Compiler (https://www.tutorialspoint.com/online_python_compiler.php)

### Vulnerability Type
Remote Code Execution (RCE)

### Vendor Response
As of the creation of this PoC, Tutorials Point has not responded to notifications of this vulnerability. It is unclear if the vendor has a security disclosure program.

### Impacts
An attacker who successfully exploits this vulnerability can run arbitrary commands on the server where the Tutorials Point Online Python Compiler is hosted. This can lead to the theft of sensitive data, installation of malware or ransomware, and disruption of normal operations.

### Solution(s)
To mitigate this vulnerability, Tutorials Point should properly sanitize user input before executing any commands. This can be done by using a combination of input validation and sanitization techniques such as whitelist filtering, input length limiting, and input type validation. Additionally, Tutorials Point should implement a security disclosure program that encourages responsible disclosure of security vulnerabilities by providing a secure channel for reporting and promptly addressing reported vulnerabilities. Users of Tutorials Point Online Python Compiler should exercise caution and refrain from submitting scripts with potentially malicious code.
