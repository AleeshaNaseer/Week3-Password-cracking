# Week3-Password-cracking
Cracking a password from a locked PDF using John the Ripper (JTR) and NETWORKWALKS tools involves extracting the password hash from the protected PDF and testing candidate passwords against it to find a match.

networkwalks-B082-week3
Password Cracking with JTR and Networkwalks Tools

🔐 PENETRATION TESTING REPORT: Password Cracking (networkwalks.com)
          

Pentester Name	Ibunkunoluwa Fasesan
Program/Batch	B082-Networkwalks
Date	27th August 2026
Modules completed	W3-PM1 (Password cracking with JTR); W3-PM2 (Password Cracking with Networwalks tools)
Client/Target	3 encrypted/locked documents
Permission secured from client?	Yes
🔔 Liability Disclaimer
I have performed these activities only on the systems & devices where I had secured written permission or the devices/systems that I own myself. All these materials are for education and research purpose only. Do not use anything from here to break the law. Every action you take is your own responsibility. Misuse can lead to criminal charges, heavy fines, loss of your job and a permanent record. In most countries unauthorized access is a crime even when nothing is damaged.

🔰 Introduction/ Project Summary
This report contains password cracking activities completed in the 3rd week of the internship program with Networkwalks. This lab had two primary activities:

Password cracking with John the Ripper
Password cracking using some Networkwalks tools. This report documents my hands-on experience and a step by step guide on how i cracked already encrypted documents given to us.
🎯 Lab Objectives
The main objectives of this project are to:

Download JTR and Johny on Windows
Find the hashing of the locked documents using the onlinehashcrack.com website
Use the password tools in JTR to locate the password of the document
Use the Networkwalks Hash Calculator tool to also find the hashing of locked document.
Use the Networkwalks Password Cracker tool to locate the password using various directories.
⚙️ Tools and Technologies
The lab provides an isolated and controlled environment for cybersecurity learning and authorized security testing.

Tool	Purpose
Windows	This was were all tools were downloaded
Johny app	This was the GUI of the JTR extension
onlinehashcrack website	Used this to find the hashing when testing with JTR
JTR exe	Attached it to the GUI so that we can crack locked documents
Networkwalks Tools	Another method of Password cracking
1️⃣ Password Cracking with JTR
John the Ripper (JTR) is a popular password cracking tool used by security professionals to test how strong passwords are. It started as a tool for Unix systems but now works on Windows, Linux, and Mac. It can check many types of password hashes and also unlock password protected files like PDF, ZIP, and Office documents. Johnny is the graphical version of John the Ripper. It gives a simple point and click screen, so beginners can use JTR without typing long commands. Both tools are widely used in security testing and learning labs to understand password safety.

This are the steps followed to crack the document MY LOCKED PDF1

STEP 1 Download John the Ripper on the window PC (or any other PC it supports) and John GUI

<img width="1340" height="625" alt="Download" src="https://github.com/user-attachments/assets/c61d24a7-36b6-4c02-885d-cbb8bf0caaa2" />

1️⃣ Password Cracking with Networkwalks Tools
Networkswalks also has some tools that can be used in the cybersecurity space. For this project, we mainly focused on the Hash Calculator and the Password Cracker tool. They are free online tools that can also be used to crack the password of an encrypted document using directories.

This are the steps followed to crack the document MY LOCKED PDF1

STEP 1 Open the Hash Calculator an any web browser on your PC https://networkwalks.com/hash-calculator/
STEP 2 Upload the encrypted document into the PDF section of the website and copy the hash provided.
The Hash Calculator also gives you to ability to download .txt document to be used in other crackers like the JTR.
STEP 3 Open the Password Cracker using this link https://networkwalks.com/password-cracker/ and paste the hash to start cracking.
Using the in built directories did not provide the right password so I add to attach my own directory from the JTR_default_password.txt. This document contains an accumulation of commonly used password, other webpages that have been cracked like Facebook and Adobe also have their own .txt accumulated document.
Click on upload wordlist and select the directory you want to try, one the system recognizes the right password, you would be able to download it and unlock your PDF document.
🔚 Conclusion
This week 3 project helped understand why more complex passwords or alphanumeric passwords are more secure. Easier passwords would be easier to crack using directories or already in built Johnny directory and would also take less time for the attacker to get access to information without stress. More complex passwords take more time to get into. I even created my own locked pdf with a very complex password and the system took a long time trying to crack into it.

Secondly, as a cybersecurity analyst, I realized that password only security is not sufficient anymore. In this fast paced tech centered environment, in other to keep your information secure, a multi factor authentication method should be implemented, instead of just one security door guarding all infrastructure information.
