# StudentDB #
## Description
Student Enrollment Form using jsonPowerDB v2.0
The project consists of a HTML form with input fields for Roll-No, Full-Name, Class, Birth-Date, Address and Enrollment-Date. The form also has three control buttons: Save, Update and Reset. The form uses JavaScript and jQuery to validate the input data and perform CRUD operations using JPDB API. The project demonstrates how to use JsonPowerDB for storing and retrieving data in a JSON format.


# Benefits of using JsonPowerDB
* JsonPowerDB is a Real-time, High Performance, Lightweight and Simple to Use, Rest API-based Multi-mode DBMS.
* JsonPowerDB has ready-to-use API for JSON document DB, RDBMS, Key-value DB, GeoSpatial DB and Time Series DB functionality.
* JPDB supports and advocates for true serverless and pluggable API development.
* JsonPowerDB is Schema-free, simple-to-use, Nimble and In-Memory database.
* It is built on top of one of the fastest and most real-time data indexing engines - PowerIndeX.
* It is a low-level (raw) form of data and is also human-readable.
* It helps developers in faster coding, which in turn reduces development costs.

# TECH STACK USED
* HTML
* CSS
* JAVASCRIPT 
* JsonPowerDB ( As Database)

# Screenshots:
<img src="/images/save_data_1.png">
<img src="./images/database.png">

# Illustrations:
* **UPDATE** : when student roll number is already present in database then student information is fetched from database and filled in respective feild then user can UPDATE student information 
* **SAVE** : If student roll number is not existed in database then we can fill other field and save in database
* **clear** : By this we can clear all field of form and with this except first field (roll-no) other field are disabled until user enter any roll number
* **Alert** : This website uses disposable Alter prompt using bootstrap

# HOW TO USE

* **Initially**
<img src="./images/Initial_home_page_look.png">

We need to enter a roll number 

If roll number is not valid 

<img src="./images/invalid_roll_number.png">

If roll number is valid and that roll number is existnig in database

<img src="./images/existing_student.png">

* **Fetching student data using roll number**
  If student already present in database, then all field filled with that student information
  
  <img src="./images/valid_roll_number.png">
  otherwise, other fields are enabled after user input roll number
  
* **Updation of student details**
  To update student details input roll number, and then we can update the student data
  
  <img src="./images/update_student_details.png">
  
  <img src="./images/alert_after_update.png">

* **Adding new student data**

  Enter new roll number and then all other fields are enabled and then after filling student information we can save this data into database only if input is valid
  
  <img src="./images/save_data_1.png">
  
  <img src="./images/alert_after_save_data.png">
  
 * **If input data is not valid**
 
   <img src="./images/invalid_details_1.png">
  
   <img src="./images/invalid_details_2.png">

    
# Scope of functionalities
* Create a new student enrollment record in the database
* Update an existing student enrollment record in the database
* Reset the form to its initial state
* Validate the input data and show error messages if any
* Display the data in the form based on the Roll-No entered by the user

  
  # Sources
  * Introduction to JsonPowerDB - V2.0 course  on https://careers.login2explore.com/
  * [JsonPowerDB YouTube Channel](https://www.youtube.com/@jsonpowerdb9811)
  * [Bootstrap](https://getbootstrap.com/docs/5.0/getting-started/introduction/) 


# Examples of use
* To create a new student enrollment record, enter a unique Roll-No and fill in the other details in the form. Then click on the Save button to store the data in the database.
* To update an existing student enrollment record, enter a Roll-No and modify the other details in the form. Then click on the Update button to update the data in the database.
* To reset the form, click on the Reset button to clear all the input fields and disable the other buttons.
 
# Release History
> 0.1.0
>> The first proper release
>> Completed the basic functionality of the form

> 0.0.1
>> Work in progress


 --------------------
