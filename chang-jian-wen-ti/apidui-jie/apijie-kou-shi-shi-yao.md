# API接口怎么用

使用API接口需有一定的编程能力，爱客CRM提供免费的API对接技术咨询服务，可解答你在对接过程中遇到问题。

#### 接口文档地址

爱客CRM独立版和钉钉版的接口文档地址均为：[http://test.ikcrm.com:8008/api\_doc/](http://test.ikcrm.com:8008/api_doc/)

#### 独立版

先通过登录接口获取user\_token，然后在其他接口中带入user\_token、version\_code和device参数就可以调用其他接口了。

通过登录接口获取user\_token时，需要通过帐号密码获取，version\_code填写3.13.0即可（后续版本的接口是向下兼容的），device填写ios或android。



