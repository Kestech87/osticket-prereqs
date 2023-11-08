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

- Step 3: Download and Install PHP Manager For IIS
- Step 4: Download and Install The Rewrite Module 
- Step 5: Download and Unzip PHP 7.3.8 into C:\PHP
- Step 6: Download and Install VC_redist.x.86
- Step 7
- Step 8

<h2>Installation Steps</h2>

<p>

Step 1
(Create A Virtual Machine in Azure)

Create a Resource Group in Microsoft Azure.
<img src="https://i.imgur.com/F7HMx1D.png" height="80%" width="80%" alt="Resource Group"/>

<img src="https://i.imgur.com/SWAnXSt.png" height="80%" width="80%" alt="Resource Group"/>
</p>

Then create a Windows 10 Virtual Machine (VM) with 2-4 Virtual CPUs, called VM-osticket to lay within that Resource Group. 
<p

<p>
<img src="https://i.imgur.com/gt5KhtC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/Fe2DTFd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/AUxJMiN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/4OIFvSD.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/yOc6EFo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/uRcsqcl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>

Once we have created our Virtual machine, we would connect to it in Microsoft Remote Desktop using the Virtual Machines Public IP address. 

<p>


</p>
<br />

<p>
<img src="https://i.imgur.com/5EkKrFU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/AByg8Xg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/ZBfpnAz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/PNOWPnR.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  
</p>



<p>
Step 2
  
Install / Enable IIS in Windows WITH CGI and Common HTTP Features AND IIS Management Console
</p>
<br />

<p>
<img src="https://i.imgur.com/qWdAIJr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  <img src="https://i.imgur.com/dMnDoBw.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  <img src="https://i.imgur.com/Jd5foko.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  <img src="https://i.imgur.com/FSrDKXS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

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

<img src="https://i.imgur.com/lsOz1D0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/ZYKRPUQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p>
Create a New PHP File on the C:\PHP
</p>


<img src="https://i.imgur.com/77nfLGF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/dXkesoo.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Step 5
  
Download and Unzip PHP 7.3.8 into C:\PHP
</p>
<br />


<p>
<img src="https://i.imgur.com/7JPbHmn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/RTGIIU4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/RoVgulS.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Step 6
  
Download and Install VC_redist.x.86
</p>
<p>

  <img src="https://i.imgur.com/GUAbSd8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

  <img src="https://i.imgur.com/QJiKW8B.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
