# FirstByte Datathon 2026

**Team Cranky Coders | NorthByte Airlines Profitability Analysis**

## Overview
We used Python, pandas, NumPy, and Altair to analyze airline financial and operational data, identify drivers of declining profitability, and develop data-driven recommendations for improving operational efficiency and an estimated increase in annual profit of $23.7M.

## Tools & Skills

- **Python, pandas & NumPy:** Data cleaning, manipulation, and financial analysis
- **Altair & Matplotlib:** Exploratory data visualization and communicating analytical findings
- **Jupyter Notebook:** Analytical workflow and scenario modeling
- **Business Analytics:** Profitability analysis, operational optimization, and cost-benefit evaluation
- **Communication:** Data storytelling, teamwork, and presenting recommendations to judges

## Business Problem

Between FY2024–25 and FY2025–26, NorthByte experienced:

- **20.3% growth** in flights operated
- **5.2% growth** in ticket-sale transactions
- **23.5% growth** in flight operating costs
- Annual losses increasing from **$22.2M to $58.4M**

Our analysis found that flight capacity expanded substantially faster than demand, contributing to higher operating costs without proportional revenue growth.

## Data & Analytical Approach

Using Python, we analyzed:

- **558,129** transaction records
- **28,801** flights with associated operating costs
- **112** airport gate lease records

Our work focused on data cleaning, exploratory data analysis, financial performance, route-level profitability, and scenario modeling to evaluate potential operational improvements.

## Key Recommendations

We developed a phased strategy to improve profitability while maintaining regional connectivity.

| Recommendation | Projected Annual Profit Improvement |
|---|---:|
| Targeted flight frequency reductions | $10.98M |
| Bus partnerships on short-haul routes | $3.24M |
| **Total operational improvements** | **$14.22M** |
| Additional seasonal pricing scenario | Up to $9.50M |

Our recommendations considered financial feasibility, customer accessibility, implementation risks, and potential demand responses.

*These figures are scenario-based estimates, not realized savings. The pricing scenario is an illustrative target rather than a validated forecast.*

## Team & Acknowledgements

**Team Cranky Coders** — FirstByte Datathon 2026 Semifinalists

### Team Members

| Name | GitHub |
|---|---|
| Derek Lee | [@Derek1267](https://github.com/Derek1267) |
| Noah Hynds| [@noahhynds](https://github.com/noahhynds) |
| Yohei Ono | [@2005yoheiUBC](https://github.com/2005yoheiUBC) |
| Jayden Lieu | [@jlieu02](https://github.com/jlieu02) |

Thank you to the FirstByte organizers and judges for the opportunity to participate.

*This repository showcases our team's competition presentation. Source datasets and exploratory notebooks are not included.*

## Repository Structure & Usage
```text
.
├── .vscode/                 # VS Code workspace settings
├── data/
│   ├── processed/           # Cleaned CSV files generated from initial data processing
│   │   ├── booking_routes.csv
│   │   ├── bookings.csv
│   │   ├── flight_costs_df.csv
│   │   ├── gates_clean.csv
│   │   └── transactions_clean.csv
│   └── raw/                 # Original excel datasets provided for the datathon
│       ├── costs.xlsx
│       ├── gates.xlsx
│       └── transactions.xlsx
├── graphs/                  # Exported plots and visualizations (.png)
├── notebooks/               # Sequential analysis notebooks
│   ├── 01_clean_data.ipynb          # Raw data ingestion & cleaning pipeline
│   ├── 02_financial_analysis.ipynb  # Financial modeling, cost/revenue breakdowns, & EDA
│   └── 03_guiding_questions.ipynb   # Exploratory notes & qualitative answers to datathon prompts
├── .gitignore               # Ignored files and system artifacts
├── CrankyCoders_FirstByte.pdf # Final presentation / executive deck export
├── overview.md              # Additional project overview notes
└── README.md                # Main repository documentation
