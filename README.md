1、集群：三台Centos6.5虚拟机，搭建的ElasticSearch和HBase集群
2、Maven构建的spring工程：
	create.do:创建索引，先后在HBase和ElasticSearch中创建索引
	search.do:搜索
该项目可以达到亿万级索引的秒级甚至毫秒级的搜索速度