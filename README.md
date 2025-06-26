# CS-340-Module-Eight

# CS 340 Project Two – Grazioso Salvare Dashboard

# Overview

This repository contains the final products for Project Two of the CS 340 course. It includes the finished interactive MongoDB dashboard made using Dash and Plotly, as well as the CRUD Python module (AnimalShelter.py) that connects to the MongoDB backend. The program lets you see, filter, update, and delete records about animal shelter data from Grazioso Salvare.
Artifacts
•	dashboard.py: Main dashboard code built using Dash/Plotly.
•	Crud.py: Python module containing CRUD operations using PyMongo.
•	README.md: Reflection journal and technical documentation.

## Reflection Journal

# How do you write programs that are maintainable, readable, and adaptable?

I concentrated on producing code that follows clean coding concepts, such modular design, descriptive naming, docstrings, and separation of responsibilities, throughout this course, but particularly in Projects One and Two. The AnimalShelter class I made in Project One is a great example of a part that can be reused and kept up to date. I put all of the database interactions into one class so that any changes in the future, like updating the database credentials or adding support for new data types, could be done in one place without disrupting the dashboard logic.
The key benefits of operating this manner were that it was clear and that it could be used again. In Project Two, while I was making the Dash dashboard, I could easily access methods like read() or update() from the AnimalShelter class without having to worry about the lower-level database functionality. This modular method let me work on UI design and backend integration independently.
In the future, I can simply reuse or add to the AnimalShelter class to work with additional collections, or change it to work with other apps that require CRUD capability. It is a base I can use to create more complicated online or desktop apps.

# How do you approach a problem as a computer scientist?

As a computer scientist, I start by breaking the issue down into smaller, easier-to-handle pieces and figuring out what the most important functional and non-functional needs are. The goal of this project was to build a data dashboard that meets the demands of a particular animal sanctuary and lets users to CRUD operations and visual analytics.
I started by figuring out what the customer (Grazioso Salvare) wanted to accomplish. They wanted to see animals that met particular criteria (such dogs who were ready to be rescued), filter data, and update records as required. Using the AnimalShelter class, I generated user stories and linked them to backend functions. Then, I used Dash to build frontend parts that let users interact with them and manipulate them via dropdowns, sliders, and charts.
This project was more useful than previous courses since it used real-world data and let users engage with it. I will keep employing entity-relationship modeling, indexing methods, and user-centered design concepts in my database initiatives in the future. I also learnt how important it is to prepare the schema structure and develop CRUD APIs early on in the design process.

# What do computer scientists do, and why does it matter?

Computer scientists use technology to address issues, and they frequently do this by making systems that are efficient, scalable, and easy to manage. We do not only build code; we also come up with logic, architecture, and operations that turn abstract concepts into real solutions.
My work on this dashboard project shows how computer science may help organizations reach their objectives. Grazioso Salvare can make better decisions, use resources more efficiently, and take better care of animals since they can easily screen animals, see data patterns, and keep track of shelter records. Without these kinds of software tools, a lot of this labor would have to be done by hand, which is prone to mistakes and takes a long time.
In the end, computer scientists' work is important since it leads to new ideas in almost every discipline, as seen here in healthcare, education, rescue operations, and animal welfare.

# Conclusion

This project has helped me learn more about full-stack programming using databases, CRUD operations, and Python for data visualization. It has taught me how to make systems that are easy to use and can grow with my customers and employers. It has also showed me how important it is to write clean code, design in modules, and concentrate on the user while developing.

