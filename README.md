# Intrusion-Detection-System-with-Snort
## Objective

The objective of this work is to install and configure Snort as a Network Intrusion Detection System (NIDS), enable promiscuous mode for effective network traffic monitoring, configure Snort variables and decoders for accurate packet inspection, create and test custom Snort rules including advanced rules using Snorpy, implement Snort community rules to improve intrusion detection, and generate Snort log files for network traffic analysis using Wireshark.

### Skills Learned

-Install and configure Snort on a Linux-based system.

-Enable promiscuous mode on the network interface to capture all network traffic.

-Set up Snort variables, preprocessors, and decoders for accurate packet inspection.

-Write, test, and validate custom Snort rules for intrusion detection.

-Create and understand advanced detection rules for complex attacks.

-Apply and manage community-based Snort rules to improve security coverage.

-Analyze network traffic and interpret Snort log files using Wireshark.

### Tools Used

-Snort  Network Intrusion Detection System (NIDS)

-Snorpy  Snort rule creation and learning tool

-Wireshark  Network traffic analysis tool

-Linux Operating System (Ubuntu & Kali)

-Metasploitable2 

-Snort Community Rules

## Steps
Lap photo demonstration

- Installing Snort 

<img src="https://imgur.com/3Ew2QXn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


- Open the virtual machine settings and set promiscuous mode to(ALLOW ALL)



<img src="https://imgur.com/6zgOakl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

- Set the network variable HOME_NET to 192.168.2.0/24

<img src="https://imgur.com/CbzSsiC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


- Testing my configuration rule.

<img src="https://imgur.com/gGkLo3O.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<img src="https://imgur.com/7lgB0PM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


- My first rule.

<img src="https://imgur.com/Oods4xe.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


- Turning off the rules and testing my new rule by pinging my Metasploitable2 from my Kali Linux  

<img src="https://imgur.com/kicD827.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

- Here is the result of the first rule 
<img src="https://imgur.com/YHi3Bkn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


