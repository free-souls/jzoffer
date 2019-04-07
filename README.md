# jzoffer
java版剑指offer代码，包含剑指offer所有算法代码，统一用java语言进行了实现，对算法感兴趣的同学可以一起学习一下，或者将要找工作面试笔试的可以参考一下  
算法口决：  
* 难题首选动归
* 受阻贪心暴力
* 考虑分治思想
* 配合排序哈希
## 第二章 面试需要的基础知识
[面试题2.实现Singleton模式](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E4%BA%8C%E7%AB%A0_%E9%9D%A2%E8%AF%95%E9%9C%80%E8%A6%81%E7%9A%84%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86/Singleton%E6%A8%A1%E5%BC%8F.java)  
[面试题3.二维数组中的查找](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E4%BA%8C%E7%AB%A0_%E9%9D%A2%E8%AF%95%E9%9C%80%E8%A6%81%E7%9A%84%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86/%E4%BA%8C%E7%BB%B4%E6%95%B0%E7%BB%84%E4%B8%AD%E7%9A%84%E6%9F%A5%E6%89%BE.java)  
[面试题4.替换空格](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E4%BA%8C%E7%AB%A0_%E9%9D%A2%E8%AF%95%E9%9C%80%E8%A6%81%E7%9A%84%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86/%E6%9B%BF%E6%8D%A2%E7%A9%BA%E6%A0%BC.java)  
[面试题5.从尾到头打印链表](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E4%BA%8C%E7%AB%A0_%E9%9D%A2%E8%AF%95%E9%9C%80%E8%A6%81%E7%9A%84%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86/%E4%BB%8E%E5%B0%BE%E5%88%B0%E5%A4%B4%E6%89%93%E5%8D%B0%E9%93%BE%E8%A1%A8.java)  
[面试题6.重建二叉树](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E4%BA%8C%E7%AB%A0_%E9%9D%A2%E8%AF%95%E9%9C%80%E8%A6%81%E7%9A%84%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86/%E9%87%8D%E5%BB%BA%E4%BA%8C%E5%8F%89%E6%A0%91.java)  
[面试题7.用两个栈实现队列](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E4%BA%8C%E7%AB%A0_%E9%9D%A2%E8%AF%95%E9%9C%80%E8%A6%81%E7%9A%84%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86/%E7%94%A8%E4%B8%A4%E4%B8%AA%E6%A0%88%E5%AE%9E%E7%8E%B0%E9%98%9F%E5%88%97.java)  
[面试题7.思考题-用两个队列实现栈](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E4%BA%8C%E7%AB%A0_%E9%9D%A2%E8%AF%95%E9%9C%80%E8%A6%81%E7%9A%84%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86/%E7%94%A8%E4%B8%A4%E4%B8%AA%E9%98%9F%E5%88%97%E5%AE%9E%E7%8E%B0%E4%B8%80%E4%B8%AA%E6%A0%88.java)  
[面试题8.旋转数组的最小数字](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E4%BA%8C%E7%AB%A0_%E9%9D%A2%E8%AF%95%E9%9C%80%E8%A6%81%E7%9A%84%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86/%E6%97%8B%E8%BD%AC%E6%95%B0%E7%BB%84%E7%9A%84%E6%9C%80%E5%B0%8F%E6%95%B0.java)  
[面试题9.斐波那契数列](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E4%BA%8C%E7%AB%A0_%E9%9D%A2%E8%AF%95%E9%9C%80%E8%A6%81%E7%9A%84%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86/%E6%96%90%E6%B3%A2%E9%82%A3%E5%A5%91%E6%95%B0%E5%88%97.java)  
[面试题9.青蛙跳台阶与变态跳台阶](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E4%BA%8C%E7%AB%A0_%E9%9D%A2%E8%AF%95%E9%9C%80%E8%A6%81%E7%9A%84%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86/%E8%B7%B3%E5%8F%B0%E9%98%B6%E4%B8%8E%E5%8F%98%E6%80%81%E8%B7%B3%E5%8F%B0%E9%98%B6.java)  
[面试题10.二进制中1的个数](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E4%BA%8C%E7%AB%A0_%E9%9D%A2%E8%AF%95%E9%9C%80%E8%A6%81%E7%9A%84%E5%9F%BA%E7%A1%80%E7%9F%A5%E8%AF%86/%E4%BA%8C%E8%BF%9B%E5%88%B6%E4%B8%AD1%E7%9A%84%E4%B8%AA%E6%95%B0.java)
## 第三章 高质量的代码
[面试题11.数值的整数次方](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E4%B8%89%E7%AB%A0_%E9%AB%98%E8%B4%A8%E9%87%8F%E7%9A%84%E4%BB%A3%E7%A0%81/%E6%95%B0%E5%80%BC%E7%9A%84%E6%95%B4%E6%95%B0%E6%AC%A1%E6%96%B9.java)  
[面试题12.打印1到最大的n位数 -](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E4%B8%89%E7%AB%A0_%E9%AB%98%E8%B4%A8%E9%87%8F%E7%9A%84%E4%BB%A3%E7%A0%81/%E6%89%93%E5%8D%B01%E8%87%B3%E6%9C%80%E5%A4%A7%E7%9A%84n%E4%BD%8D%E6%95%B0.java)  
[面试题13.在O（1）时间删除链表结点](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E4%B8%89%E7%AB%A0_%E9%AB%98%E8%B4%A8%E9%87%8F%E7%9A%84%E4%BB%A3%E7%A0%81/%E5%9C%A8O1%E6%97%B6%E9%97%B4%E5%88%A0%E9%99%A4%E9%93%BE%E8%A1%A8%E7%BB%93%E7%82%B9.java)  
[面试题14.调整数组顺序使奇数位于偶数前面](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E4%B8%89%E7%AB%A0_%E9%AB%98%E8%B4%A8%E9%87%8F%E7%9A%84%E4%BB%A3%E7%A0%81/%E8%B0%83%E6%95%B4%E6%95%B0%E7%BB%84%E9%A1%BA%E5%BA%8F%E4%BD%BF%E5%A5%87%E6%95%B0%E4%BD%8D%E4%BA%8E%E5%81%B6%E6%95%B0%E5%89%8D%E9%9D%A2.java)  
[面试题14.调整数组顺序使奇数位于偶数前面且保持顺序](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E4%B8%89%E7%AB%A0_%E9%AB%98%E8%B4%A8%E9%87%8F%E7%9A%84%E4%BB%A3%E7%A0%81/%E5%A5%87%E6%95%B0%E4%BD%8D%E4%BA%8E%E5%89%8D%E9%9D%A2%E5%81%B6%E6%95%B0%E4%BD%8D%E4%BA%8E%E5%90%8E%E9%9D%A2%E5%B9%B6%E4%B8%94%E4%B8%8D%E6%94%B9%E5%8E%9F%E5%9C%A8%E5%8E%9F%E6%95%B0%E7%BB%84%E4%B8%AD%E7%9A%84%E9%A1%BA%E5%BA%8F.java)  
[面试题15.链表中倒数第k个结点](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E4%B8%89%E7%AB%A0_%E9%AB%98%E8%B4%A8%E9%87%8F%E7%9A%84%E4%BB%A3%E7%A0%81/%E9%93%BE%E8%A1%A8%E4%B8%AD%E5%80%92%E6%95%B0%E7%AC%ACk%E4%B8%AA%E7%BB%93%E7%82%B9.java)  
[面试题16.反转链表](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E4%B8%89%E7%AB%A0_%E9%AB%98%E8%B4%A8%E9%87%8F%E7%9A%84%E4%BB%A3%E7%A0%81/%E5%8F%8D%E8%BD%AC%E9%93%BE%E8%A1%A8.java)  
[面试题17.合并两个排序的链表](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E4%B8%89%E7%AB%A0_%E9%AB%98%E8%B4%A8%E9%87%8F%E7%9A%84%E4%BB%A3%E7%A0%81/%E5%90%88%E5%B9%B6%E4%B8%A4%E4%B8%AA%E6%8E%92%E5%BA%8F%E7%9A%84%E9%93%BE%E8%A1%A8.java)  
[面试题18.树的子结构](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E4%B8%89%E7%AB%A0_%E9%AB%98%E8%B4%A8%E9%87%8F%E7%9A%84%E4%BB%A3%E7%A0%81/%E6%A0%91%E7%9A%84%E5%AD%90%E7%BB%93%E6%9E%84.java)
## 第四章 解决面试题的思路
[面试题19.二叉树的镜像](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E5%9B%9B%E7%AB%A0_%E8%A7%A3%E5%86%B3%E9%9D%A2%E8%AF%95%E7%9A%84%E6%80%9D%E8%B7%AF/%E4%BA%8C%E5%8F%89%E6%A0%91%E7%9A%84%E9%95%9C%E5%83%8F.java)  
[面试题20.顺时针打印矩阵](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E5%9B%9B%E7%AB%A0_%E8%A7%A3%E5%86%B3%E9%9D%A2%E8%AF%95%E7%9A%84%E6%80%9D%E8%B7%AF/%E9%A1%BA%E6%97%B6%E9%92%88%E6%89%93%E5%8D%B0%E7%9F%A9%E9%98%B5.java)  
[面试题21.包含min函数的栈](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E5%9B%9B%E7%AB%A0_%E8%A7%A3%E5%86%B3%E9%9D%A2%E8%AF%95%E7%9A%84%E6%80%9D%E8%B7%AF/%E5%8C%85%E5%90%ABmin%E5%87%BD%E6%95%B0%E7%9A%84%E6%A0%88.java)  
[面试题22.栈的压入、弹出序列](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E5%9B%9B%E7%AB%A0_%E8%A7%A3%E5%86%B3%E9%9D%A2%E8%AF%95%E7%9A%84%E6%80%9D%E8%B7%AF/%E6%A0%88%E7%9A%84%E5%8E%8B%E5%85%A5%E5%8F%8A%E5%BC%B9%E5%87%BA%E5%BA%8F%E5%88%97.java)  
[面试题23.从上往下打印二叉树](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E5%9B%9B%E7%AB%A0_%E8%A7%A3%E5%86%B3%E9%9D%A2%E8%AF%95%E7%9A%84%E6%80%9D%E8%B7%AF/%E4%BB%8E%E4%B8%8A%E5%BE%80%E4%B8%8B%E6%89%93%E5%8D%B0%E4%BA%8C%E5%8F%89%E6%A0%91.java)  
[面试题23.从上往下打印二叉树按行打印](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E5%9B%9B%E7%AB%A0_%E8%A7%A3%E5%86%B3%E9%9D%A2%E8%AF%95%E7%9A%84%E6%80%9D%E8%B7%AF/%E4%BB%8E%E4%B8%8A%E5%BE%80%E4%B8%8B%E6%89%93%E5%8D%B0%E4%BA%8C%E5%8F%89%E6%A0%91_%E6%8C%89%E8%A1%8C%E6%89%93%E5%8D%B0.java)  
[面试题23.之字打印二叉树](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E5%9B%9B%E7%AB%A0_%E8%A7%A3%E5%86%B3%E9%9D%A2%E8%AF%95%E7%9A%84%E6%80%9D%E8%B7%AF/%E4%B9%8B%E5%AD%97%E6%89%93%E5%8D%B0%E4%BA%8C%E5%8F%89%E6%A0%91.java)  
[面试题24.二叉搜索树的后序遍历序列](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E5%9B%9B%E7%AB%A0_%E8%A7%A3%E5%86%B3%E9%9D%A2%E8%AF%95%E7%9A%84%E6%80%9D%E8%B7%AF/%E4%BA%8C%E5%8F%89%E6%90%9C%E7%B4%A2%E6%A0%91%E7%9A%84%E5%90%8E%E5%BA%8F%E9%81%8D%E5%8E%86%E5%BA%8F%E5%88%97.java)  
[面试题25.二叉树中和为某一值的路径](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E5%9B%9B%E7%AB%A0_%E8%A7%A3%E5%86%B3%E9%9D%A2%E8%AF%95%E7%9A%84%E6%80%9D%E8%B7%AF/%E4%BA%8C%E5%8F%89%E6%A0%91%E4%B8%AD%E5%92%8C%E4%B8%BA%E6%9F%90%E4%B8%80%E5%80%BC%E7%9A%84%E8%B7%AF%E5%BE%84.java)  
[面试题26.复杂链表的复制-](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E5%9B%9B%E7%AB%A0_%E8%A7%A3%E5%86%B3%E9%9D%A2%E8%AF%95%E7%9A%84%E6%80%9D%E8%B7%AF/%E5%A4%8D%E6%9D%82%E9%93%BE%E8%A1%A8%E7%9A%84%E5%A4%8D%E5%88%B6.java)  
[面试题27.二叉搜索树与双向链表-]()  
[面试题28.字符串的排列](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E5%9B%9B%E7%AB%A0_%E8%A7%A3%E5%86%B3%E9%9D%A2%E8%AF%95%E7%9A%84%E6%80%9D%E8%B7%AF/%E5%AD%97%E7%AC%A6%E4%B8%B2%E7%9A%84%E6%8E%92%E5%88%97.java)  
[面试题28.字符串的组合](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E5%9B%9B%E7%AB%A0_%E8%A7%A3%E5%86%B3%E9%9D%A2%E8%AF%95%E7%9A%84%E6%80%9D%E8%B7%AF/%E5%AD%97%E7%AC%A6%E4%B8%B2%E7%9A%84%E7%BB%84%E5%90%88.java)  
[面试题28.字符串的排列去重](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E5%9B%9B%E7%AB%A0_%E8%A7%A3%E5%86%B3%E9%9D%A2%E8%AF%95%E7%9A%84%E6%80%9D%E8%B7%AF/%E5%AD%97%E7%AC%A6%E4%B8%B2%E7%9A%84%E5%85%A8%E6%8E%92%E5%88%97_%E5%8E%BB%E9%99%A4%E9%87%8D%E5%A4%8D.java)  
[思考题 8个数字在正方体上三组相对的面上的4个顶点的和都相等](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E5%9B%9B%E7%AB%A0_%E8%A7%A3%E5%86%B3%E9%9D%A2%E8%AF%95%E7%9A%84%E6%80%9D%E8%B7%AF/%E6%80%9D%E8%80%83%E9%A2%98_8%E4%B8%AA%E6%95%B0%E5%AD%97%E5%9C%A8%E6%AD%A3%E6%96%B9%E4%BD%93%E4%B8%8A%E4%B8%89%E7%BB%84%E7%9B%B8%E5%AF%B9%E7%9A%84%E9%9D%A2%E4%B8%8A%E7%9A%844%E4%B8%AA%E9%A1%B6%E7%82%B9%E7%9A%84%E5%92%8C%E9%83%BD%E7%9B%B8%E7%AD%89.java)  

## 第五章 优化时间和空间效率
[面试题29.数组中出现次数超过一半的数字](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E4%BA%94%E7%AB%A0_%E4%BC%98%E5%8C%96%E6%97%B6%E9%97%B4%E5%92%8C%E7%A9%BA%E9%97%B4%E6%95%88%E7%8E%87/%E6%95%B0%E7%BB%84%E4%B8%AD%E5%87%BA%E7%8E%B0%E6%AC%A1%E6%95%B0%E8%B6%85%E8%BF%87%E4%B8%80%E5%8D%8A%E7%9A%84%E6%95%B0%E5%AD%97.java)  
[面试题30.最小的k个数](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E4%BA%94%E7%AB%A0_%E4%BC%98%E5%8C%96%E6%97%B6%E9%97%B4%E5%92%8C%E7%A9%BA%E9%97%B4%E6%95%88%E7%8E%87/%E6%9C%80%E5%B0%8F%E7%9A%84k%E4%B8%AA%E6%95%B0.java)  
[面试题31.连续子数组的最大和](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E4%BA%94%E7%AB%A0_%E4%BC%98%E5%8C%96%E6%97%B6%E9%97%B4%E5%92%8C%E7%A9%BA%E9%97%B4%E6%95%88%E7%8E%87/%E8%BF%9E%E7%BB%AD%E5%AD%90%E6%95%B0%E7%BB%84%E7%9A%84%E6%9C%80%E5%A4%A7%E5%92%8C.java)  
## 第六章 面试中的各项能力
[面试题38.数字在排序数组中出现的次数](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E5%85%AD%E7%AB%A0_%E9%9D%A2%E8%AF%95%E4%B8%AD%E7%9A%84%E5%90%84%E9%A1%B9%E8%83%BD%E5%8A%9B/%E6%95%B0%E5%AD%97%E5%9C%A8%E6%8E%92%E5%BA%8F%E6%95%B0%E7%BB%84%E4%B8%AD%E5%87%BA%E7%8E%B0%E7%9A%84%E6%AC%A1%E6%95%B0.java)  
[面试题39.二叉树的深度](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E5%85%AD%E7%AB%A0_%E9%9D%A2%E8%AF%95%E4%B8%AD%E7%9A%84%E5%90%84%E9%A1%B9%E8%83%BD%E5%8A%9B/%E4%BA%8C%E5%8F%89%E6%A0%91%E7%9A%84%E6%B7%B1%E5%BA%A6.java)  
[面试题39.判断二叉树是否平衡二叉树](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E5%85%AD%E7%AB%A0_%E9%9D%A2%E8%AF%95%E4%B8%AD%E7%9A%84%E5%90%84%E9%A1%B9%E8%83%BD%E5%8A%9B/%E5%88%A4%E6%96%AD%E4%BA%8C%E5%8F%89%E6%A0%91%E6%98%AF%E5%90%A6%E4%B8%BA%E5%B9%B3%E8%A1%A1%E4%BA%8C%E5%8F%89%E6%A0%91.java)  
[面试40.数组中只出现一次的数字](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E5%85%AD%E7%AB%A0_%E9%9D%A2%E8%AF%95%E4%B8%AD%E7%9A%84%E5%90%84%E9%A1%B9%E8%83%BD%E5%8A%9B/%E6%95%B0%E7%BB%84%E4%B8%AD%E5%8F%AA%E5%87%BA%E7%8E%B0%E4%B8%80%E6%AC%A1%E7%9A%84%E6%95%B0%E5%AD%97.java)  
[面试41.和为s的两个数](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E5%85%AD%E7%AB%A0_%E9%9D%A2%E8%AF%95%E4%B8%AD%E7%9A%84%E5%90%84%E9%A1%B9%E8%83%BD%E5%8A%9B/%E5%92%8C%E4%B8%BAs%E7%9A%84%E4%B8%A4%E4%B8%AA%E6%95%B0.java)  
[面试41.和为s的连续正数序列](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E5%85%AD%E7%AB%A0_%E9%9D%A2%E8%AF%95%E4%B8%AD%E7%9A%84%E5%90%84%E9%A1%B9%E8%83%BD%E5%8A%9B/%E5%92%8C%E4%B8%BAs%E7%9A%84%E8%BF%9E%E7%BB%AD%E6%AD%A3%E6%95%B0%E5%BA%8F%E5%88%97.java)  
[面试42.翻转单词顺序](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E5%85%AD%E7%AB%A0_%E9%9D%A2%E8%AF%95%E4%B8%AD%E7%9A%84%E5%90%84%E9%A1%B9%E8%83%BD%E5%8A%9B/%E7%BF%BB%E8%BD%AC%E5%8D%95%E8%AF%8D%E9%A1%BA%E5%BA%8F.java)  
[面试42.左旋字符串](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC%E5%85%AD%E7%AB%A0_%E9%9D%A2%E8%AF%95%E4%B8%AD%E7%9A%84%E5%90%84%E9%A1%B9%E8%83%BD%E5%8A%9B/%E5%AD%97%E7%AC%A6%E5%8F%8D%E8%BD%AC.java)  
## 第八章 英文版新增面试题
[面试51.数组中重复的数字](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC8%E7%AB%A0_%E8%8B%B1%E6%96%87%E7%89%88%E6%96%B0%E5%A2%9E%E9%9D%A2%E8%AF%95%E9%A2%98/%E6%95%B0%E7%BB%84%E4%B8%AD%E9%87%8D%E5%A4%8D%E7%9A%84%E6%95%B0%E5%AD%97.java)  
[面试56.链表中环的入口结点](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC8%E7%AB%A0_%E8%8B%B1%E6%96%87%E7%89%88%E6%96%B0%E5%A2%9E%E9%9D%A2%E8%AF%95%E9%A2%98/%E9%93%BE%E8%A1%A8%E4%B8%AD%E7%8E%AF%E7%9A%84%E5%85%A5%E5%8F%A3%E7%BB%93%E7%82%B9.java)  
[面试57.删除链表中重复的结点](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E7%AC%AC8%E7%AB%A0_%E8%8B%B1%E6%96%87%E7%89%88%E6%96%B0%E5%A2%9E%E9%9D%A2%E8%AF%95%E9%A2%98/%E5%88%A0%E9%99%A4%E9%93%BE%E8%A1%A8%E4%B8%AD%E9%87%8D%E5%A4%8D%E7%9A%84%E7%BB%93%E7%82%B9.java)  
## 扩展——动态规划
[不能相邻的两个数的最大和](https://github.com/lvCmx/jzoffer/tree/master/src/main/java/%E6%89%A9%E5%B1%95_%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E4%B8%8D%E8%83%BD%E7%9B%B8%E9%82%BB%E7%9A%84%E4%B8%A4%E4%B8%AA%E6%95%B0%E7%9A%84%E6%9C%80%E5%A4%A7%E5%92%8C)  
[最大的利益](https://github.com/lvCmx/jzoffer/tree/master/src/main/java/%E6%89%A9%E5%B1%95_%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E6%9C%80%E5%A4%A7%E7%9A%84%E5%88%A9%E7%9B%8A)  
[求数组中的数之和为指定的数](https://github.com/lvCmx/jzoffer/tree/master/src/main/java/%E6%89%A9%E5%B1%95_%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E6%B1%82%E6%95%B0%E7%BB%84%E4%B8%AD%E7%9A%84%E6%95%B0%E4%B9%8B%E5%92%8C%E4%B8%BA%E6%8C%87%E5%AE%9A%E7%9A%84%E6%95%B0)  
[连续子数组的最大和](https://github.com/lvCmx/jzoffer/blob/master/src/main/java/%E6%89%A9%E5%B1%95_%E5%8A%A8%E6%80%81%E8%A7%84%E5%88%92/%E8%BF%9E%E7%BB%AD%E5%AD%90%E6%95%B0%E7%BB%84%E7%9A%84%E6%9C%80%E5%A4%A7%E5%92%8C/Main.java)
