# MSI-Reproductive-Health-Tracker
📌 Project Overview
This project involved developing a real-time data analysis ecosystem for MSI RDC (an international NGO). The system tracks and evaluates reproductive health programs across rural zones in the Democratic Republic of Congo. By connecting field data directly to SQL-based analytical dashboards, the solution provides leadership with an immediate view of program effectiveness.

🇨🇩 The DRC Challenge: Rural Data Enclavement
Field research in rural DRC faces two massive hurdles:

Connectivity: Health workers operate in "white zones" with zero internet.

Delayed Reporting: Traditional paper or manual reporting meant data reached Kinshasa weeks or months late, making it impossible to pivot programs quickly.

The Solution
An offline-first data pipeline using KoboToolbox for field collection, which automatically synchronizes with a central SQL database once a mobile connection is established.

🛠 Technical Stack
Data Collection: KoboToolbox (ODK-based) for resilient offline forms.

Database & Analysis: Advanced SQL for data transformation and aggregation.

Dashboarding: Real-time visualization of health KPIs.

Integration: API-based synchronization between field servers and analytical databases.

🚀 Key Features & Impact
Real-Time Program Evaluation: Transitioned from monthly reports to live performance tracking of reproductive health interventions.

Offline-First Architecture: Enabled 100% data capture in remote rural areas without internet access.

Data Integrity: Implemented automated SQL validation scripts to clean and standardize field entries, reducing reporting errors by [Estimated %].

Strategic Decision Making: Allowed MSI RDC to reallocate resources to underperforming zones based on evidence rather than intuition.

📐 Technical Architecture
Field Entry: Staff use mobile devices to record intervention data offline.

Sync: Data is pushed to the KoboToolbox server upon reaching a coverage zone.

ETL Process: SQL scripts extract raw JSON/XML data, transform it into structured relational tables, and load it into the reporting layer.

Visualization: Aggregated data is presented to MSI directors for monitoring program reach and demographic impact.

📸 Technical Showcase
[!IMPORTANT]


Confidentiality: To protect patient privacy and NGO internal strategy, actual data and proprietary SQL schemas are not public.



📫 Contact
For inquiries regarding this architecture or similar health-tech implementations in the DRC:
Alpha Mubay - lucmubay@gmail.com 
