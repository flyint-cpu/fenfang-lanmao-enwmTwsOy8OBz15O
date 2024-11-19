[合集 \- 经验分享(35\)](https://github.com)[1\.记一次由于操作失误致使数据库瘫痪的故障分析与解决方案2023\-09\-08](https://github.com/guoxiaoyu/p/17678340.html)[2\.网络之谜：记一次失败排查的故事2023\-11\-15](https://github.com/guoxiaoyu/p/17811098.html)[3\.你是否想知道如何应对高并发？Go语言为你提供了答案！2023\-12\-29](https://github.com/guoxiaoyu/p/17933653.html)[4\.2023年终总结：拉帮结伙，拼搏探索新机遇2023\-12\-30](https://github.com/guoxiaoyu/p/17933731.html)[5\.谁说后端不能画出美丽的动图？让我来给大家拜个年！01\-29](https://github.com/guoxiaoyu/p/17991503)[6\.【10秒开服】幻兽帕鲁全自动部署教程，难道你还想手动搭建游戏服务器吗？快来学习这个简单又快速的方法！01\-30](https://github.com/guoxiaoyu/p/17998193)[7\.踩坑指南：入门OpenTenBase之部署篇04\-10](https://github.com/guoxiaoyu/p/18116318)[8\.踩坑指南：入门OpenTenBase之监控篇04\-11](https://github.com/guoxiaoyu/p/18117472)[9\.加速博客体验：静态资源优化技巧大揭秘！04\-28](https://github.com/guoxiaoyu/p/18149525)[10\.5分钟带你了解RabbitMQ的（普通/镜像）集群06\-14](https://github.com/guoxiaoyu/p/18240661)[11\.金仓数据库全攻略：简化部署，优化管理的全流程指南06\-21](https://github.com/guoxiaoyu/p/18257320)[12\.KES数据库实践指南：探索KES数据库的事务隔离级别07\-02](https://github.com/guoxiaoyu/p/18276998)[13\.云端IDE如何重定义开发体验07\-24](https://github.com/guoxiaoyu/p/18294897)[14\.国产数据库：数字时代的科技巨擘07\-16](https://github.com/guoxiaoyu/p/18295131)[15\.浅析前端数据埋点监控：用户行为与性能分析的桥梁08\-02](https://github.com/guoxiaoyu/p/18329944)[16\.数据库与我：一段关于学习与成长的深情回顾08\-05](https://github.com/guoxiaoyu/p/18338820)[17\.观存储历史，论数据未来08\-12](https://github.com/guoxiaoyu/p/18352499)[18\.从自建到云原生：数据管理的未来与变革08\-13](https://github.com/guoxiaoyu/p/18354003):[veee加速器](https://liuyunzhuge.com)[19\.深入分析与解决方案：缓存与数据库双写不一致问题08\-20](https://github.com/guoxiaoyu/p/18363049)[20\.小白系列：数据库基础知识解析08\-19](https://github.com/guoxiaoyu/p/18363713)[21\.智能客服的演变：从传统到向量数据库的新时代08\-21](https://github.com/guoxiaoyu/p/18370513)[22\.Cloud Studio：颠覆传统的云端开发与学习解决方案08\-28](https://github.com/guoxiaoyu/p/18382973)[23\.单元测试的入门实践与应用09\-05](https://github.com/guoxiaoyu/p/18395944)[24\.Git冲突解决技巧09\-15](https://github.com/guoxiaoyu/p/18409072)[25\.提升软件测试效率与灵活性：探索Mock测试的重要性09\-22](https://github.com/guoxiaoyu/p/18419378)[26\.从设计到代码：探索高效的前端开发工具与实践09\-28](https://github.com/guoxiaoyu/p/18425801)[27\.掌握Docker：简化KES单机安装与管理的最佳实践10\-01](https://github.com/guoxiaoyu/p/18436754)[28\.AI实战篇：Spring AI \+ 混元 手把手带你实现企业级稳定可部署的AI业务智能体10\-18](https://github.com/guoxiaoyu/p/18453559)[29\.实用小工具——快速获取数据库时间写法10\-19](https://github.com/guoxiaoyu/p/18459987)[30\.从0到1实现项目Docker编排部署10\-22](https://github.com/guoxiaoyu/p/18474742)[31\.新手入门Java自动化测试的利器：Selenium WebDriver11\-10](https://github.com/guoxiaoyu/p/18515369)[32\.程序员如何借势AI提高自己：从高效工作到技能升级的全面指南11\-11](https://github.com/guoxiaoyu/p/18526930)[33\.快速上手 KSQL：轻松与数据库交互的利器11\-14](https://github.com/guoxiaoyu/p/18536656)34\.云开发实践：从 0 到 1 带你玩 AI11\-18[35\.零基础入门Hadoop：IntelliJ IDEA远程连接服务器中Hadoop运行WordCount11\-16](https://github.com/guoxiaoyu/p/18547330)收起
今天我们将深入分析云开发的 AI 能力。这次的讨论焦点不再是之前提到的云端IDE编写代码的能力，而是更为广泛和实际的内容——如何利用云平台提供的各种模块化能力，快速高效地开发。今天的主题依然围绕AI展开，但这并不妨碍我们从平台能力的开通开始，逐步引导你了解 云开发 的 AI 能力。


在这个过程中，我们会以微信订阅号后台为例，来展示整个开发流程。毕竟，微信订阅号作为目前非常流行的应用场景之一，其开发模式和需求具有很高的实用性与代表性，因此将会是我们讲解的主要对象。


# 开通云平台


首先我们需要登录一下腾讯云控制台开通微信云开发后台，地址如下：[https://tcb.cloud.tencent.com/](https://github.com)


进入后直接点击免费试用即可。然后按照自己喜欢的名字新建一个环境。


![image](https://img2024.cnblogs.com/blog/1423484/202411/1423484-20241113162114175-2139457061.png)


目前还在新用户免费一个月的过程中。所以这里不用我们花钱，不过记得如果只是想使用一下，记得关闭自动续费。


![image](https://img2024.cnblogs.com/blog/1423484/202411/1423484-20241113162119745-722347789.png)


# AI 应用快速开发


开通完毕，你就会进入到最新版本的云开发后台。如图所示：


![image](https://img2024.cnblogs.com/blog/1423484/202411/1423484-20241113162125887-243625662.png)


接下来，我将会讲一下云开发上对于 AI 接触比较多的功能，今天我们讲一下低代码开发、AI\+大模型、AI\+智能体开发。好的，我们开始。


## 低代码开发


首先，我们基本都有开发需求，可能我们的业务很小，基本用不上AI \+ 大模型的能力，但是你也可以使用云开发，这里有一个可视化开发的低代码模块。一句话即可创建一个网站。


这里我们只简单说一下因为和微信订阅号没关系，但可能有的人会使用到一键建站的需求。


### 一句文字描述，生成一个网站


界面也很简单，是大模型常用的聊天界面，并没有花里胡哨的按钮。我们直接让他帮我生成一个购物网站


![image](https://img2024.cnblogs.com/blog/1423484/202411/1423484-20241113162132650-256872122.png)


生成的比较慢，我这里演示一下生成效果，还不错的，至少省掉了前期的一些基本操作，画面美化可以后续继续深入调整即可：


![image](https://img2024.cnblogs.com/blog/1423484/202411/1423484-20241113162139331-1084216297.gif)


## AI\+


这里有两个模块，一个是对接基础大模型，另一个对接Agent智能体，不过并没有太多的编排能力，只支持知识库。基本上也够基本使用了，我们看下这两种效果。


### 大模型


这里提供了自家的hunyuan，当然也包括了超多的第三方大模型，如图所示：


![image](https://img2024.cnblogs.com/blog/1423484/202411/1423484-20241113162146143-1478927238.png)


我们继续使用hunyuan演示下。自己请去控制台申请就可以，但是不要申请错了，这次不要申请兼容OpenAI的key：


![image](https://img2024.cnblogs.com/blog/1423484/202411/1423484-20241113162158908-1163434852.png)


![image](https://img2024.cnblogs.com/blog/1423484/202411/1423484-20241113162726328-1023428227.png)


这里并不是针对订阅号后台的，是针对H5和小程序应用的。因为他会暴露出一些简易的SDK供你调用，就不用对接复杂的API接口了。


![image](https://img2024.cnblogs.com/blog/1423484/202411/1423484-20241113162731624-224599520.png)


### Agent智能体


智能体可以快速接入我们的订阅号后台。首先我们新建一个智能体。就拿营销为例子吧。


![image](https://img2024.cnblogs.com/blog/1423484/202411/1423484-20241113162737476-2146382665.png)


如果你有自己的知识库当然更好了，这里也可以进行配置：


![image](https://img2024.cnblogs.com/blog/1423484/202411/1423484-20241113162742711-1836815434.png)


然后配置成自己的微信APPID：


![image](https://img2024.cnblogs.com/blog/1423484/202411/1423484-20241113162749162-440559406.png)


最后直接授权就可以正常使用了


![image](https://img2024.cnblogs.com/blog/1423484/202411/1423484-20241113162755942-172572145.png)


这里不演示了，操作很简单。


## 工作流


这里的工作流有很多作用，我们是个人用户不涉及到支付模块，我们就单独看下对接微信订阅号后台是如何快速开发的。上面的AI Agent 基本已经可以处理订阅号后台回复的能力，但是工作流是可以处理多种业务能力的，有代码能力的小伙伴是可以尝试一下工作流。


### 订阅号消息推送


我们可以看下在云开发平台如何快速对接微信管理后台，而不用想以前那样自己买服务器然后写各种对接代码。


首先我们直接使用现成的模版接口。


![image](https://img2024.cnblogs.com/blog/1423484/202411/1423484-20241113162803284-1953635562.png)


这里配置对了，才可以正常监听消息推送。


![image](https://img2024.cnblogs.com/blog/1423484/202411/1423484-20241113162808417-112518470.png)


这里切记是在云开发后台使用调试URL作为服务器URL，并不是上面的接收推送 URL。


![image](https://img2024.cnblogs.com/blog/1423484/202411/1423484-20241113162813277-1209181129.png)


开始监听即可收到信息，这里注意下，如果你的微信后端接入了其他第三方监听你的消息，这里是正常无法监听到的。所以我重新开了一个测试号进行监听。


![image](https://img2024.cnblogs.com/blog/1423484/202411/1423484-20241113162818225-1062172649.png)


这里js脚本节点写的是如何处理消息。当然如果你有任何其他的开发需求，这里也有很多的api接口文档供你使用查看。比如你可以调用你的任何云函数或者常用的http调用。点击编辑js脚本。


![image](https://img2024.cnblogs.com/blog/1423484/202411/1423484-20241113162823811-568757974.png)


云函数调用示例也都有。


![image](https://img2024.cnblogs.com/blog/1423484/202411/1423484-20241113162829883-2105108258.png)


这些api基本就够用了，当然如果还是不行，那你可以填写申请一下：


![image](https://img2024.cnblogs.com/blog/1423484/202411/1423484-20241113162835069-1111418916.png)


### 嵌入 AI 回答


上面都是围绕着js脚本展开说的，如果你想让你的回复能力嵌入AI怎么办？当然可以添加AI大模型节点了。直接拉过来就好了。


![image](https://img2024.cnblogs.com/blog/1423484/202411/1423484-20241113162840739-429123650.png)


然后我们接着需要配置一下东西。就是js的输出和消息输出的文本格式。我先来介绍下这几个字段都是什么意思，你也好操作一下：


![image](https://img2024.cnblogs.com/blog/1423484/202411/1423484-20241113162845080-1059823005.png)


当然如果你不想要hunyuan，也可以配置其他的模型，自己新建一个即可。


![image](https://img2024.cnblogs.com/blog/1423484/202411/1423484-20241113162849841-1214761227.png)


提示词：你完全可以理解为提问的内容，并不是你所想的人设部分。


消息历史：这里你必须定义一组数组对象，里面可以包括system也就是我们常说的提示词，以及一组消息历史。如下：



```
[
  {
    "role": "user",
    "content": "你好"
  },
  {
    "role": "assistant",
    "content": "请输入你的问题"
  },
  {
    "role": "user",
    "content": "早上好"
  },
  {
    "role": "assistant",
    "content": "您也早上好"
  }
]

```

先将js脚本的输出变成普通文本，不要有特殊格式，否则会影响大模型回答。其他情况可酌情处理，代码如下：


![image](https://img2024.cnblogs.com/blog/1423484/202411/1423484-20241113162857080-29648537.png)


接下来，我们要增加引用变量，也就是用户的普通问题。


![image](https://img2024.cnblogs.com/blog/1423484/202411/1423484-20241113162901873-1143036142.png)


最后编辑一下响应字段，因为我们需要返回固定格式，微信端才会识别到。如图所示：


![image](https://img2024.cnblogs.com/blog/1423484/202411/1423484-20241113162906270-1474890516.png)


最终效果看下：


![image](https://img2024.cnblogs.com/blog/1423484/202411/1423484-20241113162912583-598736472.gif)


这里切记，不要在监听节点那里设置成异步，异步是无法返回数据的。只有同步消息才可以，如图所示：


![image](https://img2024.cnblogs.com/blog/1423484/202411/1423484-20241113162916647-449349212.png)


发布后，直接就可以集成到我们的微信订阅号中，记得将我们微信后台的URL换成这个正式的，不要原来的调试URL：


![image](https://img2024.cnblogs.com/blog/1423484/202411/1423484-20241113162956244-362645933.png)


最后所有服务都是正常的了。


![image](https://img2024.cnblogs.com/blog/1423484/202411/1423484-20241113163006369-663604396.png)


# 疑难解答


如果你真的有解决不了的问题怎么办？放心，这里有专业的7\*24小时的问题解答专人。有问题直接追着问就行。


![image](https://img2024.cnblogs.com/blog/1423484/202411/1423484-20241113162934451-1527238231.png)


再或者你也可以选择提交工单。也照样可以随时处理你专人的问题。


![image](https://img2024.cnblogs.com/blog/1423484/202411/1423484-20241113162939682-690129365.png)


# 总结


总之，云开发平台为开发者提供了一个高效、灵活且易于上手的环境，特别是在与AI技术结合的应用中。通过低代码开发、接入大模型和智能体等功能，开发者可以轻松构建复杂的AI应用，而无需深入编写大量代码。此外，微信订阅号后台的示例展示了如何借助云开发快速实现与平台的集成，简化了流程并提升了开发效率。


随着AI技术的不断发展，云平台的模块化能力为我们提供了更多的可能性，从低代码到高性能的大模型应用，几乎可以满足各种开发需求。无论你是初学者还是有经验的开发者，都能在云平台的帮助下，快速实现想法并投入到实际业务中。


