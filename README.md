# Medical-Appointment-No-Show-Prediction

Project Overview
This Capstone project aims to develop a predictive model to identify patients who are likely to miss their scheduled medical appointments. By analyzing historical appointment data, we can create a solution that will help healthcare providers proactively manage and reduce no-show rates, ultimately improving resource allocation and patient care.

Problem Area
No-shows for medical appointments represent a significant challenge for healthcare providers, leading to inefficient use of resources, increased waiting times for other patients, and potential negative impacts on patient health. Identifying patients who are likely to miss their appointments can allow providers to take preventive actions, such as sending additional reminders or offering flexible scheduling options.

Proposed Data Science Solution
We propose developing a machine learning model that predicts the likelihood of a patient not showing up for their scheduled appointment. This model will be trained on historical appointment data and will take into account various factors such as patient demographics, medical history, and appointment details.


Impact of the Solution
The implementation of this predictive model will enable healthcare providers to:

Reduce the rate of no-shows by identifying high-risk patients and implementing targeted interventions.
Improve patient care by ensuring that appointment slots are effectively utilized.
Optimize resource allocation, reducing operational inefficiencies and improving overall service delivery.


Data Dictionary:

PatientId: Identification number of a patient.
AppointmentID: Identification number for each appointment.
Gender: Gender of the patient (Male or Female).
AppointmentDay  : The date of the actual appointment.
ScheduledDay : The date when the appointment was scheduled.
Age: Age of the patient.
Neighbourhood: The location of the appointment.
Scholarship: Whether the patient is enrolled in a welfare program (True or False).
Hipertension: Whether the patient has hypertension (True or False).
Diabetes: Whether the patient has diabetes (True or False).
Alcoholism: Whether the patient has a history of alcoholism (True or False).
Handcap: Whether the patient has a disability (True or False).
SMS_received: Number of SMS reminders sent to the patient.
No-show: Whether the patient showed up for the appointment (Yes or No).
