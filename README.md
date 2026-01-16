# 🧗‍♂️ Logistics & Transport Cost Model: Rock Climbing Championship

### 📌 Project Objective
This project involves building a logistics model to calculate and optimize transport costs for a women's rock climbing championship. The model tracks 24 athletes across 67 competitions, managing movements between multiple remote locations in a National Park.

![Transport Matrix Input](transport_matrix.png)
*(Snapshot of the raw data: Multi-variable distance matrix)*

---

### ⚙️ The Logic (Technical Breakdown)
The core of this project is a **Dynamic Calculation Engine** built in Excel that handles:

1.  **Movement Tracking:** Used `COUNTIF` (CONTAR.SI) logic to track each athlete's progress through the tournament rounds.
2.  **Matrix Lookups:** Implemented **INDEX & MATCH** (INDICE y COINCIDIR) functions to extract precise transport costs from the distance matrix.
3.  **Scenario Analysis:** Created a "What-If" model to compare total logistics costs between two different starting hubs (Clarkson Town vs. Orange Grove).

![Calculation Engine](calculation_engine.png)
*(View of the calculation logic using nested formulas)*

---

### 🔧 Business Questions Answered
* **Total Operational Cost:** Comprehensive calculation of the entire championship's transport budget.
* **Segmented Analysis:** Cost tracking for specific "Favorite" athletes and high-traffic locations.
* **Strategic Pivot:** Identified the financial impact of changing the logistical starting point, quantifying potential savings.

![Final Cost Analysis](final_cost_analysis.png)
*(Final scenario comparison and budget optimization results)*

---

### 🛠️ Tools Used
* **Advanced Excel:** (Conditional Logic, Matrix Arrays, Indexing).
* **Logistics Modeling:** Asset movement tracking and redundant travel elimination.

> **Note:** The dataset and internal formulas are maintained in Spanish as per the original source, while the documentation is provided in English for global accessibility.
