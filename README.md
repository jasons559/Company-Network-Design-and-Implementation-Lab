<h1>Enterprise Network Design+Implementation Lab</h1>


<h2>Description</h2>
<p>In this project, I designed an enterprise network for a trading floor support center. The network design connects six departments,across three floors within the building. Each floor consists of two departments, with 120 expected users per department. The goal of this project, was to design a hierarchical network model to meet current business needs, and future expansion, while incorporating redundancy at each layer.</p> 

<b>Network components:</b>8 switches, 2 routers, 2 ISPS, DNS, DHCP, and E-mail servers

<b>Additional devices:</b>PCs, printers, laptops, and tablets, with wireless connectivity. 

<p><b>1st Floor:</b> Sales and Marketing+ Human Resources/Logistics
<b>2nd Floor:</b> Finance and Accounting+ Administrator/Public Relations
<b>3rd Floor:</b> ICT+Server Room</p>

<b>Process and Configuration Steps:</b>
<ul>
<li>Configured basic settings for all intermediary and end devices, such as hostname assignment, console and enable passwords, banner messaging, and IP domain lookup disabling.</li>
<li>SSH configuration on all routers and layer 3 switches, for remote login</li> 
<li>VLAN assignment for all departments, with access and trunk ports on 12 and 13 switches </li>
<li>Configured switchport security to the Finance Department</li> 
<li>Subnetting using address table+ Interface IP addressing for layer 3 switches and routers.  </li>
<li>Applied OSPF routing protocol to advertise departments on routers, and multi-layer switches</li>
<li>Statically assigned IP adresses to server room devices, and configured DHCP pools</li>
<li>Multi-layer switch configuration for inter-VLAN routing,on 13 switches. Plus DHCP helper addresses </li>
<li>Added wireless network configuration for laptops and tablets</li>
<li>Port Address Translation (PAT), and access control lists</li>
access and port trunking,
</ul>
<br />


<h2>Utilities Used</h2>

- <b>Cisco Packet Tracer</b> 


<h2>Environments Used </h2>

- <b>MAC OS</b> 

<h2>Network Screenshots:</h2>

<p align="center">
Launch the utility: <br/>
<img src="https://i.imgur.com/62TgaWL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
@@ text in purple (and bold)@@
```
--!>
