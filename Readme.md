# 📦 Windows Setup Utility | Made by N1zyyy (N1zyx3)

**Interactive PowerShell script to install apps via WinGet with menu-based prompts.**

This script helps automate the installation of common software (browsers, messengers, custom apps) on a Windows system using **WinGet**. It provides an interactive text menu and supports selecting apps by number or custom search/install

---

## 🧠 Features

- 🖥️ Installs popular web browsers: Chrome, Firefox, Brave, Opera  
- 💬 Installs selected messengers (Telegram, Discord, WhatsApp)  
- 🔍 Allows custom search & install using WinGet  
- 📈 Shows results and errors clearly  
- 🛠️ Simple interactive menu — no parameters required  

---

## 📋 Requirements

✔️ Windows 10/11 or newer  
✔️ **WinGet** must be installed and available in PATH  
> If WinGet is not found, the script will prompt you to install it first

---

## 🚀 How to Use
1. Run Powershell as administrator
2. Write:
    ```sh
    irm https://raw.githubusercontent.com/N1zyx3/WinSetUtil/refs/heads/main/winSetUtil.ps1 | iex
