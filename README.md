# Object-Oriented-Design
README:
=======

1.	Approach OO Design
	--	handle ambiguity
		- OOD questions are often intentionally vague in order to test whether you'll make assumptions or if you'll ask clarigying questions.
		- When being asked an OOD question, you should inquire who is going to use it and how they are going to use it. Who, What, Where, When, How, Why
	--	define the core object
	--	analyze relationships
		- analyze the relationships between the objects
		  which objects are members of which other objects
		  do any objects inherit from any others
		  are relationships many-to-many or one-to-many
	--	investigate actions
		consider the key actions that the objects will take and how they relate to each other(update your design)
2.	Design Patterns
	the singleton and factory method design patterns are especially useful for interviews
	--	Singleton class
		ensures that a class has only one instance and ensures access to the instance through the application
	--	Factory method
		offers an iterface for creating an instance of a class, with its subclasses deciding which class to instantiate(implement with abstract class)
