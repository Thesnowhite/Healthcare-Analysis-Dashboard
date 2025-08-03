
# Healthcare Analysis Dashboard

##  Introduction
This interactive Power BI dashboard provides a comprehensive overview of healthcare billing, treatment, and service performance across various UK regions. It enables hospital administrators, public health officials, and healthcare analysts to track key operational metrics and gain actionable insights to improve resource allocation, treatment effectiveness, and financial performance.



## Problem Statement
Healthcare organizations often face challenges in analyzing large volumes of billing and treatment data across different departments, service types, and geographic locations. Disconnected systems and manual reporting limit the ability to monitor efficiency, detect cost outliers, and improve patient services.

This dashboard solves that problem by centralizing relevant metrics into one visually-rich, interactive platform to enable fast and informed decision-making.



##  Objectives
The primary goals of the dashboard are to:

- Consolidate and visualize key billing and treatment metrics across UK states
- Track average cost per service type (room charges, medication, treatment)
- Analyze insurance coverage trends and billing breakdowns by department and procedure
- Support data-driven resource planning and risk management
- Enable filtering by state to observe regional differences in performance

  

## Dataset From Kaggle after it has been cleaned,Transformed and Loaded into Power bi Desktop




<img width="1844" height="728" alt="Screenshot 2025-08-03 230257" src="https://github.com/user-attachments/assets/0f08ce1f-309a-48eb-a67a-30c30f989cd4" />



<img width="581" height="716" alt="Screenshot 2025-08-03 230317" src="https://github.com/user-attachments/assets/439278bd-11d4-4983-bc9f-50b69fb00b8f" />



<img width="353" height="684" alt="Screenshot 2025-08-03 230335" src="https://github.com/user-attachments/assets/c3466c1d-50c1-4fe5-9b0e-dea5577922d2" />



<img width="312" height="382" alt="Screenshot 2025-08-03 230349" src="https://github.com/user-attachments/assets/c9c68dc2-09c9-479c-b0c0-d480b56a1511" />




##  Data Preparation & Process
- Data Source: Simulated healthcare billing data (cleaned Excel or synthetic dataset)
- Cleaning Tools: Microsoft Excel & Power Query  
- ETL Process
- Removed missing values and standardized field types
- Aggregated treatment costs, billing amounts, and procedure-level data
- Created calculated measures in Power BI using DAX for metrics like:
- Average Billing Per Visit
- Average Treatment and Medication Costs
- Insurance Coverage per Region



## 📈 Dashboard Features

### KPI Cards:
- Total Billing Amount: $3M  
- Treatment Amount: $3M  
- Room Charges: $180K  
- Medication Cost: $546K  
- Insurance Coverage: $2.2M

- Averages:  
  - Billing per Visit: $675  
  - Treatment Cost: $526  
  - Medication Cost: $109  
  - Insurance Coverage: $456  



Here is the Hospital Analysis Dashboard to Visualize the Dataset



<img width="1017" height="573" alt="Screenshot 2025-08-03 215128" src="https://github.com/user-attachments/assets/9ee08845-407d-4c59-8cfe-3abfc6364b1f" />




##  Key Insights
- X-Rays are the highest billed procedures, followed by CT and MRI scans.
- Cardiology and Orthopedics departments generate the highest billing revenue.
- Northern Ireland and Wales show higher billing amounts relative to population, suggesting regional demand or cost variations.
- Emergency services dominate billing across most diagnosis types, especially in Asthma and Hypertension cases.
- Average insurance coverage per visit is significantly lower than average treatment cost, suggesting a potential gap in reimbursement models.



##  Business Recommendations
- Re-evaluate treatment pricing or insurance negotiations in regions where coverage gaps persist.
- Monitor procedure frequency and costs in Cardiology and Orthopedics to manage resource use and patient flow.
- Invest in outpatient service models for diagnoses like Asthma and Migraines, where emergency services are over-utilized.
- Use regional insights to inform staffing and budget allocations across states with higher billing volume.



##  Tools & Technologies Used
- Power BI – Visualization, Data Modeling, DAX  
- Microsoft Excel – Data Cleaning & Transformation  
- Power Query – ETL (Extract, Transform, Load)  
- DAX – KPI Measures & Custom Calculations  



## powerbi, healthcare-analytics, data-visualization, dashboard, business-intelligence, bi-project, portfolio


