# Analysis of Single-Effect Absorption Refrigeration Cycles

[cite_start]This project provides a comprehensive thermodynamic study of a **Single-Effect Absorption Refrigeration System** with and without a heat exchanger (regenerator)[cite: 22, 76]. [cite_start]The study includes manual calculations and software modeling using **EES (Engineering Equation Solver)**[cite: 24, 187].

## Project Overview
[cite_start]The project compares a simple single-effect cycle with an advanced cycle featuring a regenerator[cite: 77, 88]. [cite_start]It evaluates how various temperatures (Evaporator, Generator, Condenser, and Absorber) and regenerator effectiveness impact the **Coefficient of Performance (COP)** and the **Refrigeration Effect**[cite: 25, 26, 187].


### Key Components Analyzed:
* [cite_start]**Evaporator:** Where the refrigerant (Water/LiBr) absorbs heat from the environment[cite: 122, 124].
* [cite_start]**Absorber:** Where the LiBr solution absorbs water vapor[cite: 122, 130].
* [cite_start]**Generator:** Where heat is added to separate the refrigerant from the solution[cite: 137, 138].
* [cite_start]**Condenser:** Where the refrigerant rejects heat to the environment[cite: 140, 295].
* [cite_start]**Regenerator (Heat Exchanger):** Improves efficiency by preheating the solution[cite: 38, 397].

## Parametric Study Findings
[cite_start]Based on the simulation results[cite: 187, 199]:
* [cite_start]**Evaporator Temperature:** Increasing $T_{evap}$ leads to higher COP and a greater refrigeration effect[cite: 203, 224].
* [cite_start]**Generator Temperature:** COP generally increases with $T_{gen}$ up to a certain point, while the refrigeration effect improves as well[cite: 248, 265].
* [cite_start]**Condenser & Absorber Temperatures:** Increasing these temperatures negatively impacts both COP and the refrigeration effect due to decreased pressure differentials and absorption efficiency[cite: 294, 323, 349, 373].
* [cite_start]**Regenerator Effectiveness:** Higher effectiveness increases COP by reducing the required generator heat but does not change the refrigeration effect[cite: 397, 421].

## How to Run the Code
1. Open the `.ees` file in the `/Code` directory.
2. Ensure you have the **EES** software installed.
3. [cite_start]Run the "Parametric Table" to reproduce the plots shown in the report[cite: 187, 199].

## Authors
* [cite_start]Seyed Nima Atyabi [cite: 8]
* [cite_start]Amir Abbas Ahmadizadeh [cite: 9]
* [cite_start]Sajjad Sarrafzadeh [cite: 10]

[cite_start]**Course:** Thermodynamics II, University of Tehran [cite: 5, 16]
[cite_start]**Instructor:** Dr. Behrang Sajjadi [cite: 12]
