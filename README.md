# Maximizing Profits and Expanding into New Sources of Revenue for a Software Company

**BDM Capstone Project — IITM Online BS Degree Program**
**Indian Institute of Technology, Madras**

| Field | Details |
|---|---|
| Student | Pranav Pandey |
| Roll Number | 23f2000416 |
| Email | 23f2000416@ds.study.iitm.ac.in |
| Company | BLISS Infosoft Pvt. Ltd., New Delhi |

---

## About the Company

BLISS Infosoft Pvt. Ltd. is a New Delhi-based software company incorporated in 2012 that develops applications for life insurance (LIC) agents and financial professionals. Their product suite includes tools like LIC Agent Advisor, LIC DO Advisor, Financial Calculators, and SMS Messenger for LIC professionals.

The company operates through two revenue streams:
- **B2B:** Software sold to dealers/resellers, who then sell to LIC agents
- **D2C:** Insurance agents buy directly from the company

Their network spans 40+ channel partners and 75+ dealers and resellers across urban and rural India.

---

## Problem Statements

1. **Dealer mismanagement** — Dealers engage in "cross-selling" (selling outside their assigned territory) or go dormant without paying transfer fees, causing financial losses for the company.
2. **Declining dealer base** — The number of active B2B partners is falling month on month.
3. **Overdependence on urban markets** — ~96% of revenue comes from urban areas, leaving rural India almost entirely untapped.
4. **No dedicated support team** — Post-deployment issues reach the development team only through dealers, increasing bug-fix turnaround time.
5. **Suboptimal marketing spend** — Budget is heavily concentrated in high-variance channels (billboards and seminars) with limited investment in cost-effective digital and print channels.

---

## Data

All data was sourced from the company's internal Management Information System (MIS) covering **March, April, and May 2025**.

| Dataset | Key Columns | Coverage |
|---|---|---|
| Sales / Dealer Data | Customer Name, Group, Division, Branch, Location, Revenue | 134 / 123 / 113 dealers per month |
| Marketing Data | Marketing technique, Monthly cost | 6 channels across 3 months |
| Employee Structure | Name, Department | 17 employees across 10 departments |

**Primary analysis tool:** Microsoft Excel (descriptive statistics, charts, pivot tables)

---

## Key Findings

### Sales Performance
| Month | Total Revenue (INR) | Active Dealers | MoM Growth |
|---|---|---|---|
| March 2025 | 1,80,44,028 | 133 | — |
| April 2025 | 1,70,25,605 | 122 | −5.64% |
| May 2025 | 1,56,24,405 | 112 | −8.23% |

- **Average monthly revenue decline: −6.97%**, and the rate of decline is accelerating.
- Mean revenue per dealer held steady (~₹1.39L), meaning the revenue drop is driven by fewer dealers, not weaker individual performance.
- Distribution is platykurtic with a low modal value (~₹25K), indicating a large cluster of low performers and a few high-value outliers.

### Urban vs. Rural Revenue Split (consistent across all 3 months)
| Location | % of Revenue |
|---|---|
| Urban | ~96.6% |
| Rural | ~3.3% |

### Marketing Spend Analysis
- **Billboards + Seminars** account for over 73% of total marketing spend but show the highest variance.
- **Newspaper ads** are the most stable channel; **Digital advertising** trended upward across the three months.
- Pamphlets and digital ads are low-cost, low-variance channels with strong potential for rural reach.

### Organizational Structure
| Department | Headcount |
|---|---|
| Regional Managers | 5 |
| Developers | 3 |
| Tele Callers | 2 |
| Testing | 1 |
| CTO / Admin / HR / Graphic Designer / Business Head / MD | 1 each |

No dedicated support department exists. The ratio of management to technical staff is disproportionately high for a product-focused tech firm.

---

## Solutions and Recommendations

### 1. Credit Limit System (Dealer Accountability)
Implement a structured credit limit policy per dealer:
- Evaluate dealers based on performance and assign credit limits accordingly.
- Collect a security deposit exceeding the credit limit before onboarding.
- Integrate the system into the MIS for real-time monitoring.
- Auto-block orders when the credit limit is breached; apply penalties for late payments.
- Review and revise limits periodically based on updated performance data.

### 2. Dealer Loyalty Program (Retention)
Introduce a tiered rewards program to reduce dealer churn:

| Tier | Eligibility | Benefits |
|---|---|---|
| **Silver** | Monthly sales > ₹50,000 | 1% bonus, basic marketing support, early product access |
| **Gold** | Monthly sales > ₹1,00,000 + no defaults | 2.5% bonus, dedicated regional support, co-branded materials |
| **Platinum** | Monthly sales > ₹2,50,000 for 3+ months | 5% bonus, territory protection, featured on company website |

### 3. Marketing Spend Optimization
- Survey all new clients on how they discovered the company to measure channel effectiveness.
- Reallocate budget toward **newspapers** (effective in rural areas) and **digital advertising** (cost-effective for urban reach).
- Reduce reliance on high-variance, high-cost channels like billboards and seminars until ROI data justifies them.

### 4. Cross-Training for Support Coverage
- Cross-train **tele callers** to handle a dedicated support helpline for post-deployment issues.
- Cross-train **developers** to handle bug fixes on a rotating basis during non-development periods.
- Log all support calls with fields for: Problem, Root Cause, and Solution — building an internal knowledge base to improve future products.

---

## Project Timeline

| Phase | Deliverable | Period |
|---|---|---|
| Proposal | Problem definition, approach, and timeline | May 2025 |
| Mid-Term | Data collection, cleaning, metadata, and preliminary findings | June–July 2025 |
| Final Report | Full analysis, visualizations, and recommendations | July–August 2025 |
| Viva | Oral examination | August 2025 |

---

## Repository Structure

```
.
├── proposal.pdf       # Problem statements, methodology, and Gantt chart
├── mid_term.pdf       # Metadata, descriptive statistics, and early visualizations
├── final_submission.pdf  # Complete analysis, graphs, and recommendations
└── README.md          # This file
```

---

*All recommendations are made within the context of an academic capstone project for the IIT Madras BS Degree Program. The institution does not endorse any claims or comments contained herein.*
