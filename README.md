# Flu Vaccine Inventory Optimization for OuRx Pharmacy Chain

## Introduction
This project addresses the challenge faced by OuRx, a retail pharmacy chain, in determining the optimal order quantity for flu vaccines. Due to variability in demand and a long lead time for vaccine production, OuRx aims to refine its ordering strategy to avoid overstocking or stockouts.

## Project Background
In past flu seasons, OuRx has struggled with ordering an appropriate amount of flu vaccines. With a significant lead time and fluctuating demand, the company seeks to employ a simulation-based approach to forecast and optimize their inventory levels, thereby maximizing profit and minimizing waste.

## Data Overview
- The wholesale cost of the vaccine: $12 per dose
- Retail price of the vaccine: $20 per dose
- Historical demand data suggests a lognormal distribution for weekly vaccine demand.

## Simulation Goals
- Determine the net profit for order quantities in the face of uncertain demand.
- Establish a 95% credible interval for net profit at various order quantities.
- Assess the probability of vaccine stockouts to inform ordering decisions.

## Ordering Policy Analysis
The current ordering policy and alternative policies will be examined, including:
- A fixed-order quantity policy.
- Adjusting order quantities based on historical demand patterns.

## Methodology
The simulation model will incorporate demand variability and apply different order quantity policies. By evaluating the outcomes of these simulations, OuRx can identify the most profitable ordering strategy.

## Expected Outcomes
The simulation is expected to provide insight into:
- The net profit associated with different order quantities.
- The risk of stockouts at various order levels.

## Implementation
The simulation model has been developed using Python, as detailed in the attached Jupyter Notebook (Assign_3b(ourx)-1.ipynb). The code includes data preprocessing to handle outliers and implements a simulation based on the identified demand distribution.

## Simulation Results
For a range of order quantities (400,000 to 600,000 doses), the simulation will yield:
- Expected profit figures.
- Credible intervals for net profit.
- Probabilities of running out of the vaccine.

## Conclusions and Further Research
The results of the simulation will guide OuRx in refining its ordering policy. Additional strategies, such as dynamic ordering or tiered pricing, could be explored in future studies.

