[https://leetcode.com/problems/maximum-depth-of-binary-tree/description/](https://leetcode.com/problems/maximum-depth-of-binary-tree/description/)
**题目描述**

>输入一棵二叉树，求该树的深度。
>
>从根结点到叶结点依次经过的结点（含根、叶结点）形成树的一条路径，最长路径的长度为树的深度。







#分析
-------

对二叉树进行层次遍历，维护一个层数计数器，每次进入一层就增加1，从而得到二叉树的层数。
当然如果使用递归的话，思路就更简单了，返回左右子树中深度最大的那个

