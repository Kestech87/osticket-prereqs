<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system, osTicket.<br />


<p>
  
Before installing osTicket, make sure you have PHP (version 5.6 or higher) and a compatible database system (like MySQL or MariaDB). Create a web server to host the system files,  and configure PHP settings to run the installation.

</p>





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

<img src="https://i.imgur.com/DdHsQ9S.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/SrWGqmq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


<img src="https://i.imgur.com/91Rrl3j.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/uRcsqcl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

Once we have created our Virtual machine, we would connect to it in Microsoft Remote Desktop using the Virtual Machines Public IP address. 

<p>


</p>
<br />

<p>
  
<img src="https://i.imgur.com/5EkKrFU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/AByg8Xg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/EmUm9hU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

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
  

  <img src="https://i.imgur.com/LpHPaKt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  <img src="https://i.imgur.com/vguSkT4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  <img src="https://i.imgur.com/VhaSHOn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

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

<img src="https://i.imgur.com/0QuMCQh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p>
Create a New PHP File on the C:\PHP
</p>


<img src="https://i.imgur.com/77nfLGF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/ds8B2AA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<p>
Step 5
  
Download and Unzip PHP 7.3.8 into C:\PHP
</p>
<br />


<p>
  
<img src="https://i.imgur.com/a0x9P0n.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/saEWoXX.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/RoVgulS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<p>
Step 6
  
Download and Install VC_redist.x.86
</p>
<p>

  <img src="https://i.imgur.com/Q94C9wY.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  <img src="https://i.imgur.com/syV0MXZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
Step 7
  
Download and Install MySQL 5.5.62 
</p>

<img src="https://i.imgur.com/H3gjKwo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/OxLejHd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/IesEraJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/Po5QWdT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/Ig82Il7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/8S3kcz0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/YZlVoFP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p>
Step 8
  
Configurations
</p>

<p>
  
Open IIS as an Admin
  
<img src="https://i.imgur.com/9QF1nfm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Register PHP from within IIS

<img src="https://i.imgur.com/TT1ICvw.png " height="80%" width="80%" alt="Disk Sanitization Steps"/>

Reload IIS (Open IIS, Stop and Start the server)

Download and Install osTicket v1.15.8
Extract and copy “upload” folder to c:\inetpub\wwwroot
Within c:\inetpub\wwwroot, Rename “upload” to “osTicket”

<img src="https://i.imgur.com/swsDAje.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


<img src="https://i.imgur.com/Zu9huqm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Reload IIS (Open IIS, Stop and Start the server)

Go to sites -> Default -> osTicket
On the right, click “Browse *:80”

<img src="https://i.imgur.com/pOzJ6R7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/IvOXc4r.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/3yqu3SU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Note that some extensions are not enabled
Go back to IIS, sites -> Default -> osTicket
Double-click PHP Manager
Click “Enable or disable an extension”

Enable: php_imap.dll

Enable: php_intl.dll

Enable: php_opcache.dll


<img src="https://i.imgur.com/UsbrfQ9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/BUG46lv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>



Refresh the osTicket site in your browse, observe the changes

Rename: ost-config.php
From: C:\inetpub\wwwroot\osTicket\include\ost-sampleconfig.php
To: C:\inetpub\wwwroot\osTicket\include\ost-config.php

<img src="https://i.imgur.com/2ldZbul.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


Assign Permissions: ost-config.php

Disable inheritance -> Remove All

New Permissions -> Everyone -> All

<img src="https://i.imgur.com/uUll7BC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/CeRURhC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/0UlG7bw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/iEoYRjr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


<img src="https://i.imgur.com/qTAfDH8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/OUfHgpT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


Continue Setting up osTicket in the browser (click Continue)

<img src="https://i.imgur.com/mNzTmZu.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/PeAN0Hc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


</p>


<p>
Step 9
  
Download and Install HeidiSQL.
</p>

<img src="https://i.imgur.com/T5jmOgB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/3UuIlq4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/Xf6syGK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/L9Fdjq4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


<p>
Open Heidi SQL - Create a new session,

Connect to the session - Create a database called “osTicket”



<img src="https://i.imgur.com/XBxg9ca.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


<img src="https://i.imgur.com/Ex7HxA6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/mCQZZzi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>




Continue Setting up osticket in the browser

<img src="https://i.imgur.com/JhEYGWR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

MySQL Database: osTicket


MySQL Username: root


MySQL Password: Password1


Click “Install Now!”

</p>


<p>

  
Congratulations, hopefully it is installed with no errors!


<img src="https://i.imgur.com/QQzKat7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

Help desk login page

<img src="https://i.imgur.com/LETvjeS.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>


End Users osTicket URL


<img src="https://i.imgur.com/6NPl8S3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

<br />
