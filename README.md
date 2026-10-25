<h1>Packet Tracer LAN Home Lab</h1>


<h2>Description</h2>
This lab will be simulating a small office network with three wired computers, one printer, and a wireless laptop, all connected to the same LAN. The router will provide DHCP to all devices and connectivity will be tested.
<br />


<h2>Languages and Utilities Used</h2>
 
- <b>Cisco Packet Tracer</b>


<h2>Program walk-through:</h2>

<p align="center">
Add all of the end devices: 3 PCs, 1 printer, and 1 wireless laptop.
<img src="https://imgur.com/vVX6b4Y.png" height="80%" width="80%" alt=/>  
<br/>
<br/>
Add all networking devices: 1 switch, 1 router, 1 wireless router
<img src="https://imgur.com/n8M3eu4.png" height="80%" width="80%" alt=/>
<br />
<br />
Use straight through cable to connect PCs, printer, and router to the switch. Straight through will be used to connect devices that are not alike. Use first available ports.
<img src="https://imgur.com/p2T9sT1.png" height="80%" width="80%" alt=/>
<br />
<br />
Since they are like devices, use a copper crossover cable to connect the router to the internet port on the wireless router.
<img src="https://imgur.com/u0QyZCk.png" height="80%" width="80%" alt=/>
<br />
<br />
Optional step, provide IP addressing schemes to make configuring IPs easier later.
<img src="https://imgur.com/IMJcVpI.png" height="80%" width="80%" alt=/>
<br />
<br />
Configure the default gateway on the router for the wired network. 
<img src="https://imgur.com/nlYRM9O.png" height="80%" width="80%" alt=/>
<br />
<br />
Configure gateway for wireless network and save configurations.
<img src="https://imgur.com/xtC1J14.png" height="80%" width="80%" alt=/>
<br />
<br />
Enable/open the router ports for both wired and wireless networks. Once finished, icons will turn green
<img src="https://imgur.com/J62yUSa.png" height="80%" width="80%" alt=/>
<br />
<br />
<img src="https://imgur.com/3O5BRi2.png" height="80%" width="80%" alt=/>
<br />
<br />
Configure and set up DHCP for the wired and wireless networks. Name accordingly and use ip schemes you thought of earlier.
<img src="https://imgur.com/5XU6c4G.png" height="80%" width="80%" alt=/>
<br />
<br />
To check, click onto a PC, enable DHCP, and it will say that DHCP request was successful. Confirm on all PCs.
<img src="https://imgur.com/bcKTcMD.png" height="80%" width="80%" alt=/>
<br />
<br />
Open wireless router and change SSID in the gui, after renaming save changes.
<img src="https://imgur.com/xNRxz9h.png" height="80%" width="80%" alt=/>
<br />
<br />
In the wireless security tab, change the security mode and add a password for the wireless router. 
<img src="https://imgur.com/BL7oKQg.png" height="80%" width="80%" alt=/>
<br />
<br />
Open physical tab in the laptop. Drag and drop wifi connector to the side of the laptop.
<img src="https://imgur.com/52mJ4Yh.png.png" height="80%" width="80%" alt=/>
<br />
<br />
<img src="https://imgur.com/emGorXA.png" height="80%" width="80%" alt=/>
<br />
<br />
In the desktop tab, click PC wireless and connect the laptop to the wireless router using the password you gave.  
<img src="https://imgur.com/ee99mln.png" height="80%" width="80%" alt=/>
<br />
<br />
<img src="https://imgur.com/4cqnwgn.png" height="80%" width="80%" alt=/>
<br />
<br />
The link information tab will confirm if you have successfully connected.
<img src="https://imgur.com/OhfJK8g.png" height="80%" width="80%" alt=/>
<br />
<br />
Set an ip address for the printer. The ip will be static in order for the printer to always keep the same address.
<img src="https://imgur.com/axwDS4p.png" height="80%" width="80%" alt=/>
<br />
<br />
Lastly, enter the command prompt from any pc and ping the address for the printer to check connectivity.
<img src="https://imgur.com/uT9GGco.png" height="80%" width="80%" alt=/>
 
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
