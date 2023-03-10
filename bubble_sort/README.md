# 冒泡排序

## 问题描述

给定一个未排序整数序列, 使用冒泡排序算法进行排序.

## 输入

仅一行内容，由空格分隔的未排序整数序列, 例如:

```txt
2 4 6 1 3 5
```

注意: 没有输入的整数个数提示.

## 输出

一行排序好由空格分隔的整数序列, 例如:

```txt
1 2 3 4 5 6
```

## 测试

[check.py](./check.py)脚本测试单个输入是否排好序.
[generator.py](./generator.py)脚本产生多个随机输入.
可以使用`make ramdom_test`命令来测试随机输入是否能通过验证.

## 性能分析

## 算法优化

可以增加一个flag记录这一趟是否交换元素, 如果没有交换则该list已排好序, 无需下一趟比较.