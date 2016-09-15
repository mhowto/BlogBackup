---
title: cbc的C++实现开坑啦
---

## 开坑思路
[cbc](https://github.com/aamine/cbc)是[《自制编译器》](https://book.douban.com/subject/26806041/)中一个用Java实现的编译器，这里用C++来实现一把。

## 对象与目标
文章对象: 编译原理及C++爱好者。

通过使用C++改写cbc实现，来获得以下技能:
- 使用boost.spirit x3 来生成EBNF文法的tokenizer和parser。
- 静态类型检查的简单方法
- 中间代码生成的方法
- 生成汇编代码
- 后端优化

## 系列目录

- 使用boost.spirit x3 生成parser
- 静态类型检查
- 中间代码生成
- 汇编生成
- 后端优化
- ...

