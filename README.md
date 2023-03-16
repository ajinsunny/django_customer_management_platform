Django Customer Management Platform (CRM)
=========================================

This is a web application built using the Django framework that allows businesses to manage their customer database. The application provides a user-friendly interface to add, edit, and view customer information such as name, email, phone number, and address. The application also provides a search feature to search for customers based on name or email address.

Features
--------

-   User-friendly interface to manage customer database
-   Add, edit, and view customer information
-   Search functionality to search for customers based on name or email address
-   Login and authentication system
-   User management system with different user roles
-   Responsive design for desktop and mobile devices

Getting Started
---------------

To get started with the project, follow these steps:

1.  Clone the repository to your local machine:

    `git clone https://github.com/ajinsunny/django_customer_management_platform.git`

2.  Create a virtual environment and activate it:

    `python3 -m venv env
    source env/bin/activate`

3.  Install the required packages:

    `pip install -r requirements.txt`

4.  Create the database tables:

    `python manage.py migrate`

5.  Create a superuser account:

    `python manage.py createsuperuser`

6.  Run the development server:

    `python manage.py runserver`

7.  Access the application by visiting `http://localhost:8000` in your web browser.

Usage
-----

Once you have the application up and running, you can perform the following actions:

-   Login to the application using your username and password.
-   Add customers by clicking on the "Add Customer" button on the home page.
-   Edit customer information by clicking on the "Edit" button next to the customer's name on the home page.
-   View customer information by clicking on the customer's name on the home page.
-   Search for customers by name or email address using the search box on the home page.

Contributing
------------

Contributions to the project are welcome. To contribute, follow these steps:

1.  Fork the repository.
2.  Create a new branch for your feature or bug fix:

    `git checkout -b feature-name-or-bug-fix`

3.  Make the necessary changes and commit the changes:

    `git commit -m "Commit message"`

4.  Push the changes to your fork:

    `git push origin feature-name-or-bug-fix`

5.  Create a pull request for your changes.

License
-------

This project is licensed under the MIT License. See the [LICENSE](https://chat.openai.com/chat/LICENSE) file
