# Latex最快简单入门

* 简介：Latex是一种轻量级的文章编辑语言，可以套用各种文章格式的现成模板，让你只用专注于文字的撰写，而不需要排版文字的格式，十分方便。当然，如果你只是想做一些课堂笔记或是随手写一些东西，这里还是推荐markdown语言。
* 编辑器：**[overleaf在线编辑器](https://www.overleaf.com/)**，TexWorks editor

```Latex
%导言
\documentclass{ctexart} %告知文件类型
\title{Latex最快简单入门}
\author{PHC}
\date{\today} %\today代表指今天的日期

%正文
\begin{document}%开始标志
\maketitle %执行导言部分的代码
\textbf{这是一段粗体}
\textit{这是一段斜体}
\section{第一章}
\subsection{1.1}
\subsubsection{1.1.1}
\section{第二章}
\begin{equation}%标号公式
E=MC^2
\end{equation}
这是一个行内公式$f(x)=3x^2-6$,$g(x)=f'(x)=6x$。


这是一个行间公式$$s=v(m/s)*t(s)$$
\begin{table}[]
    \centering
    \begin{tabular}{c|c|c}
        姓名 &学号&成绩  \\
         PHC& 215302&99\\
         
    \end{tabular}
    \caption{研究生期末考试成绩单}
    \label{tab:my_label}
\end{table}


\end{document}%结束标志
```

> 演示效果
>
> * overleaf编辑示意图
>
> ![overleaf编辑示意图](C:\Users\PengH\phw_mail_hfut_edu\OneDrive - mail.hfut.edu.cn\图片\项目图\Latex效果演示.PNG "overleaf编辑示意图")
>
> * PDF演示效果图
>
> ![PDF演示效果图](C:\Users\PengH\phw_mail_hfut_edu\OneDrive - mail.hfut.edu.cn\图片\项目图\PDF版本.PNG "PDF演示效果图")