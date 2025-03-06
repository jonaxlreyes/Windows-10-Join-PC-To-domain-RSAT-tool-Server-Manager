<h1>Installing Windows 10, Joining the Domain, and Configuring RSAT Tools</h1>

 

<h2>Description</h2>
In this phase of my IT helpdesk home lab, I will install Windows 10 on a virtual machine to simulate a client workstation in an enterprise environment. This will allow me to practice configuring and managing user devices within an Active Directory domain.

Once Windows 10 is installed, I will join the PC to the domain, enabling centralized authentication and policy management through Active Directory. This process will help me understand domain-based network administration and common IT support tasks, such as troubleshooting domain login issues.

Additionally, I will install and configure the Remote Server Administration Tools (RSAT) on Windows 10. RSAT provides IT administrators with tools to manage Active Directory, Group Policy, and other server roles remotely.
By completing this step, I will gain hands-on experience in domain management, user administration—critical skills for IT support and system administration.
<br />


<h2>Utilities Used</h2>

- <b>VirtualBox</b> 

<h2>Installing Windows 10</h2>

<p align="center">
Launch the VirtualBox: <br/>
<img src="https://i.imgur.com/2RLTEtE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Install Windows 10:  <br/>
<img src="https://imgur.com/Vd9F0M5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/jE508An.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enable Administrator:  <br/>
<img src="https://imgur.com/y5DosJo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/5z9qUbp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Logout then Sign-in as Administrator:  <br/>
<img src="https://imgur.com/qc0A8f2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/5z9qUbp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h2>Adding RSAT Tools</h2>

<p align="center">
Add Optional Feature: <br/>
RSAT tools gives me the ability to have Active Directory User and Computers on a Windows 10 Machine:
<img src="https://imgur.com/dNPmiiJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h2>Configure my Server 2016 IP</h2>

<p align="center">
Change my Server 2016 to static IP: <br/>
<img src="https://imgur.com/kX8CPiy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Change network setting to Host-only Adapter : <br/>
<img src="https://imgur.com/SZIvNFT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Static IP is set : <br/>
<img src="https://imgur.com/TxO9CW2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<h2>Joining my Windows 10 to the domain</h2>
  
<p align="center">
Change my Windows 10 to static IP also and connect to the domain: <br/>
<img src="https://imgur.com/kX8CPiy.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/u7NqQzb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Change computer settings to join the domain : <br/>
<img src="https://imgur.com/KvYKw6H.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/KvYKw6H.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Static IP is set and connected to the domain : <br/>
<img src="https://imgur.com/70WXJ88.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://imgur.com/tC0wVZn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Windows 10 can now access Active Directory: <br/>
<img src="https://imgur.com/QecQRrc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
