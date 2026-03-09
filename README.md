# 🚫 PreventRemoteConnections

> PowerShell script to **block all remote access** — RDP, Remote Assistance, PSRemoting, WinRM, Telnet, SMB, Wake-on-LAN, SSH, VNC, UPnP. Adds firewall rules.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🔒 **RDP** | fDenyTSConnections=1, TermService disabled |
| 🚫 **Remote Assistance** | fAllowToGetHelp=0 |
| 🚫 **PSRemoting/WinRM** | Disabled |
| 🚫 **SMB** | SMB1/SMB2 disabled |
| 🚫 **Firewall** | Blocks 3389, 445, 139, 137-138, 5985, 5986, 23 |
| 🚫 **UPnP** | SSDPSRV, upnphost disabled |

---

## 📋 Requirements

| Requirement | Details |
|-------------|---------|
| **OS** | Windows 10/11 |
| **PowerShell** | 5.1+ |
| **Privileges** | Administrator |

---

## 🚀 Usage

```powershell
.\PreventRemoteConnections.ps1
```

---

<p align="center">
  <sub>🛡️ Gorstak Security Hardening</sub>
</p>
