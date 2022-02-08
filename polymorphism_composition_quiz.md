# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?
The ability of a message to be displayed in many different forms.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
a message will be sent to multiple class objects therefore every object will respond
appropriately according to the properties of each class.

3. What can we use to implement polymorphism in Java?
we would use a class that 'extends' from another. This means that the child that 'extends'
from the parent will share its attributes

4. How many 'forms' can an object take when using polymorphism?
As many forms as what is required by the developer/code.

5. Give an example of when you could use polymorphism.
A good example would be if you had animal classes, they could 'makeSound()' but
once these are passed down the classes' makeSound() would be different.
pig makeSound(oink), dog makeSound(woof) cat makeSound(meow) etc.


# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming?
An object/class can't exist on its own without the existing parent class.

7. When would you use composition? Provide a simple example in Java.
used when one object has, or is part of another object.

8. Give a difference between composition and aggregation?
Aggregation - A child can/could exist independently of the parent
Composition - A child cannot/couldn't exist independently of the parent

9. What is/are the advantage(s) of using composition/aggregation?
it is more flexible than inheritance; as you can change the implementation of an object (changing its behaviour)

10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?
A child cannot/couldn't exist independently of the parent therefore the code would break.

11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?
A child can/could exist independently of the parent therefore the code would be fine.
