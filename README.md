<h1>Active Directory Home Lab</h1>

 

<h2>Description</h2>
After completing my CompTIA A+ and Google IT Support certifications, I wanted to take the next step: applying that knowledge in a practical setting to better prepare for a job in the industry. So I challenged myself to build a home lab environment from scratch and it’s been a great experience!

Using VirtualBox, I set up a small network running Active Directory on Windows Server. From there, I went deeper:

-Configured DHCP scopes and leases to automate IP address assignment across the virtual network <br/>
-Created and managed 1,000 users in Active Directory to simulate a real-world organization structure<br/>
-Practiced user and group policies, DNS setup, and troubleshooting within the lab environment

This project helped me reinforce key IT concepts and get hands-on experience with:

Windows Server & Active Directory administration <br/>
Networking and IP management <br/>
Identity and access control at scale <br/>
Planning and executing IT infrastructure setups <br/>

<br />


<h2>Environments Used </h2>

- <b>Windows 10</b>
-  <b>Windows 10 Server 2019</b>
-  <b>Active Directory</b>
-  <b>Oracle VirtualBox</b> 

<h2>Lab walk-through:</h2>

<p align="center">
Downloaded Windows Server 2019 ISO <br/>
<img src="https://i.imgur.com/di1qWbB.png" height="80%" width="80%" alt="Active Directory Home Lab Steps"/>
<br />
<br />
Set up and configured the "domain controller" VM running Windows Server 2019. Allocated 4GB RAM and 4 CPU cores to the VM to ensure efficient speeds.  <br/>
<img src="https://i.imgur.com/XBcGzyk.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Set up the NAT and Internal Network Adapters <br/>
<img src="https://i.imgur.com/lDniHyU.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/y3wZ6rJ.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>]
<br />
<br />
Inserted "guest additions CD image" for a better user experience naviagting the VM (reduced lag and allowed me to resize the window when needed)<br/>
[<img src="https://i.imgur.com/ZO6clLl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>]
<br />
<br />
Determined which adapter was which using the IPv4 address and renamed them accordingly  <br/>
<img src="https://i.imgur.com/42WOysq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Assigned IP addressing for the internal network. When I set up active directory, it will install DNS automatically. So I will set the DNS address to a loopback address. <br/>
<img src="https://i.imgur.com/TA8Ba6m.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Installed active directory domain services and renamed the server  <br/>
<img src="https://i.imgur.com/AiMfEDL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/91cdr9L.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br />
 <br />
Configured routing so that clients on the private network can access the internet through the domain controller <br/>
<img src="https://i.imgur.com/ZCSuoYA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/Wwtwbcp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/MEHp4oY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Set up DHCP on the domain controller
<img src="https://i.imgur.com/pji5VaX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/2ioB9P4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 <br />
 <br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
