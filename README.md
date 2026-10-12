# 💠 Dr.FinTech | AI Financial Guardian & Cyber-Terminal

**Problem Statement:** Modern users are restricted by fragmented, passive financial tools, leaving them highly vulnerable to unexpected cashflow crises, opaque lending structures, complex Indian tax liabilities, and sophisticated digital fraud. 

**The Solution:** **Dr.FinTech** is a unified, AI-driven terminal that solves this by seamlessly integrating predictive expense management, secure virtual banking, automated taxation, and institutional-grade trading intelligence into a single, immersive "Cyber-Terminal".

---

## 🔐 Evaluator Credentials & API Keys (CRITICAL)

To fully evaluate all features, Role-Based Access Control (RBAC), and AI integrations, please use the following exact credentials:

**1. Groq API Key (Required for AI Modules)**
* **Key:** `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`
* *Note: This powers the NLP Fraud Auditor and the Llama-3.2 Multimodal Chart Vision Engine.*

**2. Administrator Access (Full System & Institutional Ledger Control)**
* **Operator ID:** `maddy`
* **Secure Passkey:** `admin123`
* **Virtual Bank PIN:** `9999`
* **Features Unlocked:** Institutional Bank P&L Margin visibility, User Management & Revocation, Base Currency Global Overrides.

**3. Standard Trader Access (Standard User View)**
* **Operator ID:** `guest`
* **Secure Passkey:** `guest123`
* **Virtual Bank PIN:** `1234`
* **Features Unlocked:** Standard borrower view, restricted from institutional ledgers.

---

## ✨ The 11 Core Terminal Modules

1. **🛡️ AI Financial Guardian:** Interactive expense editor with a deterministic 15-to-30 day cash runway predictor.
2. **🕯️ Chart Vision AI:** Multimodal AI (Llama-3.2 Vision) that analyzes uploaded candlestick charts to detect support/resistance and generate precise BUY/SELL/HOLD signals.
3. **🏦 Smart Loan Engine:** Calculates risk-adjusted EMIs based on CIBIL and DTI thresholds. Includes an isolated **Institutional Profit Ledger** restricted to Admins.
4. **📊 Live Markets:** Real-time algorithmic OHLC candlestick generator (2024 Series) with order execution logic.
5. **📈 Sim Trading:** Interactive algorithmic scanner and historical portfolio strategy backtester.
6. **💳 Virtual Bank:** Tier-based simulated debit/credit ecosystem (Elite, Premium, Express) with strict PIN authentication and automated cashback routing.
7. **🇮🇳 India Tax Engine:** Statutory routing for Individual (New Regime u/s 115BAC), Corporate (25%), and GST (18%) liabilities.
8. **🎮 Corporate Sprint (Gamified Yields):** An embedded HTML5 reflex survival game. Yields are generated via cryptographic validation codes to bypass iframe security.
9. **🚨 Threat Intel & PDF Auditor:** Localized `pypdf` parser combined with an LLM inference engine to instantly audit uploaded financial contracts for hidden predatory clauses.
10. **🗺️ Interactive Architecture:** Hover-enabled Mermaid.js diagrams revealing underlying mathematical formulas and live session states.
11. **👥 Sys Admin:** Strict role-based gateway for managing operator clearances and global environment variables.

---

## 🚀 Engineering Challenges & Bug Fixes

During development, several complex architectural challenges were resolved to ensure production readiness:

* **Cryptographic CORS Bypass (Game Sync):** Modern browsers block iframe scripts from modifying the parent window's URL or DOM directly (CORS cross-origin policies). To sync the HTML5 canvas game score to the Python backend without triggering a `StreamlitWidgetAlreadyInstantiatedError` or silent failure, a robust **Cryptographic Validation Code System** was implemented. Users copy a securely hashed code generated upon crashing, validating the score mathematically.
* **Template Literal Collision Fixed:** Resolved a critical `NameError` caused by Python `f-strings` colliding with JavaScript template literals (`${score}`). This was fixed by utilizing double-brace escaping (`${{score}}`), allowing the JS script to render securely inside the Streamlit component.
* **Persistent AI Memory & State:** Engineered a robust `st.session_state` hierarchy to ensure uploaded chart images, bank balances, custom stock scanner edits, and historical simulated trades remain persistent across page reruns.

---

## 🛠️ Technical Stack

* **Frontend/UI:** Streamlit with heavily customized CSS (Fluid Aurora Live Background, Glassmorphism, CSS Animations).
* **Data Processing & Visualization:** Pandas, Altair, Python `math`.
* **Artificial Intelligence:** Groq API (`llama-3.1-8b-instant`, `llama-3.2-90b-vision-preview`).
* **Document Parsing:** `pypdf`.
* **Embedded Graphics:** HTML5 Canvas (JavaScript), Mermaid.js.

---

## ⚙️ Installation & Setup

**Step 1: Clone the Repository**
```bash
git clone [https://github.com/Maddy-002/Dr.FinTech.git](https://github.com/Maddy-002/Dr.FinTech.git)
cd Dr.FinTech

**Step 2: Install Dependencies**
```bash
pip install streamlit pandas altair pypdf groq

Step 3: Set Environment Variables (Crucial for AI)
You must set the Groq API key in your terminal before running the app.

On Windows Command Prompt:

DOS
set GROQ_API_KEY=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

Step 4: Launch the Terminal

Bash
streamlit run app.py

(If you encounter a File does not exist: app.py error on Windows, ensure the file is saved as a Python file and not a hidden text document like app.py.txt).

📜 Standards & Compliance Matrix
BIS IS 17428 (Data Privacy): No permanent storage of uploaded financial documents or charts; strictly localized session-state parsing.

ISO 27001 (Security Management): Multi-layered RBAC, isolated bank ledgers, cryptographic game-score validation, and secure PIN-based transaction authorizations.

ISO 31000 (Risk Management): Explainable, deterministic rule-based algorithms for loan eligibility (DTI thresholds).

Developed & Architected by API Architects
