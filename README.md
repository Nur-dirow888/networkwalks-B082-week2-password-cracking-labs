# Week 3 – Password Cracking Labs

## 📌 Overview

This repository documents my Week 3 cybersecurity practical labs focused on password cracking and password security.

The labs demonstrate how password-protected files can be analyzed by extracting their password hash and using password-cracking tools to recover the original password.

## 🎯 Learning Objectives

By completing these labs, I learned:

- What password hashing is
- The difference between hashing and encryption
- How password-protected PDF hashes can be extracted
- How John the Ripper can be used for password recovery
- How Networkwalks Hash Calculator and Password Cracker work
- Why weak passwords are easier to crack
- Why strong and unique passwords are important
- How password cracking can be used for authorized security testing

---

## 🧪 Project Module 1 & 2 – Password Cracking with John the Ripper and with Networkwalks

### Tools Used

- Windows OS.
- John the Ripper
- Johnny GUI
- PDF hash extraction tool
- Networkwalks password cracker

### Workflow

```text
Password-Protected PDF
        ↓
Extract Password Hash
        ↓
Save Hash
        ↓
Load Hash into Johnny
        ↓
Start Password Cracking
        ↓
Recover Password
        ↓
Unlock PDF

###🛡️ Security Takeaways

These practical labs demonstrated several important password-security concepts:

- Password-protected files can be analyzed by extracting the password hash and using password-cracking techniques.
- Password strength has a direct impact on the time required to recover a password.
- Weak and commonly used passwords are more susceptible to password-cracking attacks.
- Password hashes should be protected because attackers may attempt offline cracking if they obtain them.
- Hashing and encryption are different concepts: encryption is designed to be reversible with the appropriate key, while hashing is generally a one-way process.
- Password-cracking tools such as John the Ripper can be useful for authorized security assessments and password-strength testing.
- Security professionals should use strong, complex, and unique passwords to reduce the risk of successful password attacks.
- Password-cracking techniques should only be performed against systems or files where explicit authorization has been granted.

### Key Security Lesson

> A strong password is an important layer of defense because password complexity directly affects the difficulty and time required for password recovery.
