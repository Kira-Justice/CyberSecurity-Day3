# 💀 SUID & SGID

## 🔹 SUID
SUID allows a file to run with the permissions of the file owner.

Example:
-rwsr-xr-x (s indicates SUID)

---

## 🔹 SGID
SGID allows execution with group permissions.

---

## ⚠️ Security Risk
If a SUID file is vulnerable:
- Attacker can execute commands as root
- Leads to privilege escalation

---

## 🔍 Finding SUID Files
find / -perm -4000 2>/dev/null

---

## 🛡️ Defense
- Remove unnecessary SUID permissions
- Audit system regularly
- Apply least privilege
