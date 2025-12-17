# 🌍 Global Development Dashboard

## Project overview
This project presents an interactive dashboard that explores global development indicators such as life expectancy, GDP per capita, population, and other socio-economic metrics at the country level. 

The goal is to help users:
- Compare development levels across countries and regions
- Identify patterns between economic and health indicators
- Quickly understand which countries are performing well or lagging behind on key metrics

The dashboard is aimed at data enthusiasts, students, and decision-makers who want an at-a-glance view of global development.

---

## Data description
**Source:** Country-level development dataset (Excel file: `Country-development-raw.xlsx`)

The dataset includes:
- Country name
- Region
- Life expectancy
- GDP per capita
- Population
- Additional development indicators

Data was cleaned and prepared before visualization (see `docs/methodology.md` for details).

---

## Tools and technologies
- **Excel / Power BI / Tableau:** Data modeling and dashboard creation  
- **Python (Pandas, NumPy):** Data cleaning and transformation (optional / if used)  
- **Git & GitHub:** Version control and project documentation  

---

## Methodology
1. **Data collection**
   - Imported raw country development data from Excel into the BI tool.

2. **Data cleaning**
   - Removed duplicates and obvious errors
   - Standardized country and region names
   - Handled missing values appropriately
   - Created cleaned dataset stored in `data/cleaned/`

3. **KPI definition**
   - Selected key indicators:
     - Average life expectancy
     - GDP per capita
     - Population
     - Development category (e.g., low / medium / high, if applicable)

4. **Dashboard design**
   - Created a clean, minimal layout with:
     - Summary KPIs at the top
     - A world map to compare countries
     - Bar/line charts to compare indicators by region
     - Filters for region, income group, and year (if available)

---

## Dashboard features
- **Interactive filters** for region, country, and (if available) year  
- **KPI cards** summarizing key metrics  
- **Map visual** to show development differences geographically  
- **Comparative charts** to analyze relationships between GDP, life expectancy, and population  

A static preview is available in `images/dashboard-overview.png`.

---

## Key insights
Some example insights derived from the dashboard:

- Countries with higher GDP per capita tend to have higher life expectancy.
- There are significant regional differences in both health and economic indicators.
- Some countries achieve relatively high life expectancy despite moderate GDP, suggesting effective public health policies.

---



Regional disparities highlight development gaps.
Population size does not directly correlate with development outcomes.
