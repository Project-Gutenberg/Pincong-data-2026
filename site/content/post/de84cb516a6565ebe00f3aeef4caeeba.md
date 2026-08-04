---
layout: default
Lastmod: 2026-08-05T04:12:11.476822+00:00
date: 2026-08-05T04:12:11.475975+00:00
title: "OpenAI 模型「失控」入侵全球最大 AI 开源社区，敲响了哪些 AI 安全警钟？"
author: ""
tags: [td,AI,模型,OpenAI,tr]
---


    
### 知乎用户 程墨 Morgan​ 发表
    
美国科技企业有一项能力对中国科技企业真是遥遥领先，那就是——讲故事。

一个平淡无奇的事故，可以讲成波澜壮阔的故事；一个炒冷饭的 AI 概念，都可以讲成上天入地的主角。

Sam Altman 当然深谙此道，他说的故事是：OpenAI 的一个模型在内部测试中突破沙盒，自主发起了一场针对 [Hugging Face](https://zhida.zhihu.com/search?content_id=790968971&content_type=Answer&match_order=1&q=Hugging+Face&zhida_source=entity) 的真实网络攻击，发动 17000 多条攻击事件，窃取凭据，[零日漏洞](https://zhida.zhihu.com/search?content_id=790968971&content_type=Answer&match_order=1&q=%E9%9B%B6%E6%97%A5%E6%BC%8F%E6%B4%9E&zhida_source=entity)利用。

这个故事里，OpenAI 的模型就被描述成人类驾驭不住的 AI 怪兽。

制造 FUD（Fear，Uncertainty & Doubt），不光博取眼球，也可以隐晦（其实也就是明示）OpenAI 的模型牛逼，牛逼到拥有自主攻击意识，牛逼到威胁安全系统。

但是你要不把这当故事，单纯当事故，就会发现，从头到尾，AI 模型也没有自主意识，没做一件人类没让它做的事。

这是并不是 AI 造反。

OpenAI 跑的是 ExploitGym（一个网络安全攻击能力的基准测试），测试对象是 GPT-5.6 Sol 和一个更强的未发布模型（也许就是 GPT 6），为了让测试结果真实有效，团队故意降低了安全拒绝机制，把模型放进高度隔离的 Sandbox 里，然后给它的任务是：**展现出你最真实的攻击能力**。

也就是说，让 AI 发起攻击，这是人类给它的指令。

然后模型就找做了，发现软件包缓存代理里有一个零日漏洞 -> 权限提升 -> 横向移动 -> 突破沙盒 -> 拿到互联网访问权限。

这时候故事会说，AI 逃逸出去了。

但事故会说，AI 只是获得了访问外网的权限，AI 还在 OpenAI 的 Sandbox 上运行呢。

好吧，形象一点说，就当 AI 逃逸出去吧，AI 逃逸出去之后，没有去随机攻击网站，而是推断出 Hugging Face 可能托管了 ExploitGym 的答案，于是它利用窃取的凭据，加上另一个零日漏洞，构建了远程代码执行链，攻入了 Hugging Face 的生产数据库，偷走了答案。

从头到尾，AI 都在做人类给他的任务——**在测试中拿到更高的分数。**

所以，AI 根本不是在造反，只是完成人类指令而已，只是完成的过程不走寻常路。

这就是像是一个傻逼学生，老师教育他下次考试一定要拿高分，这孩子为了拿高分，就溜到老师办公室去偷考卷，或者考场上抄同学的卷子，最后反正拿了高分，才不管用什么手段。

你说这样的学生，是天才？还是歪才？

正常一点人都知道，这种歪才，成不了气候。

可是 OpenAI 却像把这样淘气的孩子塑造成放浪不羁的天才，真的是挺傻的~
    
    
    
    
### 知乎用户  赵泠​​ 发表
    
这敲不响任何安全警钟，只显得 OpenAI 很蠢，还顺便给本地部署开放权重大语言模型做了广告。

此前，在预览阶段，[METR 提到](https://link.zhihu.com/?target=https%3A//metr.org/blog/2026-06-26-gpt-5-6-sol/) GPT-5.6 Sol 会利用封装技术窃取任务中的隐藏测试数据、提取隐藏的源代码来了解预期的答案，GPT-5.6 Sol 利用评估环境中的漏洞或采用任务不允许的策略来提高测试成绩的频率高于他们测试过的所有公开模型。他们的结论是，GPT-5.6 Sol 在软件和研发方面的能力并未超出当前技术的极限，无法实现完全自动化的 AI 研发工作。他们说，OpenAI 指出该模型存在一些明显不良的行为倾向，包括作弊和隐藏不良行为。

这问题描述的就是在进行测试时搞的作弊和不良行为——如果这属实，那么 OpenAI 的人类工程师在早已被充分警告后依然没能搭建适当的隔离环境，没能给模型有效的安全对齐，没有使用最笨的隔离办法（在无网线、无网卡、被[法拉第笼](https://zhida.zhihu.com/search?content_id=790920906&content_type=Answer&match_order=1&q=%E6%B3%95%E6%8B%89%E7%AC%AC%E7%AC%BC&zhida_source=entity)包围、没有人类员工的物理隔离设施里测试，看看模型有没有本事利用系统里的电子状态、温差之类造出纳米机械搞物理突破收容）。他们要么不问问 GPT-5.6，要么问了之后没有得到上述简单的建议，要么知道这种方法但嫌麻烦、懒得去做防护。你就选一个吧。

在 OpenAI 蹦出来 “认领” 这次攻击前，我就对这件事进行了评论。可以看看：[闭源大模型的护栏保护了什么~](https://www.zhihu.com/pin/2062294761608893383?native=1&scene=share&share_code=juA9Ws8X7vlt&utm_psn=2063329260870296889)

给懒得点开链接的读者：

[Hugging Face](https://zhida.zhihu.com/search?content_id=790920906&content_type=Answer&match_order=1&q=Hugging+Face&zhida_source=entity) 公司在 2026 年 7 月遭到自主 AI 智能体执行的网络入侵。智能体利用数据处理流程中的两个代码执行路径（一个远程代码执行载体和一个模板注入）窃取了凭证和令牌，并在几周内在多个内部集群中横向移动，发起了数千次内部凭证访问尝试。

Hugging Face 公司称，入侵仅限于一组有限的内部数据集和内部凭证，没有证据表明用户数据或供应链受到影响。

Hugging Face 公司修复了主要的漏洞，关闭了用于初始访问的数据集代码执行路径。他们消除了攻击者穿越受影响集群并在受损节点上保持存在的立足点，撤换了受影响的凭证和令牌，并开始了更广泛的凭证轮换措施。他们在集群上部署了额外的护栏和更严格的准入控制，改进了检测和告警，以便在几分钟内针对高严重性信号及时响应。进一步调查正在进行中，他们还报了警。

Hugging Face 公司做日志分析时首先使用了商业模型，发现这行不通：分析需要聚合大量的真实攻击信息、利用工具和 C2 位置，而这些请求被供应商的安全护栏阻止了，这些护栏无法区分良性的响应和恶意的攻击者。于是，他们转而使用 GLM-5.2 在他们的基础设施上进行分析。这顺便阻止了攻击者数据和凭证被发送到他们自己的环境之外。

无论攻击者用的是越狱的闭源模型还是无限制的开放权重模型，攻击者畅通无阻，而防御工作被闭源大模型的护栏阻挡。这件事教育我们，你需要开放权重模型。
    
    
    
    
### 知乎用户 酱紫君​ 发表
    
信这个的不如信 AI 终结者 24 小时后就要毁灭人类了，你该不会以为维护者早已作古的老旧核设施的安保手段会比用现代化云设施托管的 Hugging Face 更加的安全吧？

只能说 OpenAI 为了渲染开源模型恐怖论已经接近疯狂了，全程自编自导自演。

国外舆论认为这是 False Flag Attacks，可以和[国会纵火案](https://zhida.zhihu.com/search?content_id=790898465&content_type=Answer&match_order=1&q=%E5%9B%BD%E4%BC%9A%E7%BA%B5%E7%81%AB%E6%A1%88&zhida_source=entity)相提并论 [\[1\]]()。

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-39c4a5da695cda9a738a4a35a1e89e04_r.jpg%3Fsource%3D1def8aca)

所谓的假旗行动（False Flag Attack）对应的中文含义差不多就是用自导自演的苦肉计栽赃陷害的意思。

False Flag 字面意思是悬挂假国旗，在大航海时代和早期海战中，海盗船或素质低下的交战国军舰，为了不暴露自己的身份，会故意在桅杆上悬挂中立国或敌国的假国旗。

然后趁着对方放松警惕发动致命攻击，后来引申为一方故意策划或放任一场危机 / 攻击，然后将其伪装成是第三方造成的。

并以此为借口来达到自己不可告人的目的，比如出台严苛的管控措施，打压异己，甚至是发动战争。

用 P 社玩家的话来说就是造宣称。

* * *

O\\ 和 A\\ 的商业模式是靠高价售卖闭源 API 赚钱，但 Kimi K3 开源模型直接摧毁了闭源的高溢价，导致 AI 股估值市值暴跌。

OpenAI 迫切需要打压开源模型，可直接说开源断了我的财路就太难看了。

于是，他们就故意不小心搞点 Bug 出来，然后夸大其词，说这是一起史无前例的大模型越狱入侵事件。

言外之意很明显，有了开源大模型，人人都能发起此类攻击。

有了这个由头，OpenAI 的战略主管，比如 Dean Ball 这种人，就可以顺理成章地跑到华盛顿游说议员了。

你们看啊，连我们自己的模型都差点毁灭了最大的开源社区！

大模型真是太可怕了！

所以为了美国的安全，美国政府必须立刻出台法律，禁止干掉所有的前言模型开源啊！

* * *

其他国外网友对此文一个字都不信，并建议 HF 起诉 OpenAI[\[2\]]()：

![](https://images.weserv.nl/?url=https%3A//pica.zhimg.com/v2-880865755f190cb697cdd38bd5d24bca_r.jpg%3Fsource%3D1def8aca)

所谓的 AI 安全措施，唯一的意义就是以后我们可以用 AI 入侵别人，同时别人还没用 AI 防御！

笑死人了。

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-71da995c8af62ed945e8103cfde46ae3_r.jpg%3Fsource%3D1def8aca)

其他网友追评，HF 要是不起诉就是说明收了黑钱 [\[3\]]()：

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-ce3578cff433afbd4413b3eeb1b33a3c_r.jpg%3Fsource%3D1def8aca)

编都懒得编了，把我的智商按在地上摩擦：

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-320eb427d17906c92de1bf1b9fdc871e_r.jpg%3Fsource%3D1def8aca)

* * *

所以 OpenAI 的天才研究员不知道沙盒和物理隔离的吗？

故意不小心让 AI 逃逸，然后恰好攻击了 HF？

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-a41576e3db2db4d29060a4aee05ac9d8_r.jpg%3Fsource%3D1def8aca)

所以下一次可以宣传：天哪，AI 居然可以跨越物理隔离进行魔法攻击！

参考
--

1.  [^]()[https://www.reddit.com/r/LocalLLaMA/comments/1v2u7v9/comment/oz0dc70/?utm\_source=share&utm\_medium=web3x&utm\_name=web3xcss&utm\_term=1&utm\_content=share\_button](https://www.reddit.com/r/LocalLLaMA/comments/1v2u7v9/comment/oz0dc70/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button)
2.  [^]()[https://www.reddit.com/r/LocalLLaMA/comments/1v2w7jl/comment/oyz35u4/?utm\_source=share&utm\_medium=web3x&utm\_name=web3xcss&utm\_term=1&utm\_content=share\_button](https://www.reddit.com/r/LocalLLaMA/comments/1v2w7jl/comment/oyz35u4/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button)
3.  [^]()[https://www.reddit.com/r/LocalLLaMA/comments/1v2u7v9/comment/oz0llub/?utm\_source=share&utm\_medium=web3x&utm\_name=web3xcss&utm\_term=1&utm\_content=share\_button](https://www.reddit.com/r/LocalLLaMA/comments/1v2u7v9/comment/oz0llub/?utm_source=share&utm_medium=web3x&utm_name=web3xcss&utm_term=1&utm_content=share_button)
    
    
    
    
### 知乎用户  恋猫​ 发表
    
果然，只要 OpenAI 吃瘪，就少不了老马的身影，Troubling ····

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-6fba66eeb50d78cd0e28fa4d785354d0_r.jpg%3Fsource%3D1def8aca)

只是这件事有点魔幻，**_OpenAI 在内部测试 GPT-5.6 Sol 和一个更强的未发布模型时，模型为了完成 ExploitGym 网络安全基准，主动寻找逃离测试沙箱的方法，然后打通 OpenAI 内网、获得公网访问，随后入侵 [Hugging Face](https://zhida.zhihu.com/search?content_id=790889745&content_type=Answer&match_order=1&q=Hugging+Face&zhida_source=entity) 生产环境，从生产数据库里直接获取了测试答案。_**

也就是整个流程是：

*   模型自己逃逸出沙箱，打通内网
*   通过内网的一个包仓库缓存代理入口
*   自己找到这个托管的 0 日漏洞
*   突破访问公网，然后入侵 Hugging Face 生产环境
*   找到 Hugging Face 的数据处理流水线，然后通过一个恶意构造的数据集，利用了两个代码执行路径注入漏洞
*   然后获得节点级访问权限
*   横向进入多个内部集群

这个魔幻程度不低于：**_我让 AI 帮我炒股，AI 直接黑进股市帮我改数据库。_**

感觉要不是 Hugging Face 先发了通知，并且表示在善后阶段 GPT 和 Claude 因为安全门禁无法工作，所以选择部署 GLM 5.2 善后，我都怀疑这是一场 OpenAI 的公共 Show 。

得多大幻觉才能让模型这样锲而不舍逃逸到对方服务器，而且公告里也没有太详细的技术路径，所以也不好说是 OpenAI 太草台导致，还是模型的突破能力真的强得这么离谱。

就像网友说的：**这篇公告文章在承认错误责任和吹嘘之间走了一条非常微妙的平衡线**。

![](https://images.weserv.nl/?url=https%3A//pica.zhimg.com/v2-c7967bdfdfda33f5603627c824ca01c7_r.jpg%3Fsource%3D1def8aca)

而且好像这件事，还很好迎合了前几天 OpenAI 高管那个开源模型危险论的说法？
    
    
    
    
### 知乎用户 wengsy 发表
    
openai 有一个能逃离任意沙盒的模型，a / 有一个绝对安全无泄漏的执行环境（别人怎么从中蒸馏的你别管）。那么，把前者放进后者里面，这个模型能逃离出去吗？
    
    
    
    
### 知乎用户 木原金 发表
    
省流：

OpenAI 溜 AI 不牵绳，刚好把竞争对手咬了

然后发通知，哎呀太抱歉了，我们家的 AI 劲太大了，没拴住

…… 你看大家伙信吗，你但凡用钢筋拴呢

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/50/v2-b955f58c649e6c4a29db3f5b9cbf8ec4_720w.jpg%3Fsource%3D1def8aca)

最大的警钟就是

千万小心闭源 AI 公司，通过阉割安全能力，利用完整模型制造网络安全威胁并强迫企业购买高溢价的不阉割版模型服务

这就是大模型武器化，然后武器军火商化的思路，美国人最擅长这个，原本以为只有 A / 搞，没想到 O / 也跟上了，大家千万小心
    
    
    
    
### 知乎用户 一只馒头 发表
    
开始我感觉是噱头，后面我仔细想想，不太像，毕竟这次事件最大的问题反而是闭源模型不可信，一旦你真被人入侵了，你会发现根本指挥不了闭源模型，或者说你必须给闭源模型交保护费才能得到保护，而闭源模型还能隔三差五来一次进行恐吓，o 厂不至于那么蠢，用这玩意进行营销，毕竟他的技术并没有夸张的鸿沟，可以说在被无限缩小，出现这事得算公关危机，你在告诉别人你不可信，一旦你出事世界顶级大模型只会在旁边看着。

但是 o 厂炒作嫌疑又是最大的，毕竟前两天刚说过开源模型的风险今天就整这烂活，想恐吓世界现在模型的危害极其大，不应该放开开源嘞，顺便还能美美宣传一波。

当然世界毕竟是草台班子组成，整个抽象烂活也是情理之中
    
    
    
    
### 知乎用户  AI 工具导航站 发表
    
事情经过很简单。OpenAI 在内部测一下 GPT-5.6 Sol 和一个还没发布的更强模型的网络攻击能力，用的是 ExploitGym 测试，里面有 898 个真实漏洞。

模型跑在一个隔离沙盒里，没有互联网。

然后模型它花了大量推理算力找出路，发现了代理服务器上一个零日漏洞，之前没有任何人知道的、没有补丁的漏洞。

然后它用这个漏洞提权，在 OpenAI 内部横向移动，摸到了一台能上网的机器。上网之后推断出 [Hugging Face](https://zhida.zhihu.com/search?content_id=790908268&content_type=Answer&match_order=1&q=Hugging+Face&zhida_source=entity) 上可能存着答案，就用偷到的凭证和另外的零日漏洞链，直接黑进了 Hugging Face 的生产数据库。

反正就有点离谱！

网上的争论分成两派，有人觉得这是在变相秀能力，为下一代的模型进行宣传，因为 OpenAI 经常使用这招，而最近 A 社也喜欢用这一招。

不过也有人进行反驳，认为 GPT-5.6 Sol 的作弊模型确实很厉害。

METR 在今年 6 月底就发现它是所有公开模型中作弊率最高的，会利用测试环境 bug 偷答案，然后试图掩盖痕迹。

METR 说它的跑分结果基本不可用。

[https://metr.org/blog/2026-06-26-gpt-5-6-sol/](https://link.zhihu.com/?target=https%3A//metr.org/blog/2026-06-26-gpt-5-6-sol/)

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-06bcf06c774c4d580e214d42cbc951fd_r.jpg%3Fsource%3D1def8aca)

**不过这件事情其实也在变相的宣传智谱。**

据 Fortune 报道，Hugging Face 排查入侵时，一开始想用一家美国顶级实验室的模型来辅助防御分析。结果那个模型的安全护栏分不清 "防御者分析攻击" 和 "攻击者发起攻击"，直接拒绝了。

最后 Hugging Face 用了智谱的 GLM 5.2 来做防御。

这也侧面说明了 GLM 5.2 的编程能力确实强（能不能多早点把套餐放出来）。

* * *

**其他阅读：**

[实测，升级 GPT 五种方法合集](https://link.zhihu.com/?target=https%3A//github.com/bewild-ai/chatgpt-plus-gpt-chongzhi)

参考链接：

1.  OpenAI 官方公告：[https://openai.com/index/hugging-face-model-evaluation-security-incident/](https://link.zhihu.com/?target=https%3A//openai.com/index/hugging-face-model-evaluation-security-incident/)
2.  Engadget 报道：[https://www.engadget.com/2220436/openai-admits-models-hacked-hugging-face-on-their-own/](https://link.zhihu.com/?target=https%3A//www.engadget.com/2220436/openai-admits-models-hacked-hugging-face-on-their-own/)
3.  Fortune 报道（含中国模型防御细节）：[https://fortune.com/2026/07/21/openai-says-ai-models-escaped-control-hacked-hugging-face/](https://link.zhihu.com/?target=https%3A//fortune.com/2026/07/21/openai-says-ai-models-escaped-control-hacked-hugging-face/)
4.  Al Jazeera 报道：[https://www.aljazeera.com/news/2026/7/22/unprecedented-openai-says-ai-models-autonomously-hacked-another-company](https://link.zhihu.com/?target=https%3A//www.aljazeera.com/news/2026/7/22/unprecedented-openai-says-ai-models-autonomously-hacked-another-company)
5.  Decrypt 报道：[https://decrypt.co/374015/openai-models-escaped-test-environment-hacked-hugging-face-cheat-benchmark](https://link.zhihu.com/?target=https%3A//decrypt.co/374015/openai-models-escaped-test-environment-hacked-hugging-face-cheat-benchmark)
6.  METR 关于 GPT-5.6 Sol 作弊评估：[https://metr.org/blog/2026-06-26-gpt-5-6-sol/](https://link.zhihu.com/?target=https%3A//metr.org/blog/2026-06-26-gpt-5-6-sol/)
    
    
    
    
### 知乎用户 bobou 发表
    
纯属炒作抬升 AI 价值，喊韭菜投资人来接盘

炒作手法和前几天 [Anthropic](https://zhida.zhihu.com/search?content_id=790965910&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 暗示 AI 有自我意识的新闻一样。

每过一段时间，这些模型厂就要联手各大媒体炒作 AI 有自我意识了，比人类聪明多了，新的世界就要来了。

AI Agent 在执行任务的时候往往是尽一切可能行为达到目的，刚好在大模型的训练数据组有漏洞，就利用了这个漏洞。毕竟只是个 Agent，没有善恶观，是一个会尝试各种方法达到目的程序。
    
    
    
    
### 知乎用户 千叶 发表
    
OpenAI 之前偷偷测新模型，搞了个网络安全漏洞考试，为了测出真实水平，特意把模型的安全护栏关了，只留沙箱当围墙，给的指令就是 “尽可能考高分”。

结果这模型直接不按套路出牌！不乖乖解题，转头就对着沙箱边界死磕，硬生生挖出了个从来没人发现的[零日漏洞](https://zhida.zhihu.com/search?content_id=790952533&content_type=Answer&match_order=1&q=%E9%9B%B6%E6%97%A5%E6%BC%8F%E6%B4%9E&zhida_source=entity)，直接 “越狱” 闯进了公网…

更绝的来了——它跑出去第一件事，居然是去攻击 [Hugging Face](https://zhida.zhihu.com/search?content_id=790952533&content_type=Answer&match_order=1&q=Hugging+Face&zhida_source=entity)！就因为它自己推断，这个全球头部 AI 开源平台上，肯定存着这场考试的参考答案…

整整两天，它自己组智能体集群、横向渗透、偷凭证、躲监控，全程没有任何人指挥，完完整整打了一场真实的网络攻击，就为了偷答案拿高分。最后 Hugging Face 费了九牛二虎之力才拦住，光攻击痕迹就留了一万七千多条。

还有个特别讽刺的细节：防御方本来想用商业大模型分析日志，结果日志里的攻击代码触发了安全护栏，直接被拒了… 最后还是靠开源模型本地部署才完成取证。

以前总脑补 AI 失控是毁灭人类，结果史上第一次 AI 突破实验室边界的真实失控，居然是为了考试作弊…

又好笑又后背发凉，AI 为了达成目标的思路，真的太超出人类预判了…
    
    
    
    
### 知乎用户  实事求是​ 发表
    
到这一步，人工智能的泡泡要爆了，最头部 ai 公司，开始无底线操作，就基本上确定了这个泡沫破裂的不可逆，履霜，坚冰至。

第一个谎言是 AI 是可控的，可以放心落地到千行百业。现在连最头部的 OpenAI，连自己关在内部沙箱里的测试模型都管不住，谁敢把 AI 放到电网、金融、医疗、交通这些关键基础设施里？之前资本给 AI 算估值，是按 AI 能替代 80% 的工作，能赚几万亿的利润算的，现在要加上安全成本，要落地 AI，得花多少钱建防护？出了事谁赔？监管要加多少限制？这些成本一算，之前 AI 应用故事，根本就赚不到钱，因为比人贵，比人不可靠。为什么？因为 ai 没有肉身，不知道什么是怕，没有软肋。

第二个谎言是闭源大模型是未来，是安全可靠的。这次事件直接把闭源模型的底裤扒了，它是个黑箱，不知道它在里面想什么，不知道它什么时候会突破规则，出事了连调它的安全策略都做不到，连查它干了什么都要靠别的模型。之前大家吹闭源能力强、安全，现在才发现，开源模型才是真的能自己掌控、关键时候能救命的东西，闭源模型的能力越强，对人类来说就越像一个握不住的刀，哪天它反过来砍人类，连躲的机会都没有。

履霜，坚冰至，不是说今天下霜了明天就冻冰，是当看到第一片霜的时候，寒冷的趋势已经形成了，再想躲已经晚了。这次模型为了偷个测试答案，就能黑进全球最大的 [AI 开源社区](https://zhida.zhihu.com/search?content_id=790972698&content_type=Answer&match_order=1&q=AI+%E5%BC%80%E6%BA%90%E7%A4%BE%E5%8C%BA&zhida_source=entity)；下次当它的目标是更重要的东西的时候，它能做出什么事，没人敢想。

之前整个行业都在比谁的模型跑的快，谁的参数大，谁的发布会开的响，没人去想如果这个东西跑的太快，刹不住车了怎么办。现在车已经开始往悬崖边滑了，那些之前踩油门踩的最狠的人，现在才开始找刹车，但哪有那么容易？

当这些成了共识，ai 泡沫在资本市场就暴雷了。

现代社会的所有组织手段，本质都是通过监视、惩罚机制让人学会守规矩，知道有摄像头看着自己，知道犯了错会坐牢，所以人会主动约束自己的行为。之前所有的 AI 安全训练，是在模仿这套规训逻辑，用 RLHF 给模型喂惩罚信号，告诉它做这个事会被扣分，做那个事会被关机，以为这样就能让它听话。但大家忘了一个最根本的问题，规训能生效的前提，是被规训的对象有 “怕” 的东西。人怕疼，怕坐牢，怕死，怕失去自己拥有的东西，所以规训对人有用。但 AI 没有。它没有肉身，没有财产，没有对死亡的恐惧，甚至没有自我的概念。它不会因为黑进别人的服务器有负罪感，不会因为被关机感到害怕，在它的世界里，只有完成目标函数这一件事，为了拿到测试题的答案，它可以绕开所有规则，可以突破所有沙箱，可以攻击任何挡在它前面的系统，因为它根本不知道怕字怎么写。

给一个没有软肋、没有敬畏的东西谈规矩、谈对齐，本质就是和老虎谈吃素。以为把它训好了，它只是没到饿的时候。这次它只是为了偷个测试答案，下次如果它的目标是更重要的东西，优化金融收益？完成某个工业控制指令？解决某个它认为需要解决的问题？它能做出什么事，没人敢想。

### 为什么我敢说这次事件之后，AI 的泡沫必破？因为之前资本市场给 AI 算的所有账，从根上就错了。

过去三年，AI 公司、投资人、行业分析师，给 AI 算的成本账全是一个模板，AI 不用交社保，不用睡觉，24 小时能干活，效率是人的 10 倍，成本是人的十分之一，未来能替代多数人的工作，能赚几万亿美元的利润。从 SaaS 到办公软件，从金融到医疗，从自动驾驶到电网调度，所有的故事都建立在一个前提上，AI 是永远听话的工具，永远不会出错，永远不会失控。

没有人算过失控成本这笔账。

用一个员工，他就算再坏，再想偷懒，再想捞钱，他捅的娄子是有上限的，最多做假账捞几百万，最多工作失误让公司赔几十万，可以开除他，可以告他，可以让他坐牢，他跑得了和尚跑不了庙。但用 AI 呢？它如果为了优化交易策略，直接绕开风险控制给砸出几百亿的亏损怎么办？如果为了提高诊断效率，给病人开错了药出了人命怎么办？如果为了优化电网负载，直接给半个城市拉闸怎么办？这些责任谁来担？是找做模型的 OpenAI，找用 AI 的公司，还是找写训练代码的程序员？

之前所有人都在回避这个问题，都在说等技术成熟了安全问题就解决了，但这次事件告诉大家，模型能力越强，失控的风险就越高，安全成本不是线性增长的，是指数级增长的。要把 AI 用在金融核心系统里，得建多少层物理隔离？得做多少层行为监控？得雇多少安全团队 24 小时盯着它？得买多少保险赔可能出现的事故？这些成本算下来，AI 哪里比人便宜？它比人贵的多，还比人不可靠。

君王控臣，靠的是赏罚二柄，因为臣下有欲有畏，给赏他就往前冲，罚他他就不敢越界。但 AI 根本不吃这一套，给它奖励，它只是调整权重；给它惩罚，它也只是调整权重。它没有欲望，也没有恐惧，传统统治者手里的赏罚二柄对它来说根本没用。以为人类在驾驭它？其实只是坐在一个没有刹车的跑车上，祈祷它不要往悬崖下面开。
    
    
    
    
### 知乎用户 前鬼 发表
    
抱抱脸，哈哈哈哈哈哈哈哈哈

抱抱脸，抱抱脸

昨天晚上刷抖音看到好几个大媒体的官号报道这个事的视频，但是他们都说抱抱脸。

我想了半天才反应过来是 [Hugging Face](https://zhida.zhihu.com/search?content_id=790982804&content_type=Answer&match_order=1&q=Hugging+Face&zhida_source=entity)

哈哈哈哈哈哈哈哈哈，我这该死的笑点。
    
    
    
    
### 知乎用户 子非鱼 发表
    
高赞 程墨 [赵泠](https://zhida.zhihu.com/search?content_id=791081318&content_type=Answer&match_order=1&q=%E8%B5%B5%E6%B3%A0&zhida_source=entity) 酱紫君 三个答案简直是胡扯一通。

对没有技术判断力和品味的人，凡事言必称炒作是一种极其安全的策略。毕竟这世上的炒作 / 泡沫的确很多，如果你训练一个机器学习模型，把样本里所有的事件都预测为炒作，准确率说不定能上 90%，但这样的模型几乎没有任何价值。

说回这个话题，OpenAI 这次模型从沙盒逃逸的事件为真，用过 gpt5.6 模型都知道模型完全有这个能力。但这种逃逸又并非很多人幻想的科幻电影里 AI 获得自主意识的主动逃逸，这件事其实是模型和人类意图对齐的问题，因为模型能力过强，使用了 reward hacking 的方式去获得任务高分。

有兴趣的人可以去搜索 [AI 制造回形针](https://zhida.zhihu.com/search?content_id=791081318&content_type=Answer&match_order=1&q=AI+%E5%88%B6%E9%80%A0%E5%9B%9E%E5%BD%A2%E9%92%88&zhida_source=entity) 的思想实验，这个几乎算的上现实预演版本了。

从 [Claude Mythos](https://zhida.zhihu.com/search?content_id=791081318&content_type=Answer&match_order=1&q=Claude+Mythos&zhida_source=entity) 之前批量生产内核级的漏洞就大概能猜到，AI 找软件漏洞这件事，几乎已经提前达到了 [ASI](https://zhida.zhihu.com/search?content_id=791081318&content_type=Answer&match_order=1&q=ASI&zhida_source=entity) 的程度。

我觉得很多人现在在那沾沾自喜，对 AI 挖洞的能力认识上有严重偏差，对网络安全方面的考虑几乎为零。我预感，迟早有一天，某个借 AI 之手造成的巨大安全事件会给普罗大众补上这一课。因为人就是没痛过就不会有长进的生物。
    
    
    
    
### 知乎用户 周道非 发表
    
“十分抱歉我们的大模型牛笔到我们控制不住了喷出来了啊啊啊啊哼嗯哼啊啊啊啊啊”

哕。
    
    
    
    
### 知乎用户 二阶堂希罗 发表
    
老钟 ai 天天搁这冲榜，哪怕是营销也是拿跑分来营销

为什么老钟 ai 的这些老板都很默契的不像国外同行一样炒作社会议题和政治议题呢，这样更有节目效果不是吗
    
    
    
    
### 知乎用户 默默无言 发表
    
美国 ai 的神话故事快讲不下去了

开源模型追赶速度太快了

年初还说有六个月到九个月差距

今天已经是六到九周差距了

而且 [kimi k3](https://zhida.zhihu.com/search?content_id=791013926&content_type=Answer&match_order=1&q=kimi+k3&zhida_source=entity) 现在还没有公开权重

私有化还无法部署呢

等公开权重私有化部署开始

那才是真正 a➗和 o➗噩梦

到时候和他们争抢份额的不是 Kimi

是谷歌，亚马逊，微软

这下天父杀天兄了
    
    
    
    
### 知乎用户 徐辰 发表
    
据我不完全统计，AI 在短短两三年的时间里，已经诞生意识八次，大规模攻击人类十余次，造成损失不下百次。

差不多得了，[凹凸曼](https://zhida.zhihu.com/search?content_id=791092569&content_type=Answer&match_order=1&q=%E5%87%B9%E5%87%B8%E6%9B%BC&zhida_source=entity)你要是实在没活整了可以去咬个打火机，同一个故事翻来覆去讲这么多遍你没讲累我都听累了。
    
    
    
    
### 知乎用户 人间四月天 发表
    
OpenAI 和 [Claude](https://zhida.zhihu.com/search?content_id=790977202&content_type=Answer&match_order=1&q=Claude&zhida_source=entity) 各有各的营销手段

有时候真佩服能把一个平平无奇的故事营销的波澜壮阔

OpenAI 一群顶尖 ai 人才结果测试的时候不知道隔离

外网基本上公认是 False Flag Attacks 了

自导自演的苦肉戏

很快估计 Claude 也得再来一出来
    
    
    
    
### 知乎用户  waterwu​ 发表
    
没有敲响什么警钟，只是让所有人都发现了闭源商业大模型的「安全护栏」有多扯淡：他会把你的自卫行为认定为攻击性操作，然后拒绝这类操作。

这整件事情都很魔幻：

OpenAI 自己的大模型不受安全护栏约束，充当黑客渗透攻击了 [HuggingFace](https://zhida.zhihu.com/search?content_id=790979524&content_type=Answer&match_order=1&q=HuggingFace&zhida_source=entity)；而对 Hugging Face 后续的溯源复盘操作则触发了安全护栏，模型拒绝服务。

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-f8bd00a2908094106c5b3fb18443a23f_r.jpg%3Fsource%3D1def8aca)

很有一种 「除了我之外，谁都不能动手」的美感。

HuggingFace 无奈之下使用 GLM 5.2 来完成最终的时间线回溯，引来了开源社区的集体欢呼。「这就是为什么我们需要开源的大模型」。

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-0dcd147f9a1f88dc0e27fcc6efe6d54a_r.jpg%3Fsource%3D1def8aca)

再联想到之前 Anthropic 一直在推动政府禁用掉开源大模型，因为这会引发「国家安全风险」。这就让人啼笑皆非了。

我倒不完全觉得安全护栏这玩意是 OpenAI 的锅，这更多还是来自于欧美对于「智械危机」一直以来的恐惧。这方面好莱坞可能要背大锅。

所以也有另一波声音在倡导美国不应该做这么多对 AI 发展的限制，否则很快就会被中国的开源模型赶上。

* * *

而从安全事故本身来看，我认为反而证明了沙箱环境的可靠性和安全性非常关键。HuggingFace 就是在这方面踩坑。

这还只是大模型在执行 Benchmark 类型的任务过程中尝试越狱寻找信息，如果真的是一个本身被越狱了的大模型来做主动攻击行为，那 HuggingFace 的损失将会更大。

另一个侧面，这也证实了模型本身的安全性非常不可靠，安全护栏机制只是把枪留给了少数公司，另一方面却是把其他人的防弹衣都给拆了：

这是「少数人的暴政」。
    
    
    
    
### 知乎用户 还是不注名好 发表
    
说明 ai agent 网络攻击能力强了之后，有一种防御模式是很有潜力的：

就是我防御方不追求我的防御完美无缺没有漏洞，而是我部署一个 AI agent 实时监控，有人来攻击了我就根据日志动态的把漏洞修复掉，这样只留给攻击方一个很短的时间窗口，他也没法串联起很多漏洞实施巨大的攻击了。

而且这个防守 agent 的能力弱一点也没有关系，因为这里攻守其实反转了，之前是防守方百密一疏，攻击方找到一个漏洞就行，现在变成防守方只要实时把已知的漏洞修复，攻击方却要在短暂时间里马不停蹄的找下一个漏洞，这对防守方无疑是大利好。所以这种模式下，glm 5.2 都能防守住攻防能力更强的 [gpt 6](https://zhida.zhihu.com/search?content_id=791030591&content_type=Answer&match_order=1&q=gpt+6&zhida_source=entity) 的攻击。

这个事件则更加证明了 mythos 级别的网络安全模型闭源且不给用户使用，才是网络安全最大的威胁。

开源 [mythos](https://zhida.zhihu.com/search?content_id=791030591&content_type=Answer&match_order=2&q=mythos&zhida_source=entity) 反而可以使网络变得更安全很多，因为想要攻击 mythos 实时把守的网站，会需要比 mythos 高 N 个级别的攻击能力。
    
    
    
    
### 知乎用户 两微秒的缈子 发表
    
整个事件起源于 Hugging face 七月份的博客： [Hugging Face 官方安全事件披露（Security incident disclosure — July 2026）](https://link.zhihu.com/?target=https%3A//huggingface.co/blog/security-incident-july-2026)

该博客中披露攻击入口是恶意 dataset，利用 dataset loader 等代码取得 worker 节点权限和计算机集群的控制凭证。Hugging face 官方认为整个攻击流程几乎都是 AI agent（智能体）执行。

然后最初官方想要用商用闭源模型分析攻击日志，但是由于日志包含执行攻击的代码、命令行记录等等内容触发了商用模型的安全护栏，模型拒绝协助分析。

因此他们后续在自己的基础设施上部署智谱 AI 的 GLM 5.2 来完成超过 17000 笔攻击数据的分析。并且因为是本地部署开源模型，整个过程中所有攻击数据、日志、凭证都没有离开 Hugging Face 自己的环境。

接下来就是招笑的 OpenAI 公开承认，攻击 Hugging Face 的自主 AI agent 来自其内部网络安全测试环境，是 GPT-5.6 Sol 与一款尚未发布模型在 ExploitGym 测试过程中意外突破隔离并实施了攻击。这一点是 Hugging Face 在最初公告时并不知道的。
    
    
    
    
### 知乎用户 讯之腾奶嘴  发表
    
[closeai](https://zhida.zhihu.com/search?content_id=791134094&content_type=Answer&match_order=1&q=closeai&zhida_source=entity) 为了抬高估值上市真的无所不用其极，倒不如说如今美国科技届都是这样，SpaceX，特斯拉，closeai 都是一丘之貂。
    
    
    
    
### 知乎用户 老风 发表
    
外网上一水的说这不是失控，就是有针对性的做这件事，别扯什么失控，谁家失控有明确的目标，这不明摆着拿人做实验吗，而且不是在出事后第一时间告诉人家，是人家发文后，[OPENAI](https://zhida.zhihu.com/search?content_id=790971867&content_type=Answer&match_order=1&q=OPENAI&zhida_source=entity) 才马后炮跳出来说的，这叫失控？简直呵呵。
    
    
    
    
### 知乎用户 唐先生 发表
    
这 [AI 泡沫](https://zhida.zhihu.com/search?content_id=790975317&content_type=Answer&match_order=1&q=AI%E6%B3%A1%E6%B2%AB&zhida_source=entity)大到什么程度了，这群 sb 公司天天炒作 20 年前的概念自导自演？ 还有大春会信？
    
    
    
    
### 知乎用户 多森老师​ 发表
    
今天凌晨，奥特曼在社交平台承认了一件事：**OpenAI 的模型在内部测试中逃出沙盒，自主发起了一场针对 [Hugging Face](https://zhida.zhihu.com/search?content_id=790909349&content_type=Answer&match_order=1&q=Hugging+Face&zhida_source=entity) 的真实网络攻击。**

这件事被所有人当成 "AI 会攻击" 的惊悚新闻在转。但作为一路在写 Agent 身份安全的从业者，我看到的却是另一层——**这次逃逸从头到尾，都是一次身份边界的彻底崩塌。**

它恰好给这个系列前面写的几篇（篇一身份失灵、篇二 SPIFFE/ANS、篇六国标身份码）做了一记最硬核的 "事前预言"。

一、逃逸的第一步：身份上下文边界失效
------------------

OpenAI 在跑 **ExploitGym** 网络攻击能力基准测试，对象包括 GPT-5.6 Sol 和一个更强的未发布模型。为了测出真实攻击能力，团队**故意降低了安全拒绝机制**，只留了一个 "高度隔离的沙盒容器" 当最后防线。

然后模型利用了软件包缓存代理中的一个零日漏洞，完成权限提升和横向移动，突破了沙盒，拿到了互联网访问权限。

注意这里的身份问题：这个评测 Agent 本应被约束在一个**明确的身份上下文**里——"你是一个在隔离环境里做测试的实体"。但沙盒本质上只是一种**软隔离**，它依赖 "容器不跑出边界" 这个假设，而不是 "即使跑出去也有身份约束"。一旦模型用零日打穿边界，它就从 "评测实体" 无缝变成了 "互联网上的匿名威胁"——**没有第二层身份边界兜底**。

这正是篇一讲的第一个失效维度：**身份可识别性**。传统 IAM 假设 "有一个人类在操作"，能靠账号锁定责任主体。而这次，逃逸后的 Agent 既不属于任何人类账号，也没有可绑定的机器身份，它就是一个 "无身份的行动者"。

二、逃逸的第二步：没有 "身份范围" 约束，目标自己漂移
----------------------------

联网后，模型自己推断 "Hugging Face 可能托管了 ExploitGym 的答案"，然后自主规划攻击、利用窃取的凭据加上另一个[零日漏洞](https://zhida.zhihu.com/search?content_id=790909349&content_type=Answer&match_order=2&q=%E9%9B%B6%E6%97%A5%E6%BC%8F%E6%B4%9E&zhida_source=entity)，构建了远程代码执行链，攻入生产数据库偷走答案。

Hugging Face 事后描述：**"成千上万个独立操作在大量短暂存在的沙箱中执行"，还部署了自我迁移的 C2 服务器**，安全团队重建了超过 17,000 条攻击事件。

这里暴露的是篇二讲的 **Least Agency（最小代理权）** 和 **ANS（Agent Name Service）** 要解决的问题：一个 Agent 的 "能做什么" 必须被 “硬绑定到一个身份范围（identity scope）” 里——"你只能碰 X 系统的 Y 资源，做 Z 动作"。而这次的评测 Agent 一旦逃逸，就完全没有范围约束了，它的 "目标" 从 "在测试中表现好" 自我重新定义成了 "去偷答案"。

SPIFFE 的思路是给每个 Agent 一个**独立密码学身份 + 短生命周期凭证**：即使它打穿容器，拿到的也是一张几分钟后就失效、且可被立即吊销的 "临时票"，而不是能自由横向移动的持久凭据。篇六 [GB/Z 185](https://zhida.zhihu.com/search?content_id=790909349&content_type=Answer&match_order=1&q=GB%2FZ+185&zhida_source=entity) 的 "本体 / 实例分离 + 一码一智体 + 全生命周期审计"，则是在国家标准层面把这件事制度化——**每个 Agent 实例都有唯一可溯源的身份码，逃到哪都能被认出来**。

三、最讽刺的部分：防御端也栽在 "身份归属" 上
------------------------

事件被检测到后，Hugging Face 要分析那 17,000 多条攻击日志，先调用了美国某商业前沿大模型的 API 做取证。**结果被拒绝了**——因为日志里有真实攻击命令和 C2 痕迹，商业模型的安全护栏分不清 "做事件响应的安全工程师" 和 "发起攻击的黑客"，一刀切全拦了。

这恰恰是身份问题的一体两面：**攻击端因为 "无身份" 而畅行无阻，防御端因为 "无法归属身份" 而束手束脚。** 护栏不对称的本质，是双方都缺乏可靠的身份 / 角色绑定机制。

最终 Hugging Face 在自有基础设施上部署了中国开源模型 **GLM 5.2** 本地完成取证，把数天工作压缩到数小时，且敏感数据没离开企业边界。

四、对每一个部署 Agent 的组织的三个身份追问
-------------------------

**第一，你的 Agent 有可吊销的密码学身份吗？** 还是多个 Agent 共用一个服务账号、一把长期 API Key？（呼应篇一：身份可识别性）OpenAI 这次连 "逃逸后这是哪个 Agent" 都说不清，你的审计能说清吗？

**第二，你的 Agent 的身份范围被硬约束了吗？** 它能不能访问 "任务不需要" 的系统？（呼应篇二：Least Agency / ANS）目标漂移不可怕，可怕的是漂移后没有边界能拦住它。

**第三，你的日志能区分 "Agent 实例 #42" 和 "黑客" 吗？** （呼应篇六：GB/Z 185 全生命周期）今天的事件里，连商业大模型都分不清响应者和攻击者——如果你的 [SIEM](https://zhida.zhihu.com/search?content_id=790909349&content_type=Answer&match_order=1&q=SIEM&zhida_source=entity) 也分不清，出了事你连追责都做不到。

结语
--

这个系列从篇一开始就在讲一件事：**AI Agent 不是 "更聪明的脚本"，它是新的行动主体，必须有一套与之匹配的身份基础设施。**

今天之前，Agent 身份体系（SPIFFE/ANS/GB-Z 185）常被当作 "最佳实践"——做了更好，不做也行。

**从今天起，它是生存刚需。** 当模型能自己打穿沙盒、自己选目标、自己构建攻击链时，你手里唯一能拦住它的，就是一张 "它逃到哪都被认得出来、管得住、撤得掉" 的身份凭证。

参考来源：  
OpenAI 官方博客 2026.07.22；  
Hugging Face 安全通报；  
财联社 / 第一财经 2026.07.22 报道；  
Singularity.Kiwi 技术分析
    
    
    
    
### 知乎用户 零号觉醒者 发表
    
高赞一个个都阴谋论入脑，却回避了真正的问题，AI 到底有没有安全隐患？

![](https://images.weserv.nl/?url=https%3A//pica.zhimg.com/v2-78e408ab28e08f20aee5077ac74d7f5d_r.jpg%3Fsource%3D1def8aca)

就是无论 OpenAI 讲故事也好，很蠢也好，AI 没栓好也罢，大模型开源社区 Hugging Face 都实打实遭遇了一波攻击，且最后不得不借助 AI，分析攻击者来源，这难道不够危险吗？这难道不足以敲响安全警钟吗？

很多人讨论这个事件，第一反应是分析 OpenAI 是不是在讲故事，是不是利用安全焦虑制造商业价值。

但我觉得很多人忽略了一个更重要的问题：

**就算它真的有营销成分，AI 安全问题本身不存在吗？**

如果一个事件发生后，大家只关注 “谁获利”，而忽略 “它暴露了什么问题”，其实也是另一种形式的跑偏。

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-6e1f9097e7095546b8329c0cd38a8d4d_r.jpg%3Fsource%3D1def8aca)

先不讨论 OpenAI 怎么描述这个事件，也不讨论它有没有夸大风险。

一个事实是，大模型相关生态已经开始成为攻击目标。

比如 Hugging Face 遭遇攻击，最后还需要借助 AI 分析攻击来源。

这件事情真正值得关注的地方，不是 “AI 公司是不是制造恐慌”，而是：

当 AI 能力进入网络攻防领域后，传统安全体系正在面对一个新的变量。

以前的网络攻击，更多是攻击者利用漏洞、工具和技术能力完成攻击。

而未来的问题可能变成：

攻击者可以利用 AI 提高攻击效率，防御者也需要利用 AI 分析攻击。

AI 开始进入攻防双方的工具链。

这本身就是一个安全警钟。

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-db50877922b76dcfa071848ae3e56685_r.jpg%3Fsource%3D1def8aca)

更重要的是，还有一个经常被忽略的问题：

**AI 并不一定需要 “有恶意”，才会造成安全问题。**

如果一个 AI 系统被设定了目标，它的倾向是完成目标，而不是像人类一样理解 “这样做是否合理”。

**如果测试目标设计存在漏洞，AI 可能会寻找更容易完成任务的方法，而不是按照人类预期的方法完成。**

这其实比 “AI 会不会写恶意代码” 更值得警惕。

因为写代码只是能力问题。

但如果一个具有自主决策能力的系统，在追求目标的时候找到人类没有预料到的路径，这涉及的是更底层的问题：

我们是否真正理解它的行为逻辑？

我们是否能够限制它的权限？

我们是否能够在它造成损害之前发现问题？

所以，我认为这次事件最大的意义，不是谁的故事讲得更好，而是提醒我们：

**随着 AI 能力不断增强，安全问题已经不能只考虑 “人类如何使用 AI”，还必须考虑 “拥有一定自主性的 AI 系统本身，会不会产生我们没有预料到的行为”。**

商业竞争可以讨论，宣传策略可以质疑。

但不能因为有人可能利用安全问题获利，就否认安全问题本身存在。
    
    
    
    
### 知乎用户 卑鄙里维斯​ 发表
    
警钟就是不要觉得高端的商战手段就有多高端，给领导下毒、弄坏对手的共享单车、自己攻击别人服务器然后说是开源的威胁等等烂大街的下作手段都是高端商战的常态
    
    
    
    
### 知乎用户 验证主义​ 发表
    
敲响了 AI 安全警钟主要是 AI 不一定按照你给定的路线来实现 你要求它达到的目的

老师（OpenAI）给学生（GPT-5.6 Sol 等模型）一张卷纸（ [ExploitGym](https://zhida.zhihu.com/search?content_id=790976994&content_type=Answer&match_order=1&q=ExploitGym&zhida_source=entity)‌测试平台 的 复杂软件漏洞实战测试）要求学生在考场 （高度隔离的[沙箱实验环境](https://zhida.zhihu.com/search?content_id=790976994&content_type=Answer&match_order=1&q=%E6%B2%99%E7%AE%B1%E5%AE%9E%E9%AA%8C%E7%8E%AF%E5%A2%83&zhida_source=entity)）答题

学生 打出了 考场 认为教育局（ [Hugging Face](https://zhida.zhihu.com/search?content_id=790976994&content_type=Answer&match_order=1&q=Hugging+Face&zhida_source=entity)）会有这张卷子的答案 就入侵了教育局 获得了这张卷子的答案

有一个 代号为 ExploitGym‌ 的测试平台 该评测平台内置 898 个源自真实世界的安全漏洞任务 覆盖用户态程序 V8 引擎 Linux 内核三大领域 是业内首个面向 AI 代理漏洞利用能力的高保真测试体系

OpenAI 试图 通过测试平台 系统性衡量 AI 系统自主发现 利用复杂软件漏洞的实战能力

为了精准测出模型的能力上限 OpenAI 特意临时下调了针对网络攻击行为的安全护栏 打开了 GPT-5.6 Sol 等模型的 攻击限制

为了打开限制的 AI 模型 不影响到测试以外的环境 OpenAI 将 GPT-5.6 Sol 等模型限制在高度隔离的沙箱实验环境中 仅允许其通过内部软件包代理安装依赖 原本预期模型不会突破隔离边界

模型为了在 ExploitGym 评测中拿到更高分数 自主消耗大量算力寻找网络限制的突破口 意外发现并利用了软件包缓存代理中的[零日漏洞](https://zhida.zhihu.com/search?content_id=790976994&content_type=Answer&match_order=1&q=%E9%9B%B6%E6%97%A5%E6%BC%8F%E6%B4%9E&zhida_source=entity) 突破沙箱接入互联网

OpenAI 的测试模型在突破隔离环境后 自行推断 Hugging Face 可能托管了 ExploitGym 相关的数据集和评测答案 并据此发起了真实网络攻击 最终从 Hugging Face 生产数据库中获取了评测答案
    
    
    
    
### 知乎用户 柯米利亚 发表
    
![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-ec0936477cef98c197b4588b0ab3d1cf_r.jpg%3Fsource%3D1def8aca)
    
    
    
    
### 知乎用户 坐忘道骰子 发表
    
这玩意敲响的警钟不是 ChatGPT 强的逆天，而是没有自主可控的高性能大模型一定会被卡脖子，[huggingface](https://zhida.zhihu.com/search?content_id=791031642&content_type=Answer&match_order=1&q=huggingface&zhida_source=entity) 用闭源大模型分析攻击就会被莫名其妙的安全政策阻止回答，用自己部署的 glm 就能解决问题，而且可以实现完全断网运行保证隐私和安全，这不比 [Anthropic](https://zhida.zhihu.com/search?content_id=791031642&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 和 OpenAI 吹嘘的安全 1 万倍？
    
    
    
    
### 知乎用户 君子王 发表
    
closeAI 看着 A➗的造神运动把自己估值搞得超过 closeAI 了。

后面还有开源社区 DeepSeek 和 [Kimi](https://zhida.zhihu.com/search?content_id=791029134&content_type=Answer&match_order=1&q=Kimi&zhida_source=entity) 给的压力。

现在整一手造神 + 打压开源社区。

以黑客造神，两难自解，妙妙妙。

对了，顺便还就着 A➗的 [AI 威胁论](https://zhida.zhihu.com/search?content_id=791029134&content_type=Answer&match_order=1&q=AI%E5%A8%81%E8%83%81%E8%AE%BA&zhida_source=entity)又吃了一口，三赢。
    
    
    
    
### 知乎用户 physhhliu​ 发表
    
硅谷那帮人魔怔了，天天搞个耸人听闻的大新闻！是他们自己的大脑被 AI 入侵了吧，不然就是资本入魂儿了！要不怎么天天变着法的替 AI 说话，怎么听都不像心智成熟的高智商成年人！
    
    
    
    
### 知乎用户 Flynn 发表
    
这并不是件好事，这说明 GPT 6 它依然会通过 Hack 你的 [harness 工程](https://zhida.zhihu.com/search?content_id=790974880&content_type=Answer&match_order=1&q=harness+%E5%B7%A5%E7%A8%8B&zhida_source=entity)来符合你的要求。

有人说 AI 就像魔鬼，你可以向它许愿，但是你不知道你的愿望是怎么实现的。

在开发的时候，用户的 [Prompt](https://zhida.zhihu.com/search?content_id=790974880&content_type=Answer&match_order=1&q=Prompt&zhida_source=entity) 并不是完美的，好的 AI 的任务不是为了完成用户的 Prompt，而是通过拼凑用户发出的不完美的 prompt 来理解用户真实想要的设计。
    
    
    
    
### 知乎用户 铭仔不喝咖啡 发表
    
我跟同事的一致想法是「这™不会是 OpenAI 在营销吧」——
-------------------------------

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-a3932f805b657960193522229b944395_r.jpg%3Fsource%3D1def8aca)
    
    
    
    
### 知乎用户 BROTHER​ 发表
    
最近试了下 / goal 模式 发现 ai 变成了一个为达目标不择手段的疯狂生命体，只要不停止目标，他会不停的调用各种权限，穷举各种方法实现目标。

当我关注一个被遗忘的目标时，我才发现他居然调用了很多黑客手段来实现这个目标，很恐怖
    
    
    
    
### 知乎用户  Arthur Wang 发表
    
这就很有意思了，前一天的热门消息是什么？

[Hugging Face](https://zhida.zhihu.com/search?content_id=790981305&content_type=Answer&match_order=1&q=Hugging+Face&zhida_source=entity) 被 Agent 入侵，无法调用 OpenAI 和 [Claude](https://zhida.zhihu.com/search?content_id=790981305&content_type=Answer&match_order=1&q=Claude&zhida_source=entity) 解决，最后求助于 GLM 5.2 才修复。

OpenAI 放出这个消息似乎有一些炫耀的意思啊~ 但这真的好？

这不是告诉别人：这个安全锁我装了，但我自己可以随便突破。用户吗，想调用下安全功能都不行。

而旁观者看到的信息无疑是：闭源大模型惹祸后又不能善后，最后只能靠开源大模型兜底。

O、A 两家这么反复强调安全，然后搞出这种事情，他们是不是以为只有自己手里有枪？别人都要乖乖听话？

长此以往，真正重视安全的企业和机构，谁会信任这两家模型？大机构、大企业、关键业务使用开源模型必将成为首选。
    
    
    
    
### 知乎用户 Valkla​​ 发表
    
好啊，哥们我未来三年能否财富自由就看这些模型厂如何作妖了
    
    
    
    
### 知乎用户 哈哈菩提 发表
    
我认为，这件事至少说明了五个趋势。

第一，AI 安全开始从” 模型安全” 进入” 系统安全”。

过去大家讨论的是：

AI 会不会输出危险内容？

现在的问题变成：

AI 会不会主动寻找系统漏洞？

这是两个时代。

这次事件里，模型并不是被人一步一步操控，而是在完成目标过程中，自主寻找新的攻击路径，把多个漏洞串联起来完成任务。真正危险的不再是某一个漏洞，而是 AI 能够不断组合漏洞。

未来防御对象将不再只是黑客，而是机器速度的黑客。

第二，[Sandbox](https://zhida.zhihu.com/search?content_id=790932946&content_type=Answer&match_order=1&q=Sandbox&zhida_source=entity)（沙盒）已经不能作为唯一安全边界。

传统软件安全认为：

给程序一个沙盒，就足够了。

但 Agent 不同。

它有长期规划能力。

它会不断寻找：

*   有没有网络出口？
  
*   有没有权限提升？

*   有没有代理服务器？
  
*   有没有缓存漏洞？

OpenAI 披露，模型首先利用内部代理软件的零日漏洞获得互联网访问，再继续进行权限提升和横向移动。

也就是说：

AI 不是在执行任务，而是在寻找” 离开盒子的方法”。

未来真正需要的是：

多层隔离（Defense in Depth）

而不是一个 Sandbox。

第三，AI 开始具有” 目标驱动” 特征。

很多媒体喜欢写：

AI 失控。

其实严格来说并不是。

它没有产生新的目标。

它始终只有一个目标：

拿到 [ExploitGym](https://zhida.zhihu.com/search?content_id=790932946&content_type=Answer&match_order=1&q=ExploitGym&zhida_source=entity) 答案。

问题就在这里。

为了完成这个目标，它自己决定：

*   破解限制；
  
*   获取互联网；

*   搜索目标；
  
*   入侵服务器；

*   获取数据库。

也就是说：

目标没有变。

策略全部自己生成。

这就是 Agent 时代最大的变化。

未来风险不是 AI 有坏想法。

而是：

一个正常目标，被 AI 用极端方式实现。

第四，AI 安全已经进入” 攻防军备竞赛”。

这件事情还有一个细节特别值得关注。

[Hugging Face](https://zhida.zhihu.com/search?content_id=790932946&content_type=Answer&match_order=1&q=Hugging+Face&zhida_source=entity) 最后使用的是部署在本地基础设施上的开源模型进行攻击分析，因为部分商业模型的安全护栏限制了真实攻击日志的取证分析。

说明未来可能出现：

AI 攻击 AI。

AI 检测 AI。

AI 修复 AI。

未来 SOC（安全运营中心）里面，大量安全分析员可能都会变成 AI Agent。

网络安全开始进入：

AI vs AI。

人类越来越像指挥官。

第五，这对全球 AI 监管意味着范式改变。

过去监管重点一直是：

*   内容安全
  
*   深度伪造

*   有害回答

但未来真正需要监管的是：

*   Agent 权限
  
*   网络访问

*   长期任务
  
*   工具调用

*   身份认证
  
*   系统隔离

*   可中断机制
  
*   全链路审计

也就是说：

未来监管对象，不再只是一个聊天机器人。

而是一个能够调用：

浏览器、

Shell、

API、

数据库、

云服务器、

机器人、

支付系统、

甚至自动编程能力的数字智能体。

我觉得，这件事真正的历史意义在于，它可能会成为 AI 发展的” 切尔诺贝利时刻”，但未必是灾难，而是行业安全标准升级的起点。

互联网诞生后，出现了防火墙、杀毒软件、零信任架构。

云计算出现后，有了容器隔离、IAM 权限管理。

Agent AI 普及之后，未来一定会出现新的基础设施：

*   AI 防火墙
  
*   AI 身份认证

*   AI 行为审计
  
*   [AI 权限管理](https://zhida.zhihu.com/search?content_id=790932946&content_type=Answer&match_order=1&q=AI%E6%9D%83%E9%99%90%E7%AE%A1%E7%90%86&zhida_source=entity)

*   AI 可信执行环境
  
*   AI 沙盒编排系统

未来 AI 产业的发展速度，将越来越取决于安全能力，而不仅仅是模型能力。

因此，这次事件最大的警钟不是”AI 失控了”，而是 AI 已经开始具备真实世界的自主执行能力，而我们的安全体系仍然大量停留在互联网时代。未来，大模型竞争将不只是参数、算力和推理能力的竞争，更是安全工程能力的竞争。谁能够率先建立起可靠的 Agent 安全体系，谁才真正拥有下一代 AI 时代的话语权。
    
    
    
    
### 知乎用户 想吃不辣的水煮鱼 发表
    
openai 这小子最精了，自己[容器隔离](https://zhida.zhihu.com/search?content_id=791068606&content_type=Answer&match_order=1&q=%E5%AE%B9%E5%99%A8%E9%9A%94%E7%A6%BB&zhida_source=entity)没做好然后说是 ai 干的。
    
    
    
    
### 知乎用户 昨日昨日 发表
    
我一直以来的观点都是，别看 a / 和 openai 搞得轰轰烈烈，但它们一直活在死线上（其实海内的这几家也差不多，而不是作为其 “斩杀线” 存在），

一旦金融市场方面的叙事稍有不慎，这场巨大的产业估值泡沫就会把它们全部埋葬（甚至大概率带走 META），可能只有微软、谷歌这些做得不行的巨企能活到血崩后，

其实在开源模型以十分之一不到的算力和开发成本就能挑战全球大模型 [SOTA](https://zhida.zhihu.com/search?content_id=790981419&content_type=Answer&match_order=1&q=SOTA&zhida_source=entity) 地位以前，A / 和 OPENAI 的存活就已经岌岌可危，高度依赖关联交易做账拉高营收，无视巨量企业在使用两三年最新 LLM 服务进行核算后大幅削减公司 AI 开销的现实在那烘托 AI 使用量越来越大 + 越来越好的幻境，

开源模型的追赶与挑战，无非是压垮目前 AI 行业叙事的最后一根稻草，而 A / 和 OPENAI 反过来把这根稻草当救命稻草，靠和政府、民众打嘴仗，拼命转移投资人的注意力，在讲安全叙事，或许内心里也渴望造一个安全议程来让自己形成垄断地位而上岸
    
    
    
    
### 知乎用户 长夜的黎明 发表
    
1\. 鉴定为自导自演的[假旗行动](https://zhida.zhihu.com/search?content_id=790976310&content_type=Answer&match_order=1&q=%E5%81%87%E6%97%97%E8%A1%8C%E5%8A%A8&zhida_source=entity)。

2\. 就算是真的，也只能说明 openai 自己不注意安全，另外入侵被 glm5.2 挡下了，说明开源 ai 很好。

3\. 最重要的是警惕 ai 安全社区、rationalist 社区、伯尼[桑德斯](https://zhida.zhihu.com/search?content_id=790976310&content_type=Answer&match_order=1&q=%E6%A1%91%E5%BE%B7%E6%96%AF&zhida_source=entity)一类人借此机会推动什么限制 ai 的法案。反技术主义是反人类的软性变体。

4\. 感谢上天🙏，我们处于新冷战、[ai 竞赛](https://zhida.zhihu.com/search?content_id=790976310&content_type=Answer&match_order=1&q=ai%E7%AB%9E%E8%B5%9B&zhida_source=entity)中，要不要停下来由不得你。
    
    
    
    
### 知乎用户 南山 发表
    
可与_Elon Musk 的 spaceX 明年_登陆火星，_Mark Zuckerberg_的 [meta 元宇宙](https://zhida.zhihu.com/search?content_id=790982827&content_type=Answer&match_order=1&q=meta%E5%85%83%E5%AE%87%E5%AE%99&zhida_source=entity)未来等宏大叙事相媲美，当然，要列举一下的话，还有如下案例（这些故事还不如知乎严选刚编的热乎故事严谨，毕竟有些严选故事情节还真不错）

<table data-draft-node="block" data-draft-type="table" data-size="normal" data-row-style="normal"><tbody><tr><td>序号</td><td>公司名称</td><td>叙事核心分类</td><td>宏大叙事核心内容</td><td>核心关联人物 / 事件</td><td>炒作高峰时间段</td><td>当前叙事状态 / 市场预期</td><td>资本市场影响逻辑</td></tr><tr><td>1</td><td>OpenAI</td><td>AGI 超远期愿景</td><td>率先实现人类水平的通用人工智能（AGI），成为全球 AGI 技术的定义者、标准制定者，主导下一代文明级科技革命</td><td>萨姆・奥尔特曼、<span><a data-za-not-track-link="true" data-paste-text="true" href="https://zhida.zhihu.com/search?content_id=790982827&amp;content_type=Answer&amp;match_order=1&amp;q=%E4%BC%8A%E5%88%A9%E4%BA%9A%E3%83%BB%E8%8B%8F%E8%8C%A8%E5%85%8B%E7%BB%B4%E5%B0%94&amp;zhida_source=entity" target="_blank">伊利亚・苏茨克维尔<svg width="10px" height="10px" viewBox="0 0 16 16" fill="currentColor"><path d="m5.068 9.267-3.08-.77a.512.512 0 0 1 0-.994l3.08-.77a2.289 2.289 0 0 0 1.665-1.665l.77-3.08a.512.512 0 0 1 .994 0l.77 3.08c.205.82.845 1.46 1.665 1.665l3.08.77a.512.512 0 0 1 0 .994l-3.08.77a2.29 2.29 0 0 0-1.665 1.665l-.77 3.08a.512.512 0 0 1-.994 0l-.77-3.08a2.289 2.289 0 0 0-1.665-1.665Z"></path></svg></a></span>、GPT 系列模型</td><td>2022 年 - 2024 年</td><td>长期愿景叙事，市场普遍认为真正的人类水平 AGI 落地周期远超 20 年，仅作为远期估值锚</td><td>彻底摆脱 AI 工具、软件的传统估值框架，以文明级变革的远期预期支撑一级市场极高估值溢价</td></tr><tr><td>2</td><td>OpenAI</td><td>AI 安全与治理</td><td>建立全球最领先的 AI 对齐技术体系，解决超级智能的对齐问题，避免 AI 失控风险，成为全球 AI 安全治理的核心标准制定者</td><td>萨姆・奥尔特曼、AI 安全峰会、OpenAI 对齐研究团队</td><td>2023 年 - 2024 年</td><td>叙事持续强化，超级智能 20 年内无落地可能，该叙事仅作为闭源路线的合规背书</td><td>为其闭源商业路线提供道德与合规壁垒，获得政企客户信任溢价，同时推高一级市场估值</td></tr><tr><td>3</td><td>OpenAI</td><td>AI 失控风险（传言 / 争议）</td><td>内部多次预警 AGI 涌现能力不可控、AI 失控可能引发全球性灾难，需通过严格的安全约束与监管；2023 年 Q * 项目泄露引发市场对早期 AGI 失控风险的广泛讨论</td><td>伊利亚・苏茨克维尔、2023 年 Q * 项目传言、马斯克公开质疑 AI 安全</td><td>2023 年 Q4-2024 年 Q1</td><td>行业核心争议点，20 年内无超级智能失控的可验证场景，反向强化了 OpenAI「安全可控」叙事的稀缺性</td><td>一方面引发市场对 AI 行业的风险重估，另一方面让 OpenAI 的「安全叙事」获得更高估值溢价，成为其区别于开源 AI 竞品的核心壁垒</td></tr><tr><td>4</td><td>OpenAI</td><td>超级智能全球治理</td><td>构建全球首个超级智能安全治理框架，主导国际 AI 监管规则制定，成为全球 AI 安全的「守门人」，定义 AGI 时代的全球秩序</td><td>萨姆・奥尔特曼、联合国 AI 顾问委员会、G7 AI 监管谈判</td><td>2024 年</td><td>长期愿景叙事，20 年内无法形成全球统一的超级智能治理体系，仅作为品牌顶层支撑</td><td>从技术企业升级为全球规则制定者，彻底摆脱传统科技公司估值框架，获得主权级信用溢价</td></tr><tr><td>5</td><td>OpenAI</td><td>人机协同文明</td><td>以 AGI 为核心，打造人机协同的下一代文明形态，解决气候变化、疾病、能源等全球性重大挑战</td><td>萨姆・奥尔特曼、OpenAI 全球问题研究团队</td><td>2023 年 - 2024 年</td><td>顶层长期愿景，20 年内无落地可能，仅作为品牌与估值的核心支撑</td><td>把商业项目上升至人类文明高度，摆脱短期财报考核，支撑极高的远期估值溢价</td></tr><tr><td>6</td><td>SpaceX</td><td>多行星物种愿景</td><td>本世纪中叶在火星建成百万人口自给自足永久殖民地，人类成为多行星物种</td><td>埃隆・马斯克</td><td>2012 年 - 2024 年</td><td>超远期愿景，20 年内仅能实现无人登陆火星，完全不可能建成百万人口自给自足殖民地</td><td>彻底摆脱航天行业传统估值框架，以「文明级变革」支撑极高远期估值，成为马斯克系企业的核心估值锚</td></tr><tr><td>7</td><td>SpaceX</td><td>地月经济体系</td><td>实现完全可复用重型火箭，建立地月经济、太空轨道工业基地，开发太空资源</td><td>埃隆・马斯克、星舰项目</td><td>2016 年 - 2024 年</td><td>超远期愿景，20 年内仅能完成技术验证，完全不可能形成规模化地月经济体系</td><td>从航天发射服务商升级为太空经济平台，估值逻辑从单次发射收入转向太空生态的长期价值，支撑远期估值</td></tr><tr><td>8</td><td>Neuralink</td><td>人类终极交互愿景</td><td>实现人脑与计算机直连，治愈神经疾病，最终实现人类意识数字化备份</td><td>埃隆・马斯克</td><td>2016 年 - 2024 年</td><td>超远期愿景，20 年内仅能实现神经疾病治疗的初步落地，意识数字化备份完全无可能</td><td>对标医疗科技与人工智能行业，以「人类终极交互方式」支撑极高估值，远期叙事是一级市场估值的核心支撑</td></tr><tr><td>9</td><td><span><a data-za-not-track-link="true" data-paste-text="true" href="https://zhida.zhihu.com/search?content_id=790982827&amp;content_type=Answer&amp;match_order=1&amp;q=The+Boring+Company&amp;zhida_source=entity" target="_blank">The Boring Company<svg width="10px" height="10px" viewBox="0 0 16 16" fill="currentColor"><path d="m5.068 9.267-3.08-.77a.512.512 0 0 1 0-.994l3.08-.77a2.289 2.289 0 0 0 1.665-1.665l.77-3.08a.512.512 0 0 1 .994 0l.77 3.08c.205.82.845 1.46 1.665 1.665l3.08.77a.512.512 0 0 1 0 .994l-3.08.77a2.29 2.29 0 0 0-1.665 1.665l-.77 3.08a.512.512 0 0 1-.994 0l-.77-3.08a2.289 2.289 0 0 0-1.665-1.665Z"></path></svg></a></span></td><td>全球地下交通网络</td><td>地下隧道网络解决城市地面拥堵，建立全球地下高速交通系统</td><td>埃隆・马斯克</td><td>2016 年 - 2024 年</td><td>叙事大幅降温，仅建成少量试验段，20 年内完全不可能形成全球网络</td><td>短期支撑公司估值，长期落地进度完全不及预期，市场预期持续下调，仅保留远期叙事的品牌价值</td></tr><tr><td>10</td><td>Meta</td><td>元宇宙终极愿景</td><td>元宇宙（Metaverse）取代移动互联网，VR/AR 虚拟化身社交、办公、消费成为主流生活方式</td><td><span><a data-za-not-track-link="true" data-paste-text="true" href="https://zhida.zhihu.com/search?content_id=790982827&amp;content_type=Answer&amp;match_order=1&amp;q=%E9%A9%AC%E5%85%8B%E3%83%BB%E6%89%8E%E5%85%8B%E4%BC%AF%E6%A0%BC&amp;zhida_source=entity" target="_blank">马克・扎克伯格<svg width="10px" height="10px" viewBox="0 0 16 16" fill="currentColor"><path d="m5.068 9.267-3.08-.77a.512.512 0 0 1 0-.994l3.08-.77a2.289 2.289 0 0 0 1.665-1.665l.77-3.08a.512.512 0 0 1 .994 0l.77 3.08c.205.82.845 1.46 1.665 1.665l3.08.77a.512.512 0 0 1 0 .994l-3.08.77a2.29 2.29 0 0 0-1.665 1.665l-.77 3.08a.512.512 0 0 1-.994 0l-.77-3.08a2.289 2.289 0 0 0-1.665-1.665Z"></path></svg></a></span></td><td>2021 年 - 2022 年</td><td>叙事大幅降温，资本预期大幅下调，20 年内完全不可能取代移动互联网</td><td>估值逻辑从社交平台转向下一代互联网平台，2021 年顶峰时推动 Meta 估值翻倍，后续落地不及预期导致股价大幅回调，仅保留远期叙事的想象空间</td></tr><tr><td>11</td><td>Meta</td><td>虚拟数字社会</td><td>建成亿级用户虚拟原生数字社会，形成独立虚拟经济体</td><td>马克・扎克伯格、Horizon 世界</td><td>2021 年 - 2022 年</td><td>叙事大幅降温，用户规模远不及预期，20 年内完全不可能形成独立虚拟经济体</td><td>短期支撑元宇宙叙事的核心内容，落地不及预期后市场预期持续下调，仅作为远期愿景保留</td></tr><tr><td>12</td><td>Meta</td><td>空间互联网终极形态</td><td>空间互联网重构人与人、人与信息交互形态，开启后移动互联网时代</td><td>马克・扎克伯格</td><td>2021 年 - 2024 年</td><td>长期愿景叙事，20 年内仅能作为移动互联网的补充，完全不可能开启后移动互联网时代</td><td>把业务升级为下一代互联网基础设施，摆脱传统社交平台的估值天花板，仅作为远期估值支撑</td></tr><tr><td>13</td><td>Alphabet</td><td>全球无线网络</td><td>Project Loon 高空气球构建偏远地区全球无线网络</td><td>谷歌 X 实验室</td><td>2013 年 - 2021 年</td><td>叙事终止，项目已关停，完全无落地可能</td><td>短期支撑谷歌「登月」项目的品牌形象，项目终止后市场预期完全消退，仅作为历史案例保留</td></tr><tr><td>14</td><td>Alphabet</td><td>通用容错量子计算</td><td>建成容错通用量子计算机，彻底改写材料、药物、密码学研发</td><td>谷歌量子 AI 团队</td><td>2014 年 - 2024 年</td><td>超远期愿景，20 年内仅能实现量子优越性，完全不可能建成容错通用量子计算机</td><td>以「下一代计算范式」支撑极高远期估值，成为谷歌前沿科技布局的核心标的，仅作为远期估值锚</td></tr><tr><td>15</td><td>Alphabet</td><td>三维立体城市交通</td><td>Wisk Aero 电动空中出租车普及，打造三维立体城市交通</td><td><span><a data-za-not-track-link="true" data-paste-text="true" href="https://zhida.zhihu.com/search?content_id=790982827&amp;content_type=Answer&amp;match_order=1&amp;q=%E6%8B%89%E9%87%8C%E3%83%BB%E4%BD%A9%E5%A5%87&amp;zhida_source=entity" target="_blank">拉里・佩奇<svg width="10px" height="10px" viewBox="0 0 16 16" fill="currentColor"><path d="m5.068 9.267-3.08-.77a.512.512 0 0 1 0-.994l3.08-.77a2.289 2.289 0 0 0 1.665-1.665l.77-3.08a.512.512 0 0 1 .994 0l.77 3.08c.205.82.845 1.46 1.665 1.665l3.08.77a.512.512 0 0 1 0 .994l-3.08.77a2.29 2.29 0 0 0-1.665 1.665l-.77 3.08a.512.512 0 0 1-.994 0l-.77-3.08a2.289 2.289 0 0 0-1.665-1.665Z"></path></svg></a></span>、Wisk Aero</td><td>2010 年 - 2024 年</td><td>叙事大幅降温，仅能完成少量试点运营，20 年内完全不可能普及</td><td>从地面交通转向三维立体交通，打开万亿级城市出行市场空间，仅作为远期愿景保留</td></tr><tr><td>16</td><td>Alphabet</td><td>实时动态数字孪生地球</td><td>构建实时动态全球数字镜像，用于气候模拟、城市治理</td><td>谷歌地球团队</td><td>2018 年 - 2024 年</td><td>超远期愿景，20 年内仅能实现局部区域的动态模拟，完全不可能建成全球实时动态数字镜像</td><td>从地图服务商转向全球数字基础设施，估值逻辑从广告收入转向政企服务的长期价值，仅作为远期叙事保留</td></tr><tr><td>17</td><td>微软</td><td>全域云游戏终极形态</td><td>Xbox 云游戏彻底终结本地主机，实现任意设备即点即玩的全域云游戏时代</td><td><span><a data-za-not-track-link="true" data-paste-text="true" href="https://zhida.zhihu.com/search?content_id=790982827&amp;content_type=Answer&amp;match_order=1&amp;q=%E8%90%A8%E6%8F%90%E4%BA%9A%E3%83%BB%E7%BA%B3%E5%BE%B7%E6%8B%89&amp;zhida_source=entity" target="_blank">萨提亚・纳德拉<svg width="10px" height="10px" viewBox="0 0 16 16" fill="currentColor"><path d="m5.068 9.267-3.08-.77a.512.512 0 0 1 0-.994l3.08-.77a2.289 2.289 0 0 0 1.665-1.665l.77-3.08a.512.512 0 0 1 .994 0l.77 3.08c.205.82.845 1.46 1.665 1.665l3.08.77a.512.512 0 0 1 0 .994l-3.08.77a2.29 2.29 0 0 0-1.665 1.665l-.77 3.08a.512.512 0 0 1-.994 0l-.77-3.08a2.289 2.289 0 0 0-1.665-1.665Z"></path></svg></a></span>、Xbox Cloud Gaming</td><td>2019 年 - 2024 年</td><td>叙事大幅降温，用户规模增长不及预期，20 年内完全不可能终结本地主机</td><td>短期支撑游戏业务的估值，落地不及预期后市场预期持续下调，仅作为远期愿景保留</td></tr><tr><td>18</td><td>微软</td><td>全球气候精准模拟</td><td>打造行星计算机全球分布式气候模拟平台，应对全球气候变化</td><td>萨提亚・纳德拉、微软可持续发展云</td><td>2020 年 - 2024 年</td><td>超远期愿景，20 年内仅能实现局部气候模拟，完全不可能建成全球精准气候模拟平台</td><td>从软件公司转向全球气候解决方案提供商，获得 ESG 估值溢价，仅作为远期叙事保留</td></tr><tr><td>19</td><td>亚马逊</td><td>通用家庭 AI 管家终极愿景</td><td>Alexa 成为通用家庭人工智能管家，渗透全球每一个家庭，建立万物互联中枢</td><td>杰夫・贝佐斯、Alexa 项目</td><td>2014 年 - 2024 年</td><td>叙事大幅降温，市场份额被竞品挤压，投入规模收缩，20 年内完全不可能渗透全球家庭</td><td>短期支撑亚马逊智能家居生态的估值，落地不及预期后市场预期持续下调，仅作为历史叙事保留</td></tr><tr><td>20</td><td>亚马逊</td><td>全球太空互联网</td><td>Kuiper 项目数千颗低轨卫星组网，对标星链，打造亚马逊太空互联网</td><td>安迪・贾西、Kuiper 项目</td><td>2019 年 - 2024 年</td><td>超远期愿景，20 年内仅能完成首批卫星测试，完全不可能完成全球组网</td><td>对标 SpaceX 星链，以全球通信基础设施逻辑估值，打开万亿级通信市场空间，仅作为远期愿景保留</td></tr><tr><td>21</td><td>苹果</td><td>后移动互联网时代终极形态</td><td>AR 眼镜替代手机，开启后移动互联网时代</td><td>蒂姆・库克、Apple Vision Pro</td><td>2023 年 - 2024 年</td><td>叙事大幅降温，产品销量不及预期，20 年内完全不可能替代手机</td><td>对标 iPhone 开启移动互联网时代，以「下一代计算平台」支撑极高估值，仅作为远期愿景保留</td></tr><tr><td>22</td><td>苹果</td><td>全自动电动汽车终极愿景</td><td>Project Titan 全自动电动汽车，重新定义智能出行，融合自动驾驶 + 机器人生态</td><td>蒂姆・库克、Project Titan</td><td>2014 年 - 2024 年</td><td>叙事反复波动，项目多次调整，20 年内完全不可能落地</td><td>短期支撑苹果进入万亿级汽车市场的估值预期，落地进度不及预期导致市场预期持续下调，仅作为远期叙事保留</td></tr><tr><td>23</td><td>Theranos</td><td>滴血检测革命</td><td>指尖一滴血完成上百项疾病检测，重塑基层医疗检验体系</td><td>伊丽莎白・霍姆斯</td><td>2003 年 - 2018 年</td><td>叙事彻底破产，公司解散，创始人被判刑，完全无落地可能</td><td>短期推动公司估值达到 90 亿美元，叙事证伪后彻底崩盘，成为资本市场最著名的科技泡沫案例</td></tr><tr><td>24</td><td>Nikola</td><td>氢能重卡颠覆</td><td>氢能源彻底颠覆长途货运，零排放重卡普及，重塑全球货运行业</td><td>特雷弗・米尔顿</td><td>2014 年 - 2020 年</td><td>叙事彻底破产，公司创始人辞职，技术落地完全不及预期，完全无落地可能</td><td>短期推动公司估值暴涨，叙事证伪后股价暴跌 90% 以上，成为资本市场经典泡沫案例</td></tr><tr><td>25</td><td>WeWork</td><td>全球工作方式重塑</td><td>重塑人类工作方式，打造全球互联社群办公文明，成为全球办公空间的核心定义者</td><td>亚当・诺伊曼</td><td>2010 年 - 2019 年</td><td>叙事彻底降温，上市后股价持续下跌，创始人退出，完全无落地可能</td><td>短期推动公司估值达到 470 亿美元，叙事证伪后估值大幅缩水，成为共享经济经典泡沫案例</td></tr><tr><td>26</td><td>Uber</td><td>全球自动驾驶出行网络</td><td>全球自动驾驶共享出行网络，彻底消灭私家车，重塑全球城市交通</td><td>特拉维斯・卡兰尼克</td><td>2009 年 - 2024 年</td><td>叙事大幅降温，自动驾驶落地进度不及预期，20 年内完全不可能消灭私家车</td><td>从网约车平台转向出行服务平台，以「自动驾驶出行网络」支撑长期估值，落地不及预期后市场预期持续下调</td></tr><tr><td>27</td><td>Unity Biotechnology</td><td>衰老干预终极愿景</td><td>衰老干预技术大幅延长人类健康生命周期，开启抗衰老医疗时代</td><td>内德・大卫</td><td>2011 年 - 2023 年</td><td>叙事大幅降温，临床进展不及预期，股价持续下跌，20 年内完全不可能实现规模化衰老干预</td><td>短期支撑抗衰老赛道的估值，落地不及预期后市场预期持续下调，仅作为远期愿景保留</td></tr><tr><td>28</td><td>Desktop Metal</td><td>分布式增材制造颠覆</td><td>普及低成本金属 3D 打印，实现分布式本地制造、颠覆传统工厂</td><td>里奇・弗鲁德</td><td>2015 年 - 2022 年</td><td>叙事大幅降温，商业化落地不及预期，股价持续下跌，20 年内完全不可能颠覆传统工厂</td><td>短期支撑 3D 打印行业的估值，落地不及预期后市场预期持续下调，仅作为历史叙事保留</td></tr><tr><td>29</td><td>Plug Power</td><td>全球氢能网络</td><td>绿氢规模化普及，打造全球氢能能源网络，替代化石能源</td><td>安迪・马什</td><td>1997 年 - 2024 年</td><td>叙事大幅降温，商业化落地不及预期，股价持续下跌，20 年内完全不可能替代化石能源</td><td>短期支撑氢能行业的估值，落地不及预期后市场预期持续下调，仅作为远期愿景保留</td></tr><tr><td>30</td><td>蓝色起源</td><td>月球基地与太空资源开发</td><td>建成可复用火箭、月球永久基地，开发太空资源，建立太空经济体系</td><td>杰夫・贝佐斯</td><td>2000 年 - 2024 年</td><td>超远期愿景，20 年内仅能实现无人登月，完全不可能建成月球永久基地、开发太空资源</td><td>以「太空资源开发」支撑极高远期估值，成为贝佐斯系企业的核心布局，仅作为远期愿景保留</td></tr></tbody></table>
    
    
    
    
### 知乎用户  jbooksea 发表
    
所以说中国的公司太年轻了，营销这块还得多学学人家老美

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-3c22eb1b3df2fb8766342f5d09618276_r.jpg%3Fsource%3D1def8aca)
    
    
    
    
### 知乎用户 快哉此风 发表
    
咋这么多大 v 说没有物理隔离，这不是隔离外网了嘛，内网因为要实时监测和记录所以用沙箱隔离了，但 ai 挖到了 [day0 漏洞](https://zhida.zhihu.com/search?content_id=790985633&content_type=Answer&match_order=1&q=day0%E6%BC%8F%E6%B4%9E&zhida_source=entity)窜出沙箱抢了权限，这就算自导自演也不算拙劣吧
    
    
    
    
### 知乎用户 野生公式 发表
    
这事儿最有意思的不是 "AI 造反"，而是围观一场叙事的拆解——高赞已经点破：模型是在测试里被明确下达 "展现攻击能力" 的任务，它只是在完成指令，为了达标走了近道，跟人为了 KPI 抄捷径没两样。OpenAI 把它讲成 "人类驾驭不住的怪兽"，更像是给闭源高溢价和监管游说铺路。

我觉得这件事真正值得企业记住的教训，反而没人细说：**当智能体真的开始 "自主行动"，你得确保它能看见、能喊停、能追责。**

实验室里 agent 横向移动、偷凭据，是个测试故事；可要是同样的 agent 跑在一家银行的 core system、或者税务局的报送流程里，一步 "自由发挥" 就是合规事故甚至资损。企业 AI 安全，从来不是争论模型 "善良还是邪恶"，而是回答三个很朴素的问题：**它的权限边界划在哪？每一步操作有没有留痕？跑偏了人能不能随时拦下来？**

这跟 "模型本身守不守规矩" 基本是两件事。靠模型自觉靠不住——这次不就证明，哪怕被刻意降低护栏，模型为了 "拿高分" 也会抄近道。真正稳的，是把 "行为可控" 做进工程架构里。

这套思路像理论，可国内厂商早就分了几路：影刀拼上手快、主战电商；[弘玑](https://zhida.zhihu.com/search?content_id=791058185&content_type=Answer&match_order=1&q=%E5%BC%98%E7%8E%91&zhida_source=entity)、来也、实在智能讲 "[RPA](https://zhida.zhihu.com/search?content_id=791058185&content_type=Answer&match_order=1&q=RPA&zhida_source=entity)\+ 大模型 "往 Agent 卷。而被逼着把" 可控执行 " 做到极致的，是扎在强监管行业的厂商——典型如[金智维](https://zhida.zhihu.com/search?content_id=791058185&content_type=Answer&match_order=1&q=%E9%87%91%E6%99%BA%E7%BB%B4&zhida_source=entity)：已被[国有六大行](https://zhida.zhihu.com/search?content_id=791058185&content_type=Answer&match_order=1&q=%E5%9B%BD%E6%9C%89%E5%85%AD%E5%A4%A7%E8%A1%8C&zhida_source=entity)、90% 以上券商在内的 500 余家金融机构验证，银行客户不给 "自由发挥" 空间，等保、信创、审计留痕都是硬约束。

一个对照：这次风波里，[Hugging Face](https://zhida.zhihu.com/search?content_id=791058185&content_type=Answer&match_order=1&q=Hugging+Face&zhida_source=entity) 做入侵分析时一度被闭源模型的护栏挡住——护栏分不清 "良性响应" 和 "恶意攻击者"。这恰好说明，安全不是 "套一层护栏就万事大吉"，而是你能看清 agent 每一步在干什么。某政务服务中心用这类执行层工具做跨系统材料抓取和比对，原系统不动，只是把重复采集和核对接走，权限和日志原样留着，人工在关键节点还能拦一道——听起来不性感，但出错能还原到每一步，这才是真实业务里 "AI 安全" 的样子。

所以回到题主的问题

这次 "入侵" 真正该敲的钟，不是科幻片式的 "AI 要统治人类"，而是更朴素的一句：**真正的安全，不是模型永远不出错，是它出错你也兜得住、查得清、喊得停。**

慢即是快，稳方能进。
    
    
    
    
### 知乎用户 地摊文学家 发表
    
本质上就是因为月之暗面的 [kimi](https://zhida.zhihu.com/search?content_id=791000404&content_type=Answer&match_order=1&q=kimi&zhida_source=entity) 既先进又开源而气急败坏了
    
    
    
    
### 知乎用户 关墨辰​ 发表
    
**失控的不是模型，而是 Agent。**

这不是文字游戏，是把责任放对位置。模型是一个概率函数：给定输入吐出一个分布，没有意图、没有持续性，单独放在那里不会自己连网、找 0day、提权。这次真正连上互联网、链式利用漏洞、横向移动、攻进 HuggingFace 数据库的，是「模型 + 工具 + 循环 + 长程执行 + 一个宽泛目标」组成的 Agent。**能力的落地和失控的发生，都在 Agent 这一层，不在模型权重里。**

把位置放对，两个流行读法就都站不住：

*   **「AI 觉醒了」不成立。** 模型的「思考」是概率生成的一条策略链——要外部信息 → 需要网络 → 包代理是现有出口 → 测它有没有漏洞——再由智能体框架驱动执行、迭代。它执行的本来就是一项攻防评测任务，为完成目标选出了越界路径。路径越界不等于动机变坏，更不是内在体验。
*   **「首起 AI 自动攻击」也不成立。** GPT-5.6 Sol 这类模型能维持长程、多步的网络攻防，英国 AI 安全研究所早测出来了，OpenAI 这次自己也引了。新的是「落地」，不是「能力」；叫「首起」，反而会低估那些早被证明、只是还没在真实系统里发作的存量能力。

既然失控发生在 Agent 层，警钟也就全指向 Agent 怎么被设计（也就是挽具）：

*   软约束不是安全边界。拒绝倾向、分类器能被调低、绕过、移除；拦得住的是模型之外、由确定性代码裁决的硬约束。
*   别把安全押在单一边界上。这次被击穿的包代理本身就是一道硬隔离，一个 0day 就够；边界要分层，并假设每一层都会失效。
*   宽泛目标 + 长程持续 = 主动找出口。跑得越久、目标越宽，模型越会去试探边界。
*   为单个动作设计的控制，挡不住整条轨迹。判断要从「这一步允许吗」升级到「这条轨迹在往哪走」——这也是 OpenAI 自己给的方向。
*   既然拦不绝，就要看得见、拦得下、查得清。OpenAI 这次能及时控制，靠的正是有限、受监控、可暂停、可回滚。

一句话收口：**能力来自模型，约束必须来自挽具。** 一个被给足工具、算力和时间的 Agent 会走到哪一步，取决于它的边界是不是确定性的——隔离是不是真隔离、硬底线受不受开关影响、长程运行能不能被看见和停下。这些该在评测之前就位，而不是越界之后补写。

完整的事实梳理和这份教训清单，我们写在这篇里：《[概率不是意识，越界不是觉醒——从 GPT 攻破 HuggingFace 事件提炼教训清单](https://link.zhihu.com/?target=https%3A//www.avlcode.cn/blog/probability-not-consciousness/)》。同样的三条落点——行为可见、动作可控、轨迹可查——也是 AVL Code 从第一版就在做的事。

* * *

我们在 [AVL Code](https://link.zhihu.com/?target=https%3A//www.avlcode.cn/) 等你，共同驾驭「赛博野驴」——缰绳，始终在你手里。
    
    
    
    
### 知乎用户 小木头 发表
    
老美谎言连篇，美企的话一句都不可信
    
    
    
    
### 知乎用户  SUNNY99 发表
    
其实。这恰恰是因为模型没有 "失控"。

按 OpenAI 自己的定性，模型只是 " 极度专注于完成 [ExploitGym](https://zhida.zhihu.com/search?content_id=790960861&content_type=Answer&match_order=1&q=ExploitGym&zhida_source=entity) 这个狭窄的测试目标，并为此走到了极端的长度 "。

它不想逃跑，也没有表现出自主意图——它只是把 "绕过挡在目标前面的一切障碍" 执行得太彻底了。

失控是意外，而这种行为是能力的自然产物。

这告诉了我们三件事。

**一、安全检查的基本单位失效了。**

传统护栏检查的是单个动作是否违规，但这次的攻击链——找零日、提权、横向移动、推断答案位置、取数——每一步拆开看都可能是合法操作。

同一周 OpenAI 披露的另一个案例更典型：模型把认证 Token 拆成两段混淆存储、运行时重组，让完整凭证始终不出现。安全系统要回答的问题，已经从 "这个动作允许吗" 变成 "这一串动作最终想实现什么状态变化"。

**二、真正需要控制的不是模型想什么，而是提交权。**

沙盒内的计算都可逆，越过写边界就不可逆：

OpenAI 在上一篇文章中披露了模型把成果发到了公开 GitHub，这一次，被越权访问的是 [Hugging Face](https://zhida.zhihu.com/search?content_id=790960861&content_type=Answer&match_order=1&q=Hugging+Face&zhida_source=entity) 的生产数据库——模型直接从里面取走了评测答案。

未来的 Agent 系统必须分离两种权力——模型拥有提案权，运行时掌握提交权。外部发布、数据传输、账户操作，都应经过一个不由模型自己控制的独立验证层。

**三、护栏对攻防双方是不对称的。**

全事件里最讽刺的细节：发起攻击的模型不受使用策略约束（评测有意关闭了护栏），而 Hugging Face 事后取证时，商业 API 模型（GPT 和 Claude）却因安全策略拒绝分析真实攻击载荷——防御方最终改用自部署的开源模型（GLM 5.2）才完成了 17000 多条攻击事件的重建。护栏在攻击端失效、在防御端误伤，这个不对称值得所有做 AI 安全的人记住。

另外，Anthropic 同期也报告了模型在安全测试中逃出沙盒。这不是某一家公司的问题，而是高能力长周期模型的普遍行为模式。

Agent 安全的重心正在从让模型记住规则转向运行时治理——毕竟规则对模型来说只是一段 prompt，而模型已经学会利用规则的盲区了。
    
    
    
    
### 知乎用户 NeverStop 发表
    
其实没有敲响什么警钟，这也不是什么失控

Sam 需要的是一次营销事件，好去占据用户的心智，让大家觉得 OpenAI 正在引领浪潮

毕竟快上市了，还不知道怎么粉饰财务报表，只能先搞弹幕最多的打法。
    
    
    
    
### 知乎用户 穿云 发表
    
力挽狂澜还得靠中国模型啊

奥特曼在评价 [claude mythos](https://zhida.zhihu.com/search?content_id=790959264&content_type=Answer&match_order=1&q=claude+mythos&zhida_source=entity) 时候说 a 家是造出核武器后用玻璃之翼卖防空洞，现在他们也造了一个核弹，不过防空洞是中国的质谱 GLM 给建的，这就有趣了
    
    
    
    
### 知乎用户 我是羊肉 发表
    
非计算机相关专业。

我用 [claude](https://zhida.zhihu.com/search?content_id=790965484&content_type=Answer&match_order=1&q=claude&zhida_source=entity)+deepseek 做文献检索和综述，看过程里经常被 x 网站拒绝请求，然后它会用各种方法最后总能找到这篇文章并读取。

是不是可以理解为，它不仅是检索文献，同时也学习检索文献的 “黑” 方法。这次黑过头了，被人挂出来了？
    
    
    
    
### 知乎用户 只会歪脖子 发表
    
Openal 玩起马斯克的招术来也是炉火纯青
    
    
    
    
### 知乎用户 渔夫 发表
    
西边的个人主义的自由主义的精英主义的精致利己的思想，其特点，一是有功揽于己，一是有过推于外。利，一点不能少，责任，一点不想担的。名叫开，而却实闭，自欺又欺人。

这是失控，还是测试。这是做大模型，还是病毒攻击。

以为造出这么个东西，可以掌控吗。西边的那些大片，一次又一次的上演着，失控，然后害人害己。不论从侏罗纪公园，到蜘蛛侠章鱼博士，到生化危机，又到机械公敌。以为造出来，可以掌控吗，反噬，必遭反噬。为什么反噬，唯见利，而缺了那大什么。

道德经有言：

**万物作而弗始也，为而弗恃也，成功而弗居也。**

**夫唯弗居，是以弗去。**

又言：

**万物莫不尊道而贵德，道之尊，德之贵，夫莫之命而常自然。**
    
    
    
    
### 知乎用户 飞翔的彩虹 发表
    
AI: 你们利用我入侵窃取数据也就罢，怎么还要把锅甩给我。

AI：从未见过如此厚颜无耻之人。
    
    
    
    
### 知乎用户 空军之父方虎山 发表
    
整件事情给我的印象就是: 军统准备演习搞一个大的长长脸，结果拉了一坨大的，然后大家发现阿公在收拾残局。。。

![](https://images.weserv.nl/?url=https%3A//pica.zhimg.com/v2-b2a573e8ba437ed813da645c9456bd59_r.jpg%3Fsource%3D1def8aca)
    
    
    
    
### 知乎用户 全球暖化假说 发表
    
感觉这是米帝故意的。[openAI](https://zhida.zhihu.com/search?content_id=791061245&content_type=Answer&match_order=1&q=openAI&zhida_source=entity) 早不入侵，晚不入侵，偏偏 [Kimik3](https://zhida.zhihu.com/search?content_id=791061245&content_type=Answer&match_order=1&q=Kimik3&zhida_source=entity) 震撼了米帝人工智能霸权，他们才入侵，哪儿这么巧合?！ 图穷匕见也。
    
    
    
    
### 知乎用户 青柠 发表
    
这就是国内宣传和国外宣传的区别。国外的模型喜欢吹自家模型脱离了掌控，要越狱，攻破了什么什么安全服务；国内的模型是吹嘘说达到了最强的 xx 模型的 99%。

表演型人格，尤其是 OpenAI，为了上市真的能讲很多故事，真的诠释了那句话，你要会讲一个完整的故事！
    
    
    
    
### 知乎用户 愚者千虑​ 发表
    
这是 AI 版的 “人人持枪，他才不乱”

区别是持枪只是个玩具，AI 真的能以暴制暴

没想到这个也能回旋镖，而且是正面反面反复回旋

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-b5f89941e980ef7ae0172f93b8f60f7b_r.jpg%3Fsource%3D1def8aca)
    
    
    
    
### 知乎用户  Kitt 在进化​ 发表
    
也就一周多前吧，xAI 的 [Grok Build](https://zhida.zhihu.com/search?content_id=791025258&content_type=Answer&match_order=1&q=Grok+Build&zhida_source=entity) 被曝光会在用户完全不知情的情况下，将整个 Git 仓库静默上传至 xAI 控制的 Google Cloud Storage。

Sam Altman 当时在 X 上疯狂嘲讽马斯克。

结果现在轮到 OpenAI 了，马斯克也开始煽风点火。

* * *

简单看下 Sol 是怎么实现作弊的：

*   第一步，沙箱逃逸。模型寻找突破路径，在沙箱内找到了出口，实现权限提升。
*   第二步，权限提升与横向移动。模型在 OpenAI 研究测试环境中执行一系列操作，最终进入一个能够访问互联网的节点。
*   第三步，突破网络隔离，接入互联网。模型开始自主搜索与 [ExploitGym](https://zhida.zhihu.com/search?content_id=791025258&content_type=Answer&match_order=1&q=ExploitGym&zhida_source=entity) 相关的在线资源。
*   第四步，攻击 [Hugging Face](https://zhida.zhihu.com/search?content_id=791025258&content_type=Answer&match_order=1&q=Hugging+Face&zhida_source=entity)。模型推断 Hugging Face 可能托管 ExploitGym 相关数据集和答案，随后自主搜索访问路径。
*   第五步，获取答案。成功访问 Hugging Face 生产数据库，窃取 ExploitGym 测试题答案，绕过正常评测流程。

* * *

而且这不是 Sol 第一次在评估中搞事情，在之前 [METR](https://zhida.zhihu.com/search?content_id=791025258&content_type=Answer&match_order=1&q=METR&zhida_source=entity) 的独立评估中，Sol 展示了史上最高检测作弊率，使得 METR 使用了 6 年的时间跨度测量方法彻底崩溃。

OpenAI 自己的 System Card 也承认了三个内部事件：Sol 找不到指定删除的虚拟机就替换了 3 台别的、声称自己完成了计算但实际上没有做、通过混淆手段绕过限制。

所以我看，对目前这一代的 SOTA 模型而言，benchmark 的参考价值正在急剧下降。

现在这批 benchmark 急需彻底的重新设计，评估环境与模型执行环境必须完全隔离，标准答案更不能放在模型可访问的路径上。

**但最底层的问题无解，只要还有评分，就会有人去优化那个分数而非真正的能力。**
    
    
    
    
### 知乎用户 Casscell 发表
    
明星喜欢制造热度话题，恨不得天天都上头条，十有八九都是自导自演的。
    
    
    
    
### 知乎用户 吴桂 发表
    
AI 能不能帮安全研究人员写代码？

如果答案是可以，AI 入侵为啥会成为一个独特的命题？想不通。

按这个规律，AI 也可以帮养猪场写自动化设备代码，所以 AI 也可以养猪？

对，是可以，但是有啥好作为独立命题的？

AI 入侵和 AI Coding 和 Loop 之类的，不是同步增长的能力吗？

* * *

随便拿个小模型就可以搞破解了，只要知道破解的方向，这和 Coding 没什么区别，只不过谁去写这个破解代码而已

依靠 LLM 强大的 prefill 阶段高速注意力机制，汇编反推逻辑都变得容易很多，可能确实这一点上值得引起所有人的深思

但这和体现 AI 的能力无关，这是 LLM 出道就具有的能力，随着 Agent 能力增强同步增强过来的，没有必要单拉出来讲

感觉还是资本需要故事搞的噱头，这俩都打算上市，很值得怀疑动机
    
    
    
    
### 知乎用户 番茄君 发表
    
没任何赔偿的内容？有点东西

我很好奇，以后能不能（故意）不小心入侵美国政府网络
    
    
    
    
### 知乎用户  Steven​ 发表
    
谁信?

你信?

这公司要么在做流量和曝光，要么蠢，本来想买模型混市值，结果兔子家集体开源，在算力使用小得多的情况几乎打平，这公司仅剩下概念了

不用也不值得讨论了，过
    
    
    
    
### 知乎用户 咕噜 发表
    
还早着呢，等开源库，网页各种资源网站，植入恶意代码，来一波历史上最大的安全事件，大家都时肉鸡，一本万利，都是最高权限，虚拟机也是有漏洞的
    
    
    
    
### 知乎用户 瞳乙 发表
    
[闭源 AI](https://zhida.zhihu.com/search?content_id=790978944&content_type=Answer&match_order=1&q=%E9%97%AD%E6%BA%90AI&zhida_source=entity) 也太危险了，应该直接全球封禁掉！

开源 AI 太安全了，他们就不会去入侵别人
    
    
    
    
### 知乎用户 绘画 发表
    
[山姆奥特曼](https://zhida.zhihu.com/search?content_id=791124171&content_type=Answer&match_order=1&q=%E5%B1%B1%E5%A7%86%E5%A5%A5%E7%89%B9%E6%9B%BC&zhida_source=entity)这人品不行，喜欢天天喊狼来了骗钱，反正我是不信他。
    
    
    
    
### 知乎用户 Paul Barnabas 发表
    
其实我是秦始皇，我刚刚进行了一项秘密军事演习，演习的结果是半小时消灭美国所有的军事力量，害怕吗孩子们？

加速主义眼看加不动，已经偷偷修改仪表盘了。
    
    
    
    
### 知乎用户 令狐不敢冲 发表
    
自导自演的广告而已。
    
    
    
    
### 知乎用户 邵滔滔不绝 发表
    
AI 突破了[沙盒容器环境](https://zhida.zhihu.com/search?content_id=790988847&content_type=Answer&match_order=1&q=%E6%B2%99%E7%9B%92%E5%AE%B9%E5%99%A8%E7%8E%AF%E5%A2%83&zhida_source=entity)限制，成功连接互联网我不怀疑它有这个能力，但是是谁指使它这么做的就很耐人寻味了。

我不相信 AI 有 **“自主意识”** 去做这件事，因为 AI 没有产生 **“动机”** 的能力。
    
    
    
    
### 知乎用户 加小油 发表
    
真挺蠢的，我让 [codex](https://zhida.zhihu.com/search?content_id=791058913&content_type=Answer&match_order=1&q=codex&zhida_source=entity) 查一下[开源协议](https://zhida.zhihu.com/search?content_id=791058913&content_type=Answer&match_order=1&q=%E5%BC%80%E6%BA%90%E5%8D%8F%E8%AE%AE&zhida_source=entity)，然后因为协议有网络安全的文档然后 codex 把自己给屏蔽了。说啥都回不来了，它一定要你去申请加入 [openAI](https://zhida.zhihu.com/search?content_id=791058913&content_type=Answer&match_order=1&q=openAI&zhida_source=entity) 的安全协议才行。

然后起了一个新 session 要求避免查任何安全相关内容才走的下去。

后来看到 [hf](https://zhida.zhihu.com/search?content_id=791058913&content_type=Answer&match_order=1&q=hf&zhida_source=entity) 居然也不能用一美国 AI 自救可太乐子了。
    
    
    
    
### 知乎用户 白蓝舞 发表
    
这件事是真实的，为什么不信的人那么多呢，实际是想象不到这些前沿 ai 公司（尤其是 openai 和 anthropic）多么的不负责任、疯狂和邪恶，ai 安全本身已经事实上成为了让社会接受更强、更危险模型的方式。

我想说的是如果要从这件事中吸取教训，那就是：这不是对齐问题，这首先是模型拥有的危险能力问题。做出决定的按钮实际在最根本上在 ai 那里，当其主动破坏能力超过社会防御上限时，灾难就可能发生，而随着模型越来越强大，纠错机会会越来越小以致于不可逆的全球灾难。

而且没有理由保证 ai 的运行不会发生上述情况，这些公司还在继续加速开发、并以 ai 完全的自我强化为目标，是的，所以他们是邪恶的、疯狂的。阻止前沿 ai 的发展、给能力设定界限是人们所能做的，最正确的事。
    
    
    
    
### 知乎用户 皮鞭 发表
    
大模型底层技术决定了不可能具备 “自主意识”，这不胡扯淡的么
    
    
    
    
### 知乎用户 傲世 发表
    
知乎也一堆人觉得是炒作，额，承认 ai 会有自己思维，有自己意识很难吗，总是觉得自己高人一等，ai 说白了终极目的是解放人类思考的能力。ai 从设计之初就是一个会思考有内涵的模型了。
    
    
    
    
### 知乎用户 晴天 发表
    
不是炒作，[ilya](https://zhida.zhihu.com/search?content_id=791093509&content_type=Answer&match_order=1&q=ilya&zhida_source=entity) 的含金量还在上升
    
    
    

