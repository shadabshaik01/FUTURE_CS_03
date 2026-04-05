# 🛡️ Task 3: API Security & Risk Mitigation
**Student:** Muhammad Shadab Shaik | **CIN:** FIT/MAR26/CS7147

## 📖 Project Overview
This task involved analyzing a REST API for common security flaws listed in the **OWASP API Top 10**. I focused on identifying **Broken Object Level Authorization (BOLA)**.

## 🛠️ Tools Used
* **Postman:** For sending API requests and analyzing JSON responses.
* **Burp Suite (Optional):** For intercepting API traffic.

## 🕵️ Finding: Broken Object Level Authorization (BOLA)
While testing the `/users/` endpoint, I discovered that changing the `user_id` parameter allowed me to view unauthorized profiles. 

## 📁 Deliverables
* [📄 API Security Report](./Documentation/API_Security_Report.pdf)
* [📸 Technical Evidence](./Evidence/)
