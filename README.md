# 中科大软件学院工程硕士论文模板

此模板是根据自己的论文经验编写而成，并不是官方标准，大家酌情参考。

## 声明

论文模板内容全部属于虚构，请大家关注论文格式和结构。

## 论文结构

工程硕士论文必须严格按照软件工程规范来进行编写，所以推荐大家按照论文中的每章内容来进行撰写。

## 论文格式

目前Latex的论文格式只有每章的大标题上下间距不太合适，其他都OK。我还没找到合适的调节间距的方法，希望大家使用的时候有方法调节请告诉我。

## 编译

`latexmk -cd -f -xelatex -interaction=nonstopmode -synctex=1 paper.tex`

可以使用命令行，很方便的进行编译。不过我更推荐使用[Sublime Text](https://www.sublimetext.com/)和[LaTeXTools](https://github.com/SublimeText/LaTeXTools)来进行构建和编译。

在tex文件下直接使用`Ctrl + B`就可以快速编译。Latex推荐使用 texlive 套件。

## 新手入门

* [如何使用 LaTeX 排版论文](https://www.overleaf.com/articles/ru-he-shi-yong-latex-pai-ban-lun-wen/bdynvrzpqmwq)
* [一份不太简短的LATEX介绍](http://mirror.hust.edu.cn/CTAN/info/lshort/chinese/lshort-zh-cn.pdf)


## 参考规范：
* [《中国科学技术大学研究生学位论文撰写规范》](http://gradschool.ustc.edu.cn/ylb/material/xw/wdxz/30.doc)
* [ustcthesis](https://github.com/ustctug/ustcthesis)
