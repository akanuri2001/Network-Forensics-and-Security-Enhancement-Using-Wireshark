In our project, we created a detailed "how-to" guide using Wireshark to tackle network issues like rogue applications and illicit crypto mining on a LAN. We also made a 10-15 minute video demo to walk through the steps outlined in our guide.

Tools and Techniques We Used:
Wireshark: This open-source network protocol analyzer was essential for capturing and examining network packets in real-time. It helped us gain detailed insight into network behaviors for troubleshooting and security audits.
VirusTotal: We used this online service to scan and analyze files flagged during our Wireshark sessions. It was invaluable in confirming the malicious nature of suspicious files by checking them against various antivirus databases.
Key Procedures:
HTTP Analysis: We focused on spotting suspicious HTTP traffic, such as strange file transfers or connections to malicious domains. This involved filtering and exporting HTTP objects for further investigation.
TCP Analysis: We inspected TCP traffic to find unusual connection patterns or suspicious ports, which could suggest unauthorized access or rogue applications.
DNS Analysis: Our analysis here aimed to identify rogue DNS queries that might indicate malicious activities like command-and-control operations.
UDP and Port Analysis: We examined specific UDP ports for activities related to DNS tunneling, potentially used for data exfiltration.
Findings:
We were able to identify and confirm the presence of malicious files and domains, such as "strongdomainsercerghost.com" and "www.duelmen-naturtrailpark.org," which were associated with rogue applications or malware distribution.
We found no direct evidence of active mining operations or fragmented UDP traffic. However, suspicious connections and DNS queries highlighted potential security threats.
Solutions:
We recommended implementing advanced network monitoring and filtering techniques.
We suggested using domain reputation checks to block communications with known malicious infrastructures.
We advised on deploying endpoint protection and response tools to detect and mitigate threats.
This project demonstrated Wireshark's effectiveness in network security investigations, underscoring the importance of thorough traffic analysis and proactive security measures to identify and prevent potential threats.
