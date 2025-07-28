# AutoGen EDA Pipeline

**Multi-agent system for automated exploratory data analysis and reporting**

---

## Overview
This project leverages **Microsoft AutoGen multi-agent architecture** to automate exploratory data analysis (EDA) for large datasets. It reduces manual analysis time and improves insights generation speed for business users.

---

## Problem
- Data scientists spend 40–60% of project time on repetitive EDA tasks.  
- Business stakeholders often struggle to interpret raw statistical outputs.

---

## Solution
- Built a multi-agent system using **AutoGen** where:
  - One agent generates statistical summaries & charts.
  - Another agent interprets results and narrates insights in plain language.
- Configured an **iterative feedback loop** where agents refine outputs until insights are actionable.

---

## Impact
- Reduced manual EDA time by **~70%**.
- Enabled **faster hypothesis validation** for marketing and finance analytics teams.

---

## Tech Stack
AutoGen | Python | Pandas | Matplotlib | LangChain

---

## Architecture
User → AutoGen Controller → EDA Agent (Summaries &amp; Charts) → Insight Agent (Narration &amp; Refinement) → Output Report
