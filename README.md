# Analysis of Single-Effect Absorption Refrigeration Cycles

This project provides a comprehensive thermodynamic study of a **Single-Effect Absorption Refrigeration System** with and without a heat exchanger (regenerator). The study includes manual calculations and software modeling using **EES (Engineering Equation Solver)**.

## Project Overview
The project compares a simple single-effect cycle with an advanced cycle featuring a regenerator. It evaluates how various temperatures (Evaporator, Generator, Condenser, and Absorber) and regenerator effectiveness impact the **Coefficient of Performance (COP)** and the **Refrigeration Effect**.


### Key Components Analyzed:
* **Evaporator:** Where the refrigerant (Water/LiBr) absorbs heat from the environment.
* **Absorber:** Where the LiBr solution absorbs water vapor.
* **Generator:** Where heat is added to separate the refrigerant from the solution.
* **Condenser:** Where the refrigerant rejects heat to the environment.
* **Regenerator (Heat Exchanger):** Improves efficiency by preheating the solution.

## Parametric Study Findings
Based on the simulation results:
* **Evaporator Temperature:** Increasing $T_{evap}$ leads to higher COP and a greater refrigeration effect.
* **Generator Temperature:** COP generally increases with $T_{gen}$ up to a certain point, while the refrigeration effect improves as well.
* **Condenser & Absorber Temperatures:** Increasing these temperatures negatively impacts both COP and the refrigeration effect due to decreased pressure differentials and absorption efficiency.
* **Regenerator Effectiveness:** Higher effectiveness increases COP by reducing the required generator heat but does not change the refrigeration effect.

