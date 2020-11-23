Spring boot Learning.
Before You Start:

    1. What are Rest API’S, why it is used?
    
    2. What Is Server? Why we need a Server.
    
    3. Java
        a. Classes and Objects
        b. Interface
        c. Collection
        d. All operations with collections.
        e. Sorting Techniques
        f. Template
        g. Threading (If you have extra time)
	
    4. Basics Of MySQL.( CRUD Operations)


Installation:
MySQL Workbench
Spring Tool Suite Or Any Editor With Dependencies
Postman (Rest API Client)

----------------------------------------------------------------------------------------------------------------------------------------
1st:
1)What is Springboot:
https://www.youtube.com/watch?v=Ch163VfHtvA&list=PLsyeobzWxl7oA8QOlMtQsRT_I7Rx2hoX4
2)Spring Boot Start By Navin Reddy:
https://www.youtube.com/watch?v=35EQXmHKZYs&t=1346s

3) Spring Vs Springboot:
 https://www.baeldung.com/spring-vs-spring-boot

JPA:
1) https://en.wikibooks.org/wiki/Java_Persistence/What_is_JPA%3F
2) https://www.tutorialspoint.com/jpa/jpa_architecture.htm
3) https://www.tutorialspoint.com/jpa/jpa_orm_components.htm


Assignment:
Spring MySQL Connection With Ticket Booking:
https://www.youtube.com/watch?v=voA01jXkXtk&t=840s

----------------------------------------------------------------------------------------------------------------------------------------
2nd:
Second Week Mostly Focused On Database:

    1. CRUD Operations Of Tables
    2. SELECT
    3. SELECT DISTINCT
    4. WHERE, AND ,OR ,NOT
    5. ORDER BY
    6. UPDATE , DELETE
    7. SELECT MIN , MAX , TOP, Avg , COUNT ,SUM
    8. Like
    9. IN
10.JOINS
11. Group By
12.Foreign Key
13. Normalization of database

Assignment:
Create Table with student details  username, password, name,age.
Write Models,Services,Repositories and controller for login and signup with database.
For Signup:
Request: 	
{
	“userName”:”bond”,
	“password”:”1234”,
	“name”:”James Bond”,
	“age”:”25”
}
Response: 
{
	“status”:”Success”
}
		Or
{
	“status”:”Fail”
}
For Login:
Request:  
{
  “userName”:”bond”,
	“password”:”1234”
}



Response: 
{
  “status”:”Success”
}
		Or
{
  “status”:”Fail”
}

----------------------------------------------------------------------------------------------------------------------------------------
3rd:
1.What Is Pagination
https://dzone.com/articles/pagination-in-springboot-applications
https://www.baeldung.com/spring-data-jpa-pagination-sorting

Assignment:
Create two tables With foreign key relation:
    a. user_details_table(first name,last name,dob,age sallary)
    b. authentication_table (username, password)
In Signup process take data as first name, last name, dob , age , salary, username, password at a time and store in two different tables.
And
Write one request have a url: Ip address:8080/getUsers
Which gives list of users with sets of 5 users at a time.
Sort users by alphabetical order with first name.
Request : 
{
		“pageNumber”:”0”,
		“pageSize”:”5”
}
Response:
	[
		{
	    “firstname”:”james”,
	    “lastname”:”bond”,
	    “dob”:”12/12/2012”,
	    “age”:”25”,
	    “sallary”:”10000”
    },
    {
	    User 2
    },
    {
  		User 5
    }
  ]
  
------------------------------------------------------------------------------------------------------------------------------------------------
4th:
Learn advanced things.
You should learn about
    1. What is SES Service
    2. What is SMS Service 
    3. How to Deal with OTP with server.
    4. How to send SMS , Mails from server.
    5. JWT
    6. Password Encryption Decryption.
    7. How to stabilize database.  
    8. How to deploy server on AWS Virtual Machine.
    9. How to Dump database.
Assignment:
With previous code add following services.
    1. Get OTP before Signup
    2. Validate OTP
    3. Forgot Password
    4. Change Password
    5. Edit User Info.
    6. Delete User Account.


