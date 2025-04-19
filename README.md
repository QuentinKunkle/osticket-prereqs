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

- What is osTicket
- How to install osTicket requirements
- Web server configurations for osTicket
- How to install osTicket

<h2>What is osTicket</h2>

<p>
<img src="https://github.com/user-attachments/assets/ce64d354-d74d-4a52-8af8-51b8cdb9344e" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<a href="https://osticket.com/">osTicket</a> is an open-source support ticket system that helps businesses manage customer service requests. It lets users submit tickets through email, web forms, or phone, and organizes them in one place. Agents can track, respond to, and resolve issues efficiently. It’s customizable and easy to use, making it great for beginners and small teams.

<h2>How to install osTicket requirements</h2>

</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/0cde3aae-7d4b-4fb1-9eb5-a9c84481b1d0" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
To begin <a href="https://drive.google.com/uc?export=download&id=1b3RBkXTLNGXbibeMuAynkfzdBC1NnqaD">download the osTicket-Installation-Files.zip</a> and unzip it onto your desktop. The folder should be called “osTicket-Installation-Files” We will use the files in this folder to install osTicket and some of the dependencies.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/c0b45d48-013b-432e-983c-3f8498a98a60" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next, you will install PHP Manager for IIS. From the "osTicket-installation-files" folder find PHPManagerForIIS_V1.5.0
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/d65f90dd-13d8-440e-b59f-2fe6747805b2" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Then, from the “osTicket-Installation-Files” folder, install the Rewrite Module named rewrite_amd64_en-US.msi
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/b2506de4-625c-4fb4-9cfc-af718a480e36" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Before we can continue installing the necessary programs, we will need to create a folder in our C drive named "PHP"
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/7d432ddd-020c-4a2b-ba1a-aaaa115501f7" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now that we have a PHP file in our C drive, we can extract the files from the folder "php-7.3.8-nts-Win32-VC15-x86.zip" into it. This folder is in the  “osTicket-Installation-Files” folder, which we have been working out of. 
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/d4a401ed-3efc-4c6d-b75f-2a71aa17b5e5" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Now, from the “osTicket-Installation-Files” folder, install VC_redist.x86.exe.
</p>
<br />

<p>
<img src="https://github.com/user-attachments/assets/a4488044-4381-4339-aef9-788d134b1358" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
You will also need to install MySQL 5.5.62 (mysql-5.5.62-win32.msi) from the “osTicket-Installation-Files” folder. Please follow these steps.
  
- Typical Setup
- Launch Configuration Wizard (after install)
- Standard Configuration
- Password: root

Note* making root your password is extremely insecure and should only be done in virtual machines for training purposes. 
</p>
<br />

<h2>Web server configurations for osTicket</h2>
  
<p>
<img src="https://github.com/user-attachments/assets/a4488044-4381-4339-aef9-788d134b1358" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
