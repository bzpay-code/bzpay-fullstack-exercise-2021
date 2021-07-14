# bzPay-fullstack-exercise-2021


# Introduction 

Thank you for your interest in working at bzPay, 
This challenge aims to help us evaluate your skill sets and where you are currently at within your career, so we can understand 
how you might fit within our team here at bzPay.


## Challenge

The exercise requires you to develop a `REST api in .NET 5`, which can be consumed with a Front end which is built in VueJS or ReactJS. 

### Setup

1. Create a public rep on your github, if you don't have a github account. Please sign up for one. 
2. Once completed to the best of your abilities, please commit your work and send through the link to the github project. 


### Requirements 

- Rest API in `.NET 5`, with a `React` or `VueJS` frontend, both of the applications can  be within the same repository if needed.
- While this API does not require Authentication, there is no harm in adding it ( `JWT` is preferred )
- You're welcome to use a SQLlite or TextFile.

Build a simple recipe book, that allows a user to submit a new recipe  with the following fields, 

    - Recipe  Name 
    - Vegitarian: Yes or No. 
    - Ingredients 
    - How to cook it. ( Text Field is fine ) 

The Rest API should support the following Requests 

- POST /api/recipe - Add new recipe 
- GET /api/recipe/:id - get recipe by ID.
- GET api/recipe - get all available recipes
- GET api/recipe - Search by Vegetarian or by recipe name i.e 'pasta'. 
- DELETE api/recipe/:id - Removes a recipe based on the ID.
- PUT api/recipe/:id - Update a recipe based on the ID. ( i.e. change to Vegetarian etc )

### Front End 

Build a front end application which has support for the following 

    - Adding a new recipe ( With the above paramaters ) 
    - Retrieving a list of recipes 
    - Viewing a Particular recipes 


The design is up to you, we're not expecting it to be a masterpiece and don't expect you to spend hours in this. 
You're welcome to use any UI kit of your choice if you choose to do so, such as `Bootstrap`, `Material UI` or `Tailwind CSS`



    
