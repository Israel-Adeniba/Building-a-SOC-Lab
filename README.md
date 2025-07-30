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
 For the HARD DISK, we choose 70GB:  <br/>
 HARD DISK requires 64 GB or larger storage device for Windows 11: <br/>
<img src="https://i.imgur.com/YKTGF2t.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />
Summary:  <br/>
<img src="https://imgur.com/38ojK9W.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
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



Set-up Ubuntu Linux <br />
Click New in VirtualBox <br />
Fill name: SOC 101- Ubuntu <br />
Add the destination folder and ISO Image <br/>
<img src="https://i.imgur.com/fIp0aKa.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />
 For the hardware (RAM), we would maintain same configuration as the Windows machine; 6GB and 2 CPUs:  <br/>
<img src="https://i.imgur.com/KJT9QKu.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />
 For the HARD DISK,we would maintain same configuration as the Windows machine; 70GB:  <br/>
<img src="https://i.imgur.com/YKTGF2t.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />
Summary:  <br/>
<img src="https://imgur.com/lBqClH4.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />

Start/Launch SOC 101- Ubuntu on VirtualBox:  <br/>
<img src="https://imgur.com/5K4ttUP.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />
Complete installation and Setup process, it's self explanatory:  <br/>
<img src="https://i.imgur.com/I37ku7a.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />
<img src="https://i.imgur.com/eQUUd0k.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />
<img src="https://i.imgur.com/8ArJA2M.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />
<img src="https://i.imgur.com/ru6r4Nn.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />
Ubuntu Linux is Running:  <br/>
<img src="https://i.imgur.com/Dp4vnGi.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />

To ensure our Ubuntu Linux system has the most up-to-date knowledge of what software packages are available in the repositories, we run "sudo apt update" in the command prompt.
<img src="https://imgur.com/FgjPKdi.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />
<img src="https://imgur.com/hSdaI0Q.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />
run "sudo apt install bzip2 tar gcc make prl git" in the command prompt  <br/>
<img src="https://i.imgur.com/IoQc9OP.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />
run "sudo apt install linux-headers-generic" in the command prompt  <br/>
<img src="https://i.imgur.com/PNs26g7.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />
run "sudo apt install linux-headers $(uname -r)" in the command prompt  <br/>
<img src="https://i.imgur.com/URRYbOJ.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />

Lets ensure we have git installed so we can clone the actual lab repository <br/>
<img src="https://i.imgur.com/cKf9z4s.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />
We need to clone documents from the course repository to our Ubuntu VM and confirm <br/>
<img src="https://i.imgur.com/mjkC8uJ.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />
We need to extract the course files from the SOC101_Free folder <br/>
Open a folder > Open Documents > Open SOC101_Free > Open Course_Files 
<img src="https://i.imgur.com/idhSCMh.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />
<img src="https://i.imgur.com/na82ipK.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />
<br />
<img src="https://i.imgur.com/9uIBkWi.png" height="80%" width="80%" alt="Building a SOC Lab Steps"/>
<br />






----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
