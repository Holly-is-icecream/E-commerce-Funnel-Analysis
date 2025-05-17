# 🛒 E-commerce Funnel Analysis Using Kaggle User Behavior Dataset

## 📌 Overview
This project analyzes user behavior data from a real-world e-commerce platform (Kaggle dataset) to identify drop-off points in the purchase funnel. The goal is to help businesses understand where users abandon the buying process and suggest improvements for conversion optimization.

---

## 🗂 Dataset Source

- **Kaggle Dataset**: [E-Commerce Behavior Data](https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store)
- **Size**: ~75 million events
- **Fields used**:
  - `event_time`
  - `event_type` (`view`, `cart`, `purchase`)
  - `product_id`
  - `category_code`
  - `price`
  - `user_id`
  - `user_session`

---

## 🎯 Objectives

- Clean and prepare large-scale user behavior data
- Define and compute the e-commerce funnel: `view → cart → purchase`
- Calculate conversion rates at each step
- Visualize user drop-off using a funnel chart (Tableau or Python)
- Provide business insights and recommendations

---

## 📊 Funnel Structure

| Funnel Step | Description |
|-------------|-------------|
| `view`      | User viewed a product |
| `cart`      | User added product to cart |
| `purchase`  | User completed the purchase |

---

## 🛠 Tools Used

- Python: `pandas`, `numpy`, `matplotlib`, `seaborn`
- SQL (BigQuery or SQLite): Querying grouped session-level funnels
- Tableau: Funnel visualization
- Jupyter Notebook: Analysis and insights
- GitHub: Version control and documentation

---

## 📈 Key Metrics

- View-to-Cart Conversion Rate
- Cart-to-Purchase Conversion Rate
- Session-based funnel completion rate
- Most viewed and most purchased categories

---


