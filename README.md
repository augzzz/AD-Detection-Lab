# AD-Detection-Lab

## Goal
This goal of this project was to set up an Active Directory home lab that included Splunk, Kali Linux, and Atomic Red Team for simulating and detecting attacks. This hands-on experience was designed to explore how a domain environment works and learn how to generate, ingest, and analyze logs within a SIEM to simulate real-world attack scenarios.

### Skills Learned
- Basic understanding of SIEM concepts and practical application.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize attack signatures and patterns.
- Intermediate knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills within a simulated scenario.

### Tools Used
- Security Information and Event Management (SIEM) system for log ingestion and analysis.
- Network analysis tools for capturing and examining network traffic.
- Telemetry generation tools to create realistic network traffic and attack scenarios.
- Open source library of tests for adversary simulation and defense validation.

## Steps
1) Build a logical diagram of the virtual network.
   
2) Install virtual machines.
   - Windows Server
   - Windows 10
   - Kali Linux
   - Splunk
     
3) Install and configure software.
   - Sysmon
   - Splunk
     
4) Configure Active Directory.
   - Promote server to a domain controller.
   - Add users and groups to domain.
   - Join target PC to domain.
     
5) Generate telemetry with Kali Linux and Atomic Red Team tests.
   - Use Kali machine to run brute force attacks (Crowbar) targeting a domain user.
   - Install Atomic Red Team and run various tests.
     
6) Analyze and query generated telemetry using Splunk.

## Screenshots

![Screenshot 2024-06-25 213026](https://github.com/augzzz/AD-Detection-Lab/assets/51249119/c3a62b62-13a9-41f3-ba16-88047774cef6)

<i>Ref1: Network Diagram </i>

![Screenshot 2024-06-25 182500](https://github.com/augzzz/AD-Detection-Lab/assets/51249119/9e9699ba-b081-48ad-86ef-d4dc5e3e271a)

<i>Ref2: Splunk Query </i>
