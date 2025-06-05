# US Census Demographic Data Visualization (2015)

This project uses Tableau to explore and visualize 2015 US Census data, focusing on transportation patterns, income distribution, poverty rates, and remote work trends across the United States.

## 🔍 Project Objective

To uncover and communicate socioeconomic insights from US Census data using interactive, well-designed dashboards. The goal is to help viewers understand:
- How transportation behavior varies by state and county
- The relationship between household income and poverty
- Patterns in work-from-home adoption and how they relate to income and geography

---

## 📊 Visualizations

### 1. Average Commute Time by State
**🔗 [View Dashboard](https://public.tableau.com/views/Visualisation1Averagecommutetimebystate/Sheet1)**

- **Description:** Displays average commute times across all US states.
- **Insight:** States like New Jersey, Maryland, and DC experience the longest average commutes (~30 mins), while rural states such as South Dakota and North Dakota have significantly shorter commute times.
- **Design:** 
  - Horizontal bar chart for easy comparison
  - Sorted in descending order by commute time
  - Color palette optimized for readability

---

### 2. Household Income vs. Poverty by County
**🔗 [View Dashboard](https://public.tableau.com/views/Visualisation2Householdincomeandpovertyacrossstates/Sheet2)**

- **Description:** Scatter plot illustrating the correlation between median household income and poverty rate at the county level.
- **Insight:** A strong negative correlation is evident. Counties with higher incomes typically exhibit lower poverty rates. Some outliers highlight areas with unique economic conditions.
- **Design:** 
  - Scatter plot with income on X-axis and poverty on Y-axis
  - Tooltips show county name, income, poverty rate
  - Axes formatted with appropriate units (USD and %)

---

### 3. Transportation Behavior & Income Dashboard
**🔗 [View Dashboard](https://public.tableau.com/views/Dashboard_17462039952030/Dashboard1)**

- **Description:** Combines two visualizations—transit usage by county and work-from-home rates by state.
- **Insight:** Urban counties show high public transit use. States with higher income and tech-oriented industries (e.g., Colorado, Massachusetts) lead in remote work.
- **Design:**
  - Bubble map for visualizing transit use at the county level
  - Bar chart for WFH adoption by state
  - Interactive filter for selecting individual states
  - Tooltips include state, county, population, and income

---

## 🧮 Data Source

- Dataset: [ACS 2015 County Data from Kaggle](https://www.kaggle.com/datasets/muonneutrino/us-census-demographic-data)
- File used: `acs2015-county-data.csv`

---

## 💡 Key Insights

- There is a clear disparity in commute times that aligns with levels of urbanization and congestion.
- Income is inversely related to poverty, though certain counties exhibit exceptions worth exploring.
- Remote work is more common in higher-income, tech-heavy states.
- Urban counties show higher reliance on public transit systems.

---

## 🛠️ Tools Used

- **Visualization:** Tableau Public
- **Data Prep:** CSV handling in Tableau
- **Design Framework:** Data storytelling and dashboard design principles

---

## 🎨 Design Considerations

- Visual hierarchy with clear color schemes
- Interactive elements (filters, tooltips)
- Consistent layout and formatting across dashboards
- Minimalist aesthetic to keep focus on insights

---

## 📚 Resources

- Kaggle Census Dataset
- Mapbox / OpenStreetMap (used in Tableau for base maps)
- N/A (no external blogs or academic papers referenced)

---

## 🧾 License

This project is for educational and non-commercial use under the [MIT License](https://opensource.org/licenses/MIT).

---


