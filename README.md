# 🧗‍♂️ Logistics & Transport Cost Model: Rock Climbing Championship

## 📌 Project Objective
This project involves building a logistics model to calculate and optimize transport costs for a women's rock climbing championship. The model tracks 24 athletes across 67 competitions, managing movements between multiple remote locations in a National Park.

## ⚙️ The Logic (Technical Breakdown)
The core of this project is a **Dynamic Calculation Engine** built in Excel that handles:
- **Movement Tracking:** Used `CONTAR.SI` (COUNTIF) logic to track each athlete's progress through the tournament rounds.
- **Matrix Lookups:** Implemented `INDICE` and `COINCIDIR` (INDEX & MATCH) functions to extract precise transport costs from a multi-variable distance matrix.
- **Scenario Analysis:** Created a "What-If" model to compare total logistics costs between two different starting hubs (Clarkson Town vs. Orange Grove).

## 🔧 Business Questions Answered
1. **Total Operational Cost:** Comprehensive calculation of the entire championship's transport budget.
2. **Segmented Analysis:** Cost tracking for specific "Favorite" athletes and high-traffic locations.
3. **Strategic Pivot:** Identified the financial impact of changing the logistical starting point, quantifying potential savings.

## 🛠️ Tools Used
- **Advanced Excel:** (Conditional Logic, Matrix Arrays, Indexing).
- **Logistics Modeling:** Asset movement tracking and redundant travel elimination.

*Note: The dataset and internal formulas are maintained in Spanish as per the original source, while the documentation is provided in English for global accessibility.*
