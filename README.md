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

<h2>List of Prerequisites</h2>

- Installing IIS (Internet Information Services)
- Installing software prerequsites for OSTicket (Rewrite Module, PHP, VC Redist x86, MySQL, HeidiSQL).
- Registering PHP inside of IIS.
- Enabling required extensions and creating database for OSTicket to run using HeidiSQL.
- Installing OSTicket.
  

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/VaXPJ6S.png" height="80%" width="80%" alt="[Disk Sanitization Steps]"/>
</p>
<p>
In this step, I am installing IIS in order to create a webserver that will allow users to access OSTicket.
</p>
<br />
<p>
<img src="https://i.imgur.com/qAVa1Vo.png" height="80%" width="80%" alt="Next"/>
</p>
<p>
Here, I am registering PHP Manager inside of IIS. This allows for configuration of the graphical user interface for PHP installations.
<br />
<img src="https://i.imgur.com/FMezGQr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  At this point, I have successfully installed all of the prerequisites and the required functionalities to run OSTicket! Next, we will perform further configuration for service use.
</p>
<br />
