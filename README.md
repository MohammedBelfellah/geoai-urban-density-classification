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

This project aims to classify urban zones by density using AI and geospatial data. The workflow includes:

- Data loading and inspection
- Data cleaning, harmonization, and normalization
- Outlier detection and handling
- Encoding target variable
- Train/Test split
- Model training (Random Forest, SVM, XGBoost)
- Performance evaluation and visualization

## Project Structure

- `GeoAI_UrbanDensity_Preprocessing_Normalization.ipynb` – Data preparation and normalization
- `RandomForest_UrbanDensity_Classification.ipynb` – Random Forest model
- `SVM_UrbanDensity_Classification.ipynb` – SVM model
- `XGBoost_UrbanDensity_Classification.ipynb` – XGBoost model
- `Module_Assignments_GeoAI.md` – Module assignments and member responsibilities
- `data/` – Project data files (incl. `geo_urban_density_data.csv` and preprocessed version)
- `figures/` – Visualizations and model results

## Requirements

- Python 3.8+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- rasterio
- geopandas
- folium
- jupyter
- xgboost

## Getting Started

1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Open the notebooks in Jupyter and run the cells

## Usage

- Start with `GeoAI_UrbanDensity_Preprocessing_Normalization.ipynb` to prepare the data
- Use the model notebooks to train and evaluate classifiers
- Visualizations and results are saved in `figures/`

## Results

- Models compare accuracy, F1-score, and confusion matrices
- Feature importance and class distributions are visualized
- Preprocessed dataset is saved as `data/geo_urban_density_data_preprocessed.csv`

## Notes for the Professor

- Each notebook is named to reflect its content and purpose
- The workflow follows best practices for data science and geospatial AI
- All steps are commented and visualized for clarity
- Figures and reports are saved for review

## License

This project is part of the GEO-INFO curriculum.
