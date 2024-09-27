# DAN API TEST USING POSTMAN

## Introduction
This template guides you through CRUD operations (GET, POST, PUT, DELETE) to test the API request for all the DAN modules.

## How to use this template
### 1. Send requests
RESTful APIs allow you to perform CRUD operations using the POST, GET, PUT, and DELETE HTTP methods.
This collection contains each of these request types. Open each request and click "Send" to see what happens.

### 2. View responses
Observe the response tab for status code (200 OK), response time, and size. Once you request the API, you can also expect the responses in the body tab, where you can view the responses in different predefined structures like Pretty, Raw, Preview etc.

## How to view this template
### 1. Viewing in Postman
    - Open Postman.
    - Click on the Import button (usually located in the top left corner).
    - Select the Upload Files tab and choose the JSON file you exported.
    - Click Open. Postman will create a collection with the same structure as in the JSON file.

### 2. Viewing in a Text Editor
You can view this template or JSON file using any text editor  (like Notepad, Sublime Text, VS Code, etc.) to view the raw JSON structure. This can be helpful if you want to see the underlying data.

### 3. Using JSON Viewers
There are various online JSON viewers that can format the JSON data for easier reading. Some popular options include:

    - JSON Formatter & Validator
    - JSONLint

## Modules
- Auth
- User
- Category
- Account
- Customer
- Application
- Application Form Field
- Comment
- Notification
- Form
- Form Template
- Form Template Field
- Line

## Conclusion
This template contains the API requests for all the above modules to test whether the response is responded back successfully or not.

## Points to note
- Here, I have tested the API using the local serve(localhost).
- There are some parent tables that can store, update and delete its parent table.
- Also, Please log in before testing any other modules. Otherwise, you might get unauthorized response.


