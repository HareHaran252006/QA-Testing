<h1 align="center">🧪 Tichi Web Application - QA Testing Project</h1>

<p align="center">
Manual Testing • Automation Testing • Bug Reporting
</p>

---

<h2>📌 Project Overview</h2>

This repository contains the Quality Assurance testing artifacts for the <b>Tichi Web Application</b>. The project demonstrates both <b>Manual Testing</b> and <b>Automation Testing</b> using industry-standard testing practices.

The repository includes:

✅ Test Case Documentation

✅ Bug Reports

✅ Selenium Automation Framework

✅ Pytest Execution

✅ Allure Reporting

---

<h2>📂 Repository Structure</h2>

```text
.
├── 📄 Tichi test document.xlsx      # Manual Test Cases
├── 📄 Bug_Report_Login_Invalid_Email_GokulV.docx
├── 📁 Tichi_automation
│   ├── tests
│   ├── pages
│   ├── utilities
│   ├── reports
│   └── allure-results
└── README.md
```

---

<h2>🧪 Manual Testing</h2>

The manual testing document includes comprehensive test cases covering the Login and Signup modules.

### Features Tested

- Login Validation
- Signup Validation
- Email Validation
- Mobile Number Validation
- Name Validation
- UI Validation
- Browser Compatibility
- Network Validation
- Responsive Behaviour

---

<h2>🐞 Bug Report</h2>

### Bug Summary

| Field | Value |
|--------|-------|
| Bug ID | BUG-001 |
| Module | Authentication |
| Sub Module | Login |
| Severity | Major |
| Priority | High |
| Status | Open |

### Description

The application accepts an invalid email format (example: **gokul..v@gmail.com**) and allows the user to proceed to the password page instead of displaying an email validation error.

### Expected Result

- Invalid email should not be accepted.
- Validation message should be displayed.
- User should remain on the Login page.

### Actual Result

- Invalid email is accepted.
- User is navigated to the Password page.

---

<h2>🤖 Automation Testing</h2>

The automation framework is built using:

<table>
<tr>
<td>🐍 Python</td>
<td>Selenium WebDriver</td>
</tr>

<tr>
<td>Pytest</td>
<td>Page Object Model (POM)</td>
</tr>

<tr>
<td>Allure Reports</td>
<td>Chrome Driver</td>
</tr>
</table>

---

<h2>⚙️ Framework Structure</h2>

```text
Tichi_automation
│
├── pages/
├── tests/
├── utilities/
├── screenshots/
├── allure-results/
├── requirements.txt
└── README.md
```

---

<h2>▶️ Execute Tests</h2>

Install dependencies

```bash
pip install -r requirements.txt
```

Run all tests

```bash
pytest
```

Generate Allure Report

```bash
allure serve allure-results
```

---

<h2>🛠 Tools Used</h2>

- Python
- Selenium
- Pytest
- Allure Report
- VS Code
- Git
- GitHub
- Chrome Browser

---

<h2>📊 Testing Deliverables</h2>

| Deliverable | Status |
|-------------|--------|
| Manual Test Cases | ✅ |
| Bug Report | ✅ |
| Selenium Automation | ✅ |
| Test Execution | ✅ |
| Allure Report | ✅ |

---

<h2>🎯 Objectives</h2>

- Validate application functionality.
- Identify functional defects.
- Automate repetitive test scenarios.
- Generate execution reports.
- Improve software quality.

---

<h2>👨‍💻 Author</h2>

<b>HareHaran T J</b>

QA Engineer | Manual Testing | Selenium Automation | Python

---

<h2 align="center">⭐ If you found this project useful, consider giving it a star!</h2>
