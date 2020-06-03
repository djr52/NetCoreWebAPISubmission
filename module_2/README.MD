# How to Design a Database: Crash Course
## Description
In this module you learn relational database terminology, relationships, and concepts such as normalization.  You will use your knowledge to develop fundamental documentation for your project such as Entity Relationship Diagrams, Database Schema Diagrams, and a Data Dictionary.
## Topics
- Terms: Database Server, Database, Table, Field, SQL, Query
- Relationships: one-to-one, one-to-many, and many-to-many
- Normalization

## Unit Content
### Video(s)
1.  [Instructor Video - Database Crash Course](https://youtu.be/Xj0UlRhyWE4)
### Reading(s)
1. [How to create an ERD/DRD diagram](https://www.guru99.com/er-diagram-tutorial-dbms.html)
2. [How to create a data dictionary (DD)](https://medium.com/@leapingllamas/data-dictionary-a-how-to-and-best-practices-a09a685dcd61)
## Hands On
Create an entity relationship diagram (ERD/DERD), and (DD) data dictionary to support the business requirements described below.    
#### Please upload the ERD, and DD you create here.
### Project Module Service Specifications
#### User Management
- Purpose: The users that are members of the school
- Fields: Username, Password, Email, Status, System Role ID, Created Date, Updated Date
- BREAD Queries Requirements
  - **B** rowsing all users
  - **R** etrieving one user
  - **E** diting one user
  - **D** eleting one user
#### Course Management
- Purpose: The courses students take e.g. title, description and content
- Fields: Course Title, Description, Created Date, Updated Date
- BREAD Queries Requirements
  - **B** rowsing all courses
  - **R** etrieving one course
  - **E** diting one Course
  - **D** eleting one courses
####Course Assignment Management
- Purpose: Allowing assignments to be added to courses
- Fields: Assignment Title, Description, Course ID
- BREAD Queries Requirements
  - **B** rowsing all course Assignments
  - **R** etrieving one course Assignment
  - **E** diting one Course Assignment
  - **D** eleting one courses Assignment
#### Course Section Management
- Purpose: Allowing sections to be created to enroll teachers and students in
- Fields: Course ID, Start Date, End Date, Created Date, Updated Date
- BREAD Queries Requirements
  - **B** rowsing all course sections
  - **R** etrieving one course section
  - **E** diting one course section
  - **D** eleting one courses section
#### Section Enrollment Management
- Purpose: Allowing students and teachers to be assigned to courses
- Fields: Section ID, User ID, Created Date, Updated Date
- End Date
- BREAD Queries Requirements
  - **B** rowsing all course sections
  - **R** etrieving one course section
  - **E** diting one course section
  - **D** eleting one courses section
#### Section Assignment Submission Management
- Purpose: Allowing assignments to be submitted in a section and graded
- Fields: Section ID, Assignment ID, User ID, Submission Text, Score, Created Date, Updated Date
- BREAD Queries Requirements
  - **B** rowsing all assignments in a section
  - **R** etrieving one assignment submission in a section
  - **E** diting one assignment submission in a section
  - **D** eleting one assignment submission in section

