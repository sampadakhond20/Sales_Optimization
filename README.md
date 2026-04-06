# Retail Sales Optimization

End-to-end analytics and optimization project for identifying loss-making products and improving overall sales performance using the Superstore dataset.

## 1. Project Overview

- Project Name: Sales Optimization
- Domain: Retail
- Dataset: Kaggle - Superstore Sales Dataset
- Core Problem: Identify loss-making products and optimize sales
- Primary Goal: Build strong analytics and clear, structured data representations to support business decisions

## 2. Objectives

- Clean and prepare raw sales data for analysis
- Detect products, categories, and segments that consistently generate losses
- Understand feature relationships affecting profit and sales
- Create actionable business insights backed by exploratory and statistical analysis
- Prepare a foundation for future machine learning models

## 3. Team & Responsibilities

### Team Members

- Om (Leader)
- Vanshika
- Sampada
- Yash
- Arif

### Functional Roles in Project

- Team Lead: Coordinate milestones, reviews, and final delivery
- Data Engineer: Data ingestion, cleaning pipelines, and data quality checks
- Data Analyst: Exploratory analysis, visualizations, and reporting
- Statistician: Distribution analysis, outlier strategy, and significance checks
- ML Engineer: Feature-ready dataset preparation and modeling baseline (future phase)
- Business Analyst: Translate findings into business actions and recommendations

Note: Specific role-to-person mapping can be finalized in sprint planning.

## 4. Repository Structure

```text
Sales_Optimization/
|-- data/         # Raw, interim, and processed datasets
|-- notebooks/    # EDA, profiling, and analysis notebooks
|-- src/          # Reusable Python scripts/modules
|-- reports/      # Final insights, charts, and summary outputs
`-- README.md     # Project documentation
```

## 5. Workflow

Standard team workflow:

1. JIRA Task
2. GitHub Branch
3. Commit
4. Pull Request (PR)
5. Review
6. Merge

Recommended branch naming:

- `feature/<task-name>`
- `bugfix/<task-name>`
- `analysis/<task-name>`

## 6. Current Backlog

The following tasks define the analysis pipeline:

1. Data Cleaning
2. Missing Values Treatment
3. Distribution Analysis
4. Outlier Detection & Handling
5. Category Analysis
6. Correlation Analysis
7. Insights & Recommendations

Suggested tracking format:

| Task | Owner | Status | Notes |
|------|-------|--------|-------|
| Cleaning | TBD | Planned | Standardize types, duplicates, invalid records |
| Missing Values | TBD | Planned | Null profiling and imputation strategy |
| Distribution | TBD | Planned | Sales/profit spread across dimensions |
| Outliers | TBD | Planned | Detect extreme values and business-valid exceptions |
| Category Analysis | TBD | Planned | Category/Sub-category profitability |
| Correlation | TBD | Planned | Numeric and encoded feature relationships |
| Insights | TBD | Planned | Final findings and business actions |

## 7. Analysis Scope

Key questions this project should answer:

- Which products and sub-categories are consistently loss-making?
- Which regions/segments contribute high sales but low profit?
- What discount patterns lead to negative margins?
- Which high-performing products should be prioritized?

## 8. Expected Outputs

- Cleaned analysis-ready dataset in `data/`
- EDA notebooks in `notebooks/`
- Reusable analysis utilities in `src/`
- Final report and visual summaries in `reports/`
- Actionable recommendations for sales and profitability optimization

## 9. Getting Started

1. Clone the repository.
2. Place the Superstore dataset in `data/`.
3. Create and activate a Python environment.
4. Install dependencies.
5. Run notebooks in sequence from data cleaning to insights.

Example setup commands:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

If `requirements.txt` is not available yet, install commonly used packages:

```powershell
pip install pandas numpy matplotlib seaborn jupyter scikit-learn
```

## 10. Success Criteria

- Clear identification of loss-making products and root causes
- Strong visual and statistical evidence for recommendations
- Reproducible analysis workflow for team collaboration
- Business-ready summary for decision-makers


<!-- ------------------------------------IMPORTANT------------------------------------------->

## ⚙️ Environment Setup

This project uses a unified `environment.yml` file to manage dependencies using Conda and pip.

### 📦 Prerequisites

* Install Conda (Anaconda or Miniconda)

---

### 🚀 Create the Environment

Run the following command in your project directory:

```bash
conda env create -f environment.yml
```

---

### ▶️ Activate the Environment

```bash
conda activate sales-optimization-env
```

---

### 📚 Installed Libraries

The environment includes:

* Core Data Libraries: `pandas`, `numpy`
* Visualization: `matplotlib`, `seaborn`, `plotly`
* Machine Learning: `scikit-learn`
* Notebook Support: `jupyter`, `notebook`
* File Handling: `openpyxl`

---

### 🔄 Update the Environment (if dependencies change)

```bash
conda env update -f environment.yml --prune
```

---

### ❌ Remove the Environment

```bash
conda remove --name sales-optimization-env --all
```

---

### 💡 Notes

* This setup combines Conda and pip dependencies in a single file for better reproducibility.
* Ensure the environment is activated before running notebooks or scripts.
* Python version used: **3.11**

---
