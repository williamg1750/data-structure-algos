# **Binary Tree**

Generally a normal tree can have multiple childrens
In a binary tree each node can at most have 2 children

example of a binary tree
![Binary Tree](https://media.geeksforgeeks.org/wp-content/cdn-uploads/binary-tree-to-DLL.png)

## **Binary Search Tree**

Binary Search Tree is a Binary Tree with a few extra rules
Every node to the left of a parent node is always less than the parent, and
Every node to the right of a parent node is always greater than the parent.
![Binary Tree](https://media.geeksforgeeks.org/wp-content/uploads/BSTSearch.png)

The **Big O **of binary search tree is **O(log N)** which is really good for lookup or inserting
since its near O(1)
O(log N) is for best case and also avg case
worst case it can be O(N) if its a unbalanced binary search tree
![unbalanced binary search tree](http://kamalmeet.com/wp-content/uploads/2015/08/bst_unbalanced.png)

##### A great use for a Binary Search Tree is that the data that is stored should be compairable and it makes it more efficent to check for the value that you are looking for hence the rules of the binary search tree
