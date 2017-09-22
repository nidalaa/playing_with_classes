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
