| 题目                                                         | 日期      | 难度          | 思路                                                         |
| ------------------------------------------------------------ | --------- | ------------- | ------------------------------------------------------------ |
| [A BIT of an Inequality](https://codeforces.com/contest/1957/problem/D) | 2024/4/24 | div2-D        | 注意到, 枚举每个中间数时, 对其最高 bit 位 1, 合法答案数量为左半区间为奇数个 1,右半为偶数个 1, 加上反情况, 用 dp 预处理. |
| [Unfair-Game](https://codeforces.com/problemset/problem/1955/F) | 4/26      | 1800          | 找到最近的 XOR=0, 此后删每次 2 个,                           |
| [Colored-Balls](https://codeforces.com/problemset/problem/1954/D) |           | 1800          | 水题                                                         |
| [Moving Both Hands](https://codeforces.com/contest/1966/problem/C) | 4/27      | Div2-C        | 别写思维了, 写一写正宗的 SG 吧!<br />把原序列去重排序, 让相邻两数的差值为新序列, 再从后往前跑 SG, 当某一位不为 1 时, 也要从 <x-1,before> ~ <1,before> 更新出来 |
| [Permutation Game](https://codeforces.com/problemset/problem/1772/E) | 4/29      | 1700          | 思维水题                                                     |
| [Lowbit](https://codeforces.com/problemset/gymProblem/103145/D) | 4/30      |               | 注意到每个数最多加 log 次, 就可以用统一的 *2 操作来维护, 所以建树维护, 同时特别标记每个数是否到达 100..00 状态, 没的话单独处理. **注意初始化和位移运算爆范围** |
| [Reverse Card (Hard Version)](https://codeforces.com/contest/1972/problem/D2) | 5/7       | Div2-D2       | 傻逼数学                                                     |
| [本初字符串](https://ac.nowcoder.com/acm/contest/82401/F)    | 5/10      | 牛客小白 F    | 推出` len(t)` 为` len(s)` 的因子, 之后枚举 `len(t)` 长度, 先找出每位取最大贡献字符组成的 `t`,再从前往后依次尝试缩小 `t[i]`. |
| [E.Increasing Subsequences](https://codeforces.com/problemset/problem/1922/E) | 5/11      | 1800          | 构造, STD::list 竟然是循环链表                               |
| [Stars](http://poj.org/problem?id=2352)                      | 5/11      |               | 树状数组处理二维偏序, 毒瘤的 POJ ! ! !                       |
| [F. Moving Points](https://codeforces.com/problemset/problem/1311/F) | 5/11      | 1900          | 不那么明显的二维偏序, 树状数组 + 离散化 处理                 |
| [B. Flipping Game](https://codeforces.com/gym/104459/problem/B) | 5/12      |               | 蛋哥的绝妙 DP, `dp[tis][i]`维护当前字符串有多少与目标字符串不同, 转移时转移到所有的可能下一层`dp[nex][i]`, and 卡 log 时间,预处理出来 inv. |
| [E.BaoBaoLovesReading](https://codeforces.com/gym/104459/problem/E) | 5/13      | 省赛金        | 树状数组维护每两个相同的书之间有多少种书, 种类大于 k 就要重新从书架上取, 前缀和同时维护 k=1~n 的答案. |
| [P3810[模板]三维偏序](https://www.luogu.com.cn/problem/P3810) | 5/13      | 省选+ / NOI-  | cdq 套 树状数组处理, 也可以 cdq 套 cdq 处理                  |
| [E. Liner vectors](https://codeforces.com/gym/102801/problem/E) | 5/14      |               | 线代 ? + 构造                                                |
| [最大二分图匹配](https://www.luogu.com.cn/problem/P3386)     | 5/15      |               | 匈牙利板纸                                                   |
| [P1129 [ZJOI2007] 矩阵游戏](https://www.luogu.com.cn/problem/P1129) | 5/15      | 提高+ / 省选− | 注意到, 交换行列等价, 就按黑色块的 x,y 坐标连边, 跑最大二分图 |
| [K.Bracket Sequence](https://codeforces.com/gym/103486/problem/K) | 5/15      |               | 卡特兰板纸                                                   |
| [神性之陨](https://ac.nowcoder.com/acm/problem/267934)       | 5/22      |               | https://blog.nowcoder.net/n/82256070063e4a25bbbb966f3ad4fccd |
| [模板-扫描线](https://www.luogu.com.cn/problem/P5490)        | 5/28      | 提高+/省选−   | 扫描线板纸                                                   |
| [D.Invertible_Bracket_Sequences](https://codeforces.com/contest/1976/problem/D) | 6/3       |               |                                                              |
