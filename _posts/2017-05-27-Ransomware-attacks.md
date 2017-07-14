---
published: true
---
WannaCry Ransomware Attack 
=========================

Introduction 
------------

On Friday, May 12, 2017, a ransomware cyber-attack broke out. This ransomware called WannaCrypt or WannaCry attacked and affected thousands of computers in more than 150 countries.
A ransomware is a type of malicious software designed to block access to computer files by encrypting them, then threatening to publish or delete them until a ransom is paid. 
The WannaCry ransomware targeted computer systems running Microsoft Windows operating systems, encrypted all files, and demanded ransom payments in form of bitcoin cryptocurrency. 
On Friday, April, 14, 2017, a hacker group, the Shadow Brokers, leaked an exploit called the EternalBlue that was used to carry out the WannaCry ransomware attack.
EternalBlue, an exploit that takes advantage of a vulnerability in Microsoft’s implementation of Server Message Block, is widely believed to have been developed by the U.S National Security Agency.  
The computer systems that fell prey to the WannaCry ransomware were unpatched Microsoft Windows computer systems that never installed the Microsoft security patch released on March 14, 2017 to fix this security flaw in their implementation of the Server Message Block protocol. This security update prevents remote code execution if an attacker sends specifically crafted messages to a Microsoft Server Message Block server. 
The hackers behind this attack gave their victims a 7 day ultimatum from the day their computers got infected, to pay the ransom or risk having their files deleted. 

Technical Analysis
------------------
A WannaCry worm, a form of cryptovirus, infects a computer system on a network by using EternalBlue to exploit a vulnerability in the Server Message Block (SMB), spreads through the SMB layer protocol, and installs a backdoor implant tool called DoublePulsar. After installing the backdoor tool, two threads are created, the first thread scans hosts on the LAN, while the second thread replicates 128 times and scans hosts on the wider internet. Simply put, once the malware has infected one machine on the network, it will quickly propagate within that network without user interaction. 
The initial infection vector isn’t clearly known but it’s largely believed that the ransomware spreads through these two scenarios;

•	Arrival through social engineering emails designed to trick users to run the malware and activate the worm-spreading functionality with the SMB exploit. 

•	Infection through SMB exploit when an unpatched computer can be addressed in other infected machines.
Other notable examples of ransomwares that have previously plagued computer systems include; Teslacrypt, CryptoWall, Cryakl, Scatter, Mor, CTB-Locker, Fury, TorrentLocker, Lortok, Aura, and Shade. 

Ethical Issues
--------------

Computer Security Acts world over are in agreement that protecting the security and privacy of sensitive information on private or public computer systems is an offense. And so, is the breaking and entering of a private or public network without permission. 
The WannaCry attack is in complete violation of the world’s Computer Security Acts. This attack is a total violation of digital privacy. 
The fact that this attack had no defined target, led to the corruption of thousands of computer systems, led to business stand stills world over, is evidence is that the act was grave, wrong, and totally disastrous.
Hacking, in itself, can be a noble venture. Say in situations where research and security hackers hack systems to identify critical security flaws in systems and either write code fixes or inform the vendors, so that patches can be written and released.
Hackers should steer away from selfish motivations like financial gain, or mere entertainment and look towards more society-wide fulfilling application of their skills. 
Hackers should be guided by simple societal values like respect to privacy, trust, and honesty.

Mitigation Procedures
---------------------

•	Disable SMBv1 and SMBv3 so as to stop the worm. Disabling SMB blocks access to shared files and data. So the benefits of mitigation should be weighed against potential disruption to users. 

•	Do not pay the ransom as there is no guarantee that the data will be recovered. 

The general public is advised to follow the **below practices** in order to **protect themselves**; 
                                          
+ Regular Installation of OS update releases: It is vital and highly recommended that every computer system user always install system patches as they are provided by the vendors. These patches fix identified security flaws, thereby protecting the computer systems from getting compromised through the exploitation of such known flaws. For this particular ransomware, the application of the March 14, 2017 Microsoft patch for the MS17-010 SMB vulnerability is highly recommended.

+ Get rid of End Of Life software: End Of Life (EOL) software is software that is no longer supported by the company that developed it. This means that such software isn’t updated to protect against emerging security threats. Some people become sentimental to some of their EOL software packages and refuse to stop using them. This has proved very dangerous and should be avoided.

+ Disaster Recovery:  Implement a data and backup plan to ensure that copies of proprietary data are maintained in a secure location.

+ Update Antivirus programs:

Impact of the attack.
--------------------
This attack should be seen as a wake-up call. With the daily advancement of technology, it’s going to be increasingly super hard to keep track of vulnerabilities. If this trend isn’t closely checked, It’s much possible that terrorists can muster up a lasting cyber attack. 
