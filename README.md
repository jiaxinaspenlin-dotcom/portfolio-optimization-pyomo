# Portfolio Optimization & Time-Series Analysis (Pyomo)

Team project for two 10-asset portfolio study. I served as the **Modeling Lead**, owning the end-to-end modeling workflow: returns engineering, risk metrics, optimization, and evaluation.

## Overview
This project explores portfolio construction under different risk constraints and compares tradeoffs between **expected return vs. risk**. The notebook includes:
- Data prep + returns feature engineering
- Risk metrics (e.g., volatility / downside risk depending on configuration)
- **Optimization in Pyomo** to generate portfolios under constraints
- Efficient frontier analysis across multiple risk limits

## Key Results
- Produced an **efficient frontier** across multiple risk targets/constraints
- Validated optimization outputs and summarized the **risk–return tradeoff** for decision-making

## Tech Stack
- Python
- Pyomo (optimization modeling)
- NumPy / Pandas
- Matplotlib / Seaborn

## How to Run
1. Clone the repo  
   ```bash
   git clone https://github.com/jiaxinaspenlin-dotcom/portfolio-optimization-pyomo.git
   cd portfolio-optimization-pyomo
