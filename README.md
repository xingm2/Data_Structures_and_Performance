# Data_Structures_and_Performance
by University of California, San Diego

--Week II
Project: Text Editor - determine the readability of text.
Flesch readability score.

Interned string: a single string object the Java's going to use whenever we don't explicitly create a new sting object with the keyword new and a call to the constructor.

.equal != '=='

length()
charAt()
indexOf()
split()
toCharArray(): returns a copy of the character array

in the enhanced for loop, the iterator is a copy, not the element itself.

Repetition: matches 1 or more spaces in a row? (" +")
Concatenation
Alternation
Character Classes: [] mean match "anything in the set"   "-" indicates a range   
Negation: "^" indicates NOT any characters in this set   [a-zA-Z]+   [^.?!]+
[0-9]+ caputures ANY non-negative integer

--Week III
Project: implement benchmarking to compare the running time of your basic document with the running time of the efficient document

Some factors that impact the performance of an algorithm
1. The number of operations
2. Focus on how performance scales
3. Go beyond input size

Operation: basic unit that doesn't change as the input changes.

Size of input is usually represented as n.

Asymptotic Analysis:


f(n) = O(g(n)) means, eventually, f(n) and g(n) grow in same way as their input grows
Big O notation captures the rate of growth of two functions

English reads: 1 million is big O of 1
Example: Initialization costs

1. Only keep dominant term
2. Drop constant

--- Big O with Nested Operations
Count from the inside out

--- Recursion
Is about breaking a big problem down into a smaller subprobem and then a manageable amount of work to incrementally change what we need to do.

--- Pitfalls
O(1) O(logn) O(n) O(n2)

--- Benchmarking
1. compiler
2. JVM 
3. OS
4. HW

--Week IV
---LL vs ArrayL
Two types of LL: 1. Doubly Linked List 2. Singly Linked List
Alternate Implementation: Sentinel/dummy nodes.

---Generics 
ListNode<E>     E is a type parameter
---Exception
Code methods declare that they throw exceptions? Checked Exception
For unchecked exception, declaration is not requireed, but OK

---
Recursive data type
No type parameter in the constructor header

---Test RoT
1. consider corner cases when testing
2. Test common case use
3. testing has costs

--Week V

What defines a tree?
# single root
# each node can have only one parent(except the root)
# no cycles in a tree

BT Each node needs:
1. a value
2. a parent 
3. a left child
4. a right child

Preorder Traversal:
1. self
2. left subtree
3. right subtree

DFT : pre, in, post
BFT:  Queue using LinkedList

---BST
