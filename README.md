# QTM 350 - Group 5
# Regression Analysis of Regional Indicators

## Project Description
This project explores regional differences in economic indicators using data from the World Bank's WDI (World Developement Indicators) Database. The project starts with some data exploration, followed by an analysis that focuses on identifying key predictors of GDP per capita in top-performing (North America and Europe & Central Asia) and bottom-performing (South Asia and Sub-Saharan Africa) regions. The study investigates relationships between **GDP per Capita** and the following predictors:
- Adjusted net national income per capita (annual % growth)
- Employment to population ratio (15+, total)
- Tax revenue (% of GDP)

## Repository Contents
- data folder: contains all datasets created and used
- documentation folder: contains the codebook
- figures folder: contains png files of all outputs from the data exploration and analysis
- scripts folder: contains all the files needed for the quarto report
- requirements.txt file: contains versions of all packages needed to run the code
- README.md file: project description, contents and instructions (this file)

## Instructions on How to Run the Code
1. Clone this repository
2. Install dependencies from `requirements.txt`:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the project folder in your preferred editor (e.g., VS Code, JupyterLab).
4. Render the `report.qmd` file to HTML or PDF:
   ```bash
   quarto render report.qmd
   ```