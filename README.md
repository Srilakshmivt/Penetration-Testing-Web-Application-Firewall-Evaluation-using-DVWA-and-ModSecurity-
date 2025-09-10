# Penetration-Testing-Web-Application-Firewall-Evaluation-using-DVWA-and-ModSecurity-
Objective of the project (to demonstrate common web attacks and defense using ModSecurity).  Tools used (DVWA, Kali Linux, Burp Suite, sqlmap, ModSecurity, OWASP CRS).  Key findings (e.g., DVWA is vulnerable without WAF, but ModSecurity blocks most attacks).
DVWA + ModSecurity Web Application Security Project
Project Overview

This project demonstrates web application security testing using DVWA (Damn Vulnerable Web Application) with a ModSecurity WAF deployed on Ubuntu. The main objective is to simulate real-world attacks and evaluate the effectiveness of a Web Application Firewall in protecting against them.

Through this lab, I performed attacks such as:

SQL Injection (SQLi)

Cross-Site Scripting (XSS)

Command Injection

File Upload Exploits

The project highlights both offensive (attacker) and defensive (WAF) perspectives in a controlled lab environment using Kali Linux.

Lab Setup :

Target System

Ubuntu Server with Apache2, PHP, MariaDB

DVWA installed and configured

ModSecurity WAF with OWASP Core Rule Set (CRS)

Attacker Machine

Kali Linux with sqlmap and Burp Suite

Web browser for accessing DVWA and testing attacks.

Tool	             Purpose in Project
DVWA	             Target vulnerable web application
Ubuntu             Server	Hosts DVWA, Apache, MariaDB, and ModSecurity
Kali Linux	       Launches attacks and penetration testing
ModSecurity (OWASP CRS)	Blocks malicious requests and logs attacks
sqlmap	           Automates SQL Injection attacks
Burp Suite	       Intercepts and modifies HTTP requests, inspects cookies, validates WAF.

Key Learnings

Web applications are highly vulnerable without proper security controls.

ModSecurity WAF effectively blocks most common web attacks.

Manual testing, automated tools, and log analysis are critical for penetration testing.

Offensive and defensive security skills complement each other for a stronger security posture.
