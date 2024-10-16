# osticket-prereqs
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

<h2>Set up Azure virtual machine/h2>

<h2></h2>
<h4>Locate Azure resources and create a Virtual machine</h4>
<img src="https://i.imgur.com/vKxX3hk.png"/>
<h4>Select the resource group that has already been created</h4>
<img src="https://i.imgur.com/Lwbp8Hd.png">
<h4>Select a VCPU size of 4</h4>
<img src="https://i.imgur.com/l7cBgKA.png">
Select RDP protocol
<img src="https://i.imgur.com/TJEPh9Q.png">
<h4>In "Networking" select the newly configured virtual network for this machine.</h4>
<img src="https://i.imgur.com/fm3ahTp.png">
<h4>After reviewing everything we can simply click create and allow the virtual machine to deploy</h4>
<img src="https://i.imgur.com/wNo3BIy.png">
<img src="https://i.imgur.com/GmJoLy2.png">

<h2>Log into Remote Desktop Connection</h2>
<h4>Use the public IP address, username and password to log into the virtual machine</h4>
<img src="https://i.imgur.com/UyZp3FZ.png">
<h4>Paste the public IP address and the username to identify the computer. After in the new tab enter the password that was created.</h4>
<img src="https://i.imgur.com/NTEA0fP.png">
<img src="https://i.imgur.com/7k6dthp.png">

<h2>Enabling ISS in Windows</h2>
<h4>Open control panel, then go to programs and click "uninstall programs"</h4>
<img src="https://i.imgur.com/rbdfHdO.png">
<img src="https://i.imgur.com/Gu67lwv.png">
<h4>Click "Turn Windows featuures on or off" </h4>
<img src="https://i.imgur.com/71pH3TZ.png">
<h4> Internet Information Services -> World Wide Web Services -> Application Development Features -> [X] CGI</h4>
<img src="https://i.imgur.com/XXZPO0w.png">
<img src="https://i.imgur.com/puqoF4o.png">

<h2>Downloading Files</h2>
<h4>Download PHP 7.3.8 (php-7.3.8-nts-Win32-VC15-x86.zip)</h4>
<img src="https://i.imgur.com/xFE8uBH.png">
<img src="https://i.imgur.com/GCgWrUY.png">
<h4>Rewrite Module (rewrite_amd64_en-US.msi)</h4>
<img src="https://i.imgur.com/vcrDHLg.png">
<img src="https://i.imgur.com/gLUOSUr.png">
<img src="https://i.imgur.com/Ep0oue0.png">
<h4>Go to the Windows C: drive and create a PHP folder</h4>
<img src="https://i.imgur.com/xoCXTMA.png">
<h2>Go back to the unzipped file and drag into the PHP folder, once this is done extract the file in the PHP C: drive folder.</h2>
<img src="https://i.imgur.com/o6k1hFO.png">
<img src="https://i.imgur.com/xmEAYEe.png">
<h2>Install VC_redist.x86.exe</h2>
<img src="https://i.imgur.com/jDSMeNd.png">
<img src="https://i.imgur.com/RrG7Z0V.png">
<img src="https://i.imgur.com/F5bMiIn.png">
<h2>Install MySQL 5.5.62(mysql-5.5.62-win32.msi)</h2>
<img src="https://i.imgur.com/g41yaPQ.png">
<img src="https://i.imgur.com/arqpPEH.png">
<img src="https://i.imgur.com/43SNXCe.png">
<img src="https://i.imgur.com/ZvLnbcB.png">
<img src="https://i.imgur.com/20Vn8yY.png">
<img src="https://i.imgur.com/34CPy6M.png">
<img src="https://i.imgur.com/sGgYRF2.png">

<h2>Register PHP within IIS</h2>
<img src="https://i.imgur.com/JVb5Nuu.png">
<img src="https://i.imgur.com/32oarlk.png">
<img src="https://i.imgur.com/6aBMNts.png">
<img src="https://i.imgur.com/KyK6Yx9.png">
<img src="https://i.imgur.com/I1iDbF7.png">
<img src="https://i.imgur.com/tVwfrgl.png">
<img src="">

<h2>Install osTicket</h2>
<img src="https://i.imgur.com/wz79Jmf.png">
<img src="https://i.imgur.com/PoP6GTr.png">
<img src="https://i.imgur.com/0yloXEy.png">

<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>


<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
