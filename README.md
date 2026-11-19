# Hi, I'm Mohamed Baati 👋

**Computer Science student (Licence Informatique, IIT Sfax, Tunisia)** focused on **AI / Machine Learning** and full-stack development.
I'm looking for a **6-month final-year internship (PFE) in AI/ML starting January 2027**.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-baatimed-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/baatimed-497351404)
![ISTQB](https://img.shields.io/badge/ISTQB-Certified%20Tester-2E7D32)

---

## 🧠 AI / Machine Learning projects

### [🛡️ AegisMCP: intelligent MCP gateway for LLM agents](https://github.com/baatimed5-jpg/aegis-mcp)
A gateway between LLM agents and MCP tool servers. Every tool call passes through a security and optimization pipeline:
- **Security:** PII masking (Presidio), prompt-injection detection (fine-tuned **DeBERTa** + rules + an LLM judge), and human approval for risky tools.
- **Context optimization:** learned field pruning and compact serialization, with token and cost savings measured.
- **Observability:** PostgreSQL audit log and a live **Angular** dashboard.

`Python` `MCP` `PyTorch` `DeBERTa` `FastAPI` `PostgreSQL` `Redis` `Docker` `Angular`

### [⚡ Small Model Beats Big: LoRA fine-tuning vs OpenAI 120B](https://github.com/baatimed5-jpg/small-model-beats-big)
I fine-tuned **Qwen2.5-0.5B** with **LoRA** on a 4 GB laptop GPU in 33 minutes to detect toxic gaming chat. On the same 860 human-labelled test messages:

| Model | Macro F1 | Speed | Cost / 1M messages |
|---|---|---|---|
| **Qwen 0.5B + LoRA (mine)** | **0.802** | **42 ms** | **~$0.10** |
| OpenAI GPT-OSS-120B (240× bigger) | 0.784 | 473 ms | $47.70 |

Deployed as a live moderation chat room (FastAPI + React).
`PyTorch` `Transformers` `PEFT/LoRA` `Hugging Face` `FastAPI` `React`

### [📨 Spam Classifier](https://github.com/baatimed5-jpg/spam-classifier)
Compares Naive Bayes, Logistic Regression and Linear SVM on TF-IDF features. **99.0% accuracy** (F1 0.963) on unseen SMS. Includes a React demo that explains *which words* made a message look like spam.
`scikit-learn` `TF-IDF` `FastAPI` `React`

---

## 💻 Software engineering projects

### [🏥 ClinicApp: clinic management system](https://github.com/baatimed5-jpg/clinic-app)
Patients, doctors, appointments and medical records, with UML use-case and class diagrams.
`ASP.NET Core MVC (.NET 10)` `Entity Framework Core` `SQL Server`

### [📚 Library Management System](https://github.com/baatimed5-jpg/library-management-system)
Desktop app with admin and member roles: catalogue, borrowing and return requests, reservations, and BCrypt passwords.
`Java 17` `JavaFX` `Spring Boot JDBC` `MySQL` `Maven`

### Professional & private work (code not public)
- **Kompass**: tracking and process-automation web app built during my internship at **Steros** (Sfax, 2026). `ASP.NET Core` `Next.js` `PostgreSQL`
- **Pulse**: health-tracking platform (wearable-style metrics) with an API and a mobile app. `.NET 10` `PostgreSQL` `React Native (Expo)`

---

## 🛠️ Tech stack
**AI/ML:** Python · PyTorch · Hugging Face Transformers · PEFT/LoRA · scikit-learn · LLM APIs · MCP
**Backend:** C# / .NET · ASP.NET Core · FastAPI · Flask · Java / Spring · PHP
**Frontend & mobile:** React · Angular · Next.js · React Native · Flutter
**Data & tools:** PostgreSQL · MySQL · SQL Server · Redis · Docker · Git

**Languages:** English (fluent) · French (intermediate) · Arabic (native)
