This hospital management system was made in Apache Netbeans.
The database and the tables were created in MySQL command line client.

Steps to run this project
Import the given zip file in netbeans(import project Option)
Run the login.java file(//hospital management system/source packages/default package) and enter the username "hms" and password "admin"

	
The login pages comes first in which the admin has to login with the username as "hms" and the password is "admin"
After loging in the admin will get many different options 
first one will be add patient record which will take the data of the patient that will be stored in a database named as Project in the table Patient that should be made in the admins computer.
2nd Button (Add diagnosis information) using this button the diagnosis can be added by the doctor based on the symptoms and to provide the medicines.
3rd button(Full history of patient) will be used to see the full history of the patient 
it will show all the details of the patient like the name,address,symptoms,medicines etc.
4th button (Update patient record)will be used to update the record of the patient if by any chance a wrong data was previously entered.
5th buttom (Hospital information) will show the basic details of the project
6th button (log out) willbe used to getting back to the login page.

So basically the first add patient record will add the details to a database named "Project" which will have a table "Patient".
The diagnosis i.e. when the 2nd button is pressed the diagnosis is added in a table "patientreport" in the "Project" database which will be accessed by the other buttons.

