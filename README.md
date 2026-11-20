<p align="center">
  <img src="./assets/header.svg" alt="maapik — DFIR, Reverse Engineering &amp; CTF" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Focus-DFIR_%26_Reverse-00f5d4?style=for-the-badge&labelColor=090d16" alt="Focus" />
  <img src="https://img.shields.io/badge/University-RTU_MIREA-38bdf8?style=for-the-badge&labelColor=090d16" alt="RTU MIREA" />
  <img src="https://img.shields.io/badge/Platforms-HTB_%E2%80%A2_THM_%E2%80%A2_CTF-818cf8?style=for-the-badge&labelColor=090d16" alt="Platforms" />
  <img src="https://img.shields.io/badge/Stack-Python_%E2%80%A2_.NET_%E2%80%A2_Docker-10b981?style=for-the-badge&labelColor=090d16" alt="Stack" />
</p>

```yaml
handle:   maapik
track:    Информационная безопасность в правоохранительной системе (РТУ МИРЭА)
focus:    Компьютерная экспертиза (DFIR), Incident Response & Reverse Engineering
goal:     Разбор реальных инцидентов, артефактов ОС и бинарного анализа от CTF до прода
```

Собираю здесь свои расследования, лабораторные работы, CTF-врайтапы и pet-проекты. Копаюсь в журналах событий Windows, файловой системе NTFS, фишинговых кампаниях и декомпилированном коде.

---

## 🛠️ Арсенал и инструменты

<p>
  <strong>DFIR &amp; Incident Response</strong><br />
  <img src="https://img.shields.io/badge/Windows_Event_Logs-(.evtx)-0078D6?style=for-the-badge&labelColor=0d1117" alt="EVTX" />
  <img src="https://img.shields.io/badge/EZ_Tools-MFTECmd_%E2%80%A2_Timeline_Explorer-00b4d8?style=for-the-badge&labelColor=0d1117" alt="EZ Tools" />
  <img src="https://img.shields.io/badge/NTFS_Artifacts-%24MFT_%E2%80%A2_%24J-0ea5e9?style=for-the-badge&labelColor=0d1117" alt="NTFS" />
  <img src="https://img.shields.io/badge/MITRE_ATT%26CK-Kill_Chain-ef4444?style=for-the-badge&labelColor=0d1117" alt="MITRE ATT&CK" />
  <img src="https://img.shields.io/badge/Malware_Triage-olevba_%E2%80%A2_pcode2code_%E2%80%A2_pescan-f97316?style=for-the-badge&labelColor=0d1117" alt="Malware Triage" />
  <img src="https://img.shields.io/badge/Email_%26_OSINT-.eml_%E2%80%A2_exiftool_%E2%80%A2_VirusTotal-10b981?style=for-the-badge&labelColor=0d1117" alt="OSINT" />
</p>

<p>
  <strong>Reverse Engineering &amp; CTF</strong><br />
  <img src="https://img.shields.io/badge/IDA_Pro-Hex--Rays_F5-818cf8?style=for-the-badge&labelColor=0d1117" alt="IDA Pro" />
  <img src="https://img.shields.io/badge/pwntools-ELF_Analysis-6366f1?style=for-the-badge&labelColor=0d1117" alt="pwntools" />
  <img src="https://img.shields.io/badge/Hack_The_Box-Sherlocks_%26_RE-9FEF00?style=for-the-badge&logo=hackthebox&logoColor=9FEF00&labelColor=0d1117" alt="Hack The Box" />
  <img src="https://img.shields.io/badge/TryHackMe-Web_%26_Labs-C1121F?style=for-the-badge&logo=tryhackme&logoColor=white&labelColor=0d1117" alt="TryHackMe" />
  <img src="https://img.shields.io/badge/Web_Tools-DevTools_%E2%80%A2_sqlmap_%E2%80%A2_gobuster-f59e0b?style=for-the-badge&labelColor=0d1117" alt="Web Tools" />
</p>

<p>
  <strong>Dev &amp; Infrastructure</strong><br />
  <img src="https://img.shields.io/badge/Python-Scripting_%26_CTF-3776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=0d1117" alt="Python" />
  <img src="https://img.shields.io/badge/C%23-.NET_8_%E2%80%A2_Blazor_%E2%80%A2_EF_Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white&labelColor=0d1117" alt="C# .NET" />
  <img src="https://img.shields.io/badge/SQLite-Database-003B57?style=for-the-badge&logo=sqlite&logoColor=white&labelColor=0d1117" alt="SQLite" />
  <img src="https://img.shields.io/badge/Docker-Containers_%E2%80%A2_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white&labelColor=0d1117" alt="Docker" />
  <img src="https://img.shields.io/badge/Linux-WSL_%E2%80%A2_CLI-FCC624?style=for-the-badge&logo=linux&logoColor=black&labelColor=0d1117" alt="Linux" />
</p>

---

## 📂 Репозитории

| Проект | Описание | Стек |
| :--- | :--- | :--- |
| 🔍 **[cybersec-writeups](https://github.com/maapik/cybersec-writeups)** | Архив расследований (DFIR / IR), реверс-инжиниринга, OSINT-отчётов и Web CTF разборов | `DFIR` `EVTX` `$MFT` `IDA Pro` `CTF` |
| 💳 **[FinanceTracker](https://github.com/maapik/FinanceTracker)** | Веб-приложение для учёта личных финансов с персистентной БД в контейнере | `C#` `.NET 8` `Blazor` `SQLite` `Docker` |

---

## 🎯 Избранные разборы (Featured Cases)

| Направление | Кейс | Что внутри |
| :--- | :--- | :--- |
| `DFIR` | **[RomCom — WinRAR `CVE-2025-8088`](https://github.com/maapik/cybersec-writeups/blob/main/dfir-ir/htb-sherlocks/romcom-winrar-cve-2025-8088.md)** | Разбор `$MFT` и `$J` через `MFTECmd` и `Timeline Explorer`, фиксация `ObjectIdChange`, поиск бэкдора и автозапуска `T1547.009` |
| `IR / EVTX` | **[Operation Blackout 2025: Smoke & Mirrors](https://github.com/maapik/cybersec-writeups/blob/main/dfir-ir/htb-sherlocks/operation-blackout-smoke-and-mirrors.md)** + **[Anti-VM](https://github.com/maapik/cybersec-writeups/blob/main/dfir-ir/htb-sherlocks/operation-blackout-anti-vm.md)** | Расследование отключения LSA Protection и Defender, патч `AmsiScanBuffer`, детекция `Check-VM` (Nishang) в PowerShell `.evtx` |
| `Forensics` | **[Лаба №1 (РТУ МИРЭА): Инцидент на Windows Server](https://github.com/maapik/cybersec-writeups/blob/main/dfir-ir/university-mirea/lab-01-windows-server-incident.md)** | Построение таймлайна заражения и установление причастности по `System.evtx` (Event ID `7045`), `Security.evtx` и SID |
| `Reverse` | **[FlagCasino (Hack The Box)](https://github.com/maapik/cybersec-writeups/blob/main/reverse-engineering/htb/flag-casino.md)** | Статический анализ ELF в IDA Pro (`F5`), эксплуатация предсказуемого `srand()`/`rand()` через Python `ctypes` + `pwntools` |
| `Threat Intel` | **[Operation Dream Job-2 — APT Lazarus](https://github.com/maapik/cybersec-writeups/blob/main/dfir-ir/htb-sherlocks/dream-job-2-lazarus.md)** | Маппинг по MITRE ATT&CK, анализ ISO/PE (`isoinfo`, `exiftool`, `pescan`) и декомпиляция p-code при VBA Stomping (`pcode2code`) |

---

<p align="center">
  <img src="./assets/footer.svg" alt="0xDEADBEEF // EOF // github.com/maapik" />
</p>
