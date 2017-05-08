# 《Java RESTful Web Serivce实战》读书笔记

## REST概念
1. REST（Representational State Transfer，中文译为：表述性状态转移，全称：Resource Representational State Transfer）是一种架构风格。在这种架构风格中，对象被视为一种资源，通常使用概念清晰的**名词**命名。

2. 资源：

2. 资源表述是指资源可表述性，具体是指资源的内容和资源的格式，格式可以是json、html、xml，也可以是二进制流等等，（具体资源类型可以参考:[rfc规范](http://www.ietf.org/rfc/rfc2616.txt)、[中文版](http://www.blogjava.net/sunchaojin/archive/2009/05/31/279164.html)）。

3. 状态转移：状态转移（state transfer）与状态机中的状态迁移（state transition）的含义是不同的。状态转移说的是：在客户端和服务器端之间转移（transfer）代表资源状态的表述。通过转移和操作资源的表述，来间接实现操作资源的目的。状态机中的状态迁移是指应用的状态，应用的状态是客户端维护的，这里的状态是指服务器资源的状态。

4. 六大特性 TODO
## RESTful API概念
1. RESTful：单词意义上去理解RESTful是REST的形容词，形容接口是符合REST规范的，也就是REST式的API。

2. RESTful Web Service: REST式的Web服务。REST服务是ROA（Resource-Oriented Architecture，面向资源的架构）应用。



## 创建
使用maven执行下面的命令：

    mvn archetype:generate -DarchetypeArtifactId=jersey-quickstart-webapp -DarchetypeGroupId=org.glassfish.jersey.archetypes -DinteractiveMode=false -DgroupId=org.rhine -DartifactId=resful-service-webapp -Dpackage=com.rhine -DarchetypeVersion=2.25.1

## 参考文献
[understanding-restful-style](http://www.infoq.com/cn/articles/understanding-restful-style)

[RESTful架构详解](http://kb.cnblogs.com/page/512047/)

[Java RESTful Web Service实战](http://product.dangdang.com/24008277.html)