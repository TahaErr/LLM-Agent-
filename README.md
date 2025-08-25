# 🤖 Multi-Agent LLM Mini Scenario

A **multi-agent workflow demo** built on Google Colab (with A100 GPU) simulating a “mini company” where **Manager – Researcher – Writer – Critic** agents collaborate to analyze a topic and produce an **executive summary, recommendations, table, and LinkedIn post draft**.

---

## 📌 Project Summary
A simulation where multiple LLM-powered agents cooperate to:
- Gather sources,
- Summarize findings,
- Produce a short report,

---

## 🚀 Suggested Scenario
**Topic Example:** *“Road anomaly detection trends for traffic safety (2023–2025).”*  

**Target Outputs:**
1. One-page executive summary (bullets)  
2. 3 strategic recommendations  
3. 1 comparison table  

*(The topic can be swapped with competitor analysis, product PRDs, research notes, etc.)*

---

## 🧑‍🤝‍🧑 Agents & Roles

### 1. Manager (Coordinator)
- Defines the task and acceptance criteria  
- Assigns roles and approves final package  

### 2. Researcher (Knowledge Collector)
- Extracts subtopics  
- Provides 5–8 key findings with source notes  

### 3. Writer (Editor)
- Structures the findings into:  
  - Executive summary  
  - Recommendations  
  - Table  

### 4. Critic (Quality Checker) *(optional)*
- Validates sourcing, factual accuracy, and readability  

---

## 🛠 Capabilities
- **Tools:** Web search, shared notebook memory, table generator (Markdown), summarizer  
- **Memory:**  
  - Short-term: round outputs (findings, notes)  
  - Long-term: style guide (tone, length, format)  

---

## 🔄 Orchestration Flow
1. **Manager** sets goal + assigns tasks  
2. **Researcher** collects findings + notes  
3. **Writer** builds final outputs  
4. **Critic** validates with checklist  
5. **Manager** approves and finalizes  

---

## 📊 Evaluation Metrics
- ≥80% sentences backed by sources  
- Repetition rate <10%  
- Avg. sentence length: 12–20 words  
- ≤3 rounds per workflow  
- ≥3 meaningful subtopics covered  

---

## 🖥 Demo Setup
- **Left panel:** Agent conversations  
- **Right panel:** Final package (summary, table, LinkedIn draft)  
- **Buttons:** Run scenario / New topic 

---

## 📦 Deliverables
- Screenshot of agent dialogues  
- Screenshot of summary + table  
- Workflow diagram (Manager → Researcher → Writer → Critic → Manager)  

---
