# Cross-Platform Post Orchestrator

## 📌 Overview
**Cross-Platform Post Orchestrator** is an automation system built using **Make.com** to publish and synchronize posts across multiple social media platforms such as **LinkedIn, Facebook, and Telegram** from a single source.

The project focuses on **workflow orchestration**, **automation reliability**, and **scalable content distribution**.

---

## 🎯 Objectives
- Centralize social media posting
- Eliminate repetitive manual publishing
- Ensure consistent content across platforms
- Enable scalable and extensible automation workflows

---

## 🧩 Architecture
The system follows an **orchestration-based automation architecture**:

1. **Content Source Layer**
   - Google Sheets as the centralized content input

2. **Orchestration Layer**
   - Make.com scenarios manage workflow execution, branching, and retries

3. **Distribution Layer**
   - Telegram Bot
   - (Extensible to LinkedIn, Facebook, Email, etc.)

This modular design allows easy addition of new platforms without changing the core workflow.

---

## 📂 Repository Structure
cross-platform-post-orchestrator/ ├── integration Google Sheets.blueprint.json ├── integration Telegram Bot.blueprint.json └── README.md
### File Descriptions
- **integration Google Sheets.blueprint.json**  
  Blueprint for fetching structured post content from Google Sheets

- **integration Telegram Bot.blueprint.json**  
  Blueprint for sending posts via Telegram Bot

---

## 🚀 How to Use
1. Import the `.blueprint.json` files into **Make.com**
2. Configure your own Google Sheets and Telegram Bot connections
3. Customize message formatting if required
4. Activate the scenarios

> 🔒 **Security Note:**  
> No API keys, tokens, or credentials are included in this repository.

---

## 🛠 Technologies Used
- Make.com (Integromat)
- Google Sheets
- Telegram Bot API
- Automation Orchestration
- Workflow Pipelines

---

## 👨‍💻 Author
**Vasu Gadi**  
Automation Engineer (Independent)

- GitHub: https://github.com/VasuOnFire  
- LinkedIn: https://www.linkedin.com/in/vasu-gadi  
- X (Twitter): https://x.com/Vasugadi36  

---

## 📄 License
This project is shared for **learning, demonstration, and portfolio purposes**.
