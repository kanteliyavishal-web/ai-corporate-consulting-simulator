# AI-Powered Corporate Consulting Simulator
A Harvard-style capital budgeting and corporate decision-making simulation integrating finance theory, analytics, and AI-driven insights.

## 📌 Overview
The **AI-Powered Corporate Consulting Simulator** is a Harvard-style capital budgeting and strategic decision-making simulation designed for MBA-level finance and consulting education.  
It places users in the role of a **CFO / Capital Committee member**, responsible for allocating limited capital across competing investment opportunities under real-world constraints.

The simulation emphasizes **learning by doing**, portfolio optimization, and the trade-offs between growth, risk, and shareholder value.

---

## 🎯 Learning Objectives
- Apply core capital budgeting techniques: **NPV, IRR, Payback Period, Profitability Index**
- Understand **capital rationing** and portfolio-level decision-making
- Evaluate **risk-adjusted investments** using differentiated discount rates
- Experience the strategic conflict between **short-term stability and long-term innovation**
- Quantify **opportunity cost** and value destruction from suboptimal choices

---

## 🧠 Simulation Narrative
The simulation is inspired by the **New Heritage Doll Company** case framework.

Users evaluate projects proposed by multiple divisions:
- **Production Division** – efficiency upgrades and replacement investments  
- **Retail Division** – expansion and channel optimization  
- **Licensing / New Ventures** – innovation-driven growth initiatives  

A fixed capital budget creates a **hard constraint**, forcing users to rank and prioritize projects rather than accept all positive-NPV investments.

---

## ⚖️ Core Strategic Conflict
The simulation centers on a mutually exclusive decision between:
- **Match My Doll – Clothing Line Expansion**  
  *(Lower risk, steady cash flows, moderate NPV)*

- **Design Your Own Doll – Customization Platform**  
  *(Higher risk, negative early cash flows, high terminal value)*

This trade-off highlights the limitations of IRR and reinforces **NPV and Profitability Index** as superior decision tools under capital constraints.

---

## 🔬 Financial & Analytical Engine
The simulator implements industry-standard financial logic:

- **Net Present Value (NPV)** using discounted cash flow modeling  
- **Internal Rate of Return (IRR)** via Newton–Raphson numerical methods  
- **Profitability Index (PI)** for capital rationing decisions  
- **Risk-Adjusted Discount Rates (RADR)** based on project risk categories  
- **Sensitivity Analysis** on WACC, growth rates, and terminal values  

An optimization solver compares the user’s selected portfolio against the **mathematically optimal portfolio** to calculate opportunity cost.

---

## 🧩 Simulation Flow
1. **Briefing** – Business context, constraints, and strategic mandate  
2. **Analysis** – Project evaluation, cash-flow inspection, sensitivity testing  
3. **Investment** – Capital allocation with budget enforcement  
4. **Debriefing** – Portfolio scoring, value-at-risk, and qualitative feedback  

---

## 🛠 Technology Stack (Planned / Conceptual)
- **Frontend:** React.js  
- **State Management:** Redux / Context API  
- **Visualization:** D3.js, Recharts  
- **Finance Engine:** Custom JavaScript / TypeScript modules  
- **Optimization Logic:** Knapsack / portfolio optimization algorithms  
- **AI Integration (Conceptual):** Generative AI for narrative feedback and scenario evolution  

---

## 🚀 Educational Impact
This project bridges the gap between **spreadsheet-based finance education** and **interactive, decision-driven learning**.  
It is designed to replicate the cognitive pressure, trade-offs, and ambiguity faced by real-world finance leaders and consultants.

---

## 📍 Status
📌 Conceptual architecture and simulation design  
📌 Financial logic specification complete  
📌 Suitable for future full-stack or AI-powered implementation
