# 凹语言生命游戏的例子


[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/chai2010/wa-example-life)


- 在当前目录执行 `wa run` 命令


显示效果如下:

![](screenshot.png)

## Life简介

Life——全称“Conway's Game of Life”，是一个自运行的小游戏，它模拟了一种虚拟的二维栅格生命，栅格中的每个网格被称为一个细胞，每个细胞有活/死两种状态，并且细胞状态按照以下规则演变：

- 如果一个活细胞周围的活细胞少于2个，那么下一代它将死掉
- 如果一个活细胞周围的活细胞数量为2个或3个，那么它将继续活至下一代
- 如果一个活细胞周围的活细胞数量超过3个，那么下一代它将死掉
- 如果一个死细胞周围的活细胞数量为3个，那么下一代它将复活

这里“周围”的含义是与该细胞邻接的8个细胞，并且代与代之间的状态是整体隔离的，也就是说每个细胞的状态仅取决于它周围的细胞在上一代的状态，游戏的更多详细信息可参阅维基百科：https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life。

