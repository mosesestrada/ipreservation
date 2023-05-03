<p align="center">
 <img src="https://i.imgur.com/cLOWZFd.jpg" height="80%" width="80%" alt="VM logo"/>
</p>

<h1>Creating an IP reservation</h1>


<h2>Description</h2>

Get ready for an awesome demonstration! Today, we're going to create an IP reservation for my brand new Laserjet Printer. By reserving a specific IP address for this printer, we're guaranteeing it always has the same address in our network. This simple reservation will eliminate any potential connectivity headaches and ensure that all devices in my network can quickly and easily locate the printer. So let's get started!
<br />

<h2>Environments Used </h2>

 <b>Windows Server 2019 </b> <p>
 <b>Hyper-V</b></p>

<h2>Program walk-through:</h2>

<p align="center">


<br />
From the Hyper-V manager, Select your Hyper-V host server. In this example we will highlight ours which is CORPSERVER. Next we will double-click our DHCP server to connect to the VM.
 <br/>
<img src="https://i.imgur.com/xuHGUAu.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
Once our DHCP VM connects. Open server manager then select tools> DHCP
 <br/>
<img src="https://i.imgur.com/hm0Nh6l.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
On the left plane expand your domain > IPV4 > Scope

 <br/>
<img src="https://i.imgur.com/30UkFYa.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
Right-Click Reservations and select new reservation.
<br/>
<img src="https://i.imgur.com/KsxGpCc.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
In the Reservation name field, enter a reservation name
In the IP address field, enter the IP address for the reservation.
In the MAC address field enter the MAC address of your device.
Under supported types select DHCP only. When you are done select Add to create the client reservation.
Select Yes to the DHCP prompt.


 <br/>
<img src="https://i.imgur.com/mS0hoQR.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
 That's it! We are finished! You will now see the completed reservation for our device.
 <br/>
<img src="https://i.imgur.com/SO3clD9.png" height="80%" width="80%" alt="DHCP"/>
<br />
<br />
 I hope you enjoyed this demonstration.
 <br/>
<img src="https://i.imgur.com/yJKNCtj.jpg" height="80%" width="80%" alt="DHCP"/>
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
