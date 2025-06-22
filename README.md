# ⚡ Spark-Classification

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![Apache Spark](https://img.shields.io/badge/Apache%20Spark-3.0%2B-orange.svg)](https://spark.apache.org/)

**Spark-Classification** is a scalable and distributed machine learning pipeline built on **Apache Spark**. It is designed for high-performance classification tasks using large datasets and includes data preprocessing, feature engineering, and model training using Spark MLlib.
---

DataSet : [https://www.kaggle.com/datasets/ronitf/heart-disease-uci](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data)

---

## 📁 Project Structure

```
Spark-Classification/
│
├── Source_Code/                 # All source code
│   ├── main_classification.py   # Main driver script
│   ├── spark_utils.py           # Spark setup and utilities
│   └── models/                  # Model-related scripts
│       └── logistic_model.py
│
├── Dataset/                     # Sample datasets or links
│   └── sample_data.csv
│
├── Classification_Report.pdf    # Technical report
├── Spark_Pipeline_Design.png    # Pipeline visualization
├── WhatToDo.pdf                 # Task roadmap
└── README.md                    # Project documentation
```

---

## ⚙️ Requirements & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/M-Amin-Kiani/Spark-Classification.git
cd Spark-Classification
```

### 2. Install Apache Spark

Make sure [Apache Spark](https://spark.apache.org/downloads.html) is installed and properly configured.

```bash
# Optional: Install using pip (for PySpark)
pip install pyspark
```

---

## 🚀 How to Run

```bash
spark-submit Source_Code/main_classification.py --input Dataset/sample_data.csv --model logistic
```

Arguments:

| Argument       | Description                             | Default       |
|----------------|-----------------------------------------|---------------|
| `--input`      | Path to input CSV data                  | `sample_data.csv` |
| `--model`      | Model type (`logistic`, `decision_tree`) | `logistic`     |

---

## 🧠 Models Available

- Logistic Regression (via Spark MLlib)
- Decision Tree Classifier *(planned)*

---

## 🔧 Features

- Distributed classification pipeline with Apache Spark
- Easy model switching via CLI arguments
- Preprocessing, training, and evaluation all in one
- Designed for scalability with large datasets
- Modular codebase

---

## 📈 Sample Output

```
Accuracy: 87.56%
Precision: 85.90%
Recall: 88.34%
```

📊 ![Pipeline](Spark_Pipeline_Design.png)

---

## 🙌 Contribution

Feel free to fork the repository and submit pull requests.  
You can also open issues to report bugs or suggest improvements.

---

## 📃 License

This project is licensed under the UI License.  
See the [LICENSE](LICENSE) file for details.

---

## 📬 Contact

**Author:** M. Amin Kiani  
**Email:** amin.kiani82@gmail.com 
**LinkedIn:** [linkedin.com/in/amin-kiani](https://linkedin.com/in/amin-kiani)

---

> If you find this project helpful, please consider giving it a ⭐ on GitHub!
