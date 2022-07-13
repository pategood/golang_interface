slice 和 map 的区别？

    slice 
        是构建在数组之上的一种抽象数据结构。Slice 拥有一个指向数组开始位置的指针、数组长度以及 Slice 可以使用该数组的最大容量。Slice 可以按需增长或收缩。Slice 的增长通常包括为底层的数组重新分配内存


    map 


    

    场景对比
        1. 查找int类型数据   n小用slice，n大用map
        2. 查找string类型数据    map的效率基本都不slice高
        3. 给定索引    差距不大 ，但是slice比map快
        4. 遍历元素列表进行操作 slice比map快