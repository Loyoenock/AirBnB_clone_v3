# 0x05. AirBnB clone - RESTful API

**Python | Back-end | API | Webserver | Flask**

**Concepts**
For this project, we expect you to look at these concepts:

* [REST API](https://intranet.alxswe.com/concepts/45)
* [AirBnB clone](https://intranet.alxswe.com/concepts/74)

## Resources
**Read or watch:**

* [REST API concept page]
* [Learn REST: A RESTful Tutorial](https://www.restapitutorial.com/)
* [Designing a RESTful API with Python and Flask](https://blog.miguelgrinberg.com/post/designing-a-restful-api-with-python-and-flask)
* [HTTP access control (CORS)](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS)
* [Flask cheatsheet](https://s3.amazonaws.com/intranet-projects-files/holbertonschool-higher-level_programming+/301/flask_cheatsheet.pdf)
* [What are Flask Blueprints, exactly?](https://stackoverflow.com/questions/24420857/what-are-flask-blueprints-exactly)
* [Flask](https://palletsprojects.com/p/flask/)
* [Modular Applications with Blueprints](https://flask.palletsprojects.com/en/1.1.x/blueprints/)
* [Flask tests](https://flask.palletsprojects.com/en/1.1.x/testing/)
* [Flask-CORS](https://flask-cors.readthedocs.io/en/latest/)

## Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

## General

* What REST means
* What API means
* What CORS means
* What is an API
* What is a REST API
* What are other type of APIs
* Which is the HTTP method to retrieve resource(s)
* Which is the HTTP method to create a resource
* Which is the HTTP method to update resource
* Which is the HTTP method to delete resource
* How to request REST API

## Requirements

### Python Scripts

* Allowed editors: vi, vim, emacs
* All your files will be interpreted/compiled on Ubuntu 20.04 LTS using python3 (version 3.4.3)
* All your files should end with a new line
* The first line of all your files should be exactly #!/usr/bin/python3
* A README.md file, at the root of the folder of the project, is mandatory
* Your code should use the PEP 8 style (version 1.7)
* All your files must be executable
* The length of your files will be tested using wc
* All your modules should have documentation (python3 -c 'print(__import__("my_module").__doc__)')
* All your classes should have documentation (python3 -c 'print(__import__("my_module").MyClass.__doc__)')
* All your functions (inside and outside a class) should have documentation (python3 -c 'print(__import__("my_module").my_function.__doc__)' and python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)')
* A documentation is not a simple word, it’s a real sentence explaining what’s the purpose of the module, class or method (the length of it will be verified)

### Python Unit Tests

* Allowed editors: vi, vim, emacs
* All your files should end with a new line
* All your test files should be inside a folder tests
* You have to use the unittest module
* All your test files should be python files (extension: .py)
* All your test files and folders should start by test_
* Your file organization in the tests folder should be the same as your project: ex: for models/base_model.py, unit tests must be in: tests/test_models/test_base_model.py
* All your tests should be executed by using this command: python3 -m unittest discover tests
* You can also test file by file by using this command: python3 -m unittest tests/test_models/test_base_model.py
* We strongly encourage you to work together on test cases, so that you don’t miss any edge cases

### GitHub

**There should be one project repository per group. If you clone/fork/whatever a project repository with the same name before the second deadline, you risk a 0% score.**

### More Info

![REST-API](https://s3.amazonaws.com/alx-intranet.hbtn.io/uploads/medias/2020/9/02078cd7f0573885c85a225c7436584a5afea1f9.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUSBVO6H7D%2F20230731%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230731T004419Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=aa92cf29d8e34bc46dcb2b424a97bdde8a939bec17bfd7ebbf50ada5f55ecceb)

### Install Flask
```
$ pip3 install Flask
```

### Tasks

**[0. Restart from scratch!]**

No no no! We are already too far in the project to restart everything.

But once again, let’s work on a new codebase.

For this project you will fork this codebase:

* Update the repository name to AirBnB_clone_v3
* Update the README.md:
	* Add yourself as an author of the project
	* Add new information about your new contribution
	* Make it better!
* If you’re the owner of this codebase, create a new repository called AirBnB_clone_v3 and copy over all files from AirBnB_clone_v2

**Repo:**

* GitHub repository: AirBnB_clone_v3

