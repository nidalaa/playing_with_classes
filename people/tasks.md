[#1 #2 #3]

Create class Person:

- instance vars: @id, @name, @age
- constructor with name and age as parameter (name should be optional [default "Unknown"])
- getters & setters for @name and @age
- getter for @id
- extra method is_of_age? (returns true/false)

----------------

[#4]

- make `is_of_age?` a private method
- add optional parameter and instance var in constructor called `parent_permission` (default true) with getter and setter
- add public method `can_use_services?`. Person can use services if is of age or if permission from parents exists.

----------------

[#5]

Create class Student:

- inherits from Person
- constructor extends parent's class constructor by adding instance var & param (`@classroom`/`classroom`)
- has special method `play_hooky` which returns "¯\\_(ツ)_/¯"

Create class Teacher:

- inherits from Person
- constructor extends parent's class constructor by adding instance var & param (`@specialization`/`specialization`)
- overrides parent's methos `can_use_services?` and always returns `true`

----------------

[#6]

Create class Corrector with method `correct_name`, which:

- makes sure that the first letter of the given word is a capital letter
- makes sure that name has max 10 chars (and makes it shorter and add `...` if needed)

Use and instance of Corrector class in Person class:
- in `validate_name` method, to correct person's name

----------------

[#7]

Change your own getters and setters to shortcuts:
- first only attr_reader and attr_writer
- then use attr_accessor where it makes sense

----------------
