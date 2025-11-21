# Practice-Repo

# Mini Open Methods Memo (Activity 14)

This repository contains my work for **STAT 184 / STAT 200 – Activity 14**, 
including:

- A reproducible Quarto document (`activity14-mom.qmd`)
- The rendered PDF submission (`activity14-mom.pdf`)
- A planning document (`PLAN.md`) for both the project and this repository
- Evidence of using GitHub issues, branches, commits, and pull requests


## 🔍 Project Overview

This project combines three major tasks:

### 1. Armed Forces Data Wrangling
- Reads a public Google Sheets dataset using a URL.
- Cleans and reorganizes the data.
- Lenghtens counts into individual soldier-level rows.
- Creates a frequency table focusing on **female soldiers**.

### 2. Popularity of Baby Names
- Uses `dcData::BabyNames`.
- Identifies the top three girl and boy names by total count.
- Builds a time series plot using color + line type for accessibility.

### 3. Box Problem Function Plot
- Defines a mathematical volume function for a 36 × 48 inch sheet.
- Uses `ggplot2::stat_function()` to plot volume vs. cut-out size.


## Repository Structure

/Practice-Repo-Sumaiya
│
├── activity14-mom.qmd # Quarto source file
├── activity14-mom.pdf # Rendered PDF submission
├── README.md # Repo documentation (this file)
├── PLAN.md # Planning document
└── .gitattributes


## Data Sources

- **Armed Forces dataset** (Google Sheet)  
  `https://docs.google.com/spreadsheets/d/1cn4i0-ymB1ZytWXCwsJiq6fZ9PhGLUvbMBHlzqG4bwo/export?format=xlsx&gid=597536282`

- **Baby Names dataset**  
  `dcData::BabyNames`
  

## Reproducibility

To re-render the PDF:

1. Clone the repository
2. Open `activity14-mom.qmd` in RStudio
3. Install required R packages
4. Click "Render"


## Contact

**Author:** Sumaiya Azad  
email: sva6303@psu.edu 
