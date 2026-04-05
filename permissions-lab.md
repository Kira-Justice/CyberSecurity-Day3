# 🔐 Linux Permissions Lab

## 📌 Creating File
touch testfile.txt

## 📌 Changing Permissions
chmod 744 testfile.txt

## 📌 Changing Ownership
sudo chown user:user testfile.txt

## 📌 Checking Permissions
ls -l testfile.txt

---

## 🧠 Understanding 744
- User: rwx (7)
- Group: r-- (4)
- Others: r-- (4)

---

## ⚠️ Security Insight
Permissions define who can access or modify files. Misconfigured permissions can lead to unauthorized access.
