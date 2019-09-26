# Strategic-ICT-eBusiness-Implementation

This project Considered Beaumont Hospital (Beaumont Hospital) which is one of the biggest academic teaching Hospital in Ireland. 
This Hospital uses Tradition Booking system which includes Mail, Email and Phone call. All the above method required human interaction 
to analyse the reference letter. This process takes days to reach out to the patient about appointment status through the different 
communication Medium. The process is a very time-consuming.To overcome this problem we are implementing a cloud-based system, through 
which it is possible to book an appointment using a Smartphone, web browser with the help of the internet.


## Approach Followed to Build Dataset 

1. Mock data is prepared for our project from Mockaroo which is based on 10 custom objects built in salesforce. 
2. Fields of all 10 tables are explained in detail under entity relationship heading in document. 
3. For the tables defined in our entity relationship diagram, we have created auto generated unique IDs in salesforce. 
4. Data present in other fields like Allergy (Wikipedia), Medicine Names (Pharmac.govt.nz), Department (Medicalcouncil.ie), 
5. Doctor Qualification (Medicalcouncil.ie) and Medical Council Number (Medicalcouncil.ie) was searched over the internet and real 
   values were inserted in this system. Fields for which Real like values were inserted in tables are as follows:
**Allergens** – List of common allergens are picked up from Wikipedia and then inserted in this field which is present in ‘Patient’        table.
**Medicine Name** – Different commonly used medicines are taken from pharmac.govt.nz and are used in ‘Medicine’ table under medicine                    name field.
**Doctor Qualification** – Few values are taken from medicalcouncil.ie which are used in field qualification in table ‘Doctor’
**Medical Council Number** – Medical council number is also taken from the same web site form where doctor qualification is taken. Here, we noticed that for every doctor (if you search doctor by any forename) the medical council number was of six digits. We have built our data for this field accordingly.

## Steps Taken to Build System

Steps followed to build this system are as follows:

1. All custom objects required for our system were built and represented as tabs. Default objects present in salesforce were hidden. 
   Relationship between objects was defined while creating these custom objects.
2. Data for these custom objects was prepared on mockaroo. Sample of real life data was used for few fields like medicine name, 
   allergy etc.
3. Third step was to build the reports and put them in a single dashboard. Reports like ‘Appointment Count by Doctor’, 
  ‘Appointment Count by Department’, ‘Number of Times a Medicine has been Prescribed’ and ‘Number of Appointments by Referral Status’
4. Registration web page was built for patients to register themselves if they are booking an appointment for the first time. 
   ID generated from this page will further be used to apply for an appointment through appointment request for web page.
5. Next, the appointment request form web page was created. This web page will be used by patients to apply for an appointment.
6. Registration Web Page was made public by assigning it a domain. Workflows for email alerts were also created. 

## Documents 

1. Project_Report_Online Appointment System for Public Hospitals_ICT.pdf  - Overall Report of the Project. 
2. ICT Project Flow Diagram.pdf
3. Slides -Project Layout Part 1.pptx   --- summary of the Layout.
4. Slides -Part 2 Implementation.pptx   --- Summary of the overall Implementation 
5. projectdescriptionsfsept18.pdf --- Requirment Document.
 
