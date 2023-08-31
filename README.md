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
*  [分治](#分治)
*  [Kadane](#Kadane)
*  [查找](#查找)
*  [动态规划](#动态规划)
*  [堆](#堆)

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
栈是容器适配器，底层容器使用不同的容器，导致栈内数据在内存中是不是连续分布。
缺省情况下，默认底层容器是deque，那么deque的在内存中的数据分布是什么样的呢？ 答案是：不连续的，下文也会提到deque。
经典例题：括号匹配问题、栈在系统中的应用、滑动窗口最大值、前k个最值、字符串去重问题
  * [用栈实现队列](https://github.com/MarklearnML/Leetcode/blob/main/%E6%A0%88%E4%B8%8E%E9%98%9F%E5%88%97/%E7%94%A8%E6%A0%88%E5%AE%9E%E7%8E%B0%E9%98%9F%E5%88%97)
  * [用队列实现栈(一个队列就够)](https://github.com/MarklearnML/Leetcode/blob/main/%E6%A0%88%E4%B8%8E%E9%98%9F%E5%88%97/%E7%94%A8%E9%98%9F%E5%88%97%E5%AE%9E%E7%8E%B0%E6%A0%88)
  * [有效的括号](https://github.com/MarklearnML/Leetcode/blob/main/%E6%A0%88%E4%B8%8E%E9%98%9F%E5%88%97/%E6%9C%89%E6%95%88%E7%9A%84%E6%8B%AC%E5%8F%B7)
  * [删除字符串中所有相邻重复项](https://github.com/MarklearnML/Leetcode/blob/main/%E6%A0%88%E4%B8%8E%E9%98%9F%E5%88%97/%E5%88%A0%E9%99%A4%E5%AD%97%E7%AC%A6%E4%B8%B2%E4%B8%AD%E6%89%80%E6%9C%89%E7%9B%B8%E9%82%BB%E9%87%8D%E5%A4%8D%E9%A1%B9)
  * [逆波兰表达式求值](https://github.com/MarklearnML/Leetcode/blob/main/%E6%A0%88%E4%B8%8E%E9%98%9F%E5%88%97/%E9%80%86%E6%B3%A2%E5%85%B0%E8%A1%A8%E8%BE%BE%E5%BC%8F%E6%B1%82%E5%80%BC)
  * [滑动窗口最大值(*单调队列)](https://github.com/MarklearnML/Leetcode/blob/main/%E6%A0%88%E4%B8%8E%E9%98%9F%E5%88%97/%E6%BB%91%E5%8A%A8%E7%AA%97%E5%8F%A3%E6%9C%80%E5%A4%A7%E5%80%BC)
  * [前k个高频元素(*优先级队列)](https://github.com/MarklearnML/Leetcode/blob/main/%E6%A0%88%E4%B8%8E%E9%98%9F%E5%88%97/%E5%89%8Dk%E4%B8%AA%E9%AB%98%E9%A2%91%E5%85%83%E7%B4%A0)
# 链表
链表的类型: 单链表、双链表、循环链表
链表的操作：增删改查
  * [移除链表元素](https://github.com/MarklearnML/Leetcode/blob/main/%E9%93%BE%E8%A1%A8/%E7%A7%BB%E9%99%A4%E9%93%BE%E8%A1%A8%E5%85%83%E7%B4%A0)
  * [设计链表(虚拟头结点)](https://github.com/MarklearnML/Leetcode/blob/main/%E9%93%BE%E8%A1%A8/%E8%AE%BE%E8%AE%A1%E9%93%BE%E8%A1%A8)
  * [反转链表(双指针法)](https://github.com/MarklearnML/Leetcode/blob/main/%E9%93%BE%E8%A1%A8/%E5%8F%8D%E8%BD%AC%E9%93%BE%E8%A1%A8)
  * [删除链表的倒数第N个结点(滑动窗口)](https://github.com/MarklearnML/Leetcode/blob/main/%E9%93%BE%E8%A1%A8/%E5%88%A0%E9%99%A4%E9%93%BE%E8%A1%A8%E7%9A%84%E5%80%92%E6%95%B0%E7%AC%AC%20N%20%E4%B8%AA%E7%BB%93%E7%82%B9)
  * [链表相交](https://github.com/MarklearnML/Leetcode/blob/main/%E9%93%BE%E8%A1%A8/%E9%93%BE%E8%A1%A8%E7%9B%B8%E4%BA%A4)
  * [环形链表(快慢指针*、哈希表法)](https://github.com/MarklearnML/Leetcode/blob/main/%E9%93%BE%E8%A1%A8/%E7%8E%AF%E5%BD%A2%E9%93%BE%E8%A1%A8II)
# 二叉树
题目跟一层有关的均可用层次遍历(例：层里最大值，层里平均值，右视图，左视图)
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
# 图
# 回溯
# 分治
# Kadane
# 查找
# 动态规划
# 堆
