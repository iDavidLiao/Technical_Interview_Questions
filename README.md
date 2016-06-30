## Technical Interview Questions
Here you will find various technical interview questions and their solutions.

#### Linked Lists
* [Linked List Reversal](#linked-list-reversal)
\[[Solution](solutions/linked-list-reversal.cpp)\]

#### Stacks/Queues
* [Math Stack](#math-stack)
\[[Solution](solutions/math-stack.cpp)\]

#### Trees
* [Balanced Binary Tree](#balanced-binary-tree)
\[[Solution](solutions/balanced-binary-tree.cpp)\]

* [Balanced BST Generation](#balanced-bst-generation)
\[[Solution](solutions/balanced-bst-generation.cpp)\]

#### Miscellaneous
* [Integer Set Duplicates](#integer-set-duplicates)
\[[Solution](solutions/integer-set-duplicates.cpp)\]

* [Greatest Common Divisor](#greatest-common-divisor)
\[[Solution](solutions/greatest-common-divisor.cpp)\]

---------------
#### Linked List Reversal
Implement a function that reverses a singly linked list. For example:

    // Before reversal
    2 -> 15 -> 6 -> 1 -> [NULL]
    // After reversal
    1 -> 6 -> 15 -> 2 -> [NULL]

Assume that you are implementing a member function of a LinkedList class, where you have access to the private instance variable `head`. There is no instance variable that holds the size. You must modify the data structure, not return a copy. Use the following function declaration:

    void reverse();

\[[Solution](solutions/linked-list-reversal.cpp)\]

---------------
#### Linked List Common Ancestors


![Linked List Common Ancestors Image](/assets/linked-list-common-ancestors.png)

\[[Solution](solutions/linked-list-common-ancestors.cpp)\]

---------------
#### Math Stack
Implement a class called `MathStack` that allows for certain operationsGiven a stack of integers Use the [STL stack](http://www.cplusplus.com/reference/stack/stack/) and its provided functionality to find the minimum element in a stack.

You may ONLY use stacks to complete this project (no other data structures, such as vectors or lists, are allowed). Moreover, the input stack MUST remain unchanged from its original state after the function returns; in other words, the stack has the same values in the same order after the function has completed.

\[[Solution](solutions/math-stack.cpp)\]

---------------
#### Balanced Binary Tree
Implement a function that, when  returns whether a binary tree is balanced or not.

An empty tree is considered height-balanced. A non-empty binary tree T is balanced if and only if (1) T's left and right subtrees are both balanced, and (2) the heights of T's left and right subtrees do not differ by more than 1.

\[[Solution](solutions/balanced-binary-tree.cpp)\]

---------------

#### Balanced BST Generation

Given a sorted vector, generate a balanced Binary Search Tree with minimal height.

\[[Solution](solutions/balanced-bst-generation.cpp)\]

---------------
#### Integer Set Duplicates
Based on a set containing integers from 1 to n (e.g., {1, 2, 3, 4}), you can create an array of n+1 integers that are selected from that set (e.g., [2, 3, 3, 1, 1], [4, 1, 3, 2, 4], [2, 2, 2, 2, 2]). Implement a function that finds *a* duplicate in a given array with such specifications.

\[[Solution](solutions/integer-set-duplicates.cpp)\]

---------------

#### Greatest Common Divisor

Write a function to compute the greatest common divisor (GCD) between two numbers. Recall that the GCD of two numbers, a and b, is defined as follows:

    gcd(a, b) = b               If a is divisible by b
    gcd(a, b) = gcd(b, a%b)     Otherwise

\[[Solution](solutions/greatest-common-divisor.cpp)\]
