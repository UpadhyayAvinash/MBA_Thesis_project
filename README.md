# Impact of Privacy Regulations on Digital Ad Budgeting 🔒

This repository accompanies a master's thesis titled:
**"Impact of Privacy Regulations on Digital Ad Budgeting: A Comparative Study Using Aggregated Channel Data."**

The project investigates how digital advertising budget decisions can remain **data-driven** and **ROI-focused** despite the growing constraints imposed by privacy regulations, such as **GDPR** and **CCPA**. It validates the use of aggregated, privacy-safe data to power predictive models, demonstrating that actionable insights for budget allocation are still achievable in a privacy-first environment.

---

## 🎯 Research Objectives

This project was guided by the following core objectives:

1.  **Analyze** how privacy regulations (e.g., GDPR, CCPA) have structurally changed the landscape of digital ad budgeting.
2.  **Evaluate** whether Return on Investment (ROI) can still be effectively measured using only aggregated, non-personal data.
3.  **Develop** a **Privacy-Compliant ROI Optimization (PCROIO) framework** to serve as a practical guide for future ad budgeting and strategic decision-making.

---

## ⚙️ Methodology

### Dataset
* **Primary Data:** Google Analytics Customer Revenue Prediction (Kaggle, anonymized and aggregated).

### Data Preparation
Raw data was aggregated to a **channel-week level**, cleaned, and nested JSON structures were expanded to create a privacy-safe overview suitable for modeling.

### Analysis & Modeling
The research employed a mixed-methods approach:

| Analysis | Purpose | Key Tool |
| :--- | :--- | :--- |
| **Linear Regression** | ROI prediction from spend and other variables. | Scikit-learn |
| **K-Means Clustering** | Segmenting marketing channels into distinct performance tiers. | Scikit-learn |
| **Visual Analytics** | Identifying trends and comparing channel performance (e.g., boxplots). | Matplotlib |

---

## 📊 Key Results

The findings confirm that aggregated data delivers **strategic** insights for budget optimization:

* **Regression Analysis:** The model yielded a low $R^2$ of **0.0038**, suggesting that ROI is a complex outcome driven by multiple, contextual market and creative factors, not simply monetary spend.
* **Clustering Insights:** K-Means clustering successfully segmented channels into **three distinct performance tiers**, providing a clear basis for strategic allocation.
* **Cost Efficiency:** Visual analysis highlighted that **earned media** (organic and referral traffic) consistently remains the **most cost-efficient** channel segment.
* **Conclusion:** Aggregated data is sufficient to deliver actionable, strategic budget insights without compromising user privacy.

---

## 🧠 Tools & Technologies

| Category | Tools Used |
| :--- | :--- |
| **Data Processing** | Python (`pandas`, `numpy`, `json`) |
| **Machine Learning** | `Scikit-learn` |
| **Visualisation** | `Matplotlib` |
| **Environment & Control** | Visual Studio Code, Jupyter Notebook, Git & GitHub |

---

## 🔐 Ethical Compliance

* **Data Integrity:** **No personally identifiable information (PII)** is included.
* **Sourcing:** All datasets are publicly available or synthetically generated.
* **Standards:** The project complies with Liverpool John Moores University’s (LJMU) ethical research guidelines.
