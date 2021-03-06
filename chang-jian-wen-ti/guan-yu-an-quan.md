# 爱客CRM是如何保证数据安全的？

很多客户反应自己最关注的的还是关于SaaS的数据安全问题，并且不约而同的会认为传统软件的本地化部署会比SaaS安全。

首先，用户在使用SaaS软件的过程中商业数据会在浏览器客户端和服务器端传输，如何保证数据传输过程中数据的安全性，成为用户关注的焦点。

其次，SaaS运营商存储数据的服务器有能力抵御互联网黑客的攻击么?这也是众多企业关注的问题。

另外，存放在SaaS运营商的客户数据，如何在没有客户许可的情况下不被其他人窥探也是企业非常担心的问题。

以上三方面问题，是数据安全的软肋，也是众多SaaS运营商面临的共性问题。

#### **全程采用 HTTPS 连接**

所有你和爱客CRM 直接的数据传输，均经由 HTTPS 加密传输，防止在传输过程中经过的各节点对数据进行窃听或篡改。

![](/assets/关于安全01.png)

#### 阿里云服务器

我们将用户在爱客CRM上的数据存储在阿里云的OSS云存储系统中（实时数据灾备，加密存储）；数据库采用阿里云的RDS云数据库（异地主从备份）；主机使用阿里云弹性计算，并且配备专职安全系统运维工程师，保障系统连续可靠安全运行。云服务器数据实时备份和快速恢复，确保数据安全。我们尽量多的使用成熟的云服务，也是想依托这些大型互联网公司成熟的技术经验，为爱客CRM的数据安全保驾护航。

#### 严格的服务器访问权限控制

尽一切可能，降低人的缺陷导致数据被滥用的可能性。我们的所有收入都来自客户的付费，我们相信，只要我们的软件服务好，能让客户心甘情愿的持续付费，就足以支持我们成功。我们对服务器的管理严格执行SOD，不同的人掌握不同权限的帐号，避免一个人完成所有的操作，最大限度降低数据的破坏风险性。

#### 法律保障

对于需要的用户，我们可以提供《数据安全保密协议》的签署，在法律层面多加一层保障。

