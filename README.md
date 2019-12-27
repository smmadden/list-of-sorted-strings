# Doubly Linked List of Sorted Strings
###### _Completed Dec. 14, 2019_

For this project I wrote a doubly linked list program that implements Insert, Member, Delete, and Free_list, stores a list of strings, and stores the strings in increasing alphabetical order.

Each node in the list, defined by the `list_node_s` struct, is linked to both its immediate successor and its immediate predecessor and stores a string as its data type. The first node in the list has a NULL predecessor pointer, and the last node in the list has a NULL successor pointer. Furthermore, the list as a whole, stored in a `list_s` struct, is defined by two pointers: a head pointer which references the first node in the list, and a tail pointer which references the last node in the list.

The input to the program is the commands the user enters. The user is able to insert a string of their choice into the list, print the entire list in order, check if a string is a member of the list, delete a string from the list, free the entire list, or quit the program.
