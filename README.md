# CS-340-Portfolio

SNHU CS 340 Client/Server Development Portfolio

## Project Two

This repository contains my completed CS 340 Project Two work. The project involved using MongoDB, Python, and dashboard components to create an interactive dashboard based on the animal data requirements provided by Grazioso Salvare.

The repository includes my final dashboard code and the README document from Project Two.

## Module Eight Journal Reflection

### How do you write programs that are maintainable, readable, and adaptable?

I write programs that are maintainable, readable, and adaptable by organizing the code into logical sections and separating different responsibilities. I try to use clear names and reusable functions so that the purpose of the code is easier to understand and changes can be made without having to rewrite the entire program.

The CRUD Python module from Project One was especially useful when I developed the Project Two dashboard. The CRUD module provided a separate way for the Python application to communicate with the MongoDB database. This allowed the database operations to remain separate from the dashboard interface and made the overall project easier to organize.

One advantage of using the CRUD module was that I could reuse database functionality instead of writing the same database operations again inside the dashboard. It also made troubleshooting easier because the database functionality and dashboard functionality were separated. If I needed to make a change to how information was retrieved from the database, I could work with the CRUD module instead of changing unrelated dashboard code.

I could use this CRUD Python module in future projects that need to communicate with MongoDB. For example, the same basic approach could be adapted for another dashboard, a data-management application, or another Python application that needs to create, read, update, or delete database records.

### How do you approach a problem as a computer scientist?

I approach a problem by first identifying the requirements and then breaking the larger problem into smaller tasks. For the Grazioso Salvare project, I first needed to understand what information was available in the database and what the client needed the dashboard to accomplish. I then worked on the database connection, CRUD functionality, dashboard components, filters, and visualizations.

This project differed from some of my previous assignments because it required several technologies and components to work together as one application. Instead of focusing on only one programming problem, I had to consider how MongoDB, Python, the CRUD module, the dashboard interface, and the data visualizations would work together to satisfy the client's requirements.

Testing and troubleshooting were also important parts of my approach. I needed to verify that the database operations returned the expected information and that the dashboard responded correctly when the user interacted with the controls. Breaking the project into smaller components made it easier to identify problems and make corrections.

In the future, I would use a similar process when creating databases for other clients. I would begin by understanding the client's requirements, examining the available data, identifying the information users need to access, and determining what database operations will be required. I would then design and test the database and application components before combining them into the final solution.

### What do computer scientists do, and why does it matter?

Computer scientists use programming, data, software, and problem-solving techniques to create solutions to real-world problems. Their work matters because organizations often have large amounts of information that can be difficult to manage and use effectively without appropriate technology.

My work on the Grazioso Salvare project demonstrates how computer science can help an organization work with its data more efficiently. The dashboard provides an interactive way to filter and view animal records rather than requiring users to manually search through database records. The table and visualizations also make the information easier to understand.

For a company such as Grazioso Salvare, this type of dashboard can help users find relevant animal information more quickly and reduce the amount of manual searching required. Filtering the records and displaying information visually can make it easier for users to identify useful records and locations and support their decision-making.

This project helped me understand that computer science involves more than writing code. It also involves understanding a client's requirements, working with data, designing a solution, testing the application, and creating software that provides practical value to the people who use it.

## Project Two Artifacts

* `ProjectTwoDashboard.ipynb` — Final Project Two dashboard code
* `CS340_ProjectTwo_README.docx` — Project Two README document
