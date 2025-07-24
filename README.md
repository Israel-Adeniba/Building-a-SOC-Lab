# Building-a-SOC-Lab

# Objective
This project aims to build a practical, hands-on SOC lab environment focused on monitoring, detecting, analyzing, and responding to cybersecurity threats in real time. It is designed to simulate a real-world Security Operations Center setting, enabling the development of skills in threat detection, incident response, log analysis, and use of SIEM tools. We would be
1. Learning techniques for analyzing and identifying Phishing attacks
2. Develop skills in monitoring network traffic for security threats and anomalies
3. Learn how to monitor and analyze Endpoint Security events
4. Learn how to use a SIEM for security event correlation, analysis and incident management 
5. Learn how to leverage threat intelligence to enhance security operations and incident response
6. Develop an understanding of digital forensics processes, common tools, and methodologies
7. Understand the process, procedures and best practices of incident response

 
<h2>Languages and Utilities Used</h2>

- <b>Oracle Virtualbox</b> 

<h2>Environments Used </h2>

- <b>Windows 11 Enterprise</b> 
- <b>Ubuntu Desktop 24.04.2 LTS</b> 


<h2>Program walk-through:</h2>
1.  Download all files which include;

- Oracle VirtualBox
[https://www.virtualbox.org/wiki/Downloads] or Go to google, search for Oracle VirtualBox and click the first link presented as a result, click download

  Oracle VirtualBox is a type 2 software-based hypervisor

- Windows 11 Enterprise
  [https://www.microsoft.com/en-us/evalcenter/download-windows-11-enterprise]

- Ubuntu Linux 
[https://ubuntu.com/download]

Nota bene: I strongly recommend creating a new folder to store the downloaded files. 

2. Set-up and install programs
3. Connecting the Virtual Network; Network environment setup, connecting all devices and the particular network connection established.


   
<h2>Phase 1: Download Utilities and Environment </h2>

Download VirtualBox: <br/>
 Click on the corresponding operating system you have; there are options for MacOS, Windows, Linux and Solaris.
<img src="https://imgur.com/1w7qPhN.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />
 Downloaded file:  <br/>
<img src="https://imgur.com/oG77khJ.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />

Download Windows 11 Enterprise: Select the ISO file <br/>
<img src="https://imgur.com/PUUAdt2.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />
Select the corresponding ISO Enterprise download:  <br/>
<img src="https://imgur.com/hf47L4A.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />
Downloaded file:  <br/>
<img src="https://imgur.com/Mykh22Q.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />

Download Ubuntu Desktop to have the GUI
<img src="https://imgur.com/lfi9eit.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br /> 
Select any of the Long Term Support (LTS) version
<img src="https://imgur.com/NkGWAtP.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br /> 
Downloaded file:  <br/>
<img src="https://imgur.com/F0rwJU3.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />



<h2>Phase 2: Setup and installation </h2> <p align="center">
 
 Install and open VirtualBox:  <br/>
<img src="https://imgur.com/pN8fwY0.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />
Set-up Windows 11 Enterprise; <br />
Click New in VirtualBox <br />
Fill name: SOC 101- Windows 11 VM <br />
Add the destination folder, ISO Image, Edition: Windows 11 Enterprise Evaluation (10.0.26100.1742 / x64 / en-US) <br/>
<img src="https://i.imgur.com/KgJtmj9.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />
 For the hardware (RAM), we selected 6GB and 2 CPUs:  <br/>
 Minimum RAM requirement for Windows 11 is 4 GB. <br/>
<img src="https://i.imgur.com/KJT9QKu.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />
 For the HARD DISK, we choose 70GB and 2 CPUs:  <br/>
 HARD DISK requires 64 GB or larger storage device for Windows 11: <br/>
<img src="https://i.imgur.com/YKTGF2t.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />
Summary:  <br/>
<img src="https://imgur.com/38ojK9W.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />
Setup Ubuntu Linux <br />
Click New in VirtualBox <br />
Fill name: SOC 101- Ubuntu <br />
Add the destination folder and ISO Image <br/>
<img src="https://i.imgur.com/fIp0aKa.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />





 Start/Launch SOC 101- Windows 11 VM on VirtualBox:  <br/>
<img src="https://imgur.com/WYjcgG1.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />

Complete installation and Setup process, it's self explanatory:  <br/>
<img src="https://i.imgur.com/synIG5L.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />
<img src="https://i.imgur.com/UmUgbqK.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />
<img src="https://i.imgur.com/kL6kLt2.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />
Window 11 Enterprise Running:  <br/>
<img src="https://i.imgur.com/mgjHrrZ.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />


<h2>Phase 3: Connecting the Virtual Network </h2>

 To get the ip address of the Klilinux Virtual Machine, run the command "ifconfig" in the Terminal Emulator on the Kali linux VM.
<img src="https://imgur.com/vY0TufN.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br/>
<br/>
To get the ip address of the Windows 10 VM and Windows Server, run the command "ipconfig" in the Command prompt terminal on the respective machines.
<br/>
<img src="https://imgur.com/snTV5Aj.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<img src="https://imgur.com/kL0YA3p.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br/>
<br/>

To ensure the systems are connected, ping every other system from each machine;
- Ping the Windows 10 VM and Windows 2022 server from the Kali VM
<img src="https://imgur.com/wamTYSL.png" height="80%" width="80%" alt="Building a Cybersecurity Lab Steps"/>

- Ping the Kali VM and Window 10 VM from the Windows 2022 server 
<img src="https://imgur.com/JKZj9bx.png" height="80%" width="80%" alt="Building a Cybersecurity Lab Steps"/>

- Ping the Kali VM and Windows 2022 server from the Windows 10 VM 
<img src="https://imgur.com/Rdi7kPo.png" height="80%" width="80%" alt="Building a Cybersecurity Lab Steps"/>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
