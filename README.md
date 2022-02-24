# amsspringdataSecurity:
project using spring boot framework with controllers, Actions, views and models. Manage data between views and integrate css style.

To fix it, First set the CRUD of article and provider then follow these steps:

#  1.	The Spring Boot & Spring Security Layer
    a.	Add dependencies to pom.xml file
    b.	Create User and Role entities
    c.	Create repositories for User and Roles entities
    d.	Add Configuration spring security files(2 files)
    e.	Add loginController.java
    f.	Add login/register views
    g.	Add roles to users from mysql database
    
#  2.	Template inheritance and protected access to some page using role.
    a.	Create home page after have been authenticated
    b.	See fragment thymleaf concept
    c.	Show authenticated usernames, roles, logout
    d.	Restrict access to certain pages for ADMIN role
    e.	Running the project
