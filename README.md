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

<h2>Deployment and Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/iy4OZ3C.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Active Directory (AD) is a directory service developed by Microsoft that helps manage and organize resources within a network. I can enables administrators to control access to resources such as computers, printers, files, and users within a Windows domain environment. AD is widely used in enterprise settings to provide centralized management, security, and organization of network resources. By using leveraging AD, I can organiza and enforce security policies, streamline user authentication, and simplify the management of large-scale IT infrastructures.
</p>
<br />

<p>
<img src="https://i.imgur.com/Z7evTrE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In Domain controllers I can store the Active Directory database and oversee all domain-related activities, such as login authentication, group policy enforcement, and directory searches. A domain is a logical grouping of network resources, including users, computers, and printers, within a unified administrative framework. It serves as a boundary for security and policy management, ensuring that only authorized users and devices can access network resources. Domain controllers also play a crucial role in maintaining the integrity and availability of the domain by replicating data across multiple servers for redundancy and fault tolerance.
</p>
<br />

<p>
<img src="https://i.imgur.com/1S1cS81.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I can manages user accounts and groups, streamlining administrative tasks. Users are individual accounts, while groups are collections of users that can be managed collectively, allowing me easy permission assignments to groups instead of individuals. Group policies are then used to enforce security settings and configurations across both user and computer accounts. These policies can be applied at different levels, such as domain, site, or organizational unit, ensuring consistent and centralized control. By using group policies, administrators can maintain a secure and compliant network environment while simplifying management tasks.
</p>
<br />

<p>
<img src="https://i.imgur.com/IZKGzXN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
In Wireshark I can captures network packets, decodes them, and displays the details in a human-readable format. Operating at the data link layer (Layer 2) and higher in the OSI model, Wireshark I can capture everything from Ethernet frames to application-layer protocols like HTTP, DNS, FTP, and more. Once I captured it, Wireshark decodes the packet's data based on the relevant protocol (e.g., TCP, IP, HTTP) and presents it in a detailed, layered format. This allows network administrators and security professionals to analyze network traffic, troubleshoot issues, and identify potential security vulnerabilities effectively.
</p>

<p>
<img src="https://i.imgur.com/qx72D5M.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I can use the ping command to test the connection between the computer and another device, such as a website or server, on a network. I can sends small packets of data and measures the time it takes to receive a response. If the device responds, it indicates that the connection is functioning properly; if not, there could be a network issue. It’s a quick and simple way to check if a device is online and to assess the speed of the connection. Additionally, ping can help diagnose latency issues or packet loss in the network.
</p>

