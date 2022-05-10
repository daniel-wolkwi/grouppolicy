<h1>Active Directory Group Policy</h1>

<h2>Description</h2>
This lab details the setup process for a basic Active Directory Group Policy Object. It follows the completion of the Active Directory Domain environment creation and user creation with PowerShell labs.
<br />


<h2>Technologies Used</h2>

- <b>Virtualization</b> 
- <b>Active Directory</b>
- <b>Group Policy</b>

<h2>Environments</h2>

- <b>Oracle VirtualBox</b>
- <b>Windows Server 2022</b>
- <b>Windows 10</b>

<h2>Program Walk-Through:</h2>

<p align = "center">
Create and share a folder with the desired wallpaper on the domain controller VM: <br/>
  <br/>
<img src="https://i.imgur.com/6KBvFgx.png" height="80%" width="80%" alt="Wallpaper Group Policy"/>
<br />
<br />
Create and link a GPO to the OU containing the test users:  <br/>
  <br/>
<img src="https://i.imgur.com/IIHZmW6.png" height="80%" width="80%" alt="Wallpaper Group Policy"/>
<br />
<br />
Edit the GPO so that it contains the wallpaper policy: <br/>
  (Be sure to link to the wallpaper's network path and not the local path) <br/>
  <br/>
<img src="https://i.imgur.com/oXQWsDc.png" height="80%" width="80%" alt="Wallpaper Group Policy"/>
<br />
<br />
Log in on the Windows 10 Client on the desired user and observe the new wallpaper:  <br/>
  <br/>
<img src="https://i.imgur.com/RrQIA3L.png" height="80%" width="80%" alt="Wallpaper Group Policy"/>
<br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
