# LaTeX 与科技写作

## 为什么物理自学者必须会 LaTeX

不只是为了排版好看。用 LaTeX 写习题解答会强迫你**把推导写完整**——手写时你容易跳过两步然后在第三步卡住，LaTeX 不会让你糊弄过去。

## 上手路径

| 阶段 | 做法 |
| --- | --- |
| 起步 | 直接用 [Overleaf](https://www.overleaf.com)，省去安装配置 |
| 本地 | TeX Live（跨平台）或 MiKTeX（Windows） |
| 编辑器 | VS Code + LaTeX Workshop，或 TeXstudio |
| 中文 | `ctex` 宏包 / XeLaTeX 编译 |

## 物理写作常用宏包

```latex
\usepackage{amsmath,amssymb}   % 数学公式与符号
\usepackage{physics}           % \dv, \pdv, \bra, \ket, \comm 等物理专用宏
\usepackage{siunitx}           % 单位与量纲，物理写作必备
\usepackage{booktabs}          % 三线表
\usepackage{tikz,pgfplots}     % 矢量图与数据绘图
\usepackage{hyperref}          % 交叉引用
```

!!! note "强烈推荐 `physics` 宏包"
    `\bra{\psi}`、`\ket{\psi}`、`\braket{a|b}`、`\comm{A}{B}`、`\dv{f}{x}`、`\pdv{f}{x}` —— 这些宏让量子力学与场论的书写速度快一倍，而且源码可读性极好。

## 建议的工作流

1. **每门课一个 LaTeX 文档**，作为你的"作业本"，做完的题全部归档
2. 用 `\label` / `\ref` 做交叉引用，方便回看
3. 把文档推到 GitHub，既是备份也是作品集
4. 计算项目的图用 `pgfplots` 或导出 PDF 后插入，保持矢量

## 资源

- [Overleaf 官方文档](https://www.overleaf.com/learn)　模板与教程
- [Detexify](https://detexify.kirelabs.org)　手画符号查命令
- [Physics 宏包文档](https://ctan.org/pkg/physics)
- 一份好的物理笔记模板：搜 "physics homework LaTeX template"
