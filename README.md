# Leetcode-retag
重新分类 Leetcode 高频题 2021 版- 北美leetcode

- 题目按照面试频率降序排列
- 增加难度分类，适合从简单开始学习
- 增加细分类别，例如单调栈，前缀树等，一道题目可能会有多个类别

# 目录
- [𐀴 链表](#𐀴-链表)
    - 单链表
    - 双链表
- [𐀴 树](#𐀴-树)
    - 遍历
    - 构造
    - 路径 | 深度 | 翻转
    - 二叉搜索树
    - 前缀树
    - * 线段树
- [𐀴 栈](#𐀴-栈)
    - 基础
    - 单调栈
- [𐀴 堆](#𐀴-堆)
    - 基础
- [𐀴 二分查找](#𐀴-二分查找)
- [𐀴 位运算](#𐀴-位运算)
- [𐀴 双指针与滑动窗口](#𐀴-双指针与滑动窗口)
- [𐀴 矩阵](#𐀴-矩阵)
- [𐀴 动态规划](#𐀴-动态规划)
    - 一维
    - 二维
- [𐀴 图论](#𐀴-图论)
    - DFS
    - BFS
    - * Dijkstra
    - 拓扑排序
- [𐀴 并查集](#𐀴-并查集)
- [𐀴 设计](#𐀴-设计)
- [𐀴 贪心](#𐀴-贪心)
- [𐀴 回溯](#𐀴-回溯)
- [𐀴 克隆](#𐀴-克隆)
- [𐀴 数学](#𐀴-数学)
- [𐀴 \* 极大极小化](#𐀴-极大极小化)
- [𐀴 \* 几何](#𐀴-几何)

## 𐀴 链表

#### 单链表：

###### 简单：

- [x] [206. 反转链表](https://leetcode.com/problems/reverse-linked-list/)
- [x] [141. 环形链表](https://leetcode.com/problems/linked-list-cycle/)  
- [x] [83. 删除排序链表中的重复元素](https://leetcode.com/problems/remove-duplicates-from-sorted-list/)
- [x] [234. 回文链表](https://leetcode.com/problems/palindrome-linked-list/)
- [x] [203. 移除链表元素](https://leetcode.com/problems/remove-linked-list-elements/)
- [x] [237. 删除链表中的节点](https://leetcode.com/problems/delete-node-in-a-linked-list/)
- [x] [876. 链表的中间结点](https://leetcode.com/problems/middle-of-the-linked-list/)

###### 中等

- [x] [92. 反转链表 II](https://leetcode.com/problems/reverse-linked-list-ii/)
- [x] [143. 重排链表](https://leetcode.com/problems/reorder-list/)
- [x] [82. 删除排序链表中的重复元素 II](https://leetcode.com/problems/remove-duplicates-from-sorted-list-ii/)
- [x] [19. 删除链表的倒数第 N 个结点](https://leetcode.com/problems/remove-nth-node-from-end-of-list/)
- [x] [148. 排序链表](https://leetcode.com/problems/sort-list/)
- [x] [86. 分隔链表](https://leetcode.com/problems/partition-list/)
- [x] [61. 旋转链表](https://leetcode.com/problems/rotate-list/)
- [x] [142. 环形链表 II](https://leetcode.com/problems/linked-list-cycle-ii/)
- [x] [147. 对链表进行插入排序](https://leetcode.com/problems/insertion-sort-list/)
- [x] [138. 复制带随机指针的链表](https://leetcode.com/problems/copy-list-with-random-pointer/)
- [x] [24. 两两交换链表中的节点](https://leetcode.com/problems/swap-nodes-in-pairs/)
- [x] [328. 奇偶链表](https://leetcode.com/problems/odd-even-linked-list/)
- [x] [707. 设计链表](https://leetcode.com/problems/design-linked-list/)
- [x] [109. 有序链表转换二叉搜索树](https://leetcode.com/problems/convert-sorted-list-to-binary-search-tree/)
- [x] [430. 扁平化多级双向链表](https://leetcode.com/problems/flatten-a-multilevel-doubly-linked-list/)
- [x] [725. 分隔链表](https://leetcode.com/problems/split-linked-list-in-parts/)

###### 困难
- [x] [25. K 个一组翻转链表](https://leetcode.com/problems/reverse-nodes-in-k-group/) ❤️

#### 双链表：

###### 简单：

- [x] [21. 合并两个有序链表](https://leetcode.com/problems/merge-two-sorted-lists/)
- [x] [160. 相交链表](https://leetcode.com/problems/intersection-of-two-linked-lists/)

###### 中级

- [x] [2. 两数相加](https://leetcode.com/problems/add-two-numbers/)
- [x] [445. 两数相加 II](https://leetcode.com/problems/add-two-numbers-ii/)
- [x] [1669. 合并两个链表](https://leetcode.com/problems/merge-in-between-linked-lists/)

###### 困难

- [x] [23. 合并 K 个升序链表](https://leetcode.com/problems/merge-k-sorted-lists/)

## 𐀴 树

#### 遍历

###### 简单

- [x] [145. 二叉树的后序遍历](https://leetcode.com/problems/binary-tree-postorder-traversal/)
- [x] [94. 二叉树的中序遍历](https://leetcode.com/problems/binary-tree-inorder-traversal/)
- [x] [589. N 叉树的前序遍历](https://leetcode.com/problems/n-ary-tree-preorder-traversal/)
- [x] [144. 二叉树的前序遍历](https://leetcode.com/problems/binary-tree-preorder-traversal/)
- [x] [590. N 叉树的后序遍历](https://leetcode.com/problems/n-ary-tree-postorder-traversal/)

###### 中等

- [x] [102. 二叉树的层序遍历](https://leetcode.com/problems/binary-tree-level-order-traversal/)
- [x] [103. 二叉树的锯齿形层序遍历](https://leetcode.com/problems/binary-tree-zigzag-level-order-traversal/)
- [x] [107. 二叉树的层序遍历 II](https://leetcode.com/problems/binary-tree-level-order-traversal-ii/)

#### 构造

###### 简单
- [x] [108. 将有序数组转换为二叉搜索树](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/)

###### 中等
- [x] [105. 从前序与中序遍历序列构造二叉树](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-inorder-traversal/)
- [x] [106. 从中序与后序遍历序列构造二叉树](https://leetcode.com/problems/construct-binary-tree-from-inorder-and-postorder-traversal/)
- [x] [114. 二叉树展开为链表](https://leetcode.com/problems/flatten-binary-tree-to-linked-list/)
- [x] [889. 根据前序和后序遍历构造二叉树](https://leetcode.com/problems/construct-binary-tree-from-preorder-and-postorder-traversal/)
- [x] [1008. 前序遍历构造二叉搜索树](https://leetcode.com/problems/construct-binary-search-tree-from-preorder-traversal/)

###### 困难
- [ ] [297. 二叉树的序列化与反序列化](https://leetcode.com/problems/serialize-and-deserialize-binary-tree/)

#### 路径 | 深度 | 翻转

###### 简单

- [x] [104. 二叉树的最大深度](https://leetcode.com/problems/maximum-depth-of-binary-tree/)
- [x] [101. 对称二叉树](https://leetcode.com/problems/symmetric-tree/)
- [x] [226. 翻转二叉树](https://leetcode.com/problems/invert-binary-tree/)
- [x] [543. 二叉树的直径](https://leetcode.com/problems/diameter-of-binary-tree/)
- [x] [257. 二叉树的所有路径](https://leetcode.com/problems/binary-tree-paths/)
- [x] [110. 平衡二叉树](https://leetcode.com/problems/balanced-binary-tree/)
- [x] [617. 合并二叉树](https://leetcode.com/problems/merge-two-binary-trees/)
- [x] [100. 相同的树](https://leetcode.com/problems/same-tree/)
- [x] [112. 路径总和](https://leetcode.com/problems/path-sum/)
- [x] [111. 二叉树的最小深度](https://leetcode.com/problems/minimum-depth-of-binary-tree/)

###### 中等

- [x] [236. 二叉树的最近公共祖先](https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/) ***
- [x] [222. 完全二叉树的节点个数](https://leetcode.com/problems/count-complete-tree-nodes/)
- [x] [113. 路径总和 II](https://leetcode.com/problems/path-sum-ii/)
- [x] [437. 路径总和 III](https://leetcode.com/problems/path-sum-iii/)
- [x] [129. 求根节点到叶节点数字之和](https://leetcode.com/problems/sum-root-to-leaf-numbers/)
- [x] [662. 二叉树最大宽度](https://leetcode.com/problems/maximum-width-of-binary-tree/)
- [x] [114. 二叉树展开为链表](https://leetcode.com/problems/flatten-binary-tree-to-linked-list/)
- [x] [199. 二叉树的右视图](https://leetcode.com/problems/binary-tree-right-side-view/)
- [x] [116. 填充每个节点的下一个右侧节点指针](https://leetcode.com/problems/populating-next-right-pointers-in-each-node/)
- [x] [515. 在每个树行中找最大值](https://leetcode.com/problems/find-largest-value-in-each-tree-row/)

###### 困难

- [x] [124. 二叉树中的最大路径和](https://leetcode.com/problems/binary-tree-maximum-path-sum/)

#### 二叉搜索树

###### 简单

- [x] [108. 将有序数组转换为二叉搜索树](https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/)

###### 中等

- [x] [98. 验证二叉搜索树](https://leetcode.com/problems/validate-binary-search-tree/)
- [x] [96. 不同的二叉搜索树](https://leetcode.com/problems/unique-binary-search-trees/)
- [x] [95. 不同的二叉搜索树 II](https://leetcode.com/problems/unique-binary-search-trees-ii/)
- [x] [173. 二叉搜索树迭代器](https://leetcode.com/problems/binary-search-tree-iterator/)
- [x] [230. 二叉搜索树中第 K 小的元素](https://leetcode.com/problems/kth-smallest-element-in-a-bst/)
- [ ] [99. 恢复二叉搜索树](https://leetcode.com/problems/recover-binary-search-tree/)

#### 字典树


###### 中等

- [x] [720. 词典中最长的单词](https://leetcode.com/problems/longest-word-in-dictionary/)
- [x] [208. 实现 Trie (前缀树)](https://leetcode.com/problems/implement-trie-prefix-tree/)
- [x] [692. 前 K 个高频单词](https://leetcode.com/problems/top-k-frequent-words/)
- [x] [421. 数组中两个数的最大异或值](https://leetcode.com/problems/maximum-xor-of-two-numbers-in-an-array/)

###### 困难

- [ ] [212. 单词搜索 II](https://leetcode.com/problems/word-search-ii/)

#### 线段树

###### 中等

- [ ] [1353. 最多可以参加的会议数目](https://leetcode.com/problems/maximum-number-of-events-that-can-be-attended/)
- [ ] [307. 区域和检索 - 数组可修改](https://leetcode.com/problems/range-sum-query-mutable/)

###### 困难

- [ ] [315. 计算右侧小于当前元素的个数](https://leetcode.com/problems/count-of-smaller-numbers-after-self/)
- [ ] [493. 翻转对](https://leetcode.com/problems/reverse-pairs/)
- [ ] [218. 天际线问题](https://leetcode.com/problems/the-skyline-problem/)
- [ ] [715. Range 模块](https://leetcode.com/problems/range-module/)
- [ ] [850. 矩形面积 II](https://leetcode.com/problems/rectangle-area-ii/)
- [ ] [1157. 子数组中占绝大多数的元素](https://leetcode.com/problems/online-majority-element-in-subarray/)
- [ ] [699. 掉落的方块](https://leetcode.com/problems/falling-squares/)
- [ ] [327. 区间和的个数](https://leetcode.com/problems/count-of-range-sum/)


## 𐀴 栈

#### 基础

###### 简单

- [x] [20. 有效的括号](https://leetcode.com/problems/valid-parentheses/)
- [x] [1047. 删除字符串中的所有相邻重复项](https://leetcode.com/problems/remove-all-adjacent-duplicates-in-string/)
- [x] [232. 用栈实现队列](https://leetcode.com/problems/implement-queue-using-stacks/)
- [x] [155. 最小栈](https://leetcode.com/problems/min-stack/)
- [x] [225. 用队列实现栈](https://leetcode.com/problems/implement-stack-using-queues/)
- [x] [1021. 删除最外层的括号](https://leetcode.com/problems/remove-outermost-parentheses/)
- [x] [682. 棒球比赛](https://leetcode.com/problems/baseball-game/)
- [x] [844. 比较含退格的字符串](https://leetcode.com/problems/backspace-string-compare/)

###### 中等

- [x] [1190. 反转每对括号间的子串](https://leetcode.com/problems/reverse-substrings-between-each-pair-of-parentheses/)
- [x] [394. 字符串解码](https://leetcode.com/problems/decode-string/)
- [x] [456. 132 模式](https://leetcode.com/problems/132-pattern/)
- [x] [227. 基本计算器 II](https://leetcode.com/problems/basic-calculator-ii/)
- [x] [150. 逆波兰表达式求值](https://leetcode.com/problems/evaluate-reverse-polish-notation/)
- [x] [503. 下一个更大元素 II](https://leetcode.com/problems/next-greater-element-ii/)
- [x] [71. 简化路径](https://leetcode.com/problems/simplify-path/)
- [x] [856. 括号的分数](https://leetcode.com/problems/score-of-parentheses/)
- [ ] [907. 子数组的最小值之和](https://leetcode.com/problems/sum-of-subarray-minimums/)
- [ ] [385. 迷你语法分析器](https://leetcode.com/problems/mini-parser/)
- [x] [1249. 移除无效的括号](https://leetcode.com/problems/minimum-remove-to-make-valid-parentheses/)
- [x] [636. 函数的独占时间](https://leetcode.com/problems/exclusive-time-of-functions/)
- [x] [341. 扁平化嵌套列表迭代器](https://leetcode.com/problems/flatten-nested-list-iterator/)

###### 困难

- [x] [224. 基本计算器](https://leetcode.com/problems/basic-calculator/)
- [ ] [726. 原子的数量](https://leetcode.com/problems/number-of-atoms/)


#### 单调栈

###### 简单

- [x] [496. 下一个更大元素 I](https://leetcode.com/problems/next-greater-element-i/)

###### 中等

- [x] [739. 每日温度](https://leetcode.com/problems/daily-temperatures/)
- [x] [402. 移掉 K 位数字](https://leetcode.com/problems/remove-k-digits/)
- [x] [316. 去除重复字母](https://leetcode.com/problems/remove-duplicate-letters/)
- [ ] [1124. 表现良好的最长时间段](https://leetcode.com/problems/longest-well-performing-interval/)

###### 困难

- [ ] [42. 接雨水](https://leetcode.com/problems/trapping-rain-water/)
- [ ] [84. 柱状图中最大的矩形](https://leetcode.com/problems/largest-rectangle-in-histogram/)
- [ ] [85. 最大矩形](https://leetcode.com/problems/maximal-rectangle/)
- [ ] [321. 拼接最大数](https://leetcode.com/problems/create-maximum-number/)


## 𐀴 堆

#### 基础

###### 简单

- [x] [1046. 最后一块石头的重量](https://leetcode.com/problems/last-stone-weight/)
- [x] [703. 数据流中的第 K 大元素](https://leetcode.com/problems/kth-largest-element-in-a-stream/)

###### 中等

- [ ] [215. 数组中的第 K 个最大元素](https://leetcode.com/problems/kth-largest-element-in-an-array/)
- [ ] [347. 前 K 个高频元素](https://leetcode.com/problems/top-k-frequent-elements/)
- [ ] [692. 前K个高频单词](https://leetcode.com/problems/top-k-frequent-words/)
- [ ] [378. 有序矩阵中第 K 小的元素](https://leetcode.com/problems/kth-smallest-element-in-a-sorted-matrix/)
- [ ] [451. 根据字符出现频率排序](https://leetcode.com/problems/sort-characters-by-frequency/)
- [ ] [743. 网络延迟时间](https://leetcode.com/problems/network-delay-time/)
- [ ] [787. K 站中转内最便宜的航班](https://leetcode.com/problems/cheapest-flights-within-k-stops/)
- [ ] [973. 最接近原点的 K 个点](https://leetcode.com/problems/k-closest-points-to-origin/)

###### 困难

- [ ] [239. 滑动窗口最大值](https://leetcode.com/problems/sliding-window-maximum/)
- [ ] [295. 数据流的中位数](https://leetcode.com/problems/find-median-from-data-stream/)
- [ ] [218. 天际线问题](https://leetcode.com/problems/the-skyline-problem/)


## 𐀴 二分查找

###### 简单

- [x] [69. x 的平方根](https://leetcode.com/problems/sqrtx/)
- [x] [704. 二分查找](https://leetcode.com/problems/binary-search/)
- [x] [35. 搜索插入位置](https://leetcode.com/problems/search-insert-position/)
- [x] [349. 两个数组的交集](https://leetcode.com/problems/intersection-of-two-arrays/)
- [x] [167. 两数之和 II - 输入有序数组](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/)
- [x] [278. 第一个错误的版本](https://leetcode.com/problems/first-bad-version/)

###### 中等

- [ ] [300. 最长递增子序列](https://leetcode.com/problems/longest-increasing-subsequence/)
- [ ] [74. 搜索二维矩阵](https://leetcode.com/problems/search-a-2d-matrix/)
- [ ] [34. 在排序数组中查找元素的第一个和最后一个位置](https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/)
- [ ] [81. 搜索旋转排序数组 II](https://leetcode.com/problems/search-in-rotated-sorted-array-ii/)
- [ ] [33. 搜索旋转排序数组](https://leetcode.com/problems/search-in-rotated-sorted-array/)
- [ ] [454. 四数相加 II](https://leetcode.com/problems/4sum-ii/)
- [ ] [240. 搜索二维矩阵 II](https://leetcode.com/problems/search-a-2d-matrix-ii/)
- [ ] [718. 最长重复子数组](https://leetcode.com/problems/maximum-length-of-repeated-subarray/)
- [ ] [50. Pow(x, n)](https://leetcode.com/problems/powx-n/)
- [ ] [29. 两数相除](https://leetcode.com/problems/divide-two-integers/)
- [ ] [287. 寻找重复数](https://leetcode.com/problems/find-the-duplicate-number/)
- [ ] [209. 长度最小的子数组](https://leetcode.com/problems/minimum-size-subarray-sum/)
- [ ] [153. 寻找旋转排序数组中的最小值](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/)
- [ ] [162. 寻找峰值](https://leetcode.com/problems/find-peak-element/)
- [ ] [378. 有序矩阵中第 K 小的元素](https://leetcode.com/problems/kth-smallest-element-in-a-sorted-matrix/)
- [ ] [230. 二叉搜索树中第K小的元素](https://leetcode.com/problems/kth-smallest-element-in-a-bst/)

###### 困难

- [ ] [4. 寻找两个正序数组的中位数](https://leetcode.com/problems/median-of-two-sorted-arrays/)
- [ ] [887. 鸡蛋掉落](https://leetcode.com/problems/super-egg-drop/)
- [ ] [410. 分割数组的最大值](https://leetcode.com/problems/split-array-largest-sum/)
- [ ] [154. 寻找旋转排序数组中的最小值 II](https://leetcode.com/problems/find-minimum-in-rotated-sorted-array-ii/)

## 𐀴 位运算

###### 简单

- [x] [136. 只出现一次的数字](https://leetcode.com/problems/single-number/)
- [x] [191. 位1的个数](https://leetcode.com/problems/number-of-1-bits/)
- [x] [169. 多数元素](https://leetcode.com/problems/majority-element/)
- [x] [190. 颠倒二进制位](https://leetcode.com/problems/reverse-bits/)
- [x] [231. 2的幂](https://leetcode.com/problems/power-of-two/)
- [x] [389. 找不同](https://leetcode.com/problems/find-the-difference/)
- [x] [461. 汉明距离](https://leetcode.com/problems/hamming-distance/)
- [x] [405. 数字转换为十六进制数](https://leetcode.com/problems/convert-a-number-to-hexadecimal/)
- [x] [268. 丢失的数字](https://leetcode.com/problems/missing-number/)

###### 中等

- [ ] [78. 子集](https://leetcode.com/problems/subsets/)
- [ ] [338. 比特位计数](https://leetcode.com/problems/counting-bits/)
- [ ] [1318. 或运算的最小翻转次数](https://leetcode.com/problems/minimum-flips-to-make-a-or-b-equal-to-c/)
- [ ] [89. 格雷编码](https://leetcode.com/problems/gray-code/)
- [ ] [260. 只出现一次的数字 III](https://leetcode.com/problems/single-number-iii/)
- [ ] [371. 两整数之和](https://leetcode.com/problems/sum-of-two-integers/)
- [ ] [137. 只出现一次的数字 II](https://leetcode.com/problems/single-number-ii/)
- [ ] [421. 数组中两个数的最大异或值](https://leetcode.com/problems/maximum-xor-of-two-numbers-in-an-array/)

## 𐀴 双指针与滑动窗口

###### 简单

- [x] [387. 字符串中的第一个唯一字符](https://leetcode.com/problems/first-unique-character-in-a-string/)
- [x] [349. 两个数组的交集](https://leetcode.com/problems/intersection-of-two-arrays/)
- [x] [409. 最长回文串](https://leetcode.com/problems/longest-palindrome/)
- [x] [217. 存在重复元素](https://leetcode.com/problems/contains-duplicate/)
- [x] [88. 合并两个有序数组](https://leetcode.com/problems/merge-sorted-array/)
- [x] [283. 移动零](https://leetcode.com/problems/move-zeroes/)
- [x] [125. 验证回文串](https://leetcode.com/problems/valid-palindrome/)
- [x] [344. 反转字符串](https://leetcode.com/problems/reverse-string/)
- [x] [27. 移除元素](https://leetcode.com/problems/remove-element/)
- [x] [977. 有序数组的平方](https://leetcode.com/problems/squares-of-a-sorted-array/)

###### 中等
- [ ] [204. 计数质数](https://leetcode.com/problems/count-primes/)
- [ ] [3. 无重复字符的最长子串](https://leetcode.com/problems/longest-substring-without-repeating-characters/)
- [ ] [781. 森林中的兔子](https://leetcode.com/problems/rabbits-in-forest/)
- [ ] [49. 字母异位词分组](https://leetcode.com/problems/group-anagrams/)
- [ ] [18. 四数之和](https://leetcode.com/problems/4sum/)
- [ ] [560. 和为 K 的子数组](https://leetcode.com/problems/subarray-sum-equals-k/)
- [ ] [454. 四数相加 II](https://leetcode.com/problems/4sum-ii/)
- [ ] [11. 盛最多水的容器](https://leetcode.com/problems/container-with-most-water/)
- [ ] [16. 最接近的三数之和](https://leetcode.com/problems/3sum-closest/)
- [ ] [18. 四数之和](https://leetcode.com/problems/4sum/)
- [ ] [424. 替换后的最长重复字符](https://leetcode.com/problems/longest-repeating-character-replacement/)
- [ ] [713. 乘积小于K的子数组](https://leetcode.com/problems/subarray-product-less-than-k/)

###### 困难

- [ ] [76. 最小覆盖子串](https://leetcode.com/problems/minimum-window-substring/)
- [ ] [992. K 个不同整数的子数组](https://leetcode.com/problems/subarrays-with-k-different-integers/)

## 𐀴 矩阵

###### 简单

- [x] [867. 转置矩阵](https://leetcode.com/problems/transpose-matrix/)
- [x] [832. 翻转图像](https://leetcode.com/problems/flipping-an-image/)

###### 中等

- [ ] [54. 螺旋矩阵](https://leetcode.com/problems/spiral-matrix/)
- [ ] [59. 螺旋矩阵 II](https://leetcode.com/problems/spiral-matrix-ii/)
- [ ] [73. 矩阵置零](https://leetcode.com/problems/set-matrix-zeroes/)
- [ ] [48. 旋转图像](https://leetcode.com/problems/rotate-image/)

## 𐀴 动态规划

### 一维

###### 简单

- [x] [70. 爬楼梯](https://leetcode.com/problems/climbing-stairs/)
- [x] [53. 最大子序和](https://leetcode.com/problems/maximum-subarray/)
- [x] [121. 买卖股票的最佳时机](https://leetcode.com/problems/best-time-to-buy-and-sell-stock/)
- [x] [746. 使用最小花费爬楼梯](https://leetcode.com/problems/min-cost-climbing-stairs/)

###### 中等

- [ ] [337. 打家劫舍 III](https://leetcode.com/problems/house-robber-iii/)
- [ ] [322. 零钱兑换](https://leetcode.com/problems/coin-change/)
- [ ] [300. 最长递增子序列](https://leetcode.com/problems/longest-increasing-subsequence/)
- [ ] [139. 单词拆分](https://leetcode.com/problems/word-break/)
- [ ] [152. 乘积最大子数组](https://leetcode.com/problems/maximum-product-subarray/)
- [ ] [338. 比特位计数](https://leetcode.com/problems/counting-bits/)
- [ ] [309. 最佳买卖股票时机含冷冻期](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-with-cooldown/)
- [ ] [264. 丑数 II](https://leetcode.com/problems/ugly-number-ii/)
- [ ] [279. 完全平方数](https://leetcode.com/problems/perfect-squares/)

###### 困难

- [ ] [32. 最长有效括号](https://leetcode.com/problems/longest-valid-parentheses/)
- [ ] [354. 俄罗斯套娃信封问题](https://leetcode.com/problems/russian-doll-envelopes/)
- [ ] [123. 买卖股票的最佳时机 III](https://leetcode.com/problems/best-time-to-buy-and-sell-stock-iii/)

### 二维

###### 中等

- [ ] [5. 最长回文子串](https://leetcode.com/problems/longest-palindromic-substring/)
- [ ] [1143. 最长公共子序列](https://leetcode.com/problems/longest-common-subsequence/)
- [ ] [131. 分割回文串](https://leetcode.com/problems/palindrome-partitioning/)
- [ ] [62. 不同路径](https://leetcode.com/problems/unique-paths/)
- [ ] [64. 最小路径和](https://leetcode.com/problems/minimum-path-sum/)
- [ ] [221. 最大正方形](https://leetcode.com/problems/maximal-square/)
- [ ] [416. 分割等和子集](https://leetcode.com/problems/partition-equal-subset-sum/)
- [ ] [718. 最长重复子数组](https://leetcode.com/problems/maximum-length-of-repeated-subarray/)
- [ ] [494. 目标和](https://leetcode.com/problems/target-sum/)

###### 困难

- [ ] [10. 正则表达式匹配](https://leetcode.com/problems/regular-expression-matching/)
- [ ] [72. 编辑距离](https://leetcode.com/problems/edit-distance/)
- [ ] [887. 鸡蛋掉落](https://leetcode.com/problems/super-egg-drop/)
- [ ] [132. 分割回文串 II](https://leetcode.com/problems/palindrome-partitioning-ii/)
- [ ] [44. 通配符匹配](https://leetcode.com/problems/wildcard-matching/)
- [ ] [410. 分割数组的最大值](https://leetcode.com/problems/split-array-largest-sum/)

## 𐀴 图论

### DFS

###### 中等

- [ ] [394. 字符串解码](https://leetcode.com/problems/decode-string/)
- [ ] [721. 账户合并](https://leetcode.com/problems/accounts-merge/)
- [ ] [547. 省份数量](https://leetcode.com/problems/number-of-provinces/)
- [ ] [494. 目标和](https://leetcode.com/problems/target-sum/)
- [ ] [695. 岛屿的最大面积](https://leetcode.com/problems/max-area-of-island/)
- [ ] [130. 被围绕的区域](https://leetcode.com/problems/surrounded-regions/)
- [ ] [1631. 最小体力消耗路径](https://leetcode.com/problems/path-with-minimum-effort/) 
- [ ] [207. 课程表](https://leetcode.com/problems/course-schedule/)
- [ ] [417. 太平洋大西洋水流问题](https://leetcode.com/problems/pacific-atlantic-water-flow/)

###### 困难

- [ ] [679. 24 点游戏](https://leetcode.com/problems/24-game/)

### BFS

###### 简单

- [x] [690. 员工的重要性](https://leetcode.com/problems/employee-importance/)

###### 中等

- [ ] [279. 完全平方数](https://leetcode.com/problems/perfect-squares/)
- [ ] [130. 被围绕的区域](https://leetcode.com/problems/surrounded-regions/)
- [ ] [1319. 连通网络的操作次数](https://leetcode.com/problems/number-of-operations-to-make-network-connected/)
- [ ] [934. 最短的桥](https://leetcode.com/problems/shortest-bridge/)
- [ ] [785. 判断二分图](https://leetcode.com/problems/is-graph-bipartite/)
- [ ] [994. 腐烂的橘子](https://leetcode.com/problems/rotting-oranges/)
- [ ] [752. 打开转盘锁](https://leetcode.com/problems/open-the-lock/)
- [ ] [1162. 地图分析](https://leetcode.com/problems/as-far-from-land-as-possible/)
- [ ] [529. 扫雷游戏](https://leetcode.com/problems/minesweeper/)

###### 困难

- [ ] [815. 公交路线](https://leetcode.com/problems/bus-routes/)
- [ ] [127. 单词接龙](https://leetcode.com/problems/word-ladder/)
- [ ] [1293. 网格中的最短路径](https://leetcode.com/problems/shortest-path-in-a-grid-with-obstacles-elimination/)
- [ ] [773. 滑动谜题](https://leetcode.com/problems/sliding-puzzle/)
- [ ] [827. 最大人工岛](https://leetcode.com/problems/making-a-large-island/)

### Dijkstra

- [ ] [787. K 站中转内最便宜的航班](https://leetcode.com/problems/cheapest-flights-within-k-stops/)

### 拓扑排序

###### 中等

- [ ] [207. 课程表](https://leetcode.com/problems/course-schedule/)
- [ ] [210. 课程表 II](https://leetcode.com/problems/course-schedule-ii/)

###### 困难

- [ ] [329. 矩阵中的最长递增路径](https://leetcode.com/problems/longest-increasing-path-in-a-matrix/)
- [ ] [1203. 项目管理](https://leetcode.com/problems/sort-items-by-groups-respecting-dependencies/)

## 𐀴 并查集

###### 中等

- [ ] [200. 岛屿数量](https://leetcode.com/problems/number-of-islands/)
- [ ] [721. 账户合并](https://leetcode.com/problems/accounts-merge/)
- [ ] [547. 省份数量](https://leetcode.com/problems/number-of-provinces/)
- [ ] [130. 被围绕的区域](https://leetcode.com/problems/surrounded-regions/)
- [ ] [1631. 最小体力消耗路径](https://leetcode.com/problems/path-with-minimum-effort/)
- [ ] [399. 除法求值](https://leetcode.com/problems/evaluate-division/)
- [ ] [1319. 连通网络的操作次数](https://leetcode.com/problems/number-of-operations-to-make-network-connected/)
- [ ] [684. 冗余连接](https://leetcode.com/problems/redundant-connection/)

###### 困难

- [ ] [128. 最长连续序列](https://leetcode.com/problems/longest-consecutive-sequence/)
- [ ] [765. 情侣牵手](https://leetcode.com/problems/couples-holding-hands/)

## 𐀴 设计

###### 简单

- [x] [1603. 设计停车系统](https://leetcode.com/problems/design-parking-system/)
- [ ] [705. 设计哈希集合](https://leetcode.com/problems/design-hashset/)
- [ ] [706. 设计哈希映射](https://leetcode.com/problems/design-hashmap/)
- [x] [703. 数据流中的第 K 大元素](https://leetcode.com/problems/kth-largest-element-in-a-stream/)

###### 中等

- [ ] [146. LRU 缓存机制](https://leetcode.com/problems/lru-cache/)
- [ ] [341. 扁平化嵌套列表迭代器](https://leetcode.com/problems/flatten-nested-list-iterator/)
- [ ] [208. 实现 Trie (前缀树)](https://leetcode.com/problems/implement-trie-prefix-tree/)
- [ ] [173. 二叉搜索树迭代器](https://leetcode.com/problems/binary-search-tree-iterator/)
- [ ] [622. 设计循环队列](https://leetcode.com/problems/design-circular-queue/)
- [ ] [380. O(1) 时间插入、删除和获取随机元素](https://leetcode.com/problems/insert-delete-getrandom-o1/)

###### 困难

- [ ] [295. 数据流的中位数](https://leetcode.com/problems/find-median-from-data-stream/)
- [ ] [460. LFU 缓存](https://leetcode.com/problems/lfu-cache/)

## 𐀴 贪心

###### 中等

- [ ] [264. 丑数 II](https://leetcode.com/problems/ugly-number-ii/)
- [ ] [946. 验证栈序列](https://leetcode.com/problems/validate-stack-sequences/)
- [ ] [767. 重构字符串](https://leetcode.com/problems/reorganize-string/)
- [ ] [373. 查找和最小的 K 对数字](https://leetcode.com/problems/find-k-pairs-with-smallest-sums/)
- [ ] [313. 超级丑数](https://leetcode.com/problems/super-ugly-number/)


## 𐀴 回溯

###### 中等

- [ ] [46. 全排列](https://leetcode.com/problems/permutations/)
- [ ] [22. 括号生成](https://leetcode.com/problems/generate-parentheses/)
- [ ] [93. 复原 IP 地址](https://leetcode.com/problems/restore-ip-addresses/)
- [ ] [78. 子集](https://leetcode.com/problems/subsets/)
- [ ] [17. 电话号码的字母组合](https://leetcode.com/problems/letter-combinations-of-a-phone-number/)
- [ ] [79. 单词搜索](https://leetcode.com/problems/word-search/)
- [ ] [90. 子集 II](https://leetcode.com/problems/subsets-ii/)
- [ ] [39. 组合总和](https://leetcode.com/problems/combination-sum/)
- [ ] [77. 组合](https://leetcode.com/problems/combinations/)
- [ ] [40. 组合总和 II](https://leetcode.com/problems/combination-sum-ii/)
- [ ] [47. 全排列 II](https://leetcode.com/problems/permutations-ii/)
- [ ] [842. 将数组拆分成斐波那契序列](https://leetcode.com/problems/split-array-into-fibonacci-sequence/)
- [ ] [216. 组合总和 III](https://leetcode.com/problems/combination-sum-iii/)
- [ ] [89. 格雷编码](https://leetcode.com/problems/gray-code/)

###### 困难

- [ ] [51. N 皇后](https://leetcode.com/problems/n-queens/)
- [ ] [37. 解数独](https://leetcode.com/problems/sudoku-solver/)
- [ ] [126. 单词接龙 II](https://leetcode.com/problems/word-ladder-ii/)
- [ ] [1659. 最大化网格幸福感](https://leetcode.com/problems/maximize-grid-happiness/)

## 𐀴 克隆

###### 中等

- [ ] [133. 克隆图](https://leetcode.com/problems/clone-graph/)
- [ ] [138. 复制带随机指针的链表](https://leetcode.com/problems/copy-list-with-random-pointer/)

## 𐀴 数学

##### 简单


- [x] [628. 三个数的最大乘积](https://leetcode.com/problems/maximum-product-of-three-numbers/)
- [x] [976. 三角形的最大周长](https://leetcode.com/problems/largest-perimeter-triangle/)
- [x] [202. 快乐数](https://leetcode.com/problems/happy-number/)
- [x] [1232. 缀点成线](https://leetcode.com/problems/check-if-it-is-a-straight-line/)

###### 中等
- [ ] [204. 计数质数](https://leetcode.com/problems/count-primes/)
- [ ] [29. 两数相除](https://leetcode.com/problems/divide-two-integers/)
- [ ] [343. 整数拆分](https://leetcode.com/problems/integer-break/)
- [ ] [166. 分数到小数](https://leetcode.com/problems/fraction-to-recurring-decimal/)

###### 困难

- [ ] [149. 直线上最多的点数](https://leetcode.com/problems/max-points-on-a-line/)


## 𐀴 极大极小化

###### 简单

- [x] [292. Nim 游戏](https://leetcode.com/problems/nim-game/)

###### 中等

- [ ] [375. 猜数字大小 II](https://leetcode.com/problems/guess-number-higher-or-lower-ii/)
- [ ] [486. 预测赢家](https://leetcode.com/problems/predict-the-winner/)
- [ ] [464. 我能赢吗](https://leetcode.com/problems/can-i-win/)
- [ ] [877. 石子游戏](https://leetcode.com/problems/stone-game/)

## 𐀴 几何

###### 简单

- [x] [1266. 访问所有点的最小时间](https://leetcode.com/problems/minimum-time-visiting-all-points/)
- [x] [892. 三维形体的表面积](https://leetcode.com/problems/surface-area-of-3d-shapes/)

###### 中等

- [ ] [1401. 圆和矩形是否有重叠](https://leetcode.com/problems/circle-and-rectangle-overlapping/)
- [ ] [963. 最小面积矩形 II](https://leetcode.com/problems/minimum-area-rectangle-ii/)

###### 困难

- [ ] [587. 安装栅栏](https://leetcode.com/problems/erect-the-fence/)
- [ ] [1515. 服务中心的最佳位置](https://leetcode.com/problems/best-position-for-a-service-centre/)
