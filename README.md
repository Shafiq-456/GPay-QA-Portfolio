# 💳 Google Pay (Android) — Manual QA Testing Portfolio

![QA Testing](https://img.shields.io/badge/Role-Manual%20QA%20Tester-blue?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20UPI-green?style=for-the-badge)
![Methodology](https://img.shields.io/badge/Testing-Functional%20%7C%20Security%20%7C%20Edge%20Cases-orange?style=for-the-badge)

**Tester:** Mohammed Shafiq  
**Project Type:** End-to-End Manual QA Testing & Test Artifact Design  
**Target Application:** Google Pay (Android / NPCI UPI Ecosystem)

---

## 📌 Project Overview
A comprehensive manual quality assurance project simulating a real-world testing cycle on **Google Pay (Android)**. This project demonstrates core QA competencies: designing structured test plans, executing rigorous positive/negative test scenarios, identifying edge-case defects, and documenting actionable bug reports.

### Key Modules Tested
* **Authentication & Security:** SIM binding, biometric fallback, multi-factor login, background timeout session locks.
* **Transaction Engine:** Real-time peer-to-peer transfers, UPI QR code scanner integration, daily transaction limits, split bills.
* **Account Operations:** Multi-bank integration, balance verification, secure UPI PIN setup/reset.
* **Negative & Boundary Scenarios:** Zero/negative amounts, special characters in UPI IDs, interrupted network handshakes, expired QR codes.
* **UI/UX & Resilience:** Font scaling, orientation handling, screen reader compatibility, graceful degradation under low bandwidth.

---

## 🛠️ Testing Methodologies Applied

* **Black-Box Functional Testing:** Validating system flows against standard financial transaction requirements.
* **Boundary Value Analysis (BVA) & Equivalence Partitioning (EP):** Transfer limits (`₹0`, `₹0.01`, `₹1,00,000`, `₹1,00,01`), UPI ID character validations.
* **Security & Session Testing:** Preventing clipboard sniffing of sensitive PINs, screenshot blocking on secure screens, session termination on app minimize.
* **Defect Lifecycle Management:** Tracking defects with reproduction steps, severity, priority, and root cause context.

---

## 📊 Test Execution Summary

| Metric | Value | Notes |
| :--- | :---: | :--- |
| **Total Test Cases Planned** | `35` | 100% test scenario coverage across core modules |
| **Test Cases Executed** | `35` | Executed against actual Android builds |
| **Passed Test Cases** | `35` | Post-retest verification |
| **Defects Identified** | `3` | Edge-case UI, latency, and session recovery bugs |
| **Test Execution Pass Rate** | `100%` | All blocker criteria met |

### 🐞 Logged Defects (Summary)

| Bug ID | Severity | Module | Summary |
| :---: | :---: | :--- | :--- |
| **`BUG-01`** | **Medium** | QR Scanner | Infinite loader displayed when scanning damaged/unsupported QR formats without timeout error. |
| **`BUG-02`** | **Low** | Transaction History | Currency symbol misalignment occurred when Android system display size is set to *Largest*. |
| **`BUG-03`** | **High** | Session Lock | App fails to prompt for biometric re-authentication after quick app-switch within 5 seconds. |

---

## 🚀 Key Takeaways & QA Skills Demonstrated
* **Test Artifact Design:** Authored standard IEEE-aligned test plans and granular test case sheets with clear preconditions, steps, and expected outputs.
* **Domain Knowledge:** Deep understanding of the **UPI ecosystem**, banking APIs, latency timeouts, and financial transaction states (`Success`, `Pending`, `Failed`).
* **Bug Documentation:** Captured complete bug lifecycles featuring clear step-by-step reproduction paths, device metadata, and severity triage.

---

## 📬 Contact & Connect
* **Tester:** Mohammed Shafiq
* **GitHub:** https://github.com/Shafiq-456/
* **LinkedIn:** [linkedin.com/in/your-profile](https://linkedin.com/)
