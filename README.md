# 🏥 Hospital Management Dashboard

This project is a dynamic and comprehensive **Hospital Management Dashboard** developed using **Power BI** for visualization and **SQL** for robust data management. It provides senior management with critical, actionable insights across various operational and financial aspects of the hospital, significantly improving reporting efficiency and decision-making.

***

## ✨ Key Features & Highlights

* Developed a dynamic hospital management dashboard using **Power BI and SQL** to provide **actionable insights** for senior management.
* Built a robust **Finance Dashboard** to monitor critical KPIs, including **revenue streams, operational costs**, and overall profitability, leading to the identification of significant cost-saving opportunities.
* Empowered management with a **centralized reporting tool** that **reduced manual reporting time by 40%**.

***

## 🛠️ Technologies Used

| Category | Tool/Language | Purpose |
| :--- | :--- | :--- |
| **Data Visualization** | Power BI | Creating interactive and dynamic dashboards. |
| **Database** | SQL (MySQL) | Storing and managing relational hospital data. |
| **Data Source** | CSV/Excel | Initial datasets for populating the database. |

***

## 🖼️ Dashboard Previews

The repository includes screenshots of the following interactive dashboards in the `Dashboard_Images/` folder:

| Dashboard Image | Description |
| :--- | :--- |
| `Dashboard_Images/1.png` | **Overview / Patient's Dashboard:** Shows overall hospital metrics, stock status, bed status, and monthly charges trend. |
| `Dashboard_Images/2.png` | **Patient Dashboard (Detail View):** Highlights an individual patient's medical details, diagnosis, charges breakdown, and medicine consumption over time. |
| `Dashboard_Images/3.png` | **Doctor Dashboard:** Displays a doctor's personal profile, experience, salary metrics, and list of upcoming and completed appointments. |
| `Dashboard_Images/4.png` | **Hospital / Operational Dashboard:** Focuses on bed availability (by room type), patient volume by age category, and status of patient medical tests and surgeries. |
| `Dashboard_Images/5.png` | **Finance Dashboard:** Provides a detailed financial overview with key KPIs, a breakdown of various charges (e.g., Room, Surgery, Test), and a comparison of medicine stock vs. quantity sold. |

***

## 📊 Detailed Metrics & Insights

The dashboard provides a deep dive into the following operational and financial areas:

### 1. Overview & Patient Health
* **Key Metrics:** Total Patients (30), Total Amount (854K), Total Doctors (15), Staff Count (20).
* **Trends:** Monthly revenue/charges over time (May-23 to Oct-23).
* **Charges Breakdown:** Detailed visualization of Surgery Charges, Room Charges, Test Charges, Doctor Fees, and other charges.
* **Patient Status:** Tracking discharged vs. admitted patients and upcoming appointments.

### 2. Finance
* **Financial KPIs:** Total Paid Amount (101K), Average Age of Patient (46), Average Spend (3.38K), Doctors Salary (2.09M), **Total Profit (628.68K)**.
* **Inventory:** Comparison of in-stock medicine quantity vs. quantity sold for top items (e.g., Paracetamol, Ibuprofen).
* **Suppliers:** Performance tracking based on quantity sold by various suppliers.

### 3. Operations
* **Bed Status:** Tracks available vs. occupied beds across different room types (General, Private, ICU).
* **Tests Status:** Monitors completed tests and results (Normal/Abnormal) organized by patient age category.
* **Appointments:** List of upcoming and completed doctor's appointments.

***

## 💾 Data Model (Database Tables)

The project utilizes a robust relational database with the following 14 core tables, managed via SQL:

| Table Name | Description |
| :--- | :--- |
| `patient` | Personal and admission details of patients. |
| `doctor` | Details of all medical staff, including specialization and salary. |
| `staff` | Details of non-medical staff (nurses, ward boys). |
| `department` | Information on all hospital departments and their head doctors. |
| `rooms` | Details about hospital rooms, including type, floor, capacity, and daily charge. |
| `beds` | Status of individual beds (Available/Occupied) and patient assignments. |
| `appointment` | Records of patient appointments, fees, and initial diagnosis. |
| `surgery` | Records of completed surgeries/procedures. |
| `patient_tests` | Records of medical tests prescribed, results, and fees. |
| `medical_stock` | Inventory and pricing information for all medicines/drugs. |
| `medicine_patient` | Transactional data for medicines dispensed to patients. |
| `hospital_bills` | Detailed financial records of all hospital charges and payment status. |
| `supplier` | Details of vendors supplying medical stock. |
| `satisfaction_score` | Patient feedback and rating on doctor services. |

***

## 🚀 Setup Instructions

1.  **Database Setup:**
    * Set up a **MySQL** database instance.
    * Execute the `hospital_data.sql` script to create the `hospital_data` database, its tables, and populate them with the initial data.

2.  **Data Source (Optional):**
    * The raw data files (in the `Datasets` folder) are provided if direct import/connection to the flat files is needed.

3.  **Power BI Dashboard:**
    * Open the Power BI file in Power BI Desktop.
    * Update the data connections to point to your hosted MySQL database.
    * Refresh the report to load the data and view the dashboards.
