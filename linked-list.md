# Singly-Linked-List

Linked List can be defined as collection of objects called nodes that are randomly stored in the memory.
A node contains two fields i.e. data stored at that particular address and the pointer which contains the address of the next node in the memory.
The last node of the list contains pointer to the null.


The syntax for creating a node
struct Node
{
  int Data;
  Struct Node *next;
};
The code will create a data type Node, which  will be able to store two values-:
int value – data
pointer value – address of the next node

Insertion of a node

struct node   
{  
    int data;   
    struct node *next;  
};  
struct node *head, *ptr;   
ptr = (struct node *)malloc(sizeof(struct node *));  
