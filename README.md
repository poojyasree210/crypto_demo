# Crypto Demo

This repository contains a **Python-based cryptography demo** using the `cryptography` library (**Fernet symmetric encryption**).  
It allows encrypting and decrypting files using a generated secret key.

---

## 📂 Files in this repo

- `crypt_demo.py` → Python script for encryption/decryption  
- `test.txt` → Sample text file for demo  
- `.gitignore` → Ignores `Secret.key` to keep it safe  

> **Important:** `Secret.key` is generated automatically during encryption and is **not pushed to GitHub**.

---

## ⚙️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/poojyasree210/crypto_demo.git
   cd crypto_demo
--> Install dependencies

pip install cryptography


--> Run the demo

python crypt_demo.py

▶️ Usage

Enter E → Encrypt a file

Enter D → Decrypt a file

Provide the file name (e.g., test.txt)

Secret.key is created automatically when you encrypt a file

📝 Notes

Keep Secret.key safe if you want to decrypt files later.

.gitignore ensures that Secret.key is not uploaded to GitHub.

This demo is perfect for understanding basic encryption and decryption workflow using Python and Fernet.

