<h1>Understanding the IPv4 Header</h1>



<h2>Description</h2>
In this lab, I learned about the IPv4 header. Wireshark is an open-source software tool that captures packets and analyzes protocol information from that captured data.
<br />



<h2>Environments Used </h2>

- <b>Windows Server 2016 Standard</b> 

<h2>Languages and Utilities</h2>

- <b>Wireshark</b>

<h2>Program walk-through:</h2>

<p align="center">
From the desktop open Wireshark application: <br/>
<img src="https://i.postimg.cc/1Rg3NqjW/Screen-Shot-2022-06-23-at-11-18-54-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
<br />
In the Wirshark Network Analyzer window, select the Ethernet0 interface and click the start Capturing packets icon (sharkfin icon) </br>
<img src="https://i.postimg.cc/xC3yvZ82/Screen-Shot-2022-06-23-at-11-20-10-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
  
<br />
After waiting a few minutes stop capturing packets</br>
<img src="https://i.postimg.cc/V62rbBB8/Screen-Shot-2022-06-23-at-11-23-58-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
  
<br />
In the filter toolbar, type "ssdp" in the Apply a display filter text box and press enter to see only http packets:  <br/>
<img src="https://i.postimg.cc/SQZ1HXQp/Screen-Shot-2022-06-23-at-11-25-02-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
<p align="center">
In the Packet list pane, select any SSDP protocol packet: <br/>
<img src="https://i.postimg.cc/x8v96KHM/Screen-Shot-2022-06-23-at-11-31-40-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
<br />
Under the Packet details pane, you will observe Internet Protocol Version 4: </br>
<img src="https://i.postimg.cc/P5QkpWn8/Screen-Shot-2022-06-23-at-11-33-10-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
  
<br />
Click Internet Protocol Version 4 to expand the packet to observe its fields: <br/>
<img src="https://i.postimg.cc/QMKkYbNF/Screen-Shot-2022-06-23-at-11-36-59-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
  
<br>
click file and save:  <br/>
<img src="https://i.postimg.cc/m2xD7yJd/Screen-Shot-2022-06-23-at-11-39-04-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
<br />
  
  
  



<p align="center">
Save file to have a record of the IPv4 information: <br/>
<img src="https://i.postimg.cc/T3MDY6T3/Screen-Shot-2022-06-23-at-11-41-41-AM.png" height="80%" width="80%" alt="Creating a Subinterface on a Router and Assigning an IP Address Steps"/>
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
