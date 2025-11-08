# Manufacturing_Defects_Data_Analysis

This project analyzes defect data from a manufacturing process to identify patterns, assess severity levels, and estimate repair costs.  
The analysis provides insights into the most frequent defect types, their locations, and potential factors affecting quality and cost.

---

## Objective
The goal of this analysis is to:
- Identify the most common defect types across production lines.
- Analyze how defect severity and repair costs vary by location or inspection method.
- Detect time trends in defect occurrences using the `defect_date` field.
- Support quality improvement and cost reduction decisions.

---

##  Dataset
The dataset (`defects_data.csv`) includes the following columns:

| Column | Description |
|---------|--------------|
| `defect_type` | Type or category of defect (e.g., crack, misalignment, discoloration). |
| `defect_date` | Date when the defect was detected. |
| `defect_location` | Specific location or production area where the defect occurred. |
| `severity` | Severity level of the defect (e.g., minor, major, critical). |
| `inspection_method` | Method used to detect the defect (manual, automated, visual, etc.). |
| `repair_cost` | Estimated cost (in USD) required to repair the defect. |

---

##  Tools & Libraries
The analysis uses the following Python libraries:
- `pandas` — data cleaning and manipulation  
- `numpy` — numerical analysis  
- `matplotlib` & `seaborn` — data visualization  
- `scikit-learn` — optional predictive modeling or clustering  

---

## 📊 Notebook
The analysis notebook is available here:  
[notebooks/manufacturing_defects.ipynb]
(notebooks/manufacturing_defects.ipynb)

It includes:
- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA)  
- Visualization of defect types, severity, and cost patterns  
- Optional predictive modeling for defect severity or cost  



## 🚀 How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/tinabazargani/manufacturing_defects.git


## Author
**Tina Bazargani**  
[LinkedIn](https://linkedin.com/in//tina-bazargani-552713339)  
[GitHub](https://github.com/tinabazargani)

