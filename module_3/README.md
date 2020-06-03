# How to Design a REST API Web API
## Description
In this module you learn REST API terminology, the HTTP protocol and how to design an API using the Open API Specification (Swagger).  You will apply these concepts to develop documentation for your API that will be needed to guide the development of the project as you work through the course.
## Topics
- HTTP
- Message Formats (XML and JSON)
- Open API Spec
## Unit Content
### Video(s)
* [Module 3 Lecture](https://youtu.be/7lG-gc84vdI)
### Reading(s)
* [Main thing to read it says just about everything you need to know](https://restfulapi.net)
* [REST QUICK TIP OVERVIEW – Nice Summary of The Main Things to Consider](https://www.restapitutorial.com/lessons/restquicktips.html)
* [A nice summary of basic HTTP Request Methods](https://www.restapitutorial.com/lessons/httpmethods.html)
* [MA Good Summary of HTTP Protocol](https://www.tutorialspoint.com/http/http_quick_guide.htm)
* [How to make an Open API Spec document](https://app.swaggerhub.com/help/tutorials/openapi-3-tutorial)
* [How to design an API](https://hackernoon.com/restful-api-design-step-by-step-guide-2f2c9f9fcdbf)
* [XML Explained with Detailed References](https://www.w3schools.com/xml/xml_whatis.asp)
* [JSON Explained with Detailed References](https://www.w3schools.com/js/js_json_intro.asp)

## Hands-On
Create an Openm API Design Document using the [Swagger Editor - Click To Use](http://editor.swagger.io/) for Open API 3.0.  This spec will describe the REST API functionality that you need to expose your school database design as a REST API.  Include HTTP request methods and response codes.  You also need to create a definition of HTTP response codes for errors such as 404 Not Found and other common response codes that are sent when something goes wrong.
#### Please upload the Open API API yml file that you create to the learning management system.

### Project Module API Endpoint Requirements
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
- Fields: Section ID, User ID, Created Date, Updated Date, Start Date, End Date
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
