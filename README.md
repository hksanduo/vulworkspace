# vulworkspace

## 背景
在漏洞学习过程中使用大佬提供docker靶场进行漏洞复现和研究，但是构建的靶场不提供源代码，可能涉及商业等因素考虑，这里不做过多分析，对于新人进行漏洞学习研究有些不太友好，本项目主要目的是个人在研究学习过程中对漏洞学习资料进行汇总，包括demo案例，测试工具，漏洞讲解等等，可能做的不完善，敬请谅解。

## 目录
| 序号 | 类型 | 名称 | 描述 | 
| ---- | ---- | ---- | ---- |
| 1 | shiro | CVE-2016-4437 | Apache Shiro 1.2.4及以前版本中，加密的用户信息序列化后存储在名为remember-me的Cookie中。攻击者可以使用Shiro的默认密钥伪造用户Cookie，触发Java反序列化漏洞，进而在目标机器上执行任意命令。|
