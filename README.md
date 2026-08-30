Jacques Marie Mage — Economic Nexus & State Tax Obligation Dashboard
Power BI · 2024 – 2026 H1

This dashboard provides a comprehensive view of economic nexus exposure and state tax obligations for luxury eyewear brand Jacques Marie Mage, built using a blend of genuine Avalara sales tax exports from January through June 2026 and synthetically generated data covering 2024 and 2025. Synthetic data was introduced to enable full measurement-period calculations — Prior Calendar Year and rolling window evaluations require historical depth that a mid-year export alone cannot provide. All scoring and obligation logic is applied consistently across both real and synthetic figures.

This dashboard is intended for internal planning and portfolio purposes and should not be used as a substitute for a formal nexus study.

Dashboard Pages

Executive Snapshot — National side-by-side maps of nexus exposure and tax obligation status, with state and store slicers and count bins showing Clear / Approaching / Warning / Exceeded / Suggested Remittance / Tax Owed breakdowns at any point in time
Nexus Score Analysis — State-by-state nexus scoring ranked by threshold proximity and revenue, with a nexus distribution donut and bar chart. Scores are calculated as the ratio of actual activity to state thresholds, with filing logic adjusted for revenue-only, OR, and AND states
Nexus Timeline — Gantt-style color-coded matrix showing month-by-month obligation history per state-store combination from 2024 through H1 2026, distinguishing Threshold Exceeded (red), Suggested Remittance (purple), and Tax Owed (magenta)
Monthly Nexus Monitor — Heatmap tracking month-by-month nexus band per state for the selected store, with 6-month threshold status on row click
Threshold Detail — Revenue Only — Drill-down for states that trigger nexus on revenue alone (AL, CA, FL, IL, MA, MN, MS, OH, PA, TN, TX), grouped by measurement period: Prior Calendar Year, Current or Prior Calendar Year, and Rolling 12 Months
Threshold Detail — AND/OR States — Drill-down for states with dual revenue and transaction count thresholds, separating OR states (nexus if either condition is met) from AND states CT, NY, and VT (both conditions must be crossed simultaneously), each evaluated against their distinct measurement windows
Priority Score & Risk Index — Equal-weighted priority ranking combining nexus exposure (50%) and relative revenue volume (50%), with Score Velocity indicators (↑ ↓ →) showing recent momentum shifts, and a Top 10 states priority score trend line over time
Year on Year Comparison — H1 revenue by state across 2024, 2025, and 2026, with YOY percentage change. Total H1 revenue grew from $8.10M (2024) to $8.65M (2025) to $11.16M (2026), a 29% increase year over year

Jurisdictions Excluded

Alaska, Delaware, Montana, New Hampshire, and Oregon have no state sales tax — economic nexus does not apply. Guam has no codified economic nexus threshold for remote sellers. Rows disappear throughout the dashboard when the destination state matches the store's origin state, as physical nexus is present and economic nexus does not apply.

Stores Covered: Austin · Costa Mesa · Hill Street · SoHo · Sycamore · Venice

The .pbix source file is included in this repository. Interactive access via the Power BI app is available upon request.

!(Nexus&Tax_Obligation_Snapshot.png)
