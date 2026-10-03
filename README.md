# DSA Assignment

## Q1. Stack Using Array

In this question, I have implemented a stack using an array in C.
The stack follows the LIFO (Last In First Out) principle.

The following operations are performed:

- PUSH(x) - Adds an element to the stack.
- POP() - Removes the top element from the stack.
- PEEK() - Shows the top element.
- DISPLAY() - Displays all the elements of the stack.

## Overflow and Underflow

If the stack is full and we try to add another element, Stack Overflow occurs.

If the stack is empty and we try to remove an element, Stack Underflow occurs.

## Time Complexity

- PUSH: O(1)
- POP: O(1)
- PEEK: O(1)
- DISPLAY: O(n)

## Space Complexity

The space complexity is O(n), as the stack uses an array to store the elements.

## Fixed Size Stack

In this program, the maximum size of the stack is 5.
If we try to insert more than 5 elements, the program shows Stack Overflow.

## Conclusion

This program helped me understand how a stack works using an array and how PUSH, POP, PEEK and DISPLAY operations are performed.