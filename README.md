
# Task_05_Descriptive_Stats

## 📘 Project Overview

This project is part of Research Task 05: *Descriptive Statistics and Large Language Models*. The goal was to use a small public dataset, interact with a large language model (LLM), and evaluate the LLM’s ability to answer natural language questions accurately based on the dataset.

For this task, I used the official 2025 season statistics for the **Syracuse Women’s Lacrosse** team, extracted from a publicly available PDF report.

---

## 📊 Dataset Information

- **Team:** Syracuse Women’s Lacrosse
- **Season:** 2025
- **Source:** Official athletics PDF (not included in repo)
- **Type:** Team stats (games, scores, goals per period, shots, saves)
- **Total Games:** 19

*Note: The dataset was not uploaded to GitHub as per task requirements.*

---

## 🧠 LLM Used

- **Tool:** ChatGPT (GPT-4, Code Interpreter enabled)
- **Interaction Format:** Natural language Q&A
- **Data Input:** Key stats and structured content were extracted from PDF and presented in prompt-friendly format.

---

## 📝 Prompts & Responses

I asked 10 progressively challenging questions:
- 3 basic factual
- 3 analytical (trend/avg)
- 4 strategic/interpretive

Some LLM responses were intentionally incorrect. I documented the incorrect answers and provided **revised prompts** to correct them, showcasing the process of prompt refinement.

👉 See `llm_prompts.md` for full Q&A with prompt engineering examples.

---

## 📈 Key Findings

- Syracuse scored more total goals than opponents (235 vs 221).
- They were strongest in the 1st quarter and weakest defensively in the 4th.
- Slightly better win percentage in conference games (55.6%).
- Coaching insight: **Improving 4th-quarter defense** could help win 2 more games next season.

---

## 📁 Repo Structure

```
├── llm_prompts.md       # Full Q&A with LLM, including wrong/right answers
├── README.md            # This file
├── stats_analysis.py    # (Optional) Python script for basic stats (not used here)
└── visuals/             # (Optional) Visuals folder for charts (not used here)
```

---

## ✅ Submission Details

- **Submitted to:** jrstrome@syr.edu
- **GitHub Repo Name:** Task_05_Descriptive_Stats
- **Progress Reports:**  
  - July 31 via Qualtrics  
  - August 15 via Qualtrics  
  [Qualtrics Reporting Link](https://syracuseuniversity.qualtrics.com/jfe/form/SV_cDgnzM695AMx8d8)

---
