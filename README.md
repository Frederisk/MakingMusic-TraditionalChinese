# 創作音樂（正體中文翻譯）

![progress](https://img.shields.io/badge/progress-5%-red)

翻譯進度：16/293

時間有限，而且英文水平也很有限，所以基本上就是隨便亂翻。網路上隨便找了一下貌似沒有啥能輕易取得的中文譯本，又覺得這種好書都免費提供原本數位檔了很多人卻因為語言問題沒法閱讀學習很可惜，所以就嘗試翻譯一下，順便也當是練習自己 $\LaTeX$ 能力了。原文中也比較常見那種類比的說法來描述事物，不是很擅長應對這些句子，先粗糙過一遍然後再重讀的時候精修吧Orz。

## 編譯方式

編譯所需字體：Libertinus Serif、Libertinus Sans、Source Han Serif TC、Source Han Sans TC、Source Han Sans HW TC

命令：`latexmk -synctex=1 -interaction=nonstopmode -file-line-error -xelatex book.tex`

理論也可透過 `XeLaTeX`->`BibTeX`->`XeLaTeX` 的方式構建。
