# 🧠 CrewAI Planogram Analysis

A collaborative multi-agent AI solution built using [CrewAI](https://www.crewai.com) to automate **planogram analysis** — helping retailers optimize product placement, maximize sales, and gain competitive insights using GPT-4o and external data tools.

---

![alt text](image.png)

## 📌 What is Planogram Analysis?

Planogram analysis involves examining how products are displayed on retail shelves to:
- Maximize visibility of high-margin and high-demand products
- Improve customer experience through better organization
- Align shelf strategy with evolving market trends

It is widely used in industries like:
- 🛒 Consumer Packaged Goods (CPG)
- 🏪 Supermarkets and Convenience Stores
- 🧴 Pharmacies and Personal Care
- 📱 Electronics Retail

---

## 💡 Project Objective

The goal of this project is to simulate a virtual retail audit using autonomous AI agents. These agents:
- Analyze existing shelf layouts
- Benchmark them against market and competitor insights
- Recommend actionable improvements

---

## ⚙️ Tech Stack

| Component         | Tech / Tool                         |
|------------------|-------------------------------------|
| Language          | Python                              |
| Agent Framework   | [CrewAI](https://www.crewai.com)    |
| LLM               | OpenAI GPT-4o (via Azure endpoint)  |
| External Tools    | SerperDevTool, ScrapeWebsiteTool    |
| Config Mgmt       | YAML (for agents and tasks)         |
| Output Format     | Markdown                            |


---

## 🤖 Agents Overview

The solution uses **CrewAI** to orchestrate two autonomous agents:

### 🔹 Store Manager Agent
- **Role:** In-store product layout reviewer  
- **Capabilities:**
  - Reviews shelf images or layout data
  - Identifies inefficiencies or missing planogram compliance
  - Uses **multimodal GPT-4o** for interpreting visuals

### 🔹 Market Analyst Agent
- **Role:** External data researcher and competitor analyst  
- **Capabilities:**
  - Uses `SerperDevTool` and `ScrapeWebsiteTool`
  - Scrapes external sources for competitor shelf strategies, product trends, and market data
  - Provides benchmarking and supporting evidence for recommendations

---

## 🧠 Tasks Performed

The agents collaborate to execute a sequence of three tasks:

1. **Analyze Shelf Layouts**
   - Understand current product positioning
   - Identify gaps or poor placements

2. **Provide Recommendations**
   - Suggest optimizations based on internal layout and external market research

3. **Create Shelf Optimization Action Plan**
   - Generate a detailed markdown report with recommendations and justifications

---

## 📝 Final Output

The final result is a markdown file:  
### `shelf_report.md`

This report includes:
- 🔍 Summary of detected issues
- ✅ Actionable planogram improvements
- 📊 Market insights & competitor benchmarks
- 📦 Suggested changes in product placements or ordering



