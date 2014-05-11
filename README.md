历史上的今天
===========

在百度APP引擎（BAE）上建立的微信订阅号，通过微信客户端获取每天“历史上今天”的大事记，大事记数据来源是wiki百科。


实现
===========

在BAE上建立微信订阅号服务器；
开通微信订阅号，微信服务器会中转客户端和订阅号服务器之间的消息；
订阅号服务器每天从wiki百科页面抓取“历史上的今天”上发生过大事记；
由于大事记的条目过多，根据搜索引擎（googe/baidu）返回结果判断其影响力，并进行筛选；

效果
===========

![](/snapshot.png 'snapshot')


todo
===========

加入多线程加速网页抓取速度；
加入名人影响力判断；
加入聊天机器人；
申请微信认证和推送功能；


参考
===========

http://developer.baidu.com/

https://mp.weixin.qq.com
