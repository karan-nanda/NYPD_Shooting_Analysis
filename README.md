# NYPD_Shooting_Analysis
# 🗽 NYPD Shooting Incident Analysis

This project explores and analyzes historical shooting incident data from the NYPD, with a focus on understanding patterns in time, geography, and demographics. The project includes data cleaning, visualization, predictive modeling, and discussion of systemic biases.

## 📂 Project Structure

NYPD_Shooting_Analysis/
├── NYPD_Shooting.Rmd # Reproducible R Markdown analysis
├── NYPD_Shooting.html # HTML output of the report
├── NYPD_Shooting_Incident_Data__Historic_.csv # Cleaned dataset from NYC Open Data
├── README.md # Project description and instructions
└── LICENSE # MIT License

markdown
Copy
Edit

## 📊 Overview of Analysis

### Key Visualizations:
- **Shooting Trends Over Time by Borough**
- **Hourly Distribution of Shootings**
- **Demographics of Victims & Perpetrators**

### Modeling:
A random forest classifier was trained to predict whether an incident would be classified as a **statistical murder**, using demographic and location-based features. While the model showed high sensitivity, it failed to achieve meaningful specificity, highlighting the limitations of the dataset.

### Bias Considerations:
- Missing perpetrator data
- Reporting and surveillance bias across boroughs
- Potential racial and systemic bias in law enforcement practices

---

## 🔍 Dataset Source

- **Name**: NYPD Shooting Incident Data (Historic)
- **Source**: [NYC Open Data on Data.gov](https://catalog.data.gov/dataset/nypd-shooting-incident-data-historic)
- **Format**: CSV
- **Size**: ~40,000+ records (depending on latest export)

---

## ▶️ How to Reproduce

To run the `.Rmd` file:

1. Download or clone the repository:
   ```bash
   git clone https://github.com/karan-nanda/NYPD_Shooting_Analysis.git
   ```
2. Open NYPD_Shooting.Rmd in RStudio.

3. Ensure the following R packages are installed
```bash
install.packages(c("tidyverse", "lubridate", "caret", "ggplot2"))
```
4. Click "Knit" to generate the HTML report.

   
