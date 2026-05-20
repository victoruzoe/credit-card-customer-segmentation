# Dataset

This folder is reserved for the dataset used in this project.

The raw dataset is **not included in this repository** because it was sourced from Kaggle. To run the notebook, download the dataset manually from Kaggle and place it inside this folder.

---

## Dataset Name

**Credit Card Dataset for Clustering**

---

## Dataset Source

The dataset can be downloaded from Kaggle:

```text
https://www.kaggle.com/datasets/arjunbhasin2013/ccdata?resource=download
```

---

## Dataset Description

This dataset contains credit card usage behaviour for active credit card customers over a six-month period.

It includes customer financial and behavioural features such as:

- Balance
- Purchases
- One-off purchases
- Instalment purchases
- Cash advances
- Credit limit
- Payments
- Minimum payments
- Purchase frequency
- Cash advance frequency
- Tenure

The dataset is used in this project for customer segmentation using unsupervised machine learning techniques.

---

## How to Use the Dataset

After downloading the dataset from Kaggle, place the CSV file inside this `data` folder.

Rename the downloaded CSV file to:

```text
Credit_card_dataset.csv
```

The folder should look like this:

```text
data
│
├── README.md
└── Credit_card_dataset.csv
```

---

## Expected File Path

The notebook expects the dataset to be located at:

```python
../data/Credit_card_dataset.csv
```

This means the project folder should follow this structure:

```text
credit-card-customer-segmentation
│
├── data
│   ├── README.md
│   └── Credit_card_dataset.csv
│
├── notebooks
│   └── credit_card_customer_segmentation.ipynb
│
├── images
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Important Note

The CSV file is excluded from this GitHub repository.

Before running the notebook, make sure you have downloaded the dataset from Kaggle and saved it inside this folder using the exact file name:

```text
Credit_card_dataset.csv
```

If the file name is different, the notebook may return a file path error.

---

## Project Usage

This dataset is used for:

- Exploratory data analysis
- Missing value handling
- Feature scaling
- Hierarchical clustering
- K-Means clustering
- PCA cluster visualisation
- Customer segmentation analysis