You are expected to create a console application that would be used by our 
DEMO college to manage admission of current academic year.

1. Collecting Student Information
   a. The system should allow the worker to enter n number of students 
      who are providing their admissions details.
   b. A student is represented by the following attributes.
       
       1. First Name & Last Name
       2. Date of Birth
       3. Register Number - 
          e.g 2021KA123
       4. Course
       5. Admission Fees Amount Paid
       7. Mobile Number
       8. Admission Id
   c. Upon entering the student details application should automatically generate
      an admission id based the previous admission id allocated.
      a) Admissionn ID canot be entered by the user
      b) Consider admission id to start from 1001
2. Upon completing the admission entry
    a. User muse be prompted with 4 choices
        1- Display all students 
            Selecting this choice will display all the student details
            in a well formatted manner
        2. Show total admission fees paid
            Selecting option will show sum of all the admission fees paid
        3. Display students of a course
            Selecting this will allow the user to enter the course name and will
            display students who has choosen that course.
        4. Exit
            Selecting this option will exit the application
* Note the choices should be shown again after each selection for the user to
  choose the next option untill Option 4 is selected


*****************************THINGS TO REMEMBER********************************
1. Register number is expected to be unique thus system should consider
   that no stundet details are entered with same register number
2. Enter proper validation is applied for attributes like Name, Mobile number etc..
3. Fees enterd must be added with an additional GST of 18% while calculating total fees.
