# cybersecurity lab setup 
week 1 internship project documenting a cybersecurity testing lab setup using virtualbox and kali linux.

1. Project Overview
   
This project involves setting up a virtual cybersecurity testing lab using Oracle VirtualBox and Kali Linux as part of my Cybersecurity & Ethical Hacking Internship at NETWORKWALKS.
The objective is to create a controlled virtual environment for learning network configuration, connectivity testing, and ethical hacking fundamentals.

2. System Specifications
* Host Operating System: Windows
* Virtualization Platform: Oracle VirtualBox
* Attacking Machine: Kali Linux
* Network Mode: NAT Network
* RAM: 8gb

3.Tools Used
* 7-Zip  https://7-zip.org/download.html
* Oracle VirtualBox  https://virtualbox.org/wiki/Downloads
* Kali Linux  https://kali.org/get-kali
  
  
4. Lab Setup and Configuration
The following tasks were carried out as part of the lab setup:

* Install 7-Zip
 7-Zip was installed to extract the Kali Linux virtual machine package distributed in .7z archive format.
  
* Installed and configured Oracle VirtualBox.
<img width="1920" height="1080" alt="2026-10-26 (2)" src="https://github.com/user-attachments/assets/54f36903-3ea9-4b0a-a4d2-8190ae112922" />

* Create a NAT Network
A NAT Network was configured in VirtualBox to provide network connectivity to the Kali Linux virtual machine.
Network Type: NAT Network
Subnet: 10.0.0.0/24
<img width="960" height="1280" alt="WhatsApp Image 2026-10-26 at 1 54 01 PM" src="https://github.com/user-attachments/assets/8543e67a-cb9e-4fc0-9a5c-c8fd0d62a1e4" />

* Imported and configured the Kali Linux virtual machine.
* <img width="1600" height="1200" alt="WhatsApp Image 2026-10-26 at 1 04 19 PM" src="https://github.com/user-attachments/assets/139523dd-9ef2-41da-b7e2-dbea39a9391a" />
  
* Configured and checked Kali Linux network settings.
  
* Tested network connectivity and DNS resolution.
* <img width="1200" height="1600" alt="WhatsApp Image 2026-10-26 at 1 04 24 PM" src="https://github.com/user-attachments/assets/9e0d9ca8-6aed-40c6-af32-baf03d0f1a5f" />

* Created a virtual machine snapshot for recovery.
  <img width="1280" height="960" alt="WhatsApp Image 2026-10-26 at 1 13 39 PM" src="https://github.com/user-attachments/assets/8099e076-3c19-45bb-807b-5c8ed371c377" />

5. Challenges and Troubleshooting
Issue: Missing Network Connection Editor
During the Kali Linux network configuration, I encountered an issue where the Edit Connection option was not visible in the network settings.

Troubleshooting Steps
* Opened the Kali Linux terminal using Ctrl + Alt + T.
* Used the nm-connection-editor command to access the network connection editor.
* Selected the wired network connection and opened its settings.
* Navigated to the IPv4 Settings tab to configure the network manually.
* Prepared the static IP, subnet mask, gateway, and DNS settings according to the lab requirements.

6. Learning Outcome
This issue helped me understand alternative ways to access network configuration settings in Kali Linux using terminal commands and graphical tools. 
Through this project, I explored:
* Virtual machine setup and configuration.
* Virtual networking fundamentals.
* Network connectivity and DNS testing.
* Virtual machine snapshots and recovery.
* Building a controlled environment for cybersecurity practice.

7. Conclusion
   
This Week 1 project provided practical exposure to setting up a virtual cybersecurity lab and understanding the basic networking components required for ethical hacking practice. 

Internship: Cybersecurity & Ethical Hacking — NETWORKWALKS

Disclaimer: This lab is intended for educational purposes and authorized security testing only.
