# Ethanol–Water Distillation Simulation

## Overview
This project models the separation of an ethanol–water mixture using DWSIM. This DWSIM project explores how operating conditions affect the simulated separation of an ethanol–water mixture.

## Goal
Model a steady-state distillation column separating ethanol and water. Study how changing the reflux ratio affects the simulated product compositions, ethanol recovery, and condenser and reboiler duties.

## Tools
- DWSIM Version 10.2.12.0
- Excel

## Model and method
This project will models the steady-state separation of a binary ethanol–water feed in DWSIM. The feed is Ethanol-Water at 20 degree celcius at pressure 1.01325 bar, with varying reflux ratio, and NRTL property package was used. The planned study is to vary the reflux ratio while holding the other inputs constant, then compare simulated product. compositions and energy duties and check material balances. No physical distillation experiment is planned.

## Files
- `model/` — DWSIM simulation file
- `data/` — simulation results
- `calculations/` — balance checks and calculations
- `figures/` — diagrams and plots
- `report/` — project report

## Limitations
This is a simulation project. No physical distillation experiment was performed. Results depend on the model assumptions and thermodynamic property package.

## How to view
Open the `.dwxmz` file in DWSIM. See [DWSIM’s official download page](https://dwsim.org/index.php/download/).
