## smart-socket [English](README_EN.md)
smart-socket是一款国产开源的Java AIO框架，追求代码量、性能、稳定性、接口设计各方面都达到极致。如果smart-socket对您有一丝帮助，请Star一下我们的项目并持续关注；如果您对smart-socket并不满意，那请多一些耐心，smart-socket一直在努力变得更好。

**![smart\-socket](//pub.idqqimg.com/wpa/images/group.png)：172299083**

**特色：**
1. 代码量极少，可读性强
2. 上手快，二次开发只需实现两个接口
3. 性能爆表，充分压榨CPU、带宽
4. 资源占用极低，IO线程0感知
5. 自带流控、缓存压缩、流量/消息量监控等黑科技
6. 文档齐全《[smart-socket技术小册](https://smartboot.gitee.io/docs/smart-socket/)》

### Maven
smart-socket发布了两种类型的包供大家选用：

1. aio-core，针对Socket的初级用户提供的开发包，仅提供基本的AIO通讯服务。

	```xml
	<dependency>
	    <groupId>org.smartboot.socket</groupId>
	    <artifactId>aio-core</artifactId>
	    <version>1.3.22</version>
	</dependency>
	```	

2. aio-pro，面向资深用户提供的进阶版，不仅包含了aio-core的所有功能，还提供了TLS/SSL通讯功能，并提供一些用于辅助编解码的工具类。

	```xml
	<dependency>
	    <groupId>org.smartboot.socket</groupId>
	    <artifactId>aio-pro</artifactId>
	    <version>1.3.22</version>
	</dependency>
	```

## 性能测试报告

| 项目 | 结果 |
| --- | --- |
|CPU| i7-4790 3.60Ghz|
|内存| 8G|
|测试代码|服务端：P2PServer，客户端：P2PMultiClient|
|测试时长|大于两分钟（服务端与客户端启动后的第一分钟数据是无效的，因为实际未跑满一分钟）
|时间单位|1分钟|
|数据总流量|7064MB|
|消息大小|33B|
|消息数|224484842|

## 标题党
- [《每秒处理 500W 条消息，人、机为之颤抖》](https://www.oschina.net/news/90988/smart-socket-1-2-0-beta)
- [《再见，Netty！你好，smart-socket!》](https://my.oschina.net/u/2385344/blog/1603648)

## 社区互助
如果您在使用的过程中碰到问题，可以通过下面几个途径寻求帮助，同时我们也鼓励资深用户给新人提供帮助。

1. 加入QQ群：172299083
2. Email：zhengjunweimail@163.com
3. [开源问答](https://www.oschina.net/question/tag/smart-socket)

## 参与贡献
我们非常欢迎您的贡献，您可以通过以下方式和我们一起共建 :smiley:：

- 在您的公司或个人项目中使用 smart-socket。
- 通过 [Issue](https://gitee.com/smartboot/smart-socket/issues) 报告 bug 或进行咨询。
- 提交 [Pull Request](https://gitee.com/smartboot/smart-socket/pulls) 改进 smart-socket 的代码。
- 在开源中国发表smart-socket相关的技术性文章。


## 关于作者
Edit By 三刀  
E-mail:zhengjunweimail@163.com  


Update Date: 2018-07-14