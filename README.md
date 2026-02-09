<h1>Configuring VLANs & Trunking Lab</h1>

<h2>Description</h2>
In this lab, I configured VLANs with their proper access, voice, and trunking ports, implementing static and dynamic trunking alongside learning a few new commands.
<br />


<h2>Tools & Technologies Used</h2>

- <b>Cisco Packet Tracer</b> 
- <b>VLANs & Trunking</b> 
- <b>Static & Dynamic Trunking</b>

<h2>Objectives</h2>

- <b>Implementing the VLAN Table & Assigning Access Ports to VLANs.</b>
- <b>Configuring the SVIs for the 3 Switches and assigning their corresponding IPs.</b>
- <b>Configure Static & Dynamic Trunking on the listed switches.</b>

<h2>Background: Viewing the Addressing Table + Objectives + VLAN Table</h2>

<p align="center">
<br/>
<img src="https://i.imgur.com/GIvJQ7t.png" height="80%" width="80%" alt="#1"/>
<br/>
<img src="https://i.imgur.com/ieD8DYE.png" height="80%" width="80%" alt="#2"/>
<br/>
________________________________________________________________________________________________________
<h2>Step 1: Creating the VLANs & Assigning Access Ports</h2>

 <p align="center">
1) SWB: I created the respected VLANs on SWB and assigning the connected ports F0/1, F0/2, F0/3 as access ports and to their VLANs.<br/> 
<img src="https://i.imgur.com/GVotGpo.png" height="80%" width="80%" alt="#3"/>
<br />
2) SWC: I created the respected VLANs on SWC and assigning the connected ports F0/1, F0/2, F0/3 as access ports and to their VLANs.<br/>
<img src="https://i.imgur.com/LxskFEh.png" height="80%" width="80%" alt="#4"/>
<br />
3) SWC: I configued F0/4 to their access vlan 10 and to the voice vlan 40.<br/>
<img src="https://i.imgur.com/Emk81IF.png" height="80%" width="80%" alt="#5"/>
<br />
________________________________________________________________________________________________________
<h2>Step 2: Configuring SVIs on Switches</h2>

<p align="center">
1) SWA: I configured the 1st SVI on SWA according to the Addressing Table<br/>
<img src="https://i.imgur.com/qZrPVGb.png" height="80%" width="80%" alt="#6"/>
<br />
<p align="center">
2) SWB: I configured the 1st SVI on SWB according to the Addressing Table<br/>
<img src="https://i.imgur.com/9mkTOA5.png" height="80%" width="80%" alt="#7"/>
<br />
<p align="center">
3) SWC: I configured the 1st SVI on SWC according to the Addressing Table<br/>
<img src="https://i.imgur.com/RtE3UHq.png" height="80%" width="80%" alt="#8"/>
<br />
________________________________________________________________________________________________________
<h2>Step 3: Configuring Static Trunking</h2>

<p align="center">
1) SWA: I configured G0/1 as a trunk port, setting it to nonegotiate to make it a static trunk and setting the native vlan 100. <br/>
<img src="https://i.imgur.com/LHfzIj3.png" height="80%" width="80%" alt="#9"/>
<br />
<p align="center">
2) SWB: I configured G0/1 as a trunk port, setting it to nonegotiate to make it a static trunk and setting the native vlan 100. <br/>
<img src="https://i.imgur.com/LHfzIj3.png" height="80%" width="80%" alt="#10"/>
<br />
________________________________________________________________________________________________________
<h2>Step 4: Configuring Dynamic Trunking</h2>

<p align="center">
1) SWA: I configured G0/2 as a dynamic trunk using the command "switchport mode dynamic desirable".<br/>
<img src="https://i.imgur.com/XHTIHXY.png" height="80%" width="80%" alt="#11"/>
<br />
<p align="center">
2) SWA/SWC: Configuring G0/2 trunk native to vlan 100 to fix Native VLAN Conflicts.<br/>
<img src="https://i.imgur.com/zh3UBvL.png" height="80%" width="80%" alt="#12"/>
<br />
________________________________________________________________________________________________________
<h2>OVERVIEW:</h2>
<p align="center">
Implementing VLANs & Trunking Lab:  <br/>
<p align="left">
<b> 1) Created multiple VLANs | Assigned switch ports to the correct VLANs.</b>
<p align="left">
<b> 2) Configured Access/Voice/Trunk Ports | Set up Static & Dynamic Trunking.</b>
<p align="left">
<b> 3) Refreshed and reinforced more VLANs/Trunking commands. </b>
<br />

- https://github.com/galbachjr
________________________________________________________________________________________________________
  

</p>
