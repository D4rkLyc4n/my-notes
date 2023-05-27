# HACKING NOTEs
--
## VA TOOLS
--
Nmap|
OpenVAS|
Nikto|
Lynis|
Arachni|
Metasploit|
Wapiti|
Vega|
Skipfish|
OWASP ZAP|
SQLMap|
DirBuster|
Gobuster|
WPScan|
Recon-ng
--
**NMAP**

version scan 'nmap -sV ip'
vuln scan 'nmap --script vuln ip'
all scan '-A'
block request '-Pn'

###To do list 

1.Cross-Site Scripting (XSS): Test for both reflected and stored XSS vulnerabilities, ensuring that user input is properly sanitized and encoded to prevent malicious script execution.

2.SQL Injection (SQLi): Check for SQLi vulnerabilities where untrusted user input is used in database queries. Test for various types of SQL injection, such as UNION-based, error-based, and blind SQLi.

3.Local File Inclusion (LFI) and Remote File Inclusion (RFI): Assess the application for LFI and RFI vulnerabilities that could allow an attacker to include and execute malicious files or disclose sensitive information.

4.Host Header Injection: Test for host header injection vulnerabilities, where an attacker can manipulate the host header to perform various attacks like session fixation, cache poisoning, or server-side request forgery (SSRF).

5.Web Cache Poisoning: Assess if the application's caching mechanisms are properly implemented to prevent cache poisoning attacks, where an attacker can manipulate cached content to serve malicious or unauthorized data.

6.Directory Listing: Check if directory listing is enabled, as it may disclose sensitive information or provide an entry point for further attacks.

7.Authentication and Session Management: Evaluate the application's authentication mechanisms, including password strength, session management, and potential vulnerabilities like session fixation, session hijacking, or session timeout issues.

8.CSRF (Cross-Site Request Forgery): Test if the application is vulnerable to CSRF attacks, where an attacker tricks a user into performing unintended actions on their behalf.

9.File Upload: Assess how the application handles file uploads, checking for potential vulnerabilities such as allowing the execution of malicious files or bypassing file type restrictions.

10.Information Disclosure: Look for any instances of sensitive information disclosure, such as error messages, debug information, or server configuration details, which could aid attackers in their exploitation attempts.
--

To do list

Cross-Site Scripting (XSS): Test for both reflected and stored XSS vulnerabilities, ensuring that user input is properly sanitized and encoded to prevent malicious script execution.

SQL Injection (SQLi): Check for SQLi vulnerabilities where untrusted user input is used in database queries. Test for various types of SQL injection, such as UNION-based, error-based, and blind SQLi.

Local File Inclusion (LFI) and Remote File Inclusion (RFI): Assess the application for LFI and RFI vulnerabilities that could allow an attacker to include and execute malicious files or disclose sensitive information.

Host Header Injection: Test for host header injection vulnerabilities, where an attacker can manipulate the host header to perform various attacks like session fixation, cache poisoning, or server-side request forgery (SSRF).

Web Cache Poisoning: Assess if the application's caching mechanisms are properly implemented to prevent cache poisoning attacks, where an attacker can manipulate cached content to serve malicious or unauthorized data.

Directory Listing: Check if directory listing is enabled, as it may disclose sensitive information or provide an entry point for further attacks.

Authentication and Session Management: Evaluate the application's authentication mechanisms, including password strength, session management, and potential vulnerabilities like session fixation, session hijacking, or session timeout issues.

CSRF (Cross-Site Request Forgery): Test if the application is vulnerable to CSRF attacks, where an attacker tricks a user into performing unintended actions on their behalf.

File Upload: Assess how the application handles file uploads, checking for potential vulnerabilities such as allowing the execution of malicious files or bypassing file type restrictions.

Information Disclosure: Look for any instances of sensitive information disclosure, such as error messages, debug information, or server configuration details, which could aid attackers in their exploitation attempts.
