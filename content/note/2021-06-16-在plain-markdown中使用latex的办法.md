---
title: 在plain Markdown中使用latex的办法
author: xyq
date: '2021-06-16'
slug: 在plain-markdown中使用latex的办法
categories:
  - R
tags:
  - blogdown
disable_comments: yes
---
在写PRML系列文章的时候，遇到了不能使用latex的情况。因为考虑兼容性，没使用rmd文件
使用了md文件，也就是plain markdown。在解析时候，不能读取latex文件。参考了yihui大佬的
[The Best Way to Support LaTeX Math in Markdown with MathJax](https://yihui.org/en/2018/07/latex-math-markdown/)
后，得知

> If you use Pandoc or R Markdown, there is no need to read this post, because Pandoc supports LaTeX math very well. This post is only for plain Markdown users. If you understand Chinese, you may read this post I wrote last year instead.

他的建议是在head或者foot模板里，添加下面的语句，直接调用js

> \<script src="//yihui.org/js/math-code.js">\</script>
或者是用rstudio的
>\<script async
  src="//mathjax.rstudio.com/latest/MathJax.js?config=TeX-MML-AM_CHTML">\</script>

即可解决

我怕yihui大佬又改域名，直接把他的math-code.js文件抄过来用
直接可以用这个
> \<script src="js/math-code.js">\</script>
