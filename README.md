# IMPLEMENTATION-OF-INHERITANCE
# Overview
This Java project demonstrates the concept of multiple inheritance through a simple student result system. It consists of classes representing students and their results.

## Classes
1. `Student_part2`: This class represents a student with attributes such as name, roll number, and marks for two subjects. It includes methods to get and set these attributes.

2. `Result_part2`: This class extends the `Student_part2` class and calculates the total marks and average marks of a student based on the marks obtained in two subjects. It includes a method to display the student's name, roll number, total marks, and average marks.

3. `Main_part2`: This class contains the `main` method where an instance of `Result_part2` is created and its `display` method is called to print the student's result.

# FixedStack
The FixedStack class implements a fixed-size stack with the following methods:

push(int item): Adds an item to the top of the stack.
pop(): Removes the item from the top of the stack.
displayStack(): Displays the contents of the stack.

# GrowableStack
The GrowableStack class implements a growable stack using an ArrayList with the following methods:

push(int item): Adds an item to the top of the stack. If the stack is full, it dynamically grows the stack size.
pop(): Removes the item from the top of the stack.
displayStack(): Displays the contents of the stack.

# Main
The Main class contains the main method, which demonstrates the usage of both fixed-size and growable stacks. It creates instances of FixedStack and GrowableStack and performs various stack operations such as pushing, popping, and displaying the stack contents.


