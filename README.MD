Instructions to deploye HR Analytics application
Tools and technologies used:
Python, Flask and MySQL

How to set up the database and run the application
Below SQL Commands are used to create Database, table and insert Data in all three tables:


Description of each user story and how it is fulfilled


User Story 1: Filter and Display Active Employees by Role
As a user, I should be able to:
Filter employees by Role
Select a Location and view the average compensation for that location
View a bar chart comparing compensation across all locations
Toggle to include/exclude Inactive employees
View: Employee Name, Role, Location, and Compensation
User Story 2: Group Employees by Years of Experience
As a user, I should be able to:
View a count of employees in experience ranges (e.g., 0–1, 1–2, 2–5, etc.)
Optionally group breakdown by Location or Role
User Story 3: Simulate Compensation Increments
As a user, I should be able to:
Input a global fixed % increment
See updated compensation alongside the current compensation
Bonus: Apply custom % increments per Employee or per Location
User Story 4: Download Filtered Employee Data
As a user, I should be able to:
Export filtered employee data to a CSV file
CSV should include: Name, Role, Location, Experience, Compensation, Status
Reflect any applied incremented values

Below Step Needs to follow to run this application:
1. Download zip file from Github
2. extract it and open in VS Code
3. Run below command to see User stpry 1 outputs:
    python case1.py
    It display all employee records and bar chart. Select Location, Role as per your needs and see updated ressult below. also you can apply filter on inactive employees.
    It has export option to export data to a CSV file.
4. Run below commands to see output of user story 2
   python case2/py
   It displays aggregated summary data based on role and location. It has export option to export data to a CSV file.
5. Run below command to see output of user story 3:
   python case3.py
   it gives option to simulate compensation by gicing different compensation hike percentage from a selection input field.
   It gives current and updated compensation for all employees.

Optional: Add screenshots
Attached another file in repository with all application Screenshots
