# Hi there 👋, I'm Aketana Rattanawangcharoen

<p align="left">
  <img src="https://img.shields.io/badge/Role-Senior%20IT%20Analyst%20%2F%20Cloud%20Platform%20Engineer-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Focus-Cloud%20Architecture%20%7C%20Microservices%20%7C%20AI%20RAG-orange?style=flat-square" />
  <img src="https://img.shields.io/badge/TOEIC-945%20(C1)-success?style=flat-square" />
</p>

Infrastructure & IT professional with **7+ years of experience** supporting enterprise and banking-sector environments. Currently working as a **Senior IT Analyst at the Bank of Thailand**. Actively designing and building enterprise-grade cloud-native architectures and AI platforms.

---

## 🚀 Flagship Project: CloudForge Platform

A self-directed, modular **cloud-native microservices platform** focusing on decoupled identity management, secure RAG knowledge pipelines, and automated validation gates.

### Architecture Overview
```text
                    ┌─────────────────────┐
                    │   CloudForge        │
                    │   Platform          │
                    └──────────┬──────────┘
                               │
              ┌────────────────┼────────────────┐
              │                │                │
        Identity/Auth     Foundation Gate    AI Gateway
              │                │                │
      ┌───────┼────────┐       │        ┌──────┴──────┐
      │       │        │       │        │             │
    Ingest Knowledge Security  Nova    RAG          LLM
