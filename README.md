
💳 Google Pay (Android) — Manual QA Testing Portfolio
Tester: Mohammed Shafiq
Project Type: End-to-End Manual QA Testing & Test Artifact Design
Target Application: Google Pay (Android / NPCI UPI Ecosystem)
📌 Project Overview
A comprehensive manual quality assurance project simulating a real-world testing cycle on Google Pay (Android). This project demonstrates core QA competencies: designing structured test plans, executing rigorous positive/negative test scenarios, identifying edge-case defects, and documenting actionable bug reports.
📁 Repository Structure
├── 📄 GPay_Test_Plan.docx          # Scope, test strategy, risk matrix, entry/exit criteria
├── 📊 GPay_QA_Test_Cases.xlsx      # 35 execution test cases + defect log + metrics dashboard
├── 🖼️ images/
│   └── gpay-qa-testing.png         # Test execution screenshots & visual proofs
└── 📑 README.md                    # Project documentation & summary
🎯 Test Scope & Coverage Matrix
[ Authentication & Onboarding ] ───► Phone OTP, Biometric Lock, Device Binding
[ Core Payment Workflows ]      ───► P2P Transfer (UPI ID, Phone, Contact, QR Scan)
[ Account & Banking ]           ───► Bank Account Linking, Balance Fetch, UPI PIN Reset
[ Merchant & Utility ]          ───► Bill Payments, Mobile Recharge, Auto-Pay mandates
[ Non-Functional Validations ]  ───► Network Throttling (2G/3G/Offline), Session Expiry
Key Modules Tested
Authentication & Security: SIM binding, biometric fallback, multi-factor login, background timeout session locks.
Transaction Engine: Real-time peer-to-peer transfers, UPI QR code scanner integration, daily transaction limits, split bills.
Account Operations: Multi-bank integration, balance verification, secure UPI PIN setup/reset.
Negative & Boundary Scenarios: Zero/negative amounts, special characters in UPI IDs, interrupted network handshakes, expired QR codes.
UI/UX & Resilience: Font scaling, orientation handling, screen reader compatibility, graceful degradation under low bandwidth.
🛠️ Testing Methodologies Applied
Black-Box Functional Testing: Validating system flows against standard financial transaction requirements.
Boundary Value Analysis (BVA) & Equivalence Partitioning (EP): Transfer limits (₹0, ₹0.01, ₹1,00,000, ₹1,00,001), UPI ID character validations.
Security & Session Testing: Preventing clipboard sniffing of sensitive PINs, screenshot blocking on secure screens, session termination on app minimize.
Defect Lifecycle Management: Tracking defects with reproduction steps, severity, priority, and root cause context.
📊 Test Execution Summary
Metric	Value	Notes
Total Test Cases Planned	35	100% test scenario coverage across core modules
Test Cases Executed	35	Executed against actual Android builds
Passed Test Cases	35	Post-retest verification
Defects Identified	3	Edge-case UI, latency, and session recovery bugs
Test Execution Pass Rate	100%	All blocker criteria met
🐞 Logged Defects (Summary)
Bug ID	Severity	Module	Summary
BUG-01	Medium	QR Scanner	Infinite loader displayed when scanning damaged/unsupported QR formats without timeout error.
BUG-02	Low	Transaction History	Currency symbol misalignment occurred when Android system display size is set to Largest.
BUG-03	High	Session Lock	App fails to prompt for biometric re-authentication after quick app-switch within 5 seconds.
🚀 Key Takeaways & QA Skills Demonstrated
Test Artifact Design: Authored standard IEEE-aligned test plans and granular test case sheets with clear preconditions, steps, and expected outputs.
Domain Knowledge: Deep understanding of the UPI ecosystem, banking APIs, latency timeouts, and financial transaction states (Success, Pending, Failed).
Bug Documentation: Captured complete bug lifecycles featuring clear step-by-step reproduction paths, device metadata, and severity triage.
📬 Contact & Connect
Tester: Mohammed Shafiq
GitHub: @your-username
LinkedIn: linkedin.com/in/your-profile
