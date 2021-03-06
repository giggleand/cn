## 常见问题
### ELK是什么
ELK=elasticsearch+Logstash+kibana </br>
elasticsearch：后台分布式存储以及全文检索。 </br>
logstash: 日志加工、“搬运工”。</br>
kibana：数据可视化展示。 </br>
ELK架构为数据分布式存储、可视化查询和日志解析创建了一个功能强大的管理链，三者相互配合，取长补短，共同完成分布式大数据处理工作。
### 什么是Lucene
Lucene是一套用于全文检索和搜寻的开源程式库，由Apache软件基金会支持和提供。Lucene提供了一个简单却强大的应用程式接口，能够做全文索引和搜寻。Lucene的目的是为软件开发人员提供一个简单易用的工具包，以方便的在目标系统中实现全文检索的功能，或者是以此为基础建立起完整的全文检索引擎。
### 什么是 Elasticsearch
Elasticsearch 是分布式、可扩展、实时的搜索与数据分析引擎，支持结构化、非结构化文本的多条件检索、统计、报表，建立在全文搜索引擎库 Apache Lucene基础之上，对外提供一套简单的RestfulAPI，支持各类结构化或者非结构化数据存储和查询。拥有完善的监控体系，集成了数据可视化工具 kibana，让用户更专注于业务逻辑的实现。
### 云搜索Elasticsearch适用于哪些业务场景
云搜索Elasticsearch 由于在海量数据检索方面的特性，拥有全文检索、准实时搜索、结构化搜索等能力，广泛应用于日志分析、站内搜索等业务场景。
### 云搜素Elasticsearch支持哪个版本
目前云搜索Elasticsearch搜索引擎支持Elasticsearch 5.6.9版本。
### 云搜索Elasticsearch存储容量的上限是多少
创建集群过程中，最少可创建1个节点，最多可创建25个节点，默认为3个节点。
### 集群有绿色、黄色、红色状态，分别代表什么
其中健康状态是Elasticsearch集群非常重要的监控项，用来表征集群总体上是否工作正常。健康状态种类如下：
* 绿色（green）：在云监控的集群状态中用0表示，表示所有的主分片和副本分片都已分配，集群是100%可用的，此时集群处于最健康的状态。 
* 黄色（yellow）： 在云监控的集群状态中用1表示，表示所有的主分片已经分片了，但至少有一个副本是缺失的，高可用性在某种程度上被弱化，但是数据检索的结果仍然可以正常返回。 
* 红色（red）： 在云监控的集群状态中用2表示，表示至少有一个主分片（以及它的全部副本）都在缺失中，此时查询结果会有确实，集群出现问题。 


