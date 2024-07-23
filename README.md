# 🏨 Home Sharing 🏨

👋 Welcome to our Software Development Project (SWP391) 👋

Video Demo: :point_right: 

## Table of Contents

- [Description](#description)

- [Preview Screenshot](#preview-screenshot)

- [Install and run](#install-and-run)

- [Technology](#technology)

- [Functional requirements](#functional-requirements)

- [Useful Resources](#useful-resources)

- [Contributors](#contributors)

- [Learn More](#learn-more)

- [Reference](#reference)

- [License & Copyright](#license--copyright)

## Description

- This web application is ...

## Preview Screenshot



## Install and run

### Required

- Open source code with IntelliJ IDE
- Installed JDK verison 11.x or above
- Installed Tomcat server version 8.5.x or higher and below version 10
- Installed Microsoft SQL Server Management Studio 18 and run the attached project script file in the source code folder
- Installed NodeJS Latest Version and SASS

### Install
1. Clone the source code to your computer and open the source code with Apache Netbeans
2. The library is configured by adding the jar file to the library with Java With Ant
3. Select Runs/Debug configuration
4. Select Add New Configuration
5. Select Tomcat Server Local version
6. In the Server tab, in the Application server section, link to the folder where Tomcat is installed
7. In the Server tab, in the JRE section, link to the folder where the JDK is installed
8. On the Deployment tab, click Add, select Artifact and select HappyHostel:war
9. Also in the Deployment tab, scroll down to see the Application context item is currently "/HappyHostel_war", delete "_war" and click Apply
10. In the project's Apache Netbeans window, open Terminal with Command Prompt
11. Run command ``` sass --watch src/main/webapp/assets/scss:src/main/webapp/assets/css ``` to build SCSS files into CSS files to display styles for pages

### Run
1. Click run to let IntelliJ turn on tomcat, build the project into a .war file and deploy it to the server
2. The web will automatically be turned on in the selected default browser or type "http://localhost:8080/SWP391_HomeSharing/"

## Technology

**1. Frontend**

- HTML, CSS, Javascript, Bootstrap, jQuery
- Font awesome
- JSP - JavaServer Pages
- JSTL - JSP Standard Tag Library
- ...

**2. Backend**

- Servlets - a Java programming language class that is used to extend the capabilities of servers that host applications accessed by means of a request-response programming model
- JDBC - Java Database Connectivity - a Java API to connect and execute the query with the database

**3. Database**

- Microsoft SQL Server - a relational model database server produced by Microsoft

**4. Other Technologies**

- Design pattern: MVC2

**5. Tool**

- Apache Netbeans 
- Java JDK 8
- Apache Tomcat 8.5.29
- Visual Studio Code
- Microsoft SQL Server Management Studio 18

**6.Libraries**

- Lombok
- JSTL
- sqljdbc4
