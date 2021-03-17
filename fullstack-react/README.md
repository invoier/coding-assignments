## FullStack Developer Task

> View Invoices

This case study aims to assess how you approach a problem starting from the high level solution to the low level implementation details and code quality. You will not be penalized for asking questions, so don't hesitate to ask us if you need any clarification.

## The Task

You are required to build a fullstack single page application built with

* React.js
* TypeScript
* ExpressJs, REDIS
* Vanilla CSS, Sass, Styled Components or any other CSS-in-JS but no frameworks allowed.


## Frontend Requirements


## Backend Requirements

Write an backend API endpoint which stores and handles invoice data. The invoices contains: 

InvoiceStatus 
InvoiceValue
InvoiceExpireDate
InvoiceOwner
InvoiceReceiver

Create two API Endpoints:
1.  "/api/invoices"
    - Gets all invoices for the specific account
2.  "/api/invoices/{invoiceId}" : 
    - Get a specific invoice id 
    
Here are some of the items that you should take care of

* Add Caching so that the same request is not called again.
* Write Swagger documentation with clear description, request, response & example for the endpoints
* Optional Bonus: Write API Flows for unit testing the API using any assertion library such as "SuperTest"


## Criteria

Your work will be evaluated primarily on:

* Cleanliness of the code
* Use modern ES6+ syntax, async/await, elegant & readable code
* All the edgecases have been handled
* Typescript definitions, types, interfaces.
* `README.md` file explaining your high level solution and any decisions you made and the reasons behind them
* Testcases - How well you have tested your solution 

## How to submit your work

Create a public repo on Github and push your code on it. then share the link back with the team.