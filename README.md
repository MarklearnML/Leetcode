# 目录
*  [数组/字符串](#数组/字符串)
*  [双指针](#双指针)
*  [滑动窗口](#滑动窗口)
*  [矩阵](#矩阵)
*  [哈希表](#哈希表)
*  [区间](#区间)
*  [栈和队列](#栈和队列)
*  [链表](#链表)
*  [二叉树](#二叉树)
*  [图](#图)
*  [回溯](#回溯)
*  [贪心算法](#贪心算法)
*  [分治](#分治)
*  [查找](#查找)
*  [动态规划](#动态规划)
*  [单调栈](#单调栈)

# 数组/字符串
双指针：快慢指针，头尾指针
  * [合并两个有序数组(双指针)](https://github.com/MarklearnML/Leetcode/blob/main/%E6%95%B0%E7%BB%84%E3%80%81%E5%AD%97%E7%AC%A6%E4%B8%B2/%E5%90%88%E5%B9%B6%E4%B8%A4%E4%B8%AA%E6%9C%89%E5%BA%8F%E6%95%B0%E7%BB%84)
  * [移除元素(双指针)](https://github.com/MarklearnML/Leetcode/blob/main/%E6%95%B0%E7%BB%84%E3%80%81%E5%AD%97%E7%AC%A6%E4%B8%B2/%E7%A7%BB%E9%99%A4%E5%85%83%E7%B4%A0)
  * [删除有序数组中的重复项(双指针)](https://github.com/MarklearnML/Leetcode/blob/main/%E6%95%B0%E7%BB%84%E3%80%81%E5%AD%97%E7%AC%A6%E4%B8%B2/%E5%88%A0%E9%99%A4%E6%9C%89%E5%BA%8F%E6%95%B0%E7%BB%84%E4%B8%AD%E7%9A%84%E9%87%8D%E5%A4%8D%E9%A1%B9)
  * [删除有序数组中的重复项 II(双指针)](https://github.com/MarklearnML/Leetcode/blob/main/%E6%95%B0%E7%BB%84%E3%80%81%E5%AD%97%E7%AC%A6%E4%B8%B2/%E5%88%A0%E9%99%A4%E6%9C%89%E5%BA%8F%E6%95%B0%E7%BB%84%E4%B8%AD%E7%9A%84%E9%87%8D%E5%A4%8D%E9%A1%B9%20II)
  * [多数元素(哈希表、排序法、投票法、分治法)](https://github.com/MarklearnML/Leetcode/blob/main/%E6%95%B0%E7%BB%84%E3%80%81%E5%AD%97%E7%AC%A6%E4%B8%B2/%E5%A4%9A%E6%95%B0%E5%85%83%E7%B4%A0)
  * [轮转数组(环状替换、数组翻转)](https://github.com/MarklearnML/Leetcode/blob/main/%E6%95%B0%E7%BB%84%E3%80%81%E5%AD%97%E7%AC%A6%E4%B8%B2/%E8%BD%AE%E8%BD%AC%E6%95%B0%E7%BB%84)
  * [买卖股票的最佳时机(一次遍历*)](https://github.com/MarklearnML/Leetcode/tree/main/%E6%95%B0%E7%BB%84%E3%80%81%E5%AD%97%E7%AC%A6%E4%B8%B2)
  * [买卖股票的最佳时机II(一次遍历, 动态规划*， 正数相加*)](https://github.com/MarklearnML/Leetcode/blob/main/%E6%95%B0%E7%BB%84%E3%80%81%E5%AD%97%E7%AC%A6%E4%B8%B2/%E4%B9%B0%E5%8D%96%E8%82%A1%E7%A5%A8%E7%9A%84%E6%9C%80%E4%BD%B3%E6%97%B6%E6%9C%BAII)
  * [跳跃游戏(动态规划*，贪心)](https://github.com/MarklearnML/Leetcode/blob/main/%E6%95%B0%E7%BB%84%E3%80%81%E5%AD%97%E7%AC%A6%E4%B8%B2/%E8%B7%B3%E8%B7%83%E6%B8%B8%E6%88%8F)
  * [h指数(排序)](https://github.com/MarklearnML/Leetcode/blob/main/%E6%95%B0%E7%BB%84%E3%80%81%E5%AD%97%E7%AC%A6%E4%B8%B2/h%E6%8C%87%E6%95%B0)
  * [O(1)时间插入、删除和获取随机变量(变长数组+哈希表)](https://github.com/MarklearnML/Leetcode/blob/main/%E6%95%B0%E7%BB%84%E3%80%81%E5%AD%97%E7%AC%A6%E4%B8%B2/O(1)%20%E6%97%B6%E9%97%B4%E6%8F%92%E5%85%A5%E3%80%81%E5%88%A0%E9%99%A4%E5%92%8C%E8%8E%B7%E5%8F%96%E9%9A%8F%E6%9C%BA%E5%85%83%E7%B4%A0)
  * [除自身以外数组的乘积(动态规划*左右累乘)](https://github.com/MarklearnML/Leetcode/blob/main/%E6%95%B0%E7%BB%84%E3%80%81%E5%AD%97%E7%AC%A6%E4%B8%B2/%E9%99%A4%E8%87%AA%E8%BA%AB%E4%BB%A5%E5%A4%96%E6%95%B0%E7%BB%84%E7%9A%84%E4%B9%98%E7%A7%AF)
  * [加油站(一次遍历)](https://github.com/MarklearnML/Leetcode/blob/main/%E6%95%B0%E7%BB%84%E3%80%81%E5%AD%97%E7%AC%A6%E4%B8%B2/%E5%8A%A0%E6%B2%B9%E7%AB%99)
  * [分发糖果(一次遍历*分阶段计算、二次遍历**)](https://github.com/MarklearnML/Leetcode/blob/main/%E6%95%B0%E7%BB%84%E3%80%81%E5%AD%97%E7%AC%A6%E4%B8%B2/%E5%88%86%E5%8F%91%E7%B3%96%E6%9E%9C)
  * [接雨水(二次遍历*)](https://github.com/MarklearnML/Leetcode/blob/main/%E6%95%B0%E7%BB%84%E3%80%81%E5%AD%97%E7%AC%A6%E4%B8%B2/%E6%8E%A5%E9%9B%A8%E6%B0%B4)
  * [二分查找](https://github.com/MarklearnML/Leetcode/blob/main/%E6%95%B0%E7%BB%84%E3%80%81%E5%AD%97%E7%AC%A6%E4%B8%B2/%E4%BA%8C%E5%88%86%E6%9F%A5%E6%89%BE)
  * [有序数组的平方](https://github.com/MarklearnML/Leetcode/blob/main/%E6%95%B0%E7%BB%84%E3%80%81%E5%AD%97%E7%AC%A6%E4%B8%B2/%E6%9C%89%E5%BA%8F%E6%95%B0%E7%BB%84%E7%9A%84%E5%B9%B3%E6%96%B9)
  * [长度最小的子数组(滑动窗口)](https://github.com/MarklearnML/Leetcode/blob/main/%E6%95%B0%E7%BB%84%E3%80%81%E5%AD%97%E7%AC%A6%E4%B8%B2/%E9%95%BF%E5%BA%A6%E6%9C%80%E5%B0%8F%E7%9A%84%E5%AD%90%E6%95%B0%E7%BB%84)
  * [螺旋矩阵(循环不变量*)](https://github.com/MarklearnML/Leetcode/blob/main/%E6%95%B0%E7%BB%84%E3%80%81%E5%AD%97%E7%AC%A6%E4%B8%B2/%E8%9E%BA%E6%97%8B%E7%9F%A9%E9%98%B5)
  * [替换空格](https://github.com/MarklearnML/Leetcode/blob/main/%E6%95%B0%E7%BB%84%E3%80%81%E5%AD%97%E7%AC%A6%E4%B8%B2/%E6%9B%BF%E6%8D%A2%E7%A9%BA%E6%A0%BC)
  * [反转字符串中的单词(分步写函数：去除空格、整体反转、单词反转、反转函数用双指针)](https://github.com/MarklearnML/Leetcode/blob/main/%E6%95%B0%E7%BB%84%E3%80%81%E5%AD%97%E7%AC%A6%E4%B8%B2/%E5%8F%8D%E8%BD%AC%E5%AD%97%E7%AC%A6%E4%B8%B2%E4%B8%AD%E7%9A%84%E5%8D%95%E8%AF%8D)
  * [左旋转字符串(反转再反转)](https://github.com/MarklearnML/Leetcode/blob/main/%E6%95%B0%E7%BB%84%E3%80%81%E5%AD%97%E7%AC%A6%E4%B8%B2/%E5%B7%A6%E6%97%8B%E8%BD%AC%E5%AD%97%E7%AC%A6%E4%B8%B2)
# 双指针
# 滑动窗口
# 矩阵
# 哈希表
哈希表的类型：数组、set、map
  * [有效的字母异位词(哈希表)](https://github.com/MarklearnML/Leetcode/blob/main/%E5%93%88%E5%B8%8C%E8%A1%A8/%E6%9C%89%E6%95%88%E7%9A%84%E5%AD%97%E6%AF%8D%E5%BC%82%E4%BD%8D%E8%AF%8D)
  * [两个数组的交集](https://github.com/MarklearnML/Leetcode/blob/main/%E5%93%88%E5%B8%8C%E8%A1%A8/%E4%B8%A4%E4%B8%AA%E6%95%B0%E7%BB%84%E7%9A%84%E4%BA%A4%E9%9B%86)
  * [快乐数](https://github.com/MarklearnML/Leetcode/blob/main/%E5%93%88%E5%B8%8C%E8%A1%A8/%E5%BF%AB%E4%B9%90%E6%95%B0)
  * [四数之和(分组+哈希表*)](https://github.com/MarklearnML/Leetcode/blob/main/%E5%93%88%E5%B8%8C%E8%A1%A8/%E5%9B%9B%E6%95%B0%E4%B9%8B%E5%92%8CII)
  * [赎金信](https://github.com/MarklearnML/Leetcode/blob/main/%E5%93%88%E5%B8%8C%E8%A1%A8/%E8%B5%8E%E9%87%91%E4%BF%A1)
  * [三数之和(固定一个另外两个用双指针、去重*)](https://github.com/MarklearnML/Leetcode/blob/main/%E5%93%88%E5%B8%8C%E8%A1%A8/%E4%B8%89%E6%95%B0%E4%B9%8B%E5%92%8C)
  * [四数之和(排序+双指针、去重剪枝*)](https://github.com/MarklearnML/Leetcode/blob/main/%E5%93%88%E5%B8%8C%E8%A1%A8/%E5%9B%9B%E6%95%B0%E4%B9%8B%E5%92%8C)
# 区间
# 栈和队列
栈是容器适配器，底层容器使用不同的容器，导致栈内数据在内存中是不是连续分布。    <br>
缺省情况下，默认底层容器是deque，那么deque的在内存中的数据分布是什么样的呢？ 答案是：不连续的，下文也会提到deque。   <br>
经典例题：括号匹配问题、栈在系统中的应用、滑动窗口最大值、前k个最值、字符串去重问题    <br>
  * [用栈实现队列](https://github.com/MarklearnML/Leetcode/blob/main/%E6%A0%88%E4%B8%8E%E9%98%9F%E5%88%97/%E7%94%A8%E6%A0%88%E5%AE%9E%E7%8E%B0%E9%98%9F%E5%88%97)
  * [用队列实现栈(一个队列就够)](https://github.com/MarklearnML/Leetcode/blob/main/%E6%A0%88%E4%B8%8E%E9%98%9F%E5%88%97/%E7%94%A8%E9%98%9F%E5%88%97%E5%AE%9E%E7%8E%B0%E6%A0%88)
  * [有效的括号](https://github.com/MarklearnML/Leetcode/blob/main/%E6%A0%88%E4%B8%8E%E9%98%9F%E5%88%97/%E6%9C%89%E6%95%88%E7%9A%84%E6%8B%AC%E5%8F%B7)
  * [删除字符串中所有相邻重复项](https://github.com/MarklearnML/Leetcode/blob/main/%E6%A0%88%E4%B8%8E%E9%98%9F%E5%88%97/%E5%88%A0%E9%99%A4%E5%AD%97%E7%AC%A6%E4%B8%B2%E4%B8%AD%E6%89%80%E6%9C%89%E7%9B%B8%E9%82%BB%E9%87%8D%E5%A4%8D%E9%A1%B9)
  * [逆波兰表达式求值](https://github.com/MarklearnML/Leetcode/blob/main/%E6%A0%88%E4%B8%8E%E9%98%9F%E5%88%97/%E9%80%86%E6%B3%A2%E5%85%B0%E8%A1%A8%E8%BE%BE%E5%BC%8F%E6%B1%82%E5%80%BC)
  * [滑动窗口最大值(*单调队列)](https://github.com/MarklearnML/Leetcode/blob/main/%E6%A0%88%E4%B8%8E%E9%98%9F%E5%88%97/%E6%BB%91%E5%8A%A8%E7%AA%97%E5%8F%A3%E6%9C%80%E5%A4%A7%E5%80%BC)
  * [前k个高频元素(*优先级队列)](https://github.com/MarklearnML/Leetcode/blob/main/%E6%A0%88%E4%B8%8E%E9%98%9F%E5%88%97/%E5%89%8Dk%E4%B8%AA%E9%AB%98%E9%A2%91%E5%85%83%E7%B4%A0)
# 链表
链表的类型: 单链表、双链表、循环链表   <br>
链表的操作：增删改查   <br>
  * [移除链表元素](https://github.com/MarklearnML/Leetcode/blob/main/%E9%93%BE%E8%A1%A8/%E7%A7%BB%E9%99%A4%E9%93%BE%E8%A1%A8%E5%85%83%E7%B4%A0)
  * [设计链表(虚拟头结点)](https://github.com/MarklearnML/Leetcode/blob/main/%E9%93%BE%E8%A1%A8/%E8%AE%BE%E8%AE%A1%E9%93%BE%E8%A1%A8)
  * [反转链表(双指针法)](https://github.com/MarklearnML/Leetcode/blob/main/%E9%93%BE%E8%A1%A8/%E5%8F%8D%E8%BD%AC%E9%93%BE%E8%A1%A8)
  * [删除链表的倒数第N个结点(滑动窗口)](https://github.com/MarklearnML/Leetcode/blob/main/%E9%93%BE%E8%A1%A8/%E5%88%A0%E9%99%A4%E9%93%BE%E8%A1%A8%E7%9A%84%E5%80%92%E6%95%B0%E7%AC%AC%20N%20%E4%B8%AA%E7%BB%93%E7%82%B9)
  * [链表相交](https://github.com/MarklearnML/Leetcode/blob/main/%E9%93%BE%E8%A1%A8/%E9%93%BE%E8%A1%A8%E7%9B%B8%E4%BA%A4)
  * [环形链表(快慢指针*、哈希表法)](https://github.com/MarklearnML/Leetcode/blob/main/%E9%93%BE%E8%A1%A8/%E7%8E%AF%E5%BD%A2%E9%93%BE%E8%A1%A8II)
# 二叉树
题目跟一层有关的均可用层次遍历(例：层里最大值，层里平均值，右视图，左视图)    <br>
二叉搜索树的中序遍历是有序的    <br>
  * [二叉树的递归遍历](https://github.com/MarklearnML/Leetcode/blob/main/%E4%BA%8C%E5%8F%89%E6%A0%91/%E4%BA%8C%E5%8F%89%E6%A0%91%E7%9A%84%E9%80%92%E5%BD%92%E9%81%8D%E5%8E%86)
  * [二叉树的迭代遍历(*用栈来存放树结点)](https://github.com/MarklearnML/Leetcode/blob/main/%E4%BA%8C%E5%8F%89%E6%A0%91/%E4%BA%8C%E5%8F%89%E6%A0%91%E7%9A%84%E8%BF%AD%E4%BB%A3%E9%81%8D%E5%8E%86)
  * [二叉树的层次遍历(队列)](https://github.com/MarklearnML/Leetcode/blob/main/%E4%BA%8C%E5%8F%89%E6%A0%91/%E4%BA%8C%E5%8F%89%E6%A0%91%E7%9A%84%E5%B1%82%E6%AC%A1%E9%81%8D%E5%8E%86)
  * [翻转二叉树(递归法、迭代法)](https://github.com/MarklearnML/Leetcode/blob/main/%E4%BA%8C%E5%8F%89%E6%A0%91/%E7%BF%BB%E8%BD%AC%E4%BA%8C%E5%8F%89%E6%A0%91)
  * [对称二叉树](https://github.com/MarklearnML/Leetcode/blob/main/%E4%BA%8C%E5%8F%89%E6%A0%91/%E5%AF%B9%E7%A7%B0%E4%BA%8C%E5%8F%89%E6%A0%91)
  * [二叉树的最大深度](https://github.com/MarklearnML/Leetcode/blob/main/%E4%BA%8C%E5%8F%89%E6%A0%91/%E4%BA%8C%E5%8F%89%E6%A0%91%E7%9A%84%E6%9C%80%E5%A4%A7%E6%B7%B1%E5%BA%A6)
  * [二叉树的最小深度](https://github.com/MarklearnML/Leetcode/blob/main/%E4%BA%8C%E5%8F%89%E6%A0%91/%E4%BA%8C%E5%8F%89%E6%A0%91%E7%9A%84%E6%9C%80%E5%B0%8F%E6%B7%B1%E5%BA%A6)
  * [完全二叉树的节点个数(递归+完全二叉树的性质)](https://github.com/MarklearnML/Leetcode/blob/main/%E4%BA%8C%E5%8F%89%E6%A0%91/%E5%AE%8C%E5%85%A8%E4%BA%8C%E5%8F%89%E6%A0%91%E7%9A%84%E8%8A%82%E7%82%B9%E4%B8%AA%E6%95%B0)
  * [二叉树的所有路径](https://github.com/MarklearnML/Leetcode/blob/main/%E4%BA%8C%E5%8F%89%E6%A0%91/%E4%BA%8C%E5%8F%89%E6%A0%91%E7%9A%84%E6%89%80%E6%9C%89%E8%B7%AF%E5%BE%84)
  * [左叶子之和](https://github.com/MarklearnML/Leetcode/blob/main/%E4%BA%8C%E5%8F%89%E6%A0%91/%E5%B7%A6%E5%8F%B6%E5%AD%90%E4%B9%8B%E5%92%8C)
  * [找树左下角的值](https://github.com/MarklearnML/Leetcode/blob/main/%E4%BA%8C%E5%8F%89%E6%A0%91/%E6%89%BE%E6%A0%91%E5%B7%A6%E4%B8%8B%E8%A7%92%E7%9A%84%E5%80%BC)
  * [从中序与后序遍历序列构造二叉树(*递归)](https://github.com/MarklearnML/Leetcode/blob/main/%E4%BA%8C%E5%8F%89%E6%A0%91/%E4%BB%8E%E4%B8%AD%E5%BA%8F%E4%B8%8E%E5%90%8E%E5%BA%8F%E9%81%8D%E5%8E%86%E5%BA%8F%E5%88%97%E6%9E%84%E9%80%A0%E4%BA%8C%E5%8F%89%E6%A0%91)
  * [最大二叉树](https://github.com/MarklearnML/Leetcode/blob/main/%E4%BA%8C%E5%8F%89%E6%A0%91/%E6%9C%80%E5%A4%A7%E4%BA%8C%E5%8F%89%E6%A0%91)
  * [合并二叉树](https://github.com/MarklearnML/Leetcode/blob/main/%E4%BA%8C%E5%8F%89%E6%A0%91/%E5%90%88%E5%B9%B6%E4%BA%8C%E5%8F%89%E6%A0%91)
  * [二叉搜索树的搜索](https://github.com/MarklearnML/Leetcode/blob/main/%E4%BA%8C%E5%8F%89%E6%A0%91/%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91%E7%9A%84%E6%90%9C%E7%B4%A2)
  * [验证二叉搜索树(中序遍历)](https://github.com/MarklearnML/Leetcode/blob/main/%E4%BA%8C%E5%8F%89%E6%A0%91/%E9%AA%8C%E8%AF%81%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91)
  * [二叉搜索树的最小绝对差(中序遍历)](https://github.com/MarklearnML/Leetcode/blob/main/%E4%BA%8C%E5%8F%89%E6%A0%91/%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91%E7%9A%84%E6%9C%80%E5%B0%8F%E7%BB%9D%E5%AF%B9%E5%B7%AE)
  * [二叉搜索树中的众数](https://github.com/MarklearnML/Leetcode/blob/main/%E4%BA%8C%E5%8F%89%E6%A0%91/%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91%E7%9A%84%E4%BC%97%E6%95%B0)
  * [二叉树的最近公共祖先](https://github.com/MarklearnML/Leetcode/blob/main/%E4%BA%8C%E5%8F%89%E6%A0%91/%E4%BA%8C%E5%8F%89%E6%A0%91%E7%9A%84%E6%9C%80%E8%BF%91%E5%85%AC%E5%85%B1%E7%A5%96%E5%85%88)
  * [二叉搜索树的最近公共祖先*](https://github.com/MarklearnML/Leetcode/blob/main/%E4%BA%8C%E5%8F%89%E6%A0%91/%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91%E7%9A%84%E6%9C%80%E8%BF%91%E5%85%AC%E5%85%B1%E7%A5%96%E5%85%88)
  * [二叉搜索树中的插入操作*](https://github.com/MarklearnML/Leetcode/blob/main/%E4%BA%8C%E5%8F%89%E6%A0%91/%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91%E4%B8%AD%E7%9A%84%E6%8F%92%E5%85%A5%E6%93%8D%E4%BD%9C)
  * [删除二叉搜索树中的节点*](https://github.com/MarklearnML/Leetcode/blob/main/%E4%BA%8C%E5%8F%89%E6%A0%91/%E5%88%A0%E9%99%A4%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91%E4%B8%AD%E7%9A%84%E8%8A%82%E7%82%B9)
  * [修剪二叉搜索树*](https://github.com/MarklearnML/Leetcode/blob/main/%E4%BA%8C%E5%8F%89%E6%A0%91/%E4%BF%AE%E5%BB%BA%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91)
  * [将有序数组转换为二叉搜索树](https://github.com/MarklearnML/Leetcode/blob/main/%E4%BA%8C%E5%8F%89%E6%A0%91/%E5%B0%86%E6%9C%89%E5%BA%8F%E6%95%B0%E7%BB%84%E8%BD%AC%E6%8D%A2%E4%B8%BA%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91)
  * [把二叉搜索树转换为累加树(*反中序遍历)](https://github.com/MarklearnML/Leetcode/blob/main/%E4%BA%8C%E5%8F%89%E6%A0%91/%E6%8A%8A%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91%E8%BD%AC%E6%8D%A2%E4%B8%BA%E7%B4%AF%E5%8A%A0%E6%A0%91)
  
# 图
# 回溯
排列和组合，所有需要暴力枚举的题目都可想到回溯，回溯无非就是暴力枚举+剪枝   <br>
   * [组合(递归枚举)](https://github.com/MarklearnML/Leetcode/blob/main/%E5%9B%9E%E6%BA%AF/%E7%BB%84%E5%90%88)
   * [组合总和 III](https://github.com/MarklearnML/Leetcode/blob/main/%E5%9B%9E%E6%BA%AF/%E7%BB%84%E5%90%88%E6%80%BB%E5%92%8C%20III)
   * [电话号码的字母组合](https://github.com/MarklearnML/Leetcode/blob/main/%E5%9B%9E%E6%BA%AF/%E7%94%B5%E8%AF%9D%E5%8F%B7%E7%A0%81%E7%9A%84%E5%AD%97%E6%AF%8D%E7%BB%84%E5%90%88)
   * [组合总和](https://github.com/MarklearnML/Leetcode/blob/main/%E5%9B%9E%E6%BA%AF/%E7%BB%84%E5%90%88%E6%80%BB%E5%92%8C)
   * [组合总和 II](https://github.com/MarklearnML/Leetcode/blob/main/%E5%9B%9E%E6%BA%AF/%E7%BB%84%E5%90%88%E6%80%BB%E5%92%8C%20II)
   * [分割回文串](https://github.com/MarklearnML/Leetcode/blob/main/%E5%9B%9E%E6%BA%AF/%E5%88%86%E5%89%B2%E5%9B%9E%E6%96%87%E4%B8%B2)
   * [复原IP地址**](https://github.com/MarklearnML/Leetcode/blob/main/%E5%9B%9E%E6%BA%AF/%E5%A4%8D%E5%8E%9F%20IP%20%E5%9C%B0%E5%9D%80)
   * [子集](https://github.com/MarklearnML/Leetcode/blob/main/%E5%9B%9E%E6%BA%AF/%E5%AD%90%E9%9B%86)
   * [子集II(*排序+剪枝)](https://github.com/MarklearnML/Leetcode/blob/main/%E5%9B%9E%E6%BA%AF/%E5%AD%90%E9%9B%86II)
   * [递增子序列](https://github.com/MarklearnML/Leetcode/blob/main/%E5%9B%9E%E6%BA%AF/%E9%80%92%E5%A2%9E%E5%AD%90%E5%BA%8F%E5%88%97)
   * [全排列](https://github.com/MarklearnML/Leetcode/blob/main/%E5%9B%9E%E6%BA%AF/%E5%85%A8%E6%8E%92%E5%88%97)
   * [全排列II(*排序+剪枝)](https://github.com/MarklearnML/Leetcode/blob/main/%E5%9B%9E%E6%BA%AF/%E5%85%A8%E6%8E%92%E5%88%97II)
   * [重新安排行程(***需要用到unordered_map和map，直接遍历map的key，大大的缩减了时间)](https://github.com/MarklearnML/Leetcode/blob/main/%E5%9B%9E%E6%BA%AF/%E9%87%8D%E6%96%B0%E5%AE%89%E6%8E%92%E8%A1%8C%E7%A8%8B)
   * [N皇后](https://github.com/MarklearnML/Leetcode/blob/main/%E5%9B%9E%E6%BA%AF/N%E7%9A%87%E5%90%8E)
   * [解数独(***遍历+递归，不用占有太多的内存)](https://github.com/MarklearnML/Leetcode/blob/main/%E5%9B%9E%E6%BA%AF/%E8%A7%A3%E6%95%B0%E7%8B%AC)
# 贪心算法
贪心的题目如果不要求顺序，先排序可能更好做  <br>
一次遍历，二次遍历   <br>
   * [分发饼干(*排序 + 双指针 + 贪心)](https://github.com/MarklearnML/Leetcode/blob/main/%E8%B4%AA%E5%BF%83%E7%AE%97%E6%B3%95/%E5%88%86%E5%8F%91%E9%A5%BC%E5%B9%B2)
   * [摆动序列](https://github.com/MarklearnML/Leetcode/blob/main/%E8%B4%AA%E5%BF%83%E7%AE%97%E6%B3%95/%E6%91%86%E5%8A%A8%E5%BA%8F%E5%88%97)
   * [最大子数组和(贪心、动态规划)](https://github.com/MarklearnML/Leetcode/blob/main/%E8%B4%AA%E5%BF%83%E7%AE%97%E6%B3%95/%E6%9C%80%E5%A4%A7%E5%AD%90%E6%95%B0%E7%BB%84%E5%92%8C)
   * [买卖股票的最佳时机 II](https://github.com/MarklearnML/Leetcode/blob/main/%E8%B4%AA%E5%BF%83%E7%AE%97%E6%B3%95/%E4%B9%B0%E5%8D%96%E8%82%A1%E7%A5%A8%E7%9A%84%E6%9C%80%E4%BD%B3%E6%97%B6%E6%9C%BA%20II)
   * [跳跃游戏](https://github.com/MarklearnML/Leetcode/blob/main/%E8%B4%AA%E5%BF%83%E7%AE%97%E6%B3%95/%E8%B7%B3%E8%B7%83%E6%B8%B8%E6%88%8F)
   * [跳跃游戏II](https://github.com/MarklearnML/Leetcode/blob/main/%E8%B4%AA%E5%BF%83%E7%AE%97%E6%B3%95/%E8%B7%B3%E8%B7%83%E6%B8%B8%E6%88%8FII)
   * [K 次取反后最大化的数组和](https://github.com/MarklearnML/Leetcode/blob/main/%E8%B4%AA%E5%BF%83%E7%AE%97%E6%B3%95/K%20%E6%AC%A1%E5%8F%96%E5%8F%8D%E5%90%8E%E6%9C%80%E5%A4%A7%E5%8C%96%E7%9A%84%E6%95%B0%E7%BB%84%E5%92%8C)
   * [加油站](https://github.com/MarklearnML/Leetcode/blob/main/%E8%B4%AA%E5%BF%83%E7%AE%97%E6%B3%95/%E5%8A%A0%E6%B2%B9%E7%AB%99)
   * [分糖果(前后各自遍历)](https://github.com/MarklearnML/Leetcode/blob/main/%E8%B4%AA%E5%BF%83%E7%AE%97%E6%B3%95/%E5%88%86%E7%B3%96%E6%9E%9C)
   * [柠檬水找零](https://github.com/MarklearnML/Leetcode/blob/main/%E8%B4%AA%E5%BF%83%E7%AE%97%E6%B3%95/%E6%9F%A0%E6%AA%AC%E6%B0%B4%E6%89%BE%E9%9B%B6)
   * [根据身高重建队列(*排序+贪心)](https://github.com/MarklearnML/Leetcode/blob/main/%E8%B4%AA%E5%BF%83%E7%AE%97%E6%B3%95/%E6%A0%B9%E6%8D%AE%E8%BA%AB%E9%AB%98%E9%87%8D%E5%BB%BA%E9%98%9F%E5%88%97)
   * [用最少数量的箭引爆气球(*排序+贪心)](https://github.com/MarklearnML/Leetcode/blob/main/%E8%B4%AA%E5%BF%83%E7%AE%97%E6%B3%95/%E7%94%A8%E6%9C%80%E5%B0%91%E6%95%B0%E9%87%8F%E7%9A%84%E7%AE%AD%E5%BC%95%E7%88%86%E6%B0%94%E7%90%83)
   * [无重叠区间(排序+贪心)](https://github.com/MarklearnML/Leetcode/blob/main/%E8%B4%AA%E5%BF%83%E7%AE%97%E6%B3%95/%E6%97%A0%E9%87%8D%E5%8F%A0%E5%8C%BA%E9%97%B4)
   * [划分字母区间(***二次遍历，第一遍记录字母最远，第二遍记录分割线)](https://github.com/MarklearnML/Leetcode/blob/main/%E8%B4%AA%E5%BF%83%E7%AE%97%E6%B3%95/%E5%88%92%E5%88%86%E5%AD%97%E6%AF%8D%E5%8C%BA%E9%97%B4)
   * [合并区间(排序+贪心)](https://github.com/MarklearnML/Leetcode/blob/main/%E8%B4%AA%E5%BF%83%E7%AE%97%E6%B3%95/%E5%90%88%E5%B9%B6%E5%8C%BA%E9%97%B4)
   * [单调递增的数字](https://github.com/MarklearnML/Leetcode/blob/main/%E8%B4%AA%E5%BF%83%E7%AE%97%E6%B3%95/%E5%8D%95%E8%B0%83%E9%80%92%E5%A2%9E%E7%9A%84%E6%95%B0%E5%AD%97)
   * [监控二叉树(*后序遍历+贪心)](https://github.com/MarklearnML/Leetcode/blob/main/%E8%B4%AA%E5%BF%83%E7%AE%97%E6%B3%95/%E7%9B%91%E6%8E%A7%E4%BA%8C%E5%8F%89%E6%A0%91)
# 分治
# 查找
# 动态规划
涉及一个数组分成两份重量相同或最近的两个子数组的题，想到01背包。  <br>
完全背包问题，如果是组合数，那么外循环是物品，如果是排列数，那么外循环是背包。  <br>
   * [斐波那契数](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E6%96%90%E6%B3%A2%E9%82%A3%E5%A5%91%E6%95%B0)
   * [爬楼梯](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E7%88%AC%E6%A5%BC%E6%A2%AF)
   * [使用最小花费爬楼梯](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E4%BD%BF%E7%94%A8%E6%9C%80%E5%B0%8F%E8%8A%B1%E8%B4%B9%E7%88%AC%E6%A5%BC%E6%A2%AF)
   * [不同路径](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E4%B8%8D%E5%90%8C%E8%B7%AF%E5%BE%84)
   * [不同路径 II](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E4%B8%8D%E5%90%8C%E8%B7%AF%E5%BE%84%20II)
   * [整数拆分(*两个for)](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E6%95%B4%E6%95%B0%E6%8B%86%E5%88%86)
   * [不同的二叉搜索树(*两个for)](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E4%B8%8D%E5%90%8C%E7%9A%84%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91)
## 背包问题
### 问能否能装满背包（或者最多装多少）对应题目如下：
   * [分割等和子集(**背包问题)](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E5%88%86%E5%89%B2%E7%AD%89%E5%92%8C%E5%AD%90%E9%9B%86)
   * [最后一块石头的重量 II(**背包问题)](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E6%9C%80%E5%90%8E%E4%B8%80%E5%9D%97%E7%9F%B3%E5%A4%B4%E7%9A%84%E9%87%8D%E9%87%8F%20II)
### 问装满背包有几种方法 对应题目如下：
   * [目标和(***背包问题)](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E7%9B%AE%E6%A0%87%E5%92%8C)
   * [组合总和 Ⅳ(**完全背包排列)](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E7%BB%84%E5%90%88%E6%80%BB%E5%92%8C%20%E2%85%A3)
   * [零钱兑换 II(**完全背包组合](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E9%9B%B6%E9%92%B1%E5%85%91%E6%8D%A2%20II)
### 问背包装满最大价值 对应题目如下：
   * [一和零](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E4%B8%80%E5%92%8C%E9%9B%B6)
### 问装满背包所有物品的最小个数 对应题目如下：
   * [零钱兑换](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E9%9B%B6%E9%92%B1%E5%85%91%E6%8D%A2)
   * [完全平方数*](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E5%AE%8C%E5%85%A8%E5%B9%B3%E6%96%B9%E6%95%B0)
   * [单词拆分**](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E5%8D%95%E8%AF%8D%E6%8B%86%E5%88%86)
## 打家劫舍
   * [打家劫舍*](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E6%89%93%E5%AE%B6%E5%8A%AB%E8%88%8D)
   * [打家劫舍II**](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E6%89%93%E5%AE%B6%E5%8A%AB%E8%88%8D%20II)
   * [打家劫舍III*](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E6%89%93%E5%AE%B6%E5%8A%AB%E8%88%8DIII)
## 买卖股票的最佳时机   
买卖股票的套路即分别记录各个状态下的最大现金，一般的状态有：持有股票、未持有股票、第i次持有股票、第i次未持有股票、冻结期等  <br>
   * [买卖股票的最佳时机II(*记录持有股票和未持有股票两个状态)](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E4%B9%B0%E5%8D%96%E8%82%A1%E7%A5%A8%E7%9A%84%E6%9C%80%E4%BD%B3%E6%97%B6%E6%9C%BA%20II)
   * [买卖股票的最佳时机III(***记录第一、二次持有股票和第一、二次未持有股票的状态)](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E4%B9%B0%E5%8D%96%E8%82%A1%E7%A5%A8%E7%9A%84%E6%9C%80%E4%BD%B3%E6%97%B6%E6%9C%BA%20III)
   * [买卖股票的最佳时机 IV](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E4%B9%B0%E5%8D%96%E8%82%A1%E7%A5%A8%E7%9A%84%E6%9C%80%E4%BD%B3%E6%97%B6%E6%9C%BA%20IV)
   * [买卖股票的最佳时机含冷冻期**](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E4%B9%B0%E5%8D%96%E8%82%A1%E7%A5%A8%E7%9A%84%E6%9C%80%E4%BD%B3%E6%97%B6%E6%9C%BA%E5%90%AB%E5%86%B7%E5%86%BB%E6%9C%9F)
   * [买卖股票的最佳时机含手续费](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E4%B9%B0%E5%8D%96%E8%82%A1%E7%A5%A8%E7%9A%84%E6%9C%80%E4%BD%B3%E6%97%B6%E6%9C%BA%E5%90%AB%E6%89%8B%E7%BB%AD%E8%B4%B9)
## 子序列问题
子序列问题最主要是dp如何定义，一般定义dp[i]为以num[i]元素为结尾的子序列  <br>
   * [最长递增子序列(**)](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E6%9C%80%E9%95%BF%E9%80%92%E5%A2%9E%E5%AD%90%E5%BA%8F%E5%88%97)
   * [最长连续递增序列](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E6%9C%80%E9%95%BF%E8%BF%9E%E7%BB%AD%E9%80%92%E5%A2%9E%E5%BA%8F%E5%88%97)
   * [最长重复子数组](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E6%9C%80%E9%95%BF%E9%87%8D%E5%A4%8D%E5%AD%90%E6%95%B0%E7%BB%84)
   * [最长公共子序列*](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E6%9C%80%E9%95%BF%E5%85%AC%E5%85%B1%E5%AD%90%E5%BA%8F%E5%88%97)
   * [不相交的线(与上题一样)](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E4%B8%8D%E7%9B%B8%E4%BA%A4%E7%9A%84%E7%BA%BF)
### 编辑距离
   * [判断子序列](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E5%88%A4%E6%96%AD%E5%AD%90%E5%BA%8F%E5%88%97)
   * [不同的子序列***](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E4%B8%8D%E5%90%8C%E7%9A%84%E5%AD%90%E5%BA%8F%E5%88%97)
   * [两个字符串的删除操作](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E4%B8%A4%E4%B8%AA%E5%AD%97%E7%AC%A6%E4%B8%B2%E7%9A%84%E5%88%A0%E9%99%A4%E6%93%8D%E4%BD%9C)
   * [编辑距离**](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E7%BC%96%E8%BE%91%E8%B7%9D%E7%A6%BB)
## 回文子序列
也可以用双指针做回文问题，具体就是重中点想两边扩散 判断是否是回文串  <br>
   * [回文子串](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E5%9B%9E%E6%96%87%E5%AD%90%E4%B8%B2)
   * [最长回文子序列](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E6%9C%80%E9%95%BF%E5%9B%9E%E6%96%87%E5%AD%90%E5%BA%8F%E5%88%97)
# 单调栈
通常是一维数组，要寻找任一个元素的右边或者左边第一个比自己大或者小的元素的位置，此时我们就要想到可以用单调栈了。时间复杂度为O(n)   <br>
接雨水和柱状图中最大的矩形有所不同，接雨水是找到左边最大和右边最大的下标，或者找到左边第一个大和右边第一个大的下标。柱状图是找到左边第一个最小和右边第一个最小的下标。  <br>
单调栈的目的是找到右边第一个最大/最小的下标，同时也可以找到左边第一个最大/最小的下标，前者是入栈的元素，后者是还在栈内的元素。(为了所有元素都涉及到，前后都得插入最大/最小值~0)  <br>
   * [每日温度**](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8D%95%E8%B0%83%E6%A0%88/%E6%AF%8F%E6%97%A5%E6%B8%A9%E5%BA%A6)
   * [下一个更大元素 I***](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8D%95%E8%B0%83%E6%A0%88/%E4%B8%8B%E4%B8%80%E4%B8%AA%E6%9B%B4%E5%A4%A7%E5%85%83%E7%B4%A0%20I)
   * [下一个更大元素 II](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8D%95%E8%B0%83%E6%A0%88/%E4%B8%8B%E4%B8%80%E4%B8%AA%E6%9B%B4%E5%A4%A7%E5%85%83%E7%B4%A0%20II)
   * [接雨水(***单调栈、双指针、动态规划)](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8D%95%E8%B0%83%E6%A0%88/%E6%8E%A5%E9%9B%A8%E6%B0%B4)
   * [柱状图中最大的矩形(***单调栈、双指针)](https://github.com/MarklearnML/Leetcode/blob/main/%E5%8D%95%E8%B0%83%E6%A0%88/%E6%9F%B1%E7%8A%B6%E5%9B%BE%E4%B8%AD%E6%9C%80%E5%A4%A7%E7%9A%84%E7%9F%A9%E5%BD%A2)
# 图论
   * [所有可能的路径](https://github.com/MarklearnML/Leetcode/blob/main/%E5%9B%BE%E8%AE%BA/%E6%89%80%E6%9C%89%E5%8F%AF%E8%83%BD%E7%9A%84%E8%B7%AF%E5%BE%84)
   * [岛屿数量](https://github.com/MarklearnML/Leetcode/blob/main/%E5%9B%BE%E8%AE%BA/%E5%B2%9B%E5%B1%BF%E6%95%B0%E9%87%8F)
   * [岛屿的最大面积](https://github.com/MarklearnML/Leetcode/blob/main/%E5%9B%BE%E8%AE%BA/%E5%B2%9B%E5%B1%BF%E7%9A%84%E6%9C%80%E5%A4%A7%E9%9D%A2%E7%A7%AF)
   * [被围绕的区域](https://github.com/MarklearnML/Leetcode/blob/main/%E5%9B%BE%E8%AE%BA/%E8%A2%AB%E5%9B%B4%E7%BB%95%E7%9A%84%E5%8C%BA%E5%9F%9F)
   * [太平洋大西洋水流问题](https://github.com/MarklearnML/Leetcode/blob/main/%E5%9B%BE%E8%AE%BA/%E5%A4%AA%E5%B9%B3%E6%B4%8B%E5%A4%A7%E8%A5%BF%E6%B4%8B%E6%B0%B4%E6%B5%81%E9%97%AE%E9%A2%98)
   * [最大人工岛**](https://github.com/MarklearnML/Leetcode/blob/main/%E5%9B%BE%E8%AE%BA/%E6%9C%80%E5%A4%A7%E4%BA%BA%E5%B7%A5%E5%B2%9B)
   * [单词接龙***](https://github.com/MarklearnML/Leetcode/blob/main/%E5%9B%BE%E8%AE%BA/%E5%8D%95%E8%AF%8D%E6%8E%A5%E9%BE%99)
   * [钥匙和房间](https://github.com/MarklearnML/Leetcode/blob/main/%E5%9B%BE%E8%AE%BA/%E9%92%A5%E5%8C%99%E5%92%8C%E6%88%BF%E9%97%B4)
   * [岛屿的周长](https://github.com/MarklearnML/Leetcode/blob/main/%E5%9B%BE%E8%AE%BA/%E5%B2%9B%E5%B1%BF%E7%9A%84%E5%91%A8%E9%95%BF)
  ## 并查集
  三个作用：查找一个点的根节点，判断两个点是否一个集合(两个点的根节点是否相同)，将两个节点接入到同一个集合 <br>
  无向图计算冗余线时只需找相同根就行，而有向图则是判断是否有入度为2或者成环，冗余线在上述两种情况  <br>
   * [寻找图中是否存在路径**](https://github.com/MarklearnML/Leetcode/tree/main/%E5%9B%BE%E8%AE%BA)
   * [冗余连接*](https://github.com/MarklearnML/Leetcode/blob/main/%E5%9B%BE%E8%AE%BA/%E5%86%97%E4%BD%99%E8%BF%9E%E6%8E%A5)
   * [冗余连接 II***](https://github.com/MarklearnML/Leetcode/blob/main/%E5%9B%BE%E8%AE%BA/%E5%86%97%E4%BD%99%E8%BF%9E%E6%8E%A5%20II)
# 额外题目
   * [有多少小于当前数字的数字**](https://github.com/MarklearnML/Leetcode/blob/main/%E9%A2%9D%E5%A4%96%E9%A2%98%E7%9B%AE/%E6%9C%89%E5%A4%9A%E5%B0%91%E5%B0%8F%E4%BA%8E%E5%BD%93%E5%89%8D%E6%95%B0%E5%AD%97%E7%9A%84%E6%95%B0%E5%AD%97)
   * [有效的山脉](https://github.com/MarklearnML/Leetcode/blob/main/%E9%A2%9D%E5%A4%96%E9%A2%98%E7%9B%AE/%E6%9C%89%E6%95%88%E7%9A%84%E5%B1%B1%E8%84%89)
   * [独一无二的出现次数](https://github.com/MarklearnML/Leetcode/blob/main/%E9%A2%9D%E5%A4%96%E9%A2%98%E7%9B%AE/%E7%8B%AC%E4%B8%80%E6%97%A0%E4%BA%8C%E7%9A%84%E5%87%BA%E7%8E%B0%E6%AC%A1%E6%95%B0)
   * [移动零](https://github.com/MarklearnML/Leetcode/blob/main/%E9%A2%9D%E5%A4%96%E9%A2%98%E7%9B%AE/%E7%A7%BB%E5%8A%A8%E9%9B%B6)
   * [轮转数组(**整体反转+局部反转)](https://github.com/MarklearnML/Leetcode/blob/main/%E9%A2%9D%E5%A4%96%E9%A2%98%E7%9B%AE/%E8%BD%AE%E8%BD%AC%E6%95%B0%E7%BB%84)
   * [寻找数组的中心下标](https://github.com/MarklearnML/Leetcode/blob/main/%E9%A2%9D%E5%A4%96%E9%A2%98%E7%9B%AE/%E5%AF%BB%E6%89%BE%E6%95%B0%E7%BB%84%E7%9A%84%E4%B8%AD%E5%BF%83%E4%B8%8B%E6%A0%87)
