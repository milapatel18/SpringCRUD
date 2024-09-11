# SpringCRUD

# Objective
- Basic Template For Spring MVC projects
- Used for Hybris Learning and Further Considerations
- Native Spring Development
- Understande Core Acrchitecture of MVC and SS
- XML Based Configuration
- Java Based Configuration
- Admin and User Based Login View 
- Admin View all Users and ToDo Tasks. 
- User View Only Todo
- Google and Other Social Login Strategy

  
# Tools
- Spring MVC
- Spring Security
- JSP Bootstrap UI
- Authentication
- Authorization
- AOP
- Design Patterns
- Hibernate
- MySql
- Google Authentication
- Okta Authentication
- JUnit & Mockito
- TDD Approach


Todo Application Functions
Master Admin - 
 - Manage User
 - View User Specific Tasks
 - Filter Results
 - Manage Global Categories

User - 
 - Manage Task Categories
 - Manage Task Statuses
 - Manage Task based on Status

Data Model 
 - Users
     - First Name
     - Last Name
     - Created At
     - Updated At
     - Active Status
     - Profile Image
     - DOB
     - Email
     - User Type (Admin,User)
     - Password
     - id(Primary Key)
  
 - Category
     - Name
     - Type [ Global G, User Specific U ]
     - Created At
     - Updated At
     - Active Status
     - Logo (icon class name etc.. simple text 100)
     - User id(Foreign Key)
     - id(Primary Key)
  
 - Status
     - Name
     - Status code
     - Created At
     - Updated At
     - Active Status
     - Color
     - User id(Foreign Key)
     - id(Primary Key)
  
 - Tasks
     - Name
     - Description
     - Created At
     - Updated At
     - Start Date
     - End Date
     - timeInSecond (UI can provide hrs mins etc)
     - Status
     - User id(Foreign Key)
     - Task id(Foreign Key, for parent tasks)
     - id(Primary Key)
  
       




