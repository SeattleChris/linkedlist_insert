# linkedlist_insert

Given a pointer to the head node of a linked list and an integer to insert at a certain position, create a new node with the given integer as its `data` attribute, insert this node at the desired position, and return the head node.

A position of 0 indicates the head, a position of 1 indicates one node away from the head, and so on. The head pointer given may be null, meaning that the initial list is empty.

## Function Description

Complete the function `insertNodeAtPosition` with the following parameters:

* SinglyLinkedListNode pointer head: a reference to the head of the list
* data: an integer value to insert as data in the new node
* position: an integer position to insert the new node, zero-based indexing

### Returns

* A reference to the head of the revised list

## Input Format

The first line contains an integer `n`, the number of elements in the linked list.
Each of the next `n` lines contains an integer SinglyLinkedListNode[i].data.
The next line contains an integer `data`, the data of the node that is to be inserted.
The last line contains an integer `position`.

## Constraints

* 1 <= n <= 1000
* 1 <= SinglyLinkedListNode[i].data <= 1000
* 0 <= position <= n
