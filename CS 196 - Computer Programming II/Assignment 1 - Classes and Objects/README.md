Click on the file assignment1.ipynb in this assignment.  
This is a jupyter notebook where you will add your code.

DO NOT INCLUDE YOUR NAME/EMAIL ANYWHERE IN THIS FILE.

In this notebook you should add the following 6 cells with python code (plus additional markdown cells to document the assignment):

  1. Create a class called Dog, such that any object of this class will have:
    - attributes name, age, and breed
    - methods talk, come, and sit
    - when method talk is called, print `f"{self.name} says woof"`
    - when method come is called, print `f"{self.name} runs over"`
    - when method sit is called, print `f"{self.name} sits"`

  2. Create a class called Cat, such that any object of this class will have
    - attributes name, age, and breed
    - methods talk, come, and sit
    - when method talk is called, print `f"{self.name} says meow"`
    - when method come is called, print `f"{self.name} lazily meanders over"`
    - when method sit is called, print `f"{self.name} gives you the a contemptuous look"`

  3. Create 2 different dogs (objects of class Dog) with different names, ages, and breeds; call the objects dog1 and dog2
    - specify age in years, breed could be any dog breed (e.g., golden retriever, lab)

  4. Create 2 different cats (objects of class Cat) with different names, ages, and breeds; call the objects cat1 and cat2
    - specify age in years, breed could be any cat breed (e.g., briman, toyger)

  5. Call the talk(), come(), and sit() methods for each of the 4 objects you created

  6. Do the following 3 things:
    - print the name, age, and breed for dog1 using the following code:
      `print(f"The {dog1.breed} named {dog1.name} is {dog1.age} years old now.")`
    - add 1 to the age for dog1
    - print the name, age, and breed for dog1 again, using the same code:
      `print(f"The {dog1.breed} named {dog1.name} is {dog1.age} years old now.")`

Add docstrings and comments (and/or markdown) where appropriate.

Code will be evaluated for:
- code is written and works as intended (e.g., correct calls, correct output, no errors)
- clean/efficient code (e.g., no unnecessary code)
- naming conventions (e.g., class names are UpperCamelCase)
- readability (e.g., meaningful names, separation of code into separate cells)
- documentation (e.g., docstrings, comments, argument type specification)
- click "View Rubric" on blackboard under this assignment for more details

Execute all cells in this notebook and save.

Sample output expected in this notebook:

    Kobe says woof
    Kobe runs over
    Kobe sits
    Spike says woof
    Spike runs over
    Spike sits
    Jenna says meow
    Jenna lazily meanders over
    Jenna gives you the a contemptuous look
    Sam says meow
    Sam lazily meanders over
    Sam gives you the a contemptuous look
    The Labrador named Kobe is 5 years old now.
    The Labrador named Kobe is 6 years old now.

