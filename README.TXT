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


Question 11:
The mistake is by using the type name (int) with the value (5), like you're declaring a variable. However, you're not supposed to declare the type when passing a value to a method.
this would fix it: display.setValue(5);

Question 13:
Said parameter value would be 0, because with the new condition replacementValue > 0, the number 0 is rejected, even though it used to be valid with >= 0.

Question 14:
Some of the invalid parameter values that would now be able to set the field are negative values or values equal to or greater than the limit

Question 15:
By using the code pad, I see that "! false" and "(34 != 33) && ! false" return true

Question 16: 
a == b

Question 17: 
(a && !b) || (!a && b)

Question 18:
It assumes that the value will never be more than two digits. If i use getDisplayValue() in a place that expects only two digits, I will get inconsistent formatting when the value exceeds 99.

Question 19:
No, they produce an identical result. Both expressions produce the same string representation of the int value.

Question 20:
They give the results "12cat" and "cat39" respectively. This happens because BlueJ uses left-to-right evaluation when using "+".



