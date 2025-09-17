# Economic Shocks and Socioeconomic Forces

## Project Overview
This project analyzes the impact of global crises on GDP worldwide and examines how socioeconomic factors shape economic outcomes during these periods.  

- Compiled a **multi-country panel dataset (1999–2023)** from **World Bank** and **IMF** sources.  
- Variables include: GDP, poverty rates, population, and natural resource rents.  
- Incorporated dummy variables to represent the **2008 Financial Crisis** and **COVID-19 pandemic**.  
- Preprocessed data with transformations (log, cube-root, Yeo–Johnson) and harmonization across countries.  

## Methodology
Analysis was performed in **R** using econometric and statistical modeling techniques:  

1. **Data Preparation**  
   - Extensive cleaning, transformations, and feature engineering.  
   - Constructed a balanced panel across 100+ countries.  

2. **Modeling**  
   - Estimated multiple regression and econometric models.  
   - Conducted diagnostic checks for **multicollinearity** and **heteroscedasticity**.  
   - Compared model performance using **Adjusted R²**.  

3. **Crisis Analysis**  
   - Added binary indicators for major global shocks.  
   - Investigated interactions between poverty, population, and crisis effects.  

## Results Summary
- Adjusted R² up to **0.35** across models.  
- Model diagnostics confirmed validity of regression assumptions.  
- Socioeconomic interactions were particularly influential during crisis periods.  

*(Detailed results available in `results/`)*  

## Repository Layout
- `data/` – final dataset (`Final_Data.csv`) and data processing scripts (`DataCode.R`).  
- `scripts/` – R scripts for modeling and diagnostics (`analysis.R`).  
- `results/` – figures, tables, and model outputs.  
- `README.md` – project description and instructions.  

## References
- World Bank. *World Development Indicators (WDI).* Available at: [https://databank.worldbank.org/source/world-development-indicators](https://databank.worldbank.org/source/world-development-indicators)  
- International Monetary Fund (IMF). *World Economic Outlook (WEO) Database.* Available at: [https://www.imf.org/en/Publications/WEO](https://www.imf.org/en/Publications/WEO)  

