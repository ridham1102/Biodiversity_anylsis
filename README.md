# Biodiversity Analysis of U.S. National Parks

This project explores biodiversity in selected U.S. National Parks using species and observation data. It provides insights into the distribution of species across various categories and conservation statuses. The project aims to highlight ecological diversity and conservation priorities through interactive visualizations and statistical summaries.

## Project Structure

- `observations.csv` - Dataset containing species sightings in national parks over a week.
- `species.csv` - Dataset with detailed taxonomical and conservation information of species.
- `Biodiversity_Analysis.ipynb` - Jupyter Notebook containing all analysis, visualizations, and explanations.

---

## Objectives

- Analyze species diversity across U.S. national parks.
- Identify species under threat and evaluate their conservation status.
- Explore relationships between species categories, park locations, and observation frequency.
- Visualize patterns using graphs for better understanding of biodiversity distribution.

---

## 📊 Dataset Overview

### 🔹 species.csv
Contains detailed information about each species.

- `category`: Type of organism (e.g., Mammal, Bird, Reptile, etc.)
- `scientific_name`: Scientific name of the species.
- `common_names`: Common names for the species.
- `conservation_status`: Indicates whether a species is endangered, threatened, or of concern.

### 🔹 observations.csv
Contains observational data about the frequency and location of species sightings.

- `scientific_name`: Scientific name of the species.
- `park_name`: Name of the national park.
- `observations`: Number of observations over a one-week period.

---

## Key Analyses

- Total unique species across all parks.
- Distribution of species by category.
- Number and percentage of protected species.
- National parks with the highest number of endangered or threatened species.
- Most observed species per park.
- Visualization of protection status vs category.
- Correlation between conservation status and observation frequency.

---

## 📈 Visualizations Used

- Bar Charts
- Pie Charts
- Grouped Bar Plots
- Count Plots
- Stacked Bar Charts

Libraries used:
- `pandas` for data manipulation
- `numpy` for numerical operations
- `matplotlib` and `seaborn` for data visualization

---

## Insights Gained

- Mammals and Birds are the most commonly observed species categories.
- A significant portion of species lack conservation status, suggesting under-evaluation.
- Some parks exhibit greater biodiversity but also show a higher number of endangered species.
- Protection efforts vary by category and park, which can guide future conservation planning.

---

## Technologies & Tools

- Python (Jupyter Notebook)
- pandas, numpy
- matplotlib, seaborn

---
## Project Workflow

1. **Data Preparation:** Cleaned and merged `species.csv` (taxonomy and status) with `observations.csv` (park sightings).
2. **Exploratory Analysis:** Calculated species counts, categorized by taxonomic groups, and tallied conservation statuses.
3. **Comparative Metrics:** Generated park-level summaries to highlight unique species counts and at-risk populations.
4. **Visualization:** Created bar charts, donut charts, and heatmaps to illuminate key trends.
5. **Interpretation:** Extracted stories that inform conservation priorities and research gaps.

As patterns emerged, compelling narratives took shape. I discovered that Denali’s Arctic ecosystems harbor a high number of species at risk, while parks abundant in flora often lack formal conservation assessments. Across all parks, mammals and birds accounted for the majority of sightings, but a striking 40% of species carry no official status, underscoring an urgent need for comprehensive evaluations.

Visualization played a starring role: bar charts compared category distributions, donut charts revealed the threat proportions, and heatmaps uncovered observation hotspots. These figures not only make the data accessible but also spotlight parks and species that could benefit most from targeted conservation efforts.

## Looking Forward

* **Seasonal Trends:** Expand the dataset beyond one week to uncover migration patterns and flowering seasons.
* **Interactive Dashboards:** Deploy Plotly Dash or Streamlit for real-time exploration by park managers and citizen scientists.
* **Geospatial Mapping:** Integrate Folium or GeoPandas to create map-based narratives of species distributions.
* **Predictive Modeling:** Leverage machine learning to forecast species risk levels under climate change scenarios.

I’m Ridham Arora, a final-year BCA student with a passion for data science and wildlife conservation. When I’m not building analyses, you’ll find me lost in a fantasy novel or planning my next travel adventure. If you share an interest in conservation analytics or have ideas for extending this work, I’d love to connect via [LinkedIn](https://www.linkedin.com/in/ridham-arora-24725a2a4/) or email me at [aridham1102@gmail.com](mailto:aridham1102@gmail.com).

*Made with curiosity and code by Ridham Arora*
