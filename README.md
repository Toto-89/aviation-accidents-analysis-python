# Aviation Accidents Analysis (1919–2023)

## Project Overview
This project was developed for the **International Alliance for Safe Skies (IASS)** to analyze worldwide aviation accidents from **1919 to 2023**.  
The objective was to explore almost **25,000 recorded accidents** and extract meaningful insights through data analysis and visualizations.

The analysis focuses on identifying patterns related to:
- accident frequency across countries
- temporal trends over time
- fatalities by aircraft type
- operator safety
- changes in accident patterns after major historical events such as **September 11, 2001**

## Business Context
The newly established **IASS** aims to improve aviation safety through data-driven analysis.  
To support this mission, the organization provided a dataset containing detailed records of aviation accidents over more than a century.

The role of the data analyst is to transform raw accident records into actionable insights that can help identify high-risk contexts, understand long-term trends, and support safer decision-making in the aviation sector.

## Dataset
The dataset contains information on aviation accidents from **1919 to 2023**, with the following fields:

- **date** → accident date  
- **type** → aircraft type  
- **registration** → aircraft registration code  
- **operator** → aircraft operator  
- **fatalities** → number of deaths  
- **location** → accident location  
- **country** → country where the accident occurred  
- **cat** → accident category as described by ASN  

## Files Included
- **Aviation_Accidents_1919–2023.ipynb** → Jupyter Notebook with the complete analysis
- **aviation-accidents.csv** → source dataset

## Project Objectives
The project was designed to answer analytical questions such as:
- In which country did the highest number of accidents occur?
- Are accidents more frequent on specific days of the week?
- Which operators appear to be safer?
- Which aircraft types caused the highest number of fatalities?
- How did aviation accidents evolve after **9/11**?

The analysis also goes beyond these questions by exploring additional trends and relationships found in the data.

## Analysis Scope
The notebook explores the dataset through:
- data cleaning and preparation
- descriptive statistics
- temporal analysis
- country-level analysis
- operator-level analysis
- fatalities analysis
- visualization of major patterns and anomalies

## Key Analytical Areas

### 1. Country Analysis
The project investigates the geographical distribution of aviation accidents to identify:
- countries with the highest number of accidents
- national patterns in aviation safety
- possible concentration of incidents in specific regions

### 2. Time Analysis
The temporal dimension is used to study:
- accident trends across decades
- changes in accident frequency over time
- weekly distribution of accidents
- pre- and post-September 11 comparisons

### 3. Operator Analysis
The project examines operators in order to identify:
- operators with the highest number of accidents
- operators associated with lower fatality levels
- possible indicators of relative operational safety

### 4. Aircraft Type Analysis
The analysis explores which aircraft types are associated with:
- the highest number of accidents
- the highest number of fatalities
- recurring patterns linked to specific models or categories

### 5. Fatalities Analysis
Fatalities are studied to better understand:
- the deadliest accidents
- aircraft types linked to the greatest human impact
- how the severity of accidents has changed over time

## Visualizations
The project includes charts and visual explorations to make findings more accessible and interpretable.  
Depending on the notebook implementation, these may include:
- time series plots
- bar charts
- categorical comparisons
- fatality rankings
- country-based distributions

## Bonus Analysis
As suggested by the project brief, the analysis may also include a **cartogram or geographic representation** of accident counts by country, providing an additional visual layer for understanding global accident distribution.

## Skills Demonstrated
This project showcases the following skills:
- Python data analysis
- data cleaning and preprocessing
- exploratory data analysis (EDA)
- statistical reasoning
- temporal trend analysis
- categorical analysis
- data visualization
- Jupyter Notebook documentation
- insight generation from real-world historical data

## Business Value
This project provides value by:
- highlighting long-term aviation safety patterns
- identifying high-risk countries, operators, and aircraft types
- helping interpret the evolution of aviation incidents over time
- supporting safety-oriented, evidence-based discussions
- transforming historical accident records into useful analytical insight

## Tools Used
- **Python**
- **Pandas**
- **Matplotlib / visualization libraries**
- **Jupyter Notebook**

## Author
**Salvatore Spagnolo**
