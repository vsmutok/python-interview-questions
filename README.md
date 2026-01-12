# Python Interview Questions 🐍

### Python Basics Extended 🐍

#### Code Style
1. What is PEP 8 and why is it important?
2. What is a docstring in Python?
3. How many spaces should be used for indentation in Python according to PEP8, and why is consistent indentation important?
4. What are the differences between ruff and black in terms of functionality and usage?
5. Explain the purpose of type annotations in Python and provide an example function with type annotations.

#### Debugging
1. What is debugging, and why is it an essential skill for programmers?
2. Explain the purpose of using the print function for debugging. Provide an example scenario where this method is useful.
3. Describe how the Python Debugger (PDB) can be used for debugging. What are its advantages over using print statements?
4. What strategies can be used to debug loops and functions in Python?
5. What is the impact of long-running functions on the performance of a program?

#### Numbers
1. What is the difference between regular division (/) and integer division (//) in Python? Provide an example of each.
2. Explain the use of the modulus operator (%) in Python. How can it be used to determine if a number is even or odd?
3. How does Python handle large integers, and what are the potential limitations when working with very large numbers?
4. What does NaN stand for, and in what scenarios might it be used in Python? How can you check for NaN values in a list?
5. What is the significance of handling zero division in Python, and how can you prevent a ZeroDivisionError in your code?
6. Describe the use of the random module in Python. What are some common functions provided by this module, and how are they used?

#### Strings
1. What are escape characters in Python strings, and how are they used? Provide examples of \n, \t, \r, \", and \'.
2. Explain the use of the strip, lstrip, and rstrip methods in Python. How do they differ, and when would you use each one?
3. Describe the purpose of the count method in strings. How does it work, and what is a practical example of its usage?
4. How does the join method work in Python, and what are some common use cases? Provide an example.
5. What is string slicing in Python, and how can it be used to extract substrings? Provide an example using both positive and negative indices.
6. Explain the replace method in strings. How can it be used to replace multiple occurrences of a substring? Provide an example.

#### Functions
1. What are default values for function arguments in Python, and how are they used?
2. Explain the purpose and usage of *args and **kwargs in Python functions. How do they differ?
3. How do you define a function with type annotations in Python? Provide an example and explain its benefits.
4. Describe how you can use *args and **kwargs to create a function that can handle a variable number of positional and keyword arguments. Provide an example.

#### Loops
1. What are the break and continue statements used for in Python loops? Provide an example of each.
2. Explain the concept of an infinite loop. In what scenarios might you use an infinite loop, and how can you ensure it terminates correctly?
3. Describe how nested loops work in Python. What are some potential performance concerns with using nested loops, and how can you mitigate them?
4. Describe how nested loops work in Python. What are some potential performance concerns with using nested loops, and how can you mitigate them?

#### Type Conversion
1. How does Python automatically convert different data types to boolean values? Provide examples with numbers, strings, lists, and dictionaries.
2. Explain how to convert a string to an integer and a float in Python. What happens if the string cannot be converted to a number?
3. What does Python do when comparing different data types, such as integers and floats, or integers and booleans? Provide examples.
4. How does Python handle comparisons between lists and sets? Provide examples showing when lists or sets are considered equal or not.
5. Describe the use of the bool() function in Python. How can it be used to determine the truthiness of various data types?

#### Lists
1. What is the difference between the reverse method and slicing with [::-1] when reversing a list? Provide an example of each.
2. Explain the purpose and usage of the sort method in lists. How can you sort a list in descending order?
3. Describe the difference between the copy method and directly assigning one list to another variable. Why is using copy important?
4. What does the pop method do in a list? How does it differ when an index is provided versus when it is not?
5. How can you combine two lists in Python using both the + operator and the extend method? What is the key difference between these two approaches?
6. What are the functions min, max, sum, all, and any used for in the context of lists? Provide a brief explanation for each.
7. How can we create a tuple?
8. What are the data types and what is the difference between list and tuple, when to use them?

#### Dicts
1. What is a dictionary in Python, and what distinguishes it from other data structures?
2. Explain the difference between accessing a value in a dictionary using square brackets [] and the get method. Why might you choose one over the other?
3. Describe how you can update and delete elements in a dictionary.
4. What are the keys, values, and items methods in a dictionary? How do they differ, and when would you use each one?
5. What is a set in Python, and what distinguishes it from other data structures?
6. How do you create a set in Python, and what are the limitations on the elements that can be added to a set?
7. What is the purpose of the intersection() method in Python sets, and how does it differ from the union() method?

---

### Python Core 🐍

#### How to Solve GitHub Tasks
1. How do you clone a repository from GitHub?
2. What is a pull request and what is it used for?
3. How do you create Pull Requests on GitHub?

#### Mutable Immutable Types
1. What are mutable and immutable data types in Python?
2. How does mutability affect the performance of a program?
3. Give examples of mutable and immutable types in Python.
4. Why is it important to understand mutability when using dictionaries or sets?
5. What does the term id mean in Python, how is it used, and why is it important?
6. How is the Singleton pattern applied to Python, and what are examples of Singleton objects in Python?
7. What is the difference between is and ==?

#### List and Dict Comprehensions
1. How do dict comprehension, list comprehension and set comprehension work?
2. What are the benefits of using list comprehensions over traditional loops?
3. Can you give an example of a nested list comprehension?
4. What is faster in Python, list comprehension or creating a list using a regular loop?

#### Functions in Details
2. What is the scope of variables in a function?
3. What are local variables and global variables in Python?
4. Explain the difference between local and nonlocal variables in Python.
5. What is unpacking in Python, and how is it used in assignment?
6. Explain the concept of packing values in Python and provide examples.
7. What is the purpose of using the * operator in packing and unpacking?
8. What is closure in Python?

#### Decorators
1. What is a decorator in Python, and how does it function?
2. Is it possible to use several decorators for one function?
3. Is it possible to create a decorator from a class?
4. What is a closure, and how is it related to decorators?
5. How do you define a decorator that accepts parameters?
6. What is the purpose of using the functools.wraps decorator within a decorator function?
7. Discuss the potential issue with the order of decorators when applied to a function.

#### Classes
1. What is a class in Python?
2. How do you create an object in Python?
3. Explain the role of the __init__() method in a class.
4. What is the purpose of the self parameter in Python class methods?
5. How do you define methods in a class?
6. Explain the concept that "everything is an object" in Python, and provide examples.
7. Provide an example of a class with methods that perform calculations based on its attributes.
8. Describe a scenario where you might need to use multiple classes in a Python program.

#### Classes in Details
1. What is a @classmethod in Python, and how is it different from a regular method?
2. What is a @staticmethod in Python classes, and when would you use it?
3. Explain the differences between@classmethod and @staticmethod in Python classes.
4. What are instance attributes in Python classes, and how do they differ from class attributes?
5. What is the purpose of the __del__ method?
6. What are magic methods in Python classes, and why are they called "magic"?
7. Provide an example of using the __str__ magic method to define a string representation for a custom class in Python.
8. Що таке __slots__ в Python?

#### Iterators and Generators
1. What is an iterator in Python?
2. What is a generator, and how does it differ from an iterator or regular function?
3. How do you create a generator function?
4. How can you create an iterator from an iterable using the iter() functions?
5. Explain the purpose of the next() functions when working with iterators.
6. Can you use the __next__() and __iter__() methods interchangeably with the next() and iter() functions? Explain.
7. What is the role of the StopIteration error in iterator design, and when does it typically occur?
8. How does the yield keyword contribute to the functionality of generators, and what makes them memory-efficient?

#### Modules and Imports
1. What are modules and packages in Python?
2. What is a module in Python, and what purpose does it serve?
3. How do you import a module in Python?
4. What are the different types of imports?
5. What does the dir() function do, and how can it be used with modules?
6. Explain the role of the if __name__ == "__main__": statement in Python scripts.
7. What is the significance of the __init__.py file in a Python package?
8. What are some best practices for styling import statements in Python code?

#### OOP Single Inheritance
1. What is Object-Oriented Programming (OOP), and what are its main principles in Python?
2. What is single inheritance in Python?
3. How do you implement inheritance in Python classes, and what syntax is used to denote inheritance?
4. How do you access parent class members in a child class?
5. What is the purpose of the super() function in Python inheritance, and how is it used?
6. Describe the isinstance() function in Python and provide an example of its usage.
7. Explain the issubclass() function in Python and provide an example of its usage.

#### OOP Multiple Inheritance
1. What is inheritance?
2. What is multiple inheritance?
3. How does the MRO (Method Resolution Order) work in multiple inheritance?
4. What are the advantages and disadvantages of using multiple inheritance?
5. How does operator overloading work in Python, and why is it useful?
6. What is Mixins?

#### OOP Encapsulation Polymorphism Abstraction
1. What is encapsulation in Python?
2. What is polymorphism, and how is it implemented in Python?
3. What is abstraction in Python?
4. What is the difference between public, private, and protected access modifiers?
5. How to achieve data abstraction?
6. What is ABC and @abstractmethod?

#### Properties and Descriptors
1. What are properties in Python, and how do you use them?
2. What are descriptors in Python?
3. How do properties and descriptors differ?
4. When should you use a property vs. a descriptor?
5. What is @property?
6. What are setattr(), getattr(), and hasattr(), and what are they used for? What is the difference between them?
7. Explain the significance of the __set_name__ method in Python descriptors, and provide an example illustrating its usage.

#### Exception Handling
1. What are exceptions in Python?
2. What are the three types of errors in Python, and how do they differ from each other?
3. How do you use try, except, else, and finally blocks?
4. What does the order of except keywords mean?
5. What is the purpose of using the `assert` statement in Python code?
6. How does the raise keyword differ from simply printing an error message in Python?
7. What is the significance of creating custom exceptions in Python, and how can they enhance error handling in a program?

#### Exceptions in Details
1. How are exceptions organized in Python, and what is the hierarchy of exception classes?
2. What are some common approaches to handling multiple types of exceptions in Python, and why is it important to handle them separately?
3. What is the purpose of re-raising an exception in Python, and in what scenarios might it be useful?
4. Why should the usage of the try-except block be limited in Python programs, and how can it impact program performance?

#### File Handling
1. What are the different modes for working with files in Python?
2. Why is it essential to close files after performing operations on them, and what can happen if files are left open?
3. What are the differences between using the read(), readline(), and readlines() methods for reading files, and when would you use each method?
4. How can you write data to a file in Python, and what are the differences between the w(write) and a(append) modes?
5. What are context managers in Python, and how can they be used for file handling to ensure proper resource management?

#### Memory Management
1. How does Python manage memory?
2. What is reference counting in Python, and why is it essential for memory management?
2. What is garbage collection in Python?
3. How do you get the memory address of a Python object?
4. What is the purpose of the getrefcount() function from the sys module, and how does it work in Python?
5. Explain with examples the difference between mutable and immutable objects concerning reference counting and memory management.
6. What is the difference between shallow copy and deep copy in Python, and when would you use each?

#### Testing
1. What are the differences between automated and manual testing, and what are the advantages of automated testing?
2. How does the assert statement work in Python, and what is its primary purpose in testing?
3. What is TDD (Test-Driven Development)?
4. What are some popular testing frameworks for Python?
5. What is the pytest framework, and how does it differ from unittest in terms of syntax and functionality?
6. What is unittest in Python?
7. Describe the pytest.raises method and its use case in testing for specific exceptions in Python code.
8. What is parametrization in testing, and how does pytest support it using the @pytest.mark.parametrize decorator?
9. How can you customize test names in pytest when using parametrized tests to make them more descriptive and readable?

#### Testing in Details
1. What is the Arrange/Setup step in testing, and why is it important?
2. What steps are included in Cleanup/Teardown, and why are they important?
3. What is the difference between the setUp() and setUpClass() methods in the unittest framework?
4. What is a mock object, and how can it be used to improve test quality?
5. What is the difference between using mock.patch in unittest and monkeypatch in pytest for mocking objects?
6. What does the scope parameter in pytest fixtures do?

#### Basic Modules Overview
1. What are built-in popular modules in Python?
2. How to work with dates in Python?
3. How to work with float numbers, but with better precision?
4. What are the main popular packages (requests, pytest, etc)?
5. What do you know about the collections module, which other built-in modules were used?
6. What does sys.argv return?
7. What is the primary module used for interacting with the operating system in Python?
8. How do you shuffle the elements of a list using the random module?
9. How do you get the current date and time using the datetime module?

#### Dict Advanced
1. What is algorithm complexity, and how is it defined?
2. Explain the concept of big "O" notation and its significance in algorithmic complexity.
3. What types of algorithm complexities are commonly encountered?
4. Can you give examples of tasks that are efficiently solved with linear (O(n)) algorithms?
5. Explain how Python dict works under the hood.
6. What is a hash function?

#### Additional Questions
1. What is a dynamically typed language?
2. What are literals in Python, and can you give examples of different literals?
3. What are keywords in Python?
5. What is pass or ... in Python? What is ... in Python?

---

### Django ORM 🐍

#### DataBase Intro
1. What is a database?
2. What is SQL?
3. What are the main types of databases, and how do they differ from each other?
4. What is parametrization (SQL-injection)?
5. What is connection/cursor?
6. What is CRUD?

#### ORM Intro
1. What is ORM (Object-Relational Mapping) and what is its primary purpose in software development?
2. For what purposes manage.py is used?
3. What is stored in settings.py?
4. What are models?
5. What are migrations?
6. What are QuerySets?

#### Fields and relations
1. Which different fields in Django ORM you know (list all of them)?
2. What is the difference between null and blank?
3. What are field choices?
4. What types of dependencies exist between tables in a database, and how are they represented in ORM?
5. What parameters does on_delete use for ForeignKey, and what do they do?
6. What is a backward relations in Django ORM, and how can it be used to access related model objects from the perspective of the referencing model?
7. How is OneToOneField used to establish a "one-to-one" relationship in Django ORM, and in what scenarios can this be useful?

#### Many-to-Many Relationship
1. What type of field is used to represent a many-to-many relationship in Django ORM?
2. What is the purpose of an intermediate table (Many-to-many)?
3. What is the purpose of using the @property decorator in a Django model
4. What are managers?

#### Queries
1. What are lazy QuerySets in Django?
2. What are some common field lookups used in Django queries?
3. How are joins implemented in Django ORM?
4. How can Django Shell Plus aid in understanding queries and interacting with models?
5. What is the purpose of the save() method in Django models?

#### Queries in Details
1. How does QuerySet caching work in Django, and what are its implications?
2. What are the potential drawbacks of not using QuerySets properly?
3. How can you use the aggregate() method to calculate aggregate values over a QuerySet in Django?
4. What is the difference between using the aggregate() and annotate() methods in Django for generating aggregated values?
5. What is the N+1 query problem in Django, and how can you address it?
6. How does the select_related() method improve query performance in Django, and when should it be used?
7. How does the prefetch_related() method improve query performance in Django, particularly in the context of many-to-many relationships?

#### ORM Advance
1. How can you use the Meta internal class in Django models, and what are some of its common options?
2. What is the purpose of the ordering option in the Meta class, and how is it used to specify default object ordering in Django models?
3. How can you specify human-readable names for objects using the verbose_name and verbose_name_plural options in the Meta class?
4. What is the purpose of the db_table option in the Meta class?
5. What are database indexes?
6. How does indexing improve data searching speed in a database, and how can you add indexes to fields in Django models?
7. What are constraints in Django models, and how can you define unique constraints using the UniqueConstraint option in the Meta class?
8. What is a transaction?

#### Optional Topic: Performance improvement & isolation levels
1. What is database normalization, and why is it important in database design?
2. What are the main reasons for normalizing databases, and what advantages does normalization offer?
3. What are the three normal forms (1NF, 2NF, 3NF), and what are the requirements for achieving each of them?
4. How does indexing improve data retrieval performance in a database, and what are the main types of indexing methods?
5. What are the advantages and disadvantages of indexing in a database?
6. Explain the concept of master-slave in database architecture, and how does it optimize I/O operations?
7. What is sharding in database architecture, and what are its benefits and drawbacks?
8. What is isolation in the context of database transactions, and why is it important for transaction integrity?

---

### Django 🐍

#### Django Intro
1. What is Django, and what are some of its key features?
2. What are the steps involved in setting up a Django project using the terminal?
3. How can you verify if Django is successfully installed on your system?
4. When you create a Django project, what files are generated, and what is the purpose of each file?
5. What is a Django app, and how do you create one?
6. What is the difference between a project and an app in Django?
7. Why is the Django admin panel useful, and how can you access it?
8. How do you add a model to the Django admin panel, and what is the purpose of the register() method in admin.py?
9. What customization options are available for the Django admin panel, and how can you customize it to display specific fields?

#### MVT
1. How does Django's MVT architecture facilitate the development of web applications, and what are its core components?
2. Explain the role of URLs in Django
3. Describe the significance of Views in Django's MVT architecture, and how do they interact with Models and Templates?
4. What is the context in Django?
5. Explain the importance of Models in Django, and how do they represent data within the application?
6. Describe the role of Templates in Django
7. How to omit code duplication in django templates (extending, including)?
8. What is Jinja2 templating?

#### Django Sessions and Authentication
1. Explain user authentication in Django?
2. What are middlewares?
3. What’s the use of a session framework?
4. What is CSRF?
5. What is the purpose of the @login_required decorator in Django?
6. How can you limit access to logged-out users in class-based views?

#### Django Forms
1. What is the purpose of Django forms?
2. How does Django handle forms in views?
3. What steps are involved in the form handling process in Django?
4. How can you create a basic form in Django using HTML and Django views?
5. What is Django-Crispy-Forms? And what is it used for in Django?

#### Django Forms in Details
1. What is Django form validation?
2. How can you implement custom validation in Django forms?
3. What is a UserCreationForm, and how is it used in Django?
4. What is a ForeignKey field in Django models, and how does it relate to forms?
5. What is the purpose of the clean_field function in Django forms?
6. What is a widget in Django forms?

#### Django Advanced
1. How can you implement searching by a specific parameter in Django?
2. What is the purpose of implementing a form for searching in Django?
3. What are custom template tags used for in Django?
4. What is the difference between using the GET and POST methods in forms for filtering and searching?
5. What are the main reasons for writing tests in Django?
6. How can you test custom model methods in Django?

#### Deploying Django
1. What are the main stages of deploying a Django project?
2. What steps are necessary to prepare a Django project for deployment?
3. What security practices should be considered when deploying a Django project?
4. Which database is better to choose for use during deployment?

---

### Django Rest Framework 🐍

#### Django REST Framework Intro
1. What is an API?
2. What is a REST API?
3. What is Postman?
4. What is browsable API?
5. What is the difference between stateful and stateless?
6. What is Django Rest Framework?
7. What are serializers?
8. What are serialization & deserialization?

#### Class-Based Views
1. What are ViewSets in DRF?
2. What are routers in DRF?
3. What is the difference between APIViews and ViewSets in DRF?
4. What is the difference between GenericAPIView and GenericViewSet?
5. What are ViewSet actions in DRF?
6. How to write custom action on ViewSet?

#### Serializers
1. What are the purpose of get_queryset & get_serializer_class methods in ViewSet?

#### Serializers in Details
1. What is validation in DRF?
2. What are Nested Serializers in DRF?

#### Authentication and Permissions
1. What are Permissions in DRF?
2. What is Token Authentication?

#### DRF Advance
1. How can you work with images in Django REST Framework, and what module is commonly used for image processing?
2. What is the purpose of the @action decorator in Django REST Framework, and how is it typically used?
3. How can you modify the authentication process in Django REST Framework to use email instead of username?

#### DRF JWT and Tests
1. What are JSON Web Tokens (JWTs)?
2. JWT vs Token Authentication vs Session Authentication
3. What are access/refresh token?
4. What is Swagger?

#### Docker
1. What is Docker, and how does it differ from virtual machines (VMs)?
2. Explain the concept of containerization and its advantages.
3. What is a Docker image, and how does it relate to Docker containers?

#### Docker In DRF
1. What is Docker Compose, and how does it facilitate running a Django project with a Postgres database?
2. Explain the concept of Docker volumes and their significance in persisting data generated by and used by Docker containers.
3. How can Docker be used to work with static files and media data in a Django project, and what steps are involved in setting it up?

#### Connect Backend to Frontend
1. How to fix CORS errors in Django?

---

### Asynchronous Python 🐍

#### Concurrency and Parallelism
1. What is the difference between concurrency and parallelism in programming, and when would you use each concept?
2. How does Python's Global Interpreter Lock (GIL) impact concurrency in the CPython interpreter, and what are its implications for multithreading?
3. Explain the concept of threading in Python and how it differs from multiprocessing.
4. What is the purpose of the asyncio module in Python, and how does it enable asynchronous programming?

#### Concurrency and Parallelism (Part 2)
1. How does asyncio enable asynchronous programming, and what are the key components involved in asyncio-based code?
2. Can you explain the difference between synchronous and asynchronous programming in Python, using examples from asyncio?
