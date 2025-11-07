# ⚙ Predictive Maintenance Dashboard — Power BI

### 📌 Overview
A 3-page Power BI dashboard for machine health monitoring and anomaly detection.  
It helps identify high-risk machines, analyze failure causes, and support preventive maintenance decisions.

---

## ✅ Key Features
- KPI cards for failures, anomaly rate & fleet status
- Failure distribution by machine type
- Conditional formatting for temperature & wear risk
- Drillthrough page for machine-level diagnostics
- Exportable anomaly table for maintenance teams
- Interactive slicers for Product ID and Machine Type

---

## ✅ Dashboard Pages

### 1️⃣ Executive Overview
- High-level summary of machines, failures, and anomaly rate  
- Failures by machine type  
- Machine status (Normal vs Anomaly)  
- Scatter: Speed vs Torque sized by Tool Wear  
- Global filters for Type and Product ID

### 2️⃣ Anomaly Operations Center
- Table of abnormal machines only  
- Color-coded risk highlighting  
- Filters to isolate risky machines  
- Export option for maintenance planning

### 3️⃣ Machine Diagnostics (Drillthrough)
- Opens when user right-clicks a machine  
- Shows machine-specific KPIs  
- Temperature trend over time (index-based)  
- “Machine Under Diagnosis” indicator

---

## ✅ Dataset
- AI4I Predictive Maintenance Dataset  
- 10,000+ machine cycles  
- Key fields: Temperature, rotational speed, torque, tool wear  
- Target labels: Failure / Anomaly status

---

## ✅ Tools & Methods
| Step | Tool |
|------|------|
| Visualization | Power BI |
| Data shaping | Power Query |
| Metrics & formatting | DAX + Conditional formatting |
| Interaction | Slicers & Drillthrough |

---

## ✅ How to Use
1. Open the `.pbix` file in Power BI Desktop  
2. Use slicers to filter machines  
3. Export anomaly list from Page 2  
4. Right-click any Product ID → Drillthrough → Machine Diagnostics

---

## ✅ Business Impact
- Early detection of risky machines  
- Reduces unplanned breakdowns  
- Supports preventive maintenance  
- Improves reliability and uptime

---

## ✅ Future Enhancements
- Live IoT data connection  
- Failure probability / RUL prediction  
- Automated alerts for high-risk machines

---

## ✅ Author
**Teenu Mary John**  
Power BI • Data Analytics  

LinkedIn: https://linkedin.com/in/teenu-mary-john-24b09a369  
GitHub: https://github.com/teenujohn25
