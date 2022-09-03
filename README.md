# AirBnB Clone

<img src="https://codelabs.developers.google.com/static/codelabs/cloud-functions-python-http/img/a7aaf656b78050fd.png" width="400px"/>

## Resources
Read or watch:

* [cmd module](https://docs.python.org/3.8/library/cmd.html)
* [uuid module](https://docs.python.org/3.8/library/uuid.html)
* [datetime](https://docs.python.org/3.8/library/datetime.html)
* [unittest module](https://docs.python.org/3.8/library/unittest.html#module-unittest)
* [args/kwargs](https://yasoob.me/2013/08/04/args-and-kwargs-in-python-explained/)
* [Python test cheatsheet](https://www.pythonsheets.com/notes/python-tests.html)
* [Overview](https://www.youtube.com/watch?v=QTwmCB_AWqI)
* [The Console](https://www.youtube.com/watch?v=jeJwRB33YNg&feature=youtu.be)
* [ORM](https://www.youtube.com/watch?v=ZwCD8cNZk9U)
* [RESTful API](https://www.youtube.com/watch?v=LrQhULlFJdU)
* [unittest — Unit testing framework](https://docs.python.org/3.4/library/unittest.html#module-unittest)
* [Unit Tests in Python || Python Tutorial || Learn Python Programming](https://www.youtube.com/watch?v=1Lfv5tUGsn8)


## Description
This is the first phase of a four phase project, to create a basic clone of the AirBnB web app. In this first phase a basic console was created using the Cmd Python module, to manage the objects of the whole project, being able to implement the methods create, show, update, all, and destroy to the existing classes and subclasses.


## Environment
The console was developed in Ubuntu 20.04 LTS using python3 (version 3.9.7).

### Further information
For further information on python version, and documentation visit [python.org](https://www.python.org/).

## Requirements
Knowledge in python3, how to use a command line interpreter, a computer with Ubuntu 20.04, python3 and pep8 style corrector.

## Repo Contents
This repository contain the following files:

|   **File**   |   **Description**   |
| -------------- | --------------------- |
|AUTHORS | Contains info about authors of the project |
|base_model.py| Defines BaseModel class (parent class), and methods |
|user.py| Defines subclass User |
|amenity.py| Defines subclass Amenity |
|city.py| Defines subclass City |
|place.py| Defines subclass Place |
|review.py | Defines subclass Review |
|state.py | Defines subclass State |
|file_storage.py | Creates new instance of class, serializes and deserializes data |
|console.py | creates object, retrieves object from file, does operations on objects, updates attributes of object and destroys object |
|test_base_model.py | unittests for base_model |
|test_user.py | unittests for user |
|test_amenity.py | unittests for amenity |
|test_city.py | unittests for city |
|test_place.py | unittests for place |
|test_review.py | unittests for review |
|test_state.py | unittests for state |
|test_file_storage.py | unittests for file_storage |
|test_console.py | unittests for console |

## Usage

|   **Method**   |   **Description**   |
| -------------- | --------------------- |
|create | Creates object of given class |
|show | Prints the string representation of an instance based on the class name and id |
|all | Prints all string representation of all instances based or not on the class name |
|update | Updates an instance based on the class name and id by adding or updating attribute (save the change into the JSON file) |
|destroy| Deletes an instance based on the class name and id (save the change into the JSON file) |
|count| Retrieve the number of instances of a class |
|help| Prints information about specific command |
|quit/ EOF| Exit the program |



## Built with
python3 (3.9.7)

## Acknowledgements:
To all the peers(Cohort 3-2022) that contributed with their knowledge

## Authors
* [Omini Okoi](https://twitter.com/pridemyhero)
* [Aremu Oluwafunmilayo Patience](https://github.com/omience)
