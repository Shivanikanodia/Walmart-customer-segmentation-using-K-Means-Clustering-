# 🧠 E-commerce Customer Segmentation & Behavioral Analysis

This project performs customer segmentation and purchasing behavior analysis using e-commerce data. It focuses on uncovering insights that support targeted marketing, improved sales strategies, and personalized customer experiences.

---

## 🎯 Objective

- Segment customers based on Recency, Frequency, and Monetary (RFM) behavior
- Visualize customer clusters and their key characteristics
- Identify top-performing customer segments for business targeting
- Explore regional and categorical purchase trends

---

## 📁 Dataset

- **Format**: E-commerce transaction CSV
- **Columns**: Customer Name, Order Date, Region, Sales, Quantity, Profit, Segment, Category, Sub-Category, etc.
- **Assumption**: Based on simulated or anonymized transactional data

---

## 🧰 Tools & Libraries Used

| Category         | Tools/Libraries           |
|------------------|---------------------------|
| Data Handling    | `pandas`, `numpy`         |
| Visualization    | `matplotlib`, `seaborn`   |
| Clustering       | `scikit-learn`            |
| Statistical Eval | `statsmodels`             |

---

## 🔍 Key Analysis & Techniques

- RFM Segmentation using quantiles
- K-Means Clustering for customer grouping
- Distribution analysis of sales/profit across segments and categories
- Visualization of clusters and purchasing trends

---

## 📊 Insights Derived

- Identified loyal, high-value customers (top RFM group)
- Pinpointed low-engagement segments with potential for reactivation
- Found strong sales patterns tied to specific categories and regions
- Clear differentiation in customer value across segments

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/Shivanikanodia/Walmart_Customer_Behaviour_Analysis
   cd ecommerce-customer-segmentation

2. Create a virtual environment:
    python -m venv venv
    source venv/bin/activate  # Windows: venv\Scripts\activate

3. Install the dependencies:
   pip install -r requirements.txt

4. Launch the notebook:
   jupyter notebook Ecommerce_Customer_Segmentation.ipynb





