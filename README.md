# 🧠 San Francisco Crime Classification 🔍

Welcome to the **San Francisco Crime Classification** project! This repository presents an end-to-end machine learning workflow to classify crime types using real-world data from San Francisco. The notebook explores data analysis, geospatial visualization, feature engineering, and model training.


## 📦 What's Inside?

* 📁 `project.ipynb`: The main notebook with all data loading, analysis, preprocessing, modeling, and visualization.



## 🚀 Quick Start

### 1️⃣ Install Python 3.11

This project requires **Python 3.11**. You can download it from [python.org](https://www.python.org/downloads/release/python-3110/).

### 2️⃣ Set Up Jupyter Notebook

If you're using **VS Code**, the Jupyter extension should automatically install a notebook interface.

Make sure to select the **Python 3.11 kernel** when running the notebook.



## 🛠️ Installation

Use the following commands to install the required packages. The project depends on **NumPy 1.26.4** for compatibility:

```bash
py -3.11 -m pip install numpy==1.26.4
py -3.11 -m pip install pandas matplotlib seaborn folium scikit-learn scikit-learn-extra
```



## 📊 Project Features

* ✅ **Exploratory Data Analysis (EDA)** with Pandas, Matplotlib, Seaborn
* 🗺️ **Geospatial Mapping** using Folium (Internet connection required)
* 🛠️ **Feature Engineering**: Time and location-based attributes
* 🔁 **Clustering**: KMeans and KMedoids
* 🌲 **Classification**: Random Forest for crime category prediction
* 🧪 **Model Evaluation**: Accuracy scores, classification reports



## 📌 Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/sf-crime-classification.git
   cd sf-crime-classification
   ```

2. Open the notebook:

   ```bash
   jupyter notebook project.ipynb
   ```

3. Run each cell sequentially. Ensure your internet connection is active for the **map visualizations** to work properly.



## 📜 License

This project is licensed under the MIT License.



## 🌐 Acknowledgments

San Francisco crime data sourced from [Kaggle](https://www.kaggle.com/c/sf-crime).
