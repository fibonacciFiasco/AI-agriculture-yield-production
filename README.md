# AI in Agriculture: Rice Yield Prediction

## 🌱 Motivation & Goal

Agriculture is fundamental to global food security. Accurately estimating crop yields helps farmers, policymakers, and researchers make decisions about resource allocation, crop planning, and food distribution.  
This project aims to predict **rice crop yield (kg/ha)** using machine learning models trained on historical agricultural data. By doing so, it demonstrates how data-driven approaches can enhance crop planning and agricultural output.

## 📂 Project Overview

This repository contains:
- Data preprocessing and outlier removal techniques  
- Exploratory Data Analysis (EDA)  
- Model training, evaluation & deployment  
- Visualizations of results  
- Metrics and statistical interpretation

## 🧠 Key Concepts & Metrics

Here are some concepts used in this project to help you follow along:

| Concept | Explanation |
|---|---|
| **IQR (Interquartile Range)** | Used to detect and remove outliers in the dataset by filtering values outside the typical range |
| **R² (Coefficient of Determination)** | Indicates proportion of variance in yield that is explained by the model |
| **MAE (Mean Absolute Error)** | Average absolute difference between predicted and true yields |
| **RMSE (Root Mean Squared Error)** | Penalizes larger errors more strongly; gives insight into prediction variance |

## 📁 Folder & File Structure

├── datasets/

│ ├── Crops_data.csv

│ ├── rice_data.csv

│ └── rice_data_outlier_removed.csv


├── notebooks/

│ ├── 01_Preprocessing.ipynb

│ ├── 02_EDA.ipynb

│ ├── 03_Modelling.ipynb

│ └── 04_Evaluation_Deployment.ipynb


├── models/


├── plots/


├── README.md

├── CONTRIBUTING.md

└── requirements.txt



## How to Run

1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Run notebooks in sequence: `01` to `04`
4. Don't forget to star the repo 



## Author

- **Name**: [Nupur Madaan]
- **Internship Project**: AI in Agriculture — Yield Prediction



## License

This project is licensed under the [MIT License](LICENSE.md).




