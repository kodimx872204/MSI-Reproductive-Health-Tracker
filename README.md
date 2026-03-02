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
<img width="1914" height="796" alt="Image" src="https://github.com/user-attachments/assets/4f650d6f-fe90-4901-8a87-bdca520e658b" />

<img width="918" height="841" alt="Image" src="https://github.com/user-attachments/assets/3be69be8-2b7b-42c4-8df0-62ff677db80a" />
<img width="909" height="837" alt="Image" src="https://github.com/user-attachments/assets/98d35192-be4a-42ca-b016-7c9438cf9c84" />
<img width="906" height="850" alt="Image" src="https://github.com/user-attachments/assets/e6d6355b-bea2-4840-8268-1137bd4da009" />
<img width="1905" height="807" alt="Image" src="https://github.com/user-attachments/assets/bdccc91a-b128-48c3-ba30-1f50292c6704" />
<img width="1910" height="786" alt="Image" src="https://github.com/user-attachments/assets/3fab3143-2699-4236-a8dc-2b2b53a82760" />
<img width="1915" height="792" alt="Image" src="https://github.com/user-attachments/assets/b12c8786-41ea-4801-ae3f-e9a9f9d05b84" />
<img width="1919" height="798" alt="Image" src="https://github.com/user-attachments/assets/e54ab8da-ed50-46ac-8e11-b494af852728" />
<img width="1915" height="796" alt="Image" src="https://github.com/user-attachments/assets/6f35b8a7-32b9-4758-bcd0-f02ef292f207" />
<img width="1913" height="803" alt="Image" src="https://github.com/user-attachments/assets/76fd753d-df03-4c56-ba3c-3f5fd0abf2e1" />
<img width="1916" height="802" alt="Image" src="https://github.com/user-attachments/assets/dc82f0d8-69e2-4956-973d-73c88b62ee86" />
<img width="882" height="729" alt="Image" src="https://github.com/user-attachments/assets/9b5cbae4-97ce-42f0-9e61-cc878d1587d2" />
<img width="909" height="827" alt="Image" src="https://github.com/user-attachments/assets/f58dd3f0-244d-45c3-8a1f-2098b185cb2e" />
<img width="913" height="816" alt="Image" src="https://github.com/user-attachments/assets/6c8f6be4-1fbb-46cb-a96c-f9446a4ab6ee" />
<img width="902" height="842" alt="Image" src="https://github.com/user-attachments/assets/04617c2d-54a1-4912-9949-82cf622b7ba8" />
<img width="885" height="836" alt="Image" src="https://github.com/user-attachments/assets/775874c7-c16e-4408-8748-8807040e2bbd" />

Confidentiality: To protect patient privacy and NGO internal strategy, actual data and proprietary SQL schemas are not public.



📫 Contact
For inquiries regarding this architecture or similar health-tech implementations in the DRC:
Alpha Mubay - lucmubay@gmail.com 
