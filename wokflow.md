# RevenSight™ Workflow (Simple)

### Step 1 — Generate Content → `analysis_data`
AI outputs structured JSON:
- risk_score  
- probability_close  
- key_risks[]  
- next_actions[]  
- deal_health_score  
- forecasted_revenue  
- revenue_score  
- icp_score  
- summaries  

### Step 2 — Generate Content → `final_html`
Takes analysis_data and generates a polished HTML UI:
- Risk section  
- Probability  
- Health card  
- ICP card  
- Revenue card  
- Risks and Actions lists  
- AE Coaching tips  

### Step 3 — Show User Output  
Displays final_html in HTML format.
