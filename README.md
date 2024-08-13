# Enhancing Breast Cancer Diagnosis Through Dimensionality Reduction Techniques

This repository contains the code and documentation for the project "Enhancing Breast Cancer Diagnosis Through Dimensionality Reduction Techniques," aimed at improving the diagnostic processes for breast cancer using Principal Component Analysis (PCA) and clustering methods.

## Table of Contents

- [Introduction](#introduction)
- [Project Approach](#project-approach)
- [Data Source](#data-source)
- [Project Execution](#project-execution)
- [Results](#results)
- [Conclusion](#conclusion)
- [Future Enhancements](#future-enhancements)
- [Files](#files)
- [Usage](#usage)
- [Contributors](#contributors)
- [License](#license)

## Introduction

This project leverages advanced data analysis techniques to enhance the diagnostic processes for breast cancer. By applying PCA and clustering methods on a comprehensive dataset of breast cancer cases, we aim to uncover patterns and associations that can lead to more accurate and timely diagnoses.

## Project Approach

### Techniques Used
- **Principal Component Analysis (PCA)**: To reduce the dataset's dimensionality from 30 features, focusing on principal components that capture the most variance and simplify data analysis.
- **Clustering Techniques**:
  - K-Means Clustering: Segments patients into clusters based on similar characteristics, determining the optimal number of clusters through the elbow method.
  - Hierarchical Clustering: Creates a dendrogram to visualize and understand hierarchical relationships among patient cases.

## Data Source

The dataset used for this project is the Breast Cancer Wisconsin (Diagnostic) dataset from the UCI Machine Learning Repository. It contains 569 observations and 32 variables, including features like radius, texture, and concavity of cell nuclei.

- [Dataset Link](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic)

## Project Execution

### Data Loading and Preprocessing
- Loaded the dataset using R, assigned column names, and ensured data integrity by checking for missing values.
- Conducted Exploratory Data Analysis (EDA) to understand the distribution of diagnostic outcomes and features' correlations.

### PCA and Clustering Implementation
- **PCA**: Normalized the data, performed PCA to reduce dimensionality, and analyzed the variance explained by each principal component.
- **Clustering**: Implemented K-Means and Hierarchical clustering on both the original and PCA-reduced data, evaluating clustering accuracy and visualizing results through dendrograms and biplots.

## Results

- **PCA**: The first three principal components accounted for approximately 66% of the variance.
- **Clustering**: Achieved high clustering accuracy rates:
  - Hierarchical Clustering: 90.5%
  - K-Means Clustering: 91.04%

## Conclusion

The application of PCA and clustering provided valuable insights into the underlying structure of the breast cancer dataset. The identified clusters could be associated with different severity levels of breast cancer, aiding in treatment decisions.

## Future Enhancements

- Explore integration of these techniques into clinical decision-support tools.
- Investigate other machine learning methods to enhance predictive accuracy.

## Files

- `project.Rmd`: R Markdown file containing the code and analysis.
- `wdbc.data`: Data file used in the project.
- `wdbc.names`: Column names for the dataset.
- `biplot.png`: Biplot of PCA results.
- `scree.png`: Scree plot for PCA results.
- `Project Final Report.pdf`: Detailed project report.
- `Breast Cancer Awareness.pptx`: Presentation slides.
- `Demo.mp4`: Video demonstration of the project.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/MThufail/enhancing-breast-cancer-diagnosis.git

2. Navigate to the project directory:  
   ```bash
   cd enhancing-breast-cancer-diagnosis
   
3. Open project.Rmd in RStudio to view and run the analysis.
  
   
