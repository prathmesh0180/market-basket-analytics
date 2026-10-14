# Market Basket & Convenience Store Margin Analysis

## Objective
Analyze customer transaction patterns to identify high-affinity product pairings, optimizing cross-selling strategies and point-of-sale layout for retail operations.

## Methodology
1. **Data Preprocessing:** Cleaned transactional records, removed returns, and isolated positive sales quantities.
2. **Association Rule Mining:** Applied the Apriori algorithm via Python (`mlxtend`) to compute **Support**, **Confidence**, and **Lift** metrics.

## Key Findings
- Identified primary product affinities (e.g., specific beverage and snack combinations yielding high lift scores).
- Recommended targeted promotional bundling near checkout terminals to drive basket size expansion.

## Repository Structure
- `notebooks/`: Contains the exploratory data analysis and Apriori model execution.
- `outputs/`: Exported association rules and performance tables.
- `requirements.txt`: Python package dependencies.
