# (PART) R 安装问题 {-}

# 常见问题汇总

###  github 上 项目错误被当成pacakge，进行安装

github 上的 package ，会在 README.md 中有明显的提示安装信息：

devtools::install_github('github-name/pkg-name')

remotes::install_github('github-name/pkg-name')

如果已经提交到 CRAN, 上会显示有：

install.packages('pkg-name') 类似代码



 **不含有以上代码的项目，几乎不可能是 R 语言的 package ！！！**

同时，主流的包，也会在 README.md 中显示如以下 package 类似的 badge (牌子)：

 **openxlsx 中显示 其在 CRAN 上的版本号为： 4.2.4， 且当前 github 项目的 R CMD check 自动通过，可以正常安装。**









### 规范的提问方式和流程


首先，描述问题，接着提供可以重复的最小的代码块，不要涉及到提问者过多的知识背景及复杂的原始数据，

用最小的例子，最快地说明问题，让其他人能够重复出来问题。




之后，描述提问者想要得到的结果，以及实际得到的结果。

最后，说明提问者使用的平台信息，包的版本等等。

其次，代码中涉及的数据，优先考虑最小化，以及常数通过 datapasta 包，将当前工作空间中的变量保存为可以运行的代




