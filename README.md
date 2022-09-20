# CriteriaBuilder

Step 1:- Create a database in mysql with name as "EMS"

Step 2:- Configure the application.yml file according to your database username and password

Step 3:- Run the SpringDataJpaSpecificationsApplication.java file

Step 4:- Open the Postman Api then follow below steps:

i) To insert employee details:-

        select Request as "POST"
        
        Enter the url:- http://localhost:8080/employees
        
        Enter the following in the body:-
        
        {
      
        "firstname":"yourfirstname",
        "lastname":"yourlastname",
        "department":"yourdepartment"
        }
        
        Then click on send.
        
ii) To fetch the employee details:- 
        
        select Request as "GET"
        
        Enter the url:- http://localhost:8080/employees
        
        Then click on send.
