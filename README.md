# 🎬 Netflix Dataset Analysis using Python

This project focuses on performing **data cleaning**, **exploration**, and **visualization** on a Netflix dataset using Python libraries such as **Pandas**, **Matplotlib**, and **Seaborn**.  
It also includes the implementation of **Python Logging** for tracking and debugging purposes.

---

## 📘 Project Overview

The goal of this project is to analyze the Netflix dataset to extract meaningful insights and visualize key trends such as the most frequent genres and the year with the most film releases.

---

## 🧰 Libraries Used

- **Pandas** – for data cleaning, manipulation, and statistical analysis  
- **Matplotlib** – for creating visual plots and charts  
- **Seaborn** – for advanced and aesthetic data visualizations  
- **Logging** – for tracking code execution and debugging  

---

## ⚙️ Steps Involved

### 🔹 1. Data Inspection
- Loaded the dataset using Pandas  
- Inspected rows, columns, and basic statistics  
- Checked for **null** and **duplicate** values  

### 🔹 2. Data Cleaning
- Dropped unnecessary columns  
- Modified data types of columns where required  
- Renamed labels in the `Vote_average` column based on value ranges  
- Split the **‘Genres’** column into multiple genre entries  
- Reset the dataset index for better consistency  

### 🔹 3. Statistical Analysis
- Performed descriptive statistical analysis  
- Identified **movies with maximum and minimum popularity**  

### 🔹 4. Data Visualization
- **Seaborn:** Visualized the **most frequent genres** of Netflix movies  
- **Matplotlib:** Showed **which year had the most film releases**  

### 🔹 5. Saving the Processed Dataset
- Exported the cleaned and modified dataset using `to_csv()`  

---

## 🧠 Python Logging Implementation

This project includes **logging files** that record the program’s execution flow.  
Logging was implemented using the **`logging`** module to:

- Track key processes (INFO level)  
- Identify and debug potential issues  
- Maintain clean and structured event records  


logging.info("Dataset loaded successfully.")
