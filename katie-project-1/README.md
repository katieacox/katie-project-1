# project-1
Guidelines and requirements for Project 1

> ERS, or Employee Reimbursement System, is a full-stack web application that allows employees to submit requests for reimbursements for courses, events, and certifications. These requests can then be approved or rejected by the Finance Manager, while the employee is able to track the status of their requests.
You will be required to present a 5-10 minute demo of your application and its features.

## Purpose
The main purpose of this project is to continue working with Testing Automation using Selenium and Cucumber and to begin including some Application Management Tool (like Jira, Trello, GitHub Project Board) to track the status of your Testing and Development.

### Presentation date: October 19, 2022

## Requirements
- All required business rules from the [Project1 ERS.docx](https://github.com/220912-jwa/project-1/blob/main/Project1%20ERS.docx) must be implemented.  
  - (The ability for an employee to upload a document can be considered a stretch goal along with the other business rules listed below under Stretch Goals).
- All application data must be stored in an RDS.
  - Database must be in 3NF. 
- Your application should be as RESTful as possible (at minimum it must follow the restful endpoint naming conventions).
- You must write BDD tests using Cucumber and Selenium for all user stories. 

- Project must also have:
  - User input validation.
  - Unit Tests - goal of 70% test coverage
  - Styled web pages either with CSS or Bootstrap. (Don't go overboard).
  - Requirements Traceability Matrix
  - Test Case Document

- Create a public repository for your Project 1 (firstname_lastname_p1) in our GitHub Organization (220912-jwa). 

## MVPs
- A user (Employee or Finance Manager) can login to the app using their credentials
- A user (Employee) can submit a request for reimbursement
- A user (Employee) can see the status of their current and past reimbursements
- A user (Employee) can update their reimbursement request to include their grade/presentation
- A Finance Manager can view all reimbursement requests
- A Finance Manager can approve or reject reimbursement requests
- A Finance Manager can update the status of a reimbursement request once the Employee has submitted their grade/presentation

## Stretch Goals
- Ability to upload attachments
- Finance Manager can request additional information
- Employee can cancel the reimbursement request if the reimbursable amount is changed by the Finance Manager
- Auto-approval after a certain period of time
- Available reimbursement resets on the new year

## Tech Stack
- Java 8/11
- Apache Maven
- Selenium
- Cucumber
- PostgreSQL
- AWS RDS
- Javalin
- JUnit
- JDBC 
- JavaScript
- Fetch API
- Postman
- HTML
- CSS / Bootstrap
- Jira / GitHub / Trello
