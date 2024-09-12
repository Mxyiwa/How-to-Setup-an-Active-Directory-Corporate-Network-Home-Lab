<h1>How-to-Setup-an-Active-Directory-Corporate-Network-Home-Lab</h1>

<a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/VN6G1drv/project-adam.webp' border='0' alt='Screenshot-2023-09-05-at-17-54-28'/></a>
<br />

<h2>What is an Elastic SIEM?</h2>
<b>
Elastic SIEM (Security Information and Event Management) is a comprehensive security solution built using the ELK Stack, which includes Elasticsearch, Logstash, and Kibana. These three technologies provide a powerful solution when working with large data sets which enables us defenders to set up SIEM rules to alert us of attacks on our organisation. It is a key component of Elastic Security designed to help organisations detect, prevent, and respond to security threats in real time by collecting and analysing data from various sources across an IT environment.
</b>

<h2>Lab Objectives</h2>
<b>
The lab is my walkthrough approach to setting up a mini corporate network in my home lab by designing a simple network architecture with a subnet layout, including a Domain Controller (DC) and client machine, assigning static IPs to the DC and configuring DHCP for clients. Install Windows Server on the DC, promote it to a Domain Controller by installing the AD DS role, and set up a new forest with a domain name. Next, we will configure the internal DNS settings on the DC, set clients to use it as their DNS server, and configure the NAT. We will then use Active Directory Users and Computers to create and manage user accounts and organizational units (OUs), setting permissions and updating attributes as needed. Finally, we will prepare a Windows client machine, join it to the domain by configuring system properties, and verify that it integrates properly with domain resources and policies.
</b>

<h2>Link to hands on step-by-step guide on how to perform this project</h2>

- <b>https://medium.com/@mxyiwa/how-to-setup-an-active-directory-corporate-network-home-lab-3fcc0326bef1</b>

## Skills Learned / Developed

- <b>Gain expertise in configuring and managing Active Directory (AD), including creating and managing users, groups, and organizational units (OUs), and understanding Group Policy for centralised management.</b>
- <b>Learned to install, configure, and manage Windows Server roles and features, including setting up a domain controller and understanding its role in network authentication and authorisation.</b>
- <b>Developed network settings configuration skills for both server and client VMs, including IP addressing, DNS, and network connectivity to ensure seamless communication between domain controller and client machines.</b>
- <b>Gained expertise in the VirtualBox virtualisation platforms, to set up and manage virtual machines, including resource allocation and snapshot management.</b>
- <b>Developed deep understanding for security best practices for AD environments, including setting up and managing permissions, implementing security policies, and securing both the domain controller and client machines.</b>
- <b>Enhanced problem-solving skills by diagnosing and resolving issues related to scope activation, network connectivity, and other aspects of server and client configuration.</b>  

## Tools / Technologies Used

- <b>Oracle's VirtualBox</b>
- <b>Windows 10 ISO Image</b>
- <b>Windows Server 2022 ISO</b>
- <b>Draw.io (_for the network diagram_)</b> 

## Steps

- <b>Step 1: Download VirtualBox and its Extension Pack
- <b>Step 2: Create a Domain Controller Virtual Machine
- <b>Step 3: Configure the DC Virtual Machine
- <b>Step 4: Server Installation on the DC VM
- <b>Step 5: Windows Server Launch & VM Guest Edition Setup Installation
- <b>Step 6: Set Up an IP Address for the Internal Network
- <b>Step 7: Install Active Directory Domain Services (AD DS)
- <b>Step 8: Create a Dedicated Domain Admin Account
- <b>Step 9: Sign in to the Dedicated Domain Admin Account
- <b>Step 10: Install RAS / NAT
- <b>Step 11: Set Up a DHCP Server on the DC VM
- <b>Step 12: Set up the DHCP Scope
- <b>Step 13: Create Users with a Custom PowerShell Script
- <b>Step 14: Create the Client’s (Windows 10) VM
- <b>Step 15: Change the Client’s VM and Join the Domain
- <b>Step 16: Log into the Client’s VM with any of the Created Users

## Conclusion
<b>This lab was designed to simulate how an Active Directory network is created and managed to serve as a centralised system that allows the administrator to manage users, devices, and resources across an organisation’s network and also make sure its IT infrastructure is secured.. Thanks for reading!</b>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

