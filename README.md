# breast-cancer-lp-julia

Julia project for MATH 271 (Spring 2025, Carleton College) exploring breast cancer diagnosis and prognosis using linear programming. Uses the Wisconsin Breast Cancer Diagnostic dataset to build and analyze a predictive model, comparing LP-based classification with traditional statistical methods.

This repository contains an implementation of a linear-programming–based classifier for the Wisconsin Breast Cancer Diagnostic dataset. The project investigates whether optimization-based models can achieve interpretable and competitive performance compared to standard machine-learning methods.

## Project Structure

LICENSE # License for the repository
README.md # Project documentation
data/ # Raw and processed datasets
images/ # Figures generated for analysis and the report
notebooks/ # Jupyter notebooks for EDA, modeling, and LP formulation
report.pdf # Final project report

## Project Overview

he goal of this project is to formulate the breast-cancer classification task as a **linear program (LP)** and evaluate its effectiveness.  
Key components include:

- Data cleaning and preprocessing
- Exploratory data analysis
- LP formulation for binary classification
- Implementation in Julia using JuMP and an LP solver
- Model evaluation and comparison with baseline methods
- Visualizations and interpretation of results

The complete methodology and findings are summarized in `report.pdf`.

## Technologies Used

- **Julia** (core implementation)
- **JuMP.jl** (optimization modeling)
- **HiGHS / GLPK** (LP solver)
- **IJulia / Jupyter** (interactive exploration)
- **Python/Matplotlib** (optional, if used for plots)

## 📊 Model Visualization

Below is an example of the linear programming classifier’s decision boundary:

<p align="center">
  <img src="images/msm_pca_true_labels.png" width="600">
</p>
