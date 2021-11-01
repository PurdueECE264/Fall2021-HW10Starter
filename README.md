# Who Gets the Cake (Part 2)

Learning Goals 
==============

* Insert and delete nodes in a linked list 

Changes from HW03Cake
=====================

In HW03Cake, an array is used to keep track who is still in the
game. In this assignment, a linked list is used.  The output of your
program should match the output of HW03Cake. In addition, the linked
list is printed every time one number is removed.

The files in `expected` directory have `-DDEBUG` in `Makefile` to turn
on the code printing the lists starting from the nodes to be
eliminated.  If `Makefile` does not have `-DDEBUG`, the outputs should
be the same as the files in HW03Cake.

Initialize Pointers
===================

You should *always* initialize pointers to NULL. Many students lose
points unnecessarily because they do not initialize pointers to
NULL. Uninitialized pointers can make your programs' behavior
unpredictable.  Many students lose points due to uninitialized
pointers.

Printing ListNode
===================

You should call `printListNode` each time BEFORE you delete any node 
and print the node value. In the expected files, `printListNode` is not
called for the last value in the list. Follow the 
expected files format. You can turn on the DEBUG flag in your Makefile
for printing.

You must not use a circular linked list for this assignment. The
`printListNode` does not work if the input is a circular linked
list. Yuo must not modify the `printListNode` function.

