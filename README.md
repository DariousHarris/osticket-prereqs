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

- IIS
- PHP Manager
- Rewrite Module
- Microsoft visual C++
- MySQL

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
I started by installing/enabling IIS with CGI and common HTTP features, also the IIS management console and as always 
  waited for the download process to ensure the project continues to run smoothly. Then I download and install PHP manager, rewrite module and Visual C++. Then I'll go to download and install My SQL with a typical setup. After I launch the configuration wizard I'll select "Standard Configuration" and enter a password needed for later.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
From here I will open IIS as an Admin and register PHP from within IIS then reload the server. From here Ill start to download osTicket. Afterwards extract and copy "upload" folder to wwwroot also renaming it osTicket. After reloading enable a few extentions, php_imap.dll, php_intl.dll, and php_opcache.dll. Rename ost-sampleconfig.php to ost-config.php and the change the permissions to "everyone". Now osTicket can continue installing within the browser.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
From here Heidi SQL must be set up with a new session and password. Afterwards connect to the session and create a new database called "osTicket". Then we go back and continue setting up osTicket in the browser entering in the SQL Database and password we provided and everything will be installed correctly
</p>
<br />
