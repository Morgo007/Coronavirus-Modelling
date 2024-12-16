# Coronavirus-Modelling

This repository contains a Jupyter Notebook that implements a Susceptible-Infected-Recovered-Susceptible (SIRS) model to simulate the transmission dynamics of COVID-19. The project evaluates the effects of facemask usage and population lockdowns on infection rates. Included in this repository, is a labatory report which describes and evaluates the projects methods and results. 

This repository serves as an accessible resource for researchers and policymakers aiming to understand the impact of non-pharmaceutical interventions on COVID-19 transmission dynamics.

## Table of Contents
- Introduction
- Model Description
- Notebook Contents
- Key Findings
- Contributing

## Introduction

This project applies a mathematical SIRS model to explore the effects of facemask coverage and lockdown implementation on the spread of COVID-19. By analyzing these interventions, the study aims to assess their effectiveness in reducing infection peaks and delaying outbreaks. The results are supported with statistical analyses to provide additional insights.

## Model Decription

This model incorporates:
- **Susceptible-Infected-Recovered-Susceptible (SIRS) Framework:** Accounts for the gradual loss of immunity over time, a critical feature for studying reinfection dynamics.
- **Intervention Variables:** Adjusts the transmission rate to account for varying levels of facemask effectiveness, population coverage, and lockdown implementation.
- **Statistical Testing:** Uses two-sample t-tests, to evaluate the significance of interventions on peak infections.

## Notebook Contents

1. **Parameter Initlisation:** Definition of key epidemiological parameters, including R0, recovery rate, immunity loss rate, and intervention parameters.
2. **Mathematical Modelling:** Implementation of the SIRS model using Python’s scipy and numpy libraries.
3. **Simulation Analysis:**
   - Simulation of infection dynamics for varying facemask coverage and lockdown conditions.
   - Comparison of scenarios with and without interventions.
4. **Statistical Evaluation:** Conducting t-tests to assess the significance of facemasks and lockdowns on peak infection rates.
5. **Visualisation:** Generation of heatmaps and timeseries plots to illustrate infection trends under different scenarios.

## Key Findings

1. **Facemask Effectiveness**: A fully-masked population was shown to significantly reduce infection peaks and delay outbreaks, particularly when combined with lockdowns.
2. **Lockdown Impact:** Lockdowns alone were effective in reducing transmission, but the combination of interventions had the most substantial effect on flattening infection curves.
3. **Critical Insights:** The inclusion of immunity loss revealed cyclical waves of reinfection, which were not observed in studies assuming long-term immunity.

## Contributing

Contributions to this project are welcome! If you have suggestions for improving the model, adding new analyses, or optimizing the code, please feel free to create a pull request or open an issue.



