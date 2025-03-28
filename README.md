# ⚡ Urban Energy Clustering & Prediction

This project is a completed university assignment focused on analyzing and modeling energy consumption in urban buildings. It uses machine learning techniques to cluster buildings based on similar features and predict energy usage per cluster.

---

## 📌 Description

The project addresses two key goals using the [Urban Building Energy Stock Datasets](https://data.mendeley.com/datasets/m6vv9k9gcd/1):

1. **Clustering (Unsupervised Learning)**  
   Applying the K-Means algorithm to group buildings into an optimal number of clusters based on shared attributes.

2. **Prediction (Supervised Learning)**  
   Using Support Vector Machines (SVM) to predict energy consumption for each cluster, with additional evaluation of prediction accuracy.

---

## 📁 Project Structure

```
urban-energy-clustering-prediction/
│
├── urban_energy_ai_project.ipynb      # Main notebook with clustering & prediction
├── resources/
│   └── urban_building_stock_datasets.csv (NOT included in repo due to size)
└── README.md
```

---

## 🧠 Key Concepts

- K-Means Clustering
- Elbow Method (optimal K)
- Support Vector Regression (SVR)
- Data Normalization & Scaling
- Model Evaluation (MAE, RMSE)
- Visualization with Seaborn & Matplotlib

---

## 📊 Dataset

- Name: **Urban Building Energy Stock Datasets**
- Source: [Mendeley Data](https://data.mendeley.com/datasets/m6vv9k9gcd/1)
- Size: ~200MB
- Note: The dataset is **not included in the repository** due to its size.  
  To run the notebook, download the dataset manually and place it in the `resources/` folder.

---

## ▶️ How to Run

1. Download the dataset from [here](https://data.mendeley.com/datasets/m6vv9k9gcd/1)
2. Place it in a folder named `resources/`
3. Run the `urban_energy_ai_project.ipynb` notebook in Jupyter or VS Code with the Python extension.

---

## 📌 Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

You can install dependencies using pip.

---

## 📎 Author

Created by Maksim Kos  
University project – Introduction to Artificial Intelligence

---

## 🎉 Enjoy exploring data & modeling energy-efficient cities! 🌍💡
