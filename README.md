# 🌿 Biodiversity Analysis of U.S. National Parks

This project explores biodiversity in selected U.S. National Parks using species and observation data. It provides insights into the distribution of species across various categories and conservation statuses. The project aims to highlight ecological diversity and conservation priorities through interactive visualizations and statistical summaries.

## 📁 Project Structure

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

## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/ridham1102/Biodiversity_anylsis.git
   cd Biodiversity_anylsis
