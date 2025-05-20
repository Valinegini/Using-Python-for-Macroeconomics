# Using-Python-for-Macroeconomics
# ECON 8220 Final Project - A Model with Labor, Capital Taxes, and Land

## Overview
This project, conducted for ECON 8220 - Applied Macroeconomics (Fall 2023) under Prof. Marcelo Arbex, investigates the effects of an incomplete tax system within a Neoclassical Growth Model. We focus on the steady-state equilibrium where capital, labor, and land are used in production, but the government can only tax capital and labor, leaving land untaxed. Here, "land" is broadly interpreted to include natural resources and nature’s waste-absorbing capacity. By calibrating the model to the Canadian economy and comparing it with Italy’s tax composition, we analyze optimal tax policies and their impact on economic welfare, providing insights into balancing fiscal policy and economic efficiency.

## Approach
We solved for the steady-state equilibrium of the Neoclassical Growth Model and calibrated it to reflect key features of the Canadian economy. The analysis involved:
- Comparing Canada’s tax composition (personal income tax, corporate tax, and consumption taxes) with Italy’s using data from OECD Revenue Statistics and FRED.
- Quantitatively analyzing optimal tax policies for the steady state.
- Contrasting our findings with the standard Neoclassical Growth Model discussed in class to highlight the implications of an untaxed input (land).

The model was implemented in Python, with numerical solutions derived using libraries such as `pandas`, `matplotlib`, `numpy`, `statsmodels`, `termcolor`, and `tabulate`.

## Key Outcomes
Our analysis revealed several critical insights:
- **Tax Policy Impact**: Optimizing household and firm decisions under fixed government revenue showed that higher labor and capital tax rates increase government revenue but reduce consumption, negatively affecting household utility.
- **Tax Composition Comparison**: From 1965 to 2021, Canada’s total tax revenue as a percentage of GDP rose steadily to 33.2%, while Italy’s reached 43.3%. Canada, however, has higher shares of corporate and personal income taxes compared to Italy.
- **Steady-State Calibration**: We formulated equations for household utility maximization, firm profit maximization, and government budget constraints to achieve steady-state equilibrium, calibrated to match Canadian economic data (e.g., labor share, interest rates, and land prices).

## Conclusion and Policy Implications
This study underscores the critical role of tax policy in shaping economic outcomes. Constant tax rates are insufficient for maximizing steady-state utility, and high tax rates on labor or capital can reduce welfare by lowering consumption and output. Policymakers should aim for balanced tax policies to avoid adverse effects, such as firm closures or labor market disruptions, while supporting economic stability. Consistent with the Neoclassical Growth Model, sharp increases in capital taxes reduce output and capital per worker, emphasizing the need for moderation. Our findings advocate for tax policies that promote efficiency and societal welfare by carefully balancing the needs of households, firms, and the government.

## Repository Contents
- `Group#_TaxesLand_Project.ipynb`: Python notebook containing the full analysis and code.
- `Group#_Project_Summary.pdf`: One-page executive summary of findings.
- `Tax.csv`, `Data_TR.csv`: Data files required to run the notebook.

## Requirements
To run the Python notebook, install the following:
- Python 3.x
- Libraries: `pandas`, `matplotlib`, `numpy`, `statsmodels`, `termcolor`, `tabulate`

## Instructions
1. Clone the repository: `git clone https://github.com/your-username/ECON8220-Final-Project.git`
2. Ensure all data files (`Tax.csv`, `Data_TR.csv`) are in the same directory as the notebook.
3. Install required libraries: `pip install pandas matplotlib numpy statsmodels termcolor tabulate`
4. Open and run `Group#_TaxesLand_Project.ipynb` in Jupyter Notebook or a compatible environment.

