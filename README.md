# C - Binary trees

.Project done during Full Stack Software Engineering studies at ALx Africa School. It aims to learn about what is a binary tree, the different traversal methods to go through a binary tree and the different types of binary trees (complete, full, perfect and balanced).

# Tests ✔️

.[tests],(https://github.com/Thyrox02/binary_trees/tree/master/tests): Folder of test files for all tasks. Provided by ALX.

# Technologies
.Scripts written in Bash 4.3.11(1)
.C file are compile using gcc, using the options -Wall -Werror -Wextra -pedantic-std=gnu89
. Tested on Ubuntu 14.04 LTS

# Header File 📁
.[binary_trees.h],(https://github.com/Thyrox02/binary_trees/blob/master/binary_trees.h):Header file containing definitions and prototypes for all types and functions written for the project.

Data Structures

struct binary_tree_s
{
    int n;
    struct binary_tree_s *parent;
    struct binary_tree_s *left;
    struct binary_tree_s *right;
};

typedef struct binary_tree_s binary_tree_t;
typedef struct binary_tree_s bst_t;
typedef struct binary_tree_s avl_t;
typedef struct binary_tree_s heap_t;

# Tasks 📃

0. New node
   .[0-binary_tree_node.c] +k :C function that creates a binary tree node with a given parent and value.
Returns a pointer to the new node, or NULL on failure.















# AUTHOR
JIMOH LUKMAN OLAMILEKAN 
