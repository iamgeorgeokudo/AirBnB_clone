## 0x00. AirBnB clone - The console

## 0x00.Table of contents

* [Introduction](Introduction)
* [Installation](Installation)
* [Execution](Execution)
* [Testing](Testing)
* [Documentation](Documentation)
* [Authors](Authors)

## Introduction

This is a team project to build a clone of [AirBnB](https://www.airbnb.com/).

The console is a command interpreter to manage objects abstraction betweenobjects and how they are stored.

The console is expected to perform the following tasks:

* create a new object
* retrive an object from a file
* do operations on objects
* destroy an object

## Installation

```bash
git@github.com:iamgeorgeokudo/AirBnB_clone.git
```
Switch to the `AirBnB` directory and run:
```bash
./console.py
```
## Execution
In interactive mode


```bash
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

in Non-interactive mode

```bash
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

## Testing

All the tests are stored in the `tests` directory

## Documentation
* Modules:

```python
python3 -c 'print(__import__("my_module").__doc__)'
```

* Classes:

```python
python3 -c 'print(__import__("my_module").MyClass.__doc__)'
```

* Functions (inside and outside a class):

```python
python3 -c 'print(__import__("my_module").my_function.__doc__)'
```

and

```python
python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'
```


## Authors
<details>
	<summary>George Okudo</summary>
	<ul>
	<li><a href="https://www.github.com/iamgeorgeokudo">Github</a></li>
	<li><a href="mailto:okudog1@gmail.com">E-mail</a></li>
	</ul>
</details>
