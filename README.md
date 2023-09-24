# Singpass-Student-Loans 🤓
Borrow smart, not hard!
Singpass Student Loans is a one-stop platform which consolidates the capabilities of loan application and approval from 3-parties: Students, Schools and Banks. It's purpose is to streamline and make it easy for students to apply for school loans via the school and allow them to focus on their education.

The problem statement, proposed solution and its benefits, planned aws architecture diagram, implemented aws architecture diagram, user workflow, and tech stack are outlined in the proposal slides.
[Google slides](https://docs.google.com/presentation/d/1LMR1xFt_Micqpjxa6BNI5EU_axyO9E81o4LGhPyWpyI/edit?usp=sharing)

Due to time constraints, the frontend components were not implemented in this solution. Given more time, I would complete the frontend components in this wireframe. Please press play in Figma to see how the frontend components connect to one another.
[Figma](https://www.figma.com/file/e6XEYZ9C0bzVNIXoLTN8x6/NDI-Wireframes?type=design&node-id=0%3A1&mode=design&t=HioERFttNWKGEF7L-1)

To run the solution,
1. Run docker
```
$ docker-compose build
$ docker-compose up -d
$ docker-compose run app
```

2. Import postman collection
[Postman Collection](https://raw.githubusercontent.com/your-username/your-repo-name/main/postman-collection.json)
You can call the API endpoints as-is. Postman scripts have been written to set and get the login tokens as environment variables

A sample workflow would be:
- register student
- login as student
- apply for loan
  
- register school

- login as bank
- bank approves school registration

- login as school
- school requests loan from bank on behalf of student

- login as bank
- bank approves the loan
