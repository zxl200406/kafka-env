#kafka-dev
---
kafka相应的节点，必须先在zookeeper上注册

例如：zookeeper.connect=ip1:11000,ip2:11000,ip3:11000/kafka/xltst-sadev  
kafka/xltst-sade节点已经在zk集群上注册了


log.dir也需要修改，主要是方便查看不同topic的数据


