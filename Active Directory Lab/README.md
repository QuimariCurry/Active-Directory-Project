## 🛡️ Active Directory + Atomic Red Team Project
* Simulating RDP Authentication Attacks in a Controlled Environment Using VirtualBox

## Overview
* This project is a hands‑on cybersecurity lab where I used Atomic Red Team to simulate adversary techniques against a Windows Server Active Directory environment. I paired these simulations with Kali Linux tools (Crowbar) to observe authentication behavior, analyze failures, and understand how RDP authentication is handled in real environments.

## Tools Used
* Atomic Red Team (attack simulation)
* Windows Server (Active Directory + RDP)
* Windows 11 (Endpoint)
* Ubuntu Server (Splunk Server)
* Kali Linux
* Crowbar
* Sysmon
* Draw.io (network diagram)

## 🔧 What I Configured
* Windows Server
- Created AD domain
- Added users and groups
- Enabled RDP
- Configured authentication policies

* Windows 11 Endpoint
- Installed Sysmon
- Configured Sysmon XML
- Forwarded logs to Splunk

* Splunk
** Installed on Ubuntu
** Configured data inputs

* Verified ingestion of:
- Security logs
- Sysmon logs
- System logs
- Application logs

*Kali Linux
- Used Crowbar to test RDP authentication
- Observed how Windows logs failed attempts
Installed Atomic Red Team 

## Inspired by:
MyDFIR Active Directory Project (https://youtu.be/5OessbOgyEo?si=7M_svQ5WcAXlvc1U)
