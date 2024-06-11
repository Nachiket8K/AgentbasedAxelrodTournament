# Axelrod's Tournament Simulation

## Overview
This project simulates Axelrod's Tournament on a toroidal grid where agents employ various strategies to play the Iterated Prisoner's Dilemma. The simulation involves 100 agents moving randomly across a 15x15 grid, interacting and playing the Prisoner's Dilemma when they encounter each other. The results of the simulation are saved to an Excel file and analyzed using Python.

## Installation
To run this project, you need to have Python installed along with the following libraries:

- pandas
- numpy
- matplotlib
- openpyxl

You can install the required libraries using pip:

```bash
pip install pandas numpy matplotlib openpyxl

```
 
## Strategies
The simulation includes the following strategies:

- TitForTat
- TitForTwoTats
- AlwaysCooperate
- AlwaysDefect
- Random
- GrimTrigger
- Pavlov
- GenerousTitForTat
- HardTitForTat
- ForgivingTitForTat

Each strategy defines how an agent decides its next move based on the history of interactions with its opponent.

