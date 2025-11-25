# Syntecxhub_FlowerClassification
Flower Classification (Iris) — Colab-ready notebook &amp; script for Syntecxhub internship Week 2. EDA, model training (Logistic Regression &amp; Decision Tree), evaluation, confusion matrices, and saved best model.


# Syntecxhub_FlowerClassification

**Week 2 — Flower Classification (Iris Dataset)**  
Colab-ready project for the Syntecxhub Machine Learning Internship. This repo contains a Python script and a Jupyter notebook that perform EDA, train two classifiers (Logistic Regression & Decision Tree), compare results, plot confusion matrices, and save the best model.

---

## Files to upload (local)
When uploading to GitHub, include these files (I generated them and saved locally):
- `/mnt/data/flower_classification_colab.py` — main Colab-ready script  
- `/mnt/data/flower_classification_colab.ipynb` — converted Colab notebook  
- `/mnt/data/A_screenshot_of_a_user_interface_displays_metallic.png` — LinkedIn PNG (metallic style)  
*(If you upload from your computer, use the files you downloaded from the environment.)*

---

## Project Overview
- **Dataset:** Iris (sklearn)  
- **Models:** Logistic Regression, Decision Tree  
- **Evaluation:** Accuracy, Confusion Matrix, Classification Report  
- **Output:** Saved best model pipeline in `artifacts/` and CSV summaries (misclassifications, reports)

---

## How to run

### Option A — Run in Google Colab (recommended)
1. Open Google Colab → File → Upload notebook → select `flower_classification_colab.ipynb`.
2. Run all cells.  
Artifacts will be created in `./artifacts/` (plots, `best_model_*.pkl`, CSV summaries).

_or_ run the script directly after uploading `.py` file to Colab files panel:
```python
# in a Colab cell after uploading the .py file
!python flower_classification_colab.py
