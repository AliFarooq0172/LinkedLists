# **Linked Lists Experimentation**

## **Linked List Class Methods:**
  1. Append
  2. Length
  3. Display (Ignore display2)
  4. Extractor Function (get)
  5. Delete
  6. Problem #1: Kth Node From End
  7. Problem #4: Reversing Linked List Iteratively
  8. Problem #5: Reversing Linked List Recursively

## **Independant Methods:**
  1. Problem #2: Finding Intersection Point of 2 Linked Lists
  2. Problem #3: Finding out if Linked List has a Loop/Cycle

## **Problems:**

### Problem #01: Kth Node From End
Suppose we have a Singly Linked List. User input's a number (K), and you have to return the data present in the Node, 
such that it is present on the Kth position from the Tail/End of the Linked List.

### Problem #02: Finding Intersection Point of 2 Linked Lists
Let's say we have 2 Singly Linked Lists, and that they have an intersection point, such that the linked lists converge on that node.
Our Goal here is to find that converging/intersecting node.

### Problem #03: Finding out if Linked List has a Loop/Cycle
Alright, we have a linked list, such that when we display it, it keep's on using the system's resources and runs infinitely.
Yes, you guessed that right, it's like the system is running around in circles/loops.
So, eventually we have to stop executing the code manually, and find out if the Linked List has a Loop/Cycle.

### Problem #04: Reversing Linked List Iteratively
Here's where we spice things up a bit. It's one of the most famous questions raised when discussing Linked Lists.
How to reverse a Linked List Iteratively? 
We have a normal linked list present (from our previous problems). We simply define a method in our class, where we sort this out.
We Simply use three Pointers, Current, Prev, Next.
Using the Current Pointer to iterate through the Linked List, and the prev and next pointers to save the relevant access pointers,
we simply change the current.next from the next node to the previous node in each iteration.

### Problem #05: Reversing Linked List Recursively
This problem is similar to the previous one.
It defines a helper function, reverse_util, which takes a current node and the previous node. 
During the recursive calls, it reverses the direction of pointers, and upon reaching the end of the list, it returns the new head and the last node. 
The method then updates the original linked list's head with the new head, completing the reversal. 
This approach provides an efficient and concise way to reverse a linked list using recursive techniques.
