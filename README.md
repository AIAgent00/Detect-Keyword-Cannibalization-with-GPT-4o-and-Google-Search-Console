<img width="709" height="264" alt="image" src="https://github.com/user-attachments/assets/570002f0-5113-4183-a421-efb25d3f3e04" />


# 🚀 AI-Powered Keyword Cannibalization Detection Workflow

An advanced **n8n automation workflow** designed to detect and resolve **keyword cannibalization** issues using **Google Search Console** data and **GPT-4o**. Ideal for SEO professionals managing multiple clients, this system offers **real-time monitoring**, **AI-driven analysis**, and **actionable insights** — all automated. 🔍🤖📊

---

## 🧩 Overview

This intelligent automation solution enables:
- **Real-time keyword tracking**
- **Cross-site cannibalization detection**
- **AI-powered risk analysis**
- **Client-specific reporting**

---

## ⚙️ Core Components

### 1️⃣ Automated Monitoring System

- ⏱ **Real-time Trigger**: Monitors keyword updates in **Google Sheets** every minute
- 🧑‍💼 **Multi-Client Support**: Handles up to **4 different client websites** simultaneously
- 🧠 **Intelligent Routing**: Automatically directs data into **client-specific processing paths**

---

### 2️⃣ Data Collection & Processing

- 🔌 **GSC Integration**: Pulls **last 30 days** of data via **Google Search Console API**
- 📊 **Comprehensive Metrics**: Collects:
  - Keyword
  - URL
  - Average Position
  - Clicks
  - Impressions
  - CTR
- 🔄 **Data Transformation**: Groups raw responses by **keyword** for structured analysis
- 🧬 **Cross-Referencing**: Matches target keywords from **Google Sheets** with actual **GSC performance data**

---

### 3️⃣ AI Analysis Engine

- 🤖 **Powered by GPT-4o**: Analyzes cannibalization patterns using contextual AI reasoning
- 🏷 **Risk Categorization**:
  - 🔴 **High Risk**: 5+ pages competing for the same keyword
  - 🟠 **Moderate Risk**: 3+ pages in the top 10 positions
  - 🟡 **Low Risk**: 2 pages with one clearly dominating
  - 🟢 **No Risk**: Single page ranking for the keyword
- 🧠 **Intelligent Reasoning**: Includes **detailed AI-generated explanations** for each keyword’s risk status

---

### 4️⃣ 📑 Comprehensive Reporting

- 📤 **Automated Output**: Writes all results and insights back to **Google Sheets**
- 🔍 **Detailed Insights**:
  - Risk level
  - AI-generated reasoning
  - Observations
  - Suggested fixes or SEO actions
- 📈 **Performance Tracking**: Logs complete metrics for client reporting
- 🚨 **Status Tracking**: Highlights keywords **ranking** vs. those **missing** from the results

---

## ✅ Benefits

- 🔄 Fully automated — set it and forget it
- 🤓 Expert-level analysis powered by AI
- 💼 Scalable for multiple clients
- ⏰ Saves hours of manual keyword audits
- 🎯 Improves SEO performance by fixing internal competition

---

## 📎 Requirements

- n8n self-hosted or cloud instance
- Google Search Console access per domain
- Google Sheets integration
- OpenAI API Key (GPT-4o access)
- Basic understanding of SEO & automation flows

---

## 📌 Coming Soon

- 📧 Email summaries for clients
- 📅 Weekly digest reports
- 📂 Notion & Slack integration
- 🌍 Multilingual support

---

## 👨‍💻 Contributing

Have ideas or improvements? Pull requests are welcome! 🛠

---

## 📄 License

MIT License

---

Made with ❤️ and 🤖 by SEO automation enthusiasts.
