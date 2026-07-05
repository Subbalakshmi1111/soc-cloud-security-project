Web Application Security Audit — DVWA

Conducted hands-on penetration testing on DVWA (Damn Vulnerable Web Application) identifying and exploiting 4 critical vulnerabilities across OWASP Top 10 categories using Kali Linux.

Vulnerabilities Found:
| Vulnerability | Severity | Impact |
|--------------|----------|--------|
| SQL Injection | Critical | Dumped entire user database using 1' OR '1'='1 payload |
| Command Injection | Critical | Achieved Remote Code Execution — exposed server OS via uname -a |
| Unrestricted File Upload | Critical | Uploaded PHP web shell — confirmed persistent backdoor access |
| XSS Reflected | High | Executed JavaScript in browser — session hijacking possible |

Tools Used:
Kali Linux · DVWA · Firefox · OWASP Top 10 · MITRE ATT&CK

Skills Demonstrated:
- SQL injection exploitation and database enumeration
- Remote Code Execution via command injection
- PHP web shell upload and execution
- XSS payload crafting and browser execution
- OWASP Top 10 vulnerability classification
- MITRE ATT&CK threat mapping
