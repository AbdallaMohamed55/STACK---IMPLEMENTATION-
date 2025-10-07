# STACK---IMPLEMENTATION-
To Study and Implement Stack Implementation Using Array with Menu Options (Push, Pop, Display, Exit)

# Aim 

To study the concept of stacks and implement basic stack operations — Push, Pop, and Display — using arrays in C++.

# Theory

A Stack is a linear data structure that follows the LIFO (Last In, First Out) principle, meaning the element that is inserted last is the first to be removed.
It can be implemented using either arrays or linked lists.

## Basic Stack Operations:

  1. Push: Insert an element at the top of the stack.
 
  2. Pop: Remove the top element from the stack.

  3. Display: Show all elements in the stack from top to bottom.

## Conditions:

   * Overflow: Trying to push an element into a full stack.

   * Underflow: Trying to pop an element from an empty stack.

## Applications of Stack:

   * Expression evaluation and conversion (infix, postfix, prefix)

   * Function call management (recursion)

   * Undo/Redo operations

   * Syntax parsing and backtracking algorithms

### Algorithm : Stack Implementation using Array

Step 1:

      * Start the program.

Step 2:

      * Define a constant SIZE = 5 for the maximum size of the stack.

Step 3:

    Create a class Stack with the following members:

            * arr[SIZE] → an integer array to store stack elements.

            * top → an integer variable to keep track of the top element index.

Step 4:

          Initialize the constructor:
             *  Set top = -1 to indicate the stack is initially empty.

Step 5:

    Define the Push() function:

       1. Check if top == SIZE - 1.

           * If true, print "Stack Overflow!" and return.

       2. Otherwise:

             * Increment top by 1.

             * Insert the element into arr[top].

             * Display message <value> pushed into stack.

Step 6:

    Define the Pop() function:

      1. Check if top == -1.

         * If true, print "Stack Underflow!" and return.

      2. Otherwise:

           * Print arr[top] as the popped element.

           * Decrement top by 1.

Step 7:

    Define the Display() function:

      1. Check if top == -1.

           * If true, print "Stack is empty." and return.

      2. Otherwise:

           * Print "Stack elements:".

           * Loop from i = top down to 0, displaying arr[i].

Step 8:

     In the main() function:

        1. Create a Stack object s.

        2. Perform the following operations:

            * s.push(10)

            * s.push(20)

            * s.push(30)

            * s.display()

            * s.pop()
 
            * s.display()

            * s.push(40)

            * s.push(50)

            * s.push(60) → triggers overflow.

            * s.display()

            * Perform multiple pop() operations to trigger underflow.

Step 9:

      * End the program.



## Procedure:

  i/Open a C++ compiler and create a new file.

  ii/ Write the above code and save it as stack_array.cpp.

  iii/ Compile the code to remove syntax errors.

  iv/ Run the program.
  
  v/ Test by choosing different menu options (Push, Pop, Display).

  vi/ Observe the stack operations and output.


# Conclusion 

The experiment demonstrates the LIFO behavior of the stack data structure using array implementation. The menu-driven program helps visualize stack operations, and the concept can be extended to dynamic implementations using linked lists.
