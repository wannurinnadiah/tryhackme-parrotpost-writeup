# tryhackme-parrotpost-writeup
Writeup for TryHackMe ParrotPost room

**Objective**

The goal of this room is to enumerate a vulnerable web application, identify exposed credentials, gain initial access to the system, and escalate privileges to obtain full control.

**Tools Used :**

1) Nmap
2) Gobuster
3) Web Browser (Manual Inspection)
4) SSH
5) Linux Enumeration Commands

**Step 1: Network Enumeration**

An Nmap scan was performed to identify open ports and running services on the target machine.

**Step 2: Web Enumeration**

The HTTP service was explored using a browser and directory brute-forcing to identify hidden paths and accessible resources.

**Step 3: Credential Discovery**

During web enumeration, sensitive information was discovered that exposed valid user credentials.

**Step 4: Initial Access**

Using the discovered credentials, SSH access was successfully obtained, granting a low-privileged shell on the system.

**Step 5: Privilege Escalation**

System enumeration revealed misconfigurations that allowed privilege escalation to the root user.

**Conclusion**

The ParrotPost room demonstrates the risks of exposed credentials and improper privilege management. Proper access control and secure configuration are essential to prevent such attacks.



