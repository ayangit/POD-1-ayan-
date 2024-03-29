<div align="center">
<img src="https://github.com/Rohit-83/Audit-Management/blob/main/additionalAssets/logo.png?raw=true" width="100px" height="100px" vertical-align="middle">
<h1>CDE MFPE Project- Audit Management System</h1>
</div>

## Authors :
### POD 1: Cohort 12
<table>
  <tr>
      <td>
        <a href="#">Sachin Babasaheb Banker</a>
        </td>
      <td>
        <a href="#">Rohit Kumar</a>
        </td>
      <td>
        <a href="#">Abhishek Sharma</a>
        </td>
      <td>
        <a href="#">Ishita Kumari</a>
        </td>
      <td>
        <a href="#">Ayan Chattopadhyay</a>
        </td>
    </tr>
</table>

## Overview:

* ### How to run this project || Execution :
  #### --Dependencies on Other microsevices : ** You should have Java 8 or any version above that, maven, angular-cli - to run this project**
  Git clone the project first. Then follow the steps below :<br/>

  #### --Steps after getting the project in your local machine : 
    

  * #### 1> USING CMD OR TERMINAL<br/>
    * ##### 1.1> Open CMD or any terminal and go to the "ExecuteAll" folder<br/>
    * ##### 1.2> run the "ExecuteProject" batch file<br/>

  * #### 2> Another way is -- Just go to the "ExecuteAll" folder and run the "ExecuteProject" batch file<br/>

* ### User Flow of the Audit Management App : 
    * #### 1> Audit management Portal allows a member to Login. 
    * #### 2> Once successfully logged in, the member do the following operations: 
    * #### 3> Choose the audit type to view the list of audit checklist questions
    * #### 4> Let the project manager provide answers to the questions 
    * #### 5> Invoke the Audit Severity Microservice to determine the project execution status
    * #### 6> Display the result on the Web UI 
    * #### 7> The audit response detail along with the project execution status and remedial action duration should be saved to the database
    
* ### Internal connectivity of the Audit Management App and the Microservices : 
    ![Internal Connectivity of the App](additionalAssets/Flow.png)
    
* ### JWT Processing at Each Microservice : 
    ![JWT Processing at Each Microservice](additionalAssets/DetailedFlow.png)

* ### Preview Of The Application : 
    * #### Login Page -
    ![Login Screen](additionalAssets/Login.png)
    * #### Audit Checklist Page-
    ![Checklist Screen](additionalAssets/Checklist.png)
    * #### Audit Result Page -
    ![Audit Result Screen](additionalAssets/Result.png)
    * #### Incase of Error -
    ![Error Screen](additionalAssets/Error.png)
    ![Error Screen](additionalAssets/ErrorPage.png)
    
