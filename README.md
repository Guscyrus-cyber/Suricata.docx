# Suricata.docx

Suricata is an open-source, high-performance network security tool designed for intrusion detection and prevention. It is used to monitor and analyze network traffic in real-time to detect and block potential threats. Suricata can handle a variety of network protocols and is capable of inspecting network traffic at high speeds, making it suitable for enterprise environments and security-focused operations. It supports custom rule creation, allows for deep packet inspection, and generates detailed logs and alerts for security analysis.

Lab Overview
This lab involves using Suricata, an open-source intrusion detection and prevention system (IDS/IPS), to analyze network traffic and test custom rules. Working with log files like fast.log and eve.json to identify alerts triggered by specific rules.
 
Scenario
As a security analyst,
1.	Configure Suricata to monitor network traffic using predefined and custom rules.
2.	Analyze traffic captured in a sample.pcap file.
3.	Examine alerts in the fast.log and detailed event data in the eve.json files.
 
Key Files
1.	custom.rules: Contains rules to trigger alerts.
2.	sample.pcap: A packet capture file simulating network traffic.
3.	fast.log: Stores quick alerts when rules are triggered (deprecated but useful for QA checks).
4.	eve.json: Main log file with detailed JSON-formatted event data.
This lab teaches:
•	Writing and testing custom rules in Suricata.
•	Using logs (fast.log and eve.json) to analyze alerts and events.
•	Tools like cat, less, and jq for examining and processing logs.
 
