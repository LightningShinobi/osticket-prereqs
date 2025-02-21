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



<h2>Installation Steps</h2>

<p>
  Create an Azure Virtual Machine with the Windows 10 Pro Operating System with at least 2 vCPUs.<br/>
<img src="https://github.com/user-attachments/assets/87f11197-bef2-4b6f-9e61-16291ae8f8f2" height="80%" width="80%"alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />

<p>
  Next, open Remote Desktop Protocol (RDP). Copy the Public IPv4 address given from the Azure portal and connect to the VM.<br/>
<img src="https://github.com/user-attachments/assets/40c16e85-04d6-4916-a754-358df0ae8272"/>
</p>
<p>

</p>
<br />

<p>
Once you have opened the VM press the windows key and type in "Windows Features". Follow that by enabling and installing Internet Information Service (IIS).
<p>
<img src="https://github.com/user-attachments/assets/4b991afe-c5ac-46f6-9d0e-4fbaaf2b17bd" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<br />

<p>
Click the following link to aquire the installation files needed. https://drive.google.com/uc?export=download&id=1b3RBkXTLNGXbibeMuAynkfzdBC1NnqaD
<p>
<img src="https://github.com/user-attachments/assets/c67e2670-d3b6-45f6-aaf7-47397e2892b5" height="80%" width="80%" alt="Disk Sanitization Steps"/>


<p>
Extract OsTicket files to desktop and install PHP Manager.
<p>
<img src="https://github.com/user-attachments/assets/040f9a90-2b6a-4e6e-803b-44cf3799810e" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p>
Install Rewrite Module.
<p>
<img src="https://github.com/user-attachments/assets/d10c75a5-94e6-4a0c-a991-7b8b8d03288d" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p>
Install MySQL Server using the Typical Setup option.
<p>
<img src="https://github.com/user-attachments/assets/a1e35f7c-7a9e-4740-967f-7f05d7c9199b" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p>
Extract php-7.3.8-nts-Win32-VC15-x86 to the folder name PHP in Windows (C:).
<p>
<img src="https://github.com/user-attachments/assets/7b8b892e-a4a0-455c-950a-3f3162f10b41" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://github.com/user-attachments/assets/a9caa962-8cdc-475d-abf0-cc9ab02f4632" height="80%" width="80%" alt="Disk Sanitization Steps"/>


<p>
Install VC_redist.x86.
<p>
<img src="https://github.com/user-attachments/assets/8e4ccf90-ccd9-4db4-9e38-e63057ae6e2f" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://github.com/user-attachments/assets/29185a41-d201-4469-a80c-9daf0a773beb" height="80%" width="80%" alt="Disk Sanitization Steps"/>


<p>
Open IIS as an administrator. Register PHP in IIS then restart the IIS Manager.
<p>
<img src="https://github.com/user-attachments/assets/a22dbad1-64a5-42cd-884a-9f3009391951" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p>
<p>
Extract osTicket-v1.15.8 to wwwroot file and rename folder osTicket.
<p>
<img src="https://github.com/user-attachments/assets/40bcb4bb-2282-4629-9df4-4fd07adb55d1" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<p>
Extract php-7.3.8-nts-Win32-VC15-x86 to the folder name PHP in Windows (C:).
<p>
<img src="https://github.com/user-attachments/assets/4b991afe-c5ac-46f6-9d0e-4fbaaf2b17bd" height="80%" width="80%" alt="Disk Sanitization Steps"/>
