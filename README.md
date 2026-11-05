# 🤖 AI Agent & Human Customer Support Analytics (2025–2026)

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![ZoomCharts](https://img.shields.io/badge/ZoomCharts-Drill%20Down%20PRO-007F82?style=for-the-badge)
![Customer Support Analytics](https://img.shields.io/badge/Analytics-AI%20%26%20CX%20Operations-0F172A?style=for-the-badge)

## 📌 The Business Story: Does AI Actually Improve Customer Support?

As organizations rapidly automate customer service, support leaders face a critical question: **Where does AI deliver real value, and where does automation backfire?**

This interactive 3-page Power BI report analyzes **12,000 customer-support tickets** (**€162.72K total spend**) handled between **January 2025 and September 2026** across **Live Chat, Email, and Messaging**. By comparing **AI-Only**, **AI → Human (Escalated)**, and **Human-Only** journeys, the dashboard uncovers the operational sweet spots of AI automation, exposes the hidden cost of delayed handoffs, and provides a quantified routing action plan.

### ⚡ Executive Snapshot
| Metric | Portfolio Performance | Key Takeaway |
| :--- | :---: | :--- |
| **Total Support Volume** | **12,000 Tickets** | Assist AI touches **68.2%** of all incoming volume (**39.4% AI-Only**, **28.8% AI → Human**) |
| **True First Contact Resolution (FCR)** | **80.7%** | Solved on initial contact with **zero repeat follow-ups** within 7 days |
| **True SLA Compliance** | **82.9%** | **95.6%** in `AI-Only` vs. **66.7%** in `Human-Only` (dragged down by Email queues) |
| **Customer Satisfaction (CSAT)** | **4.05 ★** | Highest in `AI-Only` (**4.40 ★**), lowest in `AI → Human` escalations (**3.52 ★**) |
| **Total Support Spend** | **€162,721.50** *(€13.56/ticket)* | `AI-Only` costs **€1.46/ticket**, while `AI → Human` escalations cost **€27.09/ticket** |

---

## 🖥️ Inside the 3-Page Interactive Report

### Page 1: Executive Overview — *The AI vs. Human Value Paradox*
<img width="671" height="379" alt="Overview" src="https://github.com/user-attachments/assets/a6d41416-41d7-4996-9804-abd4c2342231" />

Page 1 establishes the high-level performance baseline across support paths, channels, customer tiers, and product families:
* **Ticket Volume by Support Path & Channel:** Shows how the 12,000 tickets split across **AI-Only (4,724 tickets | 39.4%)**, **Human-Only (3,820 tickets | 31.8%)**, and **AI → Human (3,456 tickets | 28.8%)**, with interactive drill-downs into Channel and Priority.
* **The Cost & Quality Paradox:** Demonstrates that when `Assist AI` resolves an issue autonomously, it achieves an exceptional **86.7% True FCR** and **95.6% SLA compliance** at just **€1.46 per ticket**. However, when an AI conversation fails and escalates to a human (**AI → Human**), unit cost skyrockets **18.6x to €27.09** and True FCR drops to **70.1%**.
* **Multi-Year Adoption Trend (2025–2026):** Tracks how autonomous AI resolution expanded from **36.8% in 2025** to **42.6% in 2026** while keeping overall cost per ticket stable (**€13.56 → €13.57**).
* **Channel Performance Scorecard:** Contrasts fast synchronous channels (**Live Chat** at **92.2% SLA** and **Messaging** at **91.9% SLA**) against **Email**, where a **221.6-minute average first response time** pulls SLA compliance down to **61.4%**.

---

### Page 2: Escalation & Handoff Diagnostics — *Why AI Fails & The Cost of Waiting*
<img width="667" height="377" alt="Escalation   Handoff Diagnostics" src="https://github.com/user-attachments/assets/e98bd66e-f6c9-4035-baf0-35f2626d1dbb" />

While **AI → Human** escalations represent only **28.8% of ticket volume**, they consume **57.5% of the entire support budget (€93.63K)** and generate **€28.70K in 7-day repeat-contact waste**. Page 2 diagnoses the root causes:
* **Why AI Transfers to Humans:** **Low answer confidence (844 tickets | €20.22/ticket)** and **Customer requested human (808 tickets | €19.70/ticket)** drive nearly half (**47.8%**) of all handoffs. Meanwhile, **Missing technical knowledge (436 tickets)** is the most expensive escalation driver at **€55.98 per ticket**, followed by **Policy restriction (571 tickets)** at **€35.27 per ticket**.
* **The 12-Minute Handoff Cliff:** Timing is everything in an AI handoff.
  * **Up to 5 min handoff (753 tickets):** **€20.46/ticket** | **3.72 ★ CSAT** | **22.4% repeat rate**
  * **5–12 min handoff (1,902 tickets):** **€23.42/ticket** | **3.69 ★ CSAT** | **24.8% repeat rate**
  * **Over 12 min handoff (801 tickets):** **€42.06/ticket** | **2.92 ★ CSAT** | **32.1% repeat rate**
  > *Insight:* Letting the AI struggle with a customer for over 12 minutes before transferring to a human **doubles the ticket cost** and destroys customer satisfaction.
* **AI Containment vs. Escalation by Issue Hierarchy:** `Assist AI` autonomously contains **73.4% of Account Access** and **65.3% of Orders & Delivery** requests, but escalates **56.4% of Billing & Refunds** and **55.1% of Technical Support** tickets.
* **Subcategory Pain-Point Scorecard:** Pinpoints specific failure hotspots such as **Integration error** (436 escalations, €55.98/escalated ticket) and **Billing dispute** (37.7% repeat rate on escalations, 2.81 ★ CSAT).

---

### Page 3: Routing Optimization & Action Plan — *Where to Automate vs. Route to Humans*

Page 3 translates diagnostic findings into an operational routing matrix and a quantified action plan for leadership:
* **Support Spend Breakdown (AI vs. Human vs. Repeat Cost):** Reveals that **Technical Support (€69.0K total | €23.96/ticket)** and **Billing & Refunds (€34.2K total | €19.58/ticket)** consume **63.4% of the total budget** and **64.6% of all repeat-contact costs**.
* **Queue & First-Response Bottleneck Analysis:** Exposes the severe **Email queue bottleneck** (**498.9 minutes** average queue across all Email tickets, spiking to **672.9 minutes** on `Email Human-Only`), alongside strict **Business Tier** SLA pressure (**55.2% SLA compliance**).
* **Interactive Routing Decision Matrix:** Side-by-side comparison of **AI-Only**, **AI → Human**, and **Human-Only** across every issue category and subcategory:
  * **Keep in AI-Only:** *Password reset* (€0.78/ticket), *Order tracking* (€0.89/ticket), and *Setup guidance* (€1.76/ticket), where AI achieves **86%–89% True FCR** and **4.39+ ★ CSAT** at a fraction of human cost.
  * **Route Directly to Specialists:** High-complexity *Billing disputes* and *Integration errors*, where failed AI handoffs cost **€32–€56/ticket** compared to **€21–€28/ticket** when routed directly to human specialists.

---

## 🎯 Strategic Recommendations & Quantified Business Impact

1. **Enforce a Hard 5-Minute AI Handoff Threshold (Save ~€17.3K & Lift CSAT +0.80 ★):**
   * Trigger automatic human transfer whenever `Assist AI` confidence remains low or unresolved at the 5-minute mark, eliminating the **801 delayed handoffs (>12 min)** that currently cost **€42.06/ticket**.
2. **Bypass AI for High-Complexity Billing Disputes & Integration Errors:**
   * Route complex *Billing disputes* and *Integration errors* directly to `Billing care` and `Technical care` specialists, avoiding the **€38.29/ticket** double-handling penalty on `Technical support` escalations.
3. **Unlock Self-Service API Actions for Assist AI (Deflect 675 Escalations):**
   * Grant `Assist AI` secure API permissions to execute standard order/subscription updates and automated identity verification, eliminating the **675 "Action unavailable"** and **122 "Identity verification"** escalations.
4. **Eliminate the Email Human-Only Queue Bottleneck (Lift Email SLA from 61.4% → 85%+):**
   * Use `Assist AI` to auto-triage and draft responses for incoming emails, cutting the **672.9-minute Email Human-Only queue wait** and rescuing SLA compliance for **Business Tier** customers.

---

## 📂 Repository Structure

```text
├── assets/
│   ├── page1_executive_overview.png          # Page 1: Executive Overview screenshot
│   ├── page2_escalation_diagnostics.png      # Page 2: Escalation & Handoff Diagnostics screenshot
│   └── page3_routing_action_plan.png         # Page 3: Routing Optimization & Action Plan screenshot
├── data/
│   └── AI_Agents_Customer_Support_Challenge_clean.xlsx   # 12,000-ticket dataset
├── AI_Customer_Support_Analytics.pbix        # Power BI report file
└── README.md                                 # Project documentation
