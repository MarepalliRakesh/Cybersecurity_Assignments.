# Cybersecurity Assignments

This repository contains the practical assignments completed during my cybersecurity course. Each assignment helped me build hands-on expertise in ethical hacking, vulnerability assessments, penetration testing, and malware analysis.

## Assignments Included:

1. **Advanced Google Hacking Techniques**:
   - Used specialized Google search operators to locate sensitive information publicly available on the internet. This included identifying vulnerable systems, exposed files, and misconfigured web services. The assignment focused on demonstrating how attackers can leverage search engines for reconnaissance.

2. **Video Search Engines Information Gathering**:
   - Explored video search engines like YouTube and other platforms to extract information that could be useful for a hacker, such as tutorials, company-related videos, or security talks. This assignment was about leveraging unconventional sources for gathering intelligence.

3. **FTP Search Engines Information Gathering**:
   - Conducted searches on FTP search engines like NAPALM FTP Indexer to identify misconfigured FTP servers that could lead to data exposure. Learned how attackers target improperly secured FTP servers to extract valuable information.

4. **IoT Search Engines Information Gathering**:
   - Used specialized search engines such as Shodan and Censys to gather information on IoT devices connected to the internet. The focus was on identifying unsecured IoT devices, analyzing their vulnerabilities, and understanding how they can be exploited.

5. **NetBIOS Enumeration using Windows Command-line Utilities**:
   - Performed NetBIOS enumeration using built-in Windows command-line tools like `nbtstat`. This process allowed me to gather information about network shares, system names, and logged-in users on a local network, which can be used to identify vulnerabilities.

6. **NetBIOS Enumeration with NSE Script**:
   - Used the Nmap Scripting Engine (NSE) to automate NetBIOS enumeration. The script gathered detailed information about exposed NetBIOS services, making it easier to map out the network and find potential weaknesses in configuration.

7. **Vulnerability Research using Exploit Sites**:
   - Investigated multiple exploit databases such as Exploit-DB to find vulnerabilities related to specific software. This assignment developed my ability to search for known exploits and map them to systems or applications I’m testing.

8. **Traffic Interception using Burp Suite**:
   - Used Burp Suite to intercept and analyze HTTP/HTTPS traffic. This assignment involved capturing web traffic between a client and server, identifying sensitive data like session tokens or credentials in transit, and testing the security of web applications.

9. **Vulnerability Research with ZAP**:
   - Conducted vulnerability scanning and research using OWASP ZAP. The assignment involved setting up a web application, scanning it for vulnerabilities such as cross-site scripting (XSS) and SQL injection, and providing detailed reports on the findings.

10. **Malware/Trojan Creation using msfvenom/Metasploit**:
    - Created a malware payload using the msfvenom tool from the Metasploit Framework. The payload was designed to demonstrate how attackers could generate malicious executables to compromise systems. I also tested the payload in a controlled environment to analyze its impact.

11. **Malware Analysis using IDA/Ghidra**:
    - Performed malware analysis using IDA Pro and Ghidra to reverse engineer a sample of malware. The goal was to understand how the malware operates, what systems it targets, and what actions it takes once executed, such as stealing information or creating backdoors.

12. **File Dependency Identification using Dependency Walker**:
    - Used Dependency Walker to analyze the dependencies of an executable file. This helped in identifying which dynamic link libraries (DLLs) were required for the program to run, and could expose potential vulnerabilities if any of the DLLs were insecure or outdated.

13. **String Search using BinText**:
    - Used BinText to extract human-readable strings from binary files. This technique is often used in malware analysis to discover hidden commands, URLs, or other hardcoded data that can provide clues about the malware’s functionality.

14. **Online Malware Scanning with VirusTotal**:
    - Uploaded suspected malware files to VirusTotal for analysis. VirusTotal aggregates multiple antivirus scanners to provide a detailed report on whether a file is malicious and what malware signatures it matches. This assignment enhanced my skills in quickly identifying malware through online services.

15. **Sniffing Users’ Credentials using Social-Engineer Toolkit (SET)**:
    - Used the Social-Engineer Toolkit (SET) to perform credential sniffing. This involved setting up a fake login page to capture usernames and passwords from unsuspecting users, demonstrating how attackers can use social engineering techniques to steal credentials.

16. **Phishing using ShellPhish**:
    - Deployed a phishing attack using ShellPhish, a tool designed to create phishing pages that mimic legitimate login screens. This assignment involved sending fake login pages to victims and capturing their credentials, showcasing the effectiveness of phishing attacks.

17. **DoS Attack (SYN Flooding) with Metasploit**:
    - Performed a SYN flood attack using Metasploit to overwhelm a target system’s resources, making it unavailable for legitimate users. The assignment demonstrated how denial-of-service attacks can cripple network resources by sending a flood of SYN requests to a server.

18. **DoS Attack using hping3**:
    - Launched a DoS attack using `hping3`, a network packet crafting tool. This task involved sending a high volume of TCP packets to a target system to disrupt its normal functioning. It showed how attackers exploit network protocols to cause service disruption.

19. **DDoS Attack using HOIC**:
    - Executed a Distributed Denial of Service (DDoS) attack using High Orbit Ion Cannon (HOIC). The attack involved multiple systems targeting a single host to overwhelm it with traffic, simulating a large-scale attack. This assignment provided insights into how DDoS attacks are conducted and the defenses required to mitigate them.

## Tools Used:
- **Burp Suite**
- **Metasploit Framework**
- **IDA Pro**
- **Ghidra**
- **OWASP ZAP**
- **Social-Engineer Toolkit (SET)**
- **VirusTotal**
- **hping3**
- **HOIC**
- **BinText**
- **Dependency Walker**

Each of these assignments helped strengthen my practical skills in areas such as reconnaissance, vulnerability research, traffic interception, malware analysis, and denial-of-service attacks. 

