# Multi-Source Operations & Performance Dashboard

An interactive internal tool built in **Retool** designed to understand customer behavior, identify churn risk, and provide recommendations for targeting at risk properties. This project demonstrates high-level proficiency in data transformation, state management, and custom data visualizations.

<img width="942" height="361" alt="db" src="https://github.com/user-attachments/assets/3bfa295a-8d7c-4038-9863-4b5624725286" />

---

## 🚀 Key Features

- **Dynamic Data Ingestion:** Users can upload raw CSV files 
- **Interactive Risk Matrix:** A scatter plot that categorizes clients into "High Risk" vs. "Stable" based on conversion and adoption thresholds.
- **Custom Intelligence Tooltips:** Multi-line HTML hover states providing granular data insights (Property Name, Adoption %, Conversion %) without UI clutter.
- **Context-Aware UI:** The dashboard titles, legend names, and color schemes update dynamically based on the selected risk profile.



---

## 🛠️ Technical Stack

- **Platform:** Retool
- **Core Logic:** JavaScript, SQL
---

## 📖 How to Use the Dashboard

1. **Upload Data:** Use the File Input to upload a CSV containing client engagement metrics.
2. **Select Filter Mode:** Use the "Churn Risk" dropdown to toggle between:
   - *Low Adoption Risk* (<30%)
   - *Low Conversion Risk* (<20%)
   - *High Risk (Both Metrics Low)* - (Implemented with `AND` logic)
3. **Inspect Outliers:** Hover over any red dot on the scatter plot to view detailed property data for deeper investigation.
4. **View Takeaways:** Recommendations provided regarding next actions to minimize risk of churn along with insights about proportion of impacted properties.
5. **Clear Filters:** Use the "Reset" button to return to the full dataset view.

---
