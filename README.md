# House Price Data Cleaning & Scaling

## Project Overview
This project focuses on data cleaning and feature scaling for a housing dataset. The primary objective is to preprocess the `LotArea` feature using standardization techniques to improve the performance of machine learning models.

## Key Features
- **Data Cleaning:** Handling missing values, outliers, and inconsistencies in the dataset.
- **Feature Scaling:** Applying standardization to normalize numerical features.
- **Visualization:** KDE plots to compare data distribution before and after scaling.

## Project Structure
```
├── data
│   ├── cleaned_train.csv   # Cleaned dataset
├── notebooks
│   ├── House_price.ipynb   # Jupyter Notebook for preprocessing and visualization
├── README.md               # Project documentation
```

## Installation & Setup
1. Clone the repository:
   ```bash
   git clone <your-repository-link>
   cd House-Price-Analysis
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Run `House_price.ipynb` to preprocess the data and visualize results.

## Results
- The dataset has been standardized, ensuring improved model performance.
- KDE plots illustrate the distribution changes after scaling.

