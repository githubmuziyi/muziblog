---
title: ElasticSearch
date: 2017-02-17 23:24:29
categories: 搜索引擎
tags: 搜索
---

***简单介绍一下ES***

ElasticSearch是一个基于Lucene的搜索服务器。它提供了一个分布式多用户能力的全文搜索引擎，基于RESTful web接口。Elasticsearch是用Java开发的，并作为Apache许可条款下的开放源码发布，是当前流行的企业级搜索引擎。设计用于云计算中，能够达到实时搜索，稳定，可靠，快速，安装使用方便。
我们建立一个网站或应用程序，并要添加搜索功能，令我们受打击的是：搜索工作是很难的。我们希望我们的搜索解决方案要快，我们希望有一个零配置和一个完全免费的搜索模式，我们希望能够简单地使用JSON通过HTTP的索引数据，我们希望我们的搜索服务器始终可用，我们希望能够一台开始并扩展到数百，我们要实时搜索，我们要简单的多租户，我们希望建立一个云的解决方案。Elasticsearch旨在解决所有这些问题和更多的问题。

                                                           ---百度百科
![alt text](/material/img/ES1.jpeg "ES1")

搜索引擎：

* 搜索组件，利用Lucence进行文档索引，并提供通用的搜索组件，表现为接收客户端的查询请求并返回相应结果。（ElasticSearch）
* 索引组件，提供搜索程序的核心索引及搜索模块，完成检索原始内容，创建文档，索引文档等部分。（Lucence）

***Version***

> elastic官方版([官方版Github][authority])

  elasticsearch官方维护，最新分支（master）支持Elasticsearch5.0
  
  [authority]:  https://github.com/elastic/elasticsearch-php

> elastic民间版([民间版Github][folk])	

  民间版本比较多，这里举例公司正在用的一个版本，该项目由[ruflin][ruflin_blog]创
  建，最新分支（master）也支持Elasticsearch5.0,这里附上ES5.0新特性的一份博客[推酷][es5.0]。
  
  [ruflin_blog]: http://www.ruflin.com/
  
  [folk]: https://github.com/ruflin/Elastica
  
  [es5.0]: http://www.tuicool.com/articles/qYvUfuz
  


