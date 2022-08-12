# Ruby on Rails Engineer Coding Assessment

The purpose of this exercise is to give you a chance to demonstrate your
problem solving and coding skills. The exercise is split into two sections:
first you will complete the tasks below in a live interview;
after that, you will be asked some questions to discuss your
solution and try to add to it. This is primarily an API exercise so we
can see how you deal with Ruby on Rails architecture, controllers, models, background jobs, etc.

## The tasks

Write a Ruby on Rails API that:

- Receives a .csv`*` file in Base64 format through an endpoint
- Through a background job, process that .csv file, converting all of its structures to database records – i.e., when the .csv is received on the RoB back-end, the application creates an ActiveJob that is processed later.
- Attach the .csv file received to the corresponding model
- Have a new endpoint that returns the information that has been stored.

`*` .csv file can be found in `files/EXAMPLE_1.csv`.

Optional:

These small extensions are optional but will be considered if you choose to implement them.

- Allow the submission of multiple .csv files in the same request, creating different back-ground jobs for each of these .csv files.
- After the .csv is processed and database records are created, send an email notification using ActionMailer.
- (Only for Senior roles) Receives a second .csv`**` file in Base64 through a different endpoint
- (Only for Senior roles) Through a background job, process that .csv file, converting all of its structures to database records – i.e., when the .csv is received on the RoB back-end, the application creates an ActiveJob that is processed later. This file contains references to elements in the first .csv file.

`**` .csv file can be found in `files/EXAMPLE_2.csv`.

## What we are looking for

- Good understanding of OOP principles
- Deep understanding of REST APIs
- Good knowledge of MVC pattern in a RoR app
- Good use of routes, controllers, models, DB migrations, background jobs in a RoR app
- Problem solving skills applied to a coding problem
