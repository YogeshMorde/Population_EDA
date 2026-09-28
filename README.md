# Population_EDA
# 🌍 Indian Population EDA

Exploratory Data Analysis of Indian states and Union Territories (35 regions) to understand population size, distribution, density and literacy.

**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Plotly

---

## 📌 Key Numbers

| Metric | Value |
|---|---|
| Mean population | 34.59 M |
| Median population | 16.79 M |
| Skewness | 1.86 (highly right-skewed) |
| Std. deviation | 44.46 M (higher than the mean) |
| Top 10 states' share | 68.32% of total population |
| Population vs Literacy correlation | -0.475 |

---

## ❓ Business Questions & Answers

**1. Which state has the largest population?**
Uttar Pradesh: 199,812,341 people (16.50% of total).

**2. Which state has the smallest population?**
Lakshadweep: 64,473 people (0.01% of total).

**3. Is the population normally distributed?**
No. It is highly right-skewed (skewness = 1.86) because a few large states pull the tail to the right.

**4. Which states are outliers?**
- Population: Uttar Pradesh and Maharashtra
- Density: Delhi (11,297 people/km²) and Chandigarh (9,252 people/km²)

**5. What is the average population of a state?**
Mean is 34.59 M, but the median (16.79 M) represents a typical state better because the mean is inflated by outliers.

**6. Which region has the highest population concentration?**
Northern and western India, led by Uttar Pradesh and Maharashtra.

**7. Which region has the lowest population concentration?**
Island territories such as Lakshadweep and Andaman & Nicobar Islands.

**8. Is population density related to population size?**
Generally no. Small Union Territories have very high density despite small populations because of limited land area.

**9. What do you recommend to policymakers?**
- Focus budgets and infrastructure on the Top 10 states (68%+ of population).
- Strengthen education in high-population states, since population and literacy show a negative correlation (-0.475).

**10. What future trends can be expected?**
- Urbanisation will keep increasing density in city centres.
- Most states are likely to see stabilising growth. Nagaland is the only region with negative decadal growth (-0.5%).

---

## ✅ Conclusion

Indian population is highly unequal across states. A few large states dominate, so the **median** is a better measure than the mean. Outliers like UP, Maharashtra, Delhi and Chandigarh need special attention in planning.

---
