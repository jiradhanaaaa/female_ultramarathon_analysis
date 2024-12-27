
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
- **Age Trends:** The majority of female participants in 50km races belonged to the 40-50 age group, with more than 35000 participants.
![image](https://github.com/user-attachments/assets/6e23c738-41b2-4b37-9b59-8fde13c320bb)
- **Country Insights:** The USA had the largest number of participants, with notable contributions from Canada and the UK.
![image](https://github.com/user-attachments/assets/a8fdc888-a16e-441f-97be-64563050ace3)
- **Visual Insights:**  
  - Violin plots revealed that younger categories, like W23, tend to have higher speeds, with their distributions leaning toward higher values (above 8 km/h).
  ![Screenshot 2024-12-27 194713](https://github.com/user-attachments/assets/7f22c632-d3bb-4587-89d4-36c3b6d27e3b)
  - Histograms showed that the majority of female participants came from W23
  ![Screenshot 2024-12-27 195104](https://github.com/user-attachments/assets/e9ebd32d-3e37-47fb-a23b-8c2e746d4405)

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
