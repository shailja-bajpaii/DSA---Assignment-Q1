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





## Q2. Circular Queue Using Array

In this question, I have implemented a circular queue using an array in C.

The following operations are performed:

- ENQUEUE(x) - Adds an element to the queue.
- DEQUEUE() - Removes an element from the queue.
- FRONT() - Shows the front element.
- DISPLAY() - Displays all queue elements.

### Full and Empty Queue

If the queue is full, the program shows "Queue is Full".

If the queue is empty, the program shows "Queue is Empty".

### Time Complexity

- ENQUEUE: O(1)
- DEQUEUE: O(1)
- FRONT: O(1)
- DISPLAY: O(n)

### Space Complexity

The space complexity is O(n), as the queue uses an array.

### Circular Queue vs Linear Queue

A circular queue uses the empty spaces created at the beginning of the array, so memory is utilized better.

In a linear queue, when REAR reaches the last index, insertion may not be possible even if there are unused spaces at the beginning.

### Conclusion

This program helped me understand how a circular queue works and how ENQUEUE, DEQUEUE, FRONT and DISPLAY operations are performed.