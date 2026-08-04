AbhiBus Ticketing Analytics - Complete Deliverables Package
Everything generated for the AbhiBus synthetic bus ticketing analytics project,
built for Madras D School's Power BI / SQL / Python training track.
Folder guide
01_Dataset/
fact_bookings.csv, dim_*.csv (8-table star schema, 274,853 booking rows)
generate_abhibus_dataset.py  (the generator script - re-run to regenerate)
data_dictionary.md           (column-level reference)
validation_report.txt        (automated QA checks run at generation time)
02_PowerBI_Requirements/
AbhiBus_PowerBI_Requirements_v1.1.pdf
25-page spec: data model, relationship matrix, 6 dashboard designs
(KPIs, wireframes, chart cards), KPI catalog, full DAX guide.
03_SQL_Scenarios/
Part 1: 50 intermediate scenario Q&As
Part 2: 50 advanced scenario Q&As (window functions, cohorts, Pareto,
anomaly detection)
All 100 queries were executed and verified against the dataset.
04_Python_Scenarios/
50 scenario Q&As (pandas/NumPy/matplotlib), run in order in one session.
All 50 code blocks were executed and verified against the dataset.
05_MIS_Excel_Reports/
Daily, Weekly, Monthly, Yearly MIS workbooks - formula-driven
(INDEX/MATCH KPI scorecards, RAG conditional formatting, native charts).
All formulas recalculated clean and cross-verified against the source data.
Notes
Currency: INR. Timeframe: Jan 2024 - Aug 2026.
SQL/Python/DAX numbers reconcile with each other and with validation_report.txt
(e.g. Intra-TN share ~65%, festival rush uplift ~2.6x, top-20% customer
revenue share ~64%) - a useful self-check for students.
Generated: 29 July 2026 | Madras D School
