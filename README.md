# HospitalAPI💉👨‍⚕️

### Tech Stack Used :
* Core Java
* Spring Boot
* Hibernate
* MySQL database

### Data Flow
* Controller : 
  * In this Application 5 controllers are used
    * DoctorController
    * PatientController
    * StatusController
    * SymptomController
    * SpecialityController
* Service
  * In this Application 5 services are used
    * DoctorService
    * PatientService
    * StatusService
    * SymptomService
    * SpecialityService
* Dao
  * In this Application 5 repositories are used
    * DoctorDao
    * PatientDao
    * StatusDao
    * SymptomDao
    * SpecialityDao


### Project Summary
→ This project involves building a backend system for a platform that enables doctors to register their patients. The system provides APIs for adding a doctor, adding a patient and their symptom, and suggesting doctors based on the patient's symptom and location.

→ The database contains two entities: Doctor 👨‍⚕️ and Patient 😷. Doctors are identified by their name, city, email, phone number, and speciality. The city field can have only three values: Delhi, Noida, and Faridabad, while speciality can have four values: Orthopedic, Gynecology, Dermatology, and ENT specialist.

→ Patients are identified by their name, city, email, phone number, and symptom. The symptom field can have one of the following values: Arthritis, Back Pain, Tissue injuries, Dysmenorrhea, Skin infection, skin burn, and Ear pain.

→ The system provides validations for several fields, including name, city, email, and phone number.

→ The "Suggesting Doctors" API takes in a patient ID and returns a list of doctors based on the patient's symptom and location. The system ensures that only doctors with a speciality matching the patient's symptom are suggested. Additionally, the system handles edge cases where there are no doctors available in the patient's location or no doctors available for the patient's symptom in that location.

→ The system is built using the Spring Boot framework for core functionalities, and Hibernate is used for carrying out database operations. The API documentation is done using Swagger.

### The below video shows how the app works:

https://user-images.githubusercontent.com/112773191/234098852-492472b5-1ada-494d-848c-e9f81f76af56.mp4

### How operate this app:

* Install oracle java 17 or upgraded version
* Install any IDE like VScode or IntelliJ
* Clone this repository into your pc by using below command
```
git clone https://github.com/mahaveer3103/hospitalAPI
```
* Then you are good to go!
