Trees are data structures that consist of nodes just like a links listed, but they're in a parent child relationship. We basically end up with branches.So from one node we can have it connect to one other node or two or three or 10 or zero nodes.But we end up with these branching structures, hence the name tree.

Rules for defining a tree
-A node can only point to a child (if they point to siblings that is not a tree its a graph)
-A tree can only have one root node (the top parent)

Terms
**Child** is directly connected to another node moving away from the Root
**Parent** is the converse notion of a child
**Sibling** is a group of nodes with the same parent
**Leaf** is a node with no children
**Edge** is the connection between one node and the other node

An example of a tree
` 8 <---- Root and also parent
/ \ <---- edge (they only point down to the children)
5 15 <----Child and also parent (5 and 15 are siblings)
/ \ / \
2 7 11 17 <----Child/sibling/ and also a leaf since they dont have children
