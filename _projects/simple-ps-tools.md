# 🧰 Tools for Power Users: From PS2EXE GUI to Windows Triage

Welcome to the mell0wx toolbox – a growing collection of practical, efficient, and GUI-friendly tools for Windows users, sysadmins, and cybersecurity enthusiasts. This post highlights four of my recent creations, each solving a real-world problem with a simple and user-friendly interface. Whether you're packaging PowerShell scripts, investigating suspicious logs, organizing files, or inspecting your hardware – there's something here for you.

---

## 📦 PS2EXE GUI – Turn PowerShell Scripts into Executables (The Easy Way)

**Problem:** Turning a PowerShell script into a `.exe` typically requires command-line know-how and pre-installed modules.

**Solution:** **PS2EXE GUI** makes the entire process as easy as clicking a button.

### 🔧 Features:
- Auto-checks for the `PS2EXE` module and installs it if needed.
- Graphical interface to choose:
  - PowerShell input file
  - Custom `.ico` file
  - Output `.exe` path (auto-filled based on input)
- Handles permissions gracefully and requires no CLI usage.

**Use Case:** Package any PowerShell automation script (like the ones below!) into a portable `.exe` – perfect for deployments or users without PowerShell knowledge.

📎 [Explore the PS2EXE GUI Tool on GitHub](https://github.com/mell0wx/ps1-execonv)

---

## 🕵️‍♂️ Windows Log Triage Tool – A Cybersecurity Sidekick

**Problem:** Windows Event Viewer is powerful, but searching for suspicious logs manually is time-consuming and clunky.

**Solution:** **Windows Log Triage Tool** delivers a slick GUI for log review and exports.

### 🔍 Features:
- Load and scan key event logs (Security, Sysmon, etc.).
- Filters for:
  - Date ranges
  - Specific users
  - Keyword search
- Export suspicious activity to CSV
- Resizable GUI for all screen sizes

**Use Case:** Incident response, red/blue team training, or curious end-users who want to peek into what their system’s been up to.

📎 [View the Windows Triage Tool on GitHub](https://github.com/mell0wx/windows-log-triage)

---

## 📁 mell0wx-mover – A Smarter Auto File Organizer

**Problem:** Downloads folders get messy. Sorting manually is a waste of time.

**Solution:** **mell0wx-mover** is your background file ninja.

### 🧠 Features:
- Automatically sorts files into folders based on type and date.
- Includes a GUI scheduler to control when and how often it runs.
- Set custom log file locations to keep track of movements.
- Packaged as a `.exe` with an icon for easy usage.

**Use Case:** Maintain an organized workspace or shared drive without lifting a finger.

📎 [Download mell0wx-mover on GitHub](https://github.com/mell0wx/mell0wx-mover)

---

## 🖥️ Hardware Info Viewer – System Specs at a Glance

**Problem:** Getting accurate hardware info usually means digging through `Device Manager` or running CLI commands.

**Solution:** **Hardware Info Viewer** presents everything you need in a clean, toggleable GUI.

### ⚙️ Features:
- Displays key hardware info:
  - CPU
  - RAM
  - Motherboard
  - GPU
  - Storage
- Toggleable dark mode
- Clean UI built with a minimalist aesthetic

**Use Case:** Whether you're benchmarking, upgrading, or just curious – this tool helps you see what’s under the hood in seconds.

📎 [Try the Hardware Info Tool on GitHub](https://github.com/mell0wx/HWMonx)

---

## 💬 Final Thoughts

These tools were built with the everyday power user in mind – combining automation, security, and usability. They're free, open-source, and designed to be extended or forked. Whether you're a tech enthusiast, IT professional, or casual user, these utilities aim to save time and reduce friction in your daily workflows.

---

🔗 **Stay connected:**  
GitHub: [mell0wx](https://github.com/mell0wx)  
Coming soon: more purple teaming tools, labs, and threat emulation utilities!

*If you find any of these tools useful, feel free to star the repo, submit issues, or suggest features!*
