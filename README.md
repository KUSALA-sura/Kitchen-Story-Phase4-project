# Kitchen-Story-Phase4-project
===================================
# Kitchen-Story

## Project Details
This project aims to design and develop an E-commerce website that lets people shop basic food items using Angular and Spring boot. It enables users to search and buy the available products. It was developed as a project of Phase-4 for the Full Stack Java Developer course.
 
## Product Backlog:
1.	Create database and tables.
2.	Initialize a Spring Boot project for the Back-End side.
3.	Create REST APIs with spring Data JPA Repositories 
4.	Create a new Angular project for the Front-End side.
5.	Create login and register pages.
6.	Show all products to the home page.
7.	Create a product details component.
8.	Search a product by a category.
9.	Search a product by a keyword.
10.	Add products to the cart.
11.	Show user’s cart.
12.	Remove a product from the cart.
13.	Update user account
14.	Create the admin view 
15.	Delete a product for the admin
16.	Add a new product for the admin
17.	Add bootstrap and font awesome to the components. 
18.	Debug and test the project.


## Technologies and tools Used
1.	Angular: used in the front-end side to build modern single-page applications
2.	Spring Boot: used in the back-end side to create the REST API and retrieve data from a database.
3.	HTML/CSS: to create and format the content of the pages.
4.	Bootstrap: to use some CSS and JavaScript designs.
5.	Maven: to manage the project.
6.	Visual Studio Code: to write and run the Angular code.
7.	IntelliJ: to write and run the Spring Boot code.
8.	phpMyAdmin: to administrate and manage the database manually.

## Flowcharts of The Application
Flow chart is for submit number 1 (some few changes were not added here)
![image](https://user-images.githubusercontent.com/64940728/125710594-6d31612d-85ff-4127-bd70-d601673d6e10.png)

## Core concepts used in the project. 
1.	Object-Oriented: used to create and model objects for users and their credentials.
2.	REST API: used to communicate between the back-end and the front-end sides.
3.	Data Access Object: to abstract and encapsulate all access to the data source.
4.	Object–Relational Mapping: to map the objects to the database.
5.	Databases: used to store and retrieve data.
6.	Data Sources: used to define a set of properties required to identify and access the database.
7.	Collections: used some collections such Arraylist to store collection of data. 
8.	Exception Handling: used to catch problems that arises in the code especially in I/O blocks.


## How to run the program
•	clone project

  o	clone git : git clone  https://github.com/KUSALA-sura/Kitchen-Story-Phase4-project
  
•	Import the “database\kitchen-story.sql” file to your database administration tool.

•	Go to “Back-end\Kitchen-Story\src\main\resources\application.properties” file, open it.

•	Edit some values of the database’ properties to be suit to your database administration tool.

•	Run the back end project as a maven project:

  o	cd to your project “Back-end\Kitchen-Story”
  
  o	mvn compile
  
  o	mvn exec:java -Dexec.mainClass=com.simplilearn.KitchenStory
  
  
•	Open another command line for the front-end part.

•	cd to your project “Front-end-end\Kitchen-Story”

•	install the following:

  o	npm install --save-dev
  
  o	npm install @angular/localize --save
  
  o	npm install bootstrap --save
  
  o	npm install font-awesome –save
  
  
•	Run using ng serve –open

•	It would be shown in http://localhost:4200/


## Screenshots
![Screenshot (228)](https://user-images.githubusercontent.com/85355371/165754998-889b91f5-d258-411f-9d7b-77b8158264cd.png)


