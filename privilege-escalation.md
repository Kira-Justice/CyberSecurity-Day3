# 🧠 Privilege Escalation

## 🔹 What is it?
Privilege escalation is the process of gaining higher access (e.g., root) from a lower-level user.

---

## ⚠️ Causes
- Weak permissions (777)
- Misconfigured SUID files
- Vulnerable programs

---

## 💥 Example
A world-writable script used by root can be modified by attacker to execute malicious code.

---

## 🛡️ Defense
- Use least privilege
- Monitor file permissions
- Restrict sensitive files
