# Important Notes on Windows Activation Methods

## Activation Types & Validity
- **Digital License (HWID):** Windows 10 – Permanent Activation
- **KMS38:** Windows 10 / Server – Active Until 2038
- **Online KMS:** Windows / Server / Office – 180 Days (Renewal task required for auto lifetime activation)

## Key Points for Digital License (HWID) Activation
- Supported **ONLY** for Windows 10.
- Permanent activation tied to system hardware; stored on Microsoft servers.
- Hardware changes (e.g., motherboard) may require reactivation if not linked to a Microsoft account.
- Requires Windows Update Service and internet for initial activation.
- Auto reactivates after reinstall if Retail media is used. VL media requires Retail/OEM key input.

### Common Activation Failures
- No internet / Windows Update disabled
- VPN, custom hosts file, or firewall interference
- Corrupt system files / Microsoft server issues

## Unsupported Products
- **Office Retail (MSI Retail 2010/2013)**
- **Windows Evaluation Editions**
- **Windows 7** (Starter, HomeBasic, HomePremium, Ultimate)
- **Windows 10** (Cloud S, IoTEnterprise, ProfessionalSingleLanguage, etc.)
- **Windows Server** (Foundation, Storage Server, Home Server 2011, etc.)

## Limited KMS Activation Periods
- **Windows 10 Home variants:** Max 45 days
- **Windows 8.1 Core, Pro with Media Center, Pro Student:** Max 45 days
- **Windows 8 Core, Pro with Media Center:** Max 30 days

## Note
- Supported products only need GVLK (KMS key); volume conversion is not required.
- KMS Activation is compatible with **MBR, GPT, UEFI, and BIOS** systems.

---

## 💜 Credits
This guide is based on the work from the **Microsoft Activation Scripts (MAS)** project, maintained by @WindowsAddict, with contributions from @mspaintmsi, @vyvojar, @sponpa, @leitek8, @abbodi1406, @AveYo (@BAU), and other talented developers.

GitHub: https://github.com/massgravel/Microsoft-Activation-Scripts
GitLab: https://gitlab.com/massgrave/microsoft-activation-scripts

## 🌟 Special Thanks
- @RPO, @s1ave77, @hearywarlot, @dbenham, @Ratiborus, @mxman2k, @Yen
- @BorrowedWifi for grammar corrections
- @Chibi ANUBIS for ARM64 testing

---

## 🎓 License
This project is open-source and licensed under the **MIT License**.

