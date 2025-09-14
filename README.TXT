Project: number-display
Authors: Michael Kölling and David J. Barnes

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It is discussed in chapter 3.

To use this project, create an instance of class NumberDisplay. Then inspect this 
instance and leave the inspector window open. With the inspector window open, 
call the object's methods, such as increment and setValue.

Question 1:
class diagram: blueprints. describes the structure and design of LabClass and Student
object diagram: objects. shows data (names of the students) and links (lab1)

Question 2: 
It can change at various stages of software development. Design, during maintenance, requirements gathering, implementation or refactoring. It can be modifided manually through the UML, code based or with team decisions.

Question 3: 
During development, design, debugging or maintenance. Manually (with UML) or automatically (reverse engineering).

Question 4: 
private Instructor tutor;

Question 6: 
After calling minutes.increment(), check if minutes.getValue() == 0. If it is, then call hours.increment() to advance the hour.

Question 8:
Only the call to setValue(3) changed the stored value because it was within the allowed range (0–5). The call to setValue(10) did not change the value because it was greater than the limit.

Question 9:
After I called setValue(10), getValue() will return the previous value (likely 0), because 10 is invalid and the method will not change the stored value.

Question 10:
I see the error message "cannot make a static reference to the non-static method getValue() from the type NumberDisplay"




