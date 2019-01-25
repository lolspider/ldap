# LDAP

# 产品分类

* IBM的tds
* sunone
* openldap
* 微软的AD
* ... ...

#  词汇
* SASL: Simple Authentication and Security Layer (LDAP v3)  
	        Client and server negotiate a security mechanism ( Kerberos, TLS)  
	        # 加密client和server之间的通信
* DIT: Directory Information Tree


# 访问模式	
* read-only
* read-write


LDAP是基于 TCP/IP 的应用层协议，它不仅提供了数据的组织标准，也提供了数据的访问标准。


一个人（person）必须有通用名（commonName，cn）和姓（surName，sn)信息，同时可以有电话（telephoneNumber）、口令（userPassword）、描述（description）、参阅（seeAlso）等信息。

目前，绝大多数LDAP服务器都支持LDAP v3标准，有些则进一步基于XML的目录访问语言，即Directory Services Markup Language (DSML v2)，以提供基于Web Service的目录服务。


# 基本元素

* Directory 目录，可以是集中式的也可以是分布式的
* DIT 目录信息树，整个目录树的根节点为Root DSA Specific Entry（简称 RootDSE）
* Entry 条目，每一个条目有一个唯一的标识名（Distinguished Name，DN),DN 由RDN和PDN组成，其中RDN指DN中最靠前的一段，剩余部分为PDN，RDN可以由多个值构成
* Attribute 属性，
* AttributeType 属性类型，
* ObjectClass 对象类，

































