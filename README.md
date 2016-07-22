ORM的框架有很多，我现在只用Hibernate和Mybatis。当然这里指的是Java的框架。比较而言现在对Mybatis比较熟悉而且比较重要的是Mybatis有详细简洁的中文说明书，所有决定拿Mybatis来开刀阅读。这里是源码加上我读的注释，慢慢读慢慢更新。

这次Mybatis的版本毫无疑问在3.4.1与3.4.2之间，因为我是从master分支上拉取得代码。

对于百度呢真的很让人失望，搜Mybatis中文文档，每次都找不到文档的地址，跳出来的都是什么鬼？每次都是google解决，但是上一次google很麻烦的。这次就贴上Mybatis中文文档的地址：

http://www.mybatis.org/mybatis-3/zh/

还有项目是在itellij idea中打开所以会有相应的信息。忽略就好。


这里贴一下别人的阅读心得：http://xpenxpen.iteye.com/blog/1508749



MyBatis SQL Mapper Framework for Java
=====================================

[![Build Status](https://travis-ci.org/mybatis/mybatis-3.svg?branch=master)](https://travis-ci.org/mybatis/mybatis-3)
[![Coverage Status](https://coveralls.io/repos/mybatis/mybatis-3/badge.svg?branch=master&service=github)](https://coveralls.io/github/mybatis/mybatis-3?branch=master)
[![Dependency Status](https://www.versioneye.com/user/projects/56199c04a193340f320005d3/badge.svg?style=flat)](https://www.versioneye.com/user/projects/56199c04a193340f320005d3)
[![Maven central](https://maven-badges.herokuapp.com/maven-central/org.mybatis/mybatis/badge.svg)](https://maven-badges.herokuapp.com/maven-central/org.mybatis/mybatis)
[![License](http://img.shields.io/:license-apache-brightgreen.svg)](http://www.apache.org/licenses/LICENSE-2.0.html)
[![Stack Overflow](http://img.shields.io/:stack%20overflow-mybatis-brightgreen.svg)](http://stackoverflow.com/questions/tagged/mybatis)
[![Project Stats](https://www.openhub.net/p/mybatis/widgets/project_thin_badge.gif)](https://www.openhub.net/p/mybatis)

![mybatis](http://mybatis.github.io/images/mybatis-logo.png)

The MyBatis SQL mapper framework makes it easier to use a relational database with object-oriented applications.
MyBatis couples objects with stored procedures or SQL statements using a XML descriptor or annotations.
Simplicity is the biggest advantage of the MyBatis data mapper over object relational mapping tools.

Essentials
----------

* [See the docs](http://mybatis.github.io/mybatis-3)
* [Download Latest](https://github.com/mybatis/mybatis-3/releases)
* [Download Snapshot](https://oss.sonatype.org/content/repositories/snapshots/org/mybatis/mybatis/)
