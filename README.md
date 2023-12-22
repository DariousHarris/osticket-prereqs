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


<h2>Creating the Azure Virtual Machine</h2>

<p>
<img src="https://i.imgur.com/pKAmrzN.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
In the initial phase of this osTicket installation lab, we establish the foundation in Azure. This involves creating a Resource Group and deploying a Windows 10 Virtual Machine (VM) named "Vm-osticket" with 4 vCPUs. IIS is then installed and configured on the VM, along with essential features such as CGI and Common HTTP Features. PHP Manager for IIS and the Rewrite Module are downloaded and installed, setting the stage for PHP integration within IIS.
</p>
<br />

<h2>PHP and MySQL Setup</h2>

<p>
<img src="https://i.imgur.com/THzi02H.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
  
Continuing the setup, a PHP directory is created, and PHP 7.3.8 is installed along with the necessary dependencies. The MySQL database is installed with a standard configuration, including a password setup. IIS is reloaded, registering PHP within IIS for seamless integration. MySQL 5.5.62 is configured using the Configuration Wizard. With the groundwork laid, the environment is ready for the installation of osTicket.

</p>
<br />

<h2>osTicket Installation</h2>

<p>
<img src="https://i.imgur.com/Oc0TnRl.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
The osTicket installation involves downloading the application and extracting the contents to the designated directory within wwwroot. IIS is reloaded to reflect the changes. Extensions like php_imap.dll, php_intl.dll, and php_opcache.dll are enabled to enhance osTicket functionality. Configuration files are adjusted, and proper permissions are assigned. The setup is completed by configuring osTicket through a web browser, naming the help desk, specifying the default email, and creating a MySQL database called "osTicket."
</p>
<br />


<h2>Verification and Cleanup</h2>
<p>
<img src="https://i.imgur.com/r16sGbb.png" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
Post-installation, the installation's success is verified by browsing to the help desk login page. Additionally, end-users can access osTicket via the provided URL. Cleanup involves deleting unnecessary setup files, setting appropriate permissions on configuration files, and ensuring a secure and operational environment.

</p>
<br />

