# Obesity Analysis Final Project

## Project Overview

This project analyzes factors contributing to obesity using interview-based data. It includes:
- Exploratory data analysis (EDA) in Python (Jupyter)
- Visual analytics in Power BI
- Cleaned and raw datasets
- A PowerPoint presentation summarizing the findings

---

## Folder Structure
```bash
big_data_final_exam/
│
├── data/ # Raw and cleaned datasets
├── notebooks/ # Python (Jupyter) analysis code
├── powerBI/ # Power BI dashboard (.pbix)
├── presentation/ # PowerPoint summary presentation
└── README.md # Project guide
```
## Dataset Details:

Source Link: https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition

### Fields meaning:
- Gender (Categorical): Gender
- Age (Continuous): Age	
- Height (Continuous)
- Weight (Continuous)
- family_history_with_overweight (Binary): Has a family member suffered or suffers from overweight?
- FAVC (Binary): Do you eat high caloric food frequently?
- FCVC (Integer): Do you usually eat vegetables in your meals?
- NCP (Continuous/Integer): How many main meals do you have daily?
- CAEC (Categorical): Do you eat any food between meals? 
- SMOKE (Binary): Do you smoke?
- CH2O (Continuous): How much liters of water do you drink daily?	
- SCC (Binary): Do you monitor the calories you eat daily?	
- FAF (Continuous): How often do you have physical activity?		
- TUE (Integer): How much time do you use technological devices such as cell phone, videogames, television, computer and others?		
- CALC (Categorical): How often do you drink alcohol?		
- MTRANS (Categorical): Which transportation do you usually use?		
- NObeyesdad (Categorical): Obesity level

---

## Methodology

- **Data Source**: CSV data collected via interviews.
- **Cleaning**: Handled missing values, converted Yes/No to 1/0.
- **Analysis**: Performed using Python (pandas, matplotlib, seaborn).
- **Visualization**: Created interactive dashboards in Power BI.

---

## Power BI Dashboard

- **Page 1: Data from Interview**
  - Pie charts for Yes/No responses
  - Bar charts for frequency-type questions
  - Filters for obesity categories and age

- **Page 2: Data from Analysis**
  - Obesity category distribution
  - Insights and patterns identified during analysis
  - Use of BMI as patterns insight

> 📁 Open `powerBI/Rwagapfizi_Igor_27329_PowerBI.pbix` in Power BI Desktop

---

## Jupyter Notebook

The Python notebook:
- Loads and cleans the data
- Performs EDA
- Prepares analysis summaries

> 📁 View the notebook at `notebooks/exam.ipynb`

---

## Presentation

The slide deck highlights:
- Project overview and objectives
- Methodology and tools used
- Key results and recommendations
- Suggestions for future work

> 📁 View at `presentation/Rwagapfizi_Igor_27329_Presentation.pptx`

---

## How to Run

1. Install requirements:
   ```bash
   pip install pandas matplotlib seaborn
2. Open and run `exam.ipynb` using Jupyter Notebook.
3. Open `.pbix` file using Power BI Desktop.

## Author

**Rwagapfizi Igor, 27329, Group E**  
Adventist University of Central Africa – Introduction to Big Data Assignment Project (July 2025)