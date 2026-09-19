# 计算物理

!!! tip "这是自学者的实验室"
    物理自学最大的两个缺口是**没有实验**和**没有反馈**。计算项目能同时补上：代码跑错了会报错（反馈），跑出来的图可以展示（成果）。

本模块建议**贯穿全程**，而不是学完理论后再补。每学完一个物理板块，就立刻用代码实现它。

## 页面

- [数值方法](数值方法.md)　需要掌握的算法清单
- [项目清单](项目清单.md)　★ 按难度分层的 25 个项目

## 线上课程

| 课程 | 说明 |
| --- | --- |
| [MIT 18.335J Introduction to Numerical Methods](https://ocw.mit.edu/courses/18-335j-introduction-to-numerical-methods-spring-2019/) | 现代化，与项目清单最贴合 |
| [MIT 18.330 Introduction to Numerical Analysis](https://ocw.mit.edu/courses/18-330-introduction-to-numerical-analysis-spring-2012/) | 数值方法的理论基础，更严谨 |
| [MIT 18.085 Computational Science and Engineering I](https://ocw.mit.edu/courses/18-085-computational-science-and-engineering-i-fall-2008/) | Strang 的经典课，偏工程应用 |

完整清单见[在线课程总表](../在线课程总表.md)。

## 三条使用建议

1. **学完即做**。学完量子力学的定态薛定谔方程，立刻去写有限差分对角化。拖一周，效果减半。
2. **代码要存档**。每个项目一个 Notebook，有说明、有检验，推到 GitHub。这就是你的作品集。
3. **必须做收敛性检验**。网格加密一倍、步长减半，结果应按理论阶数收敛。这是判断代码对不对的唯一硬标准。

## 起步建议

如果你完全没有编程基础：先花两周学会 Python 基础语法 + NumPy，然后直接从[项目清单](项目清单.md)的第 1 题开始，**边做边学数值方法**，不要先把 Newman 的教材通读一遍。
