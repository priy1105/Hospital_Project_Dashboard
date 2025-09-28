# 🏥 Hospital Management Dashboard

This project is a dynamic and comprehensive **Hospital Management Dashboard** developed using **Power BI** for visualization and **SQL** for robust data management. It provides senior management with critical, actionable insights across various operational and financial aspects of the hospital, significantly improving reporting efficiency and decision-making.

***

## ✨ Key Features & Highlights

* Developed a dynamic hospital management dashboard using **Power BI and SQL** to provide **actionable insights** for senior management.
* Built a robust **Finance Dashboard** to monitor critical KPIs, including **revenue streams, operational costs**, and overall profitability, leading to the identification of significant cost-saving opportunities.
* Empowered management with a **centralized reporting tool** that **reduced manual reporting time by 40%**.

***

## 🖼️ Dashboard Previews

The repository includes screenshots of the following interactive dashboards:

| Dashboard Image | Description |
| :--- | :--- |
| `Dashboard_Images/1.png` | **Overview / Patient's Dashboard:** Shows overall hospital metrics, stock status, bed status, and monthly charges trend. |
| `Dashboard_Images/2.png` | **Patient Dashboard (Detail View):** Highlights an individual patient's medical details, diagnosis, charges breakdown, and medicine consumption over time (e.g., Amit Kumar). |
| `Dashboard_Images/3.png` | **Doctor Dashboard:** Displays a doctor's personal profile, experience, salary metrics, and list of upcoming and completed appointments (e.g., Dr. Anita Patel). |
| `Dashboard_Images/4.png` | **Hospital / Operational Dashboard:** Focuses on bed availability (by room type), patient volume by age category, and status of patient medical tests and surgeries. |
| `Dashboard_Images/5.png` | **Finance Dashboard:** Provides a detailed financial overview with key KPIs, a breakdown of various charges (e.g., Room, Surgery, Test), and a comparison of medicine stock vs. quantity sold. |

***

## 📊 Core Metrics & Insights

The solution enables tracking of vital operational and financial metrics:

* **Overview Metrics:** Total Patients (30), Total Amount (854K), Total Doctors (15), Staff Count (20).
* **Financial KPIs:** Total Paid Amount (101K), Average Patient Age (46), Average Spend (3.38K), Total Profit (628.68K).
* **Operational Status:** Stock left (4030) vs. Stock sold, and Available (16) vs. Occupied (9) beds.
* **Charges Analysis:** Detailed breakdown of charges, including Surgery Charges, Room Charges, Test Charges, Doctor Fees, and other charges.

***

## 💾 Data Model (Database Tables)

The project utilizes a relational database with the following core tables:

| Table Name | Description |
| :--- | :--- |
| `patient` | Personal and admission details of patients. |
| `doctor` | Details of all medical staff, including specialization and salary. |
| `hospital_bills` | Detailed financial records of all hospital charges and payment status. |
| `medical_stock` | Inventory and pricing information for all medicines/drugs. |
| `appointment` | Records of patient appointments, fees, and initial diagnosis. |
| `rooms` & `beds` | Status and details of hospital rooms and beds. |
| `staff` | Details of non-medical support staff. |
| `satisfaction_score` | Patient feedback and rating on doctor services. |

***

## 🚀 Setup Instructions

1.  **Database Setup:**
    * Set up a **MySQL** database instance.
    * Execute the `hospital_data.sql` script to create the `hospital_data` database, its tables, and populate them with the initial data.

2.  **Data Source (Optional):**
    * The raw data files (`.csv` and `.xlsx` files in the `Datasets` folder) are provided if direct import/connection to the flat files is preferred over SQL.

3.  **Power BI Dashboard:**
    * Open the Power BI file (not explicitly provided but assumed to exist) in Power BI Desktop.
    * Ensure the data connections within the Power BI file are updated to point to your hosted MySQL database or the local CSV/Excel files.
    * Refresh the report to load the data and view the dashboards.
