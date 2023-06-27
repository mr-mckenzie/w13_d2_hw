# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

    A - Polymorphism means many (different) forms.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

    A - Applying polymorphism to OO design means that we can use different classes at different times. For example you may require a behaivour of swim() from an object however the swim action could be performed by a Fish class or a Whale Class or a Human class or a Penguin class, etc. In essence the swimmer can take many different forms.

3. What can we use to implement polymorphism in Java?

    A - We can use interfaces to implement polymorphism.

4. How many 'forms' can an object take when using polymorphism?

    A - An object can only take on one form (the form that has the required behavior) when using polymorphism.

5. Give an example of when you could use polymorphism.

    A - An example is an eBay account. You can be both a seller or a buyer with the same account and each form has specific behaiviours. 



# Composition and Aggregation

6. What do we mean by 'composition' in reference to object-oriented programming?

    A - Composition in OO programming can be explained by the 'Has A' relationship (i.e. [object 1] has a [object 2]).

7. When would you use composition? Provide a simple example in Java.

    A - You could use composition to implement a Zoo. The Zoo class is composed of a LionEnclosure class, a ReptileHouse class, an Aquarium class, etc.

8. Give a difference between composition and aggregation?

    A - One difference is that aggregation relationship means that each exists separately, whereas composition means that the child cannot exist without the parent.

9. What is/are the advantage(s) of using composition/aggregation?

    A - Aggregation means that classes are not tightly coupled. Composition means that classes can inherit props or methods, therefore keeping your code DRY.

10. When using composition, when an object is destroyed, what happens to all the objects it is composed of?

    A - All of the objects composing the destroyed object are also destroyed.

11. When using aggregation, when an object is destroyed, what happens to all the objects it is composed of?

    A - All of the objects composing the destroyed object still exist.