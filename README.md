<h1>Testing Project for **Aeries**</h1>

| Date  | Description  | Author | Comments | 
|---|---|---|---|
| 28.05.2024 | Test Plan for version 1.0 | Madalina Bogdan|             |


1. Introduction

    1.1 Project objective
   
    1.2 Functionalities in scope

    1.3 Functionalities and tests out of scope

2. Test process

    2.1 Test planning
   
    2.2 Test analysis

    2.3 Test design

    2.4 Test implementation
   
    2.5 Test execution 

    2.6 Test closure

    2.7 Test monitoring and control
   
3. Test deliverables

    3.1 Test plan
   
    3.2 Test conditions

    3.3 Test cases

    3.4 Daily test summary reports
   
    3.5 Traceability matrix

    3.6 Test case results

    3.7 Bugs report

    3.8 Test completion report

## 1. Introduction ##

The Aeries Project aims to give students and parents with an information system where they may check grades, update contact information, and access any other school-provided information. 

This release will have restricted features. The software product's capacity will gradually increase as new functionalities are developed.

The below stories were created in Jira and describe the functional specifications of the "**Login**", "**Settings**" module, for which the final project is performed upon.

<p float="left">
  <img src="https://github.com/Madalina088/Aeries_Portal-Project/blob/main/1.Story.png" width="32%"/>
  <img src="https://github.com/Madalina088/Aeries_Portal-Project/blob/main/2.Story.png" width="33%"/>
  <img src="https://github.com/Madalina088/Aeries_Portal-Project/blob/main/3.Story.png" width="32%"/>
</p>

Here you can find the releases that were created for this project:

<img src="https://github.com/Madalina088/Aeries_Portal-Project/blob/main/Releases.png"/>

### 1.1	Project Objective ###

Before delivering the project to clients, we must identify, fix, and prevent defects in order to increase client confidence in the quality of the software. 
- Application under test: [Aeries Parent Portal](https://demo.aeries.net/ParentPortal/LoginParent.aspx?demo=True&user=student%40aeries.com&pwd=1234)
- Application documentation: 
[Suporting Documentation](https://support.aeries.com/support/home) - [API Documentation](https://support.aeries.com/support/solutions/articles/14000077926-aeries-api-full-documentation)

### 1.2 Functionalities in scope ###

- the following functionalities are going to be tested: 
Login Module, Settings Module: Change Password, Change E-mail, Configure Grade Alerts, Add New Student To Your Account, Log Out
- the features in scope for testing: Login Module, Settings Module: Change Password, Change E-mail
- testing types used: Functional Testing, Graphical User Interface(GUI)

### 1.3	 Functionalities and tests out of scope ###

- the features out of scope: Settings Module: Configure Grade Alerts, Add New Student To Your Account, Log Out
- non-functional testing like stress, load, and performance is beyond the scope of this project
- no QA support for mobile applications will be developed, just web applications will be tested
- automation testing is beyond scope

## 2.  Testing process ##

The test process was performed based on the standard test process as described below.
 	
### 2.1	 Test planning ### 

The Test Plan is designed to describe all details of testing for all the modules from the Aeries application.

Roles and responsibilities

| QA Engineer| Madalina Bogdan| Will test:  Login Module, Change Password, Change Email |
|---|---|---|

Entry criteria defined:

-	functional business specifications are defined
-	the test plan document is defined 
-	roles needed for the project are allocated

Exit criteria defined:

-	all test cases have been executed 
-	90% of tests are passed
-	no critical issues or bugs have an open status (all unresolved bugs have low priority and low severity)
-	update tests are 100% passed (update tests will not generate other new issues that impact the application)
-	complete functional coverage
-	regression tests are passed

Risks:
Project Risks: 

-	the complexity of the requirements and the large number of changes may cause delays
-	risks of instability, including crashes and disconnections
-	severe shortage of resources as employees 
-	short term for the Zephyr Squad trial

Product Risks:

-	potential impact on web page pagination on various screen sizes, including desktop, tablet, and mobile
-	design may not display correctly on the latest versions of Google Chrome, Mozilla Firefox, Apple Safari and Microsoft Edge
-	a new browser may not be supported
-	functionalities may not remain consistent across all tested browsers

### 2.2 Test analysis ### 

-	the testing process will be done based on the requirements for features: Login Module, Settings Module: Change Password, Change E-mail
-	we plan on running a full regression test on the current version to ensure no changes have affected system functionality

### 2.3 Test design ###

-	all the test cases are written and reviewed 
-	Functional test cases will be created in Zephyr Squad Test Management Tool with Jira Software Development Management Tool  
-	GUI test cases will be created in Zephyr Squad Test Management Tool with Jira Software Development Management Tool

### 2.4 Test implementation ###

The following elements are needed to be ready before the test execution phase begins:

-	all the test data is provided and reviewed including test data (email, password)
-	cycle summary was created, and test cases were added to the cycle summary 
-	test environment is up and running: [link to test environment](https://demo.aeries.net/ParentPortal/LoginParent.aspx?demo=True&user=student%40aeries.com&pwd=1234)
-	access to the test environment is given: username : parent@aeries.com | password: 1234
-	smoke test passed

  ### 2.5 Test execution ###

Test cases are executed on the created test Cycle summary: **(inserati aici numele cycle-ului pe care l-ati creat)**

-	the tests will be executed on the top 4 used browsers: Google Chrome, Mozilla Firefox, Apple Safari and Microsoft Edge. If time is available we will extend tests on the Opera Brave and Internet Explorer browsers
-	test cases will be executed based on the created Test Cycle Summary  <img src="https://github.com/Madalina088/Aeries_Portal-Project/blob/main/Cycle%20Summary.png"/>
-	bugs will be reported based on the failed tests

  ### 2.6 Test closure ###

-	at least 90% of tests are passed
-	no critical issues have open status
-	exploratory testing has been performed

### 2.7 Test monitoring and control ###

-	periodic reports (daily/weekly/bi-weekly) will be provided to track the present state of the testing process <img src="https://github.com/Madalina088/Aeries_Portal-Project/blob/main/Daily%20Test%20Execution%20Report.png" width="100%"/>

## 3.	Test deliverables ##

### 3.1 Test plan - [link to test plan]() ###
  
-	the Test Plan is designed to describe all the details of testing for the following features: Login Module, Settings Module: Change Password, Change E-mail
-	the plan identifies the items and features to be tested, the type of testing to be performed, the roles and responsibilities for the testing process, the risks associated with the plan, and the resources and schedule required to complete testing

### 3.2 Test conditions ###

-	we will use a test environment
-	the following test conditions can be found here: *[Test Conditions. ]()

### 3.3	Test cases ###

 - the test cases and the steps taken by the tester can be found here: *[Test Cases. ]()

### 3.4 Daily/Weekly/Bi-weekly test summary report ###

 - the report for the executed tests was generated after all the tests were run. Out of the total 17 tests executed, 14 were successfully executed, and 3 reported errors
   
<p float="left">
  <img src="https://github.com/Madalina088/Aeries_Portal-Project/blob/main/Test%20Execution%20by%20Cycle%201.png" width="32%"/>
  <img src="https://github.com/Madalina088/Aeries_Portal-Project/blob/main/Test%20Execution%20by%20Cycle%202.png" width="33%"/>
  <img src="https://github.com/Madalina088/Aeries_Portal-Project/blob/main/Test%20Execution%20by%20Cycle%203.png" width="32%"/>
</p>

### 3.5 Traceability matrix ###

- the traceability matrix was generated and can be found here::
![Traceability matrix!](https://github.com/Madalina088/Aeries_Portal-Project/blob/main/Traceability%20Matrix.png)

- for the first business requirement, 5 tests were run and passed  
- for the second business requirement, 7 tests were run, 5 passed, 2 failed, and I reported a bug
- for the third business requirement, 5 tests were run, 4 passed, 1 failed, and I reported a bug
- 
### 3.6 Test case results ###

 -  the test cases results can be found here: *[Test Cases Results. ]()

### 3.7 Bugs report ###

 Bugs have been created based on the failed tests. The complete bug reports can be found here:: *[Bugs Report ]()
 
 The following is a summary of the bugs that have been found
**(inserati o lista cu titlurile bug-urilor identificate impreuna cu prioritatea si severitatea fiecaruia)**   

### 3.8 Test completion report ###

 - link to test completion report <img src="" width="100%"/>
 - a total of 17 test cases were planned for execution, and all were executed.

### 3.9 Schedule ###

 - we have 4 days of testing
 - we have 17 functional and GUI tests
 - in order to finish the regression run we would need to run an ~ of 4 tests/day
