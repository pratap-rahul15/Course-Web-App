# Course-Web-App

This repository hosts the code for my project, **CourseWebApp**," 
Organized into two **separate folders:** 
one for the **back-end** and one for the **front-end.**

The project uses **React JS library** for the **front-end technology**
& **Java Spring Boot Framework** for the **Back-end technology.**

**==========================================================================================**

This Course-Web-App project is capable of performing the  **C.R.U.D.** operation.

**- Add a Course (POST)**

**- Delete a Course (DELETE)**

**- Update a Course (PUT)**

**- View a Course (GET)**

**=============================================================================================================================**

In the **Back-end Folder**
==========================

Java Version Used **Java 17**

**I have used listed things in my **pom.xml** file**

-  **Maven** as the **dependency manager** to handle all my depenedencies in the project.

-  **spring-boot-starter-web** dependency to create the Web Application.

-  **spring-boot-starter-data-jpa** dependency to  to map the java objects to database tables(**MySQL**) and manage   
    **C.R.U.D. (Create, Read, Update, Delete) operations.**

- **mysql-connector-j** dependency which works as the **JDBC driver** to connect to the **MySQL** to fetch the data.

 **In application.properties I have mentioned listed things.**

  - Database Configuartion for MySQL which runs on **localhost:3307/course**
  
  - The DB(Table) created inside MySQL is named as **course**.

  **In the src folder I have created in total 4 packages**
  
  - **Controller Package** which has a file named **Course Controller** that acts as a **Controller or View** of
    my **Course-Web-App** project, it is directly responsible for **accepting the request** from the
    **User Interface (U.I)**.

 - **dao(Data Access Object)** Package which has a file named **CourseDAO** this layer acts an abstraction
     which provides feasiblity of **Data Mapping**, **C.R.U.D.** operation & **Interacation** with my DB **MySQL**.

 - **entities** Package which has a file named **Course** which acts as **Model** layer, it contains **POJOs (Plain Old Java 
     Objects)** which is responsible for **Java Objects Data Mapping** to the **DB** in which there are **3 attributes**
   
      a -  **id** which is a **primary key** of the table **course** in my DB.  

      b -  **title**

      c -  **description**

 -  **service** Package which has 2 file named **CourseService** & **CourseServiceImplementation** which acts as the 
    **Service layer(Bussiness Logic Layer)**
**===============================================================================================================================**

  In the **Front-end Folder**
  ==========================

  **Version Used**
  
  React Version Used **18.3.1**
  
  - "react-dom": **"^18.3.1"**
  
  - "react-router-dom": **"^6.23.0"**
  
  - "axios": **"^1.6.8**
  
**In the src folder I have created in total 8 sub-folders(Components)**

   -  **AboutMe.js** component contains the javascript code for the About Me, the developer detail page.

   -  **AddCourse.js** component contains the javascript code for the AddCourse page, where the user can eneter the **id, title & description** to add a new course to the 
          DB.

   -  **AllCourses.js** component contains the javascript code for the AllCourses page, where a user can view all the subject they currently have or added to the DB.    

   - **Course.js** component contains the javascript code for the Course page, where a user can delete the existing or newly added course from the DB.

   - **Headers.js** component contains the javascript code for the Headers page.

   - **Home.js** component contains the javascript code for the Home page.

   - **Menu.js** component contains the javascript code for the Menu page, it handles all the **routable** links of the my web application.

   - **ReachMe.js** component contains the javascript code for the ReachMe page, it contains the **Linkedln** & **E-mail Address** of mine, where anybody can reach me.

   **THANK YOU**
