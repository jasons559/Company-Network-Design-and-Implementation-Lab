<h1>Enterprise Network Design+Implementation Lab</h1>


<h2>Description</h2>
<p>In this project, I designed and configured an enterprise network for a trading floor support center. The network design connects six departments, across three floors within the building. Each floor consists of two departments, with 120 expected users per department. The goal of this project was to design a hierarchical network model, to meet current business needs and future expansion, while incorporating redundancy at each layer.</p> 

<b>Network components:</b>8 switches, 2 routers, 2 ISPS, DNS, DHCP, and E-mail servers

<b>Additional devices:</b>PCs, printers, access points,laptops, and tablets, with wireless connectivity. 

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
<li>Statically assigned IP adresses to server room devices,configured DHCP server, and created pools for 5 departments</li>
<li>Inter-VLAN routing for layer 3 switches. Plus DHCP helper addresses </li>
<li>Wireless network configuration,with WPA2-PSK authentication, for laptops and tablets</li>
<li>Port Address Translation(PAT),access control lists,and default static route configurations</li>

</ul>
<br />


<h2>Utilities Used:</h2>

- <b>Cisco Packet Tracer</b> 


<h2>Environments Used: </h2>

- <b>MAC OS</b> 

<h2>Screenshots:</h2>

<p align="center">
Enterprise Network (full view): <br/>
 <img src="https://github.com/jasons559/Company-Network-Design-and-Implementation-Lab/blob/546ae814f7bfa835dd2740e253335b43e2ec6ae9/images/Enterprise_Network_Full.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Core Router 1:  <br/>
<img src="https://github.com/jasons559/Company-Network-Design-and-Implementation-Lab/blob/432b9df69b7f05dc19d3e506ea6dc3d63915b729/images/Core_RT1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Multi-Layer Switch  1: <br/>
<img src="https://github.com/jasons559/Company-Network-Design-and-Implementation-Lab/blob/310386878ae37aa434101d3abd1a6c7304579cfb/images/Mulit-layer_SW1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Finance Department Switch:  <br/>
<img src="https://github.com/jasons559/Company-Network-Design-and-Implementation-Lab/blob/79109996ea0df4af26a9fcf6653afc8b16a41445/images/Finance_SW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
DHCP Server:  <br/>
<img src=    height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wireless Connectivity for Laptops and Tablets:  <br/>
<img src=     height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
