# Intelliship Quote Automation System

> **From 2-hour quotes to under 10 minutes.**  
> A modular, YAML-driven system for automating freight quoting workflows at enterprise scale.

---

## 🧠 About This System

This is a production-grade, CLI-based quote automation architecture designed to simulate and streamline how enterprise logistics firms process freight RFQs.

It was built to solve a real-world bottleneck:  
**How do you respond to 50+ inbound quotes a day with consistency, speed, and intelligence—without hiring 20 more people?**

---

## 🧱 Modular Design (8 Repos, One Cohesive System)

| Module | Role |
|--------|------|
| [`quote-automation-abstract`](https://github.com/Intelliship/quote-automation-abstract) | Orchestrates intake, scoring, and decision flow |
| [`bash-batch-intake`](https://github.com/Intelliship/bash-batch-intake) | Handles raw file ingestion and YAML logging |
| [`rfq-normalizer`](https://github.com/Intelliship/rfq-normalizer) | Converts .msg, .pdf, and .xlsx RFQs into structured YAML |
| [`quote-risk-engine`](https://github.com/Intelliship/quote-risk-engine) | Scores RFQs based on urgency, value, and risk |
| [`quote-decision-logic`](https://github.com/Intelliship/quote-decision-logic) | Applies quote/no-quote rules + selects template |
| [`rfq-template-library`](https://github.com/Intelliship/rfq-template-library) | Markdown-based response library |
| [`quote-preview-engine`](https://github.com/Intelliship/quote-preview-engine) | Simulates full quote generation from a single CLI command |
| [`quote-feedback-loop`](https://github.com/Intelliship/quote-feedback-loop) | Captures quote outcomes and classifies RFQ intent (live vs budgetary) |

---

## 🧩 System Engineer & Architect Highlights

- **Interface-first design**  
  Uses YAML and Markdown to separate logic, data, and rendering. Engineers and sales teams can collaborate without touching code.

- **Composable CLI structure**  
  Each module can be run standalone or stitched into pipelines.

- **Structured for evolution**  
  Future-ready for LLM prompt injection, Salesforce sync, and real-time scoring APIs.

- **Built for scale**  
  Supports hundreds of daily quotes, batch ingestion, and self-improving classification logic.

---

## 🚀 Outcomes Simulated

| Before | After |
|--------|-------|
| Manual file parsing | Automated RFQ normalization |
| 2+ hour quote times | Quotes generated in <10 minutes |
| Guesswork on intent | Classifier detects `live` vs `budgetary` |
| Inconsistent messaging | Standardized Markdown templates |
| No quote analytics | Feedback loop tracks win/loss/ghosted |

---

## 📦 How to Explore

You can explore each repo independently or run the full flow using:
```
quote-preview-engine/scripts/quote_preview.py [path to YAML]
```

---

## 🛠️ Built With

- Bash (automation)
- Python (logic/classification)
- YAML + Markdown (config/data/template layers)
- GitHub Actions-ready structure

---

## 💼 Ideal For Roles Like

- Platform/System Engineer
- Infrastructure Architect
- Solutions Engineer
- DevOps or Infra Product Owner

---

## 🔗 Linked Repos

Each repo contains its own README and `SYSTEM_OVERVIEW.md` for internal documentation.

Built and maintained by **Intelliship LLC**  
Designed for real logistics workflows—and ready to scale.

