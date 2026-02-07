## UN Humanitarian Anomaly Detection  
**CMU Data Science Club Datathon 2026**

### Project Summary
This project develops an **interpretable, end-to-end anomaly detection framework** to support **United Nations humanitarian decision-making**. Using unsupervised learning, the model flags **unusual or high-risk observations** that may indicate inefficiencies, under-resourced crises, or mismatches between humanitarian need and resource allocation. The approach emphasizes **transparency, interpretability, and real-world usability** for non-technical stakeholders.

---

### Problem Context
Humanitarian datasets are often high-dimensional, noisy, and largely **unlabeled**, making supervised approaches impractical. This project addresses these constraints by identifying statistical outliers that warrant further investigation, enabling data-driven prioritization without relying on ground-truth labels.

---

### Methodology
The analysis follows a standard, reproducible data science pipeline:
- Data loading, inspection, and preprocessing (missing values, encoding, scaling)
- Exploratory data analysis to understand feature distributions and potential outliers
- Application of an **Isolation Forest** model for unsupervised anomaly detection
- Interpretation of anomaly scores and flagged observations in humanitarian context

---

### Model Choice
**Isolation Forest** was selected for its effectiveness in high-dimensional settings, ability to operate without labeled data, computational efficiency, and intuitive interpretability. Anomalies are identified as observations that require fewer splits to isolate in randomly constructed trees.

---

### Results
The model produces:
- A continuous **anomaly score** for each observation  
- A **binary anomaly flag** highlighting high-risk cases  

Flagged observations are analyzed to surface potential inefficiencies, underserved populations, or allocation mismatches, serving as **decision-support signals rather than black-box predictions**.

---

### Humanitarian Impact
This framework demonstrates how unsupervised learning can improve transparency in humanitarian data, highlight overlooked cases, and support **evidence-based resource allocation**. The methodology is intentionally lightweight and interpretable, making it suitable for real-world deployment in low-resource or field settings.

---

### Tools & Technologies
Python, NumPy, Pandas, Matplotlib, Seaborn, Scikit-learn (Isolation Forest)


