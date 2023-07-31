# 目录
*  [数组/字符串](#数组/字符串)
*  [双指针](#双指针)
*  [滑动窗口](#滑动窗口)
*  [矩阵](#矩阵)
*  [哈希表](#哈希表)
*  [区间](#区间)
*  [栈](#栈)
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
# 双指针
# 滑动窗口
# 矩阵
# 哈希表
哈希表的类型：数组、set、map
  * [有效的字母异位词(哈希表)](https://github.com/MarklearnML/Leetcode/blob/main/%E5%93%88%E5%B8%8C%E8%A1%A8/%E6%9C%89%E6%95%88%E7%9A%84%E5%AD%97%E6%AF%8D%E5%BC%82%E4%BD%8D%E8%AF%8D)
  * [两个数组的交集](https://github.com/MarklearnML/Leetcode/blob/main/%E5%93%88%E5%B8%8C%E8%A1%A8/%E4%B8%A4%E4%B8%AA%E6%95%B0%E7%BB%84%E7%9A%84%E4%BA%A4%E9%9B%86)
  * [快乐数](https://github.com/MarklearnML/Leetcode/blob/main/%E5%93%88%E5%B8%8C%E8%A1%A8/%E5%BF%AB%E4%B9%90%E6%95%B0)
  * [四数之和(分组+哈希表*)](https://github.com/MarklearnML/Leetcode/blob/main/%E5%93%88%E5%B8%8C%E8%A1%A8/%E5%9B%9B%E6%95%B0%E4%B9%8B%E5%92%8CII)
# 区间
# 栈
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
# 图
# 回溯
# 分治
# Kadane
# 查找
# 动态规划
# 堆
