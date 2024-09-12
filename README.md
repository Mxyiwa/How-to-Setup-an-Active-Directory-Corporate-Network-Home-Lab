<h1>How-to-Setup-an-Active-Directory-Corporate-Network-Home-Lab</h1>

<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/VN6G1drv/project-adam.webp' border='0' alt='Screenshot-2023-09-05-at-17-54-28'/></a>
<br />

<h2>What is an Elastic SIEM?</h2>
<b>
Elastic SIEM (Security Information and Event Management) is a comprehensive security solution built using the ELK Stack, which includes Elasticsearch, Logstash, and Kibana. These three technologies provide a powerful solution when working with large data sets which enables us defenders to set up SIEM rules to alert us of attacks on our organisation. It is a key component of Elastic Security designed to help organisations detect, prevent, and respond to security threats in real time by collecting and analysing data from various sources across an IT environment.
</b>

<h2>Lab Objectives</h2>
<b>
This lab is the walkthrough of my approach to building an Elastic SIEM lab set up in a home lab environment using Elastic SIEM within a Kali Linux VM, where data is forwarded from the VM to the SIEM through the Elastic Defend agent. In this lab, security events are generated on the Kali Linux VM using Nmap, and these logs are then queried and analysed within the Elastic web interface. To enhance visibility and monitoring, a dashboard is created to visualise the security events, and  an alert system to notify when specific security events are detected.
</b>

<h2>Link to hands on step-by-step guide on how to perform this project</h2>

- <b>https://medium.com/@mxyiwa/how-to-build-an-elastic-siem-lab-8ebd0bd74f28</b>

## Skills Learned / Developed

- <b>Advanced understanding of Elastic SIEM concepts and practical application.</b>
- <b>Ability to generate and recognize attack signatures and patterns.</b>
- <b>Expertise in dashboard creation in the Elastic SIEM to visualise security events and data patterns.</b>
- <b>Proficiency in querying, analysing, and interpreting security event logs.</b>
- <b>Ability to troubleshoot issues during the Elastic Agent installation, such as modifying commands based on archiitecture (x86_64 to arm64).</b>
- <b>Enhanced knolwedge to develop configurations to continuously generate and monitor security events to improve SIEM effectiveness.</b>  

## Tools / Technologies Used

- <b>Parallels VM</b>
- <b>Kali Linux</b>
- <b>Elastic SIEM</b>
- <b>Elastic Defend Agent</b> 

## Steps

- <b>Step 1: Set up an Elastic Account.</b> 
- <b>Step 2: Set up a Kali Linux VM.</b> 
- <b>Step 3: Install Elastic Defend as the Software Agent to Collect Logs and Forward the Audit logs and Telemetry from the Kali Linux VM to the Elastic SIEM.</b> 
- <b>Step 4: Generate Security Events on the Kali Linux VM using Nmap.</b> 
- <b>Step 5: Query and analyse the Security Event logs generated in the Elastic SIEM using the Elastic web interface.</b> 
- <b>Step 6: Create dashboards to visualise the Security Events.</b> 
- <b>Step 7: Create alerts to notify the security events that are detected.</b> 


## Conclusion
<b>In this lab, I learned to build an Elastic SIEM lab that involved setting up a free Elastic account and configuring a Kali Linux VM for data collection using the Elastic Defend agent. This lab was designed to generate security events with Nmap, which were queried and analysed through the Elastic web interface. A dashboard was created to visualise these security events, and an alert system was implemented to provide real-time notifications for detected threats. This lab aimed to gain practical experience in deploying and managing an Elastic SIEM environment, which will enhance my ability to monitor and respond to security incidents effectively. Thanks for reading!</b>

<h2>Elastic SIEM Dashboard after running a Nmap Scan within 30 minutes of deployment</h2>

<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/W41k8xCQ/scan.png' border='0' alt='Screenshot-2023-09-05-at-17-54-28'/></a>
<br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

