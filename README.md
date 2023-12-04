<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system, osTicket.<br />



<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Step 1: Create A Virtual Machine in Microsoft Azure & Connect to it using Remote Desktop.
- Step 2: Install / Enable IIS in Windows WITH CGI and Common HTTP Features AND IIS Management Console

- Step 3 : Download and Install PHP Manager For IIS
- Step 4 : Download and Install The Rewrite Module 
- Step 5 : Download and Unzip PHP 7.3.8 into C:\PHP
- Step 6 : Download and Install VC_redist.x.86
- Step 7 : Download and Install MySQL 5.5.62 
- Step 8 : osTicket Configurations
- Step 9 : Download and Install HeidiSQL.


<h2>Installation Steps</h2>

<p>

Step 1
(Create A Virtual Machine in Azure)

Create a Resource Group in Microsoft Azure.

<img src="https://i.imgur.com/okNRsTh.png" height="80%" width="80%" alt="Resource Group"/>

<img src="https://i.imgur.com/2rCx3UJ.png" height="80%" width="80%" alt="Resource Group"/>

</p>

Then create a Windows 10 Virtual Machine (VM) with 2-4 Virtual CPUs, called VM-osticket to lay within that Resource Group. 
<p

<p>
<img src="https://i.imgur.com/gt5KhtC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/SrWGqmq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/AUxJMiN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/kdjEqrX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/uRcsqcl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

Once we have created our Virtual machine, we would connect to it in Microsoft Remote Desktop using the Virtual Machines Public IP address. 

<p>


</p>
<br />

<p>
  
<img src="https://i.imgur.com/5EkKrFU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/AByg8Xg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/KOqJL2y.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/PNOWPnR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  
</p>



<p>
Step 2
  
Install / Enable IIS in Windows WITH CGI and Common HTTP Features AND IIS Management Console
</p>
<br />

<p>
  

  <img src="https://i.imgur.com/sHFV8lQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
  <img src="https://i.imgur.com/dMnDoBw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  

  <img src="https://i.imgur.com/Jd5foko.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  <img src="https://i.imgur.com/vguSkT4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  <img src="https://i.imgur.com/4wsZeWB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  <img src="https://i.imgur.com/ZsC70EO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  <img src="https://i.imgur.com/NUB76Ff.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  <img src="https://i.imgur.com/jlnx45f.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  <img src="https://i.imgur.com/G6jC2fs.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>



<p>
Step 3
  
Download and Install PHP Manager For IIS
</p>
<br />


<p>
<img src="https://i.imgur.com/rkkHvHK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
Step 4: Download and Install The Rewrite Module 

</p>
<br />

<p>
<img src="https://i.imgur.com/geaxli9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/u6mcpbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/ZYKRPUQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p>
Create a New PHP File on the C:\PHP
</p>


<img src="https://i.imgur.com/77nfLGF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/snXkw4j.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<p>
Step 5
  
Download and Unzip PHP 7.3.8 into C:\PHP
</p>
<br />


<p>
  
<img src="https://i.imgur.com/7JPbHmn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/saEWoXX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/RoVgulS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<p>
Step 6
  
Download and Install VC_redist.x.86
</p>
<p>

  <img src="https://i.imgur.com/JQNMhf7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  <img src="https://i.imgur.com/mLBOBe1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
Step 7
  
Download and Install MySQL 5.5.62 
</p>

<img src="https://i.imgur.com/horNyBU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/NdckPlk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/tFXz1RU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/h1FnaAA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/8S3kcz0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/YZlVoFP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p>
Step 8
  
Configurations
</p>

<p>
  
Open IIS as an Admin
  
<img src="https://i.imgur.com/W5e0Wok.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Register PHP from within IIS

<img src="https://i.imgur.com/QZlGC2w.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Reload IIS (Open IIS, Stop and Start the server)

Download and Install osTicket v1.15.8
Extract and copy “upload” folder to c:\inetpub\wwwroot
Within c:\inetpub\wwwroot, Rename “upload” to “osTicket”

<img src="https://i.imgur.com/swsDAje.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


<img src="https://i.imgur.com/XpCzeFx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Reload IIS (Open IIS, Stop and Start the server)

Go to sites -> Default -> osTicket
On the right, click “Browse *:80”

<img src="https://i.imgur.com/stOR9p5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/eQPw7F5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/zQKKaGE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Note that some extensions are not enabled
Go back to IIS, sites -> Default -> osTicket
Double-click PHP Manager
Click “Enable or disable an extension”

Enable: php_imap.dll

Enable: php_intl.dll

Enable: php_opcache.dll


<img src="https://i.imgur.com/bjCbDKi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/BUG46lv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>



Refresh the osTicket site in your browse, observe the changes

Rename: ost-config.php
From: C:\inetpub\wwwroot\osTicket\include\ost-sampleconfig.php
To: C:\inetpub\wwwroot\osTicket\include\ost-config.php

<img src="https://i.imgur.com/rxuLJ4J.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


Assign Permissions: ost-config.php

Disable inheritance -> Remove All

New Permissions -> Everyone -> All

<img src="https://i.imgur.com/M006OTS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/kTXeWTX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/OSPt1Rr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/wfWcyhD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


<img src="https://i.imgur.com/XLPFmW7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/mhzZv6j.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


Continue Setting up osTicket in the browser (click Continue)

<img src="https://i.imgur.com/lrCWDsn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/fuwho9h.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


</p>


<p>
Step 9
  
Download and Install HeidiSQL.
</p>

<img src="https://i.imgur.com/T5jmOgB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/3UuIlq4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/Cl2sL2v.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/L9Fdjq4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


<p>
Open Heidi SQL - Create a new session,

Connect to the session - Create a database called “osTicket”



<img src="https://i.imgur.com/XBxg9ca.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


<img src="https://i.imgur.com/Ex7HxA6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>



<img src="https://i.imgur.com/5MqkxUr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


Continue Setting up osticket in the browser

<img src="https://i.imgur.com/8QmTNpJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

MySQL Database: osTicket


MySQL Username: root


MySQL Password: Password1


Click “Install Now!”

</p>


<p>

  
Congratulations, hopefully it is installed with no errors!


<img src="https://i.imgur.com/QQzKat7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Help desk login page

<img src="https://i.imgur.com/Z2k4kUr.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>


End Users osTicket URL


<img src="https://i.imgur.com/mA1hQ43.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<br />
