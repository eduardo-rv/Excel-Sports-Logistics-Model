# Logistics & Transport Cost Model: Rock Climbing Championship

## Overview
This project is an Excel-based logistics model designed to calculate and optimize transport costs for a women's rock climbing championship. It tracks the movement of 24 athletes across 67 competitions, calculating the most efficient transit routes between remote locations in a National Park.

![Transport Matrix Input](transport_matrix.png)
*Snapshot of the multi-variable distance matrix.*

## Repository Structure
*   `Logistics_Model_Final.xlsx`: The main calculation engine and scenario dashboard.
*   `raw_tournament_data.csv`: Base dataset containing athlete progression and locations.

## Technical Implementation
The model relies on nested lookup functions and conditional logic to automate the budgeting process rather than manual routing:
*   **Movement Tracking:** Implemented `COUNTIF` (CONTAR.SI) to dynamically track each athlete's progression through the tournament brackets.
*   **Cost Extraction:** Used `INDEX` and `MATCH` arrays to pull exact transport costs from the primary distance matrix based on origin and destination variables.
*   **Scenario Modeling:** Built a comparative scenario to evaluate the financial impact of shifting the logistical starting hub from Clarkson Town to Orange Grove.

![Calculation Logic](calculation_engine.png)
*Detail of the spreadsheet logic and array functions.*

## Key Insights & Results
*   **Total Operational Cost:** Comprehensive calculation of the entire championship's transport budget.
*   **Segmented Analysis:** Cost tracking isolated for specific high-profile athletes and high-traffic locations.
*   **Strategic Pivot:** Identified and quantified the financial impact and potential savings of changing the initial logistical starting point.

![Final Cost Analysis](final_cost_analysis.png)
*Final budget comparison and optimization output.*

## Tools & Skills Used
*   **Data Analysis:** Advanced Excel (Conditional Logic, Matrix Arrays, Indexing).
*   **Domain Logic:** Logistics modeling, asset movement tracking, and redundant travel elimination.

## Future Scope
*   Migrating the raw data and routing logic to a relational SQL database to handle larger, multi-tournament schedules and automate complex routing queries.

> **Note:** The dataset and internal formulas are maintained in Spanish as per the original source, while this documentation is provided in English for global accessibility.
