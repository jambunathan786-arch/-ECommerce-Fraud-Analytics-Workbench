# -ECommerce-Fraud-Analytics-Workbench
A live operational command console designed for financial crime triage and review queue optimization
# 📊 Live Fraud Analytics Workbench & Operational Command Console

## 📌 Project Overview
As an Investigation Specialist, I engineered this dynamic Fraud Analytics Workbench to move past standard backward-looking reporting and simulate live corporate incident response. Using a transactional layout tracking **1,500 enterprise records worth \$1.34M in gross revenue**, this console functions as an interactive triage center to optimize investigator workflows and protect company margins.

---

## 🛠️ Data Model & Architecture
The analytical backend is built across a clean, decoupled relational schema designed to maximize system performance and prevent data truncation:
1. **Executive Dashboard:** A high-level control interface equipped with interactive slicers (`Clean_Status`, `Payment_Method`) allowing for instantaneous systemic health checks.
2. **Orders Ledger:** The primary transaction ledger mapping live behavior attributes (timestamps, countries, amounts, and channels).
3. **Product Catalog:** A dimension reference reference-table holding global inventory data (`SKU`, `Category`, `Unit Price`, and `Merchant Reputation Scores`).

---

## 🚨 Critical Risk Discoveries & Threat Hunting

### 1. Active Review Queue Optimization (Pending Review Monitoring)
Instead of prioritizing historical, closed disputes, this workbench isolates the active pipeline bottleneck: **183 critical holds caught at the checkpoint**. By focusing strictly on active risk vectors, the console helps prevent an operational **🔴 REVIEW SLA OVERRUN** breach.

### 2. Device Abuse Fingerprints
My stacked device visualization exposed that standard, legitimate customer checkouts map directly to clean `delivered` statuses. Conversely, **100% of malicious automated traffic completely bypassed traditional interfaces**, routing exclusively through spoofed `Bot_Server` and `Mobile_Emulator` server scripts. 

### 3. High-Value Luxury Camouflage (The "Low & Slow" Threat)
Cybercriminals utilize micro-structuring tactics by purchasing high-cost luxury goods (e.g., premium items capped at a strict quantity lock of 1 to bypass volume filters). To mitigate permanent capital loss, I constructed a high-exposure tracking matrix to isolate elite financial leakage indicators (such as transaction `ORD100414` at **\$11,683.40** via an automated server flag).

---

## 📈 Technical Skills Highlighted
* **Advanced Multi-Tab Lookups:** Cross-sheet data enrichment linking transactional events with master reference catalogs without system lag.
* **Algorithmic Logic Filtering:** Designing dynamic logical conditions (`IFS`, `AND`, `OR`) to score risk based on simultaneous multi-factor anomalies.
* **Executive Interface Optimization:** Formatting complex system summaries into clean, scannable KPIs for senior risk leadership reviews.
