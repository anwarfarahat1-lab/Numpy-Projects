# NumPy Weekly Sales Analysis Project

## 📌 Project Description

This project performs a complete data analysis of a store’s **weekly sales** using **NumPy only**. The goal is to analyze product performance, calculate revenues and profits, evaluate weekly trends, and detect low-stock items — all through efficient vectorized operations.

---

## 🛠 Requirements

### **Libraries**

* `numpy` (only)

### **Concepts Used**

* Array creation & manipulation
* Vectorized arithmetic operations
* Axis-based aggregation (`sum`, `mean`, `max`, ...)
* Boolean masking
* Broadcasting
* Basic numerical analysis

---

## 🎯 Project Objectives

1. **Generate weekly data** for sales, prices, and costs using NumPy.
2. **Calculate total sales, revenue, and profit per product.**
3. **Identify the most sold** and **most profitable product.**
4. Compute:

   * Weekly revenue
   * Average weekly profit
   * Growth rate across weeks
5. **Detect products with low remaining stock** using Boolean masking.
6. **Summarize key KPIs** for final insights.

---

## 📂 Project Structure (Suggested)

```
project/
├── data_generation.py
├── analysis.py
├── kpi_summary.py
└── README.md   <-- this file
```

---

## 🚀 How to Run

1. Install NumPy:

```bash
pip install numpy
```

2. Run data generation (if exists):

```bash
python data_generation.py
```

3. Run main analysis:

```bash
python analysis.py
```

---

## 📈 Outputs Expected

* Product-wise revenue & profit tables
* Weekly revenue trends
* Growth rate results
* Low-stock product warnings
* KPI summary printed or saved

---

## 📝 Notes

* Avoid using pandas or other libraries — **NumPy only**.
* Keep operations vectorized; avoid loops where possible.

---

## 📧 Contact

For any questions, feel free to reach out!
