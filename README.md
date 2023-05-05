Download Link: https://assignmentchef.com/product/solved-csi2110-lab5-binary-tree-traversals-and-iterators
<br>
<h3>Binary tree traversals</h3>

During lectures, we have discussed binary tree traversals. Your first task is to implement recursive methods to do preorder, inorder and postorder traversals. This should be a simple task, based on pseudocodes seen in lecture, and take only a few minutes to code and test. More specifically complete the following methods inside LikedBinarySearchTree class:

<ul>

 <li>void preorderRecursive(Node)</li>

 <li>void inorderRecursive(Node)</li>

 <li>void postorderRecursive(Node)</li>

 <li></li>

 <li></li>

 <li>Binary tree iterators In a previous course, you probably have studied the concept of an iterator for a class; you might have studied in more detail list iterators.</li>

</ul>

<h3>In this lab you will apply the concept of an iterator for a binary tree. While a list iterator is a way to move through elements of a list from beginning to end, for a tree there are many ways to move from node to node.For this part you will implement two types of iterators: a preorder and an order iterator.</h3>

<strong>You may need to review <a href="https://docs.oracle.com/javase/7/docs/api/java/util/Iterator.html">information about the Interface Iterator&amp;ltE&amp;gt</a> provided in package java.util. Your TA will briefly review iterators during the lab. Your iterators will implement this interface, so you need to provide the the constructor plus methods hasNext() and next() for each iterator implemented. </strong>

<strong>The hardest method to implement for class InorderIterator implements Iterator is next() as it entails to figure out from the current node of your iterator, who is the next node to be visited in an inorder traversal of the tree. The same is true for class PreorderIterator implements Iterator. </strong>

<strong>The <a href="DGD5-traversalNext.txt">pseudocode of the algorithms to do these tasks have been discussed in your DGD</a> and will also be reviewed by your TA in the lab. </strong>

<strong>Task details: </strong>

<h3>1.     Review class LinkedBinaryTree and class TestTree.</h3>

<h3>2.     Implement the traversal algorithms; test them using TestTree class.</h3>

Implement preorderNext and inorderNext iterators; based on pseudocodes given. These are nontrivial algorithms