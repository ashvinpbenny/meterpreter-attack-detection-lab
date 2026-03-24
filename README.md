# meterpreter-attack-detection-lab

### Project Overview

This project simulates a real-world attack scenario and demonstrates how endpoint telemetry can be used to detect and investigate malicious activity using a Security Information and Event Management (SIEM) platform.

In this lab, an attack was simulated using a Meterpreter reverse TCP payload generated from Kali Linux. The payload was executed on a Windows virtual machine, after which system activity was monitored and investigated using Sysmon logs ingested into Splunk.

The goal of this project was to demonstrate the SOC investigation workflow, including identifying indicators of compromise, correlating process activity, and tracing attacker commands executed on the compromised host.

### Lab Environment

Two virtual machines were used:

| Machine    | Role                                  |
| ---------- | ------------------------------------- |
| Kali Linux | Attacker machine                      |
| Windows VM | Victim machine with Sysmon and Splunk |

Network option for both these virtual machines was set to internal network in VirtualBox to create an isolated network.

### Skills Learned

-Simulating attacks using Metasploit and Meterpreter reverse TCP payloads
-Hosting and delivering payloads using a Python HTTP server
-Collecting endpoint telemetry using Sysmon
-Ingesting and analyzing logs in Splunk
-Investigating suspicious activity using queries
-Tracing attacker commands executed through a reverse shell
-Understanding the SOC workflow from attack simulation to detection and investigation

### Tools Used

| Tool                 | Purpose                                             |
| -------------------- | --------------------------------------------------- |
| Kali Linux           | Attack simulation machine                           |
| Metasploit Framework | Payload generation and exploitation                 |
| Python               | Hosting a simple HTTP server to deliver the payload |
| Windows VM           | Target machine                                      |
| Sysmon               | Endpoint telemetry and process logging              |
| Splunk               | Log ingestion and investigation                     |


## Steps
drag & drop screenshots here or use imgur and reference them using imgsrc

Every screenshot should have some text explaining what the screenshot is about.

Example below.

*Ref 1: Network Diagram*
