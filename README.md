#  Telco Customer Churn Analysis

### Machine Learning Portfolio Project — Data Analyst

> Built to demonstrate end-to-end ML skills applied to a real-world business problem:
> predicting which customers are likely to cancel their subscription.

---

##  Objective

Analyse customer behaviour data from a telecommunications company and build a binary
classifier to predict churn — identifying customers at risk of leaving before they do.
The project covers the full pipeline from raw data exploration through to a trained and
saved deep learning model.

---

## 📂 Project Structure
py-churn-analysis/
├── Telco_customer_churn.xlsx   ← Dataset (included in the repository)
├── churn_analaysis.ipynb       ← Main analysis and modelling notebook
├── good model.h5               ← Saved trained model (HDF5 format)
├── good model.keras            ← Saved trained model (Keras native format)
├── requirements.txt            ← Full list of dependencies
└── .gitignore

---

##  Dataset

**Source:** IBM Sample Dataset — Telco Customer Churn

The dataset is included directly in this repository as `Telco_customer_churn.xlsx`.
No manual download is required.

It contains information on ~7,000 customers including demographic details,
account information, subscribed services, and whether the customer churned.

- **Target variable:** `Churn` (Yes / No)
- **Features:** tenure, contract type, monthly charges, payment method, internet
  service, and more

---

## 🧠 ML Pipeline

| Step | Detail |
|---|---|
| **EDA** | Churn rate analysis, feature distributions, correlation exploration |
| **Preprocessing** | Encoding categorical variables, scaling numerical features, handling missing values |
| **Modelling** | Deep learning classifier built with TensorFlow / Keras |
| **Evaluation** | Accuracy, Precision, Recall, F1-score, confusion matrix |

---

##  How to Run This Project

### Prerequisites

- **Python 3.8+** — [python.org](https://www.python.org/downloads/)
- **pip** — comes bundled with Python
- **Jupyter Notebook or JupyterLab** — to open and run the notebook

---

### 1. Clone the Repository
```bash
git clone https://github.com/francesco-mt/py-churn-analysis.git
cd py-churn-analysis
```

---

### 2. Create and Activate a Virtual Environment 
```bash
# Create the virtual environment
python -m venv .venv

# Activate it — Windows
.venv\Scripts\activate

# Activate it — macOS/Linux
source .venv/bin/activate
```

---

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```

---

### 4. Launch the Notebook
```bash
jupyter notebook churn_analaysis.ipynb
```

Once open, run all cells 

The notebook will:
- Load and explore the dataset from `Telco_customer_churn.xlsx`
- Perform exploratory data analysis with visualisations
- Preprocess the data and engineer features
- Build and train a deep learning model using TensorFlow / Keras
- Evaluate the model and display performance metrics

---

## 🛡️ License

This project is licensed under the [MIT License](LICENSE).
