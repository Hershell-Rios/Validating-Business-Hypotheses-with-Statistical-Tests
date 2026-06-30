# 🧪 Landing Experiment: Validating Business Hypotheses with Statistical Tests

## 📊 Project Overview

This project analyzes an **A/B experiment** conducted on a landing page to evaluate whether a new page design (Version B) outperformed the original version (Version A).

Using statistical hypothesis testing and exploratory data analysis, the project compares conversion rates, customer spending, and user behavior across different segments to determine whether observed differences are statistically significant and actionable for business decision-making.

The analysis demonstrates how data-driven experimentation can reduce uncertainty when evaluating product and marketing changes.

---

# 🎯 Business Context

Landing pages are one of the most important touchpoints in the customer acquisition funnel. Even small improvements in conversion rate or customer value can have a significant business impact.

The business needed to determine whether launching a new landing page would:

- Increase conversion rates
- Improve customer spending
- Perform consistently across different customer segments
- Justify replacing the existing version

Rather than relying on intuition, the decision should be supported by statistical evidence.

---

# 🎯 Objective

The objective of this project was to validate business hypotheses by comparing two landing page versions using statistical analysis.

Specifically, the analysis aimed to:

- Compare conversion rates between Version A and Version B
- Compare average customer spending
- Analyze conversion behavior by traffic source
- Evaluate customer behavior across user segments
- Apply hypothesis testing to support business decisions

---

# 📂 Dataset Overview

The analysis uses a customer-level A/B testing dataset containing user interactions with two landing page versions.

### Dataset Information

| Variable | Description |
|-----------|-------------|
| user_id | Unique customer identifier |
| date | Experiment date |
| landing | Landing page version (A or B) |
| region | Customer region |
| device | Device used |
| traffic_source | Acquisition channel |
| user_type | New or returning customer |
| converted | Conversion indicator |
| spend | Customer spending |

---

# ⚙️ Process & Methodology

## 1️⃣ Data Validation

- Loaded and explored the dataset
- Verified data integrity
- Checked missing values
- Reviewed variable distributions
- Validated experiment consistency

---

## 2️⃣ Exploratory Data Analysis (EDA)

Performed exploratory analysis to understand customer behavior across both landing page versions.

The analysis included:

- Conversion distribution
- Spending distribution
- Customer segmentation
- Traffic source comparison
- Regional analysis

---

## 3️⃣ Statistical Hypothesis Testing

Applied statistical tests to determine whether observed differences were statistically significant.

Tests included:

- Independent Samples t-test
- Two-Proportion Z-Test
- Chi-Square Test of Independence

These tests were used to validate business hypotheses rather than relying solely on descriptive statistics.

---

## 4️⃣ Customer Segmentation

Compared customer behavior across multiple dimensions:

- Landing page version
- Traffic source
- User type
- Geographic region

This segmentation provided additional business context beyond overall experiment performance.

---

# 📈 Key Insights

- 📌 Conversion performance differed between landing page versions.
- 📌 Customer spending showed measurable differences across experiment groups.
- 📌 Traffic source influenced conversion behavior.
- 📌 User segments responded differently to each landing page.
- 📌 Statistical testing distinguished meaningful improvements from random variation.

---

# 💼 Business Impact

**Validated business hypotheses using statistical evidence, enabling more confident decisions regarding landing page optimization, marketing strategy, and customer acquisition initiatives.**

Rather than relying on intuition, the project demonstrates how experimentation can reduce decision-making risk through data-driven validation.

---

# 🛠️ Tools Used

- Python
- Pandas
- NumPy
- SciPy
- Statsmodels
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# 📂 Project Structure

```text
landing-experiment-analysis/
│
├── data/
├── notebooks/
├── images/
├── README.md
└── requirements.txt
```

---

# 📸 Dashboard & Visualizations

## Conversion Rate Comparison


<img width="972" height="663" alt="Tasa de conversiones por tipo de tráfico" src="https://github.com/user-attachments/assets/617b7a32-5f9d-455a-8734-f74e509a2df4" />


<img width="1007" height="695" alt="Tasa de conversiones por tipo de usuario" src="https://github.com/user-attachments/assets/938af0f9-3962-400e-8c22-ab81e19581ae" />



---

## Customer Spending Distribution


<img width="997" height="527" alt="Conversiones por tipo de usuario" src="https://github.com/user-attachments/assets/6f78776c-f657-425d-a65c-73dad6118504" />

---

## Traffic Source Analysis


<img width="1102" height="592" alt="Conversiones por tipo de tráfico" src="https://github.com/user-attachments/assets/313c29a8-05c9-4e73-a7e6-168e156825a4" />

---


# 📚 Statistical Methods

The project applies several statistical techniques commonly used in business experimentation:

- Independent Samples t-test
- Two-Proportion Z-Test
- Chi-Square Test
- Exploratory Data Analysis (EDA)
- Customer Segmentation
- Business Experiment Analysis

---

# ✅ Conclusions

The analysis demonstrates the value of statistical experimentation in product and marketing decisions.

By combining exploratory analysis with hypothesis testing, the project provides evidence-based recommendations regarding landing page performance while highlighting the importance of validating business assumptions before implementation.

---

# 🚀 Future Improvements

Potential extensions include:

- Power analysis for sample size estimation
- Bayesian A/B Testing
- Logistic regression modeling
- Uplift modeling
- Interactive Power BI dashboard
- Automated experiment reporting

---

# 📫 Contact

**Hershell Rios**

**Data Analyst | Business + Data Hybrid | Gaming & Japan Enthusiast 🎮🇯🇵**

- 💼 LinkedIn: https://www.linkedin.com/in/hershellrh/
- 📧 Email: hershell.rh@gmail.com

---

⭐ This project is part of my Data Analytics portfolio, showcasing statistical analysis, business experimentation, and data-driven decision-making using Python.
