# review-exercise

Exercise

For this exam, you are to create a database for the Sport Tournaments Association. An organization that manages soccer Events and Registrations.

Participants will go to the organization’s website to register. They will need to register to the system by entering their Name, Birth Date, Email Address, and Password.

The system must store and show the following information about Tournament: Name, Description, Address, Date, Registration Cost, Sport Type (football, tennis, etc.), Registration Close Date

A registration table must be used to store information regarding the individual registration, which includes payment information: Amount Paid, Payment Date, Event ID, Participant ID

In total, the database for this system must include only three tables.

Some business requirements that you must enforce are:

       Payments Payment date must always be the current system date
       Participants must be 16 years or older in order to register to any of these teams


Having this information in mind:


   Connect to the following database server:

   Server: INSTRUCTORIT

   User: ProfileUser

   Password: ProfileUser2019


Perform the activities listed below in order to create the database.

   All these activities must be saved in a single SQL Script file.

   The SQL Script file must be written in such a way that it can be run in a single execution. 

   Test your SQL Script before you deliver it.

   Finally, send the SQL Script via email to ejaime@ibtcollege.com


Read and follow the instructions carefully. 


1) Draw a quick logical database diagram to help you create the database. Remember, keep it simple and use the table and column naming conventions discussed in class.

2) Create a database called TOURNAMENTS_CA_[YOURNAME], e.g. TOURNAMENTS_CA_EDWARD.

3) Create a schema called Tournaments.

4) Create the three tables described above inside the Tournaments schema. Make decisions concerning CONSTRAINTS based on the business requirements.

5) Create a function to format a date as MONTH DAY, YEAR

6) Create store procedures to perform the registration to a tournament
