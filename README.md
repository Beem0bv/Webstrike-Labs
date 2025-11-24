#  Webstrike-Labs — Network Forensics Investigation
A suspicious file was detected on a company web server. The development team flagged unusual activity and collected a PCAP file for investigation.

## Lab Focus
**Malicious network traffic analysis** using **Wireshark**.  
Includes packet-level inspection, attacker profiling, and vulnerability investigation.



## Q/A

>### Q1: Understanding the geographical origin of the attack aids in geo-blocking measures and threat intelligence analysis. What city did the attack originate from?


>### Q2: Knowing the attacker's user-agent assists in creating robust filtering rules. What's the attacker's user agent?


>### Q3: We need to identify if there were potential vulnerabilities exploited. What's the name of the malicious web shell uploaded?


>### Q4: Knowing the directory where files uploaded are stored is important for reinforcing defenses against unauthorized access. Which directory is used by the website to store the uploaded files?


>### Q5: Identifying the port utilized by the web shell helps improve firewall configurations for blocking unauthorized outbound traffic. What port was used by the malicious web shell?


>### Q6: Understanding the value of compromised data assists in prioritizing incident response actions. What file was the attacker trying to exfiltrate?



## Key Takeaways
- Discovered unauthorized **web shell communication** on port `4444`
- Identified **data exfiltration** attempts through HTTP POST streams
- Applied **packet filtering and payload reconstruction** for forensic insight

## Tools Used
- **Wireshark**
- **CyberDefenders Lab**
- **Git & GitHub**

**Bradley Nicholas Fils-Aimé**   
[LinkedIn](https://linkedin.com/in/bradleyfilsaime)  
[GitHub](https://github.com/BeemObv)
