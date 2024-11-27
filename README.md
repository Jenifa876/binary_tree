# binary_tree
##Overview
This program implements a binary tree using classes in C++. It allows the user to:

Create a binary tree interactively.
Perform a preorder traversal of the tree to display its elements.
Program Structure
##Node Class:

Represents a single node in the binary tree.
Contains:
data: Holds the integer value of the node.
left and right: Pointers to the left and right children, respectively.
Constructor initializes data and sets left and right pointers to NULL.
##Tree Class:

Implements the binary tree and its operations.
Contains:
a[10]: Array-based queue to assist in level-order (breadth-first) insertion.
front and rear: Indices for managing the queue.
##Functions:
enqueue(Node* ptr): Adds a node pointer to the queue.
dequeue(): Removes and returns a node pointer from the queue.
isempty(): Checks if the queue is empty.
create(): Allows the user to create a binary tree interactively. Input -1 is used to denote no child.
preorder(Node* root): Performs a preorder traversal (Root-Left-Right) of the binary tree.
main() Function:

Creates a Tree object.
Builds the binary tree interactively.
Displays the preorder traversal of the tree.
