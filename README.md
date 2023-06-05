# Hema General Hospital

## CS50
>This was my final project to conclude the CS50 Introduction to Computer Science course.

>Technologies used: Python, Flask web framework, web development, CS50


## Features

- [Flask-qrCode](https://pypi.org/project/qrcode/)
- [Python-matplotlib](https://www.w3schools.com/python/matplotlib_pyplot.asp)
- [Python-csv](https://docs.python.org/3/library/csv.html)

I've used the Flask web framework based on the Python programming language.

It was necessary to use qrCode to generate reservation tickets. Additionally, I used matplotlib to generate bar and pie charts for doctor evaluations.

I've utilized the csv library to export CSV sheets for the accountant to review checks.

## Project Description and Database

- My final project is a website for a hospital reservation system that allows:

### 1. Patients 

 - Register accounts.
 - View available hospital specialties.
 - Make reservations with specific doctors on selected days.
 - View all reservations made by the patient.
 
### 2. Receptionists/Call Centers

- Register patient accounts while they are still on the line.
- Search for patients by their name, numbers, or age.
- Make doctor reservations for patients.
- View all available doctors for reservation.
- View all patient reservations along with their status (Reserved, Unchecked, Checked, Reviewed).
- Print tickets for patients after they have made their doctor reservation purchase.
- Review late reservations made by patients who did not attend their reservation within 8 days to check their health status and their intention to renew or cancel their reservation.
- Reset the doctor reservation queue every week, starting the queue number from 1 again.
- Write and view sent and received messages with all staff accounts.

### 3. Nurses

- Check reservations of doctor clinics for patients who attend their reservations.
- Write and view sent and received messages with all staff accounts.

### 4. Accountants

- Review reservations for all patients who have checked in with their doctors.
- The review process includes tickets generated by the receptionist and tickets checked by the nurse.
- Gather information for all reviewed reservations within a specific date range and calculate the "Total Reservations Cash".
- Export the generated table as a CSV file.
- Perform doctor evaluations within a specific date range to review the "Total Reservations" and "Total Cash" for each doctor.
- Generate bar and pie charts for the evaluation.
- Save the generated tables, charts as CSV files, and pictures.
- Undo the check-in for reservations that were mistakenly checked by the nurse.
- Write and view sent and received messages with all staff accounts.

### 5. Admins

#### The admin account has the authority to make various modifications on the website:

- Modify all staff accounts (Receptionists/Call Centers, Nurses, Accountants) by adding, removing, or modifying staff data.
- Modify doctors by adding, removing, modifying their available days, modifying doctor reservation prices, activating doctors for new reservations, or deactivating doctors.
- Modify specialties by adding or removing specialties.
- Modify basic website data in the header and footer (Phone number, Address, Email, Facebook page, Twitter page, Instagram page, and Linkedin page).
- Issue refunds for reviewed reservations if the client is dissatisfied with the services.
- Delete patient accounts due to inactivity or spam.
- Write and view sent and received messages with all staff accounts.

### 6. Developer

#### The developer account is exclusively managed by the company that developed the website for the hospital:

- Access the database through the website with an input box to make SQL queries.
- Renew the quota that allows the website to accommodate patients, receptionists/call centers, nurses, and accountants.
- Upgrade the quota to different subscriptions (Standard, Plus, Premium, Gold Premium) to increase the total number of staff and patient accounts.
- Perform web deployment by adding the path of the web containing folder.

