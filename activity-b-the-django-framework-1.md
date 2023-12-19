---
description: Describing the framework in more detail.
---

# Activity B - The Django Framework

<div align="left">

<figure><img src=".gitbook/assets/image.png" alt=""><figcaption></figcaption></figure>

</div>

<div align="left">

<figure><img src=".gitbook/assets/image (42).png" alt=""><figcaption></figcaption></figure>

</div>

### Structural overview

The framework is created through command line instructions. The naming conventions must be adhered to, and the locations of folders and files must follow the pattern defined.

It’s a ‘batteries included’ framework, so called because of the range and scope of the features that the developer can use ‘out of the box.’

### The admin project app

The ‘create project’ command sets up the admin app that is used to control the features of the application, and the links between them

### DJANGO Apps – DRY, atomic, single responsibility.

The developer is encouraged to create separate ‘apps’ that will make up the whole application. For example, in an e-commerce application, separate apps would be provided for the catalogue of products and the shopping basket, and the checkout functions.

### DJANGO Database – db.sqlite3.

The SQLite database is a library that is included with Django to allow the use of a database without an external, separate server. It provides a relational database architecture, and it supports the use of transactions. It is often used to prototype an application before deployment to an enterprise server.

In Django, we create call models defining the type of data to be stored in tables and then initiate them in the database using migrations run from the command line.

### DJANGO Admin features.

Describe how localhost/8000/admin is used to access the administration dashboard.

Describe the use of the superuser account to manage the CRUD features of the database without the need for a UI. This is especially useful during development to provide ‘dummy’ or ‘test’ data that can be used to show the populated pages of the application.

### DJANGO User administration.

Describe the use of administration dashboard features to create new users, and then define their authorisation to use selected features of the application.
