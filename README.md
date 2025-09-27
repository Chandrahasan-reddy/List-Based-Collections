# List-Based-Collections
A collection of Java programs demonstrating the usage of ArrayList, LinkedList (Singly &amp; Doubly), Stack, Queue, Deque and Array deque with examples and outputs.

Java Collections – Examples 🚀

This repository contains simple Java programs that demonstrate the usage of Java Collections Framework classes and interfaces such as:

ArrayList

LinkedList (Singly & Doubly LinkedList concepts)

Stack

Queue

Deque (Double-Ended Queue)

ArrayDeque

Each program includes definition, code, and output, making it easy to understand the behavior of these data structures.

📂 Contents
🔸 1. ArrayList

Definition:
An ArrayList is a resizable array implementation in Java. It allows random access of elements using indices and can grow dynamically as needed.

Allows duplicates and heterogeneous elements.

Best for searching and iteration.

Slower for frequent insertions/removals in the middle (as shifting occurs).

In the code:

Demonstrates dynamic resizing, insertion at index, merging lists (addAll()), and retaining common elements (retainAll()).

🔸 2. LinkedList

Definition:
A LinkedList is a doubly linked list implementation in Java. Each node contains data and pointers to both the previous and next node.

Efficient for insertions and deletions at both ends.

Slower for random access compared to ArrayList.

Concepts:

Singly Linked List → Each node points to the next node.

Doubly Linked List → Each node points to both the next and previous nodes (used by Java).

In the code:

Demonstrates methods like addFirst(), addLast(), getFirst(), getLast(), removeFirst(), removeLast(), peek(), poll(), and offer().

🔸 3. Stack (LIFO)

Definition:
A Stack is a Last In, First Out (LIFO) data structure where the last element inserted is the first to be removed (like a stack of plates 🍽️).

Key operations → push() (insert), pop() (remove), peek() (view top).

Can be implemented using LinkedList or ArrayDeque.

In the code:

Demonstrates pushing and popping elements using LinkedList.

🔸 4. Queue (FIFO)

Definition:
A Queue is a First In, First Out (FIFO) data structure where elements are inserted at the rear and removed from the front (like a line at a ticket counter 🎟️).

Key operations → add(), offer(), peek(), poll(), remove().

Can be implemented using LinkedList or PriorityQueue.

In the code:

Demonstrates insertion/removal from both ends using LinkedList.

🔸 5. Deque (Double-Ended Queue)

Definition:
A Deque (pronounced “deck”) is a double-ended queue that allows insertion and removal of elements at both ends.

Can act as both Queue (FIFO) and Stack (LIFO).

Common methods → addFirst(), addLast(), removeFirst(), removeLast(), peekFirst(), peekLast(), pollFirst(), pollLast().

In the code:

Demonstrates operations from both ends using LinkedList.

🔸 6. ArrayDeque

Definition:
An ArrayDeque is a resizable array-based implementation of the Deque interface.

Faster than LinkedList for stack/queue operations (no extra node overhead).

Cannot store null elements.

Used as both Queue and Stack.

In the code:

Demonstrates queue operations (offer(), poll(), peek()),

stack operations (push(), pop()),

and double-ended operations (addFirst(), addLast(), removeFirst(), removeLast()).

📖 Learning Takeaways

ArrayList → Best for fast random access.

LinkedList → Best for frequent insertions/deletions.

Stack → LIFO principle.

Queue → FIFO principle.

Deque → Hybrid (works as Queue + Stack).

ArrayDeque → Faster alternative to LinkedList for stack/queue use cases.
