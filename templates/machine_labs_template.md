# 💀 [Machine Name]

> 🔐 Attack Chain: Web Exploitation -> Privilege Escalation

**Platform:** HTB / THM / PG  
**OS:** Linux / Windows  
**Difficulty:** Easy / Medium  

## 🧾 Summary

Briefly describe full compromise in one sentence.

> e.g., Gained initial access via RCE and escalated to root via misconfigured sudo.

## 🔗 Attack Path

Initial access -> privilege escalation -> root

## 🧨 Initial Access

[Vector]

- **Service:** [e.g., HTTP :80]
- **Vulnerability:** [e.g., RCE in outdated plugin]

## ⚡ Privilege Escalation

[How you became root/admin]

- **Method:** [e.g., Sudo misconfiguration]
- **Vector:** [e.g., NOPASSWD on python]

## 🛠️ Exploit

```bash
# initial access
python3 exploit.py http://target --payload shell

# privesc
sudo -l
sudo python3 -c 'import os; os.system("/bin/bash")'
````

## 📸 Evidence

- user: `whoami`
- root: `root.txt`

## 🛡️ Fix

- Patch vulnerable service
- Remove dangerous sudo permissions
- Secure sensitive files

