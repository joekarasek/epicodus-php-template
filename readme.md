# _Template for PHP w/ Silex, Twig, and PHPUnit_

#### _A simple template, 2.12.2016_

### By _**Joseph Karasek**_

## Description

_This web app is designed to collect and display contact information for a number of people (basic address book). Contacts can be created, stored, deleted individually, or deleted as a group. The app was built using the micro-framework Silex, as well as Bootstrap._

_The goal of this code review is to show basic understanding and competency with php and the Silex micro-framework, including the ability to create, store, and delete instants of a given class._

_The code review will consider the following criteria.._
* Does your Contact object have all our ingredients? It should have a constructor, private properties, getters, setters, a save method, a getAll method and a deleteAll method.
* Were Twig template files used for all pages?
* Are Contacts being saved into the session and cleared correctly?
* Is your logic easy to understand?
* Did you use descriptive variable names?
* Does your code have proper indentation and spacing?
* Did you include a README with a description of the program, setup instructions, a copyright, a license, and your name?
* Is the project tracked in Git, and did you regularly make commits with clear messages that finish the phrase "This commit will…"?

## Setup/Installation Requirements

1. _Fork and clone this repository from_ [gitHub](https://github.com/joekarasek/epicodus-php-address_book.git).
2. Navigate to the root directory of the project in which ever CLI shell you are using and run the command: __composer install__ .
3. Create a local server in the /web directory within the project folder using the command: __php -S localhost:8000__ (assuming you are using a mac).
4. Open the directory http://localhost:8000 in any standard web browser.

## Known Bugs

_This application is not fully designed and may have unknown bugs._

_Currently, instants of Contact are assigned a random 6 digit ID. There is a tiny chance that multiple contacts may share an ID, deleting one of those contacts will cause the first (in order of creation) contact with that ID to be deleted._

## Support and contact details

_If you have any questions, concerns, or feedback, please contact the author through_ [gitHub](https://github.com/joekarasek/epicodus-php-address_book.git).

## Technologies Used

_This web application was created using the_  [Silex micro-framework](http://silex.sensiolabs.org/)_, as well _[Twig](http://twig.sensiolabs.org/), a template engine for php.

### License

MIT License.

Copyright (c) 2016 **_Joseph Karasek_**
