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

### Inputs 
1) Input field 1  - Search for invoices with a given Invoice Owner
2) Dropdown that should be able to filter status a list of invoice
3) Input field 2 - Find a speficic invoice with a given invoiceId 
   
When the user doesn't have any input or clears the input, the input fields should be shown in the middle of the page

When the user starts typing into the Input field 1, make an Backend API call to fetch the results and display them in the form of something that is a not a table. The data should be cached.

Here are some of the items that you should take care of

* Add debounce (feel free to import from lodash). Make the API calls only if the user has typed 3 or more characters.
* If the user changes the "Filter" value in the dropdown and user has 3 or more characters in the input already, it should refresh the results.
* If the user clears the input or types less than three characters, clear the results and show the empty screen.

Consider all the states: initial, loading, error,... and inform the user about it.

## Backend Requirements

Write an backend API endpoint which stores and handles invoice data. The invoices contains: 

InvoiceId
InvoiceStatus 
InvoiceValue
InvoiceExpireDate
InvoiceOwner
InvoiceReceiver

Create two API Endpoints:
1.  "/api/search/invoices"
    - Gets all invoices for the specific account
2.  "/api/invoices/{invoiceId}" : 
    - Get a specific invoice id 
    
Here are some of the items that you should take care of

* Add Caching so that the same request is not called again.
* Write Swagger documentation with clear description, request, response & example for the endpoints
* Optional Bonus: Write API Flows for unit testing the API using any assertion library such as "SuperTest"

### BONUS ROUND

Replace the rest endpoint with GraphQL using apollo! 

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