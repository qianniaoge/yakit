# Yakit: 集成化单兵安全能力平台

[yaklang && Yakit 项目官方网站](http://www.yaklang.io/)

## Yak和Yakit

Yak作为业内第一门 Web 安全研发的垂直领域语言，提供了非常强大的安全能力，Yak是绝大部分 “数据描述语言 / 容器语言” 的超集，具备如下特性：
1. 执行效率与特性完全继承 Go Native；Go 所有的能力与库生态，Yak 都可以具备
1. 配套 VSCode 插件，提供一定程度的自动补全功能
1. 编译集成 nuclei 生态的漏洞扫描能力
1. Golang 模块原生兼容，所有 Golang 可以实现的功能均可集成在Yak中
…………

![image](https://user-images.githubusercontent.com/94944398/145537524-01f2a9a5-674d-4751-aca3-ffb9b3eaa24a.png)

   但是限于Yak使用形式，用户必须学习 Yak 语言并同时具备对安全的一定理解。为了让 Yak 本身的安全能力更容易被大家接受和使用，我们为Yak编写了gRPC服务器，并使用这个服务器构建了一个客户端：Yakit，通过界面化GUI的形式，降低大家使用Yak的门槛。使用Yakit，使用 Yakit，我们可以做到：
1. 类 Burpsuite 的 MITM 劫持操作台
1. 查看所有劫持到的请求的历史记录以及分析请求的参数
1. 全球第一个可视化的 Web 模糊测试工具：Web Fuzzer
1. Yak Cloud IDE：内置智能提示的 Yak 语言云 IDE
1. ShellReceiver：开启 TCP 服务器接收反弹交互式 Shell 的反连
1. 第三方 Yak 模块：社区主导的第三方 Yak 模块插件，你想要的应有尽有
1. ...

![功能预览](http://www.yaklang.io/assets/images/yakit-poc-loaded-136aa1bd8e078db19aa74b4d8b4f429a.jpg)

## 独一无二的 Yakit 架构

正如我们在上面提到的，Yakit 的核心并不在工具本身上，而是依托于 Yak gRPC 接口； 也就是说，我们可以仅仅只把 Yakit 当作一个 "视窗" 来操纵 Yak 引擎来完成我们想要实现的安全能力。

![架构预览](http://www.yaklang.io/assets/images/arch-bd2e0f27b2ce06d93c7d75a78d59e1c0.jpg)

## 如何下载与使用？

进入官方网站 Yakit 产品页

[Yakit-集成化单兵工具平台 from yaklang.io](http://www.yaklang.io/products/intro/)

## 联系我们

如果对我们的产品有任何建设性意见或 BUG 反馈，欢迎大家提 issue

或通过微信公众号联系我们，也欢迎联系商业授权与合作

进群交流请添加运营小姐姐微信：Juzi19880818

![](https://www.yaklang.io/assets/images/qrcode_for_yaklang-f67bc5fedba90c628080507245f66a34.jpg)
