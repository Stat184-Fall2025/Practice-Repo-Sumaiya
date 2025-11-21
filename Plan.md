# PLAN Document – Activity 14 & Activity 15

This document outlines my planning process for both the Activity 14 project and this GitHub repository.

---

## 1. Goals

### Activity 14 Goals
- Create a complete, reproducible Quarto document for the Mini Open Methods Memo.
- Include Armed Forces data wrangling, Top 3 Baby Names data visualization, and Box Problem Function Plot.
- Provide explanations, reflection and a Code Appendix.
- Ensure YAML header is properly formatted 
- Ensure all data paths are reproducible (no local file paths).

### Activity 15 Goals
- Set up a public GitHub repository.
- Use branches, commits, pull requests, and issues properly.
- Include documentation and a planning file.
- Make the repo fully reproducible and self-contained.

---

## 2. Needs

### Project Needs
- RStudio with Quarto installed.
- R packages:  
  `readxl`, `dplyr`, `tidyr`, `janitor`, `kableExtra`, `knitr`, `dcData`, `ggplot2`.

- Data:
  - Armed Forces dataset Google Sheets URL.
  - The `dcData::BabyNames` dataset.

### Repo Needs
- A public GitHub repository.
- At least one additional branch besides `main`.
- At least two GitHub issues with labels.
- Pull requests linking commits to issues.
- `MOMM_Activity14_Sumaiya.qmd` and `MOMM_Activity14_Sumaiya.pdf` in the repo.

---

## 3. Steps

### Steps for the Project (Activity 14)

1. Write the QMD file with YAML, narrative text, and code blocks.
2. Extract Google Sheets data URL and create frequency table for female soldiers subset.
3. Generate top 3 baby names data visualization.
4. Generate Box Problem visualization section using `stat_function()`.
5. Add reflection text.
6. Render file to produce PDF.

### Steps for the GitHub Repo (Activity 15)

1. Create a public GitHub repository.
2. Clone it locally in RStudio.
3. Create a development branch (`dev-report`).
4. Add Activity 14 files, README, PLAN.md.
5. Create Issues #1 and #2.
6. Commit changes referencing issues:
7. Push commits to the dev branch.
8. Open a Pull Request from dev → main.
9. Write PR description and link issues.
10. Merge PR into main.
11. Confirm issues were automatically closed.

---
