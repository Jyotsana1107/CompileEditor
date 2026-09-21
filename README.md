# CompileEditor# Compile Editor

## Overview

**Compile Editor** is a browser-based online code editor and compiler practice project that allows users to write and execute programs in multiple programming languages.

The editor supports **C, C++, Python, and Java** by integrating external compilation/execution APIs. This project was created to practice building an interactive coding environment and working with external APIs from a web application.

---

## Supported Languages

* **C**
* **C++**
* **Python**
* **Java**

Users can select a programming language, write source code in the editor, and submit it for execution through the integrated external API.

---

## Features

* Multi-language code editor
* Support for C, C++, Python, and Java
* Code execution through external APIs
* User input support
* Display of program output
* Error/output handling
* Language selection
* Interactive coding interface
* Browser-based execution without requiring local compiler installation

---

## How It Works

The application connects the front-end code editor to an external code compilation/execution service.

```text id="7r4kq3"
User Writes Code
       ↓
Select Programming Language
       ↓
Provide Input
       ↓
Send Code to External API
       ↓
API Compiles / Executes Code
       ↓
Receive Response
       ↓
Display Output / Errors
```

---

## API Integration

A key part of the project is the use of **external APIs** to compile and execute code.

Instead of requiring a compiler or interpreter to be installed on the user's machine, the application sends the submitted source code and relevant information to the external execution service.

The API response is then processed by JavaScript and displayed in the editor interface.

This project provided practical experience with:

* API requests
* Sending structured data
* Handling API responses
* Asynchronous JavaScript
* Error handling
* Working with external services
* Connecting a front-end application to an external execution system

---

## Technologies Used

* **HTML5** — Application structure
* **CSS3** — Interface styling
* **JavaScript** — Editor logic, API communication, and DOM manipulation
* **External Compilation APIs** — Program execution

---

## JavaScript Concepts Practiced

The project helped strengthen understanding of:

* DOM manipulation
* Event listeners
* Functions
* Conditional logic
* Asynchronous programming
* Promises / API calls
* JSON request and response handling
* Error handling
* Dynamic content updates
* User input processing

---

## Project Flow

```text id="3q7p8n"
Code Editor
    │
    ├── Language Selection
    │
    ├── Source Code
    │
    └── Input
          ↓
     JavaScript
          ↓
   External API
          ↓
 ┌──────────────────┐
 │ Compilation /    │
 │ Program Execution│
 └──────────────────┘
          ↓
      API Response
          ↓
    Output / Error
```

---

## Project Structure

```text id="b6z8t2"
CompileEditor/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

> Adjust the file names above if the actual repository uses a different structure.

---

## How to Run

1. Clone or download the repository.
2. Open the project folder.
3. Open the application in a modern browser.
4. Select a programming language.
5. Write your code.
6. Provide input if required.
7. Run the program.
8. View the execution result in the output section.

Because the application relies on an external API, API availability and configuration are required for code execution.

---

## Key Learning Outcomes

Through this project, I practiced:

* Building an interactive code-editor interface
* Integrating external APIs
* Sending and receiving structured data
* Working with asynchronous JavaScript
* Handling API responses and errors
* Connecting front-end applications with external services
* Creating a multi-language programming environment

---

## Project Purpose

This project was created as a **practice and learning project** to explore how external APIs can extend the functionality of a browser-based application.

It provided hands-on experience in moving beyond static front-end applications and building an application that communicates with an external service to perform real-time code execution.

---

## Project Status

**Completed**

Created as part of my web development and programming practice portfolio.

---

## Author

**Jyotsana**

BCA | Data Analytics
Python | SQL | Excel | Power BI | JavaScript | Web Development
