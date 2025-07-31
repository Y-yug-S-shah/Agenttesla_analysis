# AgentTesla Malware Behavior Analysis (Joe Sandbox Public Sample)

This repo contains notes and indicators from analyzing a **real-world AgentTesla info-stealer sample** using a **Joe Sandbox public report**.

## 🔍 Sample Info
- **File Name:** Purchase Order 4500564358.exe  
- **Hash (MD5):** 9fd96b295c182c936d74dbb92a96a4d4  
- **Source:** Joe Sandbox Public Reports  
- **Platform:** Windows 10 x64 (cloud)

## 📌 Summary
- AgentTesla uses scheduled tasks and PowerShell for persistence and evasion.
- Exfiltration is done via SMTP using hardcoded credentials.
- Key TTPs include: Process Injection, Defender exclusion, Info discovery.

## 🔗 Links
- **Sandbox Report:** [Joe Sandbox Analysis](https://www.joesandbox.com/analysis/1747005/0/html)
- **YouTube:** [Defender Diary by Yug](https://www.youtube.com/@defenderdiarybyyug?sub_confirmation=1)

---

⚠️ For research and educational use only.
