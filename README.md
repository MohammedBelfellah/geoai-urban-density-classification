# GeoAI – Land Use Classification

## Project Title

**Mini-projet 3 – Classification de zones urbaines selon leur densité**

## Group

**Groupe 1**

- Er-rakho Khadija
- Ibn Aissa Ferdaous
- Walid El Maataoui
- Issa Zouak
- Mohammed Belfellah

## Project Overview

This project classifies urban zones by density using AI and geospatial data. The workflow includes:

- Data loading and inspection
- Data cleaning and normalization
- Feature/target preparation
- Train/Test split
- Model training and tuning
- Performance evaluation and visualization

## Project Structure

- `GeoAI_UrbanDensity_Preprocessing_Normalization.ipynb` – data preprocessing and normalization
- `module_logistic_regression.ipynb` – logistic regression baseline
- `module_knn.ipynb` – KNN classification module
- `module_Random Forest.ipynb` – Random Forest classification module
- `module_svm.ipynb` – SVM classification and tuning
- `module_xgboost_classification.ipynb` – XGBoost classification and tuning
- `data/geo_urban_density_data.csv` – raw dataset
- `data/geo_urban_density_data_preprocessed.csv` – preprocessed dataset
- `figures/` – generated figures and model outputs
- `requirements.txt` – Python dependencies

## Requirements

- Python 3.8+
- Install dependencies with:

```bash
pip install -r requirements.txt
```

## Getting Started

1. Clone/download this project.
2. Create and activate a virtual environment (recommended).
3. Install dependencies from `requirements.txt`.
4. Open the notebooks in Jupyter or VS Code.

## Suggested Execution Order

1. `GeoAI_UrbanDensity_Preprocessing_Normalization.ipynb`
2. `module_logistic_regression.ipynb`
3. `module_knn.ipynb`
4. `module_Random Forest.ipynb`
5. `module_svm.ipynb`
6. `module_xgboost_classification.ipynb`

## Results

- Models are evaluated using Accuracy, F1-score, classification report, and confusion matrix.
- Visual outputs are saved in the `figures/` directory.

## License

This project is part of the GEO-INFO curriculum.
