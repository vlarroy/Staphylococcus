# 🦠 Diversity and Antibiotic Resistance Patterns of Staphylococcus Species in Clinical Sources

![Staphylococcus](staphylococcus.png)

## 🌟 Overview

Welcome to the second project of my Data Analytics Bootcamp! This project focuses on investigating the diversity and antibiotic resistance patterns of Staphylococcus species found in different clinical sources.

[**View the Project Presentation (PDF)**](https://github.com/vlarroy/Staphylococcus/blob/master/Antibiotic%20resistance%20patterns%20in%20Staphylococcus%20isolates%20in%20clinical%20settings.pdf)

## 🎯 Objectives

### 1. Diversity of Staphylococcus Species in Clinical Sources
- **Research Questions:**
  1. What is the diversity of Staphylococcus species in different clinical sources (e.g., blood, throat, nose, endovascular, tissue)?
  2. How does the distribution of Staphylococcus aureus and Staphylococcus pseudintermedius vary across these clinical sources?

### 2. Antibiotic Resistance Patterns
- **Research Questions:**
  1. What are the antibiotic resistance patterns of Staphylococcus aureus and Staphylococcus pseudintermedius isolates from various clinical sources?
  2. Are there significant differences in antibiotic resistance profiles between isolates from different clinical sources?

## 📊 Data Sources

- **Source:** [NCBI Pathogen Detection](https://www.ncbi.nlm.nih.gov/pathogens/)
- **Datasets:**
  - S. aureus isolates
  - S. pseudintermedius isolates

## 🔍 Data Cleaning and Analysis Process

### 1. Data Cleaning
- **Techniques:**
  - Selection of relevant columns
  - Cleaning and formatting the relevant columns using functions
  - Concatenating datasets of two Staphylococcus species

### 2. Exploratory Data Analysis
- **Methods:**
  - Frequency distribution of species and genotypes
  - Shannon diversity index for assessing species diversity
  - Chi-square test for statistical significance in distribution patterns

### 3. Visualization
- **Tools:**
  - Bar charts and pie charts for diversity analysis
  - Heatmaps for antibiotic resistance patterns

## 🔑 Key Findings

1. **High Prevalence of S. aureus:** S. aureus dominates clinical samples.
2. **Respiratory System:** The primary isolation source for Staphylococcus species.
3. **Common AMR Genes:** tet(38), mepA, fosB, blaI, and blaZ are the most common.
4. **Diversity Analysis:**
   - **Highest Diversity:** The urinary system shows the highest Shannon Diversity Index, indicating a rich variety of Staphylococcus species.
   - **Lowest Diversity:** The bloodstream and cardiovascular system exhibit the lowest diversity, suggesting a more homogenous Staphylococcus population.

## 📚 Conclusions & Insights

### Key Takeaways: Unmasking Staphylococcus Threats

1. **High Prevalence of S. aureus:** Dominates clinical samples.
2. **Respiratory System:** Primary isolation source.
3. **Key AMR Genes:** tet(38), mepA, fosB are most common.
4. **Diversity:** Highest in the urinary system, lowest in the bloodstream and cardiovascular system.

## 📁 Repository Structure

- **`data/`**: Contains the raw and cleaned datasets.
- **`notebooks/`**: Jupyter notebooks used for data cleaning, EDA, and analysis.
- **`images/`**: Visualizations generated during the project.
- **`README.md`**: This file.

## 🙏 Acknowledgments

This project is the second project of my Data Analytics Bootcamp. Special thanks to the instructors and peers for their support and guidance.

