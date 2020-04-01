# JWT AND IDENTITY
## Description
In this module you learn to secure your API by implementing user authentication and authorization using MS Identity and JavaScript Web Tokens (JWT).  You will be able to assign user roles and control the request types that roles are authorized to perform.
## Topics
- Implementing Identity in ASP.NET Core Project
- Creating Tables and Inserting Roles
- User Creation
- Big Picture
- About JWT
- JWT Configuration
- Protecting Endpoints
- Implementing Authentication
- Role-Based Authorization
## Hands On
Implement user authentication for your API and implement role-based authorization.  User should be assigned the role of authenticated user when they are created by default.  You will need to create an endpoint to assign a role of authenticated, staff, or admin to your user model.  You will need to add an endpoint for a user to view a section assignment they add, so they can view their score.  You will need to add an additional endpoint for editing the score of a section assignment, since only a staff or admin can edit the score.  Refer to the following permission matrix for the user authorization per role.
### Role Based Access Control (RBAC) Matrix Requirements
|   | **Anonymous** | **Authenticated** | **Staff** | **Admin** |
| --- | --- | --- | --- | --- |
| **Browse Courses** | X | X | X | X |
| **Retrieve Courses** | X | X | X | X |
| **Edit Courses** |   |   |   | X |
| **Add Courses** |   |   |   | X |
| **Delete Courses** |   |   |   | X |
| **Browse Sections** | X | X | X | X |
| **Retrieve Sections** | X | X | X | X |
| **Edit Sections** |   |   |   | X |
| **Add Sections** |   |   |   | X |
| **Delete Sections** |   |   |   | X |
| **Browse Enrollments** |   |   | X | X |
| **Retrieve Enrollments** |   |   | X | X |
| **Edit Enrollments** |   |   | X | X |
| **Add Enrollment** |   | X | X | X |
| **Delete Enrollment** |   |   | X | X |
| **Browse Assignments** | X | X | X | X |
| **Retrieve Assignments** | X | X | X | X |
| **Edit Assignments** |   |   | X | X |
| **Add Assignments to Course** |   |   | X | X |
| **Delete Assignments** |   |   | X | X |
| **Browse Section Assignment Submissions** |   | X | X | X |
| **Retrieve Section Assignment Submission** |   |   | X | X |
| **Edit Section Assignment submission** |   | X | X | X |
| **Add Section Assignment submission** |   | X | X | X |
| **Delete Section Assignment submission** |   | X | X | X |
| **Edit Assignment submission score** |   |   | X | X |
## Unit Content
### Video(s)
### Reading(s)