# Windows Server Security Hardening (AWS EC2)

This project demonstrates security hardening techniques implemented on a Windows Server 2022 instance hosted on AWS EC2.

The objective was to strengthen authentication security, reduce the system attack surface, and improve monitoring and logging capabilities.

---

## Environment

- Windows Server 2022
- AWS EC2
- Active Directory Domain Services
- DNS Server
- Internet Information Services (IIS)

---

## Security Hardening Controls

- User account management and least privilege enforcement
- Strong password policies
- Disable LAN Manager hash storage
- Disable NTLM authentication where possible
- Credential Guard implementation
- Service hardening and attack surface reduction
- Removal of legacy protocols (SMBv1, PowerShell 2.0)
- Windows Defender and Firewall protection
- Security auditing and PowerShell logging
- DNS activity monitoring
- Automated patch management

---

## Security Impact

These configurations significantly improve the defensive posture of the system by reducing attack vectors, strengthening authentication mechanisms, and improving visibility into system activity.

---

## Full Report

You can view the full security hardening assessment report here:
https://github.com/hammakjaff-netizen/windows-server-security-hardening/blob/f77de975406bb282a72c9435a640153a66d5b859/Windows%20Server%20Security%20Hardening%20and%20System%20Configuration%20Assessment.pdf
