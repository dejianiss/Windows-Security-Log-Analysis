# 🛡️ Windows Security Monitoring Project

<p align="center">
  <img src="https://img.shields.io/badge/-SOC%20Project-1F6FEB?style=for-the-badge" />
  <img src="https://img.shields.io/badge/-Windows%20Security%20Monitoring-0EA5E9?style=for-the-badge" />
  <img src="https://img.shields.io/badge/-SIEM%20Simulation-10B981?style=for-the-badge" />
</p>

---

## 👤 Project Owner
**Gabriel Anigboro**

---

## 🎯 Objective
The Windows Security Monitoring Project aimed to build a SOC-style monitoring environment for tracking authentication activity on a Windows system. The project focuses on collecting, analyzing, and visualizing login events using Windows Security Logs, PowerShell automation, and a Python Flask dashboard.

The goal is to simulate real-world Security Operations Center (SOC) log monitoring and improve detection of successful and failed login attempts using Event IDs 4624 and 4625.

---

## 🧠 Skills Learned
- Windows Security Event Log analysis (Event ID 4624 & 4625)
- SOC Tier 1 log monitoring workflows
- Windows audit policy configuration (secpol.msc)
- PowerShell automation using `Get-WinEvent`
- CSV log extraction and processing
- SIEM-style dashboard development using Python Flask
- Security event correlation and user activity tracking
- Basic detection and investigation techniques

---

## 🛠️ Tools Used

<p align="left">

<img src="https://img.shields.io/badge/-Windows_Event_Viewer-1F6FEB?style=for-the-badge&logo=windows&logoColor=white" />
<img src="https://img.shields.io/badge/-Windows_Security_Logs-0EA5E9?style=for-the-badge&logo=windows&logoColor=white" />
<img src="https://img.shields.io/badge/-PowerShell-2563EB?style=for-the-badge&logo=powershell&logoColor=white" />
<img src="https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/-Flask-000000?style=for-the-badge&logo=flask&logoColor=white" />
<img src="https://img.shields.io/badge/-Windows%20Audit%20Policy-4B5563?style=for-the-badge&logo=windows&logoColor=white" />
<img src="https://img.shields.io/badge/-CSV%20Logs-F59E0B?style=for-the-badge&logoColor=white" />

</p>

---

## 🏗️ Architecture Flow

User Login
↓
Windows Security Logs
↓
Event Viewer / PowerShell (Get-WinEvent)
↓
CSV Log File
↓
Flask Web Dashboard

## Steps

StepsRef 1: Windows Security Event Viewer - Audit FailureThis screenshot captures a Windows Event Properties dialog for Event ID 4625. It shows an "Audit Failure" log within the Simplilearn enterprise lab infrastructure where an account failed to log on at 1:38 PM.Event Viewer - Audit Failure Event 4625

<p><strong>Ref 1: Windows Security Event Viewer - Audit Failure</strong><br>
This screenshot captures a Windows Event Properties dialog for Event ID 4625. It shows an "Audit Failure" log within the Simplilearn enterprise lab infrastructure where an account failed to log on at 1:38 PM.</p>
<img src="Screenshot 2026-06-23 at 15.50.24.png" width="700" alt="Event Viewer - Audit Failure Event 4625">
<p>Event Viewer - Audit Failure Event 4625</p>


**Ref 2: Windows Security Event Viewer - Audit Failure**
This screenshot captures a Windows Event Properties dialog for Event ID 4625. It shows an "Audit Failure" log within the Simplilearn enterprise lab infrastructure where an account failed to log on at 1:38 PM. 

<img src="path/to/your/audit_failure_screenshot.png" width="700" alt="Event Viewer - Audit Failure Event 4625">

**Ref 3: Windows Security Event Viewer - Audit Success**
This screenshot captures a Windows Event Properties dialog for Event ID 4624 within the same lab environment. It highlights an "Audit Success" log, confirming that an account successfully logged on at 1:49 PM.

<img src="path/to/your/audit_success_screenshot.png" width="700" alt="Event Viewer - Audit Success Event 4624">

