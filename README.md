# ImplementingOOP
These are three JAVA projects which are just work of basic OOP implementations. These include Bank Application, EmailApp and StudentDatabase.

OVERVIEW OF THE BANK APPLICATION:

You are a backend developer and need to create an application to handle new customer banking account requests.

Your Application should do the following:
1. Read a .csv file of names, social security numbers, account type and initial deposit.
2. Use a proper data structure to hold these accounts.
3. Both saving and checking accounts share the following properties.
    deposit()
    transfer()
    withdraw()
    showInfo()

    > 11-digit account number(generated with the following process : 1 or 2 depending upon savings or checking,
 last two digits of SSN, unique  5-digit number, and a random 3-digit number)

4. Saving account-holders are given a security deposit box, identified by a 3-digit umber and accessed by a 4-digit code
5. Check account-holders are assigned a Debit card with 12-digit number and a 4-digit PIN
6. Both accounts will use an interface that determines the base interest-rate.
    > Saving accounts will use .25 point less than the base rate.
    > Checking accounts will use 15% of the base rate.
7. The ShowInfo method should reveal relevant account information as well as information specific to the Checking
Accounts or Savings Account.
account.

OVERVIEW OF THE EMAIL APPLICATION

Learning objectives:
1. Learn to develop a robust application architecture.
2. Learn when to use abstract classes and methods.
3. Use an interface API to receive information from a developer application.
4. Explore constructors deeper and use the super() keyword.
5. Explore access specifiers and when to use public, private and protected.
6. Read data from a file and store in an appropriate data structure.
7. Generate random numbers and work with String API.


Scenario: You are an IT Support Administrator Specialist and are
charged with the task of creating email accounts for new hires.

The application should do the following:
 Generate an email with the following syntax: firstname.lastname@department.company.com
 Determine the department (sales, development, accounting), if none leave blank
 Generate a random String for a password
 Have set methods to change the password, set the mailbox capacity, and define an alternate
email address
 Have get methods to display the name, email, and mailbox capacity


OVERVIEW OF THE Student Database Application
Scenario: You are a Database Administrator for a university and need to
create an application to manage student enrollments and balance.
Your application should do the following:
 Ask the user how many new students will be added to the database
 The user should be prompted to enter the name and year for each student
 The student should have a 5-digit unique ID, with the first number being their grade level
 A student can enroll in the following courses:
History 101
Mathematics 101
English 101
Chemistry 101
Computer Science 101
 Each course costs $600 to enroll
 The student should be able to view their balance and pay the tuition
 To see the status of the student, we should see their name, ID, courses enrolled, and balance
