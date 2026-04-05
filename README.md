# 🔐 Secure File Portal with AES Encryption

A secure web-based file upload and download portal built using **Python Flask**.  
All uploaded files are encrypted using **AES encryption (Fernet)** before being stored on the server and decrypted only at download time.

This project demonstrates **secure file handling**, **basic cryptography**, and **key management best practices**, making it suitable for **cybersecurity internships, academic projects, and portfolios**.

---

## 📌 Features

- ✅ Secure file upload and download
- 🔒 AES encryption for all files at rest
- 🗝️ Encryption key stored securely using environment variables
- 🖥️ Simple and user-friendly web interface
- 🛡️ Temporary decrypted files (auto-cleanup)
- 📄 Well-structured and commented code

---

## 🛠️ Technologies Used

### Backend
- Python 3.x
- Flask  
  https://flask.palletsprojects.com/en/latest/

### Cryptography
- Cryptography (Fernet – AES encryption)  
  https://cryptography.io/

### Frontend
- HTML
- CSS
- JavaScript

### Tools
- Git & GitHub  
- Postman / curl (for API testing)
