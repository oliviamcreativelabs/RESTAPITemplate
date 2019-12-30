### BACKEND REST API/PYTHON/DJANGO (Advanced)

<!-- <img src="pydjango.jpeg" alt="Django REST API" width="150"/> -->
<hr>

#### I. STACK

 - Python 3.7
   - Application logic & tests
   - PEP-8 best practices (all lines max 79 chars & add doc.strings to functions)
   - Automated code linting

- Django 
  - Django Object Relational Mapper (ORM) 
    - Converts objects in API to rows in DB
  - Django Admin

- Django REST Framework
  - Built-in authentication
  - Viewsets to create structure of API/provide neccessary endpoints
  - Serializers to provide validation on all requests/convert JSON objects to Django db models

- Docker 
  - Isolates project dependencies from machine it's running on
  - Wraps deps in a single 'image' that can be used on any machine

- Travis CI
  - Automatically run linting & unit-tests
  - Runs a script everytime changes are made to code

- Postges 

#### II. TESTING

##### UNIT TESTS
- Unit tests shall check that our code works 
- Unit tests shall isolate specific code such as:
  - Functions
  - Classes
  - API endpoints

##### TESTING STAGES
       1. SETUP: Create sample database objects
       2. EXECUTION: Call the code
       3. ASSERTION: Check code does what it is supposed to do
    




