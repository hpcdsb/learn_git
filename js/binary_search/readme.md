在一个一维的正整数数组，查找数，如果有则返回下标，否则-1
二分查找 可以从 N -> logN
1. 二分查找要注意的问题和bug
[1, 10, 3, 6, 9] 排序

(min + max) / 2 内存的限制

2. 在基础之外，考虑异常 BAT考题
    溢出 二分查找 使用 mid 计算方法规避溢出
    考察语言的底层