# Truck Turnaround Time (TAT) Analysis and Reduction

Python analysis of truck turnaround time across 4 FMCG warehouses, with root-cause analysis and an optimisation model to reach a 3.0-hour TAT target.

## Problem
Trucks spend 4.32 hours per visit on average against an assumed 3.0-hour target. Only 21.08% of trucks meet it.

## Data
Synthetic data: 2,500 truck visits, 4 warehouses (Patna, Kolkata, Jamshedpur, Ranchi), April to September 2026. Four CSV files: truck visits, warehouse, transporter and dock masters.

## Approach
1. Data cleaning and validation
2. Exploratory analysis (8 business questions)
3. Root-cause and workload analysis
4. Optimisation: dock allocation simulation and linear programming

## Key Findings
- Loading (43%) and dock wait (32%) take most of the visit
- Dock Congestion causes 71.5% of flagged delays
- Trucks at a busy dock wait 125 min, against 24 min at a free dock
- First-free-dock allocation cuts TAT to 3.69 hours; 79.3 min per truck must be saved to reach 3.0 hours

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, SciPy

## Limitations
Data is synthetic, and the 3.0-hour target and optimisation costs are assumed.
