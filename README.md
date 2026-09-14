# CODEC-TECH-INTERNSHIP

# 🛒 Market Basket Analysis Using Apriori Algorithm

## 📌 Project Overview

This project performs **Market Basket Analysis** on grocery transaction data to identify relationships between products frequently purchased together.

The main objective is to discover useful product associations that can help businesses improve:

* Cross-selling strategies
* Product recommendations
* Promotional campaigns
* Product bundling
* Store layout and product placement

The project uses the **Apriori Algorithm** to generate frequent itemsets and association rules.

---

## 🎯 Project Goal

The goal of this project is to identify products that customers frequently purchase together and use these relationships to generate actionable business insights.

Market Basket Analysis helps businesses answer questions such as:

> If a customer purchases one product, which other products are they likely to purchase?

---

## 📂 Dataset

The dataset used in this project is:

`basket_analysis.csv`

The dataset contains **999 transactions** and multiple grocery products.

Each row represents a customer transaction, while each column represents a product.

The values are represented as:

* `True` → Product was purchased
* `False` → Product was not purchased

### Example Products

* Apple
* Bread
* Butter
* Cheese
* Corn
* Dill
* Eggs
* Ice cream
* Kidney Beans
* Milk
* Nutmeg
* Onion
* Sugar
* Unicorn
* Yogurt
* Chocolate

---

## 🛠️ Technologies Used

The project was developed using Python and Jupyter Notebook.

### Libraries Used

* Pandas
* NumPy
* Matplotlib
* Seaborn
* MLxtend

---

## ⚙️ Installation
 install the required libraries.

```bash
pip install pandas numpy matplotlib seaborn mlxtend
```

---

## 📊 Project Workflow

The project follows the following steps:

### 1. Data Loading

The grocery transaction dataset is loaded using Pandas.

### 2. Data Preprocessing

The dataset is cleaned by:

* Removing unnecessary index columns
* Checking for missing values
* Converting transaction data into Boolean format

### 3. Exploratory Data Analysis

Product purchase frequencies are calculated to identify the most commonly purchased products.

### 4. Frequent Itemset Generation

The **Apriori Algorithm** is used to identify combinations of products that frequently occur together.

### 5. Association Rule Generation

Association rules are generated using important metrics such as:

* Support
* Confidence
* Lift

### 6. Visualization

The project includes visualizations for:

* Product purchase frequency
* Top frequent itemsets
* Support vs Confidence
* Top association rules by Lift

### 7. Business Insights

The discovered association rules are used to generate recommendations for improving business sales and cross-selling opportunities.

---

## 🧠 Important Metrics

### Support

Support measures how frequently an itemset appears in all transactions.

**Formula:**

```text
Support(A → B) = Transactions containing A and B / Total Transactions
```

---

### Confidence

Confidence measures how often product B is purchased when product A is purchased.

**Formula:**

```text
Confidence(A → B) = Support(A and B) / Support(A)
```

---

### Lift

Lift measures the strength of the relationship between two products.

**Formula:**

```text
Lift(A → B) = Confidence(A → B) / Support(B)
```

### Lift Interpretation

* **Lift > 1** → Positive association
* **Lift = 1** → No significant association
* **Lift < 1** → Negative association

---

## 📈 Visualizations

The project generates the following visualizations:

### Product Purchase Frequency

Shows the products purchased most frequently by customers.

### Top Frequent Itemsets

Shows combinations of products that occur frequently in transactions.

### Support vs Confidence

Helps visualize the relationship between the frequency and reliability of association rules.

### Top Association Rules by Lift

Highlights the strongest product relationships discovered during the analysis.

---

## 💡 Business Insights

The results of Market Basket Analysis can help businesses:

### 🛍️ Improve Cross-Selling

Recommend related products when customers purchase a particular product.

### 🎁 Create Product Bundles

Combine frequently associated products into promotional packages.

### 📢 Improve Marketing Campaigns

Create targeted promotions based on customer purchasing behavior.

### 🏪 Optimize Store Layout

Place strongly associated products closer together to encourage additional purchases.

### 💻 Improve E-Commerce Recommendations

Recommend products based on association rules during online shopping.

---

## 🚀 Future Improvements

The project can be improved further by:

* Using the FP-Growth algorithm for larger datasets
* Building a product recommendation system
* Creating an interactive dashboard using Tableau or Power BI
* Applying Market Basket Analysis to real-time e-commerce data
* Comparing Apriori and FP-Growth performance

---

## 📁 Project Structure

```text
Market-Basket-Analysis/
│
├── basket_analysis.csv
├── Market_Basket_Analysis.ipynb
├── README.md

```

---

## 📦 Requirements



```text
pandas
numpy
matplotlib
seaborn
mlxtend
```

---

## 👨‍💻 Author

**YASH KHAIRE**

---

## 📄 Conclusion

This project successfully applies the **Apriori Algorithm** to grocery transaction data to discover frequent itemsets and association rules.

The results provide useful insights into customer purchasing patterns and can help businesses improve **cross-selling, product recommendations, promotional strategies, and overall customer experience**.
