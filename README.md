# Data_Structures_and_Performance
by University of California, San Diego

Week II
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

Week III
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
