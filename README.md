## AirBnB clone part 1 - The console

### Description of the Project 
The AirBnB clone project is aimed at deploying on our server a simple copy of the [AirBnB](https://www.airbnb.com) website. The copy server will be tagged, hbnb.

To strat this project, we will be creating a console using python cmd module to work on the backend. This would be the first part of this project.

### Description of the Command Interpreter
The interface of the command interpreter is just like that of the Bash shell. It is however limited, in that it will only accept commands, specifically crafted for this AirBnB clone project.

This command line interpreter serves as the frontend of the web app where users can interact with the backend which was developed with python OOP programming.

Some of the commands available are:
- show
- create
- update
- destroy
- count

And as part of the implementation of the command line interpreter coupled with the backend and file storage system, the folowing actions can be performed:
-   Creating new objects (ex: a new User or a new Place)
-   Retrieving an object from a file, a database etc…
-   Doing operations on objects (count, compute stats, etc…)
-   Updating attributes of an object
-   Destroying an object  

### How to start it
Run the command below to start
```
$ ./console
```
### How to use it with example
1. Interactive mode:
```
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb) 
(hbnb) 
(hbnb) quit
$
```
2. Non-interactive mode:
```
$ echo "help" | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
$ cat test_help
help
$
$ cat test_help | ./console.py
(hbnb)

Documented commands (type help <topic>):
========================================
EOF  help  quit
(hbnb) 
$
```

### AUTHORS
1. Obinna Ogbu
2. Kabir Adebayo
