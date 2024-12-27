
# Female Participation in 50km Ultra-Marathons in the USA (2018): An Exploratory Analysis

## Project Overview  
This project explores the participation trends in ultra-marathons, focusing on female participants in 50km races held in the USA during 2018. The dataset, sourced from [Kaggle](https://www.kaggle.com/datasets/aiaiaidavid/the-big-dataset-of-ultra-marathon-running/discussion/420633), was analyzed using Python libraries such as Pandas and Seaborn to conduct exploratory data analysis (EDA).  

The analysis focuses on identifying the most common age categories, the countries with the highest participation rates, and visualizing trends using advanced Seaborn plots.

---

## Objectives  
- Analyze ultra-marathon participation trends for female athletes in 50km races held in the USA during 2018.  
- Examine the most represented age categories and the top participating countries.  
- Visualize data trends with Seaborn's `lmplot`, `violinplot`, and `histplot`.  

---

## Techniques Used  

### 1. Data Acquisition  
- Dataset sourced from [Kaggle](https://www.kaggle.com/datasets/aiaiaidavid/the-big-dataset-of-ultra-marathon-running/discussion/420633).  
- Followed the tutorial by [Data Science Made Simple](https://www.youtube.com/watch?v=4sZFkPw87ng) for guidance.  

### 2. Data Cleaning  
- Renamed columns to improve readability.  
- Filtered data to include only:  
  - Female participants.  
  - Races held in the USA in 2018.  
  - Races with a distance of exactly 50km.  
- Addressed missing or inconsistent values in key columns.  
- Standardized country names and age formats for consistency.  

### 3. Data Analysis  

#### Age Analysis  
- Identified the most common age group for female participants in 50km races.  
- Visualization:  
  - `violinplot` to depict the spread of ages among participants.  
  - `histplot` to display the frequency of participants by age group.

#### Country Participation  
- Analyzed the top countries participating in 50km races in the USA.  
- Visualization:  
  - `lmplot` to explore the relationship between age and participation across countries.  

---

## Conclusions  
- **Age Trends:** The majority of female participants in 50km races belonged to the 30–35 age group.  
- **Country Insights:** The USA had the largest number of participants, with notable contributions from Canada and the UK.  
- **Visual Insights:**  
  - Violin plots revealed that participants in the 30–50 age range dominate 50km races.  
  - Histograms showed peaks in participation frequency at 30–35 years of age.  
  - Regression plots suggested consistent participation trends across top countries.  

These findings provide valuable insights into the demographics and regional representation in ultra-marathons.  

---

## Tools Used  
- **Python Libraries:**  
  - `Pandas` for data wrangling, cleaning, and filtering.  
  - `Seaborn` for creating advanced visualizations like violin plots, histograms, and regression plots.  

---

## How to Use  
1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/aiaiaidavid/the-big-dataset-of-ultra-marathon-running/discussion/420633).  
2. Run the Python script or Jupyter Notebook provided in this repository.  
3. Explore the visualizations to gain insights into ultra-marathon participation trends.  

---

## Acknowledgments  
- Dataset provided by [David on Kaggle](https://www.kaggle.com/datasets/aiaiaidavid/the-big-dataset-of-ultra-marathon-running).  
- Analysis guided by the tutorial from [Data Science Made Simple](https://www.youtube.com/watch?v=4sZFkPw87ng).  

## License  
This project is licensed under the [Insert License Here].  
