# RevenSight™ Intelligence Engine  
AI agent that analyzes a sales deal and generates a full deal report including:

- Risk Score  
- Probability of Close  
- Deal Health Score  
- Forecasted Revenue  
- ICP Fit Score  
- AE Coaching Tips  
- Key Risks + Next Actions  
- Full HTML UI with charts and progress bars  

### 🔗 Live Agent  
https://agent.ai/agent/llue6425uw4q4igbdonr  

---

## 📌 How It Works

1. User enters a deal name or HubSpot deal ID.  
2. Agent pulls deal notes and sends them to **GPT-5-mini** for structured analysis.  
3. AI outputs `analysis_data` (JSON: scores, summaries, risks, etc.).  
4. A second Generate Content step formats everything into a clean **HTML UI**.  
5. Output is displayed to user.

---

## 📂 Project Files

- `analysis_prompt.txt` — Prompt used for analysis_data  
- `final_html_prompt.txt` — Prompt used for HTML rendering  
- `workflow.md` — Short description of the 2-step workflow  
- `template.html` — Base HTML design for the UI  

---

## 🚀 Features

- Professional sales-report UI  
- Score bars, colored sections, and structured cards  
- Clean explanations for risk, ICP, revenue, and health  
- AE tips generated dynamically  
- Duplicate Generate Content steps handled cleanly  
- Fully functional end-to-end

---

## 🛠 Tech Stack

- Agent.ai (GPT-5-mini)  
- HTML for the final report  
- Simple JSON → HTML pipeline  

---

## 🧪 Example Output

- Risk Score  
- Probability of Close  
- Deal Health Score  
- Revenue Score & Forecast  
- ICP Alignment  
- Next Actions  
- AE Coaching  

(See full output by running the live agent)

---
