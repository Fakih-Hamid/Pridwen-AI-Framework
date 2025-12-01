# Pridwen: A Privacy-Preserving Offline AI Framework for Gamified Cybersecurity Education

<p align="center">
  <a href="https://iplab.naist.jp/" target="_blank">
    <img src="https://img.shields.io/badge/Lab-NAIST%20Cyber--Resilience-forestgreen?style=for-the-badge&logo=shield" alt="Cyber Resilience Lab" />
  </a>
  <a href="https://www.naist.jp/en/" target="_blank">
    <img src="https://img.shields.io/badge/Univ-NAIST%20(Japan)-003366?style=for-the-badge&logo=japan" alt="NAIST" />
  </a>
  <a href="#">
    <img src="https://img.shields.io/badge/Status-Research%20Prototype-orange?style=for-the-badge" alt="Status" />
  </a>
</p>

> **⚠️ Note on Source Code Availability:**
> This repository serves as a **technical overview** of my ongoing research.
> Due to academic confidentiality and pending publication, the core source code is currently **private**.

---

## 📖 Project Abstract
**Pridwen** is an offline-first, gamified cybersecurity education framework designed to address the "Human Factor" in digital security. It is specifically engineered to empower **beginners and non-technical users across diverse demographics**, ensuring accessible protection regardless of IT background.

While traditional tools are often static and cloud-dependent, Pridwen leverages **local Generative AI ** to create adaptive, culturally contextualized training scenarios without any data leaving the user's device. This ensures robust privacy while bridging the gap between theoretical knowledge and real-world behavioral resilience.

## 🎮 Key System Components
Based on the proposed research architecture, the system integrates the following modules:

| Component | Function | Technology |
| :--- | :--- | :--- |
| **Scenario Generator** | Creates culturally aware scenarios and phishing simulations. | **GenAI (Mistral-7B)** |
| **Interactive Quizzes** | Adaptive knowledge checks and mini-games. | **Gamification Engine** |
| **Guidance Avatar** | Provides motivation and explanation via an AI persona. | **NLP / Ollama** |
| **Post-Incident Module** | Offers best practices and safe browsing guidance. | **Knowledge Base** |

## 🛠️ Tech Stack & Architecture

The system is built as a modular microservices architecture designed for **offline deployment**:

* **AI Core:** Ollama (serving Mistral-7B model)
* **Backend:** Python (Flask) with Jinja2 Templating
* **Database:** SQLite (Local storage for interaction logs)
* **ML Framework:** PyTorch (for behavioral analytics)

### System Workflow
<p align="center">
  <img src="Pridwen Technology stack simplified.png" alt="Pridwen System Architecture" width="100%">
</p>
