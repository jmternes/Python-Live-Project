# Python-Live-Project
## Introduction
As part of the curriculum at The Tech Academy, I worked as a developer for a two-week sprint - creating a web app using Django, a powerful Python-based web framework that follows the model-template-views pattern. The app was assigned to focus on a personal hobby - of which I have many - but I settled on movies, to create a movie review web application.

Working with a legacy codebase for the first time, I learned what it was like to work within a collaborative environment, complete with daily stand-up meetings and end-of-day reports. The project allowed me to complete both front-end and back-end user stories, both contributing to the final product that lets users fill a relational database with their own "Movie Review", then read, update, or delete said data; implementing [CRUD Functionality](#crud-functionality)

## CRUD Functionality
CRUD (an acronym for Create, Read, Update, Delete) refers to the four main functions inherent to relational databases. Implementing the four CRUD functions, users of my Live Python Project can create, read, update, and delete their selected data.


### • ***Create***
#### Story 2 - Create a model for the collection item you will be tracking and add the ability to create a new item.
I was tasked with *creating a model*, an objects manager to access the database, a model form for users to input data, a template for creating a new item, and a *views function* that renders the create page and saves the collection item to the database.

![](https://github.com/jmternes/Python-Live-Project/blob/main/Code-Snippets/Model%20Creation.png?raw=true)

![](https://github.com/jmternes/Python-Live-Project/blob/main/Code-Snippets/Views%20Function.png)

<hr>

### • ***Read***
#### Stories 3 and 4 - Display all items from the database | Create a details page that show the details of any single item, selected by the user
Next, I created a new HTML page to display items and added a *views function* to display the items from the database. For story 4, I added another template to display any single item from within the database, and another *views function* to send the single item to the template.

![](https://github.com/jmternes/Python-Live-Project/blob/main/Code-Snippets/Display%20Items%20in%20Database.png)

![](https://github.com/jmternes/Python-Live-Project/blob/main/Code-Snippets/Details%20of%20Single%20Item%20Within%20the%20Database.png)

<hr>

### • ***Update and Delete***
#### Story 5 - Edit and delete functions
To give users the ability to edit and delete their entries, I added an edit page to the templates, and a views function to *update* or *delete* any given item in the database.

![](https://github.com/jmternes/Python-Live-Project/blob/main/Code-Snippets/Edit%20an%20Item%20in%20the%20Database.png)

![](https://github.com/jmternes/Python-Live-Project/blob/main/Code-Snippets/Delete%20an%20Item%20in%20the%20Database.png)
