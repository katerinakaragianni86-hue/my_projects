# Ship Fuel Consumption & CO2 Emissions Analysis (Team Project)

## Team Members
* Mariliza Sasmanidi
* Katerina Karagianni


## Project Overview
The **Ship Fuel Consumption & CO2 Emissions Analysis** is a comprehensive exploratory data analysis (EDA) focused on understanding maritime energy efficiency and environmental impact. Using a dataset of vessel voyages, this project investigates how factors such as ship type, route distance, fuel types, and weather conditions influence fuel consumption patterns and overall CO2 emissions. 

Our goal is to uncover meaningful insights through statistical analysis and data visualizations that can support sustainable shipping practices and data-driven operational decisions in the maritime industry.

## Objectives
* **Identify Fuel Consumption Patterns:** Analyze how fuel efficiency behaves across different vessel categories (e.g., Tankers, Fishing Trawlers, Service Boats).
* **Understand Environmental Impact:** Examine the direct correlation between fuel types, engine efficiency, operational conditions, and CO2 greenhouse gas emissions.
* **Visualize Industry Trends:** Utilize distributions, correlation plots, and comparisons to clearly communicate maritime efficiency findings.

## Dataset Features
The cleaned dataset contains information across the following key features:
* `ship_id` / `ship_type`: Identifiers and categories of vessels (e.g., Tanker Ship, Oil Service Boat, Fishing Trawler, Surfer Boat).
* `route_id`: Detailed specific maritime voyage routes.
* `distance`: Distance traveled per voyage (in miles).
* `fuel_type` / `fuel_consumption`: Types of fuel utilized (e.g., HFO, Diesel) and amounts consumed.
* `CO2_emissions`: Total carbon dioxide emitted.
* `weather_conditions`: Environmental status during transit (e.g., Stormy, Moderate, Calm).
* `engine_efficiency`: The recorded performance indicator of the vessel's engine.

## Python and Libraries Used
* **Python** (Core Language)
* **Pandas:** For data cleaning, feature engineering, and manipulation
* **NumPy:** For numerical and statistical mathematical operations
* **Matplotlib & Seaborn:** For creating high-quality analytical graphs, distributions, and correlation charts
* **Jupyter Notebook:** Interactive environment used for executing the steps of the EDA pipeline

## Project Workflow
1. **Data Cleaning & Standardization:** Handled missing values, normalized categorical strings, and outputted a reliable dataset version (`ship_fuel_efficiency_cleaned.csv`).
2. **Feature Engineering:** Calculated explicit metrics such as `fuel_per_mile` to evaluate standalone ship efficiency.
3. **Statistical Grouping:** Aggregate operations exploring average performance metrics conditioned by weather, ship type, and fuels.
4. **Data Visualization:** Built visual plots to confirm trends regarding engine stress, bad weather impacts, and emission trajectories.

## Key Insights 
* Data Cleaning & Quality: The raw dataset of 1,440 entries was verified to be of exceptionally high quality, with zero duplicate rows and no invalid or out-of-range values across any of the maritime features.

* Vessel Efficiency (Fuel per Mile): Tanker Ships were found to be the least efficient vessel type with the highest average consumption at 40.36 units per mile, while Surfer Boats proved to be the most efficient at just 15.06 units per mile.

* Fuel Consumption & CO2 Emissions: There is a direct, strong positive correlation between fuel consumption and carbon dioxide emissions, meaning that higher fuel usage instantly translates to a proportional increase in greenhouse gas output.

* Weather Conditions Impact: Adverse weather conditions, particularly stormy environments, noticeably increase the engine stress and fuel consumption per mile compared to operating in calm or moderate seas.
