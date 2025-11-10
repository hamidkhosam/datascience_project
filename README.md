# 🌍 Electricity Access Analysis (2012–2016)

This project analyzes the **percentage of population with access to electricity** across **242 countries** from **2012 to 2016**.  
It uses **Python, Pandas, Matplotlib, and Seaborn** to explore, clean, and visualize the dataset.

---

## 📊 Dataset Description

The dataset contains:
- **Country Name**, **Country Code**, **Series Name** and **Series Code**
- **Five columns (2012–2016)** indicating the percentage of population with access to electricity
- **Continent** for geographical grouping


Each row corresponds to a single country.

---

## 🧭 Project Objectives

The notebook performs several analytical steps to explore the data and derive insights:

1. **Dataset description**  
   Overview of the content and purpose of the dataset.

2. **Initial exploration**  
   - Display of dataframe shape (rows and columns)  
   - Data types inspection (`df.info()`) and commentary

3. **Data selections (4 examples)**  
   - Filtering with `.loc[]` (e.g., African countries)  
   - Selection with `.iloc[]` (specific rows/columns)  
   - Subsets for countries with low access (<80%)  
   - Reduced dataframe with selected columns

4. **Sorting (2 examples)**  
   - Ascending by 2016 access (lowest access first)  
   - Descending by 2016 access (highest access first)

5. **New column creation**  
   - Created `Access_Category` using `apply` + `lambda` to classify access as “Basso”, “Medio”, or “Alto”.

6. **Data visualization (5 graphs total)**  
   Using both **Matplotlib** and **Seaborn**:
   - 📈 **Histogram** – Distribution of access in 2016  
   - 📊 **Boxplot** – Access by continent (2016)  
   - ⚫ **Scatter plot** – Comparison between 2012 and 2016  
   - 🔹 **Line plot** – Global average over time (2012–2016)  
   - 🟩 **Bar chart** – Bottom 10 countries in 2016  

   Each visualization includes a title, axis labels, and interpretation.

7. **Conclusion**  
   Summary of key findings and possible future analyses.

---

## 🧩 Key Insights

- Global electricity access **increased steadily** between 2012 and 2016.  
- **Africa and parts of Oceania** show the lowest average access rates.  
- **Europe and North America** have nearly universal access.  
- The **distribution** is heavily skewed toward higher values, but a few countries still lag behind.  
- Categorizing countries by access level reveals significant regional disparities.

---

## ⚙️ Tools & Libraries Used

| Library | Purpose |
|----------|----------|
| **Python 3.12.7** | General programming |
| **Pandas** | Data cleaning & manipulation |
| **Matplotlib** | Visualization |
| **Seaborn** | Advanced visualization |
| **Jupyter Notebook** | Interactive analysis |

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/electricity-access-analysis.git
   cd electricity-access-analysis
