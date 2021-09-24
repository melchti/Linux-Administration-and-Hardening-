# Linux-Administration-and-Hardening-
This assignment demonstrates how a system administrator works to troubleshoot and fix a malfunctioning server. 


This unit introduces Linux operating systems and the basics of IT system administration. A strong knowledge of Linux is essential for many technical cybersecurity roles. Most computers that security professionals interact with are Linux computers, and much of their work involves configuring and networking them securely.

This unit prepared me for system administration roles by covering the foundational knowledge of users, groups, permissions, and access controls.

The Scenario for this assignment was as follows:

•	I acted acted as system administrator in order to troubleshoot a malfunctioning server.

•	The senior administrator was quite pleased with my work. Now, they would like you to prepare another server to replace this server. I was tasked with completing the steps below to prepare a new server.


Steps used to complete task:

1.	I went into the /etc/ directory where system configuration files exist. 
2.	I changed the read and write permissions for:
      -/etc/shadow, /etc/gshadow, /etc/group and etc/passwd/
3.	I used sudo access to add user accounts for “sam”, “joe”, “Amy”, “sara”, and “admin”.
4.	I made sure that only the “admin” user has general sudo group access.
5.	I added users “sam”, “joe”, “amy”, and “sara” to the newly created “engineers” group
6.	I  create a shared folder for this group: /home/engineers.
7.	I change ownership on the new “engineers” shared folder to the “engineers” group.
8.	I Installed the Lynis package to my system for auditing.
9.	I ran a Lynis system audit with sudo access.
10.	I installed chkrootkit and ran it in expert mode

