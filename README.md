0x00. AirBnB clone - The console

#0x01. Introduction
This team project is to build a clone [Airbnb] (https://www.airbnb.com/)

The console is a command interpreter to manage objects abstraction betweeen objects and how they are stored.

The console performs the following tasks 
* create a new object
* retrive an object from a file
* do operations on objects
* destroy an object

##Storage
All the classes are handled by the "storage" engine in the "filestorage"

##Installation
change to the "Airbnb" directory and run the command

##Execution
our shell works like this in interactive mode
$ ./console.py
(hbnb) help

Documented commands (type help <topic>):
========================================
EOF  help  quit

(hbnb) 
(hbnb) 
(hbnb) quit
$

It also works like this in none interactive mode
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
