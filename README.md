# leetcode_c++
STL 是“Standard Template Library”

1. 1_two_num (hash_table `include<unsordered_map>`)
1. 2_add_two_numbers (single_linked_node)
1. 3_longest_substring_without_repeating_characters(hash_table sliding_windows two_points)

## https://github.com/changgyhub/leetcode_101
教程来了
## 贪心算法
- 455_assign_cookies
vector[i]
`#include<algorithm>` sort()  https://www.cnblogs.com/stones-dream/p/10183210.html
`#include<vector>`
`#include<functional>`
- 135_candy
max()
`#include<numeric>`accumulate https://blog.csdn.net/u011499425/article/details/52756242
- 435_non_overlapping_intervals
C++11的一大亮点就是引入了Lambda表达式
https://www.cnblogs.com/DswCnblog/p/5629165.html
for (int it : myvec)
        cout << it << ' ';
#### 练习
- 605_can_place_flower
前2可以直接判定，其他情况贪心分为三部分：前2，中间，后2
Runtime: 32 ms, faster than 79.84% of C++ online submissions for Can Place Flowers.
