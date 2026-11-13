# Exploratory Data Analysis (EDA) on *"Student Performance"*
***Goal:** To understand the dataset’s structure, identify patterns, relationships, and potential
insights, and prepare it for deeper analysis.*
## 1. Data Overview
- **Dataset Title:** Student Performance Dataset
- **Context & Background:** The dataset reflects the students' academic performance through *Math, Reading, Writing* with some demographic information and parental level of education. It contributes to identifying the factors that affect students' performance.
- **Dimensions:** 202 rows (observations) và 8 column (variables).
## 2. Data Cleaning
The dataset contains 202 observations. After checking and cleaning the data, 197 valid observations remain, specifically:
#### *2.1 Handling Duplicates & Missing Values (First six columns):*
- Used **Power Query** to check and clean the first 6 columns => remove **3 duplicate rows** and **2 missing value rows.**
<img width="1920" height="593" alt="image" src="https://github.com/user-attachments/assets/8c098217-4421-41f3-9e12-9cf02d16a407" /> <img width="1920" height="788" alt="image" src="https://github.com/user-attachments/assets/448eaf9e-5c23-4a3d-a223-3403980558c5" /> 
***Result:** Retained **197 observations.*** 
#### *2.2 Calculating Missing Values (Last 2 Columns):*
- Checked the last 2 columns ***(total_score and average_score)*** and found ***4 missing cells*** in ***average_score***.
- Used Excel's **Filter** tool to filter out the blank rows in the ***average_score*** column.
  
<img width="1201" height="1133" alt="image" src="https://github.com/user-attachments/assets/f59c278c-bd53-41ac-8d87-13d94b45adf1" />

- Applied the ***= AVERAGE()*** formula to calculate and fill in the missing scores.

<img width="1408" height="480" alt="image" src="https://github.com/user-attachments/assets/e10da94f-2b68-45da-a50b-956de8c5d3f9" />

- Standardized the entire ***average_score*** column to **2 decimal places** for consistency

<img width="1398" height="432" alt="image" src="https://github.com/user-attachments/assets/5ddc309f-6652-4d37-a03f-437e71c01b30" />

***Result:** Completely clean dataset of **197 valid observations.*** 
## 3. Descriptive Statistics
- Used Excel's **Data Analysis** toolpak ***(Descriptive Statistics)*** to generate summary statistics for the score variables across **197 valid observations**.

<img width="1920" height="573" alt="image" src="https://github.com/user-attachments/assets/caedcde3-8c7b-434a-877e-23f51ff78dfe" />

<img width="1010" height="481" alt="image" src="https://github.com/user-attachments/assets/e1ede000-8fde-41c8-9b69-7a1a2244f19f" />









