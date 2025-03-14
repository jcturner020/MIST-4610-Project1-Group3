# MIST-4610-Project1-Group3


Team Name: Group 3

Team Members:

Mallavarapu, Pariprita @paripritam
Le, Yen
Asenuga, Princess
Turner, Jack
Problem Description: Our Pharmacy Database is designed to streamline the operations of a modern pharmacy business. This database facilitates the management of essential functions such as store operations, patient records, doctor affiliations, prescription tracking, medicine inventory, and sales management. By centralizing critical data, our system enhances operational efficiency, improves data accuracy, and provides valuable insights for informed decision-making by pharmacy management. Ultimately, the Pharmacy Database supports the pharmacy’s goal of delivering exceptional patient care, ensuring regulatory compliance, and optimizing resources to maximize profitability.

Data Model: This data model represents a pharmacy management system, tracking interactions between doctors, patients, prescriptions, medicines, sales transactions, employees, and stores.

The Doctor entity captures doctor information, including their name, specialization, and contact number. Each doctor is linked to multiple Prescriptions, which store prescription details, including the prescribed date, expiration date, and duration of the medication supply. A prescription is associated with a single Patient, allowing the tracking of patient medical history.

The Medicine entity links to prescriptions, recording the details of prescribed drugs such as name, manufacturer, dosage, and expiration. A prescription can include multiple medicines, but each medicine entry is tied to a specific prescription.

The Patient entity maintains patient details, including name, date of birth, gender, contact information, and address. Patients are associated with a Store, indicating the pharmacy location where they obtain their prescriptions. The Store entity stores location details and contact information and links to employees working there.

The Employee entity tracks pharmacy staff, including their roles and store assignments. Employees handle Sales transactions, where each sale is associated with a patient and a prescription. Sales transactions store details such as the sale date, total amount, and employee responsible for the sale.

The relationships between these entities ensure efficient tracking of patient prescriptions, medicine inventory, doctor interactions, ales transactions, and pharmacy staff management, forming a comprehensive pharmacy management system. sScreenshot 2025-03-13 at 10 55 43 PM

Data Dictionary:

Screenshot 2025-03-13 at 10 58 26 PM Screenshot 2025-03-13 at 10 59 19 PM Screenshot 2025-03-13 at 10 59 34 PM Screenshot 2025-03-13 at 10 59 49 PM Screenshot 2025-03-13 at 11 00 06 PM Screenshot 2025-03-13 at 11 00 20 PM Screenshot 2025-03-13 at 11 00 33 PM
Queries:

Query 1 gives us the names of all the medicines in the database along with their dosage.
Screenshot 2025-03-13 at 11 05 15 PM
Query 2 gives us the first and last name, contact number and email of the patients in the database.
Screenshot 2025-03-13 at 11 06 20 PM
Query 3 shows all the employees working at a specific store.
Screenshot 2025-03-13 at 11 20 24 PM
Query 4 gives the total number of patients in the whole database
Screenshot 2025-03-13 at 11 22 38 PM
Query 5 shows us the top 5 most sold medicines
Screenshot 2025-03-13 at 11 23 38 PM
Query 6 finds the top 3 stores with the highest number of patients
Screenshot 2025-03-13 at 11 24 55 PM
Query 7 retrieves all sales transactions processed by each employee.
Screenshot 2025-03-13 at 11 25 40 PM
Query 8 finds patients who have spent more than $70 on medicines.
Screenshot 2025-03-13 at 11 26 42 PM
Query 9 identifies the top 5 doctors who have perscribed the most medicines.
Screenshot 2025-03-13 at 11 27 39 PM
Query 10 counts the number of employees in each store.
Screenshot 2025-03-13 at 11 30 04 PM
Database Information:

Screenshot 2025-03-13 at 11 33 28 PM
Name of the database: ha_group3_crn71552
