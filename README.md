```markdown
# Iris KNN Classification – CS303 Assignment

## 📌 Overview
This repository contains my **CS303 – Machine Learning** assignment where I implemented **K-Nearest Neighbors (KNN)** to classify the famous **Iris dataset**.  
The project demonstrates:
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature scaling
- Model training and evaluation
- Visualization of results

The project is implemented in both **Jupyter Notebook** (`iris_knn.ipynb`) for detailed explanation and an optional **Python script** (`iris_knn.py`) for direct execution.

---

## 📂 Project Structure
```

iris-knn-assignment/
├── code/
│   ├── iris\_knn.ipynb        # Jupyter notebook (primary deliverable)
│   └── iris\_knn.py           # Optional script to run analysis & save outputs
├── outputs/
│   ├── pairplot.png
│   ├── heatmap.png
│   ├── boxplots.png
│   └── results\_table.csv
├── requirements.txt
├── README.md
├── THEORY.md
├── .gitignore
└── LICENSE

````

---

## 🛠️ Installation & Setup

### 1️⃣ Clone the repository
```powershell
git clone https://github.com/<your-username>/iris-knn-assignment.git
cd iris-knn-assignment
````

### 2️⃣ Create & activate a virtual environment

```powershell
python -m venv venv
venv\Scripts\activate
```

### 3️⃣ Install dependencies

```powershell
pip install -r requirements.txt
```

---

## 🚀 Usage

### Option 1 – Run the Jupyter Notebook (Recommended)

```powershell
cd code
jupyter notebook iris_knn.ipynb
```

### Option 2 – Run the Python Script

```powershell
cd code
python iris_knn.py
```

Outputs will be saved in the `outputs/` folder.

---

## 📊 Features

* **Data Exploration**: Pairplots, heatmaps, and boxplots to understand dataset characteristics.
* **Data Preprocessing**: Feature scaling and train-test split.
* **Model Implementation**: KNN from `sklearn`.
* **Performance Evaluation**: Accuracy score, classification report, confusion matrix.
* **Results Export**: Saves results and figures for reproducibility.

---

## 📈 Sample Visualizations

| Pairplot                          | Heatmap                         | Boxplot                          |
| --------------------------------- | ------------------------------- | -------------------------------- |
| ![Pairplot](outputs/pairplot.png) | ![Heatmap](outputs/heatmap.png) | ![Boxplot](outputs/boxplots.png) |

---

## 📜 Theory

Detailed explanation of **KNN algorithm** and dataset characteristics can be found in **[THEORY.md](THEORY.md)**.

---

## 🧠 Skills Demonstrated

* **Python programming**
* **Data analysis & visualization**
* **Machine learning model implementation**
* **Working with Jupyter Notebooks**
* **Version control using Git & GitHub**
* **Reproducible research & documentation**

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgments

* [Scikit-learn Documentation](https://scikit-learn.org/stable/)
* [Iris Dataset – UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/iris)

```
