# **Capstone Project Overview: Inflation vs. Wages Tracker**  

### **🌍 Problem Statement**  
Economic disparities arise when wage growth fails to keep pace with inflation, eroding purchasing power. This project quantifies the relationship between inflation and wage trends, empowering users to make data-driven financial decisions.  

---

### **🎯 Objectives**  
1. **Data Integration**  
   - Collect historical inflation (CPI) and wage growth datasets from authoritative sources (e.g., FRED, World Bank).  
2. **Trend Analysis**  
   - Identify periods where wages lagged inflation (e.g., 2022’s "silent pay cut" phenomenon).  
3. **Visualization**  
   - Build interactive dashboards to compare trends across countries/years.  
4. **Actionable Insights**  
   - Recommend policy/personal finance strategies based on gaps.  

---

### **🛠️ Technical Stack**  
| **Component**       | **Tools**                          |  
|---------------------|-----------------------------------|  
| Data Collection     | Python (`requests`, `pandas`), APIs (FRED, OECD) |  
| Data Cleaning      | `pandas`, `numpy` (handle missing values) |  
| Analysis          | Statistical modeling (YoY % changes), `scipy` |  
| Visualization     | `matplotlib`, `Plotly`, Excel (fallback) |  
| Deployment       | GitHub (code), Streamlit/Tableau (optional dashboard) |  

---

### **📂 Deliverables (Structured for Capstone)**  
1. **`/data`**  
   - Raw datasets (`inflation_raw.csv`, `wages_raw.csv`) + cleaned versions.  
2. **`/notebooks`**  
   - Jupyter Notebooks for EDA and statistical tests.  
3. **`/scripts`**  
   - Modular Python scripts (e.g., `fetch_data.py`, `analyze_trends.py`).  
4. **`/docs`**  
   - Project charter, methodology write-up, and user guide.  
5. **`/output`**  
   - Visualizations (PNG/HTML) and final report (PDF).  

---

### **⏱️ Timeline (Milestones)**  
| **Week** | **Task**                          | **Outcome**                          |  
|----------|-----------------------------------|--------------------------------------|  
| 1        | Data requisition & cleaning      | Validated datasets ready for analysis |  
| 2        | Exploratory analysis             | Key trends identified (e.g., 2022 wage gap) |  
| 3        | Visualization & dashboard build  | Interactive charts deployed          |  
| 4        | Documentation & testing          | Final report, code reviewed          |  

---

### **💡 Expected Impact**  
- **For Policymakers**: Highlight regions/industries needing wage adjustments.  
- **For Individuals**: Tool to benchmark salary raises against inflation.  
- **Academic Contribution**: Reusable pipeline for macroeconomic analysis.  

---

### **🔗 Next Steps**  
1. **Repo Setup**: Clone [this template](https://github.com/datascience/capstone-template) to align with capstone folder structure.  
2. **Data Validation**: Cross-check sources for consistency (e.g., OECD vs. national data).  
3. **Peer Review**: Share drafts with mentors for feedback.  

--- 
