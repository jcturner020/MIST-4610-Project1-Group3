# MIST-4610-Project1-Group3
Team Name:
Group 3

Team Members:
1. Mallavarapu, Pariprita @paripritam
2. Le, Yen 
3. Asenuga, Princess
4. Turner, Jack

Problem Description:
Our Pharmacy Database is designed to streamline the operations of a modern pharmacy business. This database facilitates the management of essential functions such as store operations, patient records, doctor affiliations, prescription tracking, medicine inventory, and sales management. By centralizing critical data, our system enhances operational efficiency, improves data accuracy, and provides valuable insights for informed decision-making by pharmacy management. Ultimately, the Pharmacy Database supports the pharmacy’s goal of delivering exceptional patient care, ensuring regulatory compliance, and optimizing resources to maximize profitability.

Data Model:
This data model represents a pharmacy management system, tracking interactions between doctors, patients, prescriptions, medicines, sales transactions, employees, and stores.

The Doctor entity captures doctor information, including their name, specialization, and contact number. Each doctor is linked to multiple Prescriptions, which store prescription details, including the prescribed date, expiration date, and duration of the medication supply. A prescription is associated with a single Patient, allowing the tracking of patient medical history.

The Medicine entity links to prescriptions, recording the details of prescribed drugs such as name, manufacturer, dosage, and expiration. A prescription can include multiple medicines, but each medicine entry is tied to a specific prescription.

The Patient entity maintains patient details, including name, date of birth, gender, contact information, and address. Patients are associated with a Store, indicating the pharmacy location where they obtain their prescriptions. The Store entity stores location details and contact information and links to employees working there.

The Employee entity tracks pharmacy staff, including their roles and store assignments. Employees handle Sales transactions, where each sale is associated with a patient and a prescription. Sales transactions store details such as the sale date, total amount, and employee responsible for the sale.

The relationships between these entities ensure efficient tracking of patient prescriptions, medicine inventory, doctor interactions,
ales transactions, and pharmacy staff management, forming a comprehensive pharmacy management system.
s<img width="730" alt="Screenshot 2025-03-13 at 10 55 43 PM" src="https://github.com/user-attachments/assets/82ebc201-5593-4316-a360-b73ca7b83d91" />

Data Dictionary:

<img width="427" alt="Screenshot 2025-03-13 at 10 58 26 PM" src="https://github.com/user-attachments/assets/77519323-c93d-4552-a628-0efb8be8fdec" />

<img width="382" alt="Screenshot 2025-03-13 at 10 59 19 PM" src="https://github.com/user-attachments/assets/b50e05c3-a59a-4426-9265-48f2ef4bdb26" />

<img width="398" alt="Screenshot 2025-03-13 at 10 59 34 PM" src="https://github.com/user-attachments/assets/e9ae43b9-4044-4e8c-8950-0c9a0b105607" />

<img width="372" alt="Screenshot 2025-03-13 at 10 59 49 PM" src="https://github.com/user-attachments/assets/6bafd056-cb1a-45fe-9ce0-297870a4268d" />

<img width="371" alt="Screenshot 2025-03-13 at 11 00 06 PM" src="https://github.com/user-attachments/assets/403e8e10-eb5c-46b9-9686-c12411ef3172" />

<img width="369" alt="Screenshot 2025-03-13 at 11 00 20 PM" src="https://github.com/user-attachments/assets/51e14c60-60eb-499a-8f71-cf017d40c878" />

<img width="384" alt="Screenshot 2025-03-13 at 11 00 33 PM" src="https://github.com/user-attachments/assets/1276c32f-89b8-42f7-945f-d28b9f0af820" />

Queries:
1. Query 1 gives us the names of all the medicines in the database along with their dosage.
<img width="481" alt="Screenshot 2025-03-13 at 11 05 15 PM" src="https://github.com/user-attachments/assets/bfba3903-3ba1-4cb5-a122-631c0ac0619d" />

2. Query 2 gives us the first and last name, contact number and email of the patients in the database. 
<img width="475" alt="Screenshot 2025-03-13 at 11 06 20 PM" src="https://github.com/user-attachments/assets/da4a7e7e-0bcf-401a-bce7-ead8e8fc21c0" />

3. Query 3 shows all the employees working at a specific store.
<img width="576" alt="Screenshot 2025-03-13 at 11 20 24 PM" src="https://github.com/user-attachments/assets/ab67089d-4fd8-4b96-8dfd-d453813d6ac4" />

4. Query 4 gives the total number of patients in the whole database
<img width="516" alt="Screenshot 2025-03-13 at 11 22 38 PM" src="https://github.com/user-attachments/assets/9e296a02-88bb-4f82-94fb-883dc5ddfad6" />

5. Query 5 shows us the top 5 most sold medicines
<img width="629" alt="Screenshot 2025-03-13 at 11 23 38 PM" src="https://github.com/user-attachments/assets/caee5734-4a79-42f4-97d8-052a60219b4c" />
6. Query 6 finds the top 3 stores with the highest number of patients
<img width="575" alt="Screenshot 2025-03-13 at 11 24 55 PM" src="https://github.com/user-attachments/assets/6d1103dc-fa47-49c0-81e9-8f39c032efa3" />

7. Query 7 retrieves all sales transactions processed by each employee.
<img width="694" alt="Screenshot 2025-03-13 at 11 25 40 PM" src="https://github.com/user-attachments/assets/b7dca1de-8d76-4977-978d-588d33c7081f" />

8. Query 8 finds patients who have spent more than $70 on medicines.
<img width="706" alt="Screenshot 2025-03-13 at 11 26 42 PM" src="https://github.com/user-attachments/assets/b64d76f2-a9d2-4cbb-9b33-714f3d7c9f25" />

9. Query 9 identifies the top 5 doctors who have perscribed the most medicines.
<img width="804" alt="Screenshot 2025-03-13 at 11 27 39 PM" src="https://github.com/user-attachments/assets/7b5c7606-056c-4187-9643-d18bd93c1efe" />

10. Query 10 counts the number of employees in each store.
<img width="639" alt="Screenshot 2025-03-13 at 11 30 04 PM" src="https://github.com/user-attachments/assets/fba08dbe-74e1-43fd-a16e-70a4dbedeae2" />

Database Information:
<img width="766" alt="Screenshot 2025-03-13 at 11 33 28 PM" src="https://github.com/user-attachments/assets/ceec3759-0fbe-4656-a583-efdf1a092873" />

Name of the database: ha_group3_crn71552

