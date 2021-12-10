# Yakit和Yak

[yaklang && Yakit 项目官方网站](http://www.yaklang.io/)

ak作为业内第一门 Web 安全研发的垂直领域语言，提供了非常强大的安全能力，Yak是绝大部分 “数据描述语言 / 容器语言” 的超集，特性如下
1、	执行效率与特性完全继承 Go Native；Go 所有的能力与库生态，Yak 都可以具备
2、	配套 VSCode 插件，提供一定程度的自动补全功能
3、	编译集成 nuclei 生态的漏洞扫描能力
4、	Golang 模块原生兼容，所有 Golang 可以实现的功能均可集成在Yak中
...


但是限于Yak使用形式，用户必须学习 Yak 语言并同时具备对安全的一定理解。为了让 Yak 本身的安全能力更容易被大家接受和使用，我们为Yak编写了gRPC服务器，并使用这个服务器构建了一个客户端：Yakit，通过界面化GUI的形式，降低大家使用Yak的门槛。使用Yakit，使用 Yakit，我们可以做到：
1、类 Burpsuite 的 MITM 劫持操作台，查看所有劫持到的请求的历史记录以及分析请求的参数
2、全球第一个可视化的 Web 模糊测试工具：Web Fuzzer
3、Yak Cloud IDE：内置智能提示的 Yak 语言云 IDE
4、ShellReceiver：开启 TCP 服务器接收反弹交互式 Shell 的反连
5、第三方 Yak 模块：社区主导的第三方 Yak 模块插件，你想要的应有尽有
6、原生兼容 nuclei yaml poc/exp无需额外下载 Nuclei 即可享受所有其所有漏洞检测能力
...


## Yakit和Yak愿景

Yakit作为Burpsuite 的年轻中国挑战者，我们的第一个目标是，成为像Burpsuite一样有技术深度的产品，让Burpsuite的盗版用户能有一个更好、更安全的工具去选择和使用。但脚步却不仅仅停在这里，我们的梦想是，成为安全领域的matlab，拥有强大且丰富的算法能力，成为安全领域的基座。
Yak和Yakit想做的从来不是像现在安全工具一样的孤岛，而是通过融合，为大家提供一个拥有强大且完备安全能力的产品。Yak和Yakit从开源到编写包含实战案例的安全研发教程，以及Yakit的个性自主化编辑，都在告诉大家一个理念，我们不单单只是想要为大家提供好用的工具，而是为了全面提升大家的安全能力，真正达到人与产品的共同进步。业内大多产品都强调傻瓜式的一键操作与结果可视化，这也是Yakit和Yak最大的不同，我们强调的是用户在操作中的参与感，在不断地学习中，像升级打怪一样，从小白用户蜕变成专业用户，实现国内安全从业人员的能力提升，形成自有的安全壁垒，这才是我们团队的终极目标。


## 如何下载与使用？

进入官方网站 Yakit 产品页

[Yakit-集成化单兵工具平台 from yaklang.io](http://www.yaklang.io/products/intro/)

## 联系我们

如果对我们的产品有任何建设性意见或 BUG 反馈，欢迎大家提 issue

或通过微信公众号联系我们，也欢迎联系商业授权与合作

![](https://www.yaklang.io/assets/images/qrcode_for_yaklang-f67bc5fedba90c628080507245f66a34.jpg)
