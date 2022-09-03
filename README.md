# Medical Appointment Analysis
## by Yusuff Adebayo

### Dataset Description 

This dataset is from [Kaggle](https://www.kaggle.com/joniarroba/noshowappointments) and it collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patients are included in each row.

The dataset consists of 14 variables as follows:
- **PatientId :** Unique identification of a patient
- **AppointmentID :** Unique identification of each appointment
- **Gender:** Male or Female
- **ScheduledDay:** The date on which appointment was scheduled
- **AppointmentDay:** The date on which pateint has to show-up for the appointment
- **Age:** How old the patient is
- **Neighbourhood:** Place where patient lives (where patient comes from to visit the doctor)
- **Scholarship:** Whether the patient is enrolled in Bolsa_Família, which is a social welfare program of the Government of Brazil
- **Hipertension:** Hypertension, also known as high blood pressure. Part of patient's medical history.
- **Diabetes:** Part of patient's medical history.
- **Alcoholism:** Drinking of alcohol that results in significant mental or physical health problems. Part of patient's medical history.
- **Handcap:** Handicap, part of patient's medical history.
- **SMS_received:** Frequent reminders of scheduled appointment.
- **No-show:** Whether the patient attended the appointment or not. 'Yes' means the patient did not attended the appointment

**NOTE:** Where there is 0 and 1 in the data entries: 
- **0 = False / No**
- **1 = True / Yes**

### This project seeks to provide answers to questions such as:
>- What are the general characteristics of the patients under consideration?
>- Patients that miss appointments, what do they have in common?
>- What is the proportion of those who fail to show up for their appointment?
>- Which neighbourhoods have the highest no-showing rate?
>- Is there any possibility that the patients with hypertension also have diabetes?
