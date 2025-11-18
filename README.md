<h1>VPN Setup and Usage (Proton VPN)</h1>

<h2>Description</h2>
In this lab we will see how a VPN masks your ip address giving you safer tunneling capabilites from suspicous actors. Although this isn't a fullproof way to keep your information from them it makes it more difficult for someone if they were to try. 
<br />


<h2>Utilities Used</h2>

- <b>Virtual Machines in Azure</b> 

<h2>Environments Used </h2>

- <b>Windows 10 Enterprise Gen 2 (22H2) </b> 

<h2>Create a Vitual Machine:</h2>

<p align="center">
Browse to https://whatismyipaddress.com/ FROM WITHIN YOUR OWN MACHINE and take note of this in a text file: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create a Resource Group:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create a Windows 10 Virtual Machine in another geographic location (try a different country): <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Log into the VM with Remote Desktop. Browse to https://whatismyipaddress.com/ and take note of this in a text file:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
On your actual computer, sign up for the free version of Proton VPN https://account.protonvpn.com/signup?plan=free&language=en:  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Back within your VM, download the Proton VPN client:<br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Login to the VPN (https://account.protonvpn.com/login) and choose a VPN server in yet another country. Browse to https://whatismyipaddress.com/  and take note of this in a text file:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Try browsing to Google, Disney, and/or Amazon and see if there is anything different about the sites in relation to the location of your VPN server. For example, the language or URL may be different:<br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
