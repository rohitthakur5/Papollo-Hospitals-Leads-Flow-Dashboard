# Papollo Hospitals: Leads Flow & Patient Analytics Dashboard

## 📌 Project Overview
This project features an interactive **Power BI Analytics Dashboard** built to monitor and optimize hospital operations, patient distribution, and financial performance for **Papollo Hospitals**. It provides hospital administration and stakeholders with actionable, data-driven insights into resource utilization, clinical load, and billing metrics.

The project encompasses the entire data lifecycle: from connecting to the raw Excel data source, executing data transformations in Power Query, building a robust relational data model, to crafting custom visual metrics.

---

## 📊 Dashboard Preview
![Papollo Hospitals Dashboard](Papollo-Hospitals-Dashboard/Screenshots/Screenshot%202026-05-18%20113958.png)

---

## 🛠️ Tech Stack & Tools Used
* **Business Intelligence Tool:** Power BI Desktop
* **Data Transformation Engine:** Power Query (Data cleaning, handling date formats/locale logic, and step-sequencing)
* **Data Source:** Microsoft Excel (`Papollo-Healtcare-Dataset.xlsx`)
* **Modeling Techniques:** Star Schema design with proper dimensional relationships

---

## ⚡ Key Insights & Analytical Features

### 1. Operational & Patient Flow Tracking
* **Timeline KPIs:** Dynamically monitors critical dates including **Admit Date**, **Discharge Date**, and **Follow-up Date** to analyze length of stay and patient turnover.
* **Bed Occupancy Distribution:** Breaks down total patient count into **Private**, **General**, and **ICU** categories, allowing management to balance ward capacities and avoid resource bottlenecking.

### 2. Clinical Load & Feedback Analysis
* **Feedback Volume per Doctor:** Tracks distribution across primary consulting physicians (e.g., Dr. Ravi D, Mark Joy, Jaya Yaadav) to monitor case-load distribution and operational equity.
* **Diagnosis Funnel:** Identifies seasonal and high-volume clinical cases, showing that **Viral Infections** and **Flu** drive the highest patient volumes, followed by Malaria and Typhoid.

### 3. Financial & Revenue Assurance
* **Insurance vs. Billing Correlation:** A dual-line trend visualization comparing **Health Insurance Amount** vs. **Billing Amount** across major diagnostic procedures. 
* High-revenue categories like **CT Scans**, **Ultrasound**, and **MRI** are highlighted to show the correlation between total healthcare cost and insurance recovery rates.

---
