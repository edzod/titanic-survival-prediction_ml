# Titanic – Survival Prediction (Two-Part ML Coursework)

**Overview.** Classic Kaggle binary-classification project predicting passenger survival on the Titanic.  
Built in two phases: **Part A (baseline)** - **Part B (advanced)** with richer feature engineering and model tuning.

**Collaborators:** Eden Fabrikant & Yael (course teammate)  
*(HTML notebooks include authorship in the header; this README credits both of us.)*

## Repository Structure

## Files in this repo
- "baseline_01/"  
  - "Titanic_Assignment_2.ipynb" (and ".html") - initial EDA, baseline features, simple model
- "advanced_02/"  
  - "Titanic_Assignment_3_final.ipynb" (or ".html") - advanced FE, model tuning, final model
- "submissions/"  
  - "submission_titanic_2.csv", "submission_titanic_3.csv" - Kaggle submissions

## Methods
- **EDA:** missing values, categorical encodings (sex/embarked), outlier checks.
- **Feature Engineering:** family size, title extraction, ticket/cabin handling, binning (fare/age), interactions.
- **Models:** Logistic Regression (baseline), Decision Tree, and K-Means clustering for exploratory segmentation.  
  Advanced phase include tuned tree-based models and regularized linear models.

## Results
- Local CV (accuracy/recall/F1): ⟨fill⟩  
- Kaggle Public LB: ⟨fill⟩  
- Notes: Advanced features improved ⟨metric⟩ by ⟨Δ⟩ vs. baseline.

## How to run
1. "pip install -r requirements.txt"
2. Download Kaggle Titanic "train.csv" & "test.csv" to a local "data/" folder (not committed).
3. Open notebooks in "01_baseline/" then "02_advanced/".
4. Export predictions to "submissions/" as CSV.

## Data & Academic Integrity
- Raw Kaggle data is **not** included. This repo contains **our code and submissions only**.
- This is sanitized coursework; no exam text or restricted materials are published.

## License
MIT – see "LICENSE".
