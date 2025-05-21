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

<h2>Program walk-through:</h2>

<p align="center">
Set up the "domain controller" VM running Windows Server 2019 <br/>
<img src="https://i.imgur.com/5Vd8JjL.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
