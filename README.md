<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Create A Virtual Machine/Install IIS Server
- Install the Pre-Requisites
- Item 3
- Item 4
- Item 5

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/wHP7HLq.png" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/okgmlbn.png" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a Virtual Machine in Microsoft Azure Portal. The VM will be Windows 10 and have 4vcpus. Once the VM is created, I log in the Remote Desktop Protocol with the VM IP Address and password I set up. After I login the RDP, I must install the IIS Server in Windows with CGI. IIS stands for Internet Information Services. First I bring up the control panel and click on Turn Windows Features On and Off. A window will pop up with plenty of options to check. Check the CGI Box and the Common HTTP Features, then click ok and the server will install that osTicket will run on. To make sure everything is install corectly, go to the browser and type 127.0.0.1 in the address bar. Internet Information Services web page should load up. 127.0.0.1 is a loopback address (localhost) and loopback address allow different programs to run on the same machine. This means I can run a webpage off myself.
</p>
<br />

<p>
<img src="https://i.imgur.com/a89SwNV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/eOdOAo6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To install osTicket I must first install all the Pre-Requisites. First installs will be PHPManager and Rewrite Module which allow configurations and extensions to be ran on IIS server. I must create a folder in the Cdrive name(C:\PHP). Next I download PHP.7.3.8 and extract it into the C:\PHP folder. After that I install VC_redis.x86.exe and MySQL.5.5.62 which is the database for osTicket. After those files are installed, run IIS as the adminstrator. I double click on PHP Manager and register a new PHP from the Cdrive name PHP-CGI. Then I restart the server.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
