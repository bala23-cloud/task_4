# Password Security Analysis – Mini Guide & Report

## Overview
This project explains the basics of password security in a simple and beginner-friendly way.  
It covers how passwords are stored, common password attacks, and best practices for strong authentication.  
The goal is to understand **why weak passwords fail** and **how to protect systems** from password-based attacks.

---

## Objectives
- Learn the difference between hashing and encryption
- Identify common password hash types
- Understand password cracking techniques
- Analyze why weak passwords are insecure
- Learn the importance of MFA (Multi-Factor Authentication)
- Recommend strong authentication practices

---

## Mini Guide: Password Security

### 1. How Passwords Are Stored (Hashing vs Encryption)

**Hashing**
- Converts a password into a fixed-length hash
- One-way process (cannot be reversed)
- Used to store passwords securely

**Encryption**
- Converts data into unreadable form
- Can be reversed using a key
- Not recommended for storing passwords

**Example**
- Password: `admin123`
- MD5 Hash: `0192023a7bbd73250516f069df18b500`

---

### 2. Types of Password Hashes

| Hash Type | Description |
|---------|------------|
| MD5 | Very fast, weak, easily cracked |
| SHA-1 | Better than MD5 but broken |
| SHA-256 | Stronger but needs salt |
| bcrypt | Slow and secure, best choice |

---

### 3. Generating Password Hashes

Password hashes can be generated using:
- Linux tools (openssl)
- Online hash generators
- Security tools like Hashcat

**Example Command**
```bash
echo -n password | md5sum
