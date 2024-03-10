# Project-Management-System---Assignment
Sirma Business Consulting -Assignment 
This is a simple project management system.

# Project Management System API

This is a RESTful API for a simple project management system built with Java, Spring Boot, and H2 database.

## Setup Instructions

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/Project_Management_System.git

2.**API Endpoints**
Create a Project

URL: /save

Method: POST

**Request Body:**
`{
  "id": 1,
  "name": "Project 1",
  "description": "Description of Project 1",
  "startDate": "2022-03-01",
  "endDate": "2022-03-31"
}`

**Get All Projects**
URL: /findAll
Method: GET

**Get a Project by ID**
URL: /findbyID/{id}
Method: GET

**Update a Project**
URL: /update/{id}
Method: PUT
Request Body: (Similar to create)

**Delete a Project**
URL: /deletebyID/{id}
Method: DELETE

3.**Dependencies**
Java 17
Spring Boot
H2 Database



Author
Rishant Puri Goswami

