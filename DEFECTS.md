# Defects
***
The following defects were found while testing the Paylocity Challenge Benefit Dashboard
***
##### ID: 001
##### Summary: Employee First Name and Last Name labels are incorrect
##### Description: Employee First Name and Last Name labels are located in the wrong position in the dashboard
##### Severity: High 

##### Preconditions: Log-in using valid credentials
##### Test Data: Username: TestUser19, Password: RMU!+3D^s74/

##### Steps to reproduce:
1. Log-in using the test data provided
2. On the "Paylocity Benefit Dashboard" page, click the "Add Employee" button
3. Enter "First Name" in the "First Name" field
4. Enter "Last Name" in the "Last Name" field
5. Click the "Add" button

##### Actual Results: Last Name and First Name label in the table columnsare misplaced.

##### Expected Result: First Name label should be switched with the Last Name label.

##### Screenshots:
![paylocity1](https://user-images.githubusercontent.com/65917569/126861102-355bbd58-2ea1-44fc-b36a-dbab8b0fd4de.jpg)



##### ID: 002
##### Summary: Special Characters are allowed when adding new employees.
##### Description: Special Characters are allowed in the "First Name" and "Last Name" when adding new employees.
##### Severity:High 

##### Preconditions: Log-in using valid credentials.
##### Test Data: Username: TestUser19, Password: RMU!+3D^s74/

##### Steps to reproduce:
1. Log-in using the test data provided.
2. On the "Paylocity Benefits Dashboard" page, click the "Add Employee" button.
3. Enter special characters in the "First Name" field.
4. Enter special characters in the "Last Name" field.
5. Click the "Add" button.

##### Actual Results: Special characters are allowed to be submitted in the add employee form, resulting in invalid data.

##### Expected Result: Special characters should not be allowed to be submitted in the add employee form. 

##### Screenshots:
![paylocity2](https://user-images.githubusercontent.com/65917569/126861265-bbe6ff2b-461e-43a9-aea7-14ab536d5eb0.jpg)


##### ID: 003
##### Summary: Paylocity Benefit Dashboard is not designed/fitted for mobile screens.
##### Description: The dashboard does not line up with mobile screens. 
##### Severity: Low

##### Preconditions: Log-in using valid credentials.
##### Test Data: Username: TestUser19, Password: RMU!+3D^s74/

##### Steps to reproduce:
1. Using a mobile device, log-in using the test data provided. 

##### Actual Results: The size of the dashboard does match the screen size, therefore the outline of the dashboard is smaller than the dashboard displaying a line in the middle of the dashboard. 

##### Expected Result: The outline of the dashboard should match the size of the dashboard displayed on the screen. 

##### Screenshots:
![paylocity3 1](https://user-images.githubusercontent.com/65917569/126879824-6aa5a384-c637-4c35-bea8-be3b45c9dbcd.jpg)
![paylocity3 2](https://user-images.githubusercontent.com/65917569/126879829-a4e70199-8f25-4310-bc25-9c8717d2a6b9.jpg)
![paylocity3 3](https://user-images.githubusercontent.com/65917569/126879830-bc01dfa8-d86f-4632-872e-84853d34614e.jpg)
![paylocity3 4](https://user-images.githubusercontent.com/65917569/126879834-188ca062-8287-49cd-9e2e-419131ee7ef3.jpg)
![paylocity3 5](https://user-images.githubusercontent.com/65917569/126879840-a3a77130-4439-431a-a726-72d3fd78f0f2.jpg)
![paylocity3 6](https://user-images.githubusercontent.com/65917569/126879844-b5f3c304-1528-4136-ac26-9963d6d05a62.jpg)


##### ID: 004
##### Summary: No error/warning message when the user types in wrong data in the add employee form.
##### Description: A error/warning message should be displayed when user is adding wrong data. 
##### Severity: Low

##### Preconditions: Log-in using valid credentials.
##### Test Data: Username: TestUser19, Password: RMU!+3D^s74/

##### Steps to reproduce:
1. Log-in using the test data provided
2. On the "Paylocity Benefit Dashboard" page, click the "Add Employee" button
3. Enter long characters in the "First Name" field.
4. Enter long characters in the "Last Name" field.
5. Enter characters in the "Dependent" field. 
6. Click the "Add" button. 

##### Actual Results: The data entered does not add. 

##### Expected Result: An error/warning message should be displayed showing what is wrong with the data entered. 

##### Screenshots:
![paylocity4](https://user-images.githubusercontent.com/65917569/126880050-4d350811-8635-403b-884d-cf5e1b724a02.jpg)

