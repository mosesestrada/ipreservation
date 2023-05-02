<p align="center">
 <img src="https://i.imgur.com/DfR8wiF.jpg" height="80%" width="80%" alt="VM logo"/>
</p>

<h1>Creating an IP exclusion scope</h1>


<h2>Description</h2>

Get ready for an awesome demonstration! Today, we're going to create an IP reservation for my brand new Laserjet Printer. By reserving a specific IP address for this printer, we're guaranteeing it always has the same address in our network. This simple reservation will eliminate any potential connectivity headaches and ensure that all devices in my network can quickly and easily locate the printer. Trust me, this reservation will not only make my life easier, but it'll have you on the edge of your seat with excitement!
<br />

<h2>Environments Used </h2>

 <b>Windows Server 2019 </b> <p>
 <b>Hyper-V</b></p>

<h2>Program walk-through:</h2>

<p align="center">

<br/>

<br />
<br />
From Hyper-V Manager, select  your host server, in this example ours is CORPSERVER. We are going to be double clicking on our DHCP Virtual Machine to connect to it.
 <br/>
<img src="https://i.imgur.com/EVXAv46.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
Once our DHCP VM connects. Open server manager then select tools> DHCP
 <br/>
<img src="https://i.imgur.com/LE4izeo.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
In the DHCP dialogue box expand DHCP> Your Domain> IPV4> Scope. Right click address pool and select "exclusion range".

 <br/>
<img src="https://i.imgur.com/tDBn0VB.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
Enter your desired exclusion range.
<br/>
<img src="https://i.imgur.com/EGqLtiT.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
You will then see your results posted in the prompt. You are finished, close all open boxes.

 <br/>
<img src="https://i.imgur.com/JorxxRM.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
I hope you enjoyed this demonstration.

 <br/>
<img src="https://i.imgur.com/8XiAIhm.jpg" height="80%" width="80%" alt="DHCP"/>
<br />
<br />


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
