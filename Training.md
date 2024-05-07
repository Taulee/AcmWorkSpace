| 题目                                                         | 日期      | 难度    | 思路                                                         |
| ------------------------------------------------------------ | --------- | ------- | ------------------------------------------------------------ |
| [A BIT of an Inequality](https://codeforces.com/contest/1957/problem/D) | 2024/4/24 | div2-D  | 注意到, 枚举每个中间数时, 对其最高 bit 位 1, 合法答案数量为左半区间为奇数个 1,右半为偶数个 1, 加上反情况, 用 dp 预处理. |
| [Unfair-Game](https://codeforces.com/problemset/problem/1955/F) | 4/26      | 1800    | 找到最近的 XOR=0, 此后删每次 2 个,                           |
| [Colored-Balls](https://codeforces.com/problemset/problem/1954/D) |           | 1800    | 水题                                                         |
| [Moving Both Hands](https://codeforces.com/contest/1966/problem/C) | 4/27      | Div2-C  | 别写思维了, 写一写正宗的 SG 吧!<br />把原序列去重排序, 让相邻两数的差值为新序列, 再从后往前跑 SG, 当某一位不为 1 时, 也要从 <x-1,before> ~ <1,before> 更新出来 |
| [Permutation Game](https://codeforces.com/problemset/problem/1772/E) | 4/29      | 1700    | 思维水题                                                     |
| [Lowbit](https://codeforces.com/problemset/gymProblem/103145/D) | 4/30      |         | 注意到每个数最多加 log 次, 就可以用统一的 *2 操作来维护, 所以建树维护, 同时特别标记每个数是否到达 100..00 状态, 没的话单独处理. **注意初始化和位移运算爆范围** |
| [Reverse Card (Hard Version)](https://codeforces.com/contest/1972/problem/D2) | 5/7       | Div2-D2 | 傻逼数学                                                     |
