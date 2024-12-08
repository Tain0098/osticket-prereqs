<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [Canva: How To Install osTicket with Prerequisites](https://www.canva.com/design/DAGYubtCWMU/sCEPONvSN3-4I03jDesUdA/edit?utm_content=DAGYubtCWMU&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Item 1 PHPManagerForIIS_V1.5.0.msi
- Item 2 rewrite_amd64_en-US.msi
- Item 3 VC_redist.x86.exe
- Item 4 mysql-5.5.62-win32.msi
- Item 5 osTicket v1.15.8
- Item 6 HeidiSQL

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/Dc4BnRM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Install / Enable IIS in Windows WITH CGI
  
Open the Control Panel:

Press Windows + R, type control, and hit Enter. This will open the Control Panel.
Navigate to Programs and Features:

In the Control Panel, go to Programs > Turn Windows features on or off under the Programs and Features section.
Enable IIS:

In the Windows Features dialog that appears, scroll down and locate Internet Information Services.

Expand the Internet Information Services node to see more detailed features.

Ensure the following options are selected:

Web Management Tools (including IIS Management Console)

World Wide Web Services > Application Development Features:

Check CGI.

Optionally, you can enable other features like ASP, .NET Extensibility, or ISAPI Extensions depending on your needs.
World Wide Web Services > Common HTTP Features (e.g., Static Content, Default Document, Directory Browsing).
Install IIS:

Click OK to start the installation process.
Windows will now install IIS with the selected features, including CGI. This may take a few minutes depending on your system.





<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

