# United Nations Global Terrorism Dashboard
## Overview
This project involves the creation of an interactive Tableau dashboard to analyze and visualize global terrorism data provided by the United Nations Global Terrorism Database. The dashboard offers insights into the frequency, locations, and types of terrorist incidents worldwide, providing a clear view of trends, patterns, and key factors influencing terrorism-related activities.

### Tools Used
Tableau: For creating interactive visualizations and dashboards.
United Nations Global Terrorism Database: Data source used to analyze and present terrorism-related incidents across various regions and time periods.
### Project Objective
The objective of this project is to build an informative and interactive dashboard that provides key insights into global terrorism trends. The dashboard aims to:

Analyze the distribution of terrorism incidents across countries and regions.
Identify trends in terrorism activities over time.
Examine the relationship between different types of attacks, target categories, and casualty figures.
Provide a comprehensive view of terrorism patterns and potential areas for intervention.
### Dataset Description
The dataset used in this project is the United Nations Global Terrorism Database (GTD), which includes information on global terrorist incidents from 1970 to 2017. The dataset contains the following key columns:

Year: The year the attack took place.
Country: The country where the attack occurred.
Region: The geopolitical region of the attack.
Attack Type: The type of attack (e.g., bombings, armed assault).
Target Type: The type of target (e.g., civilians, government, military).
Casualties: The number of deaths and injuries resulting from the attack.
Group Responsible: The group or organization responsible for the attack.
Location: Specific city or area of the attack.
### Data Preprocessing
The data preprocessing involved the following steps:

Data Cleaning:
Removed duplicate records to ensure data accuracy.
Filtered out irrelevant or incomplete data entries.
Handled missing values, particularly for columns like Group Responsible and Target Type.
Data Transformation:
Grouped data by year, country, and region for aggregation and analysis.
Converted categorical variables into dimensions to allow for better filtering in Tableau.
Normalization:
Standardized data entries where inconsistencies were found (e.g., different country names, inconsistent attack types).
Data Aggregation:
Aggregated data based on different dimensions such as year, country, and attack type to create meaningful insights.
### Actionable Insights
The key insights generated through the Tableau dashboard include:

Global Distribution of Terrorism:

Visualizes the number of terrorist incidents by country and region, highlighting areas most affected by terrorism.
Insight: This can help policymakers identify regions that need greater counter-terrorism resources and support.
Trends Over Time:

Displays the rise and fall of terrorist attacks over the years, illustrating periods of increased activity and potential causes (e.g., political unrest, military conflicts).
Insight: Helps understand how terrorism activity correlates with global events and political instability.
Types of Attacks and Targets:

Visualizes the types of attacks (e.g., bombings, armed assaults) and the distribution of attack targets (e.g., civilians, government buildings).
Insight: Offers insights into the most common forms of terrorism and the types of targets most frequently targeted, enabling more targeted security strategies.
Casualty Analysis:

Analyzes the number of casualties (deaths and injuries) by country, attack type, and target category.
Insight: Highlights regions with the most devastating impacts from terrorism, which could inform humanitarian aid and counter-terrorism efforts.
Identifying Key Terrorist Groups:

Identifies the most active terrorist groups and their historical impact on global terrorism.
Insight: Useful for governments and international organizations focusing on terrorism financing and neutralizing key groups.
### Visualizations
Several interactive visualizations were created in Tableau:

Map: Visualizes the global distribution of terrorist attacks by country and region.

Time-Series Graph: Shows trends in the number of terrorist incidents over time.

Bar and Pie Charts: Display attack types, targets, and casualties.

Heatmaps: Visualizes attack density across regions.

Tree Maps: Illustrates the most active terrorist groups and their attacks.
