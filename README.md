# 🚀 Postman Newman API Automation Framework

![API Testing](https://img.shields.io/badge/Testing-API-green?style=for-the-badge&logo=postman)
![Automation](https://img.shields.io/badge/Automation-Newman-orange?style=for-the-badge&logo=node.js)
![Reports](https://img.shields.io/badge/Reports-HtmlExtra-blue?style=for-the-badge)

This project contains a professional **API Testing Suite** built with Postman and executed via Newman. It is designed to ensure the reliability and performance of RESTful services through automated test execution and detailed reporting.

---

## 🛠 Tech Stack

*   **API Testing:** [Postman](https://www.postman.com/) (Collection Development)
*   **Execution:** [Newman](https://www.npmjs.com/package/newman) (CLI Runner)
*   **Reporting:** [HtmlExtra Reporter](https://www.npmjs.com/package/newman-reporter-htmlextra)
*   **Runtime:** Node.js
*   **Environment:** Dotenv (Environment Variable Management)

---

## ✨ Features

*   ✅ **Automated Test Suites:** Run multiple API requests in a single command.
*   ✅ **Advanced Reporting:** Detailed HTML reports including Request/Response headers and body.
*   ✅ **Environment Management:** Uses `.env` and Postman Environment files for security and scalability.
*   ✅ **Pre-request & Test Scripts:** Custom JavaScript logic for dynamic data handling.
*   ✅ **Assertions:** Validates Status Codes, Response Time, and JSON Schema.

---

## 📂 Project Architecture

```text
├── 📂 Collections
│   └── API_Test_Collection.json
├── 📂 Environments
│   └── Production_Env.json
├── 📂 Reports
│   └── (Generated HTML/JSON Reports)
├── .env.example
├── package.json
└── README.md
```

---

## 🚀 How to Run

### 1. Clone the repository:
```bash
git clone [https://github.com/rezwanulislamrimel/postman-newman-tests.git](https://github.com/rezwanulislamrimel/postman-newman-tests.git)
cd postman-newman-tests
```

### 2. Install Dependencies:
```bash
npm install
```

### 3. Execute Tests:
```bash
newman run Collections/API_Test_Collection.json -e Environments/Production_Env.json -r htmlextra
```

---

## 📊 Reporting Summary

The **htmlextra** reporter generates a comprehensive dashboard that shows:
*   Total Requests executed vs. failed.
*   Specific reasons for assertion failures.
*   End-to-end execution time and data transfer size.

---

## 👤 Author

**Rezwanul Islam**
*SQA Engineer | Software Quality Assurance*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/rezwanulrimel/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/rezwanulislamrimel)

---
*Maintained by Rezwanul Rimel © 2026*
