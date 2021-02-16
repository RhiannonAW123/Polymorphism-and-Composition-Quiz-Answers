# Polymorphism-and-Composition-Quiz-Answers

Polymorphism

What does the word 'polymorphism' mean?

A: the condition of occurring in several different forms.

What does it mean when we apply polymorphism to OO design? Give a simple Java example.

A: An object can have many object types for example children class attendant, manager or receptionist could all be of a parent class Staff.

What can we use to implement polymorphism in Java?

A: Interfaces or Inheritance.

How many 'forms' can an object take when using polymorphism?

A: As many as needed.

Give an example of when you could use polymorphism.

A: You could have a Vehicle class which takes in a set of sub classes such as Car, Truck, Tractor and Motorbike and so on.



Composition and Aggregation

What do we mean by 'composition' in reference to object-oriented programming?

A: Composition is the relationship between objects where the child objects cannot exist without the parent.

When would you use composition? Provide a simple example in Java.

A: We may have an “Animal” parent class with a child class “Tiger” the “Tiger'' class would not exist if the “Animal” class did not.

Give a difference between composition and aggregation?

A: Aggregation means that child components can exist without a parent. With composition child components must have a parent.

What is/are the advantage(s) of using composition/aggregation?

A: It allows us to use the behaviours between classes.

When using composition, when an object is destroyed, what happens to all the objects it is composed of?

A: All the child objects are destroyed with it because they cannot exist without a parent.

When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?

A: The child objects will still exist because they are not dependent on the parent. 
