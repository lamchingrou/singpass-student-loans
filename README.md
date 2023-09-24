# Singpass Student Loans 🤓

Borrow smart, not hard!

## Problem Statement

Many students face significant challenges when applying for a tuition loan through the university, which can be a time-consuming and frustrating process. The current process requires students to complete numerous forms and sign multiple documents, often resulting in delays and confusion. For example, when applying for loans, students would have to physically head down to the school premise to sign loan forms as a way to show the integrity of the student's signature. Additionally, students must also liaise with banks, which can add an extra layer of complexity and bureaucracy. For example, students would have to get approval from the banks to enable them as the paying account. This cumbersome process can deter students from pursuing financial assistance, ultimately limiting their access to education. By streamlining and simplifying the tuition loan application process, we aim to make higher education more accessible for all students.


## Proposed Solution

Singpass Student Loans is a one-stop platform that streamlines the process of loan application and approval for students, schools, and banks. The platform consolidates the capabilities of loan application and approval from three parties: students, schools, and banks. Its purpose is to make it easy for students to apply for school loans through their school, allowing them to focus on their education.

### User Workflow

1. Register student
2. Login as student
3. Apply for loan
4. Register school
5. Login as school
6. Request loan from bank on behalf of student
7. Login as bank
8. Approve school registration
9. Approve loan request

### Tech Stack

- Backend: Python, Flask
- Database: PostgreSQL RDS
- Deployment: Docker, AWS ECR, ECS, EC2
- Testing: Postman, Unittest

### Implemented AWS Architecture Diagram

The proposed solution is summarised in these slides:
[Google slides](https://docs.google.com/presentation/d/1LMR1xFt_Micqpjxa6BNI5EU_axyO9E81o4LGhPyWpyI/edit?usp=sharing)

[Insert diagram]

## Next Steps

Due to time constraints, the frontend components were not implemented in this solution. Given more time, I would complete the frontend components using React, connecting them to the backend API endpoints: 

### Planned AWS Architecture Diagram

[Insert diagram]

### Wireframe Design

You can view the wireframe design of the frontend components by pressing play in Figma: [Figma Link](https://www.figma.com/file/e6XEYZ9C0bzVNIXoLTN8x6/NDI-Wireframes?type=design&node-id=0%3A1&mode=design&t=HioERFttNWKGEF7L-1)

## Getting Started

Import the postman collection to call the API endpoints:

[Postman Collection](Postman Collection Link)

- The API endpoints are hosted on AWS by publishing the image on ECR, deploying the containers on ECS, and deploying the application on EC2 instances
- Postman scripts are included to automatically set and get the login tokens as environment variables

## Contact Information
Please contact me at crlam.2020@smu.edu.sg with any questions regarding this repo!
