<h1>Virtual Home Lab SetUp</h1>

<h2>Project Overview</h2>
This project documents the creation of my Virtual home lab used for security/IT future project practice's. The environment simulates an enterprise network consisting of a Windows workstation, Ubuntu server, Kali Linux attacker machine. The lab allows me to safely perform attack simulations, collect Windows logs and Server Logs, and other projects etc.
<br />

<h2>Lab Objectives </h2>

- <b>Build a Virtual Lab Environment</b>

<h2>Network Architecture</h2>
 <img src="https://i.imgur.com/E1Y2N4H.jpeg"/>

<h2>Set-Up walk-through:</h2>

<p align="center">
(Installed Oracle VirtualBox and created the virtual lab environment for cybersecurity testing) <br/>
 Installed VirtualBox on my windows Pc: <br/>
<img src="https://i.imgur.com/O7DqtGj.png"/>
Make sure Virtualization is Enabled before moving any further by opening Task Manager and go to cpu, look for Virtualization saying enable. if it say disable then go into bios and enable it from your comupter (google how to get there because each bios is different set up): <br/>
 <img src="https://i.imgur.com/e673p3a.png"/>
 After going through the install process the Main Screen pops up that i will be setting my Lab up in: <br/>
 <img src="https://i.imgur.com/92C7IhW.png"/>
<br />
<br />
 So next step is installing all the VM for this Lab Environment, Im going to be install Ubuntu Server, Windows 10 Desktop(Victims Pc):<br/>
 <img src="https://i.imgur.com/M0qXARY.png"/>
 <img src="https://i.imgur.com/qmbOjEy.png"/>
 <img src="https://i.imgur.com/ZZ6DhkH.png"/>
<br/>
<br />
After installing both VM'S (Server & Desktop) im are going to import them into virtual machine <br/>
 Click New <br/>
 1: Give it A Name <br/>
 2: Click On ISO and click "other.." since we have our own install ISO <br/>
 3: Navigate where you install your ISO to then Select the ISO (Got to do this step again since only one per isntall) <br/>
 4: By Progressing the base memory I set it to 4096 Mb enough to run the VM's smoothly with out taking a lot on my Host when running <br/>
 5: i put the CPU to 2 for both server and desktop VM'S <br/>
 6: I set my VM storage to 50GB because to run the set up for the VM's it takes half that storage to install properly while i need a little extra to install stuff on it <br/>
 7: Then click finish <br/>
 Now i got both VMs into virtual box: <br/>
<img src="https://i.imgur.com/xXwk8AE.png"/>
<img src="https://i.imgur.com/yyAPi4B.png"/>
<img src="https://i.imgur.com/94ps8MK.png"/>
<img src="https://i.imgur.com/U65KCCO.png"/>
<img src="https://i.imgur.com/QiceXQ9.png"/>
<img src="https://i.imgur.com/lPiXOkf.png"/>
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
@@ text in purple (and bold)@@
```
--!>
