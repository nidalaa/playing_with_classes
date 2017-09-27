1. Class definition
2. Constructor
    - instance vars
    - params
    - optional params
3. Getters & Setters
4. Public methods and private methods
5. Inheritance
    - children class specific methods
    - overriding parent class methods
    - extending constructor
6. Composition - use other class
7. Getters & Setters shortcuts
    - attr_writer, attr_reader
    - attr_accessor (2in1: attr_writer + attr_reader)
8. Reading recap
    - classes and objects: https://learnrubythehardway.org/book/ex42.html
    - inheritnace & Composition: https://learnrubythehardway.org/book/ex42.html
10. Basic two-ways class relationships
    - real life example: Alex `has many` animals: a dog, a spider, a cat. And each of these animals `belongs to` one owner, right? A dog belongs to Alex. A spider belongs to Alex. A cat belongs to Alex
    - `has many` - one object of class X can have a collection of objects of class Y (e.g. alex.animals)
    - `belongs to` - one object of class Y `belongs to` exactly one  object of class X (e.g. animal.owner)
    - making sure that relationship works both ways
11. Three classes relationship (has-many-through relationship)
    - real life example: a dog `has many` vet visits in their life and each of these visits `belongs to` one vet. From anther perspective: a vet `has many visits` and each of these visits `belongs to` one animal. End result is that that a dog `has many` vets through visits and a vet `has many` animals through visits.
    - `has many` + `belongs to` between class X and Y (e.g. dog.visits + visit.animal)
    - `has many` + `belongs to` between class X and Y (e.g. vet.visits + visit.vet)
12. Reading: object oriented programming
    - 4 principles - https://anampiu.github.io/blog/OOP-principles
      - encapsulation: mostly using getters and setters in responsible way + usage of private methods
      - inheritance: covered in recap in point 8
      - abstraction: no real abstract class and methods in Ruby, we can do sth like https://stackoverflow.com/a/512568 though
      - polymorphism: no specific implementation in Ruby, some ideas around well described here: https://robots.thoughtbot.com/back-to-basics-polymorphism-and-ruby
      - the simplest examples of 3 principles (abstraction is not included) in Ruby: https://devblast.com/b/ruby-inheritance-encapsulation-polymorphism
    - SOLID - https://scotch.io/bar-talk/s-o-l-i-d-the-first-five-principles-of-object-oriented-design and https://robots.thoughtbot.com/back-to-basics-solid
    - KISS & YAGNI & DRY - http://www.itexico.com/blog/bid/99765/software-development-kiss-yagni-dry-3-principles-to-simplify-your-life
13. Project schema: UML class diagram
