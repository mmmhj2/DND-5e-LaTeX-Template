# DnD 5e LaTeX 中文模板

本宏包是[DND-5e-LaTeX-Template](https://github.com/rpgtex/DND-5e-LaTeX-Template)的中文化版本。
由于中文和西方文字排版和标点的显著不同，这个宏包虽然基于上述宏包，但是表现出一些不同的行为，具体如下所述。

## 使用方法

本宏包的安装方法和原宏包没有区别，值得注意的是使用上的不同。

由于`babel`和`polyglossia`对中文的支持欠缺，本宏包推荐和`ctex`一同使用。
推荐文档类选择`ctexbook`，然后再通过`\usepackage{dnd}`引入本宏包。

本宏包提供一些专为DND设计的函数与布局，具体用法可参见`example.tex`

## 与原版的不同

由于常用的本地化宏包`babel`和`polyglossia`对中文的支持欠缺，本宏包不使用它们进行语言的选择，而是直接在英文字符串上进行修改。
相对应的，原宏包中怪物的数据板中存在一些自动生成的英文标点，这些标点也被全部替换为中文标点。

## 其他内容

有关其他补充内容，可参考英文版README文件`README-EN.md`或随宏包提供的样例文件`example.tex`。

本宏包和原宏包相同，按MIT协议发布。
