[Dives](https://app.revature.com/projectSprint/MySwoleMate%20100-21)
# Instructions #
Create 2 methods within the TraineeBLL class in the solution.

These 2 methods will do the following

Create a private method called HeightDisplay which takes in an int value. The HeightDisplay method will calculate the total int value of inches into feet and inches (so 67 value should return "5 ft. 7 in."). You will use a combination of operators and string concatenation.

Create another private method called PhoneDisplay which takes in a string value, and returns a string value with hyphens "-" in between the area code and phone number (1234567890 should return 123-456-7890)
You will then use these methods in order to store the HeightDisplay and PhoneDisplay properties within the TraineeViewModel. If you look at the TraineeBLL under the comments you will see where you need to apply these methods. 

For help, view the Data Types, Strings, and Operators videos for calculations. Also you will need to review the Loops video to traverse through each trainee that returns from the GetTrainees() method.

# SQL #
After watching the SQL videos, add the Workout table in the MySwoleMate database using SQL Server Management Studio.
You can either use SQL Queries or use the built-in options within SQL Server Management Studio.
Here is the Data Dictionary of the Workout Plan:
    - This is saved as a file in the Documentation folder

**Create a Foreign Key Relationship Between Trainee & Workout Tables**
To create a connection between the Workout Table and Trainee Table, you must create a Foreign Key Relationship between the Trainee table and Workout table.
Review the SQL Server - Creating Relationships video for review.

1. Create the Foreign Key/Primary Key relationship between both tables
    > The Foreign Key will be WorkoutID on the Trainee table.
    > The Primary Key will be the WorkoutID on the Workout table.
2. Using the Foreign Key Relationships window, set the INSERT And UPDATE Specification to Set to Null for Delete

# ER Diagram #
Instruction
You will now create an Entity Relationship Diagram (or Database Diagram) to add to the System Design Document.

The Entity Relationship Diagram provides the tables, properties, and relationships in a database.

You can use a modeling software such as Microsoft Visio or draw.io (www.draw.io) in order to create the diagrams.

Here is an example of an Entity Relationship Diagram:



This is a simple ERD of the AspNetUsers, AspNetUserRoles, and AspNetRoles tables for the ASP.NET Identity Security Framework. (don't worry if you don't have any experience with Identity right now, you will use it in the Level 300 projects!)

You are able to see where the relationships between the tables are including the column names for each table.

Primary Keys are noted with a yellow key, however you can use acronyms such as PK or FK in order to represent Primary Keys and Foreign Keys respectively.

If you haven't noticed, AspNetUserRoles table is a junction table, which represents a many-to-many relationship between Users and Roles. Since a User can be assigned multiple Roles, and a Role can be assigned to multiple Users, you will need to create a junction table to store that relationship.

You are tasked to create an Entity Relationship Diagram with the tables you just created for Trainees and Workouts including the relationship between them.

# Next #