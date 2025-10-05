# prog8245-data-processing – Week 5 Lab Notebook

This repository hosts **data processing and analysis work** for the **Week 5 lab** in the PROG8245 course. The primary artifact is a Jupyter Notebook that guides through cleaning, exploring, and preparing data for modeling.

## Repository Structure

```
/
├─ data/                       # Folder for raw or processed datasets  
├─ week5Lab.ipynb              # Lab notebook  
├─ README.md                   # This file  
└─ requirements.txt            # Python dependencies  
```

## Purpose & Scope

The notebook demonstrates:
- Loading a dataset into a `pandas` DataFrame  
- Identifying and handling missing or malformed data  
- Converting columns to appropriate types  
- Imputing missing values using median or most frequent strategies  
- Exploratory data analysis (summary stats, distribution plots)

## Learning Goals

- Load and inspect tabular data  
- Clean and normalize data frames  
- Distinguish numeric vs categorical features  
- Impute missing values responsibly  
- Document your analysis clearly for others to follow  

## Requirements

Install prerequisites before running:

```bash
pip install -r requirements.txt
```

Typical dependencies include:
- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  
- jupyter  

## How to Use

1. Clone or download this repository.  
2. Launch Jupyter in the repository directory:  
   ```bash
   jupyter notebook
   ```  
3. Open `week5Lab.ipynb` and run the cells in order.  
4. Use the Markdown explanations as guidance through each step.

