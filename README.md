# 📊 Third-Party Risk Assessment Tool

An **Excel-based risk assessment & visualization tool** designed to help organizations evaluate and monitor **third-party/vendor risks** effectively. It combines advanced Excel techniques with established risk management principles like **NIST CSF** and **ISO 27001** to deliver actionable insights via **heatmaps, dashboards, and charts**.

---

## 🚀 Features

- 📋 **Risk Register** — Log and track vendors with details like:
  - Vendor Name
  - Criticality (High, Medium, Low)
  - Data Access Level (Confidential, Sensitive, Public)
  - Auto-calculated Composite Risk

- 🎨 **Heatmap Visualization** — Color-coded risk levels using Excel conditional formatting for quick identification:
  - 🔴 High
  - 🟡 Medium
  - 🟢 Low

- 📊 **Pivot Table Summary** — Aggregated vendor count by:
  - Risk level
  - Data access level

- 📈 **Charts & Dashboard**
  - Donut / Pie chart of vendors by risk level
  - Criticality vs. Composite Risk (scatter plot) to spot anomalies
  - Stacked bar chart of data access vs. risk (optional)

- 📝 **Auto Recommendations** — Suggested mitigation strategies for high/medium-risk vendors

---

## 📄 File Contents

| Sheet Name           | Description                                                   |
|----------------------|---------------------------------------------------------------|
| `Vendor Data`        | Main data table with inputs, formulas, heatmaps               |
| `Summary`            | Pivot table summary showing vendor counts by risk levels      |
| `Criticality_vs_Risk`| Scatter plot chart comparing criticality vs. composite risk   |
| `Dashboard` (optional)| Combined visual charts for high-level insights               |

---

## 🔷 How It Works

1️⃣ **Input vendor information** in the `Vendor Data` sheet:
- Vendor Name
- Services Provided
- Criticality
- Data Access Level

2️⃣ Tool automatically calculates:
- Composite Risk Score (using internal rules)
- Risk Level (High / Medium / Low)
- Recommended Actions

3️⃣ **Visual cues via conditional formatting**:
- 🔴 High Risk
- 🟡 Medium Risk
- 🟢 Low Risk

4️⃣ **Charts and summaries update in real-time** to reflect current risk posture.

---

## 💡 Use Cases

- Third-party/vendor risk monitoring
- Audit readiness (SOC 1, SOC 2, ISO 27001)
- Risk dashboards for internal leadership reviews

---

## 🛠 Technologies & Skills Demonstrated

- **Advanced Excel**: 
  - Formulas (`IF`, `COUNTIF`, nested logic)
  - Pivot Tables
  - Conditional Formatting
  - Data Validation

- **Data Visualization**:
  - Heatmaps
  - Donut / Pie Charts
  - Scatter Plots
  - Stacked Bar Charts

- **Risk Management**:
  - Aligned with **NIST Cybersecurity Framework** & **ISO 27001**
  - Mitigation planning based on composite risk scoring

- **Process Documentation**:
  - Structured layout with easy-to-follow workflows

---

## 🖼️ Sample Screenshot

> <img width="1037" height="692" alt="image" src="https://github.com/user-attachments/assets/422b3382-cd06-4672-99c4-69b2f09b8b39" />
> <img width="1280" height="587" alt="image" src="https://github.com/user-attachments/assets/9fd6e1e7-c87d-40a5-970c-6c2054e03c99" />


---

## 👤 Author

**K. Sai Nihith**

- [LinkedIn](https://linkedin.com/in/your-profile)  
- [GitHub](https://github.com/your-username)  

---

