# Password Cracking Practice using John the Ripper (Kali Linux)

## Overview
This task focuses on understanding how password hashes work and how weak passwords can be cracked using **John the Ripper** in Kali Linux.  
The practice is done using **sample/demo hashes only** for educational purposes.

---

## Objectives
- Understand how passwords are stored as hashes
- Identify different hash types
- Practice cracking weak password hashes
- Learn dictionary and brute-force attacks
- Understand why strong passwords and MFA are important

---

## Tools Used
- Kali Linux
- John the Ripper
- Nano text editor
- RockYou wordlist

---

## Sample Hashes Used
These hashes are intentionally weak and created for practice only.

| Hash Type | Sample Hash |
|---------|-------------|
| MD5 | 5f4dcc3b5aa765d61d8327deb882cf99 |
| SHA-1 | f865b53623b121fd34ee5426c792e5c33af8c227 |
| SHA-256 | e0e609c7a9b9c25a6f5d41b5f0d7dceeea8e4a5f0e7a3f1b4d3a9b4d5e6f7a8 |
| bcrypt | $2y$10$Wq2YzQmZJY1UO9w7lHjJ4uY9h7G2sV2dZzZJ7Yq1Zx1pXbN0ZkDqC |

---

## Steps Performed

### 1. Create Hash File
```bash
nano john_hashes.txt
