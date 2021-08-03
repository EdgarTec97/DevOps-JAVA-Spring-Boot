# spring boot microservices technical test

> Attending the Code Challenge
> A microservice is developed in spring boot using good design and coding practices,
> as the SOLID principles, the ATDD approach and different frameworks and libraries to optimize the work.
> As well as the implementation of asynchronous communication

## To use this repository
This project contains both the source code and a jar ready for execution, the source code
It is a spring boot application managed with maven, so it can be cloned as a project or run the application using the jar.
The application is self-contained, when it starts it creates an H2 database in memory.

The application has a graphical interface to view the API documentation and test the different endpoints.

A set of preubes has been developed to validate the different business rules,
all have been tested successfully, if any test fails the application does not compile.

All dependencies are described in the maven configuration file pom.xml

The default port is 8084 to avoid possible conflicts

### Previous requirements
java 8 or higher
Web navigator
optional
git
Development IDE

### Test the application through the web interface
1- Download as zip or clone the repository using git or any graphic assistant
   Once downloaded you can choose to run the jar and lift the application or recompile the project if you open it in your favorite IDE
   
2- Unzip the downloaded package.

3- To run the jar use the following command replacing $ HOME with the location where you have downloaded the java -jar project $ HOME / BANK_TECHNICAL_TEST / build / bank_transactions-0.0.1-SNAPSHOT.jar

4- Verify that you have started correctly, if you have problems, validate that the .jar file exists and correct the path

5- To see the documentation and test the endpoints, navigate to the following in your web browser url http: // localhost: 8084 / swagger-ui.html # / bank-transaction-controller
   You must replace localhost with the ip of the machine where you are running the jar.
   In the interface you will be able to see the different operations and by clicking on each one of them you will be able to see the details, such as the documentation
   test data with which you can make requests to validate the endpoints.
6- If you have decided to clone the project, you should open it in your favorite IDE.

7- If you want to test the APi, you can see the details and sample data of the requests in the graphic interface.


### Unit Test
A development based on the ATDD approach has been carried out, where all the test cases have been written to validate the different
business rules and acceptance criteria.
These tests are launched automatically.

You can find the details of the cases in /BANK_TECHNICAL_TEST/src/test/java/com/sotobotero/bank/BankBusinessRuleTests.java

### More Information
Edgar Castillo Vega
