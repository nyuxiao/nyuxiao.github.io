---
layout: post
title:  "前端技术研究2-yaml"
date:   2015-09-05 08:19:44
categories: jekyll update
---

YAML主要使用在Jekyll的配置中，怎么用，这个地方先不用考虑，本篇文章主要是学习一下什么是YAML。

YAML: YAML Ain't Markup LanguageWhat It Is: YAML is a human friendly data serialization standard for all programming languages.

参见：http://yaml.org/、http://www.yaml.org/spec/1.2/spec.html

* 定义： “YAML Ain’t Markup Language” (abbreviated YAML) is a data serialization language designed to be human-friendly and work well with modern programming languages for common everyday tasks.
* 原理：There are myriad flavors of data structures, but they can all be adequately represented with three basic primitives: mappings (hashes/dictionaries), sequences (arrays/lists) and scalars (strings/numbers). 
* 跟JSON的比较：
  - JSON’s foremost design goal is simplicity and universality. Thus, JSON is trivial to generate and parse, at the cost of reduced human readability. It also uses a lowest common denominator information model, ensuring any JSON data can be easily processed by every modern programming environment.
  - In contrast, YAML’s foremost design goals are human readability and support for [serializing](http://www.yaml.org/spec/1.2/spec.html#serialize//) arbitrary [native data structures](http://www.yaml.org/spec/1.2/spec.html#native data structure//). Thus, YAML allows for extremely readable files, but is more complex to generate and parse. In addition, YAML ventures beyond the lowest common denominator data types, requiring more complex processing when crossing between different programming environments.
* 跟XML的比较：
  - YAML is primarily a data serialization language. 
  - XML was designed to be backwards compatible with the Standard Generalized Markup Language (SGML), which was designed to support structured documentation.
* 语法
  - 使用三个中划线标识文档的开头，使用三个点标识结尾
YAML uses three dashes (“---”) to separate directives from document content. This also serves to signal the start of a document if no directives are present. Three dots ( “...”) indicate the end of a document without starting a new one, for use in communication channels.
    \---
    time: 20:03:20
    player: Sammy Sosa 
    action: strike (miss)
    ...

简单的总结一下，yaml就是另一种轻量级的标记语言，类似于json，并且yaml规范中认为yaml是json的超集，主要用在一些配置文件中，暂时可以先了解这么多。



