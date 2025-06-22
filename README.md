Biodiversity Analysis in National Parks
Project Overview
This project analyzes two datasets related to National Parks and their resident species to explore patterns in biodiversity and conservation status. The analysis aims to identify relationships between species observations, their categories, and their conservation status across different national parks.

Data
The analysis utilizes two datasets:

observations.csv: Contains records of species sightings in various national parks over a one-week period.
scientific_name: Unique scientific identifier for the species.
park_name: The national park where the observation occurred.
observations: The number of times a species was observed in the preceding 7 days.
species_info.csv: Provides detailed information about species, including classification and conservation status.
category: Broad taxonomic grouping (e.g., Mammal, Bird).
scientific_name: Unique scientific identifier for each species.
common_names: Popular names for the species.
conservation_status: Conservation status (e.g., Endangered, Species of Concern).
Note: These datasets were sourced from Codecademy.com and are based on real-world concepts, though the data itself is primarily simulated.

Analysis and Key Findings
The analysis covered initial data exploration, data cleaning, and in-depth exploration of the data focusing on conservation statuses, species categories, and observations within different parks.

Key findings include:

Consistent Proportions: The relative proportions of observations across different conservation statuses and species categories are remarkably consistent across all national parks, despite variations in total observation counts.
Observation and Conservation Status Relationship: There is a clear inverse relationship between the severity of a species' conservation status and its average observation count. Species with more critical statuses tend to have fewer observations.
Category-Specific Risks:
Mammals show the highest overall risk and the highest proportion of endangered species.
Birds have the highest proportion of species of concern.
Aquatic species (Amphibians and Fish) exhibit elevated rates of endangerment and are generally more threatened.
Plant categories (Vascular and Nonvascular) have the lowest proportion of species at risk.
Statistical Significance: Statistical tests indicate that Mammals have a significantly higher rate of endangerment compared to Birds, Nonvascular Plants, and Vascular Plants (with over 95% confidence).
Notebook Structure
The analysis is structured within a Jupyter Notebook, divided into the following sections:

Initial Data Exploration: Loading and preliminary inspection of the datasets.
Cleaning the Data: Handling missing values and duplicate entries in both dataframes.
Exploring the Data:
Part 1: Analyzing conservation statuses within different parks.
Part 2: Visualizing proportions of conservation statuses and exploring the relationship with observations.
Part 3: Investigating conservation statuses within different species categories.
Part 4: Examining category observations across different parks.
Statistical Significance Among Endangered Species: Performing statistical tests to determine significant differences in endangerment rates between species categories.
Summary of Findings and Conclusions: A comprehensive summary of the insights drawn from the analysis.
