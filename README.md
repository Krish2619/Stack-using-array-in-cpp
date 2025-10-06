Aim:
To implement a stack using arrays in C++ and perform basic operations such as push, pop, peek, and display.

Apparatus:
- C++ Compiler (e.g., g++, Code::Blocks)
- System with standard input/output
- Knowledge of arrays and stack operations

Program Explanation:
The program defines a `Stack` class that uses an array of fixed size to implement stack operations. It supports:

- push: Inserts an element at the top of the stack.
- pop: Removes and returns the top element.
- peek: Returns the top element without removing it.
- display: Prints all elements from bottom to top.

The stack handles overflow (when full) and underflow (when empty) conditions gracefully with appropriate messages.


Algorithm:

push(element):
- If top == MAX - 1 → print "Stack Overflow"
- Else → increment top and insert the element

pop()
- If top == -1 → print "Stack Underflow" and return sentinel value
- Else → return element at top and decrement top

peek()
- If top == -1 → print "Stack Underflow"
- Else → return element at top

display()
- If top == -1 → print "Stack Underflow"
- Else → loop from 0 to top and print each element

 Key Concept
- **Stack** follows **LIFO** (Last In First Out) principle.
- Implemented using a static array.
- Useful for expression evaluation, backtracking, and function call management.

Conclusion
This program demonstrates a basic stack implementation using arrays in C++, performing all standard operations and handling boundary conditions like overflow and underflow effectively.
