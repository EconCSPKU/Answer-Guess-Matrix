## Guess Matrix绘制

### 已实现的功能

- 用状压DP求dag
- 从多种格式的数据进行读入
- 以png和pdf格式输出Guess Matrix

### 读入功能

- 问卷星返回的excel文件，处理完选项后复制入txt文件中，放入data目录下
- 已处理的数据放到data目录中特定目录下

### 未确定的问题

- 是否显示刻度条，在对数颜色下效果不好
- 是否显示横纵轴
- 是否显示题目名字
- 是否把文字斜过来

### TODO

- 生成latex代码(写了一半，仍有bug)
- PageRank算法