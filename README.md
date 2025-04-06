<p align="center">
<img src="https://i.imgur.com/pU5A58S.png" alt="Microsoft Active Directory Logo"/>
</p>

<h1>On-premises Active Directory Deployed in the Cloud (Azure)</h1>
This tutorial outlines the implementation of on-premises Active Directory within Azure Virtual Machines.<br />


<h2>Video Demonstration</h2>


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory Domain Services
- PowerShell

<h2>Operating Systems Used </h2>

- Windows Server 2022
- Windows 10 (21H2)

<h2>High-Level Deployment and Configuration Steps</h2>

- Step 1
- Step 2
- Step 3
- Step 4

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/iy4OZ3C.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 A directory service developed by Microsoft that is used to manage and organize the resources in a network. It helps administrators control access to resources, such as computers, printers, files, and users, within a Windows domain network. AD is most commonly used in enterprise environments to provide centralized management, security, and organization of network resources.
</p>
<br />

<p>
<img src="https://i.imgur.com/Z7evTrE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 These are servers that store the Active Directory database and manage all domain-related activities such as login authentication, group policy enforcement, and directory searches.  A domain is a logical grouping of network resources (users, computers, printers, etc.) under a single administrative umbrella. It acts as a boundary for security and policy management.
</p>
<br />

<p>
<img src="https://i.imgur.com/1S1cS81.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
It manages user accounts and groups. Users are individual accounts, while groups are collections of users that can be managed together for example, assigning permissions to a group of users rather than individually. Group policies are used to enforce security settings and configurations across user and computer accounts. Policies can be applied at various levels, such as domain, site, or organizational unit.
</p>
<br />

<p>
<img src="https://i.imgur.com/IZKGzXN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Wireshark capturing network packets, decoding them, and displaying the details in a human-readable format. It works at the data link layer (Layer 2) and higher in the OSI model, meaning it can capture everything from Ethernet frames to application-layer protocols like HTTP, DNS, FTP, and more, Once captured, Wireshark decodes the packet's data based on the protocol (e.g., TCP, IP, HTTP, etc.), and shows it in a detailed, layered format.
</p>

