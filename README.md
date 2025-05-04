# 👋 Hi, I'm Raimund Pließnig – also known as *The Mompfdie*

Welcome to my GitHub profile. I'm an experienced systems engineer and security-focused automation developer based in Austria 🇦🇹.  
I work professionally at A1 Telekom Austria and also maintain a structured **HomeLab environment**, where I develop and test enterprise-grade solutions for:

- Microsoft Public Key Infrastructure (PKI)
- PowerShell tooling & automation
- Hybrid Identity (Active Directory ↔ Entra ID)
- Windows Server, SQL Server, and Proxmox virtualization
- Monitoring & Reporting (Zabbix, ioBroker, custom dashboards)

---

## 🧰 Key Skills

| Area                    | Tools / Technologies                                      |
|-------------------------|------------------------------------------------------------|
| **Scripting & Dev**     | PowerShell 5/7, .NET (C#), GitHub Actions, REST APIs       |
| **Infrastructure**      | Active Directory, DNS/DHCP, GPO, T0 Hardening, WinRM/SSL   |
| **PKI & Security**      | MS ADCS, Tiering Model, Certificate Templates, KRA, S/MIME |
| **Cloud & Hybrid**      | Microsoft 365, Entra ID Connect, Exchange Online           |
| **Data & Monitoring**   | SQL Server, ADO.NET, Zabbix, PostgreSQL, ioBroker          |
| **Private Projects**    | Proxmox VE, Let's Encrypt, Home Assistant, Raspberry Pi    |

---

## ⚙️ Projects

### 🔐 EnvGuardSuite *(private, in development)*
> A PowerShell module for operational support, security checks and configuration audits in Windows & hybrid environments.

- Modular architecture with support for Windows & Linux (PowerShell 7)
- Built-in event logging (`Environment Guard Suite`)
- Functions for GPO inspection, AD object validation, baseline checks, and reporting
- Customizable logging (event log + file)
- Designed for: **Enterprise IT**, **Security Reviews**, **Scheduled Audits**

---

### 🧾 IceSelfCheckIn *(private, in development)*
> .NET Core-based self check-in web app with Active Directory integration for secure visitor management.

- Built with C#, .NET Core and hosted on IIS
- User-friendly interface for guest sign-ins
- Fully domain-integrated (auth + backend)
- Backend secured via on-prem firewall & PKI
- Live URL (when public): `https://IceSelfCheckIn.die-mompfdies.at/`

---

### 🧠 SmartHome / HomeLab Projects
> Private environment for automation, logging, monitoring and smart living.

- Custom domain `mompfdie.local` with internal PKI
- VMs: `MIOB01`, `MDBQ01`, `MSQL01`, `MDOC01` etc.
- Zabbix & ioBroker for environmental data & smart energy usage
- PoE-based Raspberry Pi setup (no separate power adapters)
- Daily snapshot automation, log ingestion, and PostgreSQL storage

---

## 🛡️ Philosophy

> **"If it can’t be audited, it can’t be trusted."**

Security, repeatability and transparency are the core of my technical work.  
Every script, every deployment and every policy I write follows the principles of:

- Clear structure & error handling
- Minimal privilege access
- Logging, monitoring & alerting
- Documentation as part of the process

---

## 📫 Contact & Presence

- 🧑‍💼 [LinkedIn Profile](https://www.linkedin.com/in/raimund-plie%C3%9Fnig-a3a4b3133/)
- ☎️ Reach me via GitHub Issues or private channels for collaborations

---

## 📄 Licensing

Most of my public code will follow a permissive license (MIT or custom), but some tools will have restricted commercial usage clauses.  
Feel free to reach out if you'd like to collaborate or request access.

---

🖖 *Thanks for visiting my profile – stay secure, stay curious!*

