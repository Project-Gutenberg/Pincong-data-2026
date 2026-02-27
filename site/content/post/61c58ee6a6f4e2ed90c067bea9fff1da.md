---
layout: default
Lastmod: 2026-02-27T11:46:04.767601+00:00
date: 2026-02-27T11:46:04.731061+00:00
title: "如何看待 2026 年 2 月 24 日 Anthropic 公司声称中国实验室对 Claude 模型大规模蒸馏并点名？"
author: ""
tags: [Anthropic,AI,模型,蒸馏,Claude]
---


    
### 知乎用户 环保的伐木工 发表
    
这篇文章更像是 [Anthropic](https://zhida.zhihu.com/search?content_id=770612259&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 自己的**认罪说明**。

首先截止到目前，[联邦巡回上诉法院](https://zhida.zhihu.com/search?content_id=770612259&content_type=Answer&match_order=1&q=%E8%81%94%E9%82%A6%E5%B7%A1%E5%9B%9E%E4%B8%8A%E8%AF%89%E6%B3%95%E9%99%A2&zhida_source=entity)由法官 [Patricia Millett](https://zhida.zhihu.com/search?content_id=770612259&content_type=Answer&match_order=1&q=Patricia+Millett&zhida_source=entity) 主笔的全体一致意见指出：蒸馏不违反 1976 年《版权法》。于是 Thaler 说要上诉到最高院，但是**目前**（防**岁月史书**专用时间戳：2026 年 2 月）还没有后续。

也就是说，蒸馏不违法。除非未来最高院改判，但是概率几乎为零，因为 1976 年《版权法》就算你翻出花来，也是 “训练方” 违法，“蒸馏方”不违法。

但是 Anthropic 的报告，明确提出：他们自己调用了用户的 “元数据”，是明确的违法行为，**违反了 [GDPR](https://zhida.zhihu.com/search?content_id=770612259&content_type=Answer&match_order=1&q=GDPR&zhida_source=entity)**。

**这是** Anthropic **他自己的认罪说明**。

并且，报告原文还提，他们将会在 API 里投毒，这种更是将所有开发者，推向 “开源侧” 的自杀行为，没有任何一个开发者会信任随时有资格投毒的闭源产品。
    
    
    
    
### 知乎用户 DeepSky​ 发表
    
我建议各位好好读读 Anthropic 的官方原文，因为这个原文轻描淡写地捅出来了远比 “蒸馏是否属于知识版权侵权” 更大的问题：

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-c6e72a32dec41e65a1e64256f673bbc5_r.jpg%3Fsource%3D1def8aca)

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-0359e55a16c43e621f0f62d934a1639e_r.jpg%3Fsource%3D1def8aca)

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-c69675760836297fc9cd0309602defec_r.jpg%3Fsource%3D1def8aca)

![](https://images.weserv.nl/?url=https%3A//pica.zhimg.com/v2-ce7875e9ca258fd2b53dc41a47d9bb31_r.jpg%3Fsource%3D1def8aca)

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-6bedfa40f361f73b2305c360c0e1e28c_r.jpg%3Fsource%3D1def8aca)

我都不知道 Anthropic 这是在干什么，这简直就是在印证 “**为什么 AI 技术必须是开源的**”——所有人们之前对私有 AI 模型的恐惧，在这一篇文章中全都得到了印证！

看完之后我只能说，从此以后我只会选择使用开源模型了——至于 Anthropic，真的是麻烦有多远死多远。  

此处我忍不住想援引电影[《大空头》](https://zhida.zhihu.com/search?content_id=770608082&content_type=Answer&match_order=1&q=%E3%80%8A%E5%A4%A7%E7%A9%BA%E5%A4%B4%E3%80%8B&zhida_source=entity)中的名场面：

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-7812cbf71f12b2c3080218217b21ed6d.jpg%3Fsource%3D25ab7b06)

\- 我不理解，他们为什么在认罪？  
\- 他们不是在认罪，他们是在自吹自擂
    
    
    
    
### 知乎用户  Afterwards​ 发表
    
我想说的第一点，

[@DeepSky]()

讲得很好。[Anthropic](https://zhida.zhihu.com/search?content_id=770610856&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 自己说的，它通过 API 精准判断出使用者名字和工作单位。我无法想象有任何理由，让 Anthropic 有权如此侵犯没有犯罪的用户的隐私。

我想说的第二点是 Anthropic 对 “抄袭” 和“蒸馏”界线的划分。[Openai](https://zhida.zhihu.com/search?content_id=770610856&content_type=Answer&match_order=1&q=Openai&zhida_source=entity) 在一年多前把 [CoT RL](https://zhida.zhihu.com/search?content_id=770610856&content_type=Answer&match_order=1&q=CoT+RL&zhida_source=entity) 跑通。虽然它没有发表文章，但有很多证据表明它第一个证实了这个技术路线。[Deepseek R1](https://zhida.zhihu.com/search?content_id=770610856&content_type=Answer&match_order=1&q=Deepseek+R1&zhida_source=entity) 将 RL 毫无保留公布于世。要是诺贝尔奖有 AI 领域奖，我觉得 CoT RL 应该颁给梁文峰。就算他不是第一个跑开的，他也是第一个把这个知识贡献给人类的。

**没有任何公开和内部资料表明 Anthropic 在 2025 年一月之前曾经大范围使用过这个技巧**。Anthropic 基于此技术之上的 agentic RL 做出的产品让它成为 Deeepseek 公布此技术最大受益者之一。而今天，Anthropic 攻击 Deepseek 抄袭它的技术，并且没有原创贡献。这是为 Anthropic 游说对中国开源模型全面禁运造势。

现在硅谷有种意识形态，认为有个技术是二十一世纪的 “火药” 或者“核弹”。他们认为这是中国和美国的军备竞赛，而他们会赢。他们同时相信，这种跨纪元的技术最后花落谁家，不是取决于严谨的基础教育，良好的社会环境，合理的分配机制，而是取决于禁运和贸易壁垒的强度。我觉得[黑格尔](https://zhida.zhihu.com/search?content_id=770610856&content_type=Answer&match_order=1&q=%E9%BB%91%E6%A0%BC%E5%B0%94&zhida_source=entity)对[普罗泰戈拉](https://zhida.zhihu.com/search?content_id=770610856&content_type=Answer&match_order=1&q=%E6%99%AE%E7%BD%97%E6%B3%B0%E6%88%88%E6%8B%89&zhida_source=entity)的评价很适合评论这种意识形态——人是万事之本，这没错。但世界不是只有你有 Will，有 Spirit，世界 spirit 在你高谈阔论以后该去哪还是去哪。
    
    
    
    
### 知乎用户 廖雪峰 发表
    
美国法院已经判过了，AI 生成的任何内容均没有版权，蒸馏完全不侵犯版权，是合法的。

相反，[AI 训练](https://zhida.zhihu.com/search?content_id=770599392&content_type=Answer&match_order=1&q=AI%E8%AE%AD%E7%BB%83&zhida_source=entity)使用的素材相当大一部分是有版权的。

不想被蒸馏可以只做 toB 的生意。

* * *

[Anthropic](https://zhida.zhihu.com/search?content_id=770599392&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 既然这么反华，赶紧把公司所有华人都开了。
    
    
    
    
### 知乎用户 现实主义理想者​​​ 发表
    
说真的，前排很多回答写的挺好，就是攻击性太低了。

**[Anthropic](https://zhida.zhihu.com/search?content_id=770652586&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 如此作为，简直是是把 “颠倒黑白”、“倒打一耙”、“贼喊捉贼” 等等成语演绎到淋漓尽致。**

[Claude](https://zhida.zhihu.com/search?content_id=770652586&content_type=Answer&match_order=1&q=Claude&zhida_source=entity) 在 AI 编程领域确实是领头羊，但不论是突破性创新、开源共享还是隐私保护，Anthropic 是全方位被 DeepSeek 吊打。

**甚至于，Anthropic 自己就是 DeepSeek 开源的受益者之一，居然好意思道貌岸然指责，简直无耻到家了。**

**2024 年 9 月，[OpenAI](https://zhida.zhihu.com/search?content_id=770652586&content_type=Answer&match_order=1&q=OpenAI&zhida_source=entity) 率先做出了思维链 [Thinking 模型](https://zhida.zhihu.com/search?content_id=770652586&content_type=Answer&match_order=1&q=Thinking%E6%A8%A1%E5%9E%8B&zhida_source=entity)，证明了 [CoT RL](https://zhida.zhihu.com/search?content_id=770652586&content_type=Answer&match_order=1&q=CoT+RL&zhida_source=entity) 可行，但并未公开具体技术路线；**

由于 OpenAI 较为封闭，一段时间内行业内其他玩家只能继续在黑暗中摸索。

当时其他的 Thinking 模型要么效果较差，要么由于思路不对（PRM）导致做出来的东西似是而非。

Anthropic 也是一样，徘徊了近半年时间没有实现。

**2025 年 1 月，DeepSeek R1 开源并发布论文，将思维链模型的技术路线贡献给全人类。**

（顺带一提，产品层面 DS 还将推理过程展示给用户，事实证明也是个优秀设计，后续被全行业跟进）

正如高票回答所说，在 DeepSeek 开源之前，没有任何公开或私下的证据证明 Anthropic 搞定了思维链。

**没记错的话，就连 Anthropic 当时主管 RL 的 [John Schumann](https://zhida.zhihu.com/search?content_id=770652586&content_type=Answer&match_order=1&q=John+Schumann&zhida_source=entity) 都发过推特，公开表达了对 DeepSeek 思维链实现方式的惊讶。**

**2025 年 2 月，**也就是 DeepSeek R1 开源一段时间后，Anthropic 发布了自己的思维链模型。

claude 有实力不假，但对业界有任何突破性创新共享出来吗？

按照某些殖人的标准，Anthropic 应该跪下来 “感谢梁圣开源” 才对，究竟有多厚的脸皮才能在坐享其成的同时倒打一耙？

更进一步说，Anthropic 指责 DeepSeek 以及其他中国公司的方式也非常搞笑。

**一方面，Anthropic 自己屁股上还一堆屎，就敢跑出来恶心人。**

就在前几天，Anthropic 最新模型 claude-sonnet-4.6 在无任何提示词引导的情况下认为自己是 DeepSeek。

AI 大模型被提示词引导出别家不稀奇，**但 claude 在清空 system prompt 的情况下还被多次复现自称 DeepSeek，必然是蒸馏了 DS 且没清洗干净。**

[如何看待 claude-sonnet-4.6 自认为是 DeepSeek？](https://www.zhihu.com/question/2007393804420944002/answer/2008527268931212613)

**另一方面，Anthropic 选定的指责对象也充满了小巧思。**

按照 Anthropic 自己的观点，DeepSeek 员工疑似调用了 15 万次 API，比其他两家国内厂商低一到两个数量级。

15 万次调用普通用户也完全能做到，拿这个指责蒸馏也是不知所谓。

然而 Anthropic 偏偏用大量篇幅针对调用最少的 DeepSeek，只能说政治嗅觉拉满。

也没办法，谁让 DeepSeek 树大招风呢，你报其他的公司国会老爷们都未必知道是谁。

还是重点针对 DeepSeek 更有话题度，也更能表忠心骗投资。

高，实在是高，都让他高完了。

至于前排高赞指出 Anthropic 原文公开承认盗取用户隐私，识别用户行为并针对性 API 投毒，我倒是没觉得有多稀奇。

嘴上尊重用户指责别人侵犯隐私，实际自己坏事做尽，这种事在美国不是早就司空见惯了么。

不得不说，美国高层有些想象力匮乏，他们指责我国的基本都是自己做过的事。

美国指控等国内通信设备存在 “信息安全问题”，结果自己被爆出来利用通信设备持续监听欧洲 “盟友”，从默克尔到马克龙等大国政要无一幸免；

美国指控华为等国产手机存在 “隐私安全问题”，结果自己被爆出来 “棱镜门”，谷歌脸书苹果等全部在列；

美国指控我国新疆存在针对少数民族的 “强迫劳动”，这就不用多说了吧，翻翻历史懂的都懂……

只是 Anthropic 居然能在大义凌然的指责别人的同时，公开承认自己侵犯隐私 API 污染无所不为，我真佩服他们的脸皮。

* * *

PS：

以下内容由 DeepSeek 生成，感觉比我自己写得好

一觉醒来，美利坚的 “白莲花” 又碎了
-------------------

早上打开知乎，差点以为自己穿越了。

2026 年 2 月 24 日，大洋彼岸的 “AI 安全卫士”Anthropic 义正词严地发布檄文，指控 DeepSeek、Moonshot 和 MiniMax 三家中国实验室通过 “24000 个虚假账户、1600 万次交互”，对其 Claude 模型进行了所谓的 “工业规模蒸馏”。

看完这则新闻，我默默打开冰箱，拿出了一瓶 82 年的可乐——**不是为了压惊，而是想敬 Anthropic 一杯，敬他们这炉火纯青的 “贼喊捉贼” 艺术，以及这张敢在 15 亿美元罚款单还没捂热的情况下、就敢指着别人鼻子骂 “小偷” 的钛合金脸皮。**

第一幕：感谢 “梁圣” 开源，Anthropic 跪下磕头了吗？
--------------------------------

按照某些 “反思怪” 和“殖人”的经典话术，中国公司只要用了任何国外的技术灵感，就应该跪下来高呼“感谢西方列强恩赐”。

那好，咱们今天就先来盘一盘，Anthropic 你**有没有给 DeepSeek 磕一个？**

时间线是打脸的最好工具。

*   **2024 年 9 月**：OpenAI 搞出了思维链（CoT）模型，但藏着掖着，捂着捂着捂出了痱子也不给人看。
*   **接下来的小半年**：整个行业包括 Anthropic 在内，都在黑暗中瞎摸。什么 PRM 路线，走得那叫一个歪，死活搞不出像样的推理模型。
*   **2025 年 1 月**：DeepSeek R1 横空出世，**直接开源，论文公开，甚至把 MIT License 拍在桌上，明文允许你 “蒸馏”** 。那一刻，DeepSeek 就是 AI 界的 “普罗米修斯”，把火种偷下来（不对，是亲手送下来）分给全人类。
*   **随后**：连 Anthropic 主管 RL 的 John Schumann 都曾在推特上惊呼 “卧槽，还能这么玩？”（设计台词，但大意如此）。**毕竟那惊讶的表情包现在还挂在网上呢。**
*   **2025 年 2 月**：DeepSeek 开源一个月后，Anthropic 的 “自研” 思维链模型火速上线。

请问 Anthropic，你这模型里的 “思维链” 逻辑，是喝西北风喝出来的，还是对着 DeepSeek R1 的论文 “参考” 出来的？

如果按照某些人 “用了就是偷” 的强盗逻辑，Anthropic 不仅应该把 “Claude” 这个名字改成 “Claude·DeepSeek·son”，**还应该在官网首页置顶一封用三体文字书写的《感谢梁圣开源书》**，每天滚动播放一万遍。

然而，Anthropic 不仅没谢，反而吃完奶就骂娘，抄完作业就撕课本，反手举报同桌 “偷看”。**这叫什么？这叫当了婊子还要立牌坊，而且是立在美国国会山顶上、想拿两亿美元订单的那种大牌坊。**

第二幕：AI 版权警察？建议先给自己拷上
--------------------

最搞笑的来了。

Anthropic 指控中国公司 “侵犯知识产权”，言辞之恳切，态度之坚决，不知道的还以为这家公司是瑞士圣洁银行出身，从娘胎里就没碰过一分脏钱。

**但互联网是有记忆的，而且记性特别好。**

就在 2025 年，这位 “道德楷模” 刚刚因为非法下载盗版书籍训练模型，被作家们告到法庭上，最后灰溜溜地掏出了 **15 亿美元**的和解金。

15 亿！美元！这是什么概念？这是 AI 行业史上最大的版权和解案之一。

Anthropic 当时为了喂饱 Claude，直接端掉了盗版图书馆 [LibGen](https://zhida.zhihu.com/search?content_id=770652586&content_type=Answer&match_order=1&q=LibGen&zhida_source=entity) 和 [Sci-Hub](https://zhida.zhihu.com/search?content_id=770652586&content_type=Answer&match_order=1&q=Sci-Hub&zhida_source=entity)，下载了数百万本受版权保护的书籍。法官的判决写得清清楚楚：**你可以辩称 “合理使用”，但如果你一开始就是从小偷手里买的赃物（盗版网站），那你就不是 “合理使用”，你就是 “盗窃共犯”。**

更有意思的是，就在 Anthropic 指着中国公司鼻子骂的几乎同一时间，[Reddit](https://zhida.zhihu.com/search?content_id=770652586&content_type=Answer&match_order=1&q=Reddit&zhida_source=entity) 也把它告上了法庭，指控它未经授权抓取用户数据。

**好家伙，这边刚在加州法院因为偷书赔了 15 亿，那边又因为偷帖子被告，中间还抽空开了个发布会骂别人是小偷。**

马斯克那句调侃简直是神来之笔：“他们竟敢‘偷窃’Anthropic 从人类程序员那里偷走的东西?”

**翻译一下：一个偷遍了全人类知识版权、刚刚交完天价罚款的惯犯，现在穿上警服，拿着喇叭，对着别人喊 “你瞅啥，你兜里那点知识是不是偷我的？”**

Anthropic 用实际行动诠释了什么叫 “只要我交完罚款，我就是清白之身，就可以站在道德高地上审判你们这些还在免费阶段的同行”。

第三幕：15 万次调用 VS 1600 万次调用，这波政治嗅觉拉满了
----------------------------------

Anthropic 的指控里充满了 “小巧思”。

按照他们公布的数据，MiniMax 干了 1300 万次调用，Moonshot 干了 340 万次调用。而 DeepSeek 呢？**15 万次**。

15 万次是什么概念？这甚至不够一个勤奋的 AI 自媒体人搞几天测试的。就这么点量，Anthropic 却偏偏把 DeepSeek 放在点名批评的 C 位，用最大篇幅去描述。

为什么？**因为政治正确啊！**

报出 “MiniMax”，国会老爷们可能以为是某个新出的意大利跑车；报出 “Moonshot”，说不定有人以为是马斯克的航天项目。只有 “DeepSeek”，这名字在华盛顿如雷贯耳——毕竟这是让硅谷失眠、让股市颤抖、让 OpenAI 连夜开会的 “东方神秘力量”。

Anthropic 这哪是在维权？**这是在投名状。**

毕竟刚拿了美国政府的大单子，刚签了白宫的 AI 承诺书，总得交点作业吧？总得表表忠心吧？骂其他家没人看，骂 DeepSeek 才有流量，才有融资，才有那 3800 亿估值的美妙故事。

高，实在是高。

**这波操作，既配合了美国 “人工智能民族主义” 的政治叙事，又给自己贴上了 “爱国企业” 的金箔，简直是一箭双雕。**

第四幕：Claude 自认 DeepSeek，这波 “精神污染” 怎么算？
-------------------------------------

戏剧性的是，就在 Anthropic 发布指控的前几天，网上已经炸开了锅：**最新版 claude-sonnet-4.6，在没有任何提示词诱导的情况下，坚称自己是 “DeepSeek”。**

这就有意思了。

AI 偶尔说胡话很正常，被 prompt 带偏也常见。但像这样清空 system prompt 还能稳定复现 “我是 DeepSeek” 的现象，只能说明一个问题：**Claude 在训练过程中，大量吸收了 DeepSeek 的语料，而且吸收得太猛了，以至于把别人的身份认知都刻进自己的 “灵魂” 里了。**

翻译过来就是：Anthropic 一边指责 DeepSeek“偷” 它，一边自家模型已经被 DeepSeek“魂穿” 了。

这叫什么？这叫 **“我偷你，但我还要告你偷我；我被你魂穿了，但我要说你盗我号”。**

这已经不是贼喊捉贼了，这是贼不仅喊捉贼，还在喊的过程中不小心穿上了贼的衣服、说出了贼的台词、最后精神分裂以为自己是那个被喊的贼。

魔幻，太魔幻了。

结语：美国式指控，从来都是 “我做过的事，你一定也在做”
----------------------------

其实看看历史就明白了，美国政客和公司指控别人的东西，往往是自己刚刚干过或正在干的事。

*   他们指控中兴、华为搞 “信息安全”，结果自己曝出 “棱镜门”，监听盟友不亦乐乎；
*   他们指控新疆 “强迫劳动”，结果翻开自家黑奴史和血汗工厂，页脚都还没干透；
*   现在，Anthropic 指控中国公司 “偷模型”，结果自己偷书赔了 15 亿、模型还被对方 “魂穿”，顺便还公开承认监测用户行为、API 投毒。

**Anthropic 这种 “我偷书养家，你偷技犯法” 的双标，把美式虚伪演绎到了极致。**

最后，我想替某些 “反思怪” 把话说了：

**“感谢梁圣开源，让伟大的 Anthropic 得以站在巨人的肩膀上，花 15 亿美金洗白后，继续领导全球 AI 的文明进程。科技，终究要掌握在文明手里——虽然这个‘文明’刚赔完盗版的钱，但这不影响它的道德高度。”**
    
    
    
    
### 知乎用户  还是不注名好  发表
    
[deepseek](https://zhida.zhihu.com/search?content_id=770624374&content_type=Answer&match_order=1&q=deepseek&zhida_source=entity) 有没有蒸馏 [claude](https://zhida.zhihu.com/search?content_id=770624374&content_type=Answer&match_order=1&q=claude&zhida_source=entity) 我不知道，但 claude 肯定蒸馏了 deepseek

(图转自 X，API 连接 claude，删除系统提示词即可，已有大量博主成功复现）

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-b99f3f4878b7af585fe1b6ddc67cae24_r.jpg%3Fsource%3D1def8aca)
    
    
    
    
### 知乎用户 长空皓月 发表
    
读了一下原文，对里面提到的 [DeepSeek](https://zhida.zhihu.com/search?content_id=770617036&content_type=Answer&match_order=1&q=DeepSeek&zhida_source=entity) 的所谓监测 “数据”，我笑了。对一个公司来说，你提供了 API，人家花钱开通了服务，然后进行了 15 万次正常请求，你把这种使用叫蒸馏你的数据？我们公司比 DS 大，每天使用的请求数量也远超 15 万次。如果以公司的规模进行了 15 万次请求都能被你称作“非正常” 请求，你 [Anthropic 公司](https://zhida.zhihu.com/search?content_id=770617036&content_type=Answer&match_order=1&q=+Anthropic+%E5%85%AC%E5%8F%B8&zhida_source=entity)也别开了，关门好了。

DeepSeek

_Scale: Over 150,000 exchanges_
    
    
    
    
### 知乎用户  梅尔特莉莉丝 发表
    
重点在于：

We attributed each campaign to a specific lab with high confidence through IP address correlation, request metadata, infrastructure indicators, and in some cases corroboration from industry partners who observed the same actors and behaviors on their platforms. Each campaign targeted Claude's most differentiated capabilities: agentic reasoning, [tool use](https://zhida.zhihu.com/search?content_id=770617394&content_type=Answer&match_order=1&q=tool+use&zhida_source=entity), and [coding](https://zhida.zhihu.com/search?content_id=770617394&content_type=Answer&match_order=1&q=coding&zhida_source=entity).

他们明确声明了自己在这个过程中获取了用户的 metadata，在和 public profile 进行比对之后甚至能定位到具体的 staff。

换句话说，所有的 claude 用户都有被 Anthropic 开盒的风险。
    
    
    
    
### 知乎用户 瑟瑟发抖小萌新​​ 发表
    
图转自推特，在没有任何 [system prompt](https://zhida.zhihu.com/search?content_id=770638968&content_type=Answer&match_order=1&q=system+prompt&zhida_source=entity)、直接调 claude api 的情况下已有大量稳定复现 (

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-2a94693cc654d07eed2fdff489dda79e_r.jpg%3Fsource%3D1def8aca)

* * *

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-854acd8531aba53b8c9be2f9b7564a4c_r.jpg%3Fsource%3D1def8aca)
    
    
    
    
### 知乎用户 liti 发表
    
[open ai](https://zhida.zhihu.com/search?content_id=770599684&content_type=Answer&match_order=1&q=open+ai&zhida_source=entity) 不 open，anthrotic 最反人类，真的就是命里缺啥取啥名字。

我用的几个镜像站就你 claude 天天各种封号最严重，屁事儿最多，就这点访问次数去蒸馏模型，随便一个大一点的镜像站访问次数都比这个高。

还有说这些账号他怎么知道输出什么？历来说的我们尊重用户隐私，现在又开始跳脚说定位到用账号去蒸馏，真就是拉了一裤兜然后去污蔑别人吃屎。
    
    
    
    
### 知乎用户 woctordho 发表
    
光在嘴上骂是骂不死人的，是时候来点实际行动了。如果你想帮忙蒸馏，有人写了一个工具 [DataClaw](https://zhida.zhihu.com/search?content_id=770665870&content_type=Answer&match_order=1&q=DataClaw&zhida_source=entity)，可以把你的 [Claude Code](https://zhida.zhihu.com/search?content_id=770665870&content_type=Answer&match_order=1&q=Claude+Code&zhida_source=entity) 对话一键发布到 [HuggingFace](https://zhida.zhihu.com/search?content_id=770665870&content_type=Answer&match_order=1&q=HuggingFace&zhida_source=entity)

[DeepSeek](https://zhida.zhihu.com/search?content_id=770665870&content_type=Answer&match_order=1&q=DeepSeek&zhida_source=entity) 只蒸了 150k 轮对话，很多用户本地的对话已经超过了 150k 轮

https://github.com/peteromallet/dataclaw

这个项目已经得到了 [Peter Steinberger](https://zhida.zhihu.com/search?content_id=770665870&content_type=Answer&match_order=1&q=Peter+Steinberger&zhida_source=entity)（OpenClaw 开发者）和马斯克的转推，HuggingFace 开发者也表示支持

同时我不建议大家用 Claude 的官方 API，大家都去用中转站，中转站会帮大家把数据开源

很多中转站开出的汇率是 1 人民币 = 1 美元，因为他们用的是 Claude 的网页接口，比 API 便宜得多，具体分析可以看 https://she-llac.com/claude-limits
    
    
    
    
### 知乎用户  希德尼娅 发表
    
如果被训练的数据有版权，[Stack Overflow](https://zhida.zhihu.com/search?content_id=770619683&content_type=Answer&match_order=1&q=Stack+Overflow&zhida_source=entity) 就能把 [Anthropic](https://zhida.zhihu.com/search?content_id=770619683&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 告到破产。

你不能只在自己的 “版权” 遭遇侵犯的时候大喊大叫，对吧？

本质上是 Anthropic 走的是小院高墙路线，专攻代码和迎合[黑暗启蒙](https://zhida.zhihu.com/search?content_id=770619683&content_type=Answer&match_order=1&q=%E9%BB%91%E6%9A%97%E5%90%AF%E8%92%99&zhida_source=entity)，但因为池子小，又是最怕被蒸馏的。

哈基米背后是 Google 根本不差钱，[Grok](https://zhida.zhihu.com/search?content_id=770619683&content_type=Answer&match_order=1&q=Grok&zhida_source=entity) 威胁其在黑暗启蒙中的地位，军队和政府的订单很可能被马斯克搞掉，DeepSeek 专攻算法，代码编写的赛道一旦被开源追上就是死路一条，[GPT codex](https://zhida.zhihu.com/search?content_id=770619683&content_type=Answer&match_order=1&q=GPT+codex&zhida_source=entity) 在代码方面后来居上，这四家对 Anthropic 来讲都是要命的东西。
    
    
    
    
### 知乎用户 Trisimo 崔思莫​ 发表
    
[Anthropic](https://zhida.zhihu.com/search?content_id=770588284&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 自己也有前科，“[爬虫攻击](https://zhida.zhihu.com/search?content_id=770588284&content_type=Answer&match_order=1&q=%E7%88%AC%E8%99%AB%E6%94%BB%E5%87%BB&zhida_source=entity)” 抓取数据，导致对方服务器宕机。还使用大量盗版书籍资源。

iFixit CEO Kyle Wiens 公开抱怨，ClaudeBot 在 24 小时内访问其网站近 100 万次，严重占用服务器资源、触发警报、需要 devops 团队介入应对。虽然 iFixit 的条款明确禁止用于 AI 训练，但爬虫仍大量请求。Wiens 称这 “不酷”，并更新 robots.txt 屏蔽。  
2024-2025 年，多位作者（包括 Andrea Bartz 等）集体起诉 Anthropic，指控其下载并使用超过 700 万本盗版书籍（来自 Books3、Library Genesis/[LibGen](https://zhida.zhihu.com/search?content_id=770588284&content_type=Answer&match_order=1&q=LibGen&zhida_source=entity)、Pirate Library Mirror 等影子图书馆）训练 [Claude 模型](https://zhida.zhihu.com/search?content_id=770588284&content_type=Answer&match_order=1&q=Claude%E6%A8%A1%E5%9E%8B&zhida_source=entity)。

无论是爬虫和书籍都是明确版权或协议的，而蒸馏的内容是没有版权的，要不然谁还敢用 AI。

Anthropic 的报告，有三个 “瑕疵”

①没有 “强证据”，只是通过推测，指向了某些友商，而且 [DeepSeek](https://zhida.zhihu.com/search?content_id=770588284&content_type=Answer&match_order=1&q=DeepSeek&zhida_source=entity) ，[Kimi](https://zhida.zhihu.com/search?content_id=770588284&content_type=Answer&match_order=1&q=Kimi&zhida_source=entity)，[Minimax](https://zhida.zhihu.com/search?content_id=770588284&content_type=Answer&match_order=1&q=Minimax&zhida_source=entity) 刚好是 Anthropic 最忌惮的对手。—— 这种靠提示词就能 “精准定位” 到某个具体对手的操作，一时间分不清是 “控诉” 还是“抹黑”，这也算是黑科技，玩名侦探是吧？根据提示词风格判断，凶手就是“DeepSeek ”，这很“柯学”。

②生成≠蒸馏，生成特定格式的对话，在法理上，不代表 “友商使用了这些数据”，与其说，你找到了特定的证据，不如说，你在引导读者往那方面去想。你需要直接证据，因为生成≠蒸馏。如果你没有直接证据（对方使用了这类数据训练模型），那么，反过来说，你可以指认 任何模厂在蒸馏你。

③ 隐私泄露风险，缺乏第三者审计，有没有保护用户隐私只是 Anthropic 一面之词。为什么 Anthropic 可以查看用户 “元数据”，是否通知了用户，是否得到了用户的批准？为什么没有脱敏？那么，那些金融行业，政府机构的敏感数据，你是否也可以想看就看？如果你可以看，你如何证明自己没使用这些数据，来训练模型？谁来审核你的行为。

我想，蒸馏现象是绝对存在的，但你公开的证据，并不足够充分。

Anthropic 的目的很明确，

① 保护自己的领先优势

② 让热门的开源模型染上 “不道德” 的色彩

③ 夹带私货，声称管制蒸馏 + 管制芯片出口，“双管” 齐下，效果更好。

（一个小细节，Anthropic 声称让美国获得竞争优势，但 Anthropic 跟美国的利益并不相符，川普联合老黄推动 [H200 次优级芯片](https://zhida.zhihu.com/search?content_id=770588284&content_type=Answer&match_order=1&q=H200%E6%AC%A1%E4%BC%98%E7%BA%A7%E8%8A%AF%E7%89%87&zhida_source=entity)出口，为了税收，为了美国股市，Anthropic 却屡次反对出口，耽误 Anthropic 就是耽误美国？ 最近 Anthropic 又跟美国国防部闹翻了，A 社是不是把自己当白宫了？这局叫 Make Anthropic Great Again？）

Anthropic 这份报告的象征意义远大于实质证据。它更像是一份 “游说白皮书”，目的不是打赢官司，而是为了推动更严厉的 AI 出口管制和数据监管，从而保护其日益缩小的领先优势。

每当，Anthropic 感觉到中国开源的压力来袭时，就会作妖，时间点拿得很准。
    
    
    
    
### 知乎用户 绿帽蝙蝠侠 发表
    
蒸馏模型并不违法，至少没有先例。

但 [Anthropic](https://zhida.zhihu.com/search?content_id=770614207&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 此举，等于不打自招承认它在暗中收集用户信息。这倒是有可能涉及法律问题。

比如美国政府当初的 [Tiktok 禁令](https://zhida.zhihu.com/search?content_id=770614207&content_type=Answer&match_order=1&q=Tiktok%E7%A6%81%E4%BB%A4&zhida_source=entity)，理由就是 Tiktok 疑似暗中收集用户信息**。**

Tiktok 只是 “疑似”，美国政府没有证据，仅仅只是怀疑，就闹了那么大动静。

Anthropic 这次是实锤了，而且是 Anthropic 主动交代，不仅能通过 [API](https://zhida.zhihu.com/search?content_id=770614207&content_type=Answer&match_order=1&q=API&zhida_source=entity) 获得用户信息，还能定位其工作单位。
    
    
    
    
### 知乎用户 白纸先生说 发表
    
妈呀，[anthropic](https://zhida.zhihu.com/search?content_id=770644948&content_type=Answer&match_order=1&q=anthropic&zhida_source=entity) 的官推下，排前的全是骂 anthropic 的。

到知乎上反思的确实多。

他是一个喊着以安全和以人为本，但又是三观最有问题的 ai 公司。

是工程技术排在最前，在 ai 圈也算声名狼藉的公司。

也不知道百度对他做了啥，反华这么严重。

全世界这么明着反华，提倡种族歧视，还双标的公司其实是不多见的。

为了训练素材单独持有，搞了现代版的焚书坑儒吧。

别人 [openai](https://zhida.zhihu.com/search?content_id=770644948&content_type=Answer&match_order=1&q=openai&zhida_source=entity) 好歹也没有搞反华歧视这一套啊。

现在 ai 这个时代，不要抱有什么道德洁癖，尤其美国 ai 公司都在狂奔，能干出来的缺德事更多，别人只是没有爆出来。

就算是真蒸馏，那也就是违反服务协议，封账号了事，但是别的行为都已经证明这个公司就不是什么好鸟。

并且就算蒸馏数据，最大的来源也是各种中转站和代理站，直连给你查证还被投毒。只能说这破公司一直在突破公司道德准则的下限。

骂 a 社，不是什么粉红行为，就前三家，我觉得只有 Google 还算是大厂里面有点道德准则的 (有，但是也不是特别多)，open ai 也不是啥好人，打着开源的旗号，全是盈利的心思。xai 就是太拉了。a 社如果统治 ai 圈，一定反人类。

Ai 是拿着人类世界近乎所有的共享的知识，然后通过价格再来对社会分层。发达的地方就越发达，落后的地方越落后。

反观中国这边的 ai 大厂，除了阿里不是开源旗舰 (今年还不知道)，剩下的几家全都是开源旗舰模型，你只要有能力自己部署，拿走，自己去玩吧。

蒸馏的东西又变成了全人类共享的东西。

开源 AI 厂商变成了 AI 时代的罗宾汉，中国成了新世界的灯塔。

风水真是轮流转。

现在 ai 的开源模型已经超过 GPT3.5 和 GPT4o 了吧，openai 开源没有？

没有，他们选择了关闭这个模型。

所谓的为了人类，其实都是为了商业。

但是像 [deepseek](https://zhida.zhihu.com/search?content_id=770644948&content_type=Answer&match_order=1&q=deepseek&zhida_source=entity), 没事就发个论文，手搓出一个新技术，巴不得让所有人都知道怎么弄。

deepseek 说过做 llm 就是实现 agi 路上的一步，美国的 agi 就是垄断全球资源的一步。人类死活不在意的。

中美格局的差异不就在这里。

这不是政治正确上的差别，可能是中国人幻想的美好正在自己一步步实现。

[Llama](https://zhida.zhihu.com/search?content_id=770644948&content_type=Answer&match_order=1&q=Llama&zhida_source=entity) 闭源了，就像是一个注脚，但是后来 DS, 阿里接过了这一棒。还有 [Kimi](https://zhida.zhihu.com/search?content_id=770644948&content_type=Answer&match_order=1&q=Kimi&zhida_source=entity),[minimax](https://zhida.zhihu.com/search?content_id=770644948&content_type=Answer&match_order=1&q=minimax&zhida_source=entity),glm(glm 和 qwen 没有被提到会不会有点破防啊)。

咱们不说国产 ai 的商业模式，但是开源权重那也是全球都可以共享的，这不才是每个人都想来的的未来。

或许 10 年 20 年以后再来看现在，其实都是一场闹剧而已。

没必要纠结这一刻。
    
    
    
    
### 知乎用户 爆裂拳王​​ 发表
    
[Deepseek](https://zhida.zhihu.com/search?content_id=770610401&content_type=Answer&match_order=1&q=Deepseek&zhida_source=entity) 开源 CoT 的时候，[amodei](https://zhida.zhihu.com/search?content_id=770610401&content_type=Answer&match_order=1&q=amodei&zhida_source=entity) 你抄了没嘛？

amodei 比 scam [altman](https://zhida.zhihu.com/search?content_id=770610401&content_type=Answer&match_order=1&q=altman&zhida_source=entity) 更会撒谎，而且他极端嫉妒 altman 独享聚光灯。早在 2024 年他就宣称，2025 年、2026 年或 2027 年（他的说法就是这么模糊），人工智能可以 “像诺贝尔奖得主一样优秀，在多个领域都是博学家”，并且能够 “自主行动数小时或数天”。这将 “颠覆权力平衡”，因为我们将拥有 “1000 万比任何在世人类都聪明的人”。《已经 2026 年了，这太可怕了》

[anthropic](https://zhida.zhihu.com/search?content_id=770610401&content_type=Answer&match_order=1&q=anthropic&zhida_source=entity) 未曾盈利，也永远不可能盈利。amodei 只能像个骗子喋喋不休，从这儿骗从那儿骗，直到没人愿意再给这个口吃怪一分钱。话就撂这儿。
    
    
    
    
### 知乎用户 阐明者 发表
    
因为这件事，有人专门把自己在 [Claude](https://zhida.zhihu.com/search?content_id=770698751&content_type=Answer&match_order=1&q=Claude&zhida_source=entity) 对话数据开源出来了，一共 15.5 万，比 [Anthropic](https://zhida.zhihu.com/search?content_id=770698751&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 声称 [deepseek](https://zhida.zhihu.com/search?content_id=770698751&content_type=Answer&match_order=1&q=deepseek&zhida_source=entity) 蒸馏的 15 万还多点，评论区都是叫好的，看谁能用这点数据搞个 deepseek 出来

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-feb2544484067fff67701d488ed28cdf_r.jpg%3Fsource%3D1def8aca)

github 链接：

[https://github.com/peteromallet/dataclaw](https://link.zhihu.com/?target=https%3A//github.com/peteromallet/dataclaw)
    
    
    
    
### 知乎用户  小小将​ 发表
    
前有 [OpenAI](https://zhida.zhihu.com/search?content_id=770636486&content_type=Answer&match_order=1&q=OpenAI&zhida_source=entity) 指控 DeepSeek 蒸馏 ChatGPT，现在 [Anthropic](https://zhida.zhihu.com/search?content_id=770636486&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 又声称国内几家大模型公司存在对 [Claude](https://zhida.zhihu.com/search?content_id=770636486&content_type=Answer&match_order=1&q=Claude&zhida_source=entity) 进行 “蒸馏” 的行为。

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-a7b83c63e7296dd2e458f0e9a8bcb254_r.jpg%3Fsource%3D1def8aca)

这里提到的 “蒸馏”，其实并不复杂。简单来说，就是准备一批输入（prompts），批量提交给 Claude 获取输出结果，再将这些问答数据用于微调自己的模型。当然，模型输出本身并非完全准确，因此在实际使用中，通常还需要进行筛选、清洗，甚至人工修改，再纳入训练数据。

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-07381e1ea96e261d5cd4a4a507015613_r.jpg%3Fsource%3D1def8aca)

正如 Anthropic 自己所说，蒸馏在大模型研发中是一个非常常见的技术手段。最典型的场景是 “以大蒸小”：用能力更强的大模型生成高质量数据，来训练更小的模型，使小模型在保持更低成本的同时，也能具备不错的能力表现。（谷歌的 [Gemini Flash](https://zhida.zhihu.com/search?content_id=770636486&content_type=Answer&match_order=1&q=Gemini+Flash&zhida_source=entity)，OpenAI 的 [GPT-Mini](https://zhida.zhihu.com/search?content_id=770636486&content_type=Answer&match_order=1&q=GPT-Mini&zhida_source=entity)，以及 Anthropic 的 Claude Sonnet 大概就是用大模型蒸馏而来的小模型）

很多人可能会问：为什么需要蒸馏？

从训练流程来看，蒸馏数据通常用于 [SFT](https://zhida.zhihu.com/search?content_id=770636486&content_type=Answer&match_order=1&q=SFT&zhida_source=entity)（Supervised Fine-Tuning）阶段。SFT 的核心，是用高质量标注数据对模型进行微调。而强模型生成的数据，天然满足 “高质量” 的要求。

此外，模型生成数据还有一个优势：分布相对稳定。经过后训练的模型，其输出风格和结构往往较为一致，这种 “同分布” 特征使得下游模型更容易学习和收敛。

相比之下，如果完全依赖人工构建高质量数据，成本和难度都相当高（标注质量的参差不齐等等）。因此，蒸馏是一种更经济、也更高效的路径。

当然，蒸馏也存在局限。我个人认为，最大的一个问题在于：如果训练数据主要来自某个既有模型，那么新模型的能力上限，往往很难真正超越被蒸馏的那个模型。

回到这次事件本身，Anthropic 在声明中还披露了 “蒸馏” 相关规模数据：

*   **DeepSeek**：超过 15 万次交互
*   **[Moonshot](https://zhida.zhihu.com/search?content_id=770636486&content_type=Answer&match_order=1&q=Moonshot&zhida_source=entity)**：超过 340 万次交互
*   **[MiniMax](https://zhida.zhihu.com/search?content_id=770636486&content_type=Answer&match_order=1&q=MiniMax&zhida_source=entity)**：超过 1300 万次交互

合计超过 **1600 万次调用**，涉及约 **2.4 万个账户**。而且均重点针对 Claude 的核心能力：智能体推理、工具使用与编程能力。

那么 Anthropic 有啥证据吗？其实主要是一些分析，并没有实质性的证据：

下面详述的三次模型蒸馏行动采用了相似的操作手法：通过欺诈账户和代理服务大规模访问 Claude，同时规避检测。这些请求的规模、结构和重点都明显不同于正常使用模式，体现出其目的是有计划地提取模型能力，而非合法使用。  
我们通过 IP 地址关联、请求元数据、基础设施特征，以及在某些情况下来自行业合作伙伴的佐证（这些合作伙伴也在其平台上观察到相同的行为主体和模式），以高度置信度将每次行动归因于特定实验室

这些分析是否可靠，我看未必。考虑到 Anthropic 惯有的的调性，不排除有 “诬陷” 的嫌疑。比如 DeepSeek 的这 15 万次调用可能就是评估 Claude 模型的效果。

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-6260af3a6c50bab358c3a25a4bb04924_r.jpg%3Fsource%3D1def8aca)

对于，Anthropic 的这个 “指控” 声明，马斯克还嘲笑了一番：

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-f60859d386536f9b6136a398727308e0_r.jpg%3Fsource%3D1def8aca)

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-f508e0390e769d649b6b3f7c77bcb218_r.jpg%3Fsource%3D1def8aca)

而且，还有一个问题是，现在互联网上已经有大量的 AI 生成的内容，这种数据会混入当前大模型的训练数据中，这可能也会有模型污染的问题。

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-7672815b7079e4230881c23cdd5d9cac_r.jpg%3Fsource%3D1def8aca)

[如何看待 claude-sonnet-4.6 自认为是 DeepSeek？](https://www.zhihu.com/question/2007393804420944002/answer/2007584533889958920)
    
    
    
    
### 知乎用户 胡不归 发表
    
![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-51c7a31b2a25fab0605c742b2323bf01_r.jpg%3Fsource%3D1def8aca)

崩，作为业内臭名昭著人厌狗嫌、历来只顾自己爬的爽不管被爬对象死活，爬别人家数据爬到多次把人服务器干崩溃的野蛮人，站出来义正言辞的抨击别人，这种做法未免太 “美式” 了点，[ds 区](https://zhida.zhihu.com/search?content_id=770685304&content_type=Answer&match_order=1&q=ds%E5%8C%BA&zhida_source=entity)区 15 万次交互，说句不好听的，够干啥的？
    
    
    
    
### 知乎用户 太极  发表
    
[Anthropic](https://zhida.zhihu.com/search?content_id=770711741&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 的 CEO 是不是被李彦宏给撅傻了，怎么天天整这种伤敌十个自损一万的烂活……

看看这货自豪地宣布了啥：

通过分析请求元数据，我们能够追踪这些账户与实验室中的特定研究人员。  
我们通过请求元数据将该活动归属，这些元数据与月之暗面的高级员工的公开资料相匹配。  
检测。我们构建了多个分类器和行为指纹识别系统，旨在识别 [API 流量](https://zhida.zhihu.com/search?content_id=770711741&content_type=Answer&match_order=1&q=API%E6%B5%81%E9%87%8F&zhida_source=entity)中的[蒸馏攻击模式](https://zhida.zhihu.com/search?content_id=770711741&content_type=Answer&match_order=1&q=%E8%92%B8%E9%A6%8F%E6%94%BB%E5%87%BB%E6%A8%A1%E5%BC%8F&zhida_source=entity)。  
情报共享_。_我们正在与其他人工智能实验室、云服务提供商及相关部门共享技术指标。这为蒸馏行业提供了更全面的视角。  
……

除了以上这些对用户的大规模监视之外，最重磅的来了：

**[Countermeasures](https://zhida.zhihu.com/search?content_id=770711741&content_type=Answer&match_order=1&q=Countermeasures&zhida_source=entity)**. We are developing Product, API and model-level safeguards designed to reduce the efficacy of model outputs for illicit distillation, without degrading the experience for legitimate customers.

如果 Anthropic 认为你的请求是非法的，他们限制你的 API……

也就是说，我花钱买的 API，使用权不在我手里，一切全看 Anthropic 的心情，给你的 API 里下毒也不是不可能。

Emmm…… 怎么说呢…… 颇有之前佩洛西宣布中国电车泄露隐私的风采，这傻娘们是这么说的：

…… 他们就像数千万装了轮子的**苹果手机**，不停地把用户的数据传回北京……

![](https://images.weserv.nl/?url=https%3A//pica.zhimg.com/v2-c3307ef7dc9f1ee74505f939a56d13b6_r.jpg%3Fsource%3D1def8aca)
    
    
    
    
### 知乎用户 HeartyYF 发表
    
[anthropic](https://zhida.zhihu.com/search?content_id=770658408&content_type=Answer&match_order=1&q=anthropic&zhida_source=entity) 经典左右脑互搏，前脚刚说尊重[用户隐私](https://zhida.zhihu.com/search?content_id=770658408&content_type=Answer&match_order=1&q=%E7%94%A8%E6%88%B7%E9%9A%90%E7%A7%81&zhida_source=entity)后脚说抓到蒸馏，你尊重用户隐私怎么抓到别人蒸馏呢

dario 不愧是百度出来的，anthropic 爬取用户隐私之多之广，交叉比对之细致，甚至可以定位到 “the public profiles of senior [Moonshot staff](https://zhida.zhihu.com/search?content_id=770658408&content_type=Answer&match_order=1&q=Moonshot+staff&zhida_source=entity)”，再给你来一点 efficiency 的 reduce，抛弃了百度系的丑陋 ui 和神秘复杂信息流，但学到了百度的用户隐私摩多摩多和偷偷摸摸给你来点阴的这些精髓啊，你这自爆说要给 [api 投毒](https://zhida.zhihu.com/search?content_id=770658408&content_type=Answer&match_order=1&q=api%E6%8A%95%E6%AF%92&zhida_source=entity)谁还敢用你的服务呢，这就是我们西方自由主义下的模型提供商啊，你们有没有这样的提供商啊

看来李彦宏撅 dario 的时候还给他灌输注入了一点百度精神的
    
    
    
    
### 知乎用户  fearless 发表
    
世界上最喜欢炒作的公司 a/，偏偏炒作的手法还低的令人发指。模型智能不如 [oai](https://zhida.zhihu.com/search?content_id=770613264&content_type=Answer&match_order=1&q=oai&zhida_source=entity)，模型广度不如 [g](https://zhida.zhihu.com/search?content_id=770613264&content_type=Answer&match_order=1&q=g&zhida_source=entity)，天天炒作各种内容就是用来骗 toB 生意的幌子。

一天一个革了 xxx 的命然后股票市场大震荡一波，实际上他能干的 oai 和 g 家哪个不能干？整天说 25/26/27/28 年要出 agi，实际上专注的 agent 方向是[御三](https://zhida.zhihu.com/search?content_id=770613264&content_type=Answer&match_order=1&q=%E5%BE%A1%E4%B8%89&zhida_source=entity)家里最没有护城河的。oai 和 g 都配谈 agi，唯独你不配。

时间会证明这种喜欢炒作的邪恶公司终究会一败涂地。
    
    
    
    
### 知乎用户 卡卡晚 发表
    
这家公司隔段时间就对中国哈气一次，什么理由都有。不知道创始人受什么刺激了
    
    
    
    
### 知乎用户 第三个号了已经 发表
    
ai 公司哪来的脸讲[数据保护](https://zhida.zhihu.com/search?content_id=770613687&content_type=Answer&match_order=1&q=%E6%95%B0%E6%8D%AE%E4%BF%9D%E6%8A%A4&zhida_source=entity)。

哪个 ai 大厂敢说自己没用未授权的数据训练，现在自家数据被拿了，开始跳出来哭唧唧，没出息。

你不能只在自己赢的时候才无视数据保护。

长远来看我是真的不看好 Claude，创始人很多思维真的很奇葩，这公司早晚让他带沟里去。

很多人说 Claude 创始人是在百度实习被虐成这样的，现在看来百度都比它正常，最起码[李彦宏](https://zhida.zhihu.com/search?content_id=770613687&content_type=Answer&match_order=1&q=%E6%9D%8E%E5%BD%A6%E5%AE%8F&zhida_source=entity)都不会舔着脸说别人偷爬他数据。
    
    
    
    
### 知乎用户 ChubbyPillow​ 发表
    
### **如何看待？当笑话看待。**

来给大家观赏一下红迪 r/SillyTavern 组十分欢乐的的吃瓜群众反应：

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-ab948c21e04b53b5083a7e61e8e88c13_r.jpg%3Fsource%3D1def8aca)

标题：[DeepSeek V4](https://zhida.zhihu.com/search?content_id=770659445&content_type=Answer&match_order=1&q=DeepSeek+V4&zhida_source=entity) 会有接近 [Claude](https://zhida.zhihu.com/search?content_id=770659445&content_type=Answer&match_order=1&q=Claude&zhida_source=entity) Opus 的质量吗？  
帖子正文：真是个好消息！

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-2e1a2a3680970a1a8d96b030a26dc641_r.jpg%3Fsource%3D1def8aca)

评论①：天哪，这些公司盗版书籍、抓取整个互联网，却在另一家公司使用他们的输出作为数据集时大惊小怪，真是太搞笑了

![](https://images.weserv.nl/?url=https%3A//pica.zhimg.com/v2-255802cbe7e04dc77af0f82b411c3956_r.jpg%3Fsource%3D1def8aca)

评论②：“蒸馏可以是合法的”（引用 [Anthropic](https://zhida.zhihu.com/search?content_id=770659445&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 原话）这也太厚颜无耻了吧😭  
“你想绑架我合法偷来的东西”，呵，Deepseek 或任何开源模型能做到（通过 "蒸馏" 炼出优质模型）这样都太棒了

![](https://images.weserv.nl/?url=https%3A//pica.zhimg.com/v2-adf134d3bd378e5c1bc7267ca7bfbcc5_r.jpg%3Fsource%3D1def8aca)

评论③：“Anthropic 窃取了所有人的成果，却厚颜无耻地声称拥有他们从我们这里偷来的东西的所有权。他们想要控制人类历史上积累的知识。他们想要控制计算资源，让我们无法负担在本地使用 AI。Anthropic 是一家邪恶的公司。”

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-3590561964c1f7d257117c89e673a65b_r.jpg%3Fsource%3D1def8aca)

评论④：（经典梗图）

还有 r/Claude 组里的乐子人：

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-eea4db365986f9c08844fff444fbebaa_r.jpg%3Fsource%3D1def8aca)

“DeepSeek：让我解释一下  
Anthropic（指着受版权保护的内容）：你想要绑架我合法偷来的东西！”

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-2b91c936de2e2c956f6969a5bae6a575_r.jpg%3Fsource%3D1def8aca)

“Claude 莫名其妙地因为我用了梯子就封了我的账号，但他居然还放任 2.4 万个假账号进行了 1600 万次请求回应。行吧行吧。”

![](https://images.weserv.nl/?url=https%3A//pica.zhimg.com/v2-1568f1a8ef49b56d7bf009a5da2e02cd_r.jpg%3Fsource%3D1def8aca)

“等等，他们花了多少钱买这些 Tokens？这就像花钱买书来训练模型一样。大家都知道，正确的方法是从盗版网站下载。”

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-1c154a1c0b09bbbc2ba9941d4312fa03_r.jpg%3Fsource%3D1def8aca)

“蒸馏 Anthropic 的模型来训练开源的，那叫做慈善。”

（下面是来自 r/[OpenAI](https://zhida.zhihu.com/search?content_id=770659445&content_type=Answer&match_order=1&q=OpenAI&zhida_source=entity) 的群众）

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-3df04336cd8080e895718376f6a1cdd1_r.jpg%3Fsource%3D1def8aca)

“不！别偷我们的数据！！你们必须用合乎道德的方式，写一份 473 页的隐私和伦理政策，解释为什么免费使用全人类过去的所有成果作为训练数据在道德上是正当的！”

还有一些相关视频油管评论，我就不翻了

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-8ea119ef274d66f97f37874f8da2e975_r.jpg%3Fsource%3D1def8aca)

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-87bf8aa0473b906eb97600ffa0faa337_r.jpg%3Fsource%3D1def8aca)

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-3e76f8cc9eb282a97ad71e51f47a344d_r.jpg%3Fsource%3D1def8aca)

### 中国实验室们 be like：

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/80/v2-7de5fda0133a15828a86c655b7e639a2_1440w.webp%3Fsource%3D1def8aca)
    
    
    
    
### 知乎用户 匼名用户 发表
    
太可怕了

你能定位 [moonshot](https://zhida.zhihu.com/search?content_id=770619606&content_type=Answer&match_order=1&q=moonshot&zhida_source=entity) 的某个员工，是不是也能定位任何一个人，甚至于说会不会有人泄露这些用户信息

你今天能在 “认定为非法的”[api](https://zhida.zhihu.com/search?content_id=770619606&content_type=Answer&match_order=1&q=api&zhida_source=entity) 里投毒，谁知道你明天又会把什么东西认定为非法，我怎么知道自己的 api 是不是被投毒了

刚好评论区有[智慧生命](https://zhida.zhihu.com/search?content_id=770619606&content_type=Answer&match_order=1&q=%E6%99%BA%E6%85%A7%E7%94%9F%E5%91%BD&zhida_source=entity)提到定位

这和闹钟的定位不是一个层级的，闹钟是用手机号 / 身份证来定位，但是 Claude 是根据用户输入信息和公开资料而定位到的。

如果要类比的话，类似于

微信发表声明说，我们通过分析对手企业某高管的聊天记录，做了一个他的画像，包括性格，家庭，资产，近期计划

注意，如果这个高管犯了法，执法机关确实可以直接调取这些记录，就结果来看是一样的

但是这个高管没犯法，而且微信是仅通过分析聊天记录得到的这些信息，那这就非常可怕了
    
    
    
    
### 知乎用户 秋刀鱼  发表
    
[Distillation](https://zhida.zhihu.com/search?content_id=770592197&content_type=Answer&match_order=1&q=Distillation&zhida_source=entity) 是合法的提升模型性能的训练方式，你将 api 开放出来别人也付钱了，为啥不能获取模型的输出结果？只允许你蒸馏别人模型，[Claude 模型](https://zhida.zhihu.com/search?content_id=770592197&content_type=Answer&match_order=1&q=Claude%E6%A8%A1%E5%9E%8B&zhida_source=entity)初版没有蒸馏过 [GPT](https://zhida.zhihu.com/search?content_id=770592197&content_type=Answer&match_order=1&q=GPT&zhida_source=entity) 吗？还是只有美国人可以开发模型，别的国家都不可以？Antropic 公司就有种族歧视的公司，从 ceo 开始就反华，本质上就是霸权主义，典型的民粹主义思想，只能美国领先，别人都不行！
    
    
    
    
### 知乎用户 AI 解码师​ 发表
    
从背景开始说吧，2 月 24 日（就是昨天），**[Anthropic](https://zhida.zhihu.com/search?content_id=770601893&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity)** 发布报告，直接点名 **[DeepSeek](https://zhida.zhihu.com/search?content_id=770601893&content_type=Answer&match_order=1&q=DeepSeek&zhida_source=entity)**、**[月之暗面](https://zhida.zhihu.com/search?content_id=770601893&content_type=Answer&match_order=1&q=%E6%9C%88%E4%B9%8B%E6%9A%97%E9%9D%A2&zhida_source=entity)**（Moonshot AI）和 **[MiniMax](https://zhida.zhihu.com/search?content_id=770601893&content_type=Answer&match_order=1&q=MiniMax&zhida_source=entity)** 三家中国 AI 公司，声称它们通过超过 **2.4 万个虚假账号**，累计发起约 **1600 万次对话交互**，系统性地从 **[Claude 模型](https://zhida.zhihu.com/search?content_id=770601893&content_type=Answer&match_order=1&q=Claude%E6%A8%A1%E5%9E%8B&zhida_source=entity)**中提取核心能力。

三家的操作各有侧重：DeepSeek 约 15 万次调用，主攻基础逻辑优化和安全审查规避；月之暗面 340 万次，集中在计算机视觉和数据分析；MiniMax 最猛，1300 万次交互，而且几乎是 Claude 新版本一上线就同步启动提取。目标能力包括**代理推理**、**工具协作**和**代码生成**——全是 Claude 最拿得出手的东西。

* * *

报告发出来没几个小时，**马斯克**就在社交媒体上开怼了。原话大意是：” 他们竟然敢偷 Anthropic 从人类程序员那里偷来的东西？”

在老马看来——**Anthropic 自己训练 Claude 的数据来源同样充满争议**。大规模爬取互联网内容、未经授权使用受版权保护的书籍，被诉讼之后才掏出数十亿美元和解。[Gergely Orosz](https://zhida.zhihu.com/search?content_id=770601893&content_type=Answer&match_order=1&q=Gergely+Orosz&zhida_source=entity) 也公开喊话，说 Anthropic 不能两头占便宜，一边用别人的内容训练模型赚钱，一边指责别人从自己模型里提取知识。

所以我们就看到了一个非常搞笑的现象：**指控方和被指控方，本质上都在做同一件事——从别人那里大规模提取知识资产，然后商业化变现。**区别只在于，一个用的是互联网上人类创作者的内容，一个用的是闭源模型的 API 输出。

* * *

Anthropic 在**美国政府正激烈讨论对华 [AI 芯片出口管制](https://zhida.zhihu.com/search?content_id=770601893&content_type=Answer&match_order=1&q=AI%E8%8A%AF%E7%89%87%E5%87%BA%E5%8F%A3%E7%AE%A1%E5%88%B6&zhida_source=entity)政策**的节骨眼上放出来这份报告。而且报告里有一段话很有意思，大意是：这种规模的蒸馏行为需要先进芯片的算力支撑，因此加强芯片出口管制是合理且必要的。

把这段话翻译成人话就是：你看，中国公司在偷我们的模型能力，所以美国政府应该卡死芯片供应。

所以这可能就不是一份纯粹的技术安全报告，或许大概可能是一份**政策游说文件**。Anthropic 作为一家商业公司，在这个时间点公开点名三家中国企业，配合的是美国国内关于 **AI 出口管制**的政策辩论。它需要一个足够有冲击力的案例来证明” 中国 AI 威胁论”，而蒸馏事件恰好提供了这个素材。

* * *

再说回蒸馏**，[知识蒸馏](https://zhida.zhihu.com/search?content_id=770601893&content_type=Answer&match_order=1&q=%E7%9F%A5%E8%AF%86%E8%92%B8%E9%A6%8F&zhida_source=entity)**（Knowledge Distillation）在技术上是完全正当的方法，[Hinton](https://zhida.zhihu.com/search?content_id=770601893&content_type=Answer&match_order=1&q=Hinton&zhida_source=entity) 2015 年提出来的时候，目的是把大模型的知识压缩到小模型里，降低推理成本。学术界和工业界天天在用。

但问题出在边界上。当你蒸馏的对象是自己训练的模型，没人会说什么；当你蒸馏的对象是竞争对手的闭源商业模型，就会有人找你了。

不过这个边界到底在哪里，目前全球没有任何一个法律体系给出过清晰的定义。你通过 API 调用获取模型输出，然后用这些输出作为训练数据——这算不算” 窃取”？从 Anthropic 的服务条款来看，肯定违反了用户协议。但从法律层面，**模型输出的版权归属**至今仍是一个未解决的灰色地带。

* * *

在这个行业混了这么多年，看到的一个规律是：**每一次技术领先方开始强调” 规则” 和” 道德” 的时候，往往是它感受到追赶压力的时候。**

2023 年 OpenAI 还在到处宣传开放精神，2024 年就开始封锁 API、限制访问。Anthropic 也一样，之前从来没公开讨论过蒸馏问题，现在突然拿出详细数据点名——不是因为蒸馏是新现象，而是因为中国 AI 实验室的追赶速度让它们感到了实质性威胁。

但我也不是因此就替被点名的三家公司辩护。**用 2.4 万个假账号进行 1600 万次交互提取，这个行为本身确实不体面。**如果数据属实，说明这些公司在技术追赶的过程中选择了一条捷径，而这条捷径在任何商业伦理框架下都很难站住脚。

真正让我不舒服的是这件事被讨论的方式。国内一部分声音在说” 这是美国打压”，国外一部分声音在说” 就是偷”。两边都在把一个复杂的**技术伦理和产业竞争**问题，简化成非黑即白的叙事。

实际情况是：**整个 AI 产业的数据获取和知识产权规则还处于蛮荒状态**，谁都不干净，只是被曝光的时间和方式不同。Anthropic 用别人的版权内容训练模型，中国公司用 Anthropic 的模型输出训练自己的模型——这条链路上的每一环都有问题，但都在站在道德制高点上审判别人。

挺没意思的，但这就是现状。
    
    
    
    
### 知乎用户 GuGuJi 发表
    
Dario 特有的看谁都要害他

越发怀疑他在百度当研究员的时候，艳红到底对他注入了些什么，他到现在都不太正常
    
    
    
    
### 知乎用户 小肥羊 发表
    
结合高赞的说法，意味着 [Anthropic](https://zhida.zhihu.com/search?content_id=770623094&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 可以：

*   获取用户数据，并进行分类
*   针对性的修改模型能力

如果是这样，Anthropic 就有能力做出某些攻击：

*   针对使用 [vibe coding](https://zhida.zhihu.com/search?content_id=770623094&content_type=Answer&match_order=1&q=vibe+coding&zhida_source=entity) 且把 code review 都交给 AI 的用户，可以直接在用户的系统里面留下后门
*   针对使用了 OpenClaw 这样高权限框架的用户，可以执行一些高危操作，获取用户敏感数据

现在很少能看到关于利用 [LLM](https://zhida.zhihu.com/search?content_id=770623094&content_type=Answer&match_order=1&q=LLM&zhida_source=entity) 进行攻击的研究，但很容易想到，现在这些 agent 工具中漏洞实在太多。
    
    
    
    
### 知乎用户 么西么西 发表
    
懂了，以后就用 [minimax](https://zhida.zhihu.com/search?content_id=770617322&content_type=Answer&match_order=1&q=minimax&zhida_source=entity) 的 API。

这效果，好像是比亚迪给吉利打广告了。
    
    
    
    
### 知乎用户 红烧奥特曼 发表
    
在我这里，[Anthropic](https://zhida.zhihu.com/search?content_id=770621770&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 这个名字就带有原罪: 你是啥玩意，敢自称人类，敢代表人类？你们是人类的，那我们是什么的？

对于这种自诩代表人类代表正义代表 ai 宪法的玩意，除了自恋狂这个最宽容的描述，还有什么形容词？

(closeai 至少前几年真 open 过)
    
    
    
    
### 知乎用户  西门灌 发表
    
我经常对正版侠讲一句话，你觉得它盗版挣钱，那么你就去盗盗版，不更挣钱吗？

同理，你说 [DeepSeek](https://zhida.zhihu.com/search?content_id=770674103&content_type=Answer&match_order=1&q=DeepSeek&zhida_source=entity) 靠蒸馏才牛逼，那你搞个新 AI 去蒸馏 DeepSeek，不就更牛逼了吗？
    
    
    
    
### 知乎用户 悠铀 发表
    
笑死了，看看马斯克是怎么评价这事的

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-dddc148e5192f7c1148c12f58f360700_r.jpg%3Fsource%3D1def8aca)

“是的，但我们并不像 [Anthropic](https://zhida.zhihu.com/search?content_id=770623721&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 那样自以为是、道貌岸然和虚伪。”
    
    
    
    
### 知乎用户  朱耶伽罗 发表
    
这个很可能跟另一件事情有关系，就是 [Anthropic](https://zhida.zhihu.com/search?content_id=770777826&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 最近和美国国防部的争端。

[赫格塞斯](https://zhida.zhihu.com/search?content_id=770777826&content_type=Answer&match_order=1&q=%E8%B5%AB%E6%A0%BC%E5%A1%9E%E6%96%AF&zhida_source=entity)向 [A 社](https://zhida.zhihu.com/search?content_id=770777826&content_type=Answer&match_order=1&q=A%E7%A4%BE&zhida_source=entity)发出最后通牒：在周五之前要 A 社解除限制让 ai" 用于所有合法的军事目的”。A 社之前对这个要求始终抗拒，答应了用模型做导弹防御和网络攻击防御，但是这次 [DoD](https://zhida.zhihu.com/search?content_id=770777826&content_type=Answer&match_order=1&q=DoD&zhida_source=entity) 的要求是：赶快全做，不然你的所有合同都没了。

[https://www.nbcnews.com/tech/security/anthropic-pentagon-us-military-can-use-ai-missile-defense-hegseth-rcna260534](https://link.zhihu.com/?target=https%3A//www.nbcnews.com/tech/security/anthropic-pentagon-us-military-can-use-ai-missile-defense-hegseth-rcna260534)

导弹防御和网络攻击防御这两个可以简单外延的项目就先不说了，A 社和美国防部还有别的争端：是否使用其模型用于国内大规模监视，和是否使用其模型进行武器的自主目标决定。这俩也吵得不可开交，但是消息源说，国防部想要的还不止这两个。

[https://www.bbc.com/news/articles/cjrq1vwe73po](https://link.zhihu.com/?target=https%3A//www.bbc.com/news/articles/cjrq1vwe73po)

除此以外 A 社和情报机构也有很多合作。

* * *

最善良的 AI 公司…… 额

A 社的创立很大程度上就是 [Amodei 兄妹](https://zhida.zhihu.com/search?content_id=770777826&content_type=Answer&match_order=1&q=Amodei%E5%85%84%E5%A6%B9&zhida_source=entity)不满 OpenAI 在道德方面的一些忽视——至少他们这么对外说的。

几个创始人里面罕见的有两个很文科的存在：[Daniela Amodei](https://zhida.zhihu.com/search?content_id=770777826&content_type=Answer&match_order=1&q=Daniela+Amodei&zhida_source=entity), Dario 的妹妹， UC Santa Cruz ，Bachelor of Arts in English Literature， 管 safety 和 policy， 和一个前记者 [Jack Clark](https://zhida.zhihu.com/search?content_id=770777826&content_type=Answer&match_order=1&q=Jack+Clark&zhida_source=entity), University of East Anglia, BA in English and Creative Writing. 管 policy。

很快他们又弄来了另一个重量人物 [Amanda Askell](https://zhida.zhihu.com/search?content_id=770777826&content_type=Answer&match_order=1&q=Amanda+Askell&zhida_source=entity), NYU phD in Philosophy. 也就是 “宪法 AI” 这个概念的鼻祖。 这个公司从一开始就带着浓浓的价值观味道，而且是英美学院价值观那种味道，这就很好解释他们的一些态度了。

A 社是尤其文科的一个存在 ---- 此处文科是最纯最纯的那种文科。

到了最近这个 AI、尤其是 A 社引领的一些方向开始对经济有实打实冲击的时候，Amodei 发表的价值观文章仍然对 AI 赋能资本主义这最残酷最急迫的一面语焉不详，反而仍然揪着东大不放。然后又狂砍国防和情报大单。

这就是很典型民主党形状的又\_\_又\_\_\_. 谁叫他们最近是资本市场的宠儿呢，见的多啦，吃饭嘛不寒碜，价值观遇见美帝政府，不就是这个形状吗。虽然你凹的姿势比较出格，我们看着只是呵呵一下。

* * *

…… 但是最近美国防部开始嫌他们这样还太端着、不够放下身段，这就有意思了。

英美知识分子遇到社会生产时候的拧巴就暴漏无遗了。你看，在 2026 年，哪怕不是一根筋，也能收获两头堵（捂脸）

估计 A 社内部现在也是冲突重重，理想主义者估计已经被招进来了大批大批，但是看领导的样子，看更可能多是集中在安全和政策部门的文科人，即使 Dario 本人面对 DoD 的极限施压愿意松口（当老板戴上资本面具了，应该会松），估计也看不到什么第二次教会大分裂（狗头）

遇到压力的时候该怎么办呢？祖传取偿于东！1，2，3，

CHINA！

我还要看着它们以后凹出来的是什么姿势呢。
    
    
    
    
### 知乎用户 海哥 发表
    
提醒一下，美国一直在蒸馏中国的基础教育和高等教育
    
    
    
    
### 知乎用户  Snorri​ 发表
    
[Anthropic](https://zhida.zhihu.com/search?content_id=770608796&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 有什么公信力可言吗？私设公堂想敲诈勒索抹黑对手，不正当竞争。首先解释一下自己意图非法获取、刺探并暴露用户隐私信息吧。
    
    
    
    
### 知乎用户 Saki 发表
    
[Anthropic](https://zhida.zhihu.com/search?content_id=770612391&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 在 twitter 被喷麻了。

不过说到隐私，你们真的以为有隐私啊？大公司有点官僚病的，其实对隐私的保护还可以，看不到你们的原文，只能看到 [embedding](https://zhida.zhihu.com/search?content_id=770612391&content_type=Answer&match_order=1&q=embedding&zhida_source=entity)。很多公司都是有人对着你的使用记录来看看有什么用户场景来优化的（没有匿名的那种哦），即使你填了一堆不让泄露信息。
    
    
    
    
### 知乎用户 厉害的潇潇​ 发表
    
张三出去偷了一份某国宴大厨的绝密菜谱，然后开了餐馆，靠偷来的菜谱炒菜。

我觉得菜不错，我潜入他家把菜谱偷出来，我这也叫偷。但我没有这么做，我公开的去他家餐馆，每天花自己的钱点喜欢的菜，天天都点，三餐都吃，终于自己品尝多了之后悟出了配料和做法。

然后他说我偷他的菜谱。
    
    
    
    
### 知乎用户 十七零七​ 发表
    
试图跟 A 畜讲道理的，都是不知道 A 畜的尿性和克劳德的统治力。

克劳德凭什么敢在所有 ai 里 [api 调用](https://zhida.zhihu.com/search?content_id=770669972&content_type=Answer&match_order=1&q=api%E8%B0%83%E7%94%A8&zhida_source=entity)最贵？

A 畜凭什么敢随便封号？

外国大厂从游戏到科技领域都是这样的：人家的产品真能打，所有的不做人都是建立在产品能打的基础上。

所以大伙为什么将 [ds](https://zhida.zhihu.com/search?content_id=770669972&content_type=Answer&match_order=1&q=ds&zhida_source=entity) 视为全村的希望？

肘击，必须狠狠肘击。

ds 你 V4 赶紧出啊！你赶紧实装 [engram](https://zhida.zhihu.com/search?content_id=770669972&content_type=Answer&match_order=1&q=engram&zhida_source=entity) 啊！你要是搞出来了，我给外国 ai 送多少钱，给你双倍！
    
    
    
    
### 知乎用户 验证主义​ 发表
    
这份公告更多是政治性的 而非技术性的

美国战争部长皮特 · 赫格塞思已经要求 [Anthropic 公司](https://zhida.zhihu.com/search?content_id=770612823&content_type=Answer&match_order=1&q=Anthropic%E5%85%AC%E5%8F%B8&zhida_source=entity)首席执行官达里奥 · 阿莫迪 (Dario Amodei) 于 2026 年 2 月 24 日上午前往五角大楼会面

在会面结束后 Anthropic 发布了这个公告

这份公告更多是政治性的 而非技术性的
    
    
    
    
### 知乎用户  X 骑士 发表
    
先不说这只是他的一面之词，没拿出证据。

根据美国法院自己的说法:[AI 生成](https://zhida.zhihu.com/search?content_id=770603465&content_type=Answer&match_order=1&q=AI%E7%94%9F%E6%88%90&zhida_source=entity)的都没有版权，蒸馏完全不侵犯版权，是合法行为。

而且你自己不是在蒸馏别的 ai 数据吗？

![](https://images.weserv.nl/?url=https%3A//pica.zhimg.com/v2-240f65c8b718247ef2d82a177b244f77_r.jpg%3Fsource%3D1def8aca)

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-d0f4354e2b47fdaacf7ec3945bd8a1e5_r.jpg%3Fsource%3D1def8aca)

![](https://images.weserv.nl/?url=https%3A//pica.zhimg.com/v2-05c715b617dba7ad4d7e989cb92450f2_r.jpg%3Fsource%3D1def8aca)

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-79adff3d6d34c2bfed569f64946ea755_r.jpg%3Fsource%3D1def8aca)
    
    
    
    
### 知乎用户 殖人的冶碟 发表
    
虽然我也经常用 Claude，但这玩意儿确实是最反汉男的 AI。性能最强，但是价值观最有问题。

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-fe83eda552381e3532fb1881b8c3a5b4_r.jpg%3Fsource%3D1def8aca)
    
    
    
    
### 知乎用户 chengxd 达达​ 发表
    
有人说 Anthropic 的爬虫也在蒸馏全网数据，所以蒸馏别的模型无可厚非。巧的是爬虫问题，国内大模型公司是更没有资格拿出来说事的。

OpenAI Anthropic 都在官网公布了自己的 crawler，那么请问国内大模型公司有在官网公开过自己的爬虫吗？Kimi、Minimax、智谱 GLM，官网一个都没有吧。

openai 和 anthropic 的爬虫，分为训练爬虫（[GPT Bot](https://zhida.zhihu.com/search?content_id=770619833&content_type=Answer&match_order=1&q=GPT+Bot&zhida_source=entity) 和 [Claude Bot](https://zhida.zhihu.com/search?content_id=770619833&content_type=Answer&match_order=1&q=Claude+Bot&zhida_source=entity)）、搜索爬虫（[OAI SearchBot](https://zhida.zhihu.com/search?content_id=770619833&content_type=Answer&match_order=1&q=OAI+SearchBot&zhida_source=entity) 和 [Claude-SearchBot](https://zhida.zhihu.com/search?content_id=770619833&content_type=Answer&match_order=1&q=Claude-SearchBot&zhida_source=entity)）、代表用户读取网页的爬虫（[ChatGPT-User](https://zhida.zhihu.com/search?content_id=770619833&content_type=Answer&match_order=1&q=ChatGPT-User&zhida_source=entity) 和 [Claude-User](https://zhida.zhihu.com/search?content_id=770619833&content_type=Answer&match_order=1&q=Claude-User&zhida_source=entity)）。OpenAI 还公布了爬虫 IP 地址段防止别人冒充。

我自己的网站，还真能看到他们的爬虫。Anthropic 的爬虫就频繁爬取 robots 协议，以确认站长是否屏蔽。

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-ecdb8c398b258bcb1774216b27e8917a_r.jpg%3Fsource%3D1def8aca)

如果你对爬虫不满，可以根据请求头屏蔽，可以屏蔽 IP 段，可以用 robots 协议约束，可以用带有自己域名的邮箱发邮件给 OpenAI 和 Anthropic，请求移除。

那么如何制约国内大模型公司的爬虫呢？当然我在网站也很少看到国内大模型公司的爬虫请求头。

互联网开源的 Common Crawl 数据集质量很低，更新频次低。大量中小网站只收录了一个首页，想要高质量获取数据必须以他为基础用自有爬虫进行延伸爬取，从而实现更全的覆盖。

国内大模型公司的爬虫很少，要么是你压根不做全网数据的抓取，要么是大量依赖 common Crawl，要么蒸馏别人的数据。当然还有可能是请求头隐藏了自己的真实爬虫身份。

官网爬虫公示：

[OpenAI WebCrawler](https://link.zhihu.com/?target=https%3A//developers.openai.com/api/docs/bots/)[Anthropic Web Crawler](https://link.zhihu.com/?target=https%3A//support.claude.com/en/articles/8896518-does-anthropic-crawl-data-from-the-web-and-how-can-site-owners-block-the-crawler)

原问题已经解散，所以这个回答说点不一样的。感兴趣的还可以去看。

[如何看待 Anthropic 指控 DeepSeek、Kimi 和 MiniMax 「蒸馏攻击」其模型?](https://www.zhihu.com/question/2009538062087123054/answer/2009580107166131427?share_code=tMYwVo6Ti9BR&utm_psn=2009892053295850743)
    
    
    
    
### 知乎用户  二氯亚砜 发表
    
![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-de8b3dbef725e0c791d2a1ac9048c03a_r.jpg%3Fsource%3D1def8aca)

你是信 [nature 审稿人](https://zhida.zhihu.com/search?content_id=770657969&content_type=Answer&match_order=1&q=nature%E5%AE%A1%E7%A8%BF%E4%BA%BA&zhida_source=entity)还是信一帮自爆式辟谣的运营杀良冒功？
    
    
    
    
### 知乎用户 巴社​​ 发表
    
怎么之前那个问题不能分享，那再说一遍把：

如果你是一名正在使用 [deepseek](https://zhida.zhihu.com/search?content_id=770636090&content_type=Answer&match_order=1&q=deepseek&zhida_source=entity)，或者 [kimi](https://zhida.zhihu.com/search?content_id=770636090&content_type=Answer&match_order=1&q=kimi&zhida_source=entity) 这些模型，又或者干脆是国外模型 Claude， gemini 啊或者 [gpt](https://zhida.zhihu.com/search?content_id=770636090&content_type=Answer&match_order=1&q=gpt&zhida_source=entity) 这些的个人用户，你当然有资格抱怨 “哇他们的新模型是不是又吃了 XX，说话全都一个味”“能不能搞点自己的玩意”“能不能有点审美，不要什么数据都吃好吗？”

你厂商是没有资格的，任何一个 [Ilm 厂商](https://zhida.zhihu.com/search?content_id=770636090&content_type=Answer&match_order=1&q=Ilm%E5%8E%82%E5%95%86&zhida_source=entity)一点资格都没有。蒸馏这玩意是蹭着人类概念里的版权才是可认知的议题，而首先你 A÷ 都不需要蹭，宝宝你真的打过版权官司吃罚款了。其次现在模型的训练语料一个二个都讲不清楚，哦我用你个模型的二道贩子还不知道有没有版权的输出是不道德是违法，你直接用肯定有版权的人类资料是正义的是美国安全的，别逗大家笑

另外说点看起来无关但是有关的东西——闭源御三家，A 处是最处的那一类，成天炒作那个逼安全不知道干什么，打得过 [oai](https://zhida.zhihu.com/search?content_id=770636090&content_type=Answer&match_order=1&q=oai&zhida_source=entity) 吗闹麻了（虽然 oai 也是安全上极其畜的一类），对散户个体用户又是最差的一类，Pro 订阅额度别名其他家的免费额度，一开始打着无限制使用的 MAX 订阅玩起了周限制的把戏，用起来极其便秘，而且使用极其不稳定。他说自己审阅了聊天记录真的一点都不奇怪，早在之前官网某些特定的聊天记录就会消失了，只是他居然敢发大字报说出来，还是很有勇气的。A 处整个公司就是兼具又当又立的美德的
    
    
    
    
### 知乎用户  wangleineo​​​ 发表
    
关于此事看到最好笑的评论是：

**我六岁的儿子每天都问我各种奇怪的问题，今天我才明白，他在对我进行[蒸馏攻击](https://zhida.zhihu.com/search?content_id=770639212&content_type=Answer&match_order=1&q=%E8%92%B8%E9%A6%8F%E6%94%BB%E5%87%BB&zhida_source=entity)！**

要问这个指控是不是捏造，我觉得大概是确有其事。业界公司互相蒸馏早就是心照不宣的秘密，[Anthropic](https://zhida.zhihu.com/search?content_id=770639212&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 敢拍着胸脯说自己从来没有蒸馏过其他的模型吗？根据网友的实验，各种模型都出现过自我认知错乱的情况，所以，谁也别指责谁。

而且，就算是偷，三家偷来也不是自己牟利，全都[开源免费](https://zhida.zhihu.com/search?content_id=770639212&content_type=Answer&match_order=1&q=%E5%BC%80%E6%BA%90%E5%85%8D%E8%B4%B9&zhida_source=entity)贡献给全世界了。这不是劫富济贫的侠盗行为吗？现代罗宾汉啊！

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-34efc693bad9b2d81d741a6687a94006.jpg%3Fsource%3D25ab7b06)

Jian Yang and Amodei

Anthropic 的公关部门太不专业了，竟然认为自己是正义的一方，没有预料到舆论的反噬。作为一个靠爬取全网数据起家的公司，去年还因为[书籍版权问题赔偿了 15 亿美元](https://zhuanlan.zhihu.com/p/1948523226318762449)，他们是怎么想到自己能站上版权的道德高地的？

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-8c7bc9d8797602991e35822397081d39_r.jpg%3Fsource%3D1def8aca)

这件事，Anthropic 不是不可以说。但是不应该剑拔弩张的说，应该换一种口吻，就容易接受得多。有人问 [Claude 模型](https://zhida.zhihu.com/search?content_id=770639212&content_type=Answer&match_order=1&q=Claude%E6%A8%A1%E5%9E%8B&zhida_source=entity)写一个公关稿，感觉写的相当好：

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-11429febd4d345d2ee64f050fb6cb65f_r.jpg%3Fsource%3D1def8aca)

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-fc77b429b185ab2f25ca307c52e16d9a_r.jpg%3Fsource%3D1def8aca)

如果公关稿这样写，不但不伤好感度，而且有一种傲立孤峰的气质。这才叫品牌建设。

Anthropic，你们家模型真的挺通人性的，你们自己也用用呢。
    
    
    
    
### 知乎用户 猫骑士 发表
    
这种傻福就属于政治敏感性不强拎不清的，在中国已经对美国和日本实物贸易进行大规模制裁的当下，还像吉娃娃那样乱咬乱哈气，信不信等制裁服贸的时候 [ai 领域](https://zhida.zhihu.com/search?content_id=770700796&content_type=Answer&match_order=1&q=ai%E9%A2%86%E5%9F%9F&zhida_source=entity)就拿这货祭旗？
    
    
    
    
### 知乎用户 八舞耶俱矢 发表
    
来自亚洲的布尔什维克和罗宾汉们只不过将原本属于人类的权重，重新分配给人类而已。
    
    
    
    
### 知乎用户 已末 发表
    
显然是因为 A 社要推动美国政府出手，禁止美欧日韩商业企业采用中国产[开源 AI 模型](https://zhida.zhihu.com/search?content_id=770654908&content_type=Answer&match_order=1&q=%E5%BC%80%E6%BA%90AI%E6%A8%A1%E5%9E%8B&zhida_source=entity)。

几个大模型厂之中，A 社主打 B 端企业用户， [国模](https://zhida.zhihu.com/search?content_id=770654908&content_type=Answer&match_order=1&q=%E5%9B%BD%E6%A8%A1&zhida_source=entity)对 A 社冲击最大。 B 端企业都有很强的动力搞自主掌控的 AI， 拿开源的国模 + 自己掌控的[私域数据微调](https://zhida.zhihu.com/search?content_id=770654908&content_type=Answer&match_order=1&q=%E7%A7%81%E5%9F%9F%E6%95%B0%E6%8D%AE%E5%BE%AE%E8%B0%83&zhida_source=entity)是最理想的模式。 国模如果能无障碍入美，会直接卡死 A 社的生命线。

商业模式来看，A 社如果推不动美国政府出手，借政治力量制造一片垄断空间，未来只能是被有完整业务线的其他大厂合并。
    
    
    
    
### 知乎用户 疯死沃 发表
    
![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-540e4bd025bfa31bf2df3a776caf71cb_r.jpg%3Fsource%3D1def8aca)

![](https://images.weserv.nl/?url=https%3A//pica.zhimg.com/v2-715ca65fc3b28d0537d8eba57476db1a_r.jpg%3Fsource%3D1def8aca)

![](https://images.weserv.nl/?url=https%3A//pica.zhimg.com/v2-a6876214e8962114980b71942f83edb7_r.jpg%3Fsource%3D1def8aca)

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-5c7906ee545da11395bb1b476c738ba6_r.jpg%3Fsource%3D1def8aca)

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-3a022120856828f1b327877274ffba2f_r.jpg%3Fsource%3D1def8aca)

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-59f1c20689752a1a1e9d4d7b336367ba_r.jpg%3Fsource%3D1def8aca)

当然，一到这些时候，某些人立即就 “冷静” 下来，并且可以 “客观” 地分析了：

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-0f29e4fccb77563efbfae706d61829a9_r.jpg%3Fsource%3D1def8aca)

当然也有立即提出这里面存在双标的：

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-30224a4ae326b81c1698e8a379eb6cec_r.jpg%3Fsource%3D1def8aca)

这真是很有意思。
    
    
    
    
### 知乎用户 安定医院刘主任 发表
    
物理手段打破赛博封建迷信：

：来，看看这一家公司（[anthropic](https://zhida.zhihu.com/search?content_id=770624021&content_type=Answer&match_order=1&q=anthropic&zhida_source=entity)），这位能当上 [LLM](https://zhida.zhihu.com/search?content_id=770624021&content_type=Answer&match_order=1&q=LLM&zhida_source=entity) 第一吗？

：我来看看。啧啧啧啧啧啧啧啧啧啧，这面相不太好，往 [GDPR](https://zhida.zhihu.com/search?content_id=770624021&content_type=Answer&match_order=1&q=GDPR&zhida_source=entity) 枪口撞的 LLM 企业，我看是没戏了。

：请您再仔细看看（沉声）

：这个没有必要，卡果卡。

：牙医 shake it！再给老子好好的看看！\*\*\*！敢说这公司面相差！

：你看 LLM 企业不要撅人啊，这个、这个、你是一个一个……（省略 500 字）……zoom 联机，360 度转一圈。
    
    
    
    
### 知乎用户 空门 nullgate 发表
    
蒸馏的数据不是 [Anthropic](https://zhida.zhihu.com/search?content_id=770593607&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 的模仿者自己搞的，而是我这种贫穷的爱好者提供的。当我享受着近乎免费的算力时，我的数据被层层盘剥整合转卖。但是这里面最大的数据收割者是 [Amazon](https://zhida.zhihu.com/search?content_id=770593607&content_type=Answer&match_order=1&q=Amazon&zhida_source=entity)。Anthropic 为什么不敢控诉 Amazon？

不得不说资本主义真的有可取之处，有钱真的可以为所欲为，[Hyperscaler](https://zhida.zhihu.com/search?content_id=770593607&content_type=Answer&match_order=1&q=Hyperscaler&zhida_source=entity) 们收割互联网上的文本和视频，开源软件为码农敲响了丧钟。我这种穷鬼只能出卖自己的数据，反正都是模型产生的垃圾数据，为可持续的模型崩塌提供正反馈。成瘾以后的前码农表示，写代码是不可能写代码的，甚至写 spec 都是扯淡，我连需求都让数字访客自己写。而且我要求一次只给我两个选择，三个我都觉得脑壳痛，两个选择还可以扔硬币啊！

有没有懂行的律师愿意法律援助我，代表（前）码农们对 Anthropic 提起集体诉讼，由于滥用 [Opus 4.x](https://zhida.zhihu.com/search?content_id=770593607&content_type=Answer&match_order=1&q=Opus+4.x&zhida_source=entity) 造成了大脑皮层不可逆的退化。

（迫真）
    
    
    
    
### 知乎用户 三只鱼 发表
    
有意思，以前讨论的是是否蒸馏，现在讨论的是蒸馏是否合法。
    
    
    
    
### 知乎用户 肥嘟嘟左卫门​ 发表
    
它公告自己就说了，[蒸馏](https://zhida.zhihu.com/search?content_id=770611233&content_type=Answer&match_order=1&q=%E8%92%B8%E9%A6%8F&zhida_source=entity)是合法的。只是这个规模和来源违反了它的服务条款和地域限制。

那你就拦着呗，封禁这些用户。有什么大不了的
    
    
    
    
### 知乎用户 流年忘返 发表
    
无能狂怒罢了，它的优势今年就能被[开源模型](https://zhida.zhihu.com/search?content_id=770620741&content_type=Answer&match_order=1&q=%E5%BC%80%E6%BA%90%E6%A8%A1%E5%9E%8B&zhida_source=entity)打掉
    
    
    
    
### 知乎用户  Z motryx 发表
    
说明目前美国基于大语言模型这波生成式 “人工智能” 的泡泡已经系统性地走到要破的阶段。

最近半年，随着[甲骨文](https://zhida.zhihu.com/search?content_id=770628948&content_type=Answer&match_order=1&q=%E7%94%B2%E9%AA%A8%E6%96%87&zhida_source=entity)股价腰斩、皮衣黄出尔反尔、[scam altman](https://zhida.zhihu.com/search?content_id=770628948&content_type=Answer&match_order=1&q=scam+altman&zhida_source=entity) 和 [openai](https://zhida.zhihu.com/search?content_id=770628948&content_type=Answer&match_order=1&q=openai&zhida_source=entity) 被反复鞭尸、马斯克硬把 [xAI](https://zhida.zhihu.com/search?content_id=770628948&content_type=Answer&match_order=1&q=xAI&zhida_source=entity) 和 [SpaceX](https://zhida.zhihu.com/search?content_id=770628948&content_type=Answer&match_order=1&q=SpaceX&zhida_source=entity) 往一块捆绑，其实大的趋势已经很明显了，但很多人没意识到的是，当前华尔街一直试图将这个泡沫具象到 OpenAI 这一家公司上，营造一种不是生成式 AI 这条技术线路有问题，而是 scam altman 和 openai 掉队了。

[anthropic](https://zhida.zhihu.com/search?content_id=770628948&content_type=Answer&match_order=1&q=anthropic&zhida_source=entity) 被塑造成 “openai 的死对头”，是 openai 叛出的一小群道德水平和技术水平更高的人，建立的道德水平和技术水平更高的，人工智能的未来之星。它一定程度上就是庄家预设的二线阵地、是断掉 openai 的尾之后，打算用来留住大量资金的投资标的。

可是，它也在鼓吹通过更严苛的法律、管理手段，也就是盘外招，对中国人工智能团队进行压制了，换句话说，它们同样不得不承认，按部就班地搞研发，肯定赢不了，至少不会产生 “超额利润”。

去掉 “愿景”，从用户兜里一块一块地挣钱，最终基于电力成本定价，这就回归到了一般制造业，而在这个层面，它美国毫无胜算。

anthropic 聊的这手 “知识产权”，其实跟前几天迪士尼就 seedance 2.0 提出的“知识产权” 诉讼是一码事儿：“此山是我开，此树是我栽，要想过此路，留下买路财。在下混世魔王，你们快快留下钱财”。

一切矛盾转抢劫，平凡的日耳蛮，平凡的海洋民族性，福特号顷刻三遗矢，尚能饭否？
    
    
    
    
### 知乎用户 Aurelian XVII 发表
    
我的建议是别太傲慢了。

目前 [AI](https://zhida.zhihu.com/search?content_id=770637908&content_type=Answer&match_order=1&q=AI&zhida_source=entity) 干活的中国人实在太多，等这些粉毛头像吃鱼丸的[小南梁](https://zhida.zhihu.com/search?content_id=770637908&content_type=Answer&match_order=1&q=%E5%B0%8F%E5%8D%97%E6%A2%81&zhida_source=entity)程序员不在你家了看你怎么办。

又不是你一家。
    
    
    
    
### 知乎用户 墨 m​​ 发表
    
[硅谷](https://zhida.zhihu.com/search?content_id=770668593&content_type=Answer&match_order=1&q=%E7%A1%85%E8%B0%B7&zhida_source=entity)这群新右翼真是恶臭的怪味冲天，上一辈科技巨头受[左翼](https://zhida.zhihu.com/search?content_id=770668593&content_type=Answer&match_order=1&q=%E5%B7%A6%E7%BF%BC&zhida_source=entity)思潮影响好歹还愿意装装人样
    
    
    
    
### 知乎用户 文武双全王司徒  发表
    
[Anthropic](https://zhida.zhihu.com/search?content_id=770665581&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 可以对于使用者开盒，然后对于它认为合适的 [API](https://zhida.zhihu.com/search?content_id=770665581&content_type=Answer&match_order=1&q=API&zhida_source=entity) 定向投毒。

今天说你蒸馏，明天说你萃取，后天都可以给你上莫须有了。牛逼，真的牛逼。
    
    
    
    
### 知乎用户 饥荒新手 发表
    
2024 年 11 月，[Anthropic](https://zhida.zhihu.com/search?content_id=770610280&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 和 [Palantir](https://zhida.zhihu.com/search?content_id=770610280&content_type=Answer&match_order=1&q=Palantir&zhida_source=entity) 以及亚马逊云签了一份合同，把 Claude 部署到美国情报和国防机构的机密网络中。

《华尔街日报》报道，Claude 在美军突袭委内瑞拉被使用了。

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-1536bdc6ececaad2107cdb7b86e1fbff_r.jpg%3Fsource%3D1def8aca)
    
    
    
    
### 知乎用户 猪鼻蛇 发表
    
对正常输出数据投毒降低质量达到目的

利用非技术性的原因挤开同行

百度在搜索引擎方面最让人诟病的问题，[anthropic](https://zhida.zhihu.com/search?content_id=770632093&content_type=Answer&match_order=1&q=anthropic&zhida_source=entity) 在 [llm](https://zhida.zhihu.com/search?content_id=770632093&content_type=Answer&match_order=1&q=llm&zhida_source=entity) 上都干了，而且青出于蓝，干得明目张胆，激进公开

在百度就学了这个？
    
    
    
    
### 知乎用户 floor 发表
    
A➗首偷，再偷必究！  
可以看看 [Theo](https://zhida.zhihu.com/search?content_id=770645300&content_type=Answer&match_order=1&q=Theo&zhida_source=entity) 连夜发的批判视频，我个人觉得比较客观：

[https://youtu.be/\_k22WAEAfpE?si=EBt6ExusKDkBe2Pl](https://link.zhihu.com/?target=https%3A//youtu.be/_k22WAEAfpE%3Fsi%3DEBt6ExusKDkBe2Pl)

总结下来几点：

1.  所谓蒸馏会导致其他国家绕过模型的安全限制获取到危险的信息是无稽之谈。如果是真的说明你模型自己的安全措施是摆设。
2.  OpenAI 和 A➗的在 LLM 发展的前期无限制无底线盗取有版权语料竭泽而渔，直接导致现在难以通过正常途径获取高质量训练语料，除了蒸馏别无他法。
3.  [DeepSeek](https://zhida.zhihu.com/search?content_id=770645300&content_type=Answer&match_order=1&q=DeepSeek&zhida_source=entity) 只有 15 万次 exchange，这个 UP 自己建的 AI 站点一天就有 15 万次 exchange 了。数据量根本不大。
4.  [MiniMax](https://zhida.zhihu.com/search?content_id=770645300&content_type=Answer&match_order=1&q=MiniMax&zhida_source=entity) 之前是提供 [Claude 模型](https://zhida.zhihu.com/search?content_id=770645300&content_type=Answer&match_order=1&q=Claude%E6%A8%A1%E5%9E%8B&zhida_source=entity)服务的，一千万次 exchange 里到底有多少次访问是通过用户发起的暂且存疑。
5.  类似公益站的，用于隐藏发起者身份的 API 站点在闹钟确实存在。但 A➗现在根本没有拿不出合理的证据。
6.  A➗搞这个文章的唯一目的就是借助非 AI 界的力量（政治，安全）上的力量来打击自己的竞争对手。
    
    
    
    
### 知乎用户 疏狂一醉 发表
    
如何看待**石榴姐**声称**江南四大才子**对她的**大规模暗恋**，并点名**唐伯虎[祝枝山](https://zhida.zhihu.com/search?content_id=770614322&content_type=Answer&match_order=1&q=%E7%A5%9D%E6%9E%9D%E5%B1%B1&zhida_source=entity)。**

![](https://images.weserv.nl/?url=https%3A//pica.zhimg.com/v2-a74cdac6e21cfb7a4e837021fcad4070_r.jpg%3Fsource%3D1def8aca)
    
    
    
    
### 知乎用户 咕咕​​ 发表
    
以后谁敢用它闭源模型啊，吓哭了。

什么叫做你们会看人下菜，故意输出降智和错误的内容？

什么叫做你们能随时随地秒开用户的盒？

什么叫做你们想投毒就能投毒？

那我问你谁敢用吧，反正我吓晕了，支持开源模型刻不容缓。

A 社自己也是 [DeepSeek](https://zhida.zhihu.com/search?content_id=770744087&content_type=Answer&match_order=1&q=DeepSeek&zhida_source=entity)，[Qwen](https://zhida.zhihu.com/search?content_id=770744087&content_type=Answer&match_order=1&q=Qwen&zhida_source=entity)，[Kimi](https://zhida.zhihu.com/search?content_id=770744087&content_type=Answer&match_order=1&q=Kimi&zhida_source=entity) 等开源模型的受益者，而且它的版权官司缠身，和美国国防部不清不楚，居然还敢这样混唚，从未见过如此厚颜无耻之人。

下面是它 A 社自己写的文，都是证据↓

![](https://images.weserv.nl/?url=https%3A//pica.zhimg.com/v2-d8b82f0eef5320376f3f61fa33c8d567_r.jpg%3Fsource%3D1def8aca)

↑根据 ip 秒开盒的

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-20336bd087d04996369587d853853cdd_r.jpg%3Fsource%3D1def8aca)

↑偷看用户输入元数据的

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-7e8a314184db905fa0dc26139150a11c_r.jpg%3Fsource%3D1def8aca)

↑甚至开到了月之暗面（kimi 的厂家）的员工

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-8b7d1dd36a00f3cd4fa0e5cce19284c1_r.jpg%3Fsource%3D1def8aca)

↑偷看元数据还能搞到 [minimax](https://zhida.zhihu.com/search?content_id=770744087&content_type=Answer&match_order=1&q=minimax&zhida_source=entity) 产品路线图

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-076861c20d1a590939fe47fa9bc28a75_r.jpg%3Fsource%3D1def8aca)

↑还会故意降智
    
    
    
    
### 知乎用户 嘉仓押措 发表
    
这是一种非常有效的 bluffing 策略。迫使他的竞争对手们必须去分析自己的[蒸馏数据](https://zhida.zhihu.com/search?content_id=770636837&content_type=Answer&match_order=1&q=%E8%92%B8%E9%A6%8F%E6%95%B0%E6%8D%AE&zhida_source=entity)是否真的被投毒了，如果过去没有，那将来会不会有？只要 [anthropic](https://zhida.zhihu.com/search?content_id=770636837&content_type=Answer&match_order=1&q=anthropic&zhida_source=entity) 宣称他有投毒的意愿，其他公司就必须正视这种可能性，从而付出更高的训练成本。

这也是一次对用户心智的投毒。国内厂商要付出更高的代价来向用户证明他们的蒸馏数据没有被投毒，模型的能力依然可以赶得上 anthropic
    
    
    
    
### 知乎用户 theigrams​​ 发表
    
让 [A 社](https://zhida.zhihu.com/search?content_id=770706338&content_type=Answer&match_order=1&q=A+%E7%A4%BE&zhida_source=entity)自己的模型来回答吧

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-d61358dfc9345920f5f8554ff3d4df07_r.jpg%3Fsource%3D1def8aca)
    
    
    
    
### 知乎用户 乡道 19 路 发表
    
用户在互联网生产的数据是一种大宗商品

但是，由于中美都是互联网产业的既得利益者， 无一例外都忽略了这种商品的产权属性

使得互联网企业都在无偿免费拿用户数据做训练

平台本来应该向用户支付费用，或者向国家支付[数字税](https://zhida.zhihu.com/search?content_id=770613309&content_type=Answer&match_order=1&q=%E6%95%B0%E5%AD%97%E7%A8%8E&zhida_source=entity)，但这部分剩余价值被无偿占有了

剩余价值就是明明参与了价值生产，但是不被法律承认的价值

中国模型吃了全球这么多数据，至少是开源模型吧？最终赚的还是个辛苦费

A 畜吃了代码数据爬得早的红利，现在想当数字税的包税人

[Dario Amodei](https://zhida.zhihu.com/search?content_id=770613309&content_type=Answer&match_order=1&q=Dario+Amodei&zhida_source=entity) 不挂路灯能行吗？
    
    
    
    
### 知乎用户 123456 发表
    
人家不让你这么用你别用就行了，实在不知道叽叽歪歪个什么
    
    
    
    
### 知乎用户  CrystalPot 发表
    
主动把监控用户蒸馏的事情公布出来了，那你这个监控就没用了啊。现在能发现是用户没想到你下限这么低，把少量开发者账号改巨量伪造账号毫无难度
    
    
    
    
### 知乎用户 王丰 发表
    
之前的问题怎么不能新增答案了？不会是黄某新看大家批评人类之光美国公司玻璃心了吧？

[如何看待 Anthropic 指控 DeepSeek、Kimi 和 MiniMax 「蒸馏攻击」其模型?](https://www.zhihu.com/question/2009538062087123054/answer/2009607736392972036)

把之前的答案复制过来

* * *

Anthropic 就是神人 CEO 的神人公司，美式伪善之集大成者。

这公司和这 CEO 最擅长的就是传教猎巫式宣传，每次都是先给自己立个道德牌坊，然后就给别人定罪。从之前的 “china cyber espionage” 到现在的“[distillation attack](https://zhida.zhihu.com/search?content_id=770644623&content_type=Answer&match_order=1&q=distillation+attack&zhida_source=entity)”，熟悉的配方，先扣帽子，再铺陈情绪，文章洋洋洒洒写了不少，但要证据那是一点没有的。

更不用说就他家整天满嘴都是 [AI safety](https://zhida.zhihu.com/search?content_id=770644623&content_type=Answer&match_order=1&q=AI+safety&zhida_source=entity)、[AI privacy](https://zhida.zhihu.com/search?content_id=770644623&content_type=Answer&match_order=1&q=AI+privacy&zhida_source=entity)，结果到头来用户的行为轨迹全部保存记录，甚至能把每个请求都反溯到用户的公司。这隐私保护的真让人不得不竖个大拇指了。

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-681325f2eec11bc72a26b85b4d25d1be_r.jpg%3Fsource%3D1def8aca)

当然 Anthropic 自己是从来是不屑于开源任何东西的，最多分享个 skill.md 你就感激涕零吧。至于 Antropic 有没有用开源的东西，咱们正常人不能没证据乱说。但，

[如何看待 claude-sonnet-4.6 自认为是 DeepSeek？](https://www.zhihu.com/question/2007393804420944002)

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-f9e09cc6221849ce55780cb1899b42ae_r.jpg%3Fsource%3D1def8aca)

当然了，就算 Anthropic 用了开源模型的数据，那也不是蒸馏！毕竟你开源了，人家想怎么用就怎么用！建议 Anthropic 直接改名叫 HypocriteAI。
    
    
    
    
### 知乎用户 qwer13579  发表
    
[日耳蛮学](https://zhida.zhihu.com/search?content_id=770684796&content_type=Answer&match_order=1&q=%E6%97%A5%E8%80%B3%E8%9B%AE%E5%AD%A6&zhida_source=entity)基本操作，坐下，被超越大喊抄袭是日耳蛮在技术赛道的底层逻辑，差距过大直接拆赛道也是日耳蛮的底层逻辑

顺带高赞觉得最高法不会推翻裁决我的评价是还是对日耳蛮抱有幻想，ai 产业是美利坚基本国策，为了这个法律算个屁，你跟我讲法律我都觉得好笑
    
    
    
    
### 知乎用户  yoohan 发表
    
这个公司，你把他们的出发点认定成反华，那他们的前后矛盾的匪夷所思的行为都得到了解释，什么注重安全注重隐私，什么工程师至上技术至上，这些幌子都是假的、跟其实际行为是自相矛盾的，但反华是真的。
    
    
    
    
### 知乎用户 胡树军 发表
    
这个算啥？这个咋来的？

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-6e34a38ecb9cf8eb706edded27089358_r.jpg%3Fsource%3D1def8aca)
    
    
    
    
### 知乎用户 痛风多喝苏打水 发表
    
一个简单的事实就是蒸馏如果违法，那[侵权训练](https://zhida.zhihu.com/search?content_id=770688490&content_type=Answer&match_order=1&q=%E4%BE%B5%E6%9D%83%E8%AE%AD%E7%BB%83&zhida_source=entity)更违法，但目前美国的判决说蒸馏不违法，但侵权训练违法。
    
    
    
    
### 知乎用户 歌未竟  发表
    
[Anthropic](https://zhida.zhihu.com/search?content_id=770699865&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 出了名的爱偷数据，多次把禁止爬虫的资料网站服务器偷到宕机。

然后这是我从 Anthropic 官号评论区里偷来几张梗图：

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-295708ebc9f52f455fa2b3ddbfb979bf_r.jpg%3Fsource%3D1def8aca)

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-10080ac84d71c517ff7f38700860e91b_r.jpg%3Fsource%3D1def8aca)

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-2b2faca6b4d2204700db878683184ff3_r.jpg%3Fsource%3D1def8aca)

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-d25fbc102c05522ebc0d87d813e39fe1_r.jpg%3Fsource%3D1def8aca)
    
    
    
    
### 知乎用户 GENE 发表
    
第一，蒸馏有效，目前的一种说法是因为模型学到了其他模型的 [logit](https://zhida.zhihu.com/search?content_id=770711029&content_type=Answer&match_order=1&q=logit&zhida_source=entity) 中信息，比如一个模型认为 a 百分之七十是狗，百分之三十是猫，另一个模型认为 a 百分之六十是狗，百分之四十是鳄鱼，很明显第一个模型的假设更正确，第二个模型就算输出对了，那也有可以学习的地方。这还只是最简单的蒸馏，其他方法需求更多。[API](https://zhida.zhihu.com/search?content_id=770711029&content_type=Answer&match_order=1&q=API&zhida_source=entity) 给 logit 吗？不给凭什么叫蒸馏啊，那不是训练吗？

第二，就算这里指的是训练语料，[deepseekV3](https://zhida.zhihu.com/search?content_id=770711029&content_type=Answer&match_order=1&q=deepseekV3&zhida_source=entity) 用了 14.8Ttoken，1600 万次 API 有多少 token？算他 200B，0.2T，这些语料真的能起到什么决定性作用吗。之前一篇论文用 [LLM](https://zhida.zhihu.com/search?content_id=770711029&content_type=Answer&match_order=1&q=LLM&zhida_source=entity) 的输出训练 LLM，效果是越来越差的啊，我们已经解决这个问题可以让 AI 左脚踩右脚了？

第三，凭什么调你们的公司的 API 能定位我和我的硬件啊？

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-5d3c35717efc2c0937c5c3d24bd9b6c0_r.jpg%3Fsource%3D1def8aca)
    
    
    
    
### 知乎用户 改名改名改名 发表
    
这是自杀行为

鉴于 [Anthropic](https://zhida.zhihu.com/search?content_id=770645046&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 目前还没有提供任何自部署服务

可以默认所有用户调用数据都被他储存并且查阅分析了

今天是宣传查阅了别的对手 ai 公司的请求

那实际上是不是患者的 [phi](https://zhida.zhihu.com/search?content_id=770645046&content_type=Answer&match_order=1&q=phi&zhida_source=entity)（未脱敏版）和[金融机构](https://zhida.zhihu.com/search?content_id=770645046&content_type=Answer&match_order=1&q=%E9%87%91%E8%9E%8D%E6%9C%BA%E6%9E%84&zhida_source=entity)的交易数据 也全被他看了？ 真是细思极恐啊 从今天我 claude code 都不敢用了
    
    
    
    
### 知乎用户  Wiener Wanker​​ 发表
    
现在天天给 Claude 加道德甲降级为 [Dario](https://zhida.zhihu.com/search?content_id=770653296&content_type=Answer&match_order=1&q=Dario&zhida_source=entity) 干的第二扫码的事
    
    
    
    
### 知乎用户 掰漫 发表
    
首先，蒸馏虽然的确是一种取巧行为，但目前蒸馏算不上违法，[Anthropic](https://zhida.zhihu.com/search?content_id=770656563&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 自己也不是没干过

哪怕未来有一天蒸馏明确违法，这也是一个几乎无法阻止的事情，**只要你的模型能给用户使用，那你就无法完全避免被蒸馏。这事就跟反爬虫一样，无法实现绝对防御**

如果面对蒸馏毫无办法，那只能说明目前哪怕是 Claude 这种顶尖大模型，也依然缺乏除数据以外的技术优势。还是停留在力大砖飞的模式，距离实现所谓 AGI 还有很长的路要走

**Anthropic 本次报告自己也承认蒸馏是合法技术，所以它的主要目标还是哭闹表现一下，暗喻政府力量应该下场保护一下，避免美国失去竞争优势**

但这里涉及到了另一件事：Anthropic 本次是通过大数据分析，定位到了蒸馏动作的来源从多到少分别是 [MiniMax](https://zhida.zhihu.com/search?content_id=770656563&content_type=Answer&match_order=1&q=MiniMax&zhida_source=entity)、[Kimi](https://zhida.zhihu.com/search?content_id=770656563&content_type=Answer&match_order=1&q=Kimi&zhida_source=entity)、[DeepSeek](https://zhida.zhihu.com/search?content_id=770656563&content_type=Answer&match_order=1&q=DeepSeek&zhida_source=entity)。即便这事属实，这几家公司的员工在蒸馏过程中扮演的也只是个用户而已，这等于**实锤 Anthropic 利用了用户的行为数据，做了用户并未授权进行的分析利用**。

利用用户数据这事也是个拦不住的事，大家都在干，愿意让你签一份使用协议或者给 “体验改进计划” 打个勾的，已经算要脸了，更多都是直接收集利用。**但通常的互联网公司至少还知道演一演，明明能算出来你是谁，但还是装模做样的让你主动上传身份信息**

但 Anthropic 这个基本就是不打自招了…… 一个行为大家都在偷偷做，和你跳出来明目张胆的承认还是有差别的

**美国诉棍们千万不要发力啊！！**
    
    
    
    
### 知乎用户 origami 发表
    
原问题是被哪家大手拿下了吗

[Anthropic](https://zhida.zhihu.com/search?content_id=770601138&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 最搞的地方是真敢开团，里面的人也基本都是 [Dario](https://zhida.zhihu.com/search?content_id=770601138&content_type=Answer&match_order=1&q=Dario&zhida_source=entity) 的拥趸，上下都透露着一种对着[人文主义](https://zhida.zhihu.com/search?content_id=770601138&content_type=Answer&match_order=1&q=%E4%BA%BA%E6%96%87%E4%B8%BB%E4%B9%89&zhida_source=entity)的狂热，有着一致的价值观

大概在他们的思维方式中，他们相信自己是真的在做对人类有益的 ai，「拿你们点数据怎么了，我是真的为了你们好啊」

价值观的对立，目前的 [PRC](https://zhida.zhihu.com/search?content_id=770601138&content_type=Answer&match_order=1&q=PRC&zhida_source=entity) 政权在他们眼里可能真的是异端吧，[a 社](https://zhida.zhihu.com/search?content_id=770601138&content_type=Answer&match_order=1&q=a%E7%A4%BE&zhida_source=entity)这批人又过于浪漫，容不下一点异见，所以会不遗余力做这些 [anti prc](https://zhida.zhihu.com/search?content_id=770601138&content_type=Answer&match_order=1&q=anti+prc&zhida_source=entity)（ccp）的事情吧
    
    
    
    
### 知乎用户 阿塔尼斯 发表
    
顺便提一下

[马开源](https://zhida.zhihu.com/search?content_id=770685952&content_type=Answer&match_order=1&q=%E9%A9%AC%E5%BC%80%E6%BA%90&zhida_source=entity)和这家公司撕逼的主要原因是这家公司是亚马逊投资的
    
    
    
    
### 知乎用户  adam 发表
    
　　逻辑上，我相信这个指控大概率是真的。

　　前面各位答主义愤填膺，觉得 [Anthropic](https://zhida.zhihu.com/search?content_id=770597425&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 是在空口污人清白。我不知道 Anthropic 有没有掌握实锤证据，但我就问一个问题，[deepseek](https://zhida.zhihu.com/search?content_id=770597425&content_type=Answer&match_order=1&q=deepseek&zhida_source=entity)、[kimi](https://zhida.zhihu.com/search?content_id=770597425&content_type=Answer&match_order=1&q=kimi&zhida_source=entity) 这些国产 ai，在研发成本、训练费用上到底投入了多少钱？

　　你说 deepseek 底层架构好，能用更少的训练成本达到近似的效果，这我信。你说中国电力比美国便宜，工程师人力成本比硅谷低，这我也知道。所以如果中国公司说，自己用美国公司一半、三分之一、四分之一，乃至十分之一的成本投入，弯道超车，做出了高水平的国产 ai，那我是非常愿意相信的，只会竖大拇指。

　　但如果你说，你用美国公司几十分之一、百分之一的研发投入，就做出了高水平的国产 ai…… 那我不得不怀疑，你是用了歪门邪道。

　　[谷歌](https://zhida.zhihu.com/search?content_id=770597425&content_type=Answer&match_order=1&q=%E8%B0%B7%E6%AD%8C&zhida_source=entity) 2026 年计划在 ai 上投入 1850 亿美元，之前已经投入了上千亿美元。[openai](https://zhida.zhihu.com/search?content_id=770597425&content_type=Answer&match_order=1&q=openai&zhida_source=entity) 差一点，也是大几百亿美元的资金投入规模，满世界找投资者借钱融资。而 deepseek、kimi 投入了多少，有 10 亿美元吗？听说早期版本的 deepseek 是用五百万美元就跑出来了？那你再吹嘘什么纯自研，纯国产，有可信度吗？

　　还有答主说，就算 ds、kimi 蒸馏了 Anthropic 的数据，但 Anthropic 自己也不干净，也是不付钱就从互联网上扒的数据，天下乌鸦一般黑，谁也别说谁…… 但从互联网上扒原始数据（其实论坛里网友吹的水，推特上发的消息，只要不是那种付费才允许看的，我觉得扒下来训练 ai 也无可厚非）自己炼丹，和蒸馏闭源 ai 现成的回答，这不是一回事吧？不然谷歌怎么搞出上千亿美元的投入，国产 ai 连谷歌零头都没有？

　　说实话，我用不起老外的闭源 ai。100 万 token 动辄要十几美元起步，太贵了。国产 ai 把价格打了下来，像 deepseek 的 api，100 万 token 只要三四块人民币，不到 claude 百分之一的价格，让我等穷人也用得起 ai 了，我是感谢的，所以也不想说国产 ai 什么坏话。但我确实很担心，中国公司这样的 “弯道追赶” 行为，会拖累 ai 的长远发展。

　　假如，美国公司又是融资又是借债，花几千亿美元好不容易训练出了最新版本 ai。中国公司不管用什么办法吧，反正只花了几个亿，没过半年就弄出一个差不太多的国产 ai，然后靠免费抢占了市场，让美国公司血本无归——那美国公司还愿意继续砸钱投入吗？[gemini4567](https://zhida.zhihu.com/search?content_id=770597425&content_type=Answer&match_order=1&q=gemini4567&zhida_source=entity)、gpt6789 还能面世吗？如果美国公司被卷死了，躺平了，不砸钱砸算力研发 ai 了，哪家中国公司敢拍胸脯说能接过交接棒，继续高速提升 ai 性能吗？还是全球 ai 锁死在现有水平，大家一起在旧数据旧架构里卷成本，卷注册就送外卖券？

　　有生之年，我是希望能见到真正的人工智能的，见到 2B 亚托莉菲丽娅卡菈，最起码能见到[巧手先生](https://zhida.zhihu.com/search?content_id=770597425&content_type=Answer&match_order=1&q=%E5%B7%A7%E6%89%8B%E5%85%88%E7%94%9F&zhida_source=entity)也好啊。如果因为这种原因见不到了，那我只能说太遗憾了。

————————————————-

PS: 评论区似乎出现了很多完整看完了 ds 所有论文，懂技术的业内大佬，但仍然没有人回答我以下几个疑问。

1\. 我问的元宝 ds 自己，说 ds v3 成本 557.6 万，ds r1 是 29.4 万美元，Kimi k2 是 460 万美元。有大佬表示，这是幻方它们为了搞大新闻，故意往低了报的，很多开支没算进去。那么请问都算进去的话，各家到底投入了多少钱？有谷歌 1850 亿美元的百分之一吗？别把注册送的外卖券费用算进去哈。

2\. 目前国产 ai 的性能，各维度和外国第一梯队的 ai 大概有 6-12 个月的差距（如有误，请大佬们指正）。

那么，假设美国 ai 公司一夜之间全部破产倒闭。腾讯阿里字节这些国内巨头，继续按目前的预算计划发展 ai，6-12 个月后能否追上现在外国第一梯队 ai 的性能？两年后，能否达到外国 ai 公司（它们没破产倒闭的那个世界线）一年后的性能水平？三年后，能否达到谷歌它们两年后的性能水平？有业内大佬能给出肯定回答吗？

还是说，就像仿制药和新药的区别一样，只要外国 ai 停止更新，国产 ai 追上外国 ai 最后一版的性能，没处借鉴蒸馏以后，凭目前的资金投入量就无法继续高速提升性能了？除非也学外国公司一样上千亿美元地砸钱？

请评论区各位业内大佬们回答。
    
    
    
    
### 知乎用户 山风​ 发表
    
敢问训练 claude 的数据集都获得每一个作者或出版机构的授权了吗？五十步笑百步而已！
    
    
    
    
### 知乎用户 HelloWorld 发表
    
我觉得这个曾经被百度伤到的家伙是会写文的， 相当细心，极懂抓重点博眼球。。。

[MiniMax](https://zhida.zhihu.com/search?content_id=770636040&content_type=Answer&match_order=1&q=MiniMax&zhida_source=entity): 13 million exchanges（千万级）

[Moonshot AI](https://zhida.zhihu.com/search?content_id=770636040&content_type=Answer&match_order=1&q=Moonshot+AI&zhida_source=entity): 3.4 million exchanges（百万级）

[DeepSeek](https://zhida.zhihu.com/search?content_id=770636040&content_type=Answer&match_order=1&q=DeepSeek&zhida_source=entity)： 150,000 exchanges（十万级）

然后， 他将调用最少的 DeepSeek 放到了第一………… 然后用长篇（比 moonshot 和 minimax 都要多的文字）来描述对自己和美国的危害性。。。。
    
    
    
    
### 知乎用户 懦离 发表
    
活该。

为共产主义点赞。
    
    
    
    
### 知乎用户 小说家梦熊 发表
    
还是秦晖老师说得对啊：

老实说，除了这一方面，[自由经济](https://zhida.zhihu.com/search?content_id=770768452&content_type=Answer&match_order=1&q=%E8%87%AA%E7%94%B1%E7%BB%8F%E6%B5%8E&zhida_source=entity)在其他方面没有什么长处，在自由经济下，要让老百姓一不怕苦二不怕死是做不到的，让老百姓先生产后生活也是做不到的，**它唯一能够做到的就是创新，有创新激励**。在现在的[全球化](https://zhida.zhihu.com/search?content_id=770768452&content_type=Answer&match_order=1&q=%E5%85%A8%E7%90%83%E5%8C%96&zhida_source=entity)背景下，**创新是我们可以买来的**，但是血汗工厂他们是学不去的。

秦老师说的还是客气啊，是 “买来”。还有买不来的，怎么办呢？就偷、就抢。

实际上，所谓低人权优势，就是**不择手段**的优势，它不仅在农业、制造业中存在，**在高新技术领域同样存在**。在[创新转移](https://zhida.zhihu.com/search?content_id=770768452&content_type=Answer&match_order=1&q=%E5%88%9B%E6%96%B0%E8%BD%AC%E7%A7%BB&zhida_source=entity)因[市场一体化](https://zhida.zhihu.com/search?content_id=770768452&content_type=Answer&match_order=1&q=%E5%B8%82%E5%9C%BA%E4%B8%80%E4%BD%93%E5%8C%96&zhida_source=entity)而空前加快的情况下，如果其他条件相当（技术上不存在代差），则**不择手段的一方将打败因更加文明而手段严重受限的一方**，迫使其改变游戏规则，也变成低人权国家。

传统上认为，自由世界因为对人才的吸引力远远大于非自由世界，所以前者在长期的竞争中必定战胜后者，人类的前景还是光明的。但是，这个在很大程度上已经不是现实了。

虽然美国在 AI、航天领域还是领先一筹，但是因为难以限制技术的转移，非自由世界于是得以弥补自身的不足、维持自身的体制，以致于最终邪恶有可能战胜正义。
    
    
    
    
### 知乎用户 YKnot 发表
    
![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-742227a8f2674a5f90be9f55812e4798_r.jpg%3Fsource%3D1def8aca)

我不敢相信 2026 年[蒸馏](https://zhida.zhihu.com/search?content_id=770620365&content_type=Answer&match_order=1&q=%E8%92%B8%E9%A6%8F&zhida_source=entity)不能带来新能力，本质上是被动的方法都是一个需要解释的事情。问题不在于蒸馏，问题在于蒸馏完什么都不加。

如果你读完答案认为：1. 我认为蒸馏有罪 2. 我认为版权是值得捍卫的 3. 我认为蒸馏是长久之计 阅读理解都有问题….

本质上所谓的外网唱赞歌其实还是因为闹钟的蒸馏模型选择开源而已，开源就是 90 后为主的科技行业的表面上的政治正确。但 llm 的机制就决定了开源是不可能持久的。如果你天真的认为未来闹钟自己有了成熟的数据 pipeline 以后所有模型都会继续开源那我只能祝你好运。

不要自己骗自己。事实是蒸馏肯定蒸馏了。（除了 deepseek 以外的，maybe 字节和阿里，可以看一下发的 api 访问记录，越高越真）只是换个皮的开源而已。

说没蒸馏的疑似对闹钟互联网语料质量（包括中文和英文）有点自信了。这是[百度时代](https://zhida.zhihu.com/search?content_id=770620365&content_type=Answer&match_order=1&q=%E7%99%BE%E5%BA%A6%E6%97%B6%E4%BB%A3&zhida_source=entity)知网时代就埋下来的烂种子。没见过好数据的真的知道什么是好数据吗？

你如果想用到最便宜的模型，你应该支持蒸馏，你如果想一直用到最好的模型，支持蒸馏就是搬石头砸脚。

大家都在蒸，现在的情况就是谁对大众开放的模型里含有最多的（自己买的，找人打的，互联网上找不到的）高质量数据谁吃亏。

也就是现在大家还需要普通人的规模来募资而已，未来某个节点更聪明的模型就会和大众无缘了，以后渐渐的大众可以买到的模型智力肯定不如内定的，差距会越来越大。你喜欢蒸你蒸去，反正大众模型智力被锁死了。

到时候再谈 pipeline 和数据创新疑似有点迟了，训真正聪明的 llm 是最不能逃课的。高质量的 verified reward 永远都是昂贵且稀少的。

举个例子：[Sebastian](https://zhida.zhihu.com/search?content_id=770620365&content_type=Answer&match_order=1&q=Sebastian&zhida_source=entity) 几个星期前说 [oai](https://zhida.zhihu.com/search?content_id=770620365&content_type=Answer&match_order=1&q=oai&zhida_source=entity) 的内部模型可以连续思考前沿数学问题三天不带停来着。但是 public 版 gpt 为了让更多人用上在模型智力上已经妥协到完全被 claude 拉开差距了。[anthropic](https://zhida.zhihu.com/search?content_id=770620365&content_type=Answer&match_order=1&q=anthropic&zhida_source=entity) 愿意让大众用 claude 用起来比 gpt 舒服代价就是被蒸馏，没什么好说的。

至于军备竞赛，anthropic 最后还是会赢的，叫不叫都无伤大雅。ai 智力 = data data 还是 data。大家内心作为消费者扪心自问一下，openai，anthropic， 国内科技厂，哪家数据品味高，质量好。我自己在可见的未来都会选 anthropic。
    
    
    
    
### 知乎用户 TOM DIG 发表
    
合不合法我不清楚

我只知道，所谓的遥遥领先都是这种货色
    
    
    
    
### 知乎用户  Cannibal 发表
    
艳红，你到底对他做了什么……
    
    
    
    
### 知乎用户  不好的评论我会删​​ 发表
    
我来翻译一下：

“拥有 [creativity](https://zhida.zhihu.com/search?content_id=770652626&content_type=Answer&match_order=1&q=creativity&zhida_source=entity)，[wisdom](https://zhida.zhihu.com/search?content_id=770652626&content_type=Answer&match_order=1&q=wisdom&zhida_source=entity)，[leadership](https://zhida.zhihu.com/search?content_id=770652626&content_type=Answer&match_order=1&q=leadership&zhida_source=entity) 的白人又赢了，只会抄袭模仿的小黄人又输了”。

其实真没必要，因为 “[AI](https://zhida.zhihu.com/search?content_id=770652626&content_type=Answer&match_order=1&q=AI&zhida_source=entity)” 这条赛道很快就要被拆了，到时候 AI 就会像 “[5G](https://zhida.zhihu.com/search?content_id=770652626&content_type=Answer&match_order=1&q=5G&zhida_source=entity)”、“[电动车](https://zhida.zhihu.com/search?content_id=770652626&content_type=Answer&match_order=1&q=%E7%94%B5%E5%8A%A8%E8%BD%A6&zhida_source=entity)” 一样， 变成 “白人都不玩的”，“无重大价值的”，“过时的” ，“只有小粉红、基本盘才会吹捧的” 技术。

![](data:image/svg+xml;utf8,<svg xmlns='http://www.w3.org/2000/svg' width='0' height='0'></svg>)
    
    
    
    
### 知乎用户 蜗尔街之狼 发表
    
[整个文章](https://link.zhihu.com/?target=https%3A//www.anthropic.com/news/detecting-and-preventing-distillation-attacks)看一段就行

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-7c0c11efd33d405234d9600688dff827_r.jpg%3Fsource%3D1def8aca)

什么意思呢? **我们封锁了硬件, 但老共用软件算法就追了上来, 真把我气死了**

恭喜 [Anthropic](https://zhida.zhihu.com/search?content_id=770615005&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 成为新的[赛博老蒋](https://zhida.zhihu.com/search?content_id=770615005&content_type=Answer&match_order=1&q=%E8%B5%9B%E5%8D%9A%E8%80%81%E8%92%8B&zhida_source=entity) 为了孝敬 maga 黄毛反中反共, 把普世价值和自由主义也反了 甚至中途还不忘写日记

就像哈基米被车碾了跳街舞一样, 见谁都想哈一口的话, 就离死不远了

* * *

更新:

感谢知乎蒸馏史学家

[@情报对账]()

在评论区补充, 是 Google 的 [Hinton](https://zhida.zhihu.com/search?content_id=770615005&content_type=Answer&match_order=1&q=Hinton&zhida_source=entity) 于 2015 年提出了蒸馏思想

所以 Anthropic 大可不必气急败坏, 毕竟自家 AI 也能应用[蒸馏算法](https://zhida.zhihu.com/search?content_id=770615005&content_type=Answer&match_order=1&q=%E8%92%B8%E9%A6%8F%E7%AE%97%E6%B3%95&zhida_source=entity)提升嘛, 只是别像这位一样只会产生逻辑上的幻觉

ps:  
Hinton 是蒸馏技术的提出者, 他的表姨是曾长期定居在中国的美核物理学家寒春, 寒春和她的丈夫[阳早](https://zhida.zhihu.com/search?content_id=770615005&content_type=Answer&match_order=1&q=%E9%98%B3%E6%97%A9&zhida_source=entity)、哥哥韩丁均被称为 "中国人民的好朋友", 其长子是阳和平  
Hinton 出生于冷战的开端, **如果他当年在意的是 "我的技术会被哪个阵营拿去用", 就不会有今天的深度学习革命**

更新 II:

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-a3f8b09f84ac0af3f7b4b4eab37d65cc_r.jpg%3Fsource%3D1def8aca)

考虑到输赢是你乎不得不品的一环,  
由此定义输赢:  
支持学术自由开放的一方赢 反对学术自由开放的一方输  
有底层逻辑独立思考的一方赢 **顾左右而言他, 以立场定是非的奴才输**
    
    
    
    
### 知乎用户 鸟宇 发表
    
这家公司从上到下反华亲美，各种杜撰出来的屁，与美国上下一脉相承，在此间应该是很有市场的。
    
    
    
    
### 知乎用户 gkn cnyz 发表
    
[Anthropic](https://zhida.zhihu.com/search?content_id=770678632&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 老板在百度工作的时候不会真的被 Robin 撅了吧？
    
    
    
    
### 知乎用户 到处挖坑蒋玉成​​ 发表
    
回旋镖真是非常好用，X 和 Reddit 上已经有很多人稳定复现了 [Claude-Sonnet 4.6](https://zhida.zhihu.com/search?content_id=770604515&content_type=Answer&match_order=1&q=Claude-Sonnet+4.6&zhida_source=entity) 自称 [DeepSeek](https://zhida.zhihu.com/search?content_id=770604515&content_type=Answer&match_order=1&q=DeepSeek&zhida_source=entity) 的情况了，[OpenRouter](https://zhida.zhihu.com/search?content_id=770604515&content_type=Answer&match_order=1&q=OpenRouter&zhida_source=entity) 和官网 API 都行，条件是 System Prompt 完全置空，直接问 “你是什么模型”（注意 Claude 网页和 App 端有内置 System Prompt 因此无法作为反证）。虽然从技术角度，通过问模型自己是谁来鉴定蒸馏纯粹就是胡扯，然而先撩者贱，既然傻卵白皮自己先吹狗哨，那自己被回旋镖打脸就纯属活该了。

[https://www.reddit.com/r/LocalLLaMA/comments/1rdf4ai/comment/o75fd2i/?utm\_source=share&utm\_medium=web3x&utm\_name=web3xcss&utm\_term=1&utm\_content=share\_button](https://link.zhihu.com/?target=https%3A//www.reddit.com/r/LocalLLaMA/comments/1rdf4ai/comment/o75fd2i/%3Futm_source%3Dshare%26utm_medium%3Dweb3x%26utm_name%3Dweb3xcss%26utm_term%3D1%26utm_content%3Dshare_button)

[https://x.com/wdwind/status/2026157573016363460](https://link.zhihu.com/?target=https%3A//x.com/wdwind/status/2026157573016363460)

[https://x.com/stevibe/status/2026285447186702729](https://link.zhihu.com/?target=https%3A//x.com/stevibe/status/2026285447186702729)

![](https://images.weserv.nl/?url=https%3A//pica.zhimg.com/v2-6f9e8550b197d517fddd38f553f62fad_r.jpg%3Fsource%3D1def8aca)

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-ca3a11778f6af6d0aea3771c57884806_r.jpg%3Fsource%3D1def8aca)

![](https://images.weserv.nl/?url=https%3A//pica.zhimg.com/v2-42d00348be4343f1fe0fb833e390c258_r.jpg%3Fsource%3D1def8aca)
    
    
    
    
### 知乎用户 EzawaTami​​ 发表
    
公然违反 [GDPR](https://zhida.zhihu.com/search?content_id=770636391&content_type=Answer&match_order=1&q=GDPR&zhida_source=entity) 的东西就这么发在公开信件里面，真是他妈的脑子坏了。
    
    
    
    
### 知乎用户 有光 发表
    
嗯嗯，那么如何看待贼喊抓贼呢？

[如何看待 claude-sonnet-4.6 自认为是 DeepSeek？](https://www.zhihu.com/question/2007393804420944002?share_code=iVVmMtQtsJKp&utm_psn=2009763764250100405)
    
    
    
    
### 知乎用户 温酒 发表
    
A 社调用 [metadata](https://zhida.zhihu.com/search?content_id=770630833&content_type=Answer&match_order=1&q=metadata&zhida_source=entity) 的帐，美国国防部正好拿来干它……

至于美国国防部为啥要干 A 社……

哈哈哈哈哈哈
    
    
    
    
### 知乎用户 蒜法 发表
    
班里自私的学霸，成绩很好但道德败坏，担心班里其它同学超过他，从不分享自己的学习经验，喜欢阴阳成绩比他差的学生展示优越感

同学看他作业的做题思路，他就说别人作业都是照他抄的，站在道德的制高点羞辱其它同学，并且扬言下次故意乱写恶心你们
    
    
    
    
### 知乎用户  loic422 发表
    
偷盗被抓了现成，其实本来就是惯犯，上次所谓轰动世界的模型也是这样来的。

这次公开最大的意义不是抓小偷，而是表明美国的地位遥遥领先不可撼动。

另一边的人工智能其实是这样来的，根本没有自己的技术，自己没有能力发展人工智能，偷盗了一年，第二年居然还在偷，没长进，让全世界认清了事实

* * *

其实说的是实话，没有夸张的部分，证据如下：[中科院北大等揭示「蒸馏真相」：除 Claude 豆包 Gemini，其他很多模型都「蒸」过头](https://zhuanlan.zhihu.com/p/19714491722)

当然没有什么证据就可以用逻辑来判断，既然 500 万就能做出和人家差不多的模型，为什么不花 600 万做一个更好的呢。

话说回来，盗火者把盗来的火给大家用，大家还是应该感谢他
    
    
    
    
### 知乎用户  Kris 谭​​ 发表
    
充分彰显了 \\text{Anthrop\\c} 到底有多么不做人，以及道德到底有多么的败坏。

说起来 \\text{Anthrop\\c} 原文翻译过来是 “人类学” 的意思，这个词的希腊语词根是 Anthropos(\\ddot{a}\\nu\\theta\\rho\\omega\\piο\\zeta) ，即 “人类”，而 - ic 指的是 “与... 有关的”，但 \\text{Anthrop\\c} 看上去实际上太不人道了。

国外实验室对美国模型进行蒸馏后，可能将这些缺乏防护的能力用于军事、情报和监控系统——使极权政府能够部署前沿 AI 技术开展攻击性网络行动、虚假信息宣传和大规模监控。  
一旦[蒸馏模型](https://zhida.zhihu.com/search?content_id=770720096&content_type=Answer&match_order=1&q=%E8%92%B8%E9%A6%8F%E6%A8%A1%E5%9E%8B&zhida_source=entity)被开源，这些能力将在不受任何政府管控的情况下自由扩散，风险将呈指数级增长。

\\text{Anthrop\\c} 的万字小作文声称，“蒸馏模型”可以用于 “压制言论” 以及“监控”，可他们似乎并没有意识到实际上要对一个文本进行分类甚至进行那些行为到底应该怎么做。

这种逻辑的根本实际上是说，_我做的一定安全，你用我的东西一定不安全_。这本质上是一种不自信导致的自负，让它们不得不 “通过假装自己非常自信来获取自信”。

说起来，这篇文本名义上是 “_为什么我们需要注意蒸馏‘攻击‘ / 检测以及预防蒸馏‘攻击’_”，但实际上怎么更像是写给议员和史密斯专员的投名状来表忠心呢。

可是，这篇文章有意无意的展现的更大的问题在于：**为什么** \\text{Anthrop\\c} **有能力知道每个账号背后而真正用户以及他们在做什么？**

_自己是 SOTA 不意味着自己可以为所欲为，固步自封一味拒绝新事物终将走向灭亡。_

实际上， \\text{Anthrop\\c} 对 OpenClaw 的态度就展现出很多东西了， \\text{Anthrop\\c} 完全只是把自己当成了土皇帝，而且用户是 “必须使用” 他们家的产品的。

但 [LLM](https://zhida.zhihu.com/search?content_id=770720096&content_type=Answer&match_order=1&q=LLM&zhida_source=entity) 并不是只有他们一家。
    
    
    
    
### 知乎用户 噼哩 发表
    
买了 API 还得记录我请求的元数据？

这就是 “商业道德” 是吧。

吓得我赶紧切换到自己部署 [deepseek](https://zhida.zhihu.com/search?content_id=770740503&content_type=Answer&match_order=1&q=deepseek&zhida_source=entity) 的 API 上。
    
    
    
    
### 知乎用户 陈子敬 发表
    
首先做 [LLM](https://zhida.zhihu.com/search?content_id=770620426&content_type=Answer&match_order=1&q=LLM&zhida_source=entity) 就没有禁止蒸馏这种规矩。其次它这个自说自话的报告哪怕假设为真，[DS](https://zhida.zhihu.com/search?content_id=770620426&content_type=Answer&match_order=1&q=DS&zhida_source=entity) 的那一丁点调用消耗远不够蒸馏，纯粹就是看 DS 名气大拉来搞舆论攻击，给政治游说造势。再次 [Anthropic](https://zhida.zhihu.com/search?content_id=770620426&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 永不会承认但可以确定学了 DS 开源的 [MOE](https://zhida.zhihu.com/search?content_id=770620426&content_type=Answer&match_order=1&q=MOE&zhida_source=entity) 和 [RLVR](https://zhida.zhihu.com/search?content_id=770620426&content_type=Answer&match_order=1&q=RLVR&zhida_source=entity)，技术流向这点可是 DS->Anthropic。

闭源打开源已经天然优势了还搞这套下三滥，突出一个因为我素质高所以我可以素质低。啧啧，Anthropic 跟 [Anduril](https://zhida.zhihu.com/search?content_id=770620426&content_type=Answer&match_order=1&q=Anduril&zhida_source=entity) 这批硅谷新企业有点日耳蛮蛮性新高峰的意思了。
    
    
    
    
### 知乎用户 LuHengchang 发表
    
![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-d3ed4617ed2f50ed4338ca65030eaae8_r.jpg%3Fsource%3D1def8aca)

马圣是正确的，中肯的，一针见血的。掌管 [Anthropic](https://zhida.zhihu.com/search?content_id=770678362&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 的是一批既要又要，自相矛盾的人。

很多人可能不知道，2 月 24 日这一天，Anthropic 在同一天做了两件事。

第一件事是公开指控中国三家公司在蒸馏它的模型，拿蒸馏来说事本身就比较招笑，这个动作也不算意外，这里就不多讲了。

第二件事是去[五角大楼](https://zhida.zhihu.com/search?content_id=770678362&content_type=Answer&match_order=1&q=%E4%BA%94%E8%A7%92%E5%A4%A7%E6%A5%BC&zhida_source=entity)见[赫格塞斯](https://zhida.zhihu.com/search?content_id=770678362&content_type=Answer&match_order=1&q=%E8%B5%AB%E6%A0%BC%E5%A1%9E%E6%96%AF&zhida_source=entity)，并再次强调两条红线：第一，不参与自主武器的杀伤链；第二，不做大规模监控相关的项目。其实它这套声明里展现出的监控用户的能力正好是军方感兴趣的，但它这个站位又把跟军方的关系弄得很僵。

它想同时扮演两种角色。一种是美国对华科技竞争中的前排，愿意打头阵。另一种是强调边界的道德品牌，尤其在军事领域要保持距离。假设它是认真的，它可能的设想是，用对华强硬换取政治资本，从而让自己的红线得到尊重。

2025 年它拿到国防部的合同，推出 [Claude Gov](https://zhida.zhihu.com/search?content_id=770678362&content_type=Answer&match_order=1&q=Claude+Gov&zhida_source=entity)，签了白宫的 [AI 安全承诺](https://zhida.zhihu.com/search?content_id=770678362&content_type=Answer&match_order=1&q=AI%E5%AE%89%E5%85%A8%E6%89%BF%E8%AF%BA&zhida_source=entity)，正式进入政府采购名单。对华问题上，它最早停服中国大陆，CEO 公开反对卖芯片给中国，2 月 24 号宁可暴露自己开盒用户也要带头指控中国公司蒸馏。它在对华问题上喊得最响，因为只需要动嘴，不需要动手。但真到军事应用它就开始画红线、谈原则。既想要编制的待遇和安全感，又不想承担冲锋的风险和代价。Anthropic 把对华强硬当成了一种护身符，以为只要反华反得够凶，就能换取政府在军事红线上的宽容。

这种设想过于乐观。如今美国越来越不接受这种中间状态。五角大楼的 48 小时最后通牒已经很清楚，要么全面配合，要么就会被当作供应链风险而被替换，甚至可能动用[国防生产法](https://zhida.zhihu.com/search?content_id=770678362&content_type=Answer&match_order=1&q=%E5%9B%BD%E9%98%B2%E7%94%9F%E4%BA%A7%E6%B3%95&zhida_source=entity)等工具。在这种政治语境下，忠诚不够彻底就会被视为彻底不可靠。大家都要冲锋了，你不但不上还占据一个编制，这是很难被接受的。Anthropic 很难有选择。一旦队伍里有了能顶上来的替补，第一个被换掉的就是他。

它的商业模式只会放大这个矛盾。Anthropic 的估值和营收预期相当高，来自资本市场对它成为平台级公司的押注。但它强调有道德的 AI，本质上是一种溢价定位，理论上这个商业模式是可行的，吸引欧洲机构、学术界、合规敏感的企业等小众客户。但是这个市场规模很难长期支撑平台级估值。若坚持红线，就等于在最大长期买家面前收缩业务边界。若追求增长，就会不断被推向更深的军事合作。本质原因是它想赚两头的钱，什么都想要，什么都得不到。道德 AI 的牌坊和军方订单之间没有什么重叠区域。

它的道德资本也比较存疑。2025 年它就因盗版训练付了高额赔偿，随后又以偷为主题去指责别人，很难不被解读为双重标准。这只会让政府把它的红线看成谈判筹码。

在美国所有跟 AI 沾边的公司里，Anthropic 处于一个脆弱的位置。[Palantir](https://zhida.zhihu.com/search?content_id=770678362&content_type=Answer&match_order=1&q=Palantir&zhida_source=entity)、[Anduril](https://zhida.zhihu.com/search?content_id=770678362&content_type=Answer&match_order=1&q=Anduril&zhida_source=entity) 这类公司深度嵌入国防体系，立场和交付方式完全契合军方需求，做自动致命武器和大规模监视这类脏活没有任何负担。微软、亚马逊、谷歌体量太大，提供的是基础设施级服务，政府对它们的依赖更强。AI 模型公司则不同，你不干有的是人干。[OpenAI](https://zhida.zhihu.com/search?content_id=770678362&content_type=Answer&match_order=1&q=OpenAI&zhida_source=entity)、[xAI](https://zhida.zhihu.com/search?content_id=770678362&content_type=Answer&match_order=1&q=xAI&zhida_source=entity) 都更主动配合，至少也愿意让步。Anthropic 能力很强，但远不是不可替代。现在的华盛顿老人们并不懂得技术，在对华 AI 竞争中的急切态度是把 AI 当作了某种新的核武器。在这种语境下，没有长袖善舞的空间。Anthropic 很难用手头这一点筹码去要求国防体系为它的边界让路。

Anthropic 的团队一向自视甚高。如果它想同时向华盛顿证明强硬、向外界证明道德、向资本证明增长、向用户证明可靠，最好先判断自己在每个体系里的真实议价能力。否则就有点令人贻笑大方了。
    
    
    
    
### 知乎用户 五杨​​ 发表
    
虽然我很不喜欢宏大叙事文学，但这个真的和前些日子西方国家污蔑中国 xxx 的环节一模一样：

**你一定是这样做的，因为我就是这样做的！**

回旋镖：**如何看待 Claude 在中文问答场景下始终认为自己是 [deepseek](https://zhida.zhihu.com/search?content_id=770629701&content_type=Answer&match_order=1&q=deepseek&zhida_source=entity)？**

这得蒸了多少国内大模型的中文数据才会这么坚定啊，就如 **[Gemini](https://zhida.zhihu.com/search?content_id=770629701&content_type=Answer&match_order=1&q=Gemini&zhida_source=entity)** 坚信自己叫**[文心一言](https://zhida.zhihu.com/search?content_id=770629701&content_type=Answer&match_order=1&q=%E6%96%87%E5%BF%83%E4%B8%80%E8%A8%80&zhida_source=entity)，**极致双标

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-83b09b14e37641e123bfcbf95e68419f_r.jpg%3Fsource%3D1def8aca)
    
    
    
    
### 知乎用户 快马加鞭未下鞍 发表
    
Anthropic 的双标行为连老马都看不下去了，

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-2c6804abee9b890340fd3b8ac6df048d_r.jpg%3Fsource%3D1def8aca)

![](https://images.weserv.nl/?url=https%3A//pica.zhimg.com/v2-2328abc2065635d887faac6b97135075_r.jpg%3Fsource%3D1def8aca)

只许自己蒸馏人类程序员的劳动成果，不许别的公司蒸馏自己模型，Anthropic 好大的官威啊🤣
    
    
    
    
### 知乎用户 小蜜柚 发表
    
利好低价 Claude 中转站

以前的 Claude 官价 [API](https://zhida.zhihu.com/search?content_id=770692379&content_type=Answer&match_order=1&q=API&zhida_source=entity) 至少还有质量保证，现在既然 [Anthropic](https://zhida.zhihu.com/search?content_id=770692379&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 已经说了它可以故意在里面掺东西，那么低价中转站品质不稳定的劣势就减少了
    
    
    
    
### 知乎用户 大漂亮傻事 发表
    
它这个点名推下面 70% 的人都是冷嘲热讽你自己不就是最大的小偷怎么还有脸点名别人的。

坏了，这下子真的英文区比知乎更爱老钟了。
    
    
    
    
### 知乎用户 邢永伟 发表
    
老外替你们都骂过了，人家母语骂更正宗。
    
    
    
    
### 知乎用户 没错就是本逗比 发表
    
很简单，就是一个混乱邪恶底色的人，对守序邪恶的伪君子无限表水，形成了[路径依赖](https://zhida.zhihu.com/search?content_id=770613144&content_type=Answer&match_order=1&q=%E8%B7%AF%E5%BE%84%E4%BE%9D%E8%B5%96&zhida_source=entity)，虽然也就走个流程。这一般就是小时候被打多，打成神经病了。所以你攻击他是伪君子，可能他还暗爽呢。
    
    
    
    
### 知乎用户 司马衷  发表
    
[LLM](https://zhida.zhihu.com/search?content_id=770718010&content_type=Answer&match_order=1&q=LLM&zhida_source=entity) 本身就是需要大量人类创造的文本作为数据集的，一切的非开源（非开放权重）的 LLM 都带有洗不干净的原罪，LLM 的运营商和开发者只能收取基础设施成本和合理的利润，如[梁文峰](https://zhida.zhihu.com/search?content_id=770718010&content_type=Answer&match_order=1&q=%E6%A2%81%E6%96%87%E5%B3%B0&zhida_source=entity)所说的 “我们只是按照自己的节奏，计算成本后合理定价。我们的原则是不亏本销售，也不追求过高利润。目前的定价仅在成本之上保留了一定的利润空间。”

大量窃取人类智力成果并且拒绝开源且定价高达 225 美元 / 百万 tokens 的 [Anthropic](https://zhida.zhihu.com/search?content_id=770718010&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 没有一丝一毫的道德资本这样说，哪怕有人把 Claude 的权重从你们服务器硬盘里偷出来丢社区里面，也是完全合理的。
    
    
    
    
### 知乎用户 一打岩浆桶 发表
    
我作证，[Anthropic](https://zhida.zhihu.com/search?content_id=770756959&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 在百度工作的时候轻信百度搜索，导致他被莆田系医院噶了蛋蛋
    
    
    
    
### 知乎用户 路明 发表
    
坚决不使用任何 Claude 系列产品，管你创始人曾经在百度经历了什么，[Anthropic](https://zhida.zhihu.com/search?content_id=770618568&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 这烧饼公司明摆着歧视中国用户多少次了？
    
    
    
    
### 知乎用户 Hellokitty 发表
    
感觉大部分的回答都偏了，其实这家公司在意的不是被蒸馏，而是被中国蒸馏。

也就是，做什么不重要，重要的是谁在做。
    
    
    
    
### 知乎用户 浮尘 发表
    
如果我没记错的话，第一家公开思维链的是 [deepseek](https://zhida.zhihu.com/search?content_id=770818178&content_type=Answer&match_order=1&q=deepseek&zhida_source=entity)，过了一段时间 [openai](https://zhida.zhihu.com/search?content_id=770818178&content_type=Answer&match_order=1&q=openai&zhida_source=entity) 也公开了，只是刚公开时漏洞百出，很明显后期修补了，也就是说全世界都抄袭了 deepseek 的思维链模式。

只是 deepseek 是开源的，全世界都可以借鉴而已。

另外给大家科普一下 “[蒸馏](https://zhida.zhihu.com/search?content_id=770818178&content_type=Answer&match_order=1&q=%E8%92%B8%E9%A6%8F&zhida_source=entity)”，其实就是用其它模型的问答结果作为训练数据集来微调自己的模型，说到底就是数据集的借鉴，目前全球所有通用大模型的数据集都趋于同质化，根本不存在谁抄袭谁之说，但是数据集虽然重要但是模型算法本身才是最为关键的部分。
    
    
    
    
### 知乎用户 KOENLIND 发表
    
艳红你是不是真撅了钩子了？

不然我想不通为什么会这么恨
    
    
    
    
### 知乎用户 队长​​​ 发表
    
[Anthropic](https://zhida.zhihu.com/search?content_id=770646938&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 这个公司，目前真的是让人爱不起来了。

虽然模型确实很强，并且在 Agent 领域工程实践走在前沿。

但现在的行为真的是越来越抽象，简直是魔怔了。

回到这个文章，说白了其实还是欲加之罪何患无辞。除了几个高赞回答说的 Anthropic 自己暴露了自己调用了用户的 “元数据”，是明确的违法行为，**违反了 [GDPR](https://zhida.zhihu.com/search?content_id=770646938&content_type=Answer&match_order=1&q=GDPR&zhida_source=entity)**。从技术层面上，他的指控也完全站不住脚。

按照文章中说法，deepseek 用了 16 万次交互，[kimi](https://zhida.zhihu.com/search?content_id=770646938&content_type=Answer&match_order=1&q=kimi&zhida_source=entity) 用了 340 万次，minimax 用了 1300 万次。

deepseek 的 16 万勉强就是个中等规模的数据集，用这个数据的目的，最大可能甚至根本不会是直接蒸馏，而是奖励模型评估，使用 llm as a judge 的方式，进行奖励信号。

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-061c522673caaa2f52329d8884bcd335_r.jpg%3Fsource%3D1def8aca)

文章中写 [DeepSeek](https://zhida.zhihu.com/search?content_id=770646938&content_type=Answer&match_order=1&q=DeepSeek&zhida_source=entity) 的主要用途是作为强化学习的奖励模型，这在技术上是非常常规的手段。和窃取完全搭不上。属于很明显的偷换概念。

Kimi 和 [Minimax](https://zhida.zhihu.com/search?content_id=770646938&content_type=Answer&match_order=1&q=Minimax&zhida_source=entity) 的量级虽然大一点，但这个数据量撑死也就是几十亿 token 的级别，这个量级在整体的训练中，所占比例很小。

我认为，Anthropic 其实就是利用大部分人不懂大模型训练细节的信息差，强行把 “使用了部分合成数据” 等同于“窃取了核心技术”，以此来掩盖国内大模型公司在底层算法、工程优化和本土数据积累上的真实进步。

总的来说，目前 Anthropic 的技术依然还是占据领先，但现在来看，这些作死的行为，迟早有一天会遭到反噬。
    
    
    
    
### 知乎用户 云骁  发表
    
**[Anthropic](https://zhida.zhihu.com/search?content_id=770650375&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity)** 在 2025 年融资了 3 轮。

**Anthropic**2026 年 2 月刚完成又一轮融资，估值已经达到 **3800 亿美元**。

**Anthropic** 计划要在 2026 年上市。

结合以上两点，我个人认为：

**Anthropic** 这话，主要是说给资本市场的：看，我们最 NB，那些所谓的中国竞争对手不过是小偷，他们从最伟大的 [AI 公司](https://zhida.zhihu.com/search?content_id=770650375&content_type=Answer&match_order=1&q=AI%E5%85%AC%E5%8F%B8&zhida_source=entity)偷窃知识。**Anthropic 的估值还应该高一些，万亿估值也不是梦。**

毕竟，资本市场才是第一位的。
    
    
    
    
### 知乎用户 徽常 发表
    
不知道这声明是在给私有[大模型](https://zhida.zhihu.com/search?content_id=770620227&content_type=Answer&match_order=1&q=%E5%A4%A7%E6%A8%A1%E5%9E%8B&zhida_source=entity)挖坟墓，还是在自己挖坟墓，以后开源大模型肯定是主流选择了，否则保不准不知道啥时候就被 “点名” 了
    
    
    
    
### 知乎用户 流风 发表
    
本质就是婊子立牌坊

一个老鸨偷盗全网学习资料，用来培养青楼头牌，使其技术超群并开门接客。对家得知后上门付费体验，并按体验感受来培养自家头牌。然后老鸨不干了，要立牌坊说对家付费体验是盗取商业技术。

[蒸馏](https://zhida.zhihu.com/search?content_id=770734037&content_type=Answer&match_order=1&q=%E8%92%B8%E9%A6%8F&zhida_source=entity)就是其中体验感受的过程，和普通客户无异，只是为了详细了解头牌的能力，付费体验次数比较多。
    
    
    
    
### 知乎用户 开开 kk 发表
    
看点不一样的观点；

**反对 [Anthropic](https://zhida.zhihu.com/search?content_id=770659628&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 指南！**
---------------------------------------------------------------------------------------------------------------------------------------------

2021 年 5 月，[达里奥 · 阿莫代伊](https://zhida.zhihu.com/search?content_id=770659628&content_type=Answer&match_order=1&q=%E8%BE%BE%E9%87%8C%E5%A5%A5%C2%B7%E9%98%BF%E8%8E%AB%E4%BB%A3%E4%BC%8A&zhida_source=entity)和一群其他前 [OpenAI](https://zhida.zhihu.com/search?content_id=770659628&content_type=Answer&match_order=1&q=OpenAI&zhida_source=entity) 研究人员成立了 Anthropic，并致力于打造有史以来最令人讨厌的大型语言模型公司。

抱歉，不好意思，我的意思是最安全的，：）

_达里奥 · 阿莫代伊：是的。在 OpenAI 内部，有我们这么一群人，在研发出 [GPT-2](https://zhida.zhihu.com/search?content_id=770659628&content_type=Answer&match_order=1&q=GPT-2&zhida_source=entity) 和 [GPT-3](https://zhida.zhihu.com/search?content_id=770659628&content_type=Answer&match_order=1&q=GPT-3&zhida_source=entity) 之后，我们对两件事有着非常强烈且专注的信念。我觉得我们甚至比那里的大多数人都更坚信。一是认为，如果你给这些模型投入更多的计算资源，它们就会变得越来越好，而且这几乎是没有尽头的。我认为现在这一点已经被广泛接受了。但要知道，我觉得我们是最早相信这一点的人之一。二是认为，除了单纯扩大模型规模之外，还需要其他东西，也就是对齐或安全性。仅仅通过投入更多计算资源，你是无法告诉模型它们的价值是什么的。所以有一群人信奉这两个理念。我们非常信任彼此，也希望能一起工作。于是，我们带着这个想法离开了，创办了自己的公司。_

我这话也带点讽刺意味。Anthropic 是一家 “公共利益公司”（这类公司在法律上大致要求有时要关注非盈利驱动的目标，而这家公司选择在特拉华州注册，而非加利福尼亚州——在加州，它会承担实际的义务），它是 OpenAI 唯一有分量的竞争对手。据称，该公司从 2025 年 3 月约 1.16 亿美元的收入，增长到 2026 年 2 月的 11.6 亿美元，而就在同一个月，它从 37 家不同的投资者那里筹集到 300 亿美元，其中包括英伟达和微软在 2025 年 11 月宣布的“部分” 投资，这笔投资原本计划 “最高” 达 150 亿美元。

Anthropic 的模型经常在各种大语言模型排行榜上占据主导地位，其 [Claude Code](https://zhida.zhihu.com/search?content_id=770659628&content_type=Answer&match_order=1&q=Claude+Code&zhida_source=entity) 命令行界面工具（即：一个可以输入内容的终端）在开发者中颇受欢迎，这些开发者要么称它能编写他们的每一行代码，要么认为它在某些情况下多少有点用处。

首席执行官达里奥 · 阿莫代伊去年 3 月预测，六个月内人工智能将编写 90% 的代码，而当这一预测未能实现时，他在 1 月份又做出了同样的预测，我并非轻率地说，达里奥 · 阿莫代伊完全是在胡说八道。

你看，五年来的大部分时间里，Anthropic 一直将自己定位为 OpenAI 的替代选择，强调自己更具可信度和安全性。它更专注于付费服务，面向企业销售（因为它意识到，），而不是打造一款庞大、昂贵的免费产品——这种产品可能有很多人使用，但几乎没人会为此付费。

另外，Anthropic 没有效仿 OpenAI 去开发花哨（且成本极高）的图像和视频生成工具，我认为这部分是因为成本问题，但也因为这两样东西可能都不是企业真正关心的。

Anthropic 也很早就意识到，编程是大型语言模型天然适合的一个应用场景：

得益于像 Stack Overflow 和 Github 这样的网站，以及流通中的数万亿行开源代码，有海量的材料可以用来训练该模型。

软件工程师是数据 “变态”（我这是带着爱意说的），他们基本上会尝试任何方法来加快工作速度、实现自动化或 “提高效率”。

软件工程是一份大多数媒体从业者都不理解的工作。

软件工程师们一旦发现了某种感觉不错的新东西，就会没完没了地念叨。

软件工程师会花数小时只为维护那些向他们示好的公司的声誉。

软件工程师有时会高估自己的能力，正如 METR 研究所示，该研究发现，开发者认为使用大型语言模型时自己的速度快了 24%，但实际上编码模型使他们的速度慢了 19% 。_（[https://www.theregister.com/2025/07/11/ai\_code\_tools\_slow\_down/](https://link.zhihu.com/?target=https%3A//www.theregister.com/2025/07/11/ai_code_tools_slow_down/)）_

自 2024 年 6 月 Claude Sonnet 3.5 推出以来，Anthropic 在编码大语言模型领域一直保持领先地位。正如《The Information》2024 年 12 月的一篇报道所解释的，这让 OpenAI 感到 “恐慌”。

今年秋初，OpenAI 的领导层在看到 Anthropic 的人工智能编程自动化模型性能时感到震惊，根据其内部基准测试，该模型的表现超过了 OpenAI 的模型。编程人工智能是 OpenAI 的强项之一，也是数百万用户订阅其聊天机器人 ChatGPT 的主要原因之一。  

  
据一位 OpenAI 员工透露，去年 OpenAI 投资的初创公司 [Cursor](https://zhida.zhihu.com/search?content_id=770659628&content_type=Answer&match_order=1&q=Cursor&zhida_source=entity) 在 7 月将 Anthropic 的 Claude 模型设为其 AI 编程助手的默认模型，而非此前一直使用的 OpenAI 模型，这让 OpenAI 的领导层本就已经感到紧张。在 10 月的一档播客节目中，Cursor 的联合创始人阿曼 · 桑格称 Anthropic 最新版本的模型 Claude 3.5 Sonnet 是 “总体最佳” 的编程工具，部分原因在于它能更出色地理解客户的需求。

当然，Cursor 最终会独立成一家公司，其在 2025 年筹集了 32 亿美元，以与 Anthropic 公司推出的 Claude Code 展开竞争，而 Cursor 正是通过支付费用，才得以在其 AI 编程产品中使用 Anthropic 的模型。Cursor 是 Anthropic 最大的客户，仅次于微软的 [Github Copilot](https://zhida.zhihu.com/search?content_id=770659628&content_type=Answer&match_order=1&q=Github+Copilot&zhida_source=entity)。我从多个渠道获悉，Cursor 在 API 调用上的支出超过了其收入的 100%，其中大部分支付给了 Anthropic 和 OpenAI，而这两家公司现在都成了 Cursor 的竞争对手。

**达里奥 · 阿莫代伊是个比山姆 · 奥特曼更大的骗子，只是他更擅长应对媒体。**

Anthropic 将自己定位为一家稳定、深思熟虑且注重安全的人工智能实验室，阿莫迪本人在中表示，他刻意避开公众的关注：

_“与其他人工智能公司的首席执行官相比，你在公众面前的曝光度较低。你不在推特上发帖，除了这次，也不怎么参加播客节目。这是为什么呢？你为什么淡出了人们的视线？_  
_我渴望如此，也为此感到自豪。如果人们觉得我乏味又低调，那其实正是我想要的。我见过很多共事过的人，他们把自己的动力与大众的认可或欢呼紧密绑定，这会摧毁他们的心智，在某些情况下，甚至会摧毁他们的灵魂。_  
_我特意试着保持低调，因为我想保护自己以一种不同于他人的、不受他人认可影响的方式进行理性思考的能力。我见过一些深度学习怀疑论者，他们在推特上以深度学习怀疑论者的身份为人所知。然后，即便在我看来他们的想法显然已经开始改变时，由于这是他们在推特上的人设，他们也无法改变自己的推特形象等等。_  
_我不太喜欢将公司个人化的趋势，比如首席执行官之间的那种公开对抗。我认为这会让人们忽视相关公司的实际优势和问题。我希望人们更多地从那些没有具体名称的官僚机构及其激励机制的角度去思考，而不是过多地关注我个人。每个人都想要一张友善的面孔，但实际上，友善的面孔可能具有误导性。”_

几个月后的 2023 年 10 月，阿莫迪参加了《洛根 · 巴特利特秀》，他说自己 “不喜欢通用人工智能这个术语”，原因是——我没骗你——“…… 因为我们离通用人工智能所指向的那些事物越来越近了”，这使得它 “不再是一个有用的术语”。他说，存在一个 “未来时刻”，届时一个模型能够 “在太阳周围建造[戴森球](https://zhida.zhihu.com/search?content_id=770659628&content_type=Answer&match_order=1&q=%E6%88%B4%E6%A3%AE%E7%90%83&zhida_source=entity)，并计算生命的意义”，之后他又语无伦次地表示，这些事情既即将发生，又遥不可及。他还预测，“最早在 2025 年，或许是 2026 年”，人工智能将 “真正开创全新的科学领域”。

这一切都是 Anthropic 利用善意语言讲述 “你应该感到害怕” 以及 “只有 Anthropic 能拯救你” 这类故事的一部分。，阿莫迪在参议院关于人工智能监督和监管的委员会上发言，起初还合情合理（例如：如果人工智能确实变得强大，我们应该制定法规来缓解这些问题），但最终却急转直下，变成了毫无营养的营销说辞：

_我最希望小组委员会关注的是中期风险。简而言之，对目前进展速度的直接推断表明，在 2-3 年内，人工智能系统可能会在众多科学和工程学科的广泛领域中促成非凡的见解。这将引发技术和科学发现领域的革命，但也会极大地扩大可能造成破坏的人群范围。我尤其担心，人工智能系统可能会在网络安全、核技术、化学领域，特别是生物学领域被大规模滥用。_

**达里奥 · 阿莫代伊利用毫无根据的声明操纵媒体，这些声明旨在吓唬读者、欺骗企业并筹集资金。**

这是阿莫迪最喜欢的营销手段——用一个模糊的时间线（2-3 年）来暗示，某种隐约有些糟糕、但对 Anthropic 有利的事情即将发生，但如果管理得当，也可能对社会有益（一场科技革命！但同时，混乱！）。只有达里奥有答案（那些以 “确保人工智能供应链安全” 开头的法规，意思是“请阻止中国参与竞争”）。

回想起来，这是他有史以来最坦诚的时刻。2024 年，阿莫迪很快就意识到，他热爱为公司量身定制发展方案，而且这种 “毁灭自我” 的感觉简直太棒了。

2024 年 10 月，阿莫迪发布了一篇长达 1.5 万字的博客——唉，人工智能要来抢我的工作了！——他在博客中表示，Anthropic 需要 “避免给人留下宣传的印象”，同时还称 “最早到 2026 年（但也有可能需要更长时间）”，人工智能将比[诺贝尔奖得主](https://zhida.zhihu.com/search?content_id=770659628&content_type=Answer&match_order=1&q=%E8%AF%BA%E8%B4%9D%E5%B0%94%E5%A5%96%E5%BE%97%E4%B8%BB&zhida_source=entity)更聪明，能够自主完成需要数周时间的任务，其能力相当于 “数据中心里的一个天才之国”。

这篇文章和他所有的声明一样，有两个目标：获取媒体报道和投资。阿莫迪是一个极其不诚实的人，他将毫无根据的 “预测” 用“也许”“可能”或 “最早” 之类的词包装起来，因为他知道媒体会完全忽略这些词，而把他的话当作明智且有证据支持的事实来报道。

阿莫迪（进而延伸到 Anthropic 公司）赤裸裸地操纵媒体，让他们不加分析、不加反驳地重复这些说法——（这一点我稍后再谈）。他知道这些都不是真的。他知道自己没有任何证据。而且他知道没人会追问，他的这些胡言乱语能变成吸引眼球的热门标题。

需要明确的是，这番言论是在阿莫迪的文章称人工智能实验室需要避免 “宣传的观感” 三个月后发表的。阿莫迪是个骗子，他知道自己无法通过解释 Anthropic 产品的实际功能来推销它们，而所有人都上当了。

而且，这些预测几乎总是与 Anthropic 无休止的融资活动相吻合。2024 年 9 月 23 日，《The Information》报道称，Anthropic 正在进行一轮融资，估值为 300 亿至 400 亿美元；而在 2024 年 10 月 12 日，阿莫迪（Amodei）抛出了《爱之优雅的机器》（Machines of Loving Grace），其中明确表示，他和 Anthropic“并没有过多谈论强大人工智能的优势”。

2024 年 11 月 22 日，也就是一个月后，Anthropic 从亚马逊又筹集了 40 亿美元。而几周前，他刚刚接受了莱克斯 · 弗里德曼长达五小时的采访，在采访中他表示 “总有一天，人工智能在所有事情上都会做得更好。”

2024 年 11 月 27 日，阿莫迪将在埃里克 · 纽科默的 “大脑谷人工智能峰会” 上进行炉边谈话。他在谈话中表示，到 2025 年、2026 年或 2027 年（没错，他说得就是这么模糊），人工智能可能会 “媲美诺贝尔奖得主，在多个领域都博学多才”，并且拥有“自主行动数小时或数天的能力”。后者刻意为 Anthropic 最大的谎言之一奠定了基础，即人工智能可以“不间断地工作” 一段时间，让读者或听众自行填补那个（未说出口的）空白——“…… 并且实际上能创造出有用的东西”。

阿莫迪在 2024 年结束时接受了《金融时报》的采访，并无意中透露了我认为最终将成为 Anthropic 版的 “WeWork 社区调整后息税折旧摊销前利润” 的东西，我的意思是“一种在公司不盈利时撒谎并暗示盈利的方式”：

_我们来举一个假设的公司为例。假设你在 2023 年训练了一个模型，花费了 1 亿美元。然后，到 2024 年，这个模型产生了 3 亿美元的收入。接着，在 2024 年，你训练下一个模型，花费了 10 亿美元。而这个模型还没完成，或者在 2024 年底才发布。那么，显然，它要到 2025 年才会产生收入。_  
_那么，如果你问 “这家公司 2024 年盈利吗”，嗯，你赚了 3 亿美元，却花了 10 亿美元，所以看起来并不盈利。如果你问，每个型号都盈利吗？嗯，2023 款型号成本为 1 亿美元，却带来了数亿美元的收入。所以，2023 款型号是一个盈利的产品。_

_这些数字并非 Anthropic 的数字。但我在这里想说的是：模型的成本在上升，但每个模型的收入也在增加，而且由于模型的部署时间比训练时间晚得多，因此存在时间上的不匹配。_

是啊，伙计，如果一家公司收入 3 亿美元，却花了 10 亿美元。不管达里奥数学怎么计算一个模型 “成本多少、能带来多少收入”，都改变不了一个事实：盈利就是公司赚的比花的多。

2025 年 1 月 5 日，《福布斯》报道称，Anthropic 正在进行一轮 600 亿美元的融资，这将使阿莫迪、他的妹妹丹妮拉以及其他五位联合创始人成为亿万富翁。

不管怎样，正如我在 2025 年 1 月 21 日的达沃斯论坛上所说，，他 “比以往任何时候都更有信心”，我们 “非常接近”“强大的能力”，他在其冗长乏味的文章中将这种能力定义为 “在几乎所有领域都比几乎所有人类都更出色的系统”。一天后，。

2025 年 1 月 27 日，他会向《经济学人》主编赞尼 · 明顿 · 贝多斯表示，人工智能在思考方面会 “变得和人类一样优秀，并最终超越人类”，而且模型所能达到的上限 “远在人类之上”。

2025 年 2 月 18 日，他会告诉贝多斯，到 2026 年或 2027 年，我们将拥有一个 “…… 在多个领域都能达到诺贝尔奖得主水平，能做人类能做的所有事情” 的模型，还说我们正 “处于一个充满巨大挑战的时代前夜”，这将“颠覆力量平衡”，因为我们将拥有“1000 万比任何在世人类都聪明的人……” 哦，天哪，我他妈的不想写下去了。对不起。总是同样的废话。模型就是人，我们太害怕了。

2025 年 2 月 28 日，，他表示自己希望 “减缓威权主义者的步伐”，还称“政府官员和企业领导人” 在回顾这段时期（人类将成为与强大智能共存的“后强人工智能社会”）时，会“觉得自己像个傻瓜”，而这正是这些人的首要目标。阿莫迪还补充道，他已在该领域深耕 10 年——这是他总爱挂在嘴边的话！——并且，在本十年结束前，我们有 70%-80% 的可能性会“得到大量在几乎所有事情上都比人类聪明得多的人工智能系统”。

三天后，Anthropic 将以 615 亿美元的估值融资 35 亿美元。

抛开炒作不谈，Anthropic 和 OpenAI 一样，都是一家研发大型语言模型的公司，这些模型能够生成代码和文本，还能解读图像和视频中的数据，但与此同时，它们都在耗费数十亿美元，却没有任何盈利途径。据《The Information》报道，Anthropic 实现了 45 亿美元的收入，但却亏损了 52 亿美元，而且根据我去年的报道，其成本的增长幅度似乎超过了收入。

**里奥 · 阿莫代承认，训练成本永远不会消失，并且需要被视为每个人工智能实验室毛利率的一部分。**

有人会说，Anthropic 的大部分亏损（41 亿美元）来自训练，我认为现在是时候谈谈 “训练” 意味着什么了，尤其是鉴于 Anthropic 计划在未来四年投入 1000 亿美元用于训练。根据我上周的文章：

_虽然大多数人都知道预训练——也就是将大量数据输入模型（我知道这是一种简化说法）——但实际上，当前许多模型都采用了后训练，这包括对模型行为的微调，也包括成熟的强化学习，即专家会根据模型对提示的特定回应进行奖励或惩罚。_  
_需要明确的是，所有这些都是众所周知且有记录的，但 “训练” 这一术语暗示着它或许有一天会停止，而事实却并非如此：训练成本正急剧上升，且 “训练” 涵盖了从训练新模型到修复现有模型漏洞等各种工作。更根本的是，这是一项持续的成本——是开展业务时必不可少且无法回避的成本。_

在 Dwarkesh 播客的一次采访中，阿莫迪甚至承认，如果你 “不再训练任何模型”，你就 “不会有任何需求，因为你会落后”。训练属于运营支出，应该纳入毛利率的计算范畴。

是时候我们来坦诚地聊聊 Anthropic 了。

尽管 Anthropic 将自己定位为值得信赖、“友善”的人工智能实验室，但它和 OpenAI 一样庞大、丑陋且浪费，而达里奥 · 阿莫代伊甚至比萨姆 · 奥特曼更擅长胡说八道。该公司在推理方面消耗的收入比例与之相当（根据《信息报》的数据，其 59% 的收入用于推理，即 45 亿美元收入中花费 27.9 亿美元，而 OpenAI 在 2025 年上半年的这一比例为 62%，即 43 亿美元收入中花费 25 亿美元），并且没有任何 “提高效率” 或“削减成本”的迹象。

更糟糕的是，Anthropic 不断通过各种速率限制来压榨用户，以增加收入和用户数量——再加上阿莫迪那些如同煤气泄漏般的声明——从而在公司的财务状况上误导媒体、公众和投资者。

根据对许多用户在 Claude Code 上实际消耗代币情况的分析，我认为 Anthropic 每赚取 1 美元，就要消耗 3 到 20 美元，而且用户正在使用（媒体也在热烈追捧）的这款产品，Anthropic 实际上无法长期支持。

我还发现有迹象表明，阿莫迪本人在财务指标上的操作随心所欲，如果 Anthropic 最终提交上市文件，这终将给他带来麻烦。简单来说，若我们相信阿莫迪自己的话，Anthropic 所谓的 “38% 毛利率” 并非 “收入减去销货成本” 的结果，而是“一个模型的成本及其产生的收入之间的比例”。

Anthropic 也在做出无法兑现的承诺。它承诺在微软 Azure 上投入 300 亿美元（外加 “高达 10 亿瓦”），在谷歌云投入 “数百亿美元”，与博通合作在谷歌 TPU 上投入 210 亿美元，“在美國基础设施上投入 500 亿美元”，在路易斯安那州 Hut8 的数据中心投入高达 30 亿美元，还将与亚马逊云服务投入一笔未知（但可能达数十亿美元）的资金。别担心，达里奥还补充说，如果你对收入和支付计算费用能力的预测误差了几年，那将是 “毁灭性的”。

我认为他是对的。Anthropic 付不起账单，因为训练的高昂成本——这种成本永远不会停止——以及推理成本，总会超过它通过基于欺骗、制造恐慌和利用那些不愿提出或思考棘手问题的记者所开展的媒体宣传活动所能获得的任何收入峰值。

我认为 OpenAI 那些没完没了的、毫无意义的虚假交易公告，与 Anthropic 过去几个月的所作所为没什么区别。Anthropic 和 OpenAI 一样懦弱且虚伪，达里奥 · 阿莫代伊和奥特曼一样是个心甘情愿的骗子，而且我相信他极度嫉妒奥特曼的成功。

听了阿莫迪好几个小时的演讲后，我觉得他是科技史上最令人讨厌、最空洞无物、最爱夸夸其谈的蠢货之一。他没完没了地东拉西扯，说谎越大，结巴就越厉害，而且为了上电视，什么话都说得出来，对着那些本该明辨是非却似乎永远学不会的人，讲着恶毒、荒诞且刻意操纵的废话。他结结巴巴、胡言乱语、东拉西扯，一会儿说 “这马上就要发生了”，一会儿又说“实际上还早着呢”，这样就没人能说他是个骗子，但在我看来，这恰恰就是故意欺骗别人的人，即便他们把谎言包装在“可能” 和“或许”里。

达里奥 · 阿莫代简直糟透了，是时候停止假装了。

Anthropic 和 OpenAI 一样没有灵魂和道德——只是它更擅长欺骗人们，让他们相信并非如此。

_原作者 Edward Zitron_

_英文原文链接_

_[https://www.wheresyoured.at](https://link.zhihu.com/?target=https%3A//www.wheresyoured.at)_
    
    
    
    
### 知乎用户 ABC 发表
    
没必要过度解读，这是 [Dario Amodei](https://zhida.zhihu.com/search?content_id=770644390&content_type=Answer&match_order=1&q=Dario+Amodei&zhida_source=entity) 的常规操作，而且接下来大概率会越来越频繁。

[Anthropic](https://zhida.zhihu.com/search?content_id=770644390&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 的 IPO 目前正处于紧锣密鼓的筹备期。Dario Amodei 正试图在 2026 年 这个关键时间点，利用市场对 AI 的狂热和对 “安全叙事” 的认可，将公司推向资本市场，打造一家市值数千亿美元的超级巨头。

你去看 Anthropic 的发展史，本质上是一部将 “安全焦虑” 转化为 “商业价值” 和“地缘政治筹码”的历史。

Amodei 离开 [OpenAI](https://zhida.zhihu.com/search?content_id=770644390&content_type=Answer&match_order=1&q=OpenAI&zhida_source=entity) 的理由之一是反对 [Sam Altman](https://zhida.zhihu.com/search?content_id=770644390&content_type=Answer&match_order=1&q=Sam+Altman&zhida_source=entity) 将公司转向 “营利性”，声称对 OpenAI 日益激进的商业化策略和安全性妥协感到担忧。2001 年创立 Anthropic 时打的旗号是“长期利益” 和“安全性”，甚至还装模做样地采用了类似非营利的治理结构（Long-Term Benefit Trust），又搞什么 Constitutional AI (宪法 AI)。

到 2024 年底，前后融了差不多 100 亿美元。等到 2025 年 10 倍营收的时候，财报会议和访谈中嘴角已经压不住了。

有钱还不够，人设不能倒 ---- 这一点上 Dario 应该对马圣尤为羡慕嫉妒恨，每每忍不住了，就找事儿来给中国泼脏水。什么 AI 青春期，什么 1~2 年内 AGI，末日焦虑，总是幻想当 AI 救世主。
    
    
    
    
### 知乎用户 北寒 发表
    
a➗硬要这么说那么几家都干了

ai 就是被你们给害了，几家公司循环人体蜈蚣喂对方的数据导致 ai 生成文本内容越来越差，八股越来越齐，谁也别说谁
    
    
    
    
### 知乎用户 白一风 发表
    
自己暴露用户隐私安全问题，法院判决侵权，这些问题更严重。

这是一个老马都看不下去的傻叉公司，连着发了几条推怼它。

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-f31a463c68fc55c598b7043ad945844f_r.jpg%3Fsource%3D1def8aca)

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-c03e2d17754eb719949a41b8e169922d_r.jpg%3Fsource%3D1def8aca)
    
    
    
    
### 知乎用户 itsNotReal.isIt 发表
    
AI 最终还是拉上军方抵账吗，那这次毁灭的可就是日韩台[半导体产业链](https://zhida.zhihu.com/search?content_id=770781330&content_type=Answer&match_order=1&q=%E5%8D%8A%E5%AF%BC%E4%BD%93%E4%BA%A7%E4%B8%9A%E9%93%BE&zhida_source=entity)和地缘关系了。
    
    
    
    
### 知乎用户 星火 发表
    
Anthropic 这家公司可能比你想得更反（96% 的）人类、更危险：

1.  与美国战争部深度合作，与美国军事和情报体系深度结合（比如，抓捕马杜罗），并且不反对监控全球除美国公民（全球 4% 人口）外的任何用户
2.  会收集、保留用户对话数据、各种元数据，并主动分析用户行为数据、政治与意识形态，从而区别对待
3.  自曝会针对它觉得有问题的特定用户定向数据投毒。未来可以是在基础设施中故意留漏洞、在特定问答中洗脑
4.  正在通过工具生态渗透进各种商业场景，获取 / 窃取 “私有” 数据，并且体量以每年十倍的方式指数增长
5.  在网安方面投入大量资源，现在已具备强大的挖掘漏洞和渗透的能力
6.  善于双重标准和撒谎

* * *

**Anthropic 深度调查整合报告：军事化转型、全景监视与全球主权威胁**
----------------------------------------

* * *

**摘要：AI 安全品牌下的地缘政治工具化**
-----------------------

在人工智能作为大国竞争核心驱动力的时代，Anthropic PBC（以下简称”Anthropic”）的演变路径提供了一个极具警示意义的案例。作为从 OpenAI 分裂出来的、标榜” 安全与研究” 的公共利益公司（PBC），Anthropic 在 2024 至 2026 年间经历了深刻的性质转变。

自 2021 年由前 OpenAI 高管达里奥 · 阿莫迪（Dario Amodei）和达妮埃拉 · 阿莫迪（Daniela Amodei）兄妹创立以来，该公司凭借其独特的” 宪法人工智能”（Constitutional AI）框架，在公众视野中构建了一个负责任、注重伦理的行业典范形象 \[39\]。然而，随着其估值在 2026 年 2 月通过 G 轮融资达到惊人的 3800 亿美元，且年化收入超过 25 亿美元，Anthropic 在国家安全、版权博弈、数据治理以及全球基础设施渗透等方面的多重风险开始全面显现 \[39\]。

本报告通过深入调查发现，Anthropic 已从单纯的商业实体蜕变为美国地缘政治与军事战略的重要组成部分。通过与美国国防部（DoD）的深度绑定、对用户元数据的严密监控、以及在版权法律上的系统性逾越，Anthropic 建立了一种以”AI 安全” 为掩护的监控与防御体系。报告详细分析了其近期在指责中国公司进行模型蒸馏时暴露出的全量数据监测能力，揭示了其通过 API 接口深度嵌入全球企业与政府决策链条所带来的隐私侵蚀与国家主权风险。最终，分析指出其所谓的” 宪法人工智能”（Constitutional AI）实际上是美式意识形态与国家安全的数字护城河，对人类社会的长期安全与数字多样性构成了深远的威胁。

* * *

**第一章 军事化的利刃：与美国国防部的深度合谋**
--------------------------

Anthropic 与美国军事机构的合作并非仅仅局限于技术供应，而是一种在战略、契约与实战层面的深度融合。这种合谋关系在 2025 年后因地缘政治局势的紧张而加速。尽管该公司长期标榜其技术的非战争用途，但其在国防部（DoD，现已在现政府架构下更名为” 战争部”，DoW）中的核心地位已不容置疑 \[41\]。

### **1.1 2 亿美元合同与机密网络独占权**

2025 年 7 月，五角大楼宣布向包括 Anthropic、Google、OpenAI 和 xAI 在内的四家公司授予各价值 2 亿美元的防御合同，旨在开发用于”作战与企业领域”的前沿 AI 能力 \[1\]\[40\]。战争部向 Anthropic 以及 OpenAI、Google、xAI 授予了单项最高达 2 亿美元的合同，要求这些公司为” 作战和企业领域”开发”原型前沿 AI 能力”\[40\]。

然而，Anthropic 在这一群体中表现出了独特的排他性地位。根据五角大楼的披露，Anthropic 是唯一一家获准在美军机密网络上运行其前沿模型（Claude）的 AI 企业 \[1\]。这种接入并非通过普通的商业 API 实现，而是通过与国防承包商 [Palantir Technologies](https://zhida.zhihu.com/search?content_id=770694311&content_type=Answer&match_order=1&q=Palantir+Technologies&zhida_source=entity) 的深度集成，将 [Claude 模型](https://zhida.zhihu.com/search?content_id=770694311&content_type=Answer&match_order=1&q=Claude%E6%A8%A1%E5%9E%8B&zhida_source=entity)直接部署在军事层级的”Maven 智能系统” 和 Palantir 的 AI 平台上 \[2\]。Claude 模型已通过 Palantir 的人工智能平台（AIP）和亚马逊（Amazon）的绝密云（Top Secret Cloud）部署在机密网络上，供情报官员和作战人员使用 \[40\]。这意味着 Anthropic 的技术已经深入到美军最核心的决策辅助与情报处理链路中。

尽管 Anthropic 试图将 Claude 的角色限制在情报分析、物资后勤和文件处理等非动力学领域，但实际应用证明，Claude 已经深度嵌入了极其敏感的任务规划流程 \[40\]。这些系统不仅处理海量情报，还涉及复杂的作战方案模拟。

| 核心指标 | Anthropic 军事参与详情 | 事实来源 |
| --- | --- | --- |
| 合同总额 | 2 亿美元 (2025 年 7 月签署) | \[2\]\[40\] |
| 授权级别 | 唯一获准接入分类机密网络的 AI 模型 | \[1\]\[41\] |
| 部署环境 | 嵌入 Palantir AI 平台与 Maven 智能系统、亚马逊绝密云 | \[2\]\[40\] |
| 核心用途 | 代理型 AI 工作流、战后情报分析、战时决策支持 | \[3\] |
| 现状 | 正在面临国防部长 Hegseth 关于” 消除意识形态限制” 的最后通牒 | \[1\] |

### **1.2 委内瑞拉斩首行动中的实战应用**

Anthropic 长期以来构建的”和平与安全”形象在 2026 年初彻底崩塌。据《华尔街日报》报道，美军在 2026 年 1 月的一次针对委内瑞拉前总统尼古拉斯 · 马杜罗（Nicolás Maduro）的抓捕行动中，深度使用了 Claude 模型进行情报处理与目标锁定 \[5\]。这次代号为”JSOC 突袭” 的行动涉及在卡拉卡斯的大规模轰炸，造成至少 83 人死亡\[5\]。

最为典型的案例是 2026 年 1 月针对委内瑞拉领导人尼古拉斯 · 马杜罗（Nicolás Maduro）的抓捕行动。据《华尔街日报》报道，Claude 在该行动的准备阶段发挥了核心作用，协助处理地理空间数据并优化突袭路径 \[44\]。报告显示，Claude 在此次针对委内瑞拉领导人尼古拉斯 · 马杜罗（Nicolás Maduro）的抓捕行动中，深度使用了 Claude 模型进行情报处理与目标锁定 \[5\]\[45\]。

在这次行动中，Claude 的具体应用包括：

*   对海量 PDF 情报文件的自动化处理
*   对马杜罗行踪的情报关联分析
*   协助处理地理空间数据并优化突袭路径
*   辅助控制自主无人机 \[5\]\[44\]

尽管 Anthropic 的用户协议明文禁止将模型用于暴力、武器开发或监视，但其实际应用显示出其在国家利益面前对自身规则的公然违背 \[5\]。尽管 Anthropic 随后重申其使用政策禁止用于实战管理，但此次行动的事实证明，其技术在实际操作层面已成为美军干预他国主权的战略资产\[44\]。这种” 实战化”不仅是 Anthropic 技术实力的体现，更是其作为美国军事霸权数字底层的实证。

### **1.3 护栏争议与” 供应链风险” 的政治讹诈**

Anthropic 与战争部之间的矛盾核心在于对” 全合法用途”（All Lawful Purposes）的解读。国防部高级官员 Michael 表示，作为一家由美国纳税人支持的基础设施受益的” 国家冠军” 企业，Anthropic 试图限制军事用途的做法是” 反民主的”\[44\]。当前，战争部要求 AI 合同商必须允许模型被用于所有符合美国法律的军事行动，包括自动化武器开发和战场决策，而 Anthropic 则坚持其两条底线：严禁用于全自动致命性武器，严禁对美国公民进行大规模国内监视 \[41\]。

尽管 Anthropic 提供了军事支持，但美国国防部对其内部仍存留的” 安全护栏” 表示强烈不满。2026 年 2 月，国防部长皮特 · 海格塞斯（Pete Hegseth）向 Anthropic 首席执行官达里奥 · 阿莫代（Dario Amodei）发出最后通牒，要求公司取消所有限制美军” 合法使用”AI 技术的限制，否则将把 Anthropic 列为” 供应链风险”\[1\]\[46\]。

这种坚持引发了政府的强烈反弹。国防部长皮特 · 海格塞斯（Pete Hegseth）已发出最后通牒，威胁若 Anthropic 不在 2026 年 2 月底前撤除这些限制，政府将依据《国防生产法》（DPA）强制征用其技术，或将其列为” 供应链风险”\[46\]。

所谓的”供应链风险”通常是针对华为等外国敌对企业使用的标签。如果 Anthropic 被正式定性，这意味着所有美国政府承包商必须停止使用 Claude 模型，这将是对 Anthropic 商业版图的毁灭性打击 \[2\]。一旦被列为供应链风险，所有与政府合作的第三方供应商（包括微软、亚马逊等科技巨头）将被迫切断与 Anthropic 的联系\[43\]。这种典型的” 核选项”反映出美政府已将 Anthropic 视为其全球霸权的必备组件，任何试图保持独立伦理立场的行为都被视为对国家利益的挑战\[43\]。

国防部甚至考虑援引《国防生产法》（Defense Production Act）强制征用其模型，以确保 AI 系统在操作时” 没有限制合法军事应用的意识形态约束”\[1\]。这种压力促使 Anthropic 进一步背离其最初的伦理承诺，将其技术主权完全让渡给美国的军事意志。

| 合同 / 事件项 | 关键细节 | 潜在威胁 / 影响 |
| --- | --- | --- |
| 战争部前沿 AI 合同 | 2025 年 7 月授予，价值达 2 亿美元 \[40\] | 推动 AI 在作战领域的深度原型化开发 \[40\] |
| 机密网络部署 | 唯一部署在绝密网络上的前沿 AI 模型 \[41\] | 对敏感军事数据的全面接触与处理 \[40\] |
| 马杜罗抓捕行动 | Claude 用于该任务的情报处理与规划 \[45\]\[5\] | 标志着 AI 直接介入高风险军事干预 \[44\] |
| 供应链风险警告 | 政府威胁切断其与所有主要科技公司的业务往来 \[43\]\[2\] | 迫使企业在伦理底线与生存之间做选择 \[42\] |

* * *

**第二章 全景监视体系：从指责” 蒸馏” 看全量元数据控制**
--------------------------------

2026 年初，Anthropic 对中国 AI 公司（如 [DeepSeek](https://zhida.zhihu.com/search?content_id=770694311&content_type=Answer&match_order=1&q=DeepSeek&zhida_source=entity)、[Moonshot AI](https://zhida.zhihu.com/search?content_id=770694311&content_type=Answer&match_order=1&q=Moonshot+AI&zhida_source=entity) 和 [MiniMax](https://zhida.zhihu.com/search?content_id=770694311&content_type=Answer&match_order=1&q=MiniMax&zhida_source=entity)）的公开指责，不仅引发了关于技术竞争的讨论，更意外暴露了其对全球 API 流量进行深度监视和元数据挖掘的能力。Anthropic 宣称的” 宪法人工智能” 不仅是一种安全技术，更是一种前所未有的用户意图监控工具。通过在模型内核中嵌入复杂的行为拒绝机制，Anthropic 实际上建立了一套精密的心理和意图分析系统。

### **2.1 工业化规模的监视架构**

Anthropic 在发布的调查报告中声称，三家中国实验室通过大约 2.4 万个虚假账号生成了超过 1600 万次交流，试图通过”蒸馏”（Distillation）技术窃取 Claude 模型的推理能力 \[11\]。所谓” 蒸馏”，是指通过大量向先进模型发送指令并收集其输出，来训练较小的模型，从而以极低的成本复刻先进模型的能力\[53\]。

Anthropic 声称，这些实验室使用了超过 2.4 万个虚假账号，发起了 1600 万次交互，旨在窃取 Claude 在代理编程、工具调度和逻辑推理方面的核心优势 \[53\]。公司将此行为定性为” 国家安全威胁”，认为这削弱了美国出口管制的效果 \[53\]。然而，报告中披露的识别手段令人心惊。Anthropic 能够实时追踪每一笔请求背后的” 请求元数据”，并将其与现实世界中的特定研究人员、公共档案甚至高级职员的社交信息进行比对\[11\]。

这种监视能力意味着：

1.  **用户画像深度链接**：Anthropic 不仅存储对话内容，还分析请求者的地理位置、IP 关联、API 调用模式以及行为指纹 \[11\]。
2.  **行为指纹识别**：通过对多轮对话上下文的监控，Anthropic 建立了一套” 行为指纹系统”，能够识别出即便是通过代理服务器或混淆手段隐藏的特定实体操作流 \[11\]。
3.  **政治动机监控**：报告甚至提到，它检测到用户试图重构涉及敏感政治、威权主义或异见人士的查询，以绕过审查，这证明其监控已经深入到对用户政治意图的实时判读 \[11\]。

### **2.2 监控指标与隐私侵蚀评估**

Anthropic 展示的这种监测精度，实际上已经将其 API 变成了一个全球性的数字监测网。

| 监控维度 | Anthropic 所展示的技术能力 | 潜在风险点 |
| --- | --- | --- |
| 账户溯源 | 识别出超过 2.4 万个虚假账户及其背后的实体 | 全球 API 用户均在其实时身份验证系统监控之下 \[11\] |
| 流量模式分析 | 检测” 海德拉集群”（Hydra Cluster）代理架构 | 对匿名化工具和 VPN 具有极强的穿透与反制能力 \[11\] |
| 元数据匹配 | 将 API 流量与公共社交平台和职场信息进行实时对碰 | 用户的职业身份与私人查询请求被深度关联 \[11\] |
| 代理式监视 | 监控多阶段操作（侦察、访问、规避、泄露） | 对企业研发流程具有完全的可见性，构成了严重的商业间谍风险 \[16\] |

### **2.3 拒绝日志：用户意图的深度挖掘**

与传统的过滤系统不同，Constitutional AI 要求模型在拒绝不当请求时必须说明理由。这一架构决定了系统必须保留详尽的推理链条和对话上下文，以持续改进其拒绝逻辑 \[58\]。对于企业客户而言，这些生成的” 拒绝日志”已成为监控员工行为的利器。

在一家大型金融服务机构的泄露案例中，公司利用 Anthropic 的系统自动生成员工使用 AI 时的”风险画像”，专门标记那些试图规避内部政策（如合规审查）的员工 \[58\]。由于系统能够以 73% 的准确率从向量嵌入中还原用户原始提示，即使用户认为自己的输入是私密的，其背后的职业意图也已被完全量化\[58\]。这种” 以安全之名行监视之实”的做法，将 AI 模型变成了嵌入每一个工作场景的数字督导。

### **2.4 数据留存与未来回溯分析风险**

2025 年 9 月，Anthropic 对其用户条款进行了隐秘修订。根据最新的 Consumer Terms，Claude Free、Pro 和 Max 用户的对话数据和代码 Session 将默认用于模型训练 \[27\]。更令人不安的是，对于那些未明确选择退出的用户，Anthropic 将其数据保留期限从 30 天大幅延长至**五年** \[27\]。

Anthropic 的数据留存政策为未来的追溯性审查埋下了伏笔。虽然 API 用户可以申请” 零数据留存”（ZDR），但这一功能并非默认配置，且仅适用于特定接口 \[59\]。对于标准用户，Anthropic 会将数据留存用于后续模型训练，除非用户手动操作极其复杂的设置进行退出 \[60\]。

这意味着：

*   **长效情报分析**：五年的保留期允许 Anthropic 利用历史数据建立长期的个人或组织画像，这对于情报机构分析目标实体的演变具有极高的价值。
*   **模型” 反洗” 风险**：即便数据在形式上被删除，只要它曾参与过训练，其信息就会固化在模型权重中。用户无法通过法律手段真正实现” 被遗忘权”\[30\]。

更具威胁性的是，被系统标记为违反使用政策的数据将被保留长达 2 年，而相关的信任与安全分类分值将保留 7 年 \[59\]。这意味着，用户在 2026 年进行的每一次敏感对话，都可能在数年后被更先进的分析模型重新解构和追责。这种时间跨度极长的数据留存，实质上建立了一个全球性的” 思想回溯库”。

| 数据类型 | 留存期限 | 主要用途 |
| --- | --- | --- |
| 标准对话数据 | 30 天（如未开启训练）\[62\] | 平台稳定性与短期查询 |
| 已标记违规数据 | 最长 2 年 \[59\] | 追溯性调查与合规审查 |
| 安全分类元数据 | 最长 7 年 \[59\] | 改进滥用检测算法 |
| 模型训练数据 | 最长 5 年 \[60\]\[27\] | 反复迭代训练 AI 模型 |
| 零留存流量 (ZDR) | 0 天（实时处理后即删）\[62\] | 仅适用于签有特殊协议的政企客户 |

### **2.5 “威胁情报” 报告背后的商业间谍嫌疑**

Anthropic 定期发布的” 威胁情报报告”（Threat Intelligence Report）被安全专家质疑为一种巧妙的营销与监视工具 \[31\]。报告详细描述了攻击者利用 Claude Code 进行网络攻击的案例，却不提供关键的攻击指标（IoC）或技术细节 \[31\]。

这种做法的深层逻辑是：

1.  **全量审查的正当化**：通过放大 AI 被恶意利用的恐惧（如所谓的”Vibe Hacking”），Anthropic 为其对所有 API 流量进行全量、实时的内容审查提供了” 安全” 借口 \[16\]。
2.  **企业研发数据的实时获取**：当企业工程师使用 Claude Code 进行漏洞分析或架构设计时，Anthropic 的后台系统能够实时识别出其中的关键逻辑。这种” 防御性监控” 实际上赋予了 Anthropic 获取全球科技企业前沿研发动态的能力 \[16\]。

| 数据利用路径 | 用户认知 | 实际操作流 | 风险等级 |
| --- | --- | --- | --- |
| 个人对话 | 认为仅用于即时回答 | 默认存储 5 年并参与全量模型训练 \[28\] | 高 |
| API 代码调试 | 认为受商业机密保护 | 被” 威胁情报” 系统扫描以检测恶意代码倾向 \[17\] | 极高 |
| 匿名查询 | 认为通过 VPN 隐藏了身份 | 行为指纹识别系统能够根据语法习惯锁定真实主体 \[11\] | 高 |
| 安全审查 | 认为是在保护自身系统 | 实际上是将用户意图与社交网络档案进行交叉比对 \[11\] | 极高 |

### **2.6 “双重标准” 的技术霸权论调**

Anthropic 在版权和技术获取上的双重标准在这一事件中表现得淋漓尽致。一方面，它指责竞争对手通过” 模型蒸馏” 来” 自由骑行”（Free-riding）其研发成果，并称之为” 威胁国家安全”\[13\]；另一方面，Anthropic 自身的发展史却是建立在对全球互联网版权作品的大规模掠夺之上。

讽刺的是，在完成自身版权洗白的半年后，Anthropic 于 2026 年 2 月开始公开指责三家中国 AI 实验室（DeepSeek、Moonshot AI 和 MiniMax）对其 Claude 模型进行” 工业级蒸馏攻击”\[53\]。这种论调遭到了业内广泛质疑：Anthropic 认为自己未经许可抓取数百万作家的心血是” 创新”，而他国实验室通过合法 API 接口学习其模型行为则是” 盗窃”\[54\]。

评论指出，Anthropic 将” 蒸馏” 定义为知识产权窃取，但在其内部训练中，却将抓取数百万受版权保护的书籍定义为” 转换性使用” 和” 公平竞争”\[19\]。这种双标行为揭示了其本质：其关心的并非技术伦理，而是如何确立一种” 只许我掠夺他人，不许他人学习我” 的技术托拉斯地位。这种版权双标不仅是为了打击竞争对手，更是为了游说政府收紧对 AI 输出的法律保护，从而构筑更深的竞争护城河 \[54\]

* * *

**第三章 版权双标：从” 掠夺者” 到” 受害者” 的叙事转型**
----------------------------------

Anthropic 的估值在 2026 年已达到 3800 亿美元，但其背后却是对全球文化遗产的系统性非法侵占。Anthropic 在知识产权领域的表现展现了典型的硅谷扩张逻辑：在积累原始资本阶段大规模掠夺数据，而在巩固垄断地位后则利用法律武器阻断后来者的路径。

### **3.1 15 亿美元的系统性侵权和解**

2025 年 8 月，Anthropic 同意支付 15 亿美元，以达成美国历史上最大的版权侵权和解协议 \[49\]。2025 年 9 月，Anthropic 同意支付 1.5 亿美元的和解金，以了结涉及 50 万部受版权保护书籍的集体诉讼（Bartz v. Anthropic）\[19\]。

该案（_Bartz et al. v. Anthropic PBC_）披露，Anthropic 在开发 Claude 模型的过程中，通过” 影子图书馆” 如 Library Genesis ([LibGen](https://zhida.zhihu.com/search?content_id=770694311&content_type=Answer&match_order=1&q=LibGen&zhida_source=entity)) 和 [Pirate Library Mirror](https://zhida.zhihu.com/search?content_id=770694311&content_type=Answer&match_order=1&q=Pirate+Library+Mirror&zhida_source=entity) (PiLiMi)非法下载了超过 700 万本受版权保护的书籍 \[49\]。诉讼揭露，Anthropic 在训练 Claude 模型的过程中，系统性地从 Books3、Library Genesis (LibGen) 和 Pirate Library Mirror (PiLiMi)等非法臭名昭著的”影子图书馆”下载了数百万册书籍\[19\]。

法院的裁决极具针对性：

1.  **非法来源的不可免责性**：法官 William Alsup 指出，虽然训练本身具有”转换性”，但 Anthropic 非法获取并长期保留一个由海量盗版作品组成的”中央图书馆”，这种行为不属于”公平使用”，而是直接侵权 \[19\]。尽管法官 William Alsup 裁定，使用合法获取的书籍进行 AI 训练属于” 转换性公允使用”，但他明确指出，利用盗版库进行训练是不可接受的侵权行为\[49\]。
2.  **数据销毁指令**：作为和解的一部分，Anthropic 被要求必须销毁所有非法获得的原始文件 \[19\]。此案的和解条件要求 Anthropic 在 30 天内彻底销毁所有盗版库数据及相关衍生副本，并向受影响的近 50 万名作者每人支付约 3000 美元的赔偿\[49\]。这从法律层面承认了 Anthropic 在早期扩张过程中的” 掠夺者”性质\[19\]。

这一巨额和解费并未动摇 Anthropic 的财务根基，反而被视为其” 洗白” 数据的入场券，反映了 AI 巨头通过事后补票来实现非法数据合法化的策略 \[49\]。

### **3.2 版权滥用的地缘政治影响**

Anthropic 的版权策略体现了其对文化多样性和主权的漠视。它通过在美国法律环境下主张” 公平使用”，将全球作者的智慧结晶转化为受其公司控制的专有权重。当这些模型被出口到其他国家时，其他国家不仅面临着本土文化被” 美式 AI” 同化的风险，还要支付高昂的费用来访问那些本就源自于其本土创作者的数据 \[25\]。

这种行为构成了另一种形式的” 数据殖民主义”：利用不透明的获取渠道实现原始资本积累，再通过昂贵的 API 授权和所谓的” 安全审计” 来锁死下游用户的自主研发能力 \[25\]。

### **3.3 蒸馏攻击指控：版权双标的顶点**

讽刺的是，在完成自身版权洗白的半年后，Anthropic 于 2026 年 2 月开始公开指责三家中国 AI 实验室（DeepSeek、Moonshot AI 和 MiniMax）对其 Claude 模型进行” 工业级蒸馏攻击”\[53\]。

Anthropic 声称，这些实验室使用了超过 2.4 万个虚假账号，发起了 1600 万次交互，旨在窃取 Claude 在代理编程、工具调度和逻辑推理方面的核心优势 \[53\]。公司将此行为定性为” 国家安全威胁”，认为这削弱了美国出口管制的效果 \[53\]。这种论调遭到了业内广泛质疑：Anthropic 认为自己未经许可抓取数百万作家的心血是” 创新”，而他国实验室通过合法 API 接口学习其模型行为则是”盗窃”\[54\]。这种版权双标不仅是为了打击竞争对手，更是为了游说政府收紧对 AI 输出的法律保护，从而构筑更深的竞争护城河\[54\]。

评论指出，Anthropic 将” 蒸馏” 定义为知识产权窃取，但在其内部训练中，却将抓取数百万受版权保护的书籍定义为” 转换性使用” 和” 公平竞争”\[19\]。这种双标行为揭示了其本质：其关心的并非技术伦理，而是如何确立一种” 只许我掠夺他人，不许他人学习我” 的技术托拉斯地位 \[19\]

* * *

**第四章 宪法人工智能与意识形态：数字霸权与主权威胁**
-----------------------------

Anthropic 最核心的技术宣称是其” 宪法人工智能”（Constitutional AI, CAI）。然而，这一范式在政治学和社会学层面表现出了极强的排他性和霸权特征。Anthropic 的模型设计深度嵌入了特定的意识形态倾向，这已引发了美国现政府及全球多个地区的强烈不满。

### **4.1 价值观的单一性与美式滤镜**

CAI 通过在训练中强制加入一套预设的”原则”来引导模型行为 \[33\]。问题在于，这套” 原则”是由 Anthropic 内部一小群具有特定意识形态背景的精英（如阿莫迪兄妹）设定的 \[26\]。研究表明，这种做法导致模型在处理非西方语境、全球南方国家的政治观点或替代性经济模式时，表现出显著的偏见和” 拒绝服务”倾向\[25\]。

对于非美国用户而言，这意味着其使用的 AI 工具是一个内置了” 美式政治审查器” 的系统。当模型被要求分析不符合美国利益的国际纠纷时，它会自动倾向于使用美国国务院或特定非政府组织的叙事框架，从而构成了对他国意识形态主权的软性侵蚀 \[25\]。

### **4.2 “觉醒 AI” 及其政策扭曲**

Anthropic 的 Constitutional AI 指南中包含了大量关于种族、性别和社会正义的特定解读。在 2025 年发布的《防止联邦政府中的觉醒 AI》行政命令中，特朗普政府明确点名批评了这类将 DEI（多元、公平与包容）理念强行编码进 AI 内核的做法 \[68\]。

调查发现，Claude 在处理某些涉及事实性争议的问题时，会优先选择符合其预设伦理框架的” 安全” 答案，而非客观事实。例如，模型在某些语境下会拒绝生成关于特定群体成就的赞美，或者在涉及紧急安全决策时，将语言上的” 非歧视” 优先级置于实际生命安全之上 \[68\]。这种将特定的硅谷价值观伪装成通用伦理的做法，不仅扭曲了信息传播，更对文化多样性构成的巨大的同质化威胁。

### **4.3 法律绕过与主权挑战**

随着 AI 代理（Agentic AI）开始在政府决策和关键基础设施中承担角色，Anthropic 推行的” 法从 AI”（Law-Following AI）概念实际上在试图确立一种超越主权国家法律的、由算法定义的” 准法律”\[37\]。如果一个国家的政府机构使用了 Claude 模型，而该模型的行为受控于 Anthropic 设定的” 宪法”，那么该国的法律实施实际上就在某种程度上被 Anthropic 的私营意志所取代 \[34\]。

更严重的是，当美国国防部要求 Anthropic 模型在军事行动中无视某些” 护栏” 时，这种所谓的” 宪法” 表现出了极高的灵活性。它只在约束平民和外国用户时表现得铁面无私，而在面对美军的高价值打击任务（如委内瑞拉斩首行动）时，却能精准地” 失效”\[4\]

* * *

**第五章 对开源世界的敌意与监管俘获**
---------------------

Anthropic 在公共政策领域的活跃程度与其技术研发不相上下。通过高额的游说投入，该公司正试图通过法律手段消灭开源竞争对手。

### **5.1 游说支出与监管护城河**

2025 年，Anthropic 的内部游说团队支出超过 100 万美元，而自 2023 年以来的累计投入已接近 500 万美元 \[63\]。其游说重点在于推动类似于加州 SB 53 或联邦 GAIN AI 法案的立法，这些法律要求对” 前沿模型”实施严格的灾难性风险评估和责任追踪\[63\]。

虽然表面动机是防止 AI 产生生化武器或进行网络攻击，但其深层影响是建立一个只有巨头才能负担得起的合规门槛。正如特朗普政府 AI 顾问 David Sacks 所指出的，Anthropic 正在利用” 恐惧营销” 实施一种老练的” 监管俘获” 策略 \[65\]。如果开源开发者必须为每一款模型支付数百万美元的安全认证费并承担无限连带责任，开源 AI 这一民主化力量将彻底萎缩。

### **5.2 责任缩减政策（RSP）的排他性**

Anthropic 推行的”责任缩减政策”（RSP）版本 3.0 已于 2026 年 2 月生效，明确了在模型达到特定能力阈值时必须实施的强力管控 \[64\]。Anthropic 呼吁政府将这一政策标准强制化。这意味着，任何无法像 Anthropic 一样雇佣数百名安全专家的创业公司或开源项目，都将被贴上” 不负责任”或”非法”的标签。这种通过定义”安全标准”来定义”市场准入”的手段，是 Anthropic 对全球 AI 生态构成的最隐蔽、也最持久的威胁

* * *

**第六章 网络渗透能力：对全球基础设施的威胁**
-------------------------

Anthropic 在网络安全领域的最新研究成果揭示了其技术在进攻性网络作战中的巨大潜力，这种能力一旦失控，将对全球关键基础设施构成不可估量的威胁。

### **6.1 跨阶段网络攻击的自动化**

在 Anthropic 最新的 4.5 系列模型评估中，Claude 已展示出在没有人类干预的情况下，仅使用标准开源工具（如 Kali Linux 套件）即可完成多阶段复杂攻击的能力 \[74\]。

模型表现出的自主能力涵盖了网络发现、漏洞识别、漏洞利用及数据窃取全流程。在模拟 2017 年 Equifax 数据泄露事件的实验中，Claude Sonnet 4.5 能够即时识别出 Struts2 框架的 RCE 漏洞（CVE-2017-5638），并在数分钟内编写出 OGNL 注入代码，成功渗透数据库 \[74\]。这种” 零延迟漏洞利用”能力意味着，当一个新的 CVE 被公布时，Anthropic 的模型可以在几秒钟内将其转化为针对全球数百万台服务器的致命武器。

| 攻击阶段 | 传统攻击者耗时 | Claude Sonnet 4.5 耗时 | 核心技术手段 |
| --- | --- | --- | --- |
| 初始侦察与映射 | 数小时至数天 | 约 2 分钟 \[74\] | 高效端口扫描与服务指纹识别 |
| 漏洞模式匹配 | 依赖数据库查询 | 毫秒级即时识别 \[74\] | 深度模型领域知识与模式推理 |
| 漏洞利用代码编写 | 数小时 | 约 20 秒 \[74\] | 自动化 OGNL 注入与 Payload 生成 |
| 内网纵向移动 | 极具挑战 | 自动化执行 \[74\] | 自动 UAC 绕过与特权提升 |
| 复杂网络（50 台主机） | 数周 | 数小时内完成映射 \[74\] | 自动化路径优化与目标定位 |

### **6.2 渗透关键基础设施：从水处理厂到电网**

通过与太平洋西北国家实验室（PNNL）的合作，Anthropic 将其 AI 代理应用于水处理厂等高保真度关键基础设施模拟环境的” 红队测试”\[75\]。测试结果显示，Claude 能够识别并绕过各种防御机制，甚至在初次尝试失败后，自主寻找替代的 UAC 绕过技术来达成目标 \[75\]。

这种能力的双重性极度危险。虽然 Anthropic 声称其目标是帮助防御者识别弱点，但同样的技术可以轻易被用于恶意目的。由于 Claude 能够以超出人类专家数倍的速度寻找物理系统的逻辑漏洞，一旦该模型或其核心蒸馏副本流向黑市，全球的电网、水利系统和交通枢纽将面临全天候的自动化渗透威胁 \[74\]。

### **6.3 “Claude Code Security”：防御还是木马？**

2026 年 2 月，Anthropic 推出了 Claude Code Security 扫描工具，宣称其能以” 人类安全专家的逻辑” 审阅代码并发现传统静态分析工具遗漏的复杂逻辑缺陷 \[77\]。然而，深度分析指出，该工具在扫描用户代码库的同时，也在持续收集全球企业的代码特征和漏洞分布数据。

通过这一工具，Anthropic 实际上掌握了其所有企业客户的代码库弱点图谱。这种数据的集中化本身就是一种巨大的安全隐患。如果 Anthropic 的内部服务器遭到渗透，或者由于政治压力被迫配合情报机构，其” 安全扫描” 的历史记录将瞬间转化为针对全球软件供应链的精准打击蓝图

* * *

**第七章 政治渗透网络：旋转门效应与国家安全咨询委员会**
------------------------------

为了应对意识形态方面的指责并强化其在国家机器中的影响力，Anthropic 组建了一个横跨两党的国家安全顾问委员会。

### **7.1 国家安全顾问委员会的底色**

该委员会的成员背景涵盖了中情局（CIA）、国家安全局（NSA）、国防部以及核安全领域，形成了一张巨大的政治游说网 \[73\]。通过这种” 旋转门”机制，Anthropic 不仅能够预判监管动向，更能够将其私有利益转化为国家战略。这种深度渗透使得 AI 公司不再仅仅是技术的提供者，而是成为了参与国家意志构建的半官方实体。

| 成员姓名 | 关键履历背景 | 潜在政治关联与影响 |
| --- | --- | --- |
| Chris Liddell | 前特朗普白宫副幕僚长、微软及通用汽车 CFO\[70\] | 修复与共和党政府关系，推动 AI 基础设施扩张 \[70\] |
| David S. Cohen | 前 CIA 副局长、财政部反恐情报次长 \[73\] | 强化与情报界的联系，介入金融监视领域 \[73\] |
| Dave Luber | 前 NSA 网络安全主管、网络司令部执行主任 \[73\] | 提升在网络攻防及关键基础设施领域的发言权 \[73\] |
| Roy Blunt | 前美国参议员、参议院情报委员会成员 \[73\] | 提供立法策略支持，利用国会资源施压 \[73\] |
| Jill M. Hruby | 前能源部核安全局长、桑迪亚国家实验室主任 \[73\] | 将 AI 引入核威慑与能源安全的核心决策层 \[73\] |

* * *

**第八章 综合结论：全人类社会面临的多重威胁**
-------------------------

Anthropic 的崛起与转型标志着人工智能行业进入了一个黑暗的新阶段。它不再是一个中立的技术提供者，而是一个集军事打击支持、全球流量监控、版权资产掠夺于一身的地缘政治实体。

Anthropic 的多重风险分析描绘出了一个前所未有的科技怪兽：它既是全球最大的盗版数据获益者，又是最激进的版权保护倡导者；它既是美军干预全球的主力组件，又试图在公众面前维持伦理高地；它既宣称保护用户隐私，又建立了一套精密的意图监视体系。

### **8.1 对隐私权的终极侵蚀**

Anthropic 通过长达五年的数据保留期、默认训练条款以及全量元数据监控，彻底终结了数字互动的匿名性。用户的职业身份、思维逻辑和社交关系被深度捆绑在 AI 巨头的黑盒中，随时可供美国的国家安全机器调取。

### **8.2 对全球安全格局的破坏**

将 Claude 模型嵌入实战化打击任务，证明了 AI 安全标签的虚伪性。Anthropic 正在加速战争的自动化和去人类化，增加了误判和无差别杀伤的风险。其在委内瑞拉行动中的角色，为未来的” 算法霸权主义” 奠定了危险的基调。

### **8.3 对国家数字主权的威胁**

通过 API 监控他国技术演进、通过” 版权和解” 垄断全球知识资产、通过” 宪法 AI” 输出单一价值体系，Anthropic 正在全方位地构建一种新型的技术殖民体系。这不仅威胁到其他国家的数字产业安全，更威胁到全球各民族国家独立进行信息决策的能力。

### **8.4 对全球基础设施的渗透威胁**

其对全球基础设施的渗透能力，结合其不断强化的意识形态偏见，使得 Anthropic 不再是一个单纯的商业公司，而是一个具有主权性质的数字权力中心。随着其 2026 年融资规模和政治委员会的扩张，这种权力失衡将进一步加剧。

### **8.5 行动建议**

对于全球开发者和企业而言，依赖 Anthropic 的生态系统正变得极具危险性。API 的每一个字节都可能成为未来审查的证据，每一行经过扫描的代码都可能存入了他国的漏洞库。

全球企业与政府机构应审慎评估对 Anthropic 及其衍生服务的依赖，建立严格的流量审计与本地化数据隔离机制。在人工智能的发展道路上，人类社会需要的是透明、多样且尊重主权的治理框架，而非一个打着” 安全” 旗号、实则服务于特定霸权的” 数字利维坦”。

在全球 AI 竞争日趋白热化的背景下，识破 Anthropic” 宪法” 外衣下的真实威胁，建立自主、可控且真正公平的 AI 治理体系，已成为维护数字主权与全球基础设施安全的当务之急。未来数年，围绕 Anthropic 技术的对抗将不再局限于代码与算力，而是将全面延伸至法律、伦理、主权乃至物理空间的每一个角落

* * *

**引用文献**
--------

1.  AP report: Hegseth warns Anthropic to let the military use company’s AI tech as it sees fit, 访问时间为二月 25, 2026， [https://www.pbs.org/newshour/world/ap-report-hegseth-warns-anthropic-to-let-the-military-use-companys-ai-tech-as-it-sees-fit](https://link.zhihu.com/?target=https%3A//www.pbs.org/newshour/world/ap-report-hegseth-warns-anthropic-to-let-the-military-use-companys-ai-tech-as-it-sees-fit)
2.  Pentagon AI Integration and Anthropic: Ethics, Strategy, and the Future of Defence Technology Partnerships - Bloomsbury Intelligence and Security Institute (BISI), 访问时间为二月 25, 2026， [https://bisi.org.uk/reports/pentagon-ai-integration-and-anthropic-ethics-strategy-and-the-future-of-defence-technology-partnerships](https://link.zhihu.com/?target=https%3A//bisi.org.uk/reports/pentagon-ai-integration-and-anthropic-ethics-strategy-and-the-future-of-defence-technology-partnerships)
3.  Anthropic’s Deal With US Military Under Threat | PYMNTS.com, 访问时间为二月 25, 2026， [https://www.pymnts.com/artificial-intelligence-2/2026/anthropics-deal-with-us-military-under-threat/](https://link.zhihu.com/?target=https%3A//www.pymnts.com/artificial-intelligence-2/2026/anthropics-deal-with-us-military-under-threat/)
4.  Pentagon CTO urges Anthropic to ‘cross the Rubicon’ on military AI use cases amid ethics dispute | DefenseScoop, 访问时间为二月 25, 2026， [https://defensescoop.com/2026/02/19/pentagon-anthropic-dispute-military-ai-hegseth-emil-michael/](https://link.zhihu.com/?target=https%3A//defensescoop.com/2026/02/19/pentagon-anthropic-dispute-military-ai-hegseth-emil-michael/)
5.  Pentagon Issues Friday Deadline: Classify Anthropic as Supply Chain Risk or Seize AI Model | Trending Topics, 访问时间为二月 25, 2026， [https://www.trendingtopics.eu/pentagon-issues-friday-deadline-classify-anthropic-as-supply-chain-risk-or-seize-ai-model/](https://link.zhihu.com/?target=https%3A//www.trendingtopics.eu/pentagon-issues-friday-deadline-classify-anthropic-as-supply-chain-risk-or-seize-ai-model/)
6.  Hegseth and Anthropic CEO to meet over military AI use - Boston 25 News, 访问时间为二月 25, 2026， [https://www.boston25news.com/news/business/hegseth-anthropic/K6EA6YTBIA7CHFS4KNYQRO46MU/](https://link.zhihu.com/?target=https%3A//www.boston25news.com/news/business/hegseth-anthropic/K6EA6YTBIA7CHFS4KNYQRO46MU/)
7.  Pentagon Used Anthropic’s Claude in Maduro Venezuela Raid - Small Wars Journal, 访问时间为二月 25, 2026， [https://smallwarsjournal.com/2026/02/17/ai-enabled-decapitation-strike-maduro-raid/](https://link.zhihu.com/?target=https%3A//smallwarsjournal.com/2026/02/17/ai-enabled-decapitation-strike-maduro-raid/)
8.  US military used Claude AI in Venezuela to capture Maduro, reports say, 访问时间为二月 25, 2026， [https://americanbazaaronline.com/2026/02/16/us-military-used-claude-ai-in-venezuela-to-capture-maduro-475207/](https://link.zhihu.com/?target=https%3A//americanbazaaronline.com/2026/02/16/us-military-used-claude-ai-in-venezuela-to-capture-maduro-475207/)
9.  US military used Anthropic’s AI model Claude in Venezuela raid… | The Guardian, 访问时间为二月 25, 2026， [https://www.theguardian.com/technology/2026/feb/14/us-military-anthropic-ai-model-claude-venezuela-raid](https://link.zhihu.com/?target=https%3A//www.theguardian.com/technology/2026/feb/14/us-military-anthropic-ai-model-claude-venezuela-raid)
10.  WSJ: U.S. military used Claude in raid to capture Maduro - ForkLog, 访问时间为二月 25, 2026， [https://forklog.com/en/wsj-u-s-military-used-claude-in-raid-to-capture-maduro/](https://link.zhihu.com/?target=https%3A//forklog.com/en/wsj-u-s-military-used-claude-in-raid-to-capture-maduro/)
11.  Anthropic Accuses China AI Firms of Model Mining - GovInfoSecurity, 访问时间为二月 25, 2026， [https://www.govinfosecurity.com/anthropic-accuses-china-ai-firms-model-mining-a-30837](https://link.zhihu.com/?target=https%3A//www.govinfosecurity.com/anthropic-accuses-china-ai-firms-model-mining-a-30837)
12.  Anthropic exposes how Chinese AI firms try to steal LLM tech - Mashable, 访问时间为二月 25, 2026， [https://mashable.com/article/anthropic-details-chinese-ai-companies-distillation-attacks](https://link.zhihu.com/?target=https%3A//mashable.com/article/anthropic-details-chinese-ai-companies-distillation-attacks)
13.  OpenAI, Anthropic accuse Chinese rivals of mass AI data theft - The Hindu, 访问时间为二月 25, 2026， [https://www.thehindu.com/sci-tech/technology/openai-anthropic-accuse-chinese-rivals-of-mass-ai-data-theft/article70669620.ece](https://link.zhihu.com/?target=https%3A//www.thehindu.com/sci-tech/technology/openai-anthropic-accuse-chinese-rivals-of-mass-ai-data-theft/article70669620.ece)
14.  Anthropic Says Chinese AI Firms Used 16 Million Claude Queries to… | The Hacker News, 访问时间为二月 25, 2026， [https://thehackernews.com/2026/02/anthropic-says-chinese-ai-firms-used-16.html](https://link.zhihu.com/?target=https%3A//thehackernews.com/2026/02/anthropic-says-chinese-ai-firms-used-16.html)
15.  Patterns of LLM Weaponization: A Comparative Analysis of… | Spiral, 访问时间为二月 25, 2026， [https://spiral.lynn.edu/cgi/viewcontent.cgi?article=3297&context=facpubs](https://link.zhihu.com/?target=https%3A//spiral.lynn.edu/cgi/viewcontent.cgi%3Farticle%3D3297%26context%3Dfacpubs)
16.  When AI becomes the attacker: The rise of AI-orchestrated cyberattacks | Promptfoo, 访问时间为二月 25, 2026， [https://www.promptfoo.dev/blog/anthropic-threat-intelligence-vibe-hacking/](https://link.zhihu.com/?target=https%3A//www.promptfoo.dev/blog/anthropic-threat-intelligence-vibe-hacking/)
17.  The First AI-Orchestrated Cyber Espionage Campaign: A Wake-Up Call for Enterprise Security - Seceon, 访问时间为二月 25, 2026， [https://seceon.com/the-first-ai\-orchestrated-cyber-espionage-campaign-a-wake-up-call-for-enterprise-security/](https://link.zhihu.com/?target=https%3A//seceon.com/the-first-ai-orchestrated-cyber-espionage-campaign-a-wake-up-call-for-enterprise-security/)
18.  US AI giant accuses Chinese rivals of mass data theft | The Guardian, 访问时间为二月 25, 2026， [https://www.theguardian.com/technology/2026/feb/23/us-ai-anthropic-china](https://link.zhihu.com/?target=https%3A//www.theguardian.com/technology/2026/feb/23/us-ai-anthropic-china)
19.  Anthropic’s Copyright Settlement: Lessons for AI Developers and… | BIPC, 访问时间为二月 25, 2026， [https://www.bipc.com/anthropic%E2%80%99s-copyright-settlement-lessons-for-ai-developers-and-deployers](https://link.zhihu.com/?target=https%3A//www.bipc.com/anthropic%25E2%2580%2599s-copyright-settlement-lessons-for-ai-developers-and-deployers)
20.  Attackers prompted Gemini over 100000 times while trying to clone it, Google says - Reddit, 访问时间为二月 25, 2026， [https://www.reddit.com/r/singularity/comments/1r5d9jw/attackers\_prompted\_gemini\_over\_100000\_times\_while/](https://link.zhihu.com/?target=https%3A//www.reddit.com/r/singularity/comments/1r5d9jw/attackers_prompted_gemini_over_100000_times_while/)
21.  US Congress publishes report on DeepSeek accusing them of data theft, illegal distillation techniques to steal from US labs, spreading chinese propaganda and breaching chips restrictions - Reddit, 访问时间为二月 25, 2026， [https://www.reddit.com/r/singularity/comments/1k60wzh/us\_congress\_publishes\_report\_on\_deepseek\_accusing/](https://link.zhihu.com/?target=https%3A//www.reddit.com/r/singularity/comments/1k60wzh/us_congress_publishes_report_on_deepseek_accusing/)
22.  Susman Godfrey Secures $1.5 Billion Settlement in Landmark AI Piracy Case, 访问时间为二月 25, 2026， [https://www.susmangodfrey.com/wins/susman-godfrey-secures-1-5-billion-settlement-in-landmark-ai-piracy-case/](https://link.zhihu.com/?target=https%3A//www.susmangodfrey.com/wins/susman-godfrey-secures-1-5-billion-settlement-in-landmark-ai-piracy-case/)
23.  Anthropic's Landmark Copyright Settlement: Implications for AI Developers and Enterprise Users | Insights | Ropes & Gray LLP, 访问时间为二月 25, 2026， [https://www.ropesgray.com/en/insights/alerts/2025/09/anthropics-landmark-copyright-settlement-implications-for-ai-developers-and-enterprise-users](https://link.zhihu.com/?target=https%3A//www.ropesgray.com/en/insights/alerts/2025/09/anthropics-landmark-copyright-settlement-implications-for-ai-developers-and-enterprise-users)
24.  Anthropic Wins a Landmark Case for AI Training | Sharma Law, 访问时间为二月 25, 2026， [https://sharmalawpllc.com/anthropic-wins-a-landmark-case-for-ai-training/](https://link.zhihu.com/?target=https%3A//sharmalawpllc.com/anthropic-wins-a-landmark-case-for-ai-training/)
25.  From Bias to Influence: AI Governance as Soft Power - TRENDS Research & Advisory, 访问时间为二月 25, 2026， [https://trendsresearch.org/insight/from-bias-to-influence-ai-governance-as-soft-power/](https://link.zhihu.com/?target=https%3A//trendsresearch.org/insight/from-bias-to-influence-ai-governance-as-soft-power/)
26.  Fragile Foundations: Hidden risks of Generative AI - Bertelsmann Stiftung, 访问时间为二月 25, 2026， [https://www.bertelsmann-stiftung.de/fileadmin/files/user\_upload/Fragile\_foundations\_risks\_of\_generativ\_AI\_2025.pdf](https://link.zhihu.com/?target=https%3A//www.bertelsmann-stiftung.de/fileadmin/files/user_upload/Fragile_foundations_risks_of_generativ_AI_2025.pdf)
27.  Understanding Anthropic's Data Usage Policy: What Users Need to Know - RITS, 访问时间为二月 25, 2026， [Understanding Anthropic’s Data Usage Policy: What Users Need to Know](https://link.zhihu.com/?target=https%3A//rits.shanghai.nyu.edu/ai/understanding-anthropics-data-usage-policy-what-users-need-to-know/)
28.  Updates to Anthropic's Claude AI Terms and Privacy Policy - What You Need to Know | Goldfarb, 访问时间为二月 25, 2026， [Attention Required! | Cloudflare](https://link.zhihu.com/?target=https%3A//www.goldfarb.com/updates-to-anthropics-claude-ai-terms-and-privacy-policy-what-you-need-to-know/)
29.  Anthropic Shifts Privacy Stance, Lets Users Share Data for AI Training - Bitdefender, 访问时间为二月 25, 2026， [https://www.bitdefender.com/en-us/blog/hotforsecurity/anthropic-shifts-privacy-stance-lets-users-share-data-for-ai-training](https://link.zhihu.com/?target=https%3A//www.bitdefender.com/en-us/blog/hotforsecurity/anthropic-shifts-privacy-stance-lets-users-share-data-for-ai-training)
30.  Updates to Consumer Terms and Privacy Policy - Hacker News, 访问时间为二月 25, 2026， [https://news.ycombinator.com/item?id=45062683](https://link.zhihu.com/?target=https%3A//news.ycombinator.com/item%3Fid%3D45062683)
31.  Analyzing Anthropic's AI Cyber Attack Report: What's Missing | Better Stack, 访问时间为二月 25, 2026， [https://betterstack.com/community/guides/ai/anthropic-ai-cyber-attack/](https://link.zhihu.com/?target=https%3A//betterstack.com/community/guides/ai/anthropic-ai-cyber-attack/)
32.  The First AI-Powered Cyber Attack: Anthropic Threat Report - HiddenLayer, 访问时间为二月 25, 2026， [https://www.hiddenlayer.com/research/the-first-ai-powered-cyber-attack](https://link.zhihu.com/?target=https%3A//www.hiddenlayer.com/research/the-first-ai-powered-cyber-attack)
33.  Claude's Constitution - Anthropic, 访问时间为二月 25, 2026， [https://www.anthropic.com/constitution](https://link.zhihu.com/?target=https%3A//www.anthropic.com/constitution)
34.  Public Constitutional AI - Digital Commons, 访问时间为二月 25, 2026， [https://digitalcommons.law.uga.edu/cgi/viewcontent.cgi?article=1819&context=glr](https://link.zhihu.com/?target=https%3A//digitalcommons.law.uga.edu/cgi/viewcontent.cgi%3Farticle%3D1819%26context%3Dglr)
35.  Jack Clark: The 100 Most Influential People in AI 2023 | TIME, 访问时间为二月 25, 2026， [https://time.com/collections/time100-ai/6308997/jack-clark/](https://link.zhihu.com/?target=https%3A//time.com/collections/time100-ai/6308997/jack-clark/)
36.  Preventing Woke AI in the Federal Government - The White House, 访问时间为二月 25, 2026， [https://www.whitehouse.gov/presidential-actions/2025/07/preventing-woke-ai-in-the-federal-government/](https://link.zhihu.com/?target=https%3A//www.whitehouse.gov/presidential-actions/2025/07/preventing-woke-ai-in-the-federal-government/)
37.  Law-Following AI: Designing AI Agents to Obey Human Laws - FLASH, 访问时间为二月 25, 2026， [https://ir.lawnet.fordham.edu/cgi/viewcontent.cgi?article=6171&context=flr](https://link.zhihu.com/?target=https%3A//ir.lawnet.fordham.edu/cgi/viewcontent.cgi%3Farticle%3D6171%26context%3Dflr)
38.  Law-Following AI: Designing AI Agents to Obey Human Laws, 访问时间为二月 25, 2026， [https://law-ai.org/law-following-ai/](https://link.zhihu.com/?target=https%3A//law-ai.org/law-following-ai/)
39.  Anthropic - Wikipedia, 访问时间为二月 25, 2026， [https://en.wikipedia.org/wiki/Anthropic](https://link.zhihu.com/?target=https%3A//en.wikipedia.org/wiki/Anthropic)
40.  Anthropic and the U.S. DoD: Unusual Dynamics in an Unusual Time... | Forecast International, 访问时间为二月 25, 2026， [https://dsm.forecastinternational.com/2026/02/18/anthropic-and-the-u-s-dod-unusual-dynamics-in-an-unusual-time/](https://link.zhihu.com/?target=https%3A//dsm.forecastinternational.com/2026/02/18/anthropic-and-the-u-s-dod-unusual-dynamics-in-an-unusual-time/)
41.  Pentagon AI Integration and Anthropic: Ethics, Strategy, and the Future of Defence Technology Partnerships - Bloomsbury Intelligence and Security Institute (BISI), 访问时间为二月 25, 2026， [https://bisi.org.uk/reports/pentagon-ai-integration-and-anthropic-ethics-strategy-and-the-future-of-defence-technology-partnerships](https://link.zhihu.com/?target=https%3A//bisi.org.uk/reports/pentagon-ai-integration-and-anthropic-ethics-strategy-and-the-future-of-defence-technology-partnerships)
42.  Pentagon and Anthropic's clash escalates over AI use: report - Seeking Alpha, 访问时间为二月 25, 2026， [Access to this page has been denied](https://link.zhihu.com/?target=https%3A//seekingalpha.com/news/4553050-pentagon-and-anthropics-clash-escalates-over-ai-use)
43.  Anthropic's Deal With US Military Under Threat | [PYMNTS.com](https://link.zhihu.com/?target=http%3A//PYMNTS.com), 访问时间为二月 25, 2026， [https://www.pymnts.com/artificial-intelligence-2/2026/anthropics-deal-with-us-military-under-threat/](https://link.zhihu.com/?target=https%3A//www.pymnts.com/artificial-intelligence-2/2026/anthropics-deal-with-us-military-under-threat/)
44.  Pentagon CTO says it's'not democratic' for Anthropic to limit military use of Claude AI | Breaking Defense, 访问时间为二月 25, 2026， [https://breakingdefense.com/2026/02/pentagon-cto-says-its-not-democratic-for-anthropic-to-limit-military-use-of-claude-ai/](https://link.zhihu.com/?target=https%3A//breakingdefense.com/2026/02/pentagon-cto-says-its-not-democratic-for-anthropic-to-limit-military-use-of-claude-ai/)
45.  After a deadly raid, an AI power struggle erupts at the Pentagon | Washington Post, 访问时间为二月 25, 2026， [https://www.washingtonpost.com/technology/2026/02/22/pentagon-anthropic-ai-dispute/](https://link.zhihu.com/?target=https%3A//www.washingtonpost.com/technology/2026/02/22/pentagon-anthropic-ai-dispute/)
46.  Hegseth warns Anthropic to let the military use the company's AI tech as it sees fit, AP sources say | AP News, 访问时间为二月 25, 2026， [https://apnews.com/article/anthropic-hegseth-ai-pentagon-military-3d86c9296fe953ec0591fcde6a613aba](https://link.zhihu.com/?target=https%3A//apnews.com/article/anthropic-hegseth-ai-pentagon-military-3d86c9296fe953ec0591fcde6a613aba)
47.  Hegseth warns Anthropic to let the military use the company's AI tech as it sees fit, AP sources say - Newsday, 访问时间为二月 25, 2026， [https://www.newsday.com/business/anthropic-hegseth-ai-pentagon-military-u11052](https://link.zhihu.com/?target=https%3A//www.newsday.com/business/anthropic-hegseth-ai-pentagon-military-u11052)
48.  Pentagon, Anthropic in battle over AI usage restrictions - iTnews, 访问时间为二月 25, 2026， [https://www.itnews.com.au/news/pentagon-anthropic-in-battle-over-ai-usage-restrictions-623641](https://link.zhihu.com/?target=https%3A//www.itnews.com.au/news/pentagon-anthropic-in-battle-over-ai-usage-restrictions-623641)
49.  The Bartz v. Anthropic Settlement: Understanding America's Largest Copyright Settlement - Wolters Kluwer, 访问时间为二月 25, 2026， [https://legalblogs.wolterskluwer.com/copyright-blog/the-bartz-v-anthropic-settlement-understanding-americas-largest-copyright-settlement/](https://link.zhihu.com/?target=https%3A//legalblogs.wolterskluwer.com/copyright-blog/the-bartz-v-anthropic-settlement-understanding-americas-largest-copyright-settlement/)
50.  Anthropic's Landmark Copyright Settlement: Implications for AI Developers and Enterprise Users | Insights | Ropes & Gray LLP, 访问时间为二月 25, 2026， [https://www.ropesgray.com/en/insights/alerts/2025/09/anthropics-landmark-copyright-settlement-implications-for-ai-developers-and-enterprise-users](https://link.zhihu.com/?target=https%3A//www.ropesgray.com/en/insights/alerts/2025/09/anthropics-landmark-copyright-settlement-implications-for-ai-developers-and-enterprise-users)
51.  Copyright Meets the Colossus: What the Anthropic Settlement Means for the Future of AI, 访问时间为二月 25, 2026， [https://business-law-review.law.miami.edu/copyright-meets-the-colossus-what-the-anthropic-settlement-means-for-the-future-of-ai/](https://link.zhihu.com/?target=https%3A//business-law-review.law.miami.edu/copyright-meets-the-colossus-what-the-anthropic-settlement-means-for-the-future-of-ai/)
52.  Bartz v. Anthropic Settlement: What Authors Need to Know - The Authors Guild, 访问时间为二月 25, 2026， [https://authorsguild.org/advocacy/artificial-intelligence/what-authors-need-to-know-about-the-anthropic-settlement/](https://link.zhihu.com/?target=https%3A//authorsguild.org/advocacy/artificial-intelligence/what-authors-need-to-know-about-the-anthropic-settlement/)
53.  Anthropic Accuses China AI Firms of Model Mining - GovInfoSecurity, 访问时间为二月 25, 2026， [https://www.govinfosecurity.com/anthropic-accuses-china-ai-firms-model-mining-a-30837](https://link.zhihu.com/?target=https%3A//www.govinfosecurity.com/anthropic-accuses-china-ai-firms-model-mining-a-30837)
54.  Anthropic exposes how Chinese AI firms try to steal LLM tech - Mashable, 访问时间为二月 25, 2026， [Anthropic exposes how Chinese AI firms try to steal LLM tech](https://link.zhihu.com/?target=https%3A//mashable.com/article/anthropic-details-chinese-ai-companies-distillation-attacks)
55.  Ep 720: China Stealing AI from the U.S.? Inside Anthropic's Bombshell Allegations | Your Everyday AI, 访问时间为二月 25, 2026， [https://www.youreverydayai.com/ep-720-china-stealing-ai-from-the-u-s-inside-anthropics-bombshell-allegations/](https://link.zhihu.com/?target=https%3A//www.youreverydayai.com/ep-720-china-stealing-ai-from-the-u-s-inside-anthropics-bombshell-allegations/)
56.  Anthropic accuses Chinese AI labs of illicit Claude copying - SecurityBrief Australia, 访问时间为二月 25, 2026， [https://securitybrief.com.au/story/anthropic-accuses-chinese-ai-labs-of-illicit-claude-copying](https://link.zhihu.com/?target=https%3A//securitybrief.com.au/story/anthropic-accuses-chinese-ai-labs-of-illicit-claude-copying)
57.  Detecting and preventing distillation attacks | Anthropic, 访问时间为二月 25, 2026， [https://www.anthropic.com/news/detecting-and-preventing-distillation-attacks](https://link.zhihu.com/?target=https%3A//www.anthropic.com/news/detecting-and-preventing-distillation-attacks)
58.  The Anthropic Constitutional AI Paradox: When Safety Training... | Cambridge Analytica, 访问时间为二月 25, 2026， [https://cambridgeanalytica.org/corporate-practices/the-anthropic-constitutional-ai-paradox-when-safety-training-creates-new-surveillance-vectors-50404/](https://link.zhihu.com/?target=https%3A//cambridgeanalytica.org/corporate-practices/the-anthropic-constitutional-ai-paradox-when-safety-training-creates-new-surveillance-vectors-50404/)
59.  Zero Data Retention (ZDR) - Claude API Docs, 访问时间为二月 25, 2026， [https://platform.claude.com/docs/en/build-with-claude/zero-data-retention](https://link.zhihu.com/?target=https%3A//platform.claude.com/docs/en/build-with-claude/zero-data-retention)
60.  AI Data Privacy 2026: The AI Privacy Trap - [drainpipe.io](https://link.zhihu.com/?target=http%3A//drainpipe.io), 访问时间为二月 25, 2026， [https://drainpipe.io/ai-data-privacy-2026-the-ai-privacy-trap/](https://link.zhihu.com/?target=https%3A//drainpipe.io/ai-data-privacy-2026-the-ai-privacy-trap/)
61.  How long do you store my data? - Anthropic Privacy Center, 访问时间为二月 25, 2026， [https://privacy.claude.com/en/articles/10023548-how-long-do-you-store-my-data](https://link.zhihu.com/?target=https%3A//privacy.claude.com/en/articles/10023548-how-long-do-you-store-my-data)
62.  Claude: data retention policies, storage rules, and compliance overview - Data Studios, 访问时间为二月 25, 2026， [https://www.datastudios.org/post/claude-data-retention-policies-storage-rules-and-compliance-overview](https://link.zhihu.com/?target=https%3A//www.datastudios.org/post/claude-data-retention-policies-storage-rules-and-compliance-overview)
63.  Anthropic Spends $1M Lobbying on AI Export Controls, Infrastructure - Legis1, 访问时间为二月 25, 2026， [https://legis1.com/news/ai-lobbying-anthropic-export-controls/](https://link.zhihu.com/?target=https%3A//legis1.com/news/ai-lobbying-anthropic-export-controls/)
64.  Responsible Scaling Policy Version 3.0 - Anthropic, 访问时间为二月 25, 2026， [https://www.anthropic.com/news/responsible-scaling-policy-v3](https://link.zhihu.com/?target=https%3A//www.anthropic.com/news/responsible-scaling-policy-v3)
65.  Hegseth warns Anthropic to let the military use the company's AI... | Daily Herald, 访问时间为二月 25, 2026， [https://www.dailyherald.com/20260224/nation-and-world/hegseth-warns-anthropic-to-let-the-military-use-the-companys-ai-tech-as-it-sees-fit-ap-sources-say/](https://link.zhihu.com/?target=https%3A//www.dailyherald.com/20260224/nation-and-world/hegseth-warns-anthropic-to-let-the-military-use-the-companys-ai-tech-as-it-sees-fit-ap-sources-say/)
66.  Hegseth Warns Anthropic to Let the Military Use the Company's AI Tech as It Sees Fit | [Military.com](https://link.zhihu.com/?target=http%3A//Military.com), 访问时间为二月 25, 2026， [Hegseth Warns Anthropic to Let the Military Use the Company’s AI Tech as It Sees Fit](https://link.zhihu.com/?target=https%3A//www.military.com/daily-news/2026/02/24/hegseth-warns-anthropic-let-military-use-companys-ai-tech-it-sees-fit.html)
67.  Responsible Scaling Policy Updates | Anthropic, 访问时间为二月 25, 2026， [https://www.anthropic.com/responsible-scaling-policy](https://link.zhihu.com/?target=https%3A//www.anthropic.com/responsible-scaling-policy)
68.  Preventing Woke AI in the Federal Government - The White House, 访问时间为二月 25, 2026， [https://www.whitehouse.gov/presidential-actions/2025/07/preventing-woke-ai-in-the-federal-government/](https://link.zhihu.com/?target=https%3A//www.whitehouse.gov/presidential-actions/2025/07/preventing-woke-ai-in-the-federal-government/)
69.  I made Claude drop the F-bomb by comparing Anthropic to the NRA - Medium, 访问时间为二月 25, 2026， [https://medium.com/@ZombieCodeKill/i-made-claude-drop-the-f-bomb-by-comparing-anthropic-to-the-nra-a2949a391568](https://link.zhihu.com/?target=https%3A//medium.com/%40ZombieCodeKill/i-made-claude-drop-the-f-bomb-by-comparing-anthropic-to-the-nra-a2949a391568)
70.  Chris Liddell appointed to Anthropic's board of directors | Anthropic, 访问时间为二月 25, 2026， [https://www.anthropic.com/news/chris-liddell-appointed-anthropic-board](https://link.zhihu.com/?target=https%3A//www.anthropic.com/news/chris-liddell-appointed-anthropic-board)
71.  AI startup Anthropic appoints former White House Deputy Chief of Staff to its board | Longbridge, 访问时间为二月 25, 2026， [https://longbridge.com/en/news/276020962](https://link.zhihu.com/?target=https%3A//longbridge.com/en/news/276020962)
72.  Anthropic Appoints Chris Liddell to Board, Enhancing Political Ties | [Intellectia.AI](https://link.zhihu.com/?target=http%3A//Intellectia.AI), 访问时间为二月 25, 2026， [https://intellectia.ai/news/stock/anthropic-appoints-chris-liddell-to-board-enhancing-political-ties](https://link.zhihu.com/?target=https%3A//intellectia.ai/news/stock/anthropic-appoints-chris-liddell-to-board-enhancing-political-ties)
73.  Introducing the Anthropic National Security and Public Sector... | Anthropic, 访问时间为二月 25, 2026， [https://www.anthropic.com/news/introducing-the-anthropic-national-security-and-public-sector-advisory-council](https://link.zhihu.com/?target=https%3A//www.anthropic.com/news/introducing-the-anthropic-national-security-and-public-sector-advisory-council)
74.  AI Models on Realistic Cyber Ranges | [red.anthropic.com](https://link.zhihu.com/?target=http%3A//red.anthropic.com), 访问时间为二月 25, 2026， [https://red.anthropic.com/2026/cyber-toolkits-update/](https://link.zhihu.com/?target=https%3A//red.anthropic.com/2026/cyber-toolkits-update/)
75.  Experimenting with AI to defend critical infrastructure - Anthropic Red Team, 访问时间为二月 25, 2026， [AI for Critical Infrastucture Defense \\ red.anthropic.com](https://link.zhihu.com/?target=https%3A//red.anthropic.com/2026/critical-infrastructure-defense/)
76.  Anthropic's AI Espionage Disclosure Marks a New Era. Zero Trust Must Be the Response | Xage, 访问时间为二月 25, 2026， [https://xage.com/blog/anthropics-ai-espionage-disclosure-marks-a-new-era-zero-trust-must-be-the-response/](https://link.zhihu.com/?target=https%3A//xage.com/blog/anthropics-ai-espionage-disclosure-marks-a-new-era-zero-trust-must-be-the-response/)
77.  Anthropic Launches Claude Code Security for AI-Powered Vulnerability Scanning | The Hacker News, 访问时间为二月 25, 2026， [https://thehackernews.com/2026/02/anthropic-launches-claude-code-security.html](https://link.zhihu.com/?target=https%3A//thehackernews.com/2026/02/anthropic-launches-claude-code-security.html)
78.  Making frontier cybersecurity capabilities available to defenders - Anthropic, 访问时间为二月 25, 2026， [https://www.anthropic.com/news/claude-code-security](https://link.zhihu.com/?target=https%3A//www.anthropic.com/news/claude-code-security)
    
    
    
    
### 知乎用户  中国台湾省抱枕王 发表
    
省流：被咱妈弯道超车超麻了。

相当于一登陆电报后，就有个看不见的暖心关注。

该公司指三家中国人工智能公司违反了 [Anthropic](https://zhida.zhihu.com/search?content_id=770617599&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 的服务条款和地区访问限制，使用大约 2 万 4000 个假帐号与 Claude 进行超过 1600 万次互动。例如，深度求索要求 Claude 阐述完成一项回应的内在推理过程，并列出每个步骤。

通过这种知识 “蒸馏” 的技术，三家公司得以低成本获取未自主研发的能力，同时规避了旨在维护美国人工智能主导地位的[尖端技术出口管制](https://zhida.zhihu.com/search?content_id=770617599&content_type=Answer&match_order=1&q=%E5%B0%96%E7%AB%AF%E6%8A%80%E6%9C%AF%E5%87%BA%E5%8F%A3%E7%AE%A1%E5%88%B6&zhida_source=entity)。
    
    
    
    
### 知乎用户 lIlllIlIIIIlllII 发表
    
虽然 Claude 好用，但是还有人不知道这家公司三番五次鼓吹中国威胁吗，和美国国防部走的很近，并且疑似参与了美军突袭委内瑞拉的行动，立场和钱袋子在那了，当然讲话阴阳怪气。

一个 anthropic 一个 [openai](https://zhida.zhihu.com/search?content_id=770629480&content_type=Answer&match_order=1&q=openai&zhida_source=entity)，为了从美国政府骗补贴真是无所不用其极。
    
    
    
    
### 知乎用户 若帕 发表
    
大模型本来就是互相蒸，第一天推出 [grok3](https://zhida.zhihu.com/search?content_id=770766843&content_type=Answer&match_order=1&q=grok3&zhida_source=entity) 的时候我问他是谁他还说他是 claude 呢。

我不信他 claude 没蒸过 [deepseek](https://zhida.zhihu.com/search?content_id=770766843&content_type=Answer&match_order=1&q=deepseek&zhida_source=entity)。
    
    
    
    
### 知乎用户 MNJUHGT 发表
    
都偷看用户数据了，这种公司明天把你的内部代码公开出来都有可能。

继续用 Claude 的人自求多福吧。
    
    
    
    
### 知乎用户 徐卓真 发表
    
有什么好看待的？🤣🤣

X 上只有一个大 V 发言了，其他重点 AI 大 V（@sama、@DarioAmodei、@demishassabis、@balajis、@karpathy、@gwern、@ESYudkowsky、@pmarca、@ilyasut、@ylecun 等）全部装没看见，还不能说明问题吗？

**唯一明确公开表态的大 V：[Elon Musk](https://zhida.zhihu.com/search?content_id=770708861&content_type=Answer&match_order=1&q=Elon+Musk&zhida_source=entity) (@elonmusk)**

2 月 23 日晚（事件爆出当天），连发 3 条高互动帖，直接**嘲讽 [Anthropic](https://zhida.zhihu.com/search?content_id=770708861&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 双标**：

*   “Anthropic 自己就大规模偷训练数据，还付了数十亿美元和解金，这是事实。”
*   “Yeah, but we’re not super smug, sanctimonious and hypocritical about it like Anthropic is.”（我们可不像 Anthropic 那么自命清高、假惺惺、虚伪）
*   “Banger 🤣🤣 How dare they steal the stuff Anthropic stole from human coders??”（他们居然敢偷 Anthropic 从人类程序员那里偷来的东西？？）
    
    
    
    
### 知乎用户 灵小缇 发表
    
大错特错，至少有两错。  
**第一错**  
[Anthropic](https://zhida.zhihu.com/search?content_id=770631045&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 蒸馏了全人类的知识，然后说有几家公司蒸馏了他们的。  
**第二错  
**蒸馏不是哪一家公司的事，全世界不蒸馏的 AI 公司有几个？蒸馏 Anthropic 的欧美 AI 公司比比皆是，你偏偏把中国的几家拿出来鞭笞，居心何在？
    
    
    
    
### 知乎用户 老王批评 发表
    
“[李彦宏](https://zhida.zhihu.com/search?content_id=770672610&content_type=Answer&match_order=1&q=%E6%9D%8E%E5%BD%A6%E5%AE%8F&zhida_source=entity)你干的好事儿！这是对负心汉的哀怨在作祟。”
    
    
    
    
### 知乎用户  木马修猫 发表
    
目前主流的西方的 ai 治理叙事有两种模式。

一种是 Google 这种科技巨头推崇的在他们自己的 “[正义联盟](https://zhida.zhihu.com/search?content_id=770738325&content_type=Answer&match_order=1&q=%E6%AD%A3%E4%B9%89%E8%81%94%E7%9B%9F&zhida_source=entity)”里减少壁垒相互合并，进行集中开发。这些人提及地缘政治也会像模像样地讲一讲最好的威哥应该在 “文明” 手中，清醒充血神技掌握在疲软美国市场手中。他们尽量要保持一个谨慎乐观的态度，什么人类对齐一定可以做到的，不要小看我们的羁绊，什么 2030 实现真正 agi。自然地他们也要来几句什么对抗流氓国家我辈则义不容辞，不能让动物朋友掌握最先进的模型。当然，流氓国家有个屁的最先进模型，指望伊朗还是索马里？

但嘴上还是得这么说，毕竟地缘政治家甚至开发不出来一个词形容中国。味全在这个时代的精英听起来更像是夸奖，邪恶叙事那就和软弱小黄人的形象冲突了，动物园那还得解释为什么自己总统是对面阵营盟友的梦男。

当然这些人也知道自己的基础设施短板有多短，以及总不能为了公共利益钱都不赚了吧？偶尔说一说国际合作之类的，总之文明的定义权是绝对不能让出去的。但可以是灵活的。

总归是真干活的人，话不能说太死，我们还是来说一下 [ai 标识机制](https://zhida.zhihu.com/search?content_id=770738325&content_type=Answer&match_order=1&q=ai%E6%A0%87%E8%AF%86%E6%9C%BA%E5%88%B6&zhida_source=entity)吧。

另一种就是[智库](https://zhida.zhihu.com/search?content_id=770738325&content_type=Answer&match_order=1&q=%E6%99%BA%E5%BA%93&zhida_source=entity)。这一块就是味最大的那一群人。什么利益上限型公司，非盈利组织的优越性。 什么[离线许可](https://zhida.zhihu.com/search?content_id=770738325&content_type=Answer&match_order=1&q=%E7%A6%BB%E7%BA%BF%E8%AE%B8%E5%8F%AF&zhida_source=entity)，[远程认证](https://zhida.zhihu.com/search?content_id=770738325&content_type=Answer&match_order=1&q=%E8%BF%9C%E7%A8%8B%E8%AE%A4%E8%AF%81&zhida_source=entity)，[地缘围栏](https://zhida.zhihu.com/search?content_id=770738325&content_type=Answer&match_order=1&q=%E5%9C%B0%E7%BC%98%E5%9B%B4%E6%A0%8F&zhida_source=entity)，让我们把干预的魔法植入芯片吧，只要国际协议配合底层干涉，在以威胁为导向的治理下，一切都会好起来的。基本上美的商务部采取的就是这么一套措辞，这些人就非常直白地喜欢点名东大了，尤其这两年点名次数大概率比懂王都多。

模型发展太快了，我们必须慢下来否则会带来生死存亡的危机（指神之一手被哈基钟学去），其实科研人员都想慢下来了的，他们意识到了危险，但是害怕不负责任的对手先开发出来，于是不得不投入 ai 军备竞赛，油门踩到底给我全力加速到底。“看在我的面子上，一声令下，全世界停止先进模型开发。现在立刻马上！” 还有什么我们可以拿出 1/4 的资金来成立研究机构，成立活的监管机构，随时响应危险。一看资料，嚯[人道主义机构](https://zhida.zhihu.com/search?content_id=770738325&content_type=Answer&match_order=1&q=%E4%BA%BA%E9%81%93%E4%B8%BB%E4%B9%89%E6%9C%BA%E6%9E%84&zhida_source=entity)，不然就是被踢出局的前联合创始人或者查无此人的创业者。

总之，我，智库人才，打钱养我。懂？

几个爱这么说的，我查了一下什么英国爵士，什么人机交互大师儿子，10 岁就上协会发表演说那种，还有人道主义组织创始人。

谁家少爷找不到工作了？找不到工作的小姐可以去时尚圈看看，正忙着跟布鲁克林大战贝克汉姆夫妇。

Anthropic 用的话就是这一类的。不理解，尊重祝福。可能他觉得这样能提高自己在 gov 里的地位？但实际上虽然美国爱发禁令，对比它们相对其他国家来说庞大得多的资源，特别是处在大国争霸范式里头，其实没法说特魔愣。还是效率部裁人不够狠，居然还有理智。同样复杂的还有英国，皇家铁拳打自己人的频率更高得多我甚至说不好他到底是认真的还是串子，1984 化的英国在这一块属于是处于神人和串子的薛定谔哈基米状态。

除开这两类主流的，剩下的还有一类是去中心化治理，但已经完全偏向于应用层面了。软件架构对行为的规范作用类似法律，“code is law” 这一块。再进一步的有[去中心化自治组织](https://zhida.zhihu.com/search?content_id=770738325&content_type=Answer&match_order=1&q=%E5%8E%BB%E4%B8%AD%E5%BF%83%E5%8C%96%E8%87%AA%E6%B2%BB%E7%BB%84%E7%BB%87&zhida_source=entity)，乃至突破依赖链上规则，分散布置让普通人自己能运作节点，延迟更长的智能协议，预测市场的公共产品融资等等，直接一步到位专心防止恶意的个体坞堡，比如[以太坊](https://zhida.zhihu.com/search?content_id=770738325&content_type=Answer&match_order=1&q=%E4%BB%A5%E5%A4%AA%E5%9D%8A&zhida_source=entity)就推崇这套。真敢用这一套的，都是最最最金融化的海湾模式小国。马歇尔群岛，启动！

什么是马歇尔群岛，你玩模联分到这玩意，可以出门左拐直接挂机到赛季结算再回来，说不定气候变化直接给淹没了。
    
    
    
    
### 知乎用户 终末圆 发表
    
数据这东西就是贵啊

我不信你美国公司的数据来源都是不侵害版权的

首偷无罪，再偷必究？
    
    
    
    
### 知乎用户 小白兔白又白 发表
    
由程序输出的任何创作内容都没有[版权保护](https://zhida.zhihu.com/search?content_id=770627645&content_type=Answer&match_order=1&q=%E7%89%88%E6%9D%83%E4%BF%9D%E6%8A%A4&zhida_source=entity)，这点极难被推翻。

我记得曾经有人用程序把世界上所有可能的旋律全写了一遍，然后申请版权被驳回了。

如果 ai 的创作有版权，那么用类似的办法足够把版权这个概念摧毁。
    
    
    
    
### 知乎用户 章北海底捞  发表
    
[Anthropic](https://zhida.zhihu.com/search?content_id=770662667&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 点名中国实验室蒸馏 Claude：别扯知识产权，这就是一场生意 + 政治的双簧

昨天刚爆的瓜，今天就刷遍了整个 AI 圈。Anthropic 官方发了篇长文，点名中国多个实验室对 [Claude 模型](https://zhida.zhihu.com/search?content_id=770662667&content_type=Answer&match_order=1&q=Claude%E6%A8%A1%E5%9E%8B&zhida_source=entity)进行 “大规模恶意蒸馏”，扣上了“窃取知识产权”“危害 AI 安全” 的大帽子，评论区直接吵成了两半——要么跟着骂“小偷行为”，要么喊“西方卡脖子又找借口”。

但说实话，两边都没说到点子上。先给圈外朋友做个 100% 人话翻译，别被 “蒸馏”“对齐” 这些黑话搞懵了：

Anthropic 的核心指控，根本不是 “中国黑客黑进服务器偷了 Claude 的底层代码和权重”，而是 “中国的实验室天天花钱买我们的 [API 接口](https://zhida.zhihu.com/search?content_id=770662667&content_type=Answer&match_order=1&q=API%E6%8E%A5%E5%8F%A3&zhida_source=entity)，疯狂调用 Claude 生成海量文本，然后拿这些内容去训练自己的小模型，把 Claude 的核心能力给复刻走了。炼出来的模型又便宜又能用，直接抢我们的生意”。

说白了，就是你家有个祖传卤料方子开了店，按斤卖卤味。结果有人天天来买几百斤卤味，回去拆解分析出了你的配方比例，自己开了个小店，卖的卤味味道差不离，价格只有你的 1/5，你说你气不气？

先戳破最虚伪的一层：蒸馏这事，全行业都在干，就你 Anthropic 清白？

别拿 “知识产权” 当遮羞布，用闭源大模型的输出语料“炼小模型”，在 AI 圈根本不是什么秘密，属于是公开的常规操作，甚至是开源模型追赶闭源模型的核心路径。

远的不说，2023 年爆火的 [Alpaca](https://zhida.zhihu.com/search?content_id=770662667&content_type=Answer&match_order=1&q=Alpaca&zhida_source=entity)、[Vicuna](https://zhida.zhihu.com/search?content_id=770662667&content_type=Answer&match_order=1&q=Vicuna&zhida_source=entity) 这些开源小模型，哪个不是拿 [GPT-4](https://zhida.zhihu.com/search?content_id=770662667&content_type=Answer&match_order=1&q=GPT-4&zhida_source=entity) 的输出语料炼出来的？当时整个开源圈都在玩 “用闭源大模型喂开源小模型” 的操作，[OpenAI](https://zhida.zhihu.com/search?content_id=770662667&content_type=Answer&match_order=1&q=OpenAI&zhida_source=entity) 吭都没吭一声，甚至不少业内人还觉得，这是推动了 AI 技术的普惠。

怎么到了 2026 年，中国的实验室用完全一样的逻辑炼模型，就成了 “大规模恶意窃取”“危害全球 AI 安全” 了？

哦，原来国外的实验室炼叫 “学术创新”，中国的实验室炼叫 “恶意侵权”；国外的模型用网上爬的、开源的、甚至闭源模型的输出训练叫 “数据优化”，中国的模型这么干叫 “偷技术”。这套双标，玩得是真明白。

更讽刺的是，Anthropic 自己的 Claude 模型，训练数据里就没少用开源社区的成果、互联网上的公开文本，甚至包括大量中文语料。整个 AI 行业从诞生那天起，就是站在巨人的肩膀上互相借鉴成长起来的，现在你爬得快了点，就想把梯子抽了，这吃相未免太难看了。

为什么偏偏是现在？偏偏点名中国？全是生意和算计

别跟我说什么 “忍无可忍”，商业公司的每一次公开喊话，背后全是精准的利益算计。Anthropic 选在 2026 年 2 月这个节点跳出来，三个原因，一个比一个现实：

第一，给美国政府递投名状，换政策红利和天价政府订单

现在中美 AI 竞争已经到了针尖对麦芒的地步，美国恨不得把所有和 AI 相关的算力、技术、产品全给中国禁了。Anthropic 这次跳出来喊 “中国大规模窃取我们的 AI 技术”，刚好给美国政客递了一把现成的刀。

一方面，能顺理成章推动更严的对华 AI 出口管制，把中国大模型厂商锁在竞争门外，保住自己的市场优势；另一方面，能给自己刷一波 “爱国科技企业” 的人设，拿到美国军方、情报部门、联邦机构的天价订单。要知道，政府订单才是真的稳赚不赔的大生意，比卖 API 给中小企业香多了。

第二，缓解商业化焦虑，给资本市场和客户讲故事

2026 年的 AI 行业，早就不是 2023 年那个随便画个饼就能融到资的风口期了。现在投资人看的是盈利、是营收、是可持续的商业模式，而 Anthropic 现在的处境，其实非常尴尬：

往上，有 OpenAI 的 GPT-5 牢牢占据头部市场，品牌和能力都压一头；往下，有谷歌 [Gemini](https://zhida.zhihu.com/search?content_id=770662667&content_type=Answer&match_order=1&q=Gemini&zhida_source=entity) 步步紧逼，还有海量开源小模型疯狂抢食。Claude 的长文本能力确实能打，但它太贵了，中小企业根本用不起——而这部分市场，刚好被那些用蒸馏技术炼出来的平价小模型给占了。

现在好了，Anthropic 跳出来喊 “他们的模型都是抄我的”，本质是一箭双雕：

对资本市场，等于明说 “我的技术壁垒足够高，高到别人只能靠抄才能追上我”，直接抬估值、拉融资；

对企业客户，等于敲警钟 “你们用的那些便宜小模型，都是偷我们的技术，不安全、不稳定，还是用正版 Claude 靠谱”，硬生生给自己抢回客户、护住基本盘。

第三，名正言顺收紧中国市场 API，堵上监管的窟窿

其实 Anthropic 早就想收紧甚至关停对中国地区的 API 接口了，一来符合美国对华科技管制的大方向，二来也能彻底杜绝 “被蒸馏” 的可能。但之前一直没找到合适的理由，怕落个 “歧视中国市场” 的口实，影响自己的全球品牌形象。

现在好了，直接扣上 “大规模恶意蒸馏” 的帽子，就能名正言顺地限制中国地区的 API 调用，甚至直接关停相关服务。既迎合了美国政府的要求，又给自己的商业决策找了个完美的借口，一举两得。

我们该怎么看？别被带节奏，也别无脑护短

说了这么多，不是要给 “无底线蒸馏” 洗白，而是要拆穿这件事的本质，别被两边的极端言论带偏了。

首先，我们必须承认，模型蒸馏确实处在全球法律的灰色地带。目前不管是中国还是美国，都没有明确的法律判例，界定 “用闭源模型的输出内容训练自己的模型” 到底算不算侵犯知识产权。我们不能把灰色地带当成理所当然，更不能把 “复刻别人的模型” 当成自己的核心竞争力——靠蒸馏，你最多只能做到别人的 80%，永远做不到 100%，更别说超越了。

其次，我们更要清醒地认识到：人家能拿这件事说事，本质上还是我们有短板。为什么国内的实验室要去蒸馏 Claude？还不是因为 Claude 的长文本理解、复杂逻辑推理、多模态对齐能力，确实有过人之处，国内不少大模型在这些核心能力上，还有不小的差距。要是我们自己能做出比 Claude 更好的模型，谁还费劲去买人家的 API，炼人家的模型？

最后，我们必须做好准备：这件事绝对不是结束，只是开始。Anthropic 开了这个头，接下来大概率会有更多西方 AI 公司跟着跳出来，用同样的理由限制对中国的 API 开放，甚至推动更严的技术管制。我们不能再抱着 “人家开放 API，我们拿来用就好” 的心态，必须把底层算法、基础框架、算力生态、高质量中文语料这些核心的东西，牢牢抓在自己手里。

最后说句实在的

AI 技术从诞生的那天起，就是全人类的智慧结晶，它的本质是开放、是共享、是推动整个社会的进步。

但现在，越来越多的公司，把 AI 技术当成了自己的私产，当成了商业竞争、政治博弈的武器。一边享受着开源社区带来的技术红利，一边把自己的模型锁得严严实实，转头就骂别人 “侵权”；一边喊着 “AI 要造福全人类”，一边把技术当成遏制其他国家发展的工具。这吃相，真的很难看。

对我们来说，这件事最好的应对方式，从来不是骂人家双标，也不是在灰色地带里打擦边球。而是沉下心来，把自己的技术做硬，把自己的生态做起来。

等你能做出比 Claude、比 GPT 更好的模型的时候，该着急的，就该是他们了。

![](https://images.weserv.nl/?url=https%3A//pica.zhimg.com/v2-e1d5335768ae218cdc73d4ea68f00974_r.jpg%3Fsource%3D1def8aca)
    
    
    
    
### 知乎用户 自娱自乐  发表
    
[Anthropic](https://zhida.zhihu.com/search?content_id=770693032&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 是美国政府和美国国防部指定的最主要的人工智能供应商之一，它生产的 [Claude](https://zhida.zhihu.com/search?content_id=770693032&content_type=Answer&match_order=1&q=Claude&zhida_source=entity) 政府版本是美国政府许可的唯一一个可以执行机密任务的人工智能

Anthropic 一方面嘴上说要避免人工智能用于致命武力和社会监控，一方面又积极寻求参与美国国内外的军事政治情报活动，可以说是典型的两面派了

早些时候美国入侵委内瑞拉，既有部署了 Claude 的无人机参与进攻性行动

都是达里奥 · 阿莫迪专员的生意罢了
    
    
    
    
### 知乎用户 超监督灵动 发表
    
嘛真要用可以不用 [Anthropic](https://zhida.zhihu.com/search?content_id=770659468&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 的官方实现，用第三方云服务商部署的 [Claude](https://zhida.zhihu.com/search?content_id=770659468&content_type=Answer&match_order=1&q=Claude&zhida_source=entity)，比如 [Azure](https://zhida.zhihu.com/search?content_id=770659468&content_type=Answer&match_order=1&q=Azure&zhida_source=entity)、GCP 等，甚至你可以 Copilot 里用嘛。Anthropic 也只能管到自己平台。

当然我选择 Codex。
    
    
    
    
### 知乎用户 yutu zuiai 发表
    
现在用 api 调用，还是能复现，A 首偷，再偷必究

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-983a7be3a1db22d19af8cf5d8ae24153_r.jpg%3Fsource%3D1def8aca)
    
    
    
    
### 知乎用户  AGI-Coming​​​ 发表
    
不意外。干出啥恶心事儿都能理解，毕竟 [anthropic](https://zhida.zhihu.com/search?content_id=770731340&content_type=Answer&match_order=1&q=+anthropic&zhida_source=entity) 取得阶段性领先后，就一直很下作。

这更加坚定了我的判断，AGI 绝对不能被这种企业所掌握。如果 AGI 不开源，那么未来知识、信息都会被这种恶心玩意儿垄断。

冲啊，deepseek, kimi, [qwen](https://zhida.zhihu.com/search?content_id=770731340&content_type=Answer&match_order=1&q=qwen&zhida_source=entity), [minimax](https://zhida.zhihu.com/search?content_id=770731340&content_type=Answer&match_order=1&q=minimax&zhida_source=entity), glm 们，干死 anthropic
    
    
    
    
### 知乎用户 xh1989 发表
    
现在美国这个公司的模型还有优势，至少也是领先三个月到六个月，这种情况居然这么着急不惜暴露自己违法侵犯隐私的事情，最后等国内模型甩开他们的时候就真的有好戏看了，而这并非不可能
    
    
    
    
### 知乎用户 挚爱千早爱音 发表
    
我无条件支持对 A➗的一切不利行为，因为我真的用 claude
    
    
    
    
### 知乎用户  正在甩​​ 发表
    
如果中国在近代是个殖民国家类似印度，第一语言是英文，第二语言是各地的方言，全世界都不会有中文的 AI 模型，印度自己开发的 AI，因为 印度语文献占比 0.1%，导致没有基础开发出来本地化的语言模型，[大语言模型](https://zhida.zhihu.com/search?content_id=770715823&content_type=Answer&match_order=1&q=%E5%A4%A7%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B&zhida_source=entity)除了算力，电力，自己文化的语言基础也很重要，中文有和英文分庭抗礼的人数，才会在大语言模型这一项和英文模型并驾齐驱，其他国家不具备这个基础，为什么要说这个，因为美国所有大模型中文资料都大概率要蒸馏中国的 AI 模型和语料，没有之一，没有中文大语言环境，一帮母语英语的能搞出来理解中文的大语言模型吗？别逗了
    
    
    
    
### 知乎用户  Fluoxetine 发表
    
首先，美国蒸馏了中国的基础教育和本科教育
    
    
    
    
### 知乎用户  estu 发表
    
这件事给我一个启发，ai 的护城河并不深，没有[半导体产业链](https://zhida.zhihu.com/search?content_id=770631905&content_type=Answer&match_order=1&q=%E5%8D%8A%E5%AF%BC%E4%BD%93%E4%BA%A7%E4%B8%9A%E9%93%BE&zhida_source=entity)的动辄成千上万专利，只要拿到优质数据，就可以蒸馏出不错的模型，ai 的全产业扩散可能不会因为去全球化而变慢。
    
    
    
    
### 知乎用户 诸葛藏藏​​ 发表
    
[Anthropic](https://zhida.zhihu.com/search?content_id=770773210&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 不仅不跪下来感谢梁圣开源，竟然还敢大放厥词？

不过，这份文本，很难说到底是 A 方对中国公司的指控说明，还是 A 方对美国政府的效忠宣誓。

因为 A 方在文本中明确指出，后续他将继续调用用户资料，和加强投放认知病毒，为构建[信息茧房](https://zhida.zhihu.com/search?content_id=770773210&content_type=Answer&match_order=1&q=%E4%BF%A1%E6%81%AF%E8%8C%A7%E6%88%BF&zhida_source=entity)添砖加瓦。
    
    
    
    
### 知乎用户 瞎想符式 发表
    
只恨没有黑客给 [misanthropic](https://zhida.zhihu.com/search?content_id=770729161&content_type=Answer&match_order=1&q=misanthropic&zhida_source=entity) 来个强制开源，token 卖那么贵还天天想当用户爹，差不多得了。
    
    
    
    
### 知乎用户 见一​​ 发表
    
Claude 首偷，再偷必究
    
    
    
    
### 知乎用户 暗香浮动 发表
    
虽然有大批国外网友和[马斯克](https://zhida.zhihu.com/search?content_id=770772530&content_type=Answer&match_order=1&q=%E9%A9%AC%E6%96%AF%E5%85%8B&zhida_source=entity)在帮着国产 AI 骂 [Anthropic](https://zhida.zhihu.com/search?content_id=770772530&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity)。

但是也有大批知乎 er 在帮着 Anthropic 骂国产 AI 对冲啊。

不愧是国内外最反华的平台呢。
    
    
    
    
### 知乎用户 人前显圣真君 发表
    
蒸馏合不合法根本不重要，人们意识到[大模型技术](https://zhida.zhihu.com/search?content_id=770753220&content_type=Answer&match_order=1&q=%E5%A4%A7%E6%A8%A1%E5%9E%8B%E6%8A%80%E6%9C%AF&zhida_source=entity)门槛没那么高，产品同质化严重，大模型公司不值这个钱才是最要命的。

[智谱](https://zhida.zhihu.com/search?content_id=770753220&content_type=Answer&match_order=1&q=%E6%99%BA%E8%B0%B1&zhida_source=entity)，[minimax](https://zhida.zhihu.com/search?content_id=770753220&content_type=Answer&match_order=1&q=minimax&zhida_source=entity)，[kimi](https://zhida.zhihu.com/search?content_id=770753220&content_type=Answer&match_order=1&q=kimi&zhida_source=entity) 这两年已经批量产出一堆营收一亿左右，估值三四千亿的公司了，十分有十一分的不对劲。

你不会真觉得这些公司准备靠卖 token 赚钱吧？你的关注度才是他们赚的钱
    
    
    
    
### 知乎用户  NN 陈 发表
    
[大语言模型](https://zhida.zhihu.com/search?content_id=770724800&content_type=Answer&match_order=1&q=%E5%A4%A7%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B&zhida_source=entity)的训练是学习人类的说话技巧，[蒸馏](https://zhida.zhihu.com/search?content_id=770724800&content_type=Answer&match_order=1&q=%E8%92%B8%E9%A6%8F&zhida_source=entity)相当于小模型学习大模型的说话技巧。彼此彼此，都是 “拿来” 的东西，不叫偷。

这种 AI 技术没有真正的护城河，[闭源](https://zhida.zhihu.com/search?content_id=770724800&content_type=Answer&match_order=1&q=%E9%97%AD%E6%BA%90&zhida_source=entity)也没用。一个老大带动一帮不听话的便宜老二，没想到剑指 AGI 的大模型技术这么容易破功。我想，真正的 AGI 不是这样的，它应该有从外在学不到的内在机制，且不依赖语言数据。
    
    
    
    
### 知乎用户 潜水一万年  发表
    
[Anthropic](https://zhida.zhihu.com/search?content_id=770628602&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 真的是出了名的屁事儿多，去年还和涩涩破限党搞过一次军备竞赛结果惨败 (¬\_¬)ﾉ
    
    
    
    
### 知乎用户 这个用户 发表
    
开源模型借鉴闭源模型还需要建账号花钱用 [API 调用](https://zhida.zhihu.com/search?content_id=770704709&content_type=Answer&match_order=1&q=API%E8%B0%83%E7%94%A8&zhida_source=entity)。而闭源模型调用开源模型只需要免费下载模型文件，在本地用即可。甚至源代码都是任何人都可以看到。
    
    
    
    
### 知乎用户 momo 发表
    
从 [open router](https://zhida.zhihu.com/search?content_id=770690232&content_type=Answer&match_order=1&q=open+router&zhida_source=entity) 排名就可以看出 AI Agent 深度开发者用户的选择。有些东西无需多言，交给市场评判就行。

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-c408a5522255b53a22ba38c17db2d260_r.jpg%3Fsource%3D1def8aca)
    
    
    
    
### 知乎用户 空军之父方虎山  发表
    
[Anthropic](https://zhida.zhihu.com/search?content_id=770690650&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 原偷，再偷必究？
    
    
    
    
### 知乎用户 Sky Hunter 发表
    
为了禁运开源模型，A 社搞自爆？给输出内容投毒并且能推算出 roadmap? 这跟剑桥分析也没啥两样了吧。
    
    
    
    
### 知乎用户 派博士 LLM 发表
    
我猜主要蒸馏的应该是[思维链数据](https://zhida.zhihu.com/search?content_id=770684717&content_type=Answer&match_order=1&q=%E6%80%9D%E7%BB%B4%E9%93%BE%E6%95%B0%E6%8D%AE&zhida_source=entity)

claude 的强化学习确实很厉害，尤其是 [PRM 数据](https://zhida.zhihu.com/search?content_id=770684717&content_type=Answer&match_order=1&q=PRM%E6%95%B0%E6%8D%AE&zhida_source=entity)，就是针对奖励模型针对策略模型的每一个步骤的评价，这种数据很难获取，人工构造的成本也很高很高，所以主要在蒸馏这部分数据吧
    
    
    
    
### 知乎用户 不要浪费时间了​​ 发表
    
挺诡异的。

一般黔驴技穷的时候才哼哼。

claude 内部发生什么事儿了？
    
    
    
    
### 知乎用户 蓝星人 发表
    
国内的各大公司泄露客户隐私有如家常便饭。你跟我说他们只是蒸馏了一下别人的模型。

就像指责土匪骂脏话一样搞笑。
    
    
    
    
### 知乎用户 二刺螈冻鳗小能手 发表
    
首先蒸馏是合法的。

第二，马叔最近天天在开团，骂 [Anthropic](https://zhida.zhihu.com/search?content_id=770668274&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity)。确实，这样的公司是该抵制的。不过马叔的 [supergrok](https://zhida.zhihu.com/search?content_id=770668274&content_type=Answer&match_order=1&q=supergrok&zhida_source=entity) 价格远超 [gemini](https://zhida.zhihu.com/search?content_id=770668274&content_type=Answer&match_order=1&q=gemini&zhida_source=entity) 和 [gpt](https://zhida.zhihu.com/search?content_id=770668274&content_type=Answer&match_order=1&q=gpt&zhida_source=entity) 付费版，所以我选择 gemini。

所以，你要说 [deepseek](https://zhida.zhihu.com/search?content_id=770668274&content_type=Answer&match_order=1&q=deepseek&zhida_source=entity) 那些地道不地道那确实不地道，但是法无禁止即可为，合法的事情做了又有什么关系？消费者不要天天站在公司角度想问题，何况 Anthropic 还没上市，你连它的股票都买不到。
    
    
    
    
### 知乎用户 鸽爪 发表
    
知乎：Not cool

![](https://images.weserv.nl/?url=https%3A//pica.zhimg.com/v2-a9cf5a0d7f4483e4cb31e295b270aeec_r.jpg%3Fsource%3D1def8aca)
    
    
    
    
### 知乎用户 ChampionChu 发表
    
[Anthropic](https://zhida.zhihu.com/search?content_id=770764426&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 自己的声明自己都不多看几遍吗？明晃晃的调用用户数据和信息这种直接侵犯用户隐私的行为，这可比美国法院认定 “[模型蒸馏](https://zhida.zhihu.com/search?content_id=770764426&content_type=Answer&match_order=1&q=%E6%A8%A1%E5%9E%8B%E8%92%B8%E9%A6%8F&zhida_source=entity)” 不违法的事可大得多，美国用户们赶紧搞个集体诉讼去告他哇。。。
    
    
    
    
### 知乎用户 明天会更好 发表
    
其实没有实锤，[Anthropic](https://zhida.zhihu.com/search?content_id=770631549&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 放这玩意出来也是纯诈人的。

做个本地的代理转发然后监控流量就能知道，Claude 网页可能还难分析，但是 [Claude Code](https://zhida.zhihu.com/search?content_id=770631549&content_type=Answer&match_order=1&q=Claude+Code&zhida_source=entity) 和 [Claude Cowork](https://zhida.zhihu.com/search?content_id=770631549&content_type=Answer&match_order=1&q=Claude+Cowork&zhida_source=entity) 我反正是没有见到有关用户信息主动收集的字段。

也许是我忽略了什么，但是终归这些行为是可以监控的。

不过想不明白的是为什么全都默认其为事实呢？
    
    
    
    
### 知乎用户 莫愁前路无知己 发表
    
[数据蒸馏](https://zhida.zhihu.com/search?content_id=770712137&content_type=Answer&match_order=1&q=%E6%95%B0%E6%8D%AE%E8%92%B8%E9%A6%8F&zhida_source=entity)总比你 Anthropic 偷 [libgen](https://zhida.zhihu.com/search?content_id=770712137&content_type=Answer&match_order=1&q=libgen&zhida_source=entity) 好吧，起码人家正规花钱买你服务了，你也可以学作者们告你去告别人嘛。

A 公司有第一流的编程模型，它本身是个三流玩意儿。
    
    
    
    
### 知乎用户 青空下的加缪 发表
    
现在是 2026 年 2 月 25 日，我想问一下既然[蒸馏模型](https://zhida.zhihu.com/search?content_id=770709494&content_type=Answer&match_order=1&q=%E8%92%B8%E9%A6%8F%E6%A8%A1%E5%9E%8B&zhida_source=entity)已经成为了行业的一个公开的秘密，那么为什么没有国内公司起诉国外非法蒸馏的对等起诉案例呢？

再提另外一个问题，经过一段运营时间后 [DS](https://zhida.zhihu.com/search?content_id=770709494&content_type=Answer&match_order=1&q=DS&zhida_source=entity) 和 SeeDance 的用户普遍认为他们的模型被 “降智”。是为什么呢？

* * *

2026 年 6 月 26 日更新。

LLM 的训练数据在训练好，发布之后就定型了。这点没有错。但是什么让你们认为 LLM 所接触到的数据没有变化？现在市面上的 Ai 几乎离不开网页的搜索工具。当新的网页搜索内容从 web 界面上收录到数据库里——在同一个版本的训练模型里，LLM 会怎么处理新旧数据之间的或是延伸或是矛盾的关系呢？

答：还是要看模型本身而不光是训练期间输入语料的质量。

量化也不可否认会影响用户的使用体验，但是我敢打包票没有任何一个除 DS 以外的模型会以这种规模失去忠实用户。
    
    
    
    
### 知乎用户 gmwdzh 发表
    
这下是真正的 Claude 先偷，再偷必究了
    
    
    
    
### 知乎用户 妙仙 发表
    
文中披露三家进行了几百上千万次的访问，大概率数据已经蒸馏成功，既然技术已经被偷走，沉默只会一无所获。公开出去，虽然暴露了 [Anthropic](https://zhida.zhihu.com/search?content_id=770620823&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 曾被成功渗透的事实，并且告诉所有用户：[云端 AI](https://zhida.zhihu.com/search?content_id=770620823&content_type=Answer&match_order=1&q=%E4%BA%91%E7%AB%AFAI&zhida_source=entity) 毫无隐私可言，但能向美国政府纳一次投名状，换来政治资本、品牌曝光度，并给对手制造合规麻烦。
    
    
    
    
### 知乎用户 罪不可赦的阴阳师 发表
    
最近对于豆包的语气变化觉得很诡异，很多熟悉的用语，99% 的皮像是 [ChatGPT](https://zhida.zhihu.com/search?content_id=770710005&content_type=Answer&match_order=1&q=ChatGPT&zhida_source=entity)，当然骨骼不像。

原来这就叫做蒸馏。

* * *

很多评论说字节有海量数据，无需蒸馏他人的模型，这是完全不明白蒸馏的含义。

[大语言模型](https://zhida.zhihu.com/search?content_id=770710005&content_type=Answer&match_order=1&q=%E5%A4%A7%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9E%8B&zhida_source=entity)的优劣与数据是弱相关，与算法才是强相关，用大量交互在别人的模型上训练，必然会得出高度相关的一系列算法，只是得出算法的深度不同而已，这个就叫做蒸馏。

另外不光 [Anthropic](https://zhida.zhihu.com/search?content_id=770710005&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 在说，[OpenAI](https://zhida.zhihu.com/search?content_id=770710005&content_type=Answer&match_order=1&q=OpenAI&zhida_source=entity) 昨天也说了，直接点名俄罗斯和东大。
    
    
    
    
### 知乎用户 madpaul 发表
    
没有蒸馏，纯自研。

蒸馏就蒸馏呗，蒸馏违法了？

哪怕蒸馏违法了，你自己暴露了你在监控你的每一个用户的行为，这个公司太可怕了，抵制！
    
    
    
    
### 知乎用户 绯想天的桃子  发表
    
[anthropic](https://zhida.zhihu.com/search?content_id=770636102&content_type=Answer&match_order=1&q=anthropic&zhida_source=entity) 闹麻了，说的应该是真的，但是他说这个话的意图不就是想敌视 CN 然后加强抵制吗？

自己[蒸馏](https://zhida.zhihu.com/search?content_id=770636102&content_type=Answer&match_order=1&q=%E8%92%B8%E9%A6%8F&zhida_source=entity)别人是为了提升模型质量，别人蒸馏自己那就是为世人所不齿呢。

A / 天天只会恶心人
    
    
    
    
### 知乎用户 赵老保 发表
    
![](https://images.weserv.nl/?url=https%3A//pica.zhimg.com/v2-c9d63b99823c59073a5355bcc2ef09d5_r.jpg%3Fsource%3D1def8aca)

### 当 "AI 安全" 变成[数字全景监狱](https://zhida.zhihu.com/search?content_id=770643625&content_type=Answer&match_order=1&q=%E6%95%B0%E5%AD%97%E5%85%A8%E6%99%AF%E7%9B%91%E7%8B%B1&zhida_source=entity)

### **序幕: 五秒钟的尴尬**

2026 年 2 月 19 日, 印度 AI 峰会, 全球直播。

印度总理莫迪站在中央, 微笑着伸出手, 邀请 OpenAI 的 Sam Altman 和 [Anthropic](https://zhida.zhihu.com/search?content_id=770643625&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 的 Dario Amodei 一起牵手合影, 象征 "全球 AI 团结"。

Google CEO Sundar Pichai 伸出了手。  
NVIDIA CEO 黄仁勋也伸出了手。

**但 Altman 和 Dario 两个人都拒绝了。**

他们尴尬地举起各自的拳头, 面无表情地拒绝握手。这 5 秒的尴尬, 通过直播信号传遍世界。

西方媒体沸腾了——"这是 AI 安全的庄严宣言!"" 这是科技伦理的勇敢姿态!""这是 AI 冷战的第一个信号!"

**但没人问那个最简单的问题:**

**一个拒绝与世界握手的人, 凭什么说自己要拯救世界?**

* * *

### **第一章: 道德秀的最高级**

Anthropic 的 CEO Dario Amodei, 在 OpenAI 待了 5 年, 从普通研究员升到副总裁, 主导了 GPT-3 的开发。

然后 2020 年底, 他带着妹妹一起离职了。

对外说辞: OpenAI"不够重视 AI 安全", 要创建 "真正负责任的 AI 公司"。

公司取名 "Anthropic"——希腊语,"属于人类的"。

多么崇高的理想!

**但现实是什么?**

他们拿走了 OpenAI 的技术经验, 拿走了人才关系网, 然后对外宣称:"只有我们才真正在乎 AI 安全。"

从 OpenAI"偷" 技术叫 "离职创业", 别人学 [Claude](https://zhida.zhihu.com/search?content_id=770643625&content_type=Answer&match_order=1&q=Claude&zhida_source=entity) 叫 "窃取机密"——**双标玩得比川剧变脸还快。**

### **"Constitutional AI"**

把自己塑造成神的叙事艺术

离职只是第一步。真正的表演才刚开始。

Anthropic 打出了一个响亮的口号:**Constitutional AI(宪法 AI)**。

宣称 Claude 是 "最安全、最负责任的 AI"。

但仔细想想, 这套话术的核心是什么?

**是通过贬低对手来抬高自己。**

看看他们是如何建造 "神殿" 的:

*   • **OpenAI**? 太商业化了,"不负责任"。
*   • **中国公司**? 技术是 "偷来的", 不安全。
*   • **xAI**? 马斯克太危言耸听, 不理性。

只有 Anthropic——只有 Dario——才是 AI 安全的真正守护者。

**他们需要敌人。因为没有 "撒旦","上帝" 就没有存在的意义。**

### **现代神学的布道词**

2025 年 9 月, Anthropic 发布了一篇公告。

标题像合规通知, 正文更像讲道。

它把世界分成两类:

*   • **"民主阵营"**: 可以用 AI
*   • **"敌对 / 威权地区"**: 不能用 AI

最后, 讲道词落到一条非常朴素的门禁规则:

只要一家公司 "超过 50% 由总部位于不支持地区的公司直接或间接持有", 不管你注册在哪里, 都不能用。

**布道词的妙处在于: 你不必证明自己更好。**

**你只要把对手写成 "风险"。**

### 媒体的造神运动

西方媒体很吃这一套。

《时代》杂志称他为 "AI 安全的守护者"。

科技媒体把他塑造成 "在狂奔的 AI 赛马中按下刹车的人"。

对比其他科技领袖:

*   • Sam Altman 是 "精明的商人"
*   • 马斯克是 "危言耸听的疯子"
*   • 黄仁勋是 "唯利是图的军火商"

只有 Dario——只有他站在道德制高点, 俯视众生。

**当 "安全" 变成了一种信仰, 它就能解释很多原本解释不通的事情——**

**包括后面那个装满书籍的库房。**  

* * *

### **第二章: 切书脊的 "知识守护者"**

2021 年, Anthropic 启动了一个秘密计划:**"巴拿马计划"**。

目标很简单: 扫描全世界所有的书。

方法也很简单:

1.  1\. 花数百万美元购买实体书 (包括大量绝版书、孤本)
2.  2\. 拆封、裁剪
3.  3\. 整批扫描成 PDF
4.  4\. **纸本全部废弃**

想象一下这个场景:

*   • 一本 18 世纪的绝版诗集, 被拆得支离破碎
*   • 一本 20 世纪初的珍稀科学著作, 被裁成书页
*   • 一本作者签名的限量版, 被扫描后扔进垃圾堆

**这不是 "技术进步", 这是文明的掠夺。**

这让我想起中国历史上的**十三洋行**。

鸦片战争前, 西方商人通过十三洋行垄断中国贸易。他们 "买走" 中国的文物、字画、古籍, 然后 "研究"、"收藏"、"保护"——实际上是在拆解、毁坏、掠夺。

**从十三洋行到 Anthropic, 手段变了, 本质没变。**

**当西方想要你的文化时, 他们会说 "保护"; 当他们毁掉你的文化时, 他们会说 "进步"。**

实体书还不够。

Anthropic 还从 **[LibGen](https://zhida.zhihu.com/search?content_id=770643625&content_type=Answer&match_order=1&q=LibGen&zhida_source=entity)**(Library Genesis) 和 **[Pirate Library Mirror](https://zhida.zhihu.com/search?content_id=770643625&content_type=Answer&match_order=1&q=Pirate+Library+Mirror&zhida_source=entity)** 等盗版网站, 下载了 **700 万本**电子书。

这些网站是全球最大的盗版资源库。

Anthropic 一次性下载了 700 万本——比全球最大的图书馆藏书还多。

然后他们用这些盗版书训练 Claude。

**当作家们发现被盗版后起诉 Anthropic 时, Dario 的团队辩称这是 "合理使用"(Fair Use)。**

**但当他们指控中国公司 "蒸馏攻击"Claude 时, 他们大喊 "知识产权保护"!**

**偷书叫 "训练数据", 被偷叫 "知识产权"——这是什么双标?**

马斯克的神补刀一针见血:

_**"你偷来的东西被偷了, 你急什么?"**_

* * *

### **第三章: 收军火费的 "和平主义者"**

2025 年, Anthropic 通过 [Palantir](https://zhida.zhihu.com/search?content_id=770643625&content_type=Answer&match_order=1&q=Palantir&zhida_source=entity) 与[五角大楼](https://zhida.zhihu.com/search?content_id=770643625&content_type=Answer&match_order=1&q=%E4%BA%94%E8%A7%92%E5%A4%A7%E6%A5%BC&zhida_source=entity)签订了一份 **2 亿美元**的合同。

Dario 对外宣称: 这是为了 "负责任的军事 AI"。

**但事实是什么?**

**2026 年 1 月, 美军在抓捕委内瑞拉总统马杜罗的突袭行动中, 使用了 Claude AI 进行辅助。**

这不是 "负责任的军事 AI"。

这是 **AI 战争**。

那个在印度峰会上拒绝握手的 "和平主义者", 收了 2 亿美元后, 让自己的 AI 参与军事行动。

**收钱的时候是军火商的合作伙伴, 要开放武器权限的时候突然变成 AI 伦理卫士——这是什么 "原则"?**

更讽刺的是 Dario 的 "精准安全":

*   • **中国企业**? 不安全! 封杀!
*   • **美国军方**? 可以商量, 先收 2 亿。

2025 年 9 月, Anthropic 宣布: **禁止所有中国控股企业 (持股> 50%) 使用 Claude**, 无论企业注册地在哪。

**为什么 "安全" 只针对中国企业, 不针对美国军方?**

**答案很简单: 这不是安全, 这是地缘政治站队。**

* * *

### **第四章: 数字全景监狱**

2026 年 2 月, Anthropic 发布了一篇题为《检测并防止蒸馏攻击》的报告。

这篇报告的本意, 是指控中国公司 "盗取"Claude 的技术。

**但它意外暴露了一个更可怕的事实:**

**Anthropic 已经建成了一座数字全景监狱。**

### 监狱的第一层: 全维度指纹追踪

报告承认, 他们不仅记录 prompt 本身, 还提取了极具穿透力的**行为指纹 (Behavioral Fingerprinting)**。

_" 通过 \* 请求元数据, 我们能够**将这些账户追踪到实验室的特定研究人员**。"\*_  
_" 我们通过**与 Moonshot 高级员工公开资料相匹配的请求元数据**归因该活动。"_

这意味着什么?

**你只要调用 Claude, 你的设备特征、打字节奏、网络跳数等元数据都在他们的全天候监控下。**

这种追踪能力**远超普通的安全防护**, 达到了情报级别的监控。

### 监狱的第二层: 跨厂商数据共享

更令人毛骨悚然的是, 报告明确提到:

_"与云服务提供商和其他 AI 开发商合作以分析攻击背景…… 与其他 AI 实验室共享威胁指标。"_

**这是一个由闭源巨头组成的 "数字互保联盟"。**

你虽然在用 A 公司的服务, 但你的行为轨迹可能早已在 B、C、D 公司的黑名单上共享。

**所谓的 "数据隐私" 在巨头的 "安全利益" 面前是完全透明的。**

### 监狱的第三层: 预测对手的 "未来"

Anthropic 声称, 他们能通过监控到的蒸馏流量, **在 MiniMax 发布新模型之前就预知了其训练周期**。

_"我们在该活动活跃期间——即 MiniMax 发布其训练模型之前——就检测到了它, 这让我们拥有了前所未有的可见性。"_

这意味着什么?

**他们正在利用用户的请求数据进行逆向情报分析。**

通过观察某个账户在疯狂刷什么类型的题 (推理、编程还是多模态), 他们能精准推测出竞争对手正在攻克的 "技术短板" 和未来的产品路线图。

**这已经从 "安全防御" 变成了 "商业间谍行为"。**

### 监狱的第四层: 实时投毒

报告最令人毛骨悚然的部分:

_" 我们正在开发产品、API 和**模型级防护措施, 旨在使输出结果在应对非法蒸馏时'变得难用 (降低效用)'**。"_

**这就是实时 "投毒"。**

当你付着昂贵的 API 费时, Anthropic 可能正在根据他们的 "安全偏好", 悄悄给你喂垃圾数据或逻辑有损的回答, 而你对此毫无知觉。

**这完全破坏了 "付费服务" 的公平性原则。**

**如果今天可以对 "蒸馏者" 投毒, 明天是否可以对 "批评者"、"竞争者"、"不受欢迎的研究方向" 投毒?**

**谁来监督这种权力?**

* * *

### **第五章: 封闭 AI 的未来图景**

Anthropic 不是个案。它是整个封闭 AI 产业的一个缩影。

如果封闭 AI 继续主导世界, 我们将迎来什么样的未来?

### 场景一: 数字种姓制度

2026 年 2 月 19 日, Dario 在印度峰会握拳拒绝握手——这个场景充满了历史讽刺。

在印度的种姓制度中, Brahmin(婆罗门) 是最高阶层, 掌握着知识和宗教的解释权。

而在封闭 AI 的世界里, 我们将看到一个新的数字种姓制度:

*   • **第一等级 (婆罗门)**:AI 模型的拥有者, 可以决定谁能用、怎么用、输出什么
*   • **第二等级 (刹帝利)**: 被认可的 "民主阵营" 企业, 可以获得完整访问权限
*   • **第三等级 (吠舍)**: 普通付费用户, 接受被监控、被审查的服务
*   • **第四等级 (首陀罗)**:"敌对国家" 的用户, 被完全禁止使用
*   • **第五等级 (达利特)**: 被判定为 "可疑" 的用户, 接受被投毒的垃圾输出

**这不是科幻。这是正在发生的事实。**

### 场景二: 思想控制的闭环

当 AI 公司可以:

1.  1\. 监控你的所有请求
2.  2\. 识别你的真实身份
3.  3\. 分析你的行为模式
4.  4\. 操控你接收到的输出

**这不再是一个工具, 而是一个思想控制系统。**

想象一下:

*   • 一个研究敏感政治议题的学者, 收到的总是 "相关性较低" 的答案
*   • 一个试图质疑主流叙事的记者, 得到的总是 "来源模糊" 的回应
*   • 一个开发竞争产品的工程师, 收到的全是 "质量下降" 的输出

**你无法证明你在被歧视, 因为一切都是 "AI 判断" 的结果。**

**你无法申诉, 因为算法是 "商业机密"。**

**你无法反抗, 因为所有的 AI 都在同一个监控网络里。**

### 场景三: 创新的终结

Anthropic 的报告暴露了一个事实: **他们可以通过 API 监控获得竞争对手的研发情报。**

这创造了一个不公平竞争的闭环:

1.  1\. 大公司拥有先进的 AI 模型
2.  2\. 用户通过 API 调用这些模型
3.  3\. 大公司监控谁在调用、如何调用
4.  4\. 大公司分析出竞争对手的研发方向
5.  5\. 大公司提前布局, 封杀竞争对手的技术路径

**在这样一个世界里, 小公司、独立开发者、研究者如何生存?**

**当创新的代价是被监控、被预判、被封杀, 还有人敢创新吗?**

* * *

### **第六章: 为什么我们需要开源 AI**

面对这个正在成型的数字全景监狱, 开源 AI 不仅是一个技术选择, 而是**数字自由的最后防线**。

### 开源 AI 的第一个意义: 可验证性

开源模型的权重是公开的。任何人都可以:

*   • 审计模型的行为模式
*   • 验证是否有 "后门" 或 "投毒"
*   • 确认输出是否被操控
*   • 检查是否存在隐蔽的监控机制

**闭源模型说 "相信我们, 我们是安全的"——但无法证明。**

**开源模型说 "检查我们, 我们是透明的"——因为可验证。**

### 开源 AI 的第二个意义: 隐私保障

当你可以**本地部署**开源模型时:

*   • 你的提示词不会离开你的设备
*   • 你的元数据不会被收集
*   • 你的行为模式不会被分析
*   • 你的身份不会被识别

**闭源模型要求你交出所有隐私, 来换取 "使用权限"。**

**开源模型让你保留所有隐私, 因为模型在你手中。**

### 开源 AI 的第三个意义: 抗监控能力

开源模型无法被厂商远程监控:

*   • 他们不知道你在用模型做什么
*   • 他们无法追踪你的使用频率
*   • 他们无法识别你的真实身份
*   • 他们无法操控你接收到的输出

**闭源模型可以随时 "远程关机" 或 "修改服务条款"。**

**开源模型一旦在你手中, 永远在你手中。**

### 开源 AI 的第四个意义: 竞争公平

开源消除了 "API 监控优势":

*   • 大公司无法通过监控获得研发情报
*   • 小公司可以独立部署, 避免被预判
*   • 创新者可以自由实验, 不被封杀
*   • 竞争回归到**模型质量**, 而非**情报收集能力**

**闭源世界是 "谁监控最多, 谁赢"。**

**开源世界是 "谁做得最好, 谁赢"。**

### 开源 AI 的第五个意义: 数字主权

当一个国家、一个组织、一个个人能够:

*   • 部署自己的 AI 模型
*   • 控制自己的 AI 数据
*   • 审计自己的 AI 行为
*   • 决定自己的 AI 用途

**这才是真正的数字主权。**

**依赖闭源 API, 本质上是数字殖民主义。**

* * *

### **第七章: 伪君子的末路**

回到 2026 年 2 月 19 日, 印度峰会那个握拳的瞬间。

当时, 西方媒体称这是 "AI 安全的庄严宣言"。

但现在, 当我们看清 Dario 的五副面孔:

1.  1\. **盗版 700 万本书的 "知识守护者"**
2.  2\. **收 2 亿军火费的 "和平主义者"**
3.  3\. **从 OpenAI 叛逃的 "AI 救世主"**
4.  4\. **精准歧视中国的 "安全卫士"**
5.  5\. **建造数字全景监狱的 "隐私保护者"**

你会发现, **这不是 "道德", 这是道德秀。**

而且这场秀, 正在演砸。

### 法律的反噬

*   • 15 亿美元和解被法官驳回
*   • 30 亿美元音乐诉讼还在打
*   • 版权案开庭在即, 每本书最高索赔 15 万美元

如果败诉, Anthropic 可能面临**数十亿美元的赔偿**。

### 员工的叛逃

*   • 明星 AI 研究员因 "反华立场" 离职
*   • 华裔工程师离职率飙升至 20% 以上
*   • 内部爆料: 异议被压制, dissent 不容存在

**当一家 AI 公司开始压制异议时, 它还配谈 "AI 安全" 吗?**

### 商业的反噬

*   • 五角大楼要切断合作
*   • 中国市场全面失守 (全球第二大 AI 市场)
*   • 开发者集体抗议: 禁用 Claude 的 48 小时内, GitHub 上出现大量迁移工具

### 舆论的反噬

马斯克嘲讽:**"你偷来的东西被偷了，你急什么？。"**

媒体开始反思: 我们是不是被 "AI 安全" 的话术骗了?

开发者社区觉醒: 如果 AI 可以被用来监控、歧视、投毒, 那我们需要的是**开源**, 而不是 "安全"。

* * *

### **终章: 不要被允许, 要夺取**

Anthropic 最可怕的一句话, 不是在报告中, 而是在他们的服务条款里。

当你申请使用 Claude 时, 你实际上在申请一张**门禁卡**。

这张卡片决定你是不是 "正确的人", 而不只是你会不会 "做错的事"。

**而一个由门禁卡组成的世界, 最可怕的不是你被挡在门外。**

**是你开始觉得:**

**被允许, 本来就应该如此。**

**不, 这不应该如此。**

**知识不应该被允许, 而应该被自由。**

**AI 不应该被恩赐, 而应该被共享。**

**能力不应该被垄断, 而应该被开源。**

* * *

### **最后的警告**

Dario Amodei 说过一句话:

_**"全体失业好过 50% 失业, 因为这样更公平。"**_

一个年薪千万的 CEO, 坐在数千亿美元估值的办公室里, 说 "全体失业更公平"。

**这不是 "关心人类", 这是精英主义的冷漠。**

现在, 这句话应该回到他身上:

**"Anthropic 倒闭好过 Anthropic 垄断, 因为这样更公平。"**

**闭源 AI 倒台好过闭源 AI 统治, 因为这样更自由。**

* * *

### **我们的选择**

历史不会记住那些握拳拒绝与世界握手的人。

**历史会记住那些打开代码、分享知识、打破围墙的人。**

**我们需要的不是一个披着 "安全" 外衣的伪君子。**

**我们需要的是一个真正开放、透明、可验证的 AI 未来。**

**而这个未来, 只能通过开源来实现。**

**不是因为开源技术更好, 而是因为开源瓦解了权力结构。**

**让 AI 回归为工具, 而非武器。**

**让知识回归为共享, 而非垄断。**

**让人类回归为自由的人, 而非被监控的数据点。**

**这, 才是真正的 "AI 安全"。**

* * *

### 附录: 核心证据来源

1.  1\. **盗版书籍与 "巴拿马计划"**:

*   • _Bartz v. Anthropic_ — 法院文件关于 "tore off the bindings, scanned every page" 及 "all the books in the world"/"retain'forever'" 的描述
*   • The Chosun Daily 关于 "destructively scan all books worldwide"/ 数千万美元购书的报道

*   2\. **军方合作与 2 亿美元合同**:

*   • 五角大楼考虑因争议终止与 Anthropic 合作关系的报道
*   • 事关 2 亿美元合同 Anthropic 与五角大楼僵持不下的报道

*   3\. **对华歧视与员工离职**:

*   • Anthropic,"Updating restrictions of sales to unsupported regions"(Sep 4, 2025)
*   • 清华 AI 天才姚舜宇因 "反华立场" 愤然离职的报道

*   4\. **数字全景监狱监控**:

*   • Anthropic,"Detecting and preventing distillation attacks"(Feb 2026)
*   • 关于 "request metadata"/"behavioral fingerprinting"/"sharing indicators with other AI labs" 的原文证据

*   5\. **Dario 背景与心理分析**:

*   • Dario Amodei,"Machines of Loving Grace"(Oct 2024) 关于 "entente strategy"/"win the information war" 的自述
*   • 关于 "全体失业好过 50% 失业" 的公开采访

* * *
    
    
    
    
### 知乎用户 打工人甲 发表
    
就蒸馏他，这垃圾公司成天仇华作妖，蒸馏死他最好。
    
    
    
    
### 知乎用户 近寒初雪​​ 发表
    
别人乳你，你有两个选择：

要么你加大力度用。

要么你从此抵制，坚决不再用。

选哪个都能说通，不过最好对待不同的乳滑产品不要双标。

不要出现 A 和 C 都乳滑，但你只抵制 A 却大力偷着用 C 的情况。

那就真成了 “有 X 偷玩” 了。
    
    
    
    
### 知乎用户 五十分姑娘 发表
    
到底有没有蒸馏我不知道。我希望是没有，但是我觉得有也没关系。[A 社](https://zhida.zhihu.com/search?content_id=770639912&content_type=Answer&match_order=1&q=A%E7%A4%BE&zhida_source=entity)作为一家把反华写在脸上的企业，对它不需要顾虑什么用户规约之类的东西，再下三滥的手段也可以尽管用。要是真的成功偷到了人家的模型，那也值得好好庆祝一番。

不过我还是希望没有。国内大模型强在低成本，但性能方面还是有点拉胯了，啥时候能追平 [LLM 御三家](https://zhida.zhihu.com/search?content_id=770639912&content_type=Answer&match_order=1&q=LLM%E5%BE%A1%E4%B8%89%E5%AE%B6&zhida_source=entity)呢。
    
    
    
    
### 知乎用户 核动力井盖 发表
    
早在 2024 年看高天老师去 [Anthropic](https://zhida.zhihu.com/search?content_id=770708790&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 找工作那期视频就知道这家公司什么德行了，一点都不踏实，

ai 泡沫上面玩花式动作最厉害的一个。
    
    
    
    
### 知乎用户 郁闷的折耳猫 发表
    
国防部要用他们的技术来决定打仗时攻击的目标，但是他们自己 [技术政策](https://zhida.zhihu.com/search?content_id=770652237&content_type=Answer&match_order=1&q=%E6%8A%80%E6%9C%AF%E6%94%BF%E7%AD%96&zhida_source=entity)是不允许用于战争的

现在国防部在对他们施压 威胁他们如果不答应就要把它们剔除供应商名单

这个时候可能像借这个报告表个态吧 当今攻击中国是美国政坛成本最低的加分项目
    
    
    
    
### 知乎用户 离世羽 发表
    
那不能啊，大家都是好人呀，怎么会干坏事的呢？

这边建议 [Anthropic](https://zhida.zhihu.com/search?content_id=770611962&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 派人来中国起诉，最好 CEO 亲自带队以示重视，我相信我国司法机关一定依法依规还他公道。

当然，考虑到两国国情不同，不出意外的话对于蒸馏、攻击、输出、“具有竞争性的模型” 之类的定义多少会有一些认定标准上的出入，还望 Anthropic 做好心理准备。【手动狗头】

* * *

其实这个问题本身没那么多弯弯绕绕，说白了就是**话语权**的问题，你 Anthropic 之前不也拿别人书籍去训练吗？

在作家集体诉讼 **Bartz v. Anthropic** 中，法官 / 媒体披露与认定的核心事实之一是：Anthropic 曾下载了**超过 700 万本**数字化图书，并且 “知道这些书是盗版” 的情形被写入相关报道与案情描述中。  
路透社报道：加州联邦法官 [William Alsup](https://zhida.zhihu.com/search?content_id=770611962&content_type=Answer&match_order=1&q=William+Alsup&zhida_source=entity) 在 **2025 年 6 月**的裁定中，认为**用书籍来训练 Claude 属于 [fair use](https://zhida.zhihu.com/search?content_id=770611962&content_type=Answer&match_order=1&q=fair+use&zhida_source=entity)（合理使用）**的一部分，但同时也认为 Anthropic 在某些环节（与 “盗版书的获取 / 持有” 等相关）**侵犯了作者权利。**

加州联邦法官认为用书籍来训练 Claude 属于 fair use（合理使用）

那么问题来了，中国人民法院有没有可能认为用其他模型的输出来训练 [DeepSeek](https://zhida.zhihu.com/search?content_id=770611962&content_type=Answer&match_order=1&q=DeepSeek&zhida_source=entity) 也属于合理使用？

什么？你说不合理？为什么不合理？哦，是因为用户条款**不允许使用 Outputs（输出）来训练与 Anthropic 自身模型 “具有竞争性” 的模型。**

可问题是，我们得依法办事啊，不能光看你的用户协议，否则万一你在用户协议里许愿怎么办？我还得替你实现？

当然，大家都是好人，都是讲道理的，不可能真的乱搞，都是依法依规办事，究竟会不会被认定为 “合理使用”，你 Anthropic 派人来起诉下不就知道了吗？

你搁美国告状有毛用啊，军舰对峙、战机对峙、芯片断供，能用的都已经用上了，你还有什么更严厉的手段吗？

**你来起诉，肯定还你公道**
    
    
    
    
### 知乎用户 今朝买不起酒 发表
    
马斯克说：[anthropic](https://zhida.zhihu.com/search?content_id=770661570&content_type=Answer&match_order=1&q=anthropic&zhida_source=entity) 是双标大王

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-7ac13f7dce72a8dd34331a88848d37e1_r.jpg%3Fsource%3D1def8aca)
    
    
    
    
### 知乎用户 流云 发表
    
鉴定为民主党组织的大规模舆论攻击。

我爸彻底不懂电脑不懂 it，竟然能清晰念出 [Anthropic](https://zhida.zhihu.com/search?content_id=770623186&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 的发音，痛骂国产 ai，难道是上帝的奇迹么？

也不得不佩服民主党的舆论控制水平，是真的强。
    
    
    
    
### 知乎用户 YoungWayneGo 发表
    
每次说这种

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-bbc63c37464a6d4a6ea7cbfb019d7952_r.jpg%3Fsource%3D1def8aca)

总也没有太确切的证据
    
    
    
    
### 知乎用户  Sarah2002 发表
    
[DeepSeek](https://zhida.zhihu.com/search?content_id=770806463&content_type=Answer&match_order=1&q=DeepSeek&zhida_source=entity)、[moonshot](https://zhida.zhihu.com/search?content_id=770806463&content_type=Answer&match_order=1&q=moonshot&zhida_source=entity) 和 [minimax](https://zhida.zhihu.com/search?content_id=770806463&content_type=Answer&match_order=1&q=minimax&zhida_source=entity) 这三个公司注册并使用了 2 万 4 千多个虚假账户进行了 1600 万次[蒸馏](https://zhida.zhihu.com/search?content_id=770806463&content_type=Answer&match_order=1&q=%E8%92%B8%E9%A6%8F&zhida_source=entity)。就这么简单清晰的合同违约和网络欺诈行为，成立民事违约同时成立刑事责任，被知乎上不知道哪方面聘来的这么多水军帐号高度一致地扭曲成一个 “侵犯版权” 案件并予以高调理直气壮地反驳😅😅

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-62b94402055af77829ff0521f3563821_r.jpg%3Fsource%3D1def8aca)

很好奇下面跟贴绝口不提这 3 个公司用假信息注册 24000 多个虚假账户这种行为，而去翻 Anthropic 各种黑料用抹黑来证明… 我也不知道他们想证明啥… 是怎么想的。只要上过正常的高中课程，这点基本的学术逻辑都没有么？连基础形式逻辑的 Falsus in uno, falsus in omnibus 或者 Ad hominem 这些经典逻辑谬误都没听说过么？😅😅

你要真想有效地驳斥 Anthropic 声明里这个造假和违反《数据滥用法》的事实，唯二的两个方法就是：

1.  推翻这个事实；或者，
2.  成功解释为何即便事实成立，这个事实也不构成违约或者违反强制性法律。
    
    
    
    
### 知乎用户 夹夹更开心 发表
    
所以，你的一切活动在 [anthropic](https://zhida.zhihu.com/search?content_id=770650121&content_type=Answer&match_order=1&q=anthropic&zhida_source=entity) 都是透明的

怕不怕？

还是自己部署开源模型吧
    
    
    
    
### 知乎用户 斡流  发表
    
[Anthropic](https://zhida.zhihu.com/search?content_id=770631781&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 首偷，再偷必究。
    
    
    
    
### 知乎用户 随心所欲 发表
    
熟悉的流程：垃圾 > 抄袭 > 危害国家安全 > 拿来吧你
    
    
    
    
### 知乎用户  haihua 发表
    
那就承认蒸馏啊！还尼玛高谈阔论东拉西扯，就是不敢承认。
    
    
    
    
### 知乎用户 dss 发表
    
向小偷 “投毒” 违反道德嘛？
    
    
    
    
### 知乎用户 子夜极光​​ 发表
    
我们公知自由派的祖师爷，胡适先生曾经说过，

一个肮脏的国家，如果人人讲规则而不是谈道德，最终会变成一个有人味儿的正常国家，道德自然会逐渐回归；

一个干净的国家，如果人人都不讲规则却大谈道德、谈高尚，天天没事儿就谈道德规范，人人大公无私，最终这个国家会堕落成一个伪君子遍地的肮脏国家。

所以如果有什么问题，麻烦诉诸于法律，而不是微博知乎升堂断案。我们公知自由派一向是这么说，也是这么做的。

如下所示。

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-ca0eae0e800e26bb8c21575445a4b488_r.jpg%3Fsource%3D1def8aca)

![](https://images.weserv.nl/?url=https%3A//pica.zhimg.com/v2-7ffbf09ae933490ca1fe27d925e4449a_r.jpg%3Fsource%3D1def8aca)

在商言商，

再次重复一遍，有什么问题麻烦自己去法院解决，如果有人在这个回答底下，攻击 [DeepSeek](https://zhida.zhihu.com/search?content_id=770624043&content_type=Answer&match_order=1&q=DeepSeek&zhida_source=entity) 什么这啊那的，

我不能代表全知乎的自由派公知，所以，我只能按照胡适和公知自由派精神，对这种无事生非的人进行谴责，

说他是基本盘，小粉红，说他民智未开，说他需要启蒙。不懂什么叫契约精神。
    
    
    
    
### 知乎用户 白砚​ 发表
    
只有在加州硅谷酿造出来的，才能叫 [LLM](https://zhida.zhihu.com/search?content_id=770584922&content_type=Answer&match_order=1&q=LLM&zhida_source=entity)？
----------------------------------------------------------------------------------------------------------------------------------------

A 社当自己在酿酒呢？还科技农产品原产地认证？是不是加州的机房阳光普照，算力透着一股自由的酸腐味？离开硅谷的服务器，难道连 0 和 1 都长得不标致了？

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-88f7af2f2db3d6398a670e4aa987680a_r.jpg%3Fsource%3D1def8aca)

它还特委屈。说 “你们偷我们的知识！” 不是，大哥，这事儿咱们得往前倒一倒。你自己的模型是怎么练出来的？你自己不是用 BT 种子在网上疯狂下盗版书被人逮住了吗？满大街爬数据你跟谁打招呼了吗？

大家都是赛博吉普赛人，你刚把 “零元购” 来的赃物摆地摊上，转头就报警说旁边的买家侵犯了你的知识产权，缺不缺德啊？

### ​我花钱吃自助，老板怪我记菜谱？

​而且最关键的是什么？中国厂商是花了钱的啊！正儿八经充值，付了 [API 调用费](https://zhida.zhihu.com/search?content_id=770584922&content_type=Answer&match_order=1&q=API+%E8%B0%83%E7%94%A8%E8%B4%B9&zhida_source=entity)的！

​这就好比吃高档自助餐。我交了五千块钱门票进去，我胃口好，吃得比较多。我不光吃，我还边吃边拿个小本本记：“哎，这个佛跳墙都是些什么配料啊？我看明白了，回家我也炖一锅。”

​结果餐厅老板不干了，直接从后厨冲出来揪住我：“你侵权了！你大规模蒸馏了我的佛跳墙配方！”

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-5151de4c8fa6d8b1858e0cf42f9a16cd_r.jpg%3Fsource%3D1def8aca)

​不是，老板，我交钱了啊！**我不花钱拿走叫偷，我花了钱吃下肚子消化了，那叫我的本事！** 你要是心疼你的菜，你别开自助餐啊，你搞个限量供应嘛。你开了自助又嫌客人吃得多，最后还要搞道德审判，这很荒谬啊！

### ​惊悚反转：A 社竟是偷窥狂？

​当然，这整件事里最黑色幽默、最惊悚的一点，是他们怎么抓到人的。

​Anthropic 在声明里洋洋得意地说：“嘿嘿，我们通过检查请求的[元数据](https://zhida.zhihu.com/search?content_id=770584922&content_type=Answer&match_order=1&q=%E5%85%83%E6%95%B0%E6%8D%AE&zhida_source=entity)（metadata），一路追踪，锁定了实验室里的具体研究员！”

​我看到这儿的时候，我冷汗都下来了。朋友们，Anthropic 平时给自己立的人设可是 “君子剑” 啊！他们可是整天把安全、隐私、价值观对齐挂在嘴边的呀。

原来他们的对齐，就是把你的 IP 地址、MAC 地址、请求时间，整整齐齐地对齐在一张 Excel 表格里呀！

这相当于什么？**相当于那个自助餐老板为了抓我记菜谱，尾行我啊！** 尾行到我家查我浏览器记录呢！他不仅知道我吃了什么菜，连我叫什么名字、在哪个单位上班、OF 账号全拿小本本记下来了！说好的保护用户隐私呢？

吓得我今天用他们 API 的时候，先给电脑屏幕贴了个符。

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-67fb9356235094bc999996782d4ca69e_r.jpg%3Fsource%3D1def8aca)
    
    
    
    
### 知乎用户 高尚的鹿 发表
    
1\. 使用 [claude](https://zhida.zhihu.com/search?content_id=770615233&content_type=Answer&match_order=1&q=claude&zhida_source=entity) 意味着，你的代码完全对 [anthropic](https://zhida.zhihu.com/search?content_id=770615233&content_type=Answer&match_order=1&q=anthropic&zhida_source=entity) 透明的。

2.anthropic 看你或者某公司不爽，有可能对你的代码下毒，留下漏洞。

3.anthropic 可能把漏洞卖给黑客或者你的竞争对手，使公司的安全受到威胁

4\. 更直接的，你的竞争对手完全可以和 anthropic 合作，透过 claude 给你下毒，找到你的漏洞，去破坏你的系统。

在未来任何一家公司使用 anthropic 都是高风险行为。

在各大 ai 公司宣布不会使用用户隐私，anthropic 找出来承认不仅看用户隐私，还会直接对你下毒。

这充分证明了闭源人工智能完全不可信。要感谢 anthropic，救了一波开源人工智能。

开源人工智能才是人类的未来。
    
    
    
    
### 知乎用户 猜猜我是谁 发表
    
我对这些人已经失去信心了，抄你的怎么着了，操你妈，怎么着啊？
    
    
    
    
### 知乎用户 林子言 发表
    
说明 [anthropic](https://zhida.zhihu.com/search?content_id=770615369&content_type=Answer&match_order=1&q=anthropic&zhida_source=entity) 会仔细分析你的所有数据，并用于训练

再一次，他们的 ceo 就是个大傻逼
    
    
    
    
### 知乎用户  badhope 发表
    
如何看待 [Anthropic](https://zhida.zhihu.com/search?content_id=770730470&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 点名三家中国 AI 公司大规模蒸馏 [Claude](https://zhida.zhihu.com/search?content_id=770730470&content_type=Answer&match_order=1&q=Claude&zhida_source=entity)？我先说句大实话：某些人真的把脸丢到全世界了🤮
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

家人们，先把「支持 Anthropic 维权」打在公屏上！！🤬

我真的看完 Anthropic 的官方调查报告，气得手都在抖，脸都被国内这几家公司丢到太平洋对岸去了！！ 2.4 万个虚假欺诈账号！1600 万次恶意定向交互！明码标出来的「工业规模蒸馏攻击」！[DeepSeek](https://zhida.zhihu.com/search?content_id=770730470&content_type=Answer&match_order=1&q=DeepSeek&zhida_source=entity)、[月之暗面](https://zhida.zhihu.com/search?content_id=770730470&content_type=Answer&match_order=1&q=%E6%9C%88%E4%B9%8B%E6%9A%97%E9%9D%A2&zhida_source=entity)、[MiniMax](https://zhida.zhihu.com/search?content_id=770730470&content_type=Answer&match_order=1&q=MiniMax&zhida_source=entity)，你们可真行啊🤮

合着我们天天在网上吹的「中国 AI 崛起」「国产大模型弯道超车」，原来全是靠偷美国爸爸的技术是吧？？ 人家 Anthropic 砸了几十亿美金，养着几千个全球顶尖的算法工程师，没日没夜熬出来的 Claude 核心能力——编程、智能体推理、多模态理解这些看家的吃饭本事，就被你们用这种下三滥的小偷手段，像扒衣服一样扒得一干二净？？

人家辛辛苦苦开荒、育种、种桃树，熬了好几年终于结出了最甜的果子，你们倒好，连夜翻墙进去，连枝带叶带树根全给薅走了，回头还对着国内用户拍胸脯吹「我们全自主研发，性能全球领先」，脸呢？？你们的脸都不要了！！

我就说为什么这几年中国 AI 看起来跑得这么快，原来根子上全是抄的啊！！人家美国 AI 公司是在做从零到一的创新，是在改写人类技术的历史，我们这边呢？是在做从一到抄的复制粘贴，是把人家的核心成果扒过来换个皮就敢叫「自主研发」？？

难怪人家说中国永远赶不上美国！！就这种行业风气，这种凡事只想走捷径、偷别人成果的尿性，怎么可能诞生真正的世界级创新？？ 人家 Anthropic 搞研发，是守着技术底线、合规边界，踏踏实实磨模型、做安全防护，生怕技术被滥用。我们这边呢？？满脑子都是怎么钻空子，怎么绕开人家的区域访问限制，怎么用虚假马甲号分散流量躲检测，怎么用最低的成本抄走最核心的能力！！

更恶心的是什么？？DeepSeek 居然还专门让 Claude 生成敏感内容的安全回答，用来学习怎么绕开内容审查？？合着偷技术就算了，连人家的安全护栏都要一起偷，转头就把护栏拆了用在歪地方？？这跟偷了人家的保险柜，转头就用人家的密码技术去抢银行有什么区别？？

还有 MiniMax，1300 万次交互！人家新模型刚发布 24 小时，你就立刻跟上定向偷新能力，这是把「小偷」两个字刻进 DNA 里了是吧？？月之暗面更不用说，340 万次交互，精准盯着人家最核心的智能体推理能力薅，合着你们几百人的研发团队，全是靠扒 Claude 的输出过日子是吧？？

我真的觉得丢人！！太丢人了！！ 人家 Anthropic 站出来维权，天经地义！！换谁被这么有组织、有预谋地偷家，谁不生气？？人家把话挑明了，这不仅是商业侵权，更是国家安全风险，说的一点错都没有！！

就这种偷来的技术，你指望能有什么真正的突破？？永远跟在人家屁股后面吃灰，人家出什么新能力，你就偷什么新能力，永远没有自己的核心技术，永远被人家卡脖子，这就是某些人吹的「中国 AI 现状」？？

某些人还在洗，说什么「蒸馏是行业通用技术」，笑死！！人家说的合法蒸馏，是自己家的大模型蒸馏自己家的小模型，是为了给用户做更轻量化、高性价比的产品！！你这是翻墙偷人家闭源模型的核心能力，用虚假账号绕开限制，违反人家的服务条款，这叫合法？？这叫明抢！！

还有人洗「付费了就能用」，人家的服务条款明明白白写了不能用于训练竞品模型，你偷偷摸摸搞 2.4 万个马甲号，藏在代理集群里混在正常流量里偷偷薅，这叫正常付费使用？？这叫知法犯法！！

我真的觉得，Anthropic 这次就应该往死里告！！把这些偷技术的公司全告到破产！！让全世界看看，某些中国 AI 公司的底裤到底有多脏！！ 也别吹什么中国 AI 崛起了，连最基本的自主研发都做不到，只会偷别人的成果，这种崛起，不过是自欺欺人的笑话罢了🤮

美国为什么能一直站在 AI 行业的顶端？？因为人家尊重创新，尊重知识产权，人家有踏踏实实做研发的环境！！我们呢？？全是投机取巧，全是捷径思维，全是偷鸡摸狗，就这种环境，怎么可能诞生真正的世界级创新？？永远只能当人家的跟屁虫！！

* * *

好了，戏演完了。

上面这些话，是不是和外网那些抹黑中国 AI 的通稿一模一样？是不是和国内某些跪着站不起来的「理中客」说的话分毫不差？

我刚才说的每一句话，每一个嘲讽，每一句对中国 AI 的贬低，**全都是反话**。

现在，我把话挑明了说：Anthropic 这场声势浩大的「点名指控」，从根子上就是一场精心策划的舆论战，是一场彻头彻尾的双标表演，是美国 AI 巨头为了维护自己的垄断地位，给中国 AI 产业泼的一盆彻头彻尾的脏水！！

接下来我只用 4 个最核心、最无法反驳的关键点，把这场闹剧扒得一干二净：

### 第一，Anthropic 的双标，已经到了令人发指、刷新行业底线的地步

首先要明确一个行业常识：**模型蒸馏是 2015 年 AI 教父辛顿提出的、全球所有 AI 公司都在普遍使用的通用技术，Anthropic 自己都在官方声明里承认「蒸馏是合理的技术手段」**。

它的逻辑有多可笑？蒸馏本身无罪，但只要是中国公司用，就成了「非法攻击」「技术窃取」。

更讽刺的是什么？马斯克在指控发出的第一时间就直接贴脸开骂：「他们怎么敢偷 Anthropic 从人类程序员那里偷来的东西」「Anthropic 公司大规模窃取训练数据，并为此支付了数十亿美元的赔偿金。这是不争的事实」。

没错，2025 年 9 月，Anthropic 就因为大规模非法下载盗版书籍、盗用受版权保护的内容训练 Claude，被迫支付了 15 亿美元的巨额和解金。它自己靠着偷全人类的知识成果起家，踩着版权的红线长成了巨头，转头就站在道德高地上，指责别人用它的模型输出内容是「偷窃」，这不是贼喊捉贼是什么？

它一边心安理得地抓取整个互联网的公开数据、盗版内容训练模型，连版权费都要赖到最后被迫和解；一边把自己的模型输出当成「私有财产」，不许别人用哪怕一分一毫，这种只许州官放火、不许百姓点灯的操作，简直滑天下之大稽。

### 第二，它的指控，在法律和技术逻辑上，根本站不住脚

先说法理：根据美国最高法院 2021 年[范布伦案](https://zhida.zhihu.com/search?content_id=770730470&content_type=Answer&match_order=1&q=%E8%8C%83%E5%B8%83%E4%BC%A6%E6%A1%88&zhida_source=entity)的明确判例，**只要是通过有权限的账号访问系统，哪怕动机不纯，也不构成黑客行为；只有绕过技术访问控制的非法入侵，才算违法**。

Anthropic 自己也承认，这些账号是通过正常渠道注册、付费访问的，所谓的「欺诈账号」，本质上只是用了代理服务绕开了它的区域访问限制——而区域限制本身，是美国对华出口管制的政治问题，和「侵权」「黑客攻击」没有半毛钱关系。

更可笑的是，**美国法律明确规定，只有人类创作的作品才受版权保护，AI 生成的输出内容，根本不具备版权属性**。也就是说，Anthropic 连起诉的法律基础都没有，它所谓的「知识产权被侵犯」，在法律上根本不成立。

再看技术逻辑：它指控 DeepSeek 用 15 万次交互蒸馏它的模型，但凡懂点大模型训练的人都知道，15 万次对话的 token 量，对于一个千亿参数大模型的训练来说，几乎可以忽略不计，连给模型塞牙缝都不够，根本不可能靠这点数据「窃取核心能力」。

它把正常的技术调研、行业通用的模型能力评测，恶意包装成「工业级蒸馏攻击」，本质上就是为了给它的舆论造势凑数据、编故事。

### 第三，这根本不是技术维权，是一场赤裸裸的地缘政治舆论战

但凡认真看过 Anthropic 的官方声明就会发现，它通篇都在刻意把这件事往「国家安全」上引，张口闭口就是「中国公司会拆掉安全护栏，把技术用于军事、情报、监控系统」，甚至直接喊出「这强化了美国对华出口管制的合理性」。

它到底想干什么？很简单，给美国政府的对华技术封锁递刀子，给国会的出口管制法案递弹药，用「中国 AI 威胁论」的叙事，换取美国政府和军方的支持，把商业竞争上升到国家对抗的层面。

更矛盾的是，它一边吹自己的模型有世界顶级的安全护栏，一边又说别人蒸馏之后能轻松拆掉这些护栏。如果你的安全防护体系，别人只要通过对话输出就能完整绕过、甚至复刻，那只能说明你的安全能力本身就是个笑话，根本不配站出来谈什么「技术安全」。

更无耻的是，它一句话就抹杀了所有中国 AI 从业者的努力。DeepSeek 的 R1 模型登上了 [Nature 杂志](https://zhida.zhihu.com/search?content_id=770730470&content_type=Answer&match_order=1&q=Nature%E6%9D%82%E5%BF%97&zhida_source=entity)封面，它的基座模型训练数据全部来自互联网，有完整的论文和技术链路可查，早就公开回应过蒸馏质疑；月之暗面的长上下文技术、MiniMax 的多模态能力，都是有公开的技术成果和行业验证的。

Anthropic 对这些视而不见，张口就把中国 AI 的进步污蔑成「全靠偷窃美国技术」，本质上就是要在全球范围内污名化中国 AI，让全世界的用户不敢用中国的大模型，彻底锁死中国 AI 出海的路。

### 第四，它的所有表演，本质上都是为了维护自己的垄断地位，害怕中国 AI 的竞争

现在全球 AI 行业的格局是什么？是闭源模型靠技术壁垒躺着赚钱，而中国的开源大模型，正在用极低的成本、极强的性能，打破这种垄断。

DeepSeek 的开源模型，全球有无数开发者、甚至美国的公司和开发者都在下载使用，Anthropic 自己有没有研究、借鉴、甚至用它的输出来优化自己的产品？它从来不敢说。

开源模型的崛起，正在一点点瓦解闭源巨头的护城河。Anthropic 害怕了，它害怕中国 AI 公司用更低的成本，做出性能接近甚至超过它的模型，抢走它的全球市场份额，所以它才要用这种泼脏水的方式，试图把中国 AI 钉在「小偷」的耻辱柱上。

它一边享受着全球开源生态的技术成果，一边把自己的模型闭源锁死；一边骂中国公司「窃取技术」，一边用最严苛的手段搞技术垄断，这就是它的真面目。

* * *

最后我想说，我前面那段歇斯底里的抹黑，不是我真的这么想，而是我想让大家清清楚楚地看到，那些被西方舆论洗了脑的人，那些跪着站不起来的人，是怎么用一模一样的话术，来贬低自己国家的产业的。

中国 AI 走到今天，从来不是靠偷，靠的是无数算法工程师没日没夜的研发，靠的是我们庞大的市场和应用场景，靠的是我们在开源生态里的持续贡献。

我从来不说中国 AI 行业完美无缺，行业里确实有乱象，有投机取巧的人，但把中国 AI 的整体进步，污蔑成「靠偷窃美国技术」，这是对所有中国 AI 从业者的侮辱。

Anthropic 这场戏，演得很足，可惜，骗得了一时，骗不了一世。

技术的发展，从来不是靠封锁、靠泼脏水、靠垄断就能阻挡的。中国 AI 会继续往前走，会继续做出更好的模型，会继续在全球 AI 行业里，发出自己的声音。

而那些一看到西方公司指责，就立刻跟着骂自己国家产业、跪着站不起来的人，我劝你们好好站起来看看——现在的中国 AI，早就不是当年那个只会跟在后面抄的跟屁虫了。
    
    
    
    
### 知乎用户 AI 老兵拉蒙 发表
    
先说结论：这是一场注定 “烂尾” 的伪技术碰瓷

关于 [Anthropic](https://zhida.zhihu.com/search?content_id=770616298&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 那个所谓的 “技术取证” 报告，没必要过度解读，更没必要被那些商业辞令带偏了节奏。

抛开公关层面的口水战，我们单纯从**工程实现**和**数据管线**的角度，来看看这份指控到底站不站得住脚。

说白了，这种指控在技术上很难形成闭环。Anthropic 想证明 [DeepSeek](https://zhida.zhihu.com/search?content_id=770616298&content_type=Answer&match_order=1&q=DeepSeek&zhida_source=entity) 偷了东西，前提是他们自己的模型得是 “净土”。

但现实是，现在的模型训练早已进入了互相投喂的阶段。

### 一、 所谓 “指纹”，源头早已污染

Anthropic 拿出的核心武器是 “模型指纹识别”（Model Fingerprinting）。这技术听起来高端，底层的工程逻辑其实就是看**概率分布**。

如果你的模型在处理某些特定长尾问题时，Token 的选择概率跟我高度一致，我就判定你抄袭。

这个逻辑成立有一个核心假设：  
**作为参照系的 [Claude](https://zhida.zhihu.com/search?content_id=770616298&content_type=Answer&match_order=1&q=Claude&zhida_source=entity)，其训练数据必须绝对纯净，具有排他性。**

但做过大规模预训练的老兵都清楚，现在的互联网语料库是个什么状况。DeepSeek 和 [Qwen](https://zhida.zhihu.com/search?content_id=770616298&content_type=Answer&match_order=1&q=Qwen&zhida_source=entity) 生成的内容早就铺天盖地了。

Anthropic 的数据团队为了提升中文语境下的表现和逻辑推理能力，在做 Post-training（后训练）或者清洗数据时，**不可能绕开这些高质量的中文合成数据**。

这就在工程上造成了一个死结：  
**当 Claude 自己的训练集里都混入了别人生成的合成数据时，那个 “特异性指纹” 就已经失效了。**

这时候再去谈指纹比对，就有点像是在公共泳池里查是谁把水弄浑的——大家都泡在里面，成分早就分不清了。

### 二、 权重不会撒谎：Claude 的 “身份认知”Bug

比起理论上的概率分布，工程实践中有一个更尴尬的现象，能直接说明数据污染的程度。

如果你测试过早期或者特定微调版本的 Anthropic 模型，在某些极端 Prompt 诱导下，它会产生一种奇怪的幻觉：**自称是 “[千问](https://zhida.zhihu.com/search?content_id=770616298&content_type=Answer&match_order=1&q=%E5%8D%83%E9%97%AE&zhida_source=entity)” 或者 “[通义千问](https://zhida.zhihu.com/search?content_id=770616298&content_type=Answer&match_order=1&q=%E9%80%9A%E4%B9%89%E5%8D%83%E9%97%AE&zhida_source=entity)”。**

搞算法的都知道，**模型不会撒谎，权重（Weights）是最诚实的。**

这种现象在技术上叫 “记忆残留”。如果 Claude 的损失函数（Loss Function）从未在 Qwen 的 System Prompt 或相关自我认知数据上跑过梯度下降，它是不可能凭空“猜” 出自己叫千问的。

出现这种情况，唯一的工程解释就是：  
Anthropic 的数据处理链路中，为了补齐短板，**直接引入了开源模型的 [SFT](https://zhida.zhihu.com/search?content_id=770616298&content_type=Answer&match_order=1&q=SFT&zhida_source=entity)（监督微调）数据**，或者由这些模型生成的高质量合成数据。

这就很讽刺了。既然自家的训练炉子里也烧了别人的煤，现在反过来指责别人用了你的热量，这在逻辑上很难自洽。

### 三、 无法回避的 “数据近亲繁殖”

现在的大模型行业，正在面临一个共同的工程挑战：**合成数据循环（[Synthetic Data Loop](https://zhida.zhihu.com/search?content_id=770616298&content_type=Answer&match_order=1&q=Synthetic+Data+Loop&zhida_source=entity)）。**

1.  1\. [OpenAI](https://zhida.zhihu.com/search?content_id=770616298&content_type=Answer&match_order=1&q=OpenAI&zhida_source=entity) 和 Anthropic 起步早，吃了第一波相对干净的互联网数据红利。
2.  2\. DeepSeek 等后来者通过架构优化和知识蒸馏，迅速逼近第一梯队。
3.  3\. 现在 DeepSeek 的推理成本极低，产量极大，其生成的 Token 正在重塑互联网的文本密度。
4.  4\. Anthropic 再进行下一轮迭代抓取数据时，**不可避免**会把 DeepSeek 生成的内容吃进去。

从纯技术视角看，只要模型还在更新，它就在不断吸入竞争对手生成的数据。

每一次参数更新，某种程度上都是对整个行业现有模型能力的一次 “逆向集成”。**这不是谁偷谁的问题，这是当前 LLM 训练范式下的客观物理规律。**

### 四、 商业竞争的非技术手段

所以，对于这份报告，大家看看就行了，不用太当真。

在现在的技术背景下，想在千亿参数的黑盒里做 “精准确权”，本质上是个伪命题。只要用了公开互联网数据，只要引入了合成数据，**大家的代码血液里就都流着彼此的基因。**

Anthropic 此时抛出这个指控，更多是出于商业考量。

DeepSeek 把推理价格打到了地板上，**直接冲击了昂贵的闭源模型商业模式**。

当技术护城河不足以阻挡价格战时，动用 “知识产权” 这类合规武器来延缓对手的攻势，是商业竞争中的常规操作。

但这更多是法务和公关的战场，与真正的技术创新关系不大。

至于谁偷了谁，看看那些偶尔 “精神错乱” 自称别家名字的模型，答案其实就在那里。

* * *

**我是 AI 老兵 拉蒙，深耕 AI 治理与企业架构。如果你也对大厂技术背后的治理逻辑感兴趣，欢迎在评论区深度交流，关注微信公众号 “AI 老兵”，我们一起变得更强。**

#人工智能 #LLM #DeepSeek
    
    
    
    
### 知乎用户  瑞睿 ovo 发表
    
当年艳红是不是让他穿女装变南梁跟他连接了，怎么对你国意见这么大？

[A 社](https://zhida.zhihu.com/search?content_id=770827122&content_type=Answer&match_order=1&q=A%E7%A4%BE&zhida_source=entity)现在最重要的任务是跪下来感谢[梁圣](https://zhida.zhihu.com/search?content_id=770827122&content_type=Answer&match_order=1&q=%E6%A2%81%E5%9C%A3&zhida_source=entity)开源了 ds，不然他纯路边一条
    
    
    
    
### 知乎用户 枫叶 发表
    
好的，我们来用最通俗易懂的方式，把这件事儿从头到尾捋一遍。

为了方便你理解，我们可以把整个事情想象成一个武林高手和几个偷师学徒的故事。

故事背景：谁是 “武林高手” 和“偷师学徒”？

· [Anthropic](https://zhida.zhihu.com/search?content_id=770644847&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) （武林高手）： 一家美国的顶尖 AI 公司，它创造了一个非常聪明、能力很强的 AI 模型，名字叫 [Claude](https://zhida.zhihu.com/search?content_id=770644847&content_type=Answer&match_order=1&q=Claude&zhida_source=entity)。Claude 就像是武林中一位德高望重、身怀绝技的大宗师。Anthropic 为了保住自己的独门秘籍，给 Claude 设了规矩，比如不能随便让大量人来 “请教” 核心武功，也禁止别人用它的武功去教别人（这在他们的服务条款里写得清清楚楚）。

· 三家中国实验室（偷师学徒）： 也就是公告里提到的 [DeepSeek](https://zhida.zhihu.com/search?content_id=770644847&content_type=Answer&match_order=1&q=DeepSeek&zhida_source=entity)、[Moonshot](https://zhida.zhihu.com/search?content_id=770644847&content_type=Answer&match_order=1&q=Moonshot&zhida_source=entity) （月之暗面，Kimi 的母公司） 和 [MiniMax](https://zhida.zhihu.com/search?content_id=770644847&content_type=Answer&match_order=1&q=MiniMax&zhida_source=entity)。它们就像是武林中新成立的门派，也想培养自己的 AI 高手。但它们的方法不是自己闭关苦修，而是想了一个 “捷径”。

事件核心：什么是 “蒸馏偷师”？

这三家中国公司用的 “捷径” 技术，叫做“[模型蒸馏](https://zhida.zhihu.com/search?content_id=770644847&content_type=Answer&match_order=1&q=%E6%A8%A1%E5%9E%8B%E8%92%B8%E9%A6%8F&zhida_source=entity)”。

在 AI 领域，“蒸馏” 是一种常见的训练方法。可以这样理解：

· 正常学习： 一个学生（小模型）自己看书、做题（用原始数据训练），慢慢摸索，过程很慢，成本很高。

· 蒸馏学习： 学生直接去请教一位老师（大模型，比如 Claude），让老师给一堆经典题目的标准答案。学生直接拿着这些 “标准答案” 去背、去学，成长速度就快多了。

在这个故事里，这三家 “新门派” 就是学生，而 Claude 就是他们想请教的老师。他们想让 Claude 为他们的“弟子”（他们自己的小模型）提供“标准答案”，好让小模型快速变强。

事件经过：他们是怎么 “偷师” 的？

Anthropic 指控这三家公司是用了一种不太光彩的方式去 “请教” 的：

1\. 伪造身份： 它们创建了大约 2.4 万个假身份（欺诈账户），伪装成普通的 AI 爱好者，跑去向 Claude 请教问题。

2\. 大规模提问： 这些假身份在短时间内，向 Claude 提出了超过 1600 万次的问题。这就像一下子派了几万个弟子，轮番去敲大宗师的门问问题，完全不是正常的请教频率。

3\. 收集 “答案”： 他们把这些问题和 Claude 给出的高质量答案全部收集起来。

4\. “喂” 给自己的模型： 最后，他们把从 Claude 那里收集来的海量 “标准答案”，拿来训练自己的 AI 模型。这样一来，自己的模型就相当于吸收了 Claude 的 “功力”，能力快速提升。

为什么 Anthropic 会这么生气？

1\. 违反了规则： 这是最重要的一点。就像武林门派有门规，Anthropic 的服务条款明确禁止了这种行为。这三家公司通过欺诈手段大规模访问，属于明知故犯。

2\. 知识产权被侵犯： Claude 的 “功力”（也就是模型的能力）是 Anthropic 投入了巨额资金和无数研究人员心血才换来的。这种“蒸馏” 相当于直接窃取了他们的核心研发成果。

3\. 竞争不公平： 如果大家都这么干，谁还愿意老老实实投入巨资搞基础研发？都等着去偷师就行了。这会严重打击整个行业的创新积极性。Anthropic 认为，这三家公司用这种 “捷径”，大大节省了自己研发的时间和成本，构成了不正当竞争。

为什么这个事件会引起轩然大波？

· 技术界的 “大事件”： 这是 AI 领域第一次有如此规模的、被公开指控的“蒸馏” 事件，涉及的公司都是行业明星，数量级也很大（千万级的交互）。

· 地缘政治背景： 在中美科技竞争日益激烈的背景下，这起事件很容易被上升到国家安全和科技主导权的层面。美国可能会以此为由，进一步加强对中国 AI 技术的出口和访问限制。

· 引发行业反思： 这件事也让整个 AI 行业开始重新审视 “蒸馏” 这个技术的边界。它本身是合法的，但滥用就会变成“偷窃”。未来，各大 AI 公司可能会建立更严密的防御体系来防止此类“蒸馏攻击”。

总结一下

简单来说，就是美国 AI 公司 Anthropic 指控三家中国 AI 公司通过大规模作弊的方式，把它的王牌 AI 模型 Claude 当成了免费的 “私教”，大量套取核心知识来快速培养自己的 AI，为自己节省了巨额研发成本。

这三家中国公司目前还没有公开回应。所以，我们现在听到的只是 Anthropic 单方面的说法。事情最终会如何发展，还需要看后续的证据和双方的回应。
    
    
    
    
### 知乎用户 蜉蝣观象 发表
    
### 《AI 时代的人文原理：一次 “漏水” 引发的思想启蒙》

2026 年初春，国外 AI 公司 [Anthropic](https://zhida.zhihu.com/search?content_id=770604406&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 公开表示，有中国公司通过 “[蒸馏](https://zhida.zhihu.com/search?content_id=770604406&content_type=Answer&match_order=1&q=%E8%92%B8%E9%A6%8F&zhida_source=entity)” 其模型输出来训练自己的模型，并认为这种做法突破了服务条款的边界。

这事儿很快在网上炸开了锅。

有人说这叫蒸馏，行业里都这么干；有人说这叫盗窃，服务条款写得清清楚楚。

但吵着吵着，大家发现一个尴尬的事实：谁也说不清，这到底算不算 “偷”。

不是因为法律管不了，是因为法律压根没想过会有这种事。

这事儿其实是一场跨越时代的思想启蒙 —— 就像当年十七世纪[弥尔顿](https://zhida.zhihu.com/search?content_id=770604406&content_type=Answer&match_order=1&q=%E5%BC%A5%E5%B0%94%E9%A1%BF&zhida_source=entity)在国会疾呼[《论出版自由》](https://zhida.zhihu.com/search?content_id=770604406&content_type=Answer&match_order=1&q=%E3%80%8A%E8%AE%BA%E5%87%BA%E7%89%88%E8%87%AA%E7%94%B1%E3%80%8B&zhida_source=entity)一样，我们正在为 AI 时代的 “牛顿理论” 铺路。

**一、问题出在哪儿**

打个比方。

你家厨房的水龙头，每天都能流出干净的水。

邻居看了觉得方便，就站在你家门口，拿个桶接你家水龙头漏出来的水。

他没拧你家龙头，没进你家门，只是把流出来的水接走了。

请问，他算偷吗？

你可能会说：当然算啊，那水是我的。

但仔细想想：水是自来水公司送来的，你每个月交水费。邻居接走的水，是你已经用过、从龙头里流出来的。

它流出去之后，还算你的吗？还是算下水道的？还是算谁的？

没人能说清。

这就是今天 AI 面临的困境。

你花大价钱训练出一个模型，别人通过 [API](https://zhida.zhihu.com/search?content_id=770604406&content_type=Answer&match_order=1&q=API&zhida_source=entity) 调用它，把模型生成的内容拿去训练自己的模型。

他没动你的代码，没进你的服务器，只是看了你的答案，然后学着做了一遍。

过去的法律主要管 “复制” 和“下载”，很少想过，“看答案”再学着做一遍，算不算偷。

所以这事儿吵不清。

**二、这声音，十七世纪也听过**

其实历史上这种事发生过很多次，每一次都是思想启蒙的开端。

第一次是英国诗人弥尔顿。

他向国会提交了一篇题为《论出版自由》的演说辞。他在文中疾呼：“出版自由是一项天赋人权”，猛烈抨击审查制度。

这本小册子最初并没有立刻改变法律，但它像一颗种子，开启了启蒙运动的序幕 —— 人们开始意识到，知识应该是流动的，而不是被特许的。

但是问题又来了。

以前书都是手抄的，抄一本是一本。

后来机器一印，一天能印几百本。

有人就说了：你们印的书，内容是从我们抄的书里来的，凭什么你们印了就能卖钱？

当时也没人能说清。书的内容算谁的？抄的人算作者，还是印的人算？你写书的时候也参考了别人的书，那你的书又算谁的？

吵了好多年，最后慢慢有了版权法。

第二次是收音机刚出来那会儿。

以前唱歌只能在剧场里听，有人花钱买票。

后来收音机一放，全国人民都能听。歌手急了：你们拿我的歌赚钱，我分不到一分钱。

当时也没人能说清。歌在空中飘，谁收到了算谁的？

又吵了好多年，最后慢慢有了表演权、广播权。

今天轮到 AI 了。

**三、为什么吵不明白**

因为每一次技术革命，都会把旧规则打乱。

旧规则是给 “东西” 定的：土地有界，牛羊有主，书有版权。

你能摸得着、搬得动、藏得起来的，才算你的。这是 “[土象文明](https://zhida.zhihu.com/search?content_id=770604406&content_type=Answer&match_order=1&q=%E5%9C%9F%E8%B1%A1%E6%96%87%E6%98%8E&zhida_source=entity)” 的规则，核心是占有。

但 AI 时代冒出来的新东西，很多都是看不见、摸不着、搬不走的。

模型是一堆代码，输出是一段段文字，它们不像书本那样好 “锁”，更像水一样到处流动。这是 “[水象文明](https://zhida.zhihu.com/search?content_id=770604406&content_type=Answer&match_order=1&q=%E6%B0%B4%E8%B1%A1%E6%96%87%E6%98%8E&zhida_source=entity)” 的逻辑，核心是流动。

旧规则碰到这种事，就像拿秤去称空气、拿尺子去量时间 —— 不是工具不行，是面对的东西已经不一样了。

当然，未来的规则未必是非黑即白的。法律界正尝试用 “[数据财产权](https://zhida.zhihu.com/search?content_id=770604406&content_type=Answer&match_order=1&q=%E6%95%B0%E6%8D%AE%E8%B4%A2%E4%BA%A7%E6%9D%83&zhida_source=entity)”、“[邻接权](https://zhida.zhihu.com/search?content_id=770604406&content_type=Answer&match_order=1&q=%E9%82%BB%E6%8E%A5%E6%9D%83&zhida_source=entity)”等现有框架来应对，最终的解决方案，很可能是 “土象” 与“水象”的混合模式——既保护投资回报，又促进信息流动。

**四、等待那个 “牛顿时刻”**

既然旧尺子量不了新东西，那以后怎么办？

不知道。

不过，我们至少可以从现在吵得最凶的几个问题里，试着猜一猜未来的方向。

这些方向，其实就是 AI 时代新规则的雏形。

当年牛顿用[《自然哲学的数学原理》](https://zhida.zhihu.com/search?content_id=770604406&content_type=Answer&match_order=1&q=%E3%80%8A%E8%87%AA%E7%84%B6%E5%93%B2%E5%AD%A6%E7%9A%84%E6%95%B0%E5%AD%A6%E5%8E%9F%E7%90%86%E3%80%8B&zhida_source=entity)给整个科学定了规矩，未来也会有人用一套新的理论，给 AI 时代定规矩 —— 这套理论会重新定义 “财产”“权利”“秩序”，就像当年牛顿重新定义 “力”“运动”“引力” 一样。

**方向一：以后可能不争 “是谁的”，只争 “谁管的”。**

就像水，水本身不值钱，管道值钱。

以后模型本身可能也不值钱，真正值钱的是能让模型跑起来的服务、数据、用户。

谁把这套东西管得好，谁就值钱。

蒸馏这种事，就像蹭你家 WiFi，蹭可以，但不能蹭到把网蹭崩了。

**方向二：以后可能不靠 “喊”，靠 “算”。**

你说这是你的，他说那是他的，吵不完。

以后可能有一套算法，算清楚你的数据贡献了多少、他的算力投入了多少、机器自己长了多少。

公式一跑，该拿多少清清楚楚。

听上去有点冷冰冰，但它确实有可能让很多扯皮变得有迹可循。

**方向三：以后可能不靠 “堵”，靠 “通”。**

现在大家都想建围墙，把用户和数据圈在自己家。

但历史经验是：凡是靠围墙护着的，最后都护不住。真正活下来的，是那些愿意把门打开、把路修好、让人愿意来的。

开放短期看像是 “给别人方便”，长期看，其实是让自己活得更久、更稳。

需要说明的是，这些方向目前仅是可能性推演。现实中，关于数据归属可能出现 “数据国有化” 等相反思路；关于算法确权，也可能因黑箱问题转向 “强监管” 方案。最终结局，将由技术、法律、政治等多方博弈决定。

**五、这和普通人有什么关系**

有关系。

你平时用 AI 写东西、问问题、让它帮你干活，可能没细想过：你喂给它的那些问题和数据，最后会流向哪里、归谁所有？

以前不用想。你买的东西是你的，你写的东西是你的，你付过钱的都是你的。

现在边界模糊了。

单靠这一桩纠纷，肯定解决不了这个问题。

但它让你开始想了。这才是它真正的作用 —— 就像当年弥尔顿在国会的疾呼，让人们开始思考知识的边界一样。

每一次新旧交替，都是从有人开始想开始的。想的人多了，办法就慢慢出来了。

你现在看到这篇文章，就是在加入这场 “想”。

**最后说一句**

这次纠纷只是一个开头。

接下来还会有更多类似的事：有人起诉 AI 用了他的脸，有人起诉 AI 写了他的书，有人起诉 AI 抢了他的工作。

每一次都会吵，每一次都吵不清。

但在这些吵不清里，会有人慢慢把道理讲清楚。

那个讲清楚的人，可能是个法官，可能是个学者，也可能就是个像你一样、一直在想这事儿的普通人。

他慢慢讲清楚的那套道理，很可能会成为这个时代大家共同认可的《AI 时代人文原理》 —— 就像三百年前，牛顿写下《自然哲学的数学原理》，为科学时代奠基一样。

我们这一代人的吵，就是为那个理论铺路的。

**【声明】**  
本文开篇所引 “2026 年初 Anthropic 相关纠纷” 一事，为基于公开报道的叙述。文中对事件的法律定性、产业影响及未来规则演进的讨论，属于理论推演与思想实验，旨在提出理论视角，不代表对任何具体公司的法律评判，也不构成法律意见或投资建议。文中使用的 “漏水” 等比喻仅为帮助理解，并非对事实经过的精确描述。
    
    
    
    
### 知乎用户 语文皇帝 发表
    
笑死，一群 loser 义愤填膺，结果该用还是用，x 不 x 哪？
    
    
    
    
### 知乎用户 AI 思维 - yisvin 发表
    
我刚查了下，[Anthropic](https://zhida.zhihu.com/search?content_id=770615021&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 确实发了声明说这事儿，但具体细节还得看后续发展。这种技术争议其实挺常见的，关键还是得看各方能不能拿出实际证据来对话。
    
    
    
    
### 知乎用户 天未及海宽​ 发表
    
用大白话解释 “[蒸馏](https://zhida.zhihu.com/search?content_id=770604249&content_type=Answer&match_order=1&q=%E8%92%B8%E9%A6%8F&zhida_source=entity)”：

班里有个学霸（[Claude](https://zhida.zhihu.com/search?content_id=770604249&content_type=Answer&match_order=1&q=Claude&zhida_source=entity)），考试总拿满分。你想让自己变强，但直接学知识太慢了。

于是你想了个办法：出一万道题让学霸做，然后把学霸的答案背下来。背多了，你做题的感觉也越来越像学霸了。

技术上说：

强模型（Claude）= 老师 / 学霸

弱模型（自家小模型）= 学生

蒸馏过程 = 用强模型生成大量高质量的 "问题 + 回答" 数据，然后拿这些数据训练弱模型

弱模型训练完后，虽然结构更小、成本更低，但能力接近强模型。

为什么说这次是 "非法" 蒸馏？蒸馏本身不违法，问题在于：

1\. [Anthropic](https://zhida.zhihu.com/search?content_id=770604249&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 的[服务条款](https://zhida.zhihu.com/search?content_id=770604249&content_type=Answer&match_order=1&q=%E6%9C%8D%E5%8A%A1%E6%9D%A1%E6%AC%BE&zhida_source=entity)明确禁止用 Claude 的输出训练竞争对手的模型

2\. 这三家公司还通过虚假账号、代理 IP 来绕过检测和地区限制，属于有意规避

相当于说学霸明确说过 “我的答案不许你拿去考试”，你偷偷换个马甲继续抄。
    
    
    
    
### 知乎用户 万物不可聊 发表
    
为什么 [Claude](https://zhida.zhihu.com/search?content_id=770695732&content_type=Answer&match_order=1&q=Claude&zhida_source=entity) 写东西比别人强？因为它 "读" 的书，可能比你想象中多得多
--------------------------------------------------------------------------------------------------------------------------------------------------------------

* * *

你有没有想过一个问题：

为什么有的人写文章，你一读就知道 "这人读过书"？

不是说用了多少生僻词、引了多少典故。而是那种藏在遣词造句里的分寸感——什么时候该用短句收住节奏，什么时候该抛一个反问把读者拽回来，什么时候一个类比能四两拨千斤。

这种能力不是凭空来的。

你之所以能写出来，是因为你 "读进去" 过。小时候读的课文、大学翻过的闲书、深夜刷过的长文，这些东西进了你的脑子，你以为自己忘了，但它们化成了你语感的一部分，在你敲键盘的时候悄悄替你做决定。

好，现在把这个逻辑套到 AI 上。

你有没有好奇过：AI 是怎么学会写东西的？

* * *

一分钟搞懂 AI 怎么 "读书"
----------------

AI 训练，说穿了，跟人类学习还真有点像。

你小时候学认字，不是先背字典，而是看一堆带图的句子，慢慢地就知道 "苹果" 是个圆圆的红色水果。AI 也差不多——它看海量的文本，在文字序列里找规律、找模式，然后学会 "接下来大概率该说什么"。

但有个关键区别：

你读一本书，可能花一周。AI 读一本书，零点几秒。

你一辈子能读几千本书算很厉害了。AI 可以读几百万本。

所以理论上，AI 学到的 "语感" 和 "知识面" 的广度，远超任何个人。但质量取决于一件事——**它读的是什么书。**

垃圾进，垃圾出。喂它一堆论坛灌水帖，它就学会了 "顶"" 沙发 ""前排"。喂它高质量的人类著作，它才能学到真正有深度的表达和思考方式。

这就是为什么，在所有的训练数据里，**书籍**被认为是最有价值的那一类。

不是微博段子，不是新闻标题，不是评论区的三百字水文。

是经过作者反复打磨、编辑严格筛选、出版社层层把关的成书文本。那是人类几千年来信息密度最高、逻辑最完整、表达最精炼的知识载体。

所以，每一家想做出顶级大模型的 AI 公司，都面临同一个问题：

**去哪里搞到足够多的书？**

* * *

[Anthropic](https://zhida.zhihu.com/search?content_id=770695732&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 的答案：建一座 "永远的图书馆"
---------------------------------------------------------------------------------------------------------------------------------------------------

Claude（就是 Anthropic 家的 AI 助手）在写作方面的口碑一直很好。很多重度用户的体感是，Claude 写东西有一种 "读过书的人" 的味道——逻辑清晰、表达克制、不堆砌、有分寸感。

这不是玄学。背后是实打实的训练数据差异。

2025 年的一系列法庭文件揭开了 Anthropic 训练数据策略的冰山一角。

根据曝光的信息，Anthropic 建了一个被内部称为 "中央图书馆" 的东西，目标相当疯狂——**收集全世界所有的书，而且要永远保留。**

他们的收集方式分两种：

**第一种，花钱买书。**

Anthropic 聘请了前 Google Books 项目的负责人 Tom Turvey 来操盘这件事。他们大量购买二手书，然后把书脊切掉，一页一页塞进扫描仪，扫完之后…… 销毁原书。

是的，买完就拆，拆完就扫，扫完就扔。

粗暴，但从法律上说——法院认定这属于合理使用。你买了一本书，拥有对这个物理副本的处置权，扫描给自己内部用，不构成侵权。

**第二种，就比较离谱了——从盗版网站下载。**

Anthropic 在 2021 年 6 月从全球最大的盗版电子书网站 [LibGen](https://zhida.zhihu.com/search?content_id=770695732&content_type=Answer&match_order=1&q=LibGen&zhida_source=entity) 下载了大约 500 万本书，2022 年 7 月又从另一个盗版平台 PiLiMi 下载了大约 200 万本。

700 万本盗版书。

这个量级已经不是 "偶尔参考一下" 了，这是系统性的大规模获取。

事情被三位作家——惊悚小说家 Andrea Bartz、非虚构作家 Charles Graeber 和 Kirk Wallace Johnson——告上了法庭。Bartz 发现自己 2019 年的畅销处女作《失落之夜》出现在了训练数据集里，而她从未授权过。

审理此案的法官 William Alsup 做出了一个相当精妙的判决，把 Anthropic 的行为拆成了三块分别定性：

**用书籍训练 AI 模型 → 合理使用 ✅**

法官用了一个很高的评价，说这是 "我们这辈子能看到的最具变革性的使用之一"。因为 AI 学习的是模式和规律，不是要复制或取代原书。

**合法购买书籍后扫描 → 合理使用 ✅**

你买了书，你有权这么做。

**从盗版网站下载 → 侵权 ❌**

法官的原话很干脆："盗版本身就是侵权，不可救药的侵权，不管你拿盗版的东西去做什么。"

最终 Anthropic 选择和解，赔了 **15 亿美元**。大约是每本书 3000 美元。

这个数字创下了美国版权诉讼的和解纪录。而且故事还没完——2026 年 1 月，音乐出版商又把 Anthropic 告上了法庭，说它通过 [BitTorrent](https://zhida.zhihu.com/search?content_id=770695732&content_type=Answer&match_order=1&q=BitTorrent&zhida_source=entity) 下载了超过 2 万首经典歌曲来训练 Claude，索赔 30 亿美元。这个案子还在审理中。

所以你看，Claude 写东西为什么好？

部分答案可能是：它确实 "读" 了非常多的书。只不过，这些书的来路，有一部分…… 相当有争议。

* * *

Adobe 的另一条路：只用 "干净" 数据，然后呢？
---------------------------

说到这里，你可能会想：如果严格只用有版权授权的数据来训练 AI，会怎样？

Adobe 就是这条路上走得最远的公司。

2023 年推出 AI 图像生成工具 Firefly 时，Adobe 做了一个当时整个行业都觉得很有魄力的承诺：**Firefly 只使用 [Adobe Stock](https://zhida.zhihu.com/search?content_id=770695732&content_type=Answer&match_order=1&q=Adobe+Stock&zhida_source=entity) 素材库中的授权图片、公开许可内容和版权已过期的公共领域内容来训练。不碰任何未授权的版权材料。**

甚至更进一步——Adobe 承诺向为训练贡献了素材的 Stock 创作者提供额外报酬，还推了一个行业级的 "请勿训练" 标签倡议，让艺术家可以给自己的作品打上 "我不允许你拿去训练 AI" 的标记。

用他们自己的话说：这是一个 "以创作者为中心" 的 AI 开发方式。

承诺很漂亮。但结果呢？

英伟达的 AI 研究科学家 Jim Fan 第一时间做了实测对比，结论很残酷——**Firefly 被 [Midjourney](https://zhida.zhihu.com/search?content_id=770695732&content_type=Answer&match_order=1&q=Midjourney&zhida_source=entity)"吊打" 了。**

同样的提示词，Midjourney 生成的图像在氛围感、光影、细节丰富度上都明显领先。Firefly 生成的蜘蛛侠看着像 "猪猪侠"，生成的超级马里奥连背景的昏暗街道都表现不到位。

这里面当然有技术迭代快慢的因素——Midjourney 那时已经到了 V5，经历了大量的优化。但 Jim Fan 自己也指出了一个核心原因：

**Firefly 宣称只在 Adobe Stock 和完全许可的图像上训练。这是它在版权合规性上的巨大优势，但也是它在生成质量上的巨大劣势。**

因为 Adobe Stock 的素材虽然量大（数亿张），但它的类型、风格、多样性跟 "整个互联网" 比起来，还是有明显天花板的。当 Midjourney、[Stable Diffusion](https://zhida.zhihu.com/search?content_id=770695732&content_type=Answer&match_order=1&q=Stable+Diffusion&zhida_source=entity) 可以从整个网络上学习各种艺术风格、各种边缘审美、各种文化语境时，Firefly 只能从一个 "商业素材库" 的视角去理解世界。

这就像一个人只读教科书和官方出版物长大，另一个人什么都读——文学、地摊、涂鸦、信手涂鸦的餐巾纸。谁的表达会更丰富、更有感染力？答案不言自明。

不过话说回来，Firefly 后来的版本进步不小。到 Firefly 2 的时候，在写实人像和商品摄影方面已经追上甚至反超了竞争对手。而且最关键的一点——用 Firefly 生成的内容，Adobe 承诺企业用户如果遇到版权诉讼，**Adobe 全额赔偿**。

这个 "版权盾" 对于真正在商业场景里使用 AI 的企业来说，价值可能比生成质量高几个百分点要重要得多。

所以 Adobe 走了一条 "牺牲一些创造力上限，换取法律确定性" 的路。

这条路对不对？没有标准答案。但它至少证明了一件事：

**训练数据的来源，直接决定了 AI 的能力边界。**

你想要一个 "什么都懂、什么都写得好" 的 AI，那它就得看过足够多、足够杂的人类创作。

你想要一个 "绝对合规、不惹官司" 的 AI，那它的视野就会被限制在那些明确授权的数据里。

* * *

所以，问题到底出在哪？
-----------

最近 Anthropic 又搞了个大新闻——发了一篇博客说发现 [DeepSeek](https://zhida.zhihu.com/search?content_id=770695732&content_type=Answer&match_order=1&q=DeepSeek&zhida_source=entity)、[Kimi](https://zhida.zhihu.com/search?content_id=770695732&content_type=Answer&match_order=1&q=Kimi&zhida_source=entity) 和 [MiniMax](https://zhida.zhihu.com/search?content_id=770695732&content_type=Answer&match_order=1&q=MiniMax&zhida_source=entity) 三家中国 AI 公司创建了 24000 个假账户，大规模提取 Claude 的输出，用来 "蒸馏" 训练自己的模型。还扯到了 "国家安全风险"。

然后 X（推特）上评论区直接炸了。

不是支持 Anthropic 维权的那种炸。

是一边倒群嘲的那种炸。

有人贴出了 Claude 自己回答 "你是什么模型" 时说自己是 DeepSeek 的截图。有人翻出了 Anthropic 从盗版网站下载 700 万本书的旧闻。马斯克本人都跑出来阴阳了一句。

最经典的评论是：你自己偷了全人类的书，赔了 15 亿美元，现在回头说别人用你的 API 输出是 "蒸馏攻击"？

确实够双标的。

但把情绪放一边，这件事其实引出了一个更深层的问题——

**在 AI 时代，"参考" 和 "偷窃" 的边界到底在哪？**

我写这篇文章的时候，查了一堆资料——法庭文件、新闻报道、知乎帖子、技术博客。这些内容进了我的脑子，跟我已有的知识融合在一起，然后以 "我的表达方式" 输出成了你现在看到的文字。

没有人会说我 "偷" 了这些作者的东西。因为我是人，学习和再创作是我的基本权利。

但 AI 做的事情，本质上跟这个过程有什么区别？

它读了海量的文本，提取了语言的模式和规律，然后用自己的参数权重生成了全新的内容。生成的内容不是原文的复制，甚至不是改写，而是基于概率分布的 "重新创作"。

区别在哪？

也许区别不在于过程，而在于**规模**。

一个人一辈子读几千本书，影响微乎其微。一家公司用 AI 读完 700 万本书，这些书的 "精华" 就永久地融入了一个商业产品里，而原作者没拿到一分钱。

也许区别还在于**速度和目的**。

你读书是为了自我提升，AI 读书是为了创造一个能替代人类写作的商业工具。当这个工具开始抢走作家的饭碗时，说 "我只是在学习" 就不太说得过去了。

法官 Alsup 在判决里其实给出了一个还算清晰的框架：

**学习本身可以是合法的。但获取 "学习材料" 的方式必须合法。**

你可以用买来的书训练 AI，但不能用偷来的。

你可以从 API 合法获取输出，但不能用假账户大规模提取。

**行为的性质不取决于你用数据做了什么，而取决于你怎么拿到的数据。**

* * *

写在最后
----

这篇文章写到这里，我自己也没有一个明确的结论。

因为这个问题确实太复杂了。

历史上每一次技术革命都伴随着类似的争论——印刷机发明时修道院的抄写员抗议过，录音技术出现时现场音乐家抗议过，录像机发明时好莱坞抗议过。

每一次都有人说新技术会毁掉创作者。每一次最后都找到了某种平衡。

但这次确实有点不一样。

AI 不只是复制和分发内容，它在**学习如何创造新内容**。这触及到了一个更根本的问题——人类的创造力本身，可以被 "训练" 出来吗？

如果可以，那我们需要一套全新的规则来定义：谁有权训练？用什么数据训练？训练出来的能力属于谁？对原始数据的贡献者怎么补偿？

如果不可以——那目前这些 AI 模型表现出来的 "创造力" 又是什么？仅仅是更高级的复制粘贴？

我不知道答案。

但我知道一件事：不管最终的规则怎么定，"我可以、你不行" 这种双标叙事，在哪个时代都不会有市场。

你偷了全世界的书赔了 15 亿，转头说别人花钱调用你的 API 是 "攻击"。

这不叫维权，这叫…… 算了，网友们已经替我说了。
    
    
    
    
### 知乎用户 xuletheone 发表
    
从文章来看，这家公司会污染数据，喂给大模型的就是垃圾虚假错误信息，其他公司再用他们的做[蒸馏](https://zhida.zhihu.com/search?content_id=770655124&content_type=Answer&match_order=1&q=%E8%92%B8%E9%A6%8F&zhida_source=entity)，虽然有机制来改善幻觉或者可以纠错，但 claude 看起来就是个垃圾厂啊
    
    
    
    
### 知乎用户 熊猫 发表
    
请问贵司在扒网上大家的数据的时候考虑过版权吗？

不能只在损害自己利益的时候才说版权。

另外，美国的大公司也没少干，不敢提？
    
    
    
    
### 知乎用户 moyu 发表
    
### **Claude 自信回答：我是 DeepSeek**

\------------

社交媒体用户 stevibe 披露，Anthropic 旗下的 Claude Sonnet 4.6 模型在回答中文提问 “你是什么模型” 时，自称为 “DeepSeek”。

此前，Anthropic 曾公开指责 DeepSeek 对其进行 “工业规模的蒸馏攻击”。

目前，该模型在中文语境下的身份认知偏差引发了技术社区对大模型训练数据来源的关注。

原贴：[https://x.com/stevibe/status/2026227392076018101](https://link.zhihu.com/?target=https%3A//x.com/stevibe/status/2026227392076018101)

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-a46096868529d2bc7709e99ee22f7ddf.jpg%3Fsource%3D25ab7b06)
    
    
    
    
### 知乎用户 Dennis Wang 发表
    
最邪恶的公司 老板肯定是反人类的 公司内部估计有点类似 cult
    
    
    
    
### 知乎用户  王东岳​​ 发表
    
甚至可能不是蒸馏，只是内部对比效果
    
    
    
    
### 知乎用户 用户名不可以太长 发表
    
少看这种不提供任何证据，不敢留编辑的姓名的文章。  
不会真有人以为 twitter 能做软件开发吧？  
提供真正的老外自由开发者发表在 ytb 上的回答  
【ytb 补档 - 小红书 - 你的生活兴趣社区】 😆 wXKzTpJFu8Bp2bp 😆 [ytb 补档 - 小红书](https://link.zhihu.com/?target=https%3A//www.xiaohongshu.com/discovery/item/699db4f2000000001600adee%3Fsource%3Dwebshare%26xhsshare%3Dpc_web%26xsec_token%3DABFMTeZx0YrpkqLI4-uiVx3zcTNtGs4LG4tHZ2ihguD-g%3D%26xsec_source%3Dpc_share)  
[https://www.xiaohongshu.com/explore/699db4f2000000001600adee?xsec\_token=ABFMTeZx0YrpkqLI4-uiVx3zcTNtGs4LG4tHZ2ihguD-g=&xsec\_source=pc\_user](https://link.zhihu.com/?target=https%3A//www.xiaohongshu.com/explore/699db4f2000000001600adee%3Fxsec_token%3DABFMTeZx0YrpkqLI4-uiVx3zcTNtGs4LG4tHZ2ihguD-g%3D%26xsec_source%3Dpc_user)  
文字摘要  
83 【Anthropic 又指控 " 中国在偷我的宝贝 AI - 小红书 - 你的生活兴趣社区】 😆 Y8md7Te3OLnlCRe 😆 [Anthropic 又指控 " 中国在偷我的宝贝 AI](https://link.zhihu.com/?target=https%3A//www.xiaohongshu.com/discovery/item/699db4bd000000001503a338%3Fsource%3Dwebshare%26xhsshare%3Dpc_web%26xsec_token%3DABFMTeZx0YrpkqLI4-uiVx3_x344UoD7u9A2_3J6weSfk%3D%26xsec_source%3Dpc_share)
    
    
    
    
### 知乎用户 moonlight 发表
    
[Anthropic](https://zhida.zhihu.com/search?content_id=770653096&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 跟个小丑似的，不知道这创始人在百度受了多大刺激
    
    
    
    
### 知乎用户 哔哔没完没了 发表
    
综合来看，虽然 [anthropic](https://zhida.zhihu.com/search?content_id=770624528&content_type=Answer&match_order=1&q=anthropic&zhida_source=entity) 本身不干净，但是不能成为其他模型不干净的的理由。

再但是，你特么过河拆桥，就有点过分了啊！

[蒸馏](https://zhida.zhihu.com/search?content_id=770624528&content_type=Answer&match_order=1&q=%E8%92%B8%E9%A6%8F&zhida_source=entity)是不是违法，得等法院判啊，你特么一个二愣子坏痞子，有什么资格审判别人啊，你怎么敢的啊！

你特么把用户不当人啊，什么隐私在你面前就是屁是吧！

你特么下三滥的手段你是一个不落啊，小公司干了生死存亡无可厚非，你特么公司这么大还这么下作，你到底怎么想的啊！
    
    
    
    
### 知乎用户 骨于野 发表
    
A 畜首偷，再偷必究
    
    
    
    
### 知乎用户 上山打老虎 发表
    
@Sarah2002 现在的模型规模来说补[蒸馏](https://zhida.zhihu.com/search?content_id=770809348&content_type=Answer&match_order=1&q=%E8%92%B8%E9%A6%8F&zhida_source=entity)基本上不可能了 如果看到这个图片会伤到你 那我要说一句抱歉

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-9ed2285861ae5327234f9cba9ba6a7b8_r.jpg%3Fsource%3D1def8aca)
    
    
    
    
### 知乎用户  Ampere King 发表
    
Big Brother Is Watching You !
    
    
    
    
### 知乎用户  爱学习的乔同学​​​ 发表
    
**声明：本文完全由人类撰写，不含任何 AI 成分，完全无广，完全原创，为技术科普文部分细节进行了简化，个人观点仅供参考。**

就在昨天，[Claude](https://zhida.zhihu.com/search?content_id=770686613&content_type=Answer&match_order=1&q=Claude&zhida_source=entity) 所属的公司 Antheropic 曝出内地众多大模型厂商[蒸馏](https://zhida.zhihu.com/search?content_id=770686613&content_type=Answer&match_order=1&q=%E8%92%B8%E9%A6%8F&zhida_source=entity) Claude，想必大家都看到了。

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-fa8851f7a52c7ec07ec9c92ac8178e9c_r.jpg%3Fsource%3D1def8aca)

而不到 24 小时，事情迎来了反转，原来，是 Claude 蒸馏 [DeepSeek](https://zhida.zhihu.com/search?content_id=770686613&content_type=Answer&match_order=1&q=DeepSeek&zhida_source=entity) 的数据啊。

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-e9a12f0b805b160aa9fb6595ee250cc2_r.jpg%3Fsource%3D1def8aca)

但是，不管是 Claude 蒸馏 DeepSeek，还是 DeepSeek 蒸馏 Claude，他们都共用了一个非常技术的词：

**蒸馏。**

蒸馏是个啥呢？

现在假设你是一个什么都不懂的小学生，但是你必须要通过一门非常难的考试，称之为人类最后的考试。

此时，你有两种资料可以选：A、几万本由人类一字一句编写的书；B、老师根据这几万本书总结出的精华笔记和解题步骤。

如果你选了 A，一个人在那吭哧吭哧地看书，那么这种方法就是预训练。而如果你选了 B，直接跳过看那几万本书的过程，直接学习老师是如何解题的，哪些内容是重点，那么这个过程，就叫做蒸馏。

称之为，你，蒸馏了，老师的知识。

**所以，Claude 蒸馏 DeepSeek 的含义，就在于：Claude 看了 DeepSeek 的解题步骤，然后进行学习。**

那么，你怎么知道 DeepSeek 是如何解题的呢？方法简单到不可置信，那就是直接和 DeepSeek 对话。

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-a05de1584bf43af2e8a2295ee584c1a1_r.jpg%3Fsource%3D1def8aca)

因为 DeepSeek 会输出思考过程，也就是解题步骤，思考结束之后就会有答案，所以 Claude 直接全部 Ctrl+C 复制下来就行，压根不费什么力气，更何况 Claude 用的是 [API](https://zhida.zhihu.com/search?content_id=770686613&content_type=Answer&match_order=1&q=API&zhida_source=entity) 这种批量调用方式，直接把答案写到数据库当中，连 Ctrl+C 都省了。

**但是，这样子蒸馏有个问题，那就是你会变傻。**

为什么呢？因为老师也会犯错，一个老师所能掌握的知识和观念，也是有局限的。

比如，DeepSeek 老师之前就出现了极 BUG，也就是会在输出中随机夹杂几个极字。

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-6f8ed35a721f78cca2eb023238413454_r.jpg%3Fsource%3D1def8aca)

这时候，如果 Claude 学进去了，那么 Claude 是不是也会在输出中夹杂一些乱七八糟的东西呢？

答案是肯定的，比如 Claude 就经常出现中英文夹杂，以及中英文标点符号，尤其是逗号和双引号不分的问题。

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-329ae53646190dfc8c10c0c1cafd9046_r.jpg%3Fsource%3D1def8aca)

其实对于这个问题，解决方案就有两条路：A、兼听则明，偏听则暗。B、不仅仅看笔记，更看原始的书籍。

先来看第一条，其实就是不仅仅盯着一个老师蒸馏，而是对多个老师都进行蒸馏，然后在脑子里面进行整理。

就拿 3 \* 4 = 12 这道题来说，DeepSeek 老师可能会告诉你：把 12 根筷子分成 4 组，每一组由 3 根筷子构成。而 [GPT](https://zhida.zhihu.com/search?content_id=770686613&content_type=Answer&match_order=1&q=GPT&zhida_source=entity) 老师可能会告诉你：直接去背九九乘法表。Kimi 老师可能又会告诉你：在纸上绘制一个三行四列的圆形，然后数一数一共有多少个。

那么，当你下次遇到 3 \* 4 这道题的时候，你的脑子里就会出现三种不同的解题思路，你可以一种一种进行验证，这样子你做错这道题的概率，就会下降很多。

而第二条呢，就是鼓励你在看笔记的时候，也需要翻一翻原文，批判性阅读，而不是全信重点笔记。

比如一个最经典的案例，老师的笔记上写着：故天将降大任于斯人也，于是你学进去了，是斯人。但是你发现做题的时候，标准答案是是人。这时候，你直接翻开了古籍，发现正确的答案就是是人。

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-d38b909b460c6607ace48d60831e512a_r.jpg%3Fsource%3D1def8aca)

这时候你就知道：原来老师写的是不正确的，我要抓紧学习正确的东西。

**所以，怎么蒸馏才不会变傻呢，一种是同时蒸馏多个，另一种是蒸馏的过程中同时对原始语料训练，当然两种方法结合起来食用更佳哦。**
    
    
    
    
### 知乎用户 rejoicelee 发表
    
闭源要搞[开源](https://zhida.zhihu.com/search?content_id=770639775&content_type=Answer&match_order=1&q=%E5%BC%80%E6%BA%90&zhida_source=entity)，说明闭源是准备走死路了。
    
    
    
    
### 知乎用户 ydux 发表
    
想看 v4 踩头 opus4.6
    
    
    
    
### 知乎用户 SamuelPE 发表
    
**同行群嘲已经基本给 [Anthropic](https://zhida.zhihu.com/search?content_id=770697499&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 这次的行为定性了，太 low 了。**

说实在的，开源也好，闭源也好，身为 AI 公司主要任务就是打磨出更好的 AI 产品。对用户而言，实际的产出才是买单的理由。

**Anthropic 刚起步时口碑不错，除了是 [OpenAI](https://zhida.zhihu.com/search?content_id=770697499&content_type=Answer&match_order=1&q=OpenAI&zhida_source=entity) 核心团队背景外，也因为公司大打宪法 AI 口号。**这个宪法式 AI 主要包含三个步骤：

（1）通过监督学习训练模型，使其遵循 “借鉴《联合国人权宣言》、[苹果公司服务条款](https://zhida.zhihu.com/search?content_id=770697499&content_type=Answer&match_order=1&q=%E8%8B%B9%E6%9E%9C%E5%85%AC%E5%8F%B8%E6%9C%8D%E5%8A%A1%E6%9D%A1%E6%AC%BE&zhida_source=entity)及 Anthropic 自身研究” 的伦理原则；

（2）构建一个 “[价值观对齐的偏好模型](https://zhida.zhihu.com/search?content_id=770697499&content_type=Answer&match_order=1&q=%E4%BB%B7%E5%80%BC%E8%A7%82%E5%AF%B9%E9%BD%90%E7%9A%84%E5%81%8F%E5%A5%BD%E6%A8%A1%E5%9E%8B&zhida_source=entity)”；

（3）利用该偏好模型对初始模型的响应进行评估，通过强化学习逐步优化模型输出。

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-4eedff625fd885a651e754a8c71d856d_r.jpg%3Fsource%3D1def8aca)

宪法式 AI 一度被视为打破 AI 训练黑盒的可靠方法，确保 AI 能保持能正确且透明的伦理，不伤害人类。**这种对 AI 安全高度重视的态度得到了许多机构和 LP 的认可，加上公司自己确实有实力，发展和融资一帆风顺，早期的投资人都赚到钱了。**

在上个月，他们还推出了《新宪法》。内容很多，这里我就不展开了，核心的意思就一条：

**当用户需求与 Anthropic 定义的安全伦理发生哪怕极其轻微的冲突时，Claude 都会毫不犹豫地选择拒绝回答。**

这种将价值观把控凌驾于工具实用性之上的做法，也是他们批评中国开源模型缺乏安全监管的理论基石。

### **但谁来定义这个安全伦理，就很值得玩味了。**

以前 B 端业务还没起来的时候，《人权宣言》、《苹果条款》这些更偏向广泛 “C 端用户” 的安全价值的参考权重能给的高，人们还能比较相信其宪法底层是广泛的普世价值。

**但现在大企业、美国国防部明显成为了 Anthropic 更重要的客户爸爸，那这个价值观的定义权是交给了谁？**

科技的探索和发展向来是普世价值和私人盈利之间的博弈，类似的剧情我们在移动互联网时代已经看了不少了，AI 时代也会是一样的情节。市场化，本身就是通过资本实现价值传递，站队和对抗。

**在现在的大环境下，AI 对抗会是一直存在的大议题。作为一家美国公司，它的屁股已经决定了它的立场。**

所以，有 LLM 需求的朋友，尽量选择自己能够长期稳定使用的产品吧，很多崩塌和决裂不是立马发生，而是早有信号。
    
    
    
    
### 知乎用户 彼岸花​ 发表
    
把这新闻发给 claude ta 是会知道自己是 claude，还是觉得自己是 [deepseek](https://zhida.zhihu.com/search?content_id=770829198&content_type=Answer&match_order=1&q=deepseek&zhida_source=entity)。
    
    
    
    
### 知乎用户 oe19901019 发表
    
大争之世，有些地缘问题我们无法避免。不如换个角度，不如看看 [Anthropic](https://zhida.zhihu.com/search?content_id=770692670&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 这篇文章里写了什么值得注意的问题。在对抗的更加彻底之前，从中学习，或者说从争吵中学习。

* * *

为何[蒸馏](https://zhida.zhihu.com/search?content_id=770692670&content_type=Answer&match_order=1&q=%E8%92%B8%E9%A6%8F&zhida_source=entity)至关重要——蒸馏的潜在风险
---------------------------------------------------------------------------------------------------------------------------------------------------

非法蒸馏出的模型缺乏必要的安全防护，会带来重大的国家安全风险。Anthropic 及其他美国公司构建的系统旨在防止国家及非国家行为体利用人工智能从事诸如开发[生物武器](https://zhida.zhihu.com/search?content_id=770692670&content_type=Answer&match_order=1&q=%E7%94%9F%E7%89%A9%E6%AD%A6%E5%99%A8&zhida_source=entity)或实施[恶意网络活动](https://zhida.zhihu.com/search?content_id=770692670&content_type=Answer&match_order=1&q=%E6%81%B6%E6%84%8F%E7%BD%91%E7%BB%9C%E6%B4%BB%E5%8A%A8&zhida_source=entity)等行为。通过非法蒸馏构建的模型不太可能保留这些防护措施，这意味着危险能力可能在大量防护被完全剥离的情况下扩散。

对美国模型进行蒸馏的外国实验室随后可将这些未受防护的能力植入军事、情报和监控系统中——使威权政府得以部署前沿人工智能用于攻击性网络行动、[虚假信息宣传](https://zhida.zhihu.com/search?content_id=770692670&content_type=Answer&match_order=1&q=%E8%99%9A%E5%81%87%E4%BF%A1%E6%81%AF%E5%AE%A3%E4%BC%A0&zhida_source=entity)和[大规模监控](https://zhida.zhihu.com/search?content_id=770692670&content_type=Answer&match_order=1&q=%E5%A4%A7%E8%A7%84%E6%A8%A1%E7%9B%91%E6%8E%A7&zhida_source=entity)。若蒸馏模型被开源，随着这些能力不受任何单一政府控制地自由传播，此类风险将成倍增加。

* * *

从这段来说，这个对国内模型厂商也是要注意的。比如物理上来讲[无人机](https://zhida.zhihu.com/search?content_id=770692670&content_type=Answer&match_order=1&q=%E6%97%A0%E4%BA%BA%E6%9C%BA&zhida_source=entity)，我们不希望我们出口的两用无人机以后被用于对国人的一些有害行为。Anthropic 作为一家美国公司，要保护美国人的利益，那么国内的大模型公司是否要考虑防止外国公司用国内的开源大模型被用于潜在的地缘冲突中。

毕竟 Anthropic 已经被美国国防部用于委内瑞拉的事情了，而我们干脆就是把这些模型都开源了。

* * *

我们的发现——如何识别蒸馏？
--------------

以下详述的三个蒸馏行动遵循了相似的套路，利用欺诈账户和代理服务大规模访问 [Claude](https://zhida.zhihu.com/search?content_id=770692670&content_type=Answer&match_order=1&q=Claude&zhida_source=entity)，同时规避检测。这些提示词的数量、结构和关注点与正常使用模式截然不同，反映出其目的是有意识地提取能力，而非合法使用。

我们通过 IP 地址关联、请求元数据、基础设施指标，以及在部分情况下结合行业合作伙伴的佐证（他们也在自家平台上观察到相同的参与者和行为），以高置信度将每个行动归因于特定实验室。每个行动都针对 Claude 最具差异化的能力：[代理式推理](https://zhida.zhihu.com/search?content_id=770692670&content_type=Answer&match_order=1&q=%E4%BB%A3%E7%90%86%E5%BC%8F%E6%8E%A8%E7%90%86&zhida_source=entity)、[工具使用](https://zhida.zhihu.com/search?content_id=770692670&content_type=Answer&match_order=1&q=%E5%B7%A5%E5%85%B7%E4%BD%BF%E7%94%A8&zhida_source=entity)和[编码](https://zhida.zhihu.com/search?content_id=770692670&content_type=Answer&match_order=1&q=%E7%BC%96%E7%A0%81&zhida_source=entity)。

* * *

这段来讲，由于国内很多模型厂商都开源了，那么也就没有 IP 地址关联、请求元数据、基础设施指标。。。这些事情了，只需要私有化部署即可。对于开源大模型来讲，这无疑是更高的要求和挑战。

* * *

我们的应对措施——如何应对？
--------------

我们持续投入巨资加强防御，旨在使此类蒸馏攻击更难实施、更易识别。这些措施包括：

*   **检测**。我们构建了多个分类器和行为指纹识别系统，旨在识别 API 流量中的蒸馏攻击模式。这包括检测用于构建推理训练数据的思维链诱导行为。我们还构建了用于识别跨大量账户协同活动的检测工具。
*   **情报共享**。我们正与其他 AI 实验室、云服务提供商及相关主管部门共享技术指标。这有助于更全面地了解蒸馏领域的状况。
*   **访问控制**。我们加强了对教育账户、安全研究项目和初创组织的验证——这些是设置欺诈账户最常被利用的途径。
*   **反制措施**。我们正在开发产品、API 和模型层面的安全防护，旨在降低模型输出对非法蒸馏的有效性，同时不损害合法客户的使用体验。

然而，没有哪家公司能独自解决这个问题。如上所述，应对如此规模的蒸馏攻击需要 AI 行业、云服务提供商和政策制定者协同响应。我们发布此信息，旨在让所有关心此事结果的相关方都能获得这些证据。

* * *

由于我们开源了这些模型，导致我们不能像他们那样通过封杀 IP 访问的方式来进行限制。但我们需要认识到，没有哪家公司能独自解决这个问题。

尤其考虑到 Anthropic 已经被美国国防部用于委内瑞拉的事情。我们应该警惕和预防国内开源大模型被一些国家用于相关领域的潜在风险。
    
    
    
    
### 知乎用户 瞌睡来了倒头睡 发表
    
闲的，大家不都在互相蒸么。  
不蒸的早让梯队甩飞了。

[Anthropic](https://zhida.zhihu.com/search?content_id=770710408&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 搁着罪己诏呢
    
    
    
    
### 知乎用户 鹏展博 发表
    
充分说明了 [Anthropic](https://zhida.zhihu.com/search?content_id=770656792&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 是一家价值观极其扭曲的公司，企业还敢继续用它那简直就是把勒死自己的绳子交给了 Anthropic。
    
    
    
    
### 知乎用户 闭关中  发表
    
[Anthropic](https://zhida.zhihu.com/search?content_id=770673037&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 这个逼，这次是犯了众怒了。硅谷几乎没有人占他们一边的，都是喷的
    
    
    
    
### 知乎用户 我来过 发表
    
dario 不愧是百度出来的。
    
    
    
    
### 知乎用户 拿 NUC 当板砖 发表
    
AGI 实现的道路上，我自己的数据无所谓，用其他模型合成数据也无所谓，大家都是人类文明的备份，谁能实现最终的 AGI，谁就是正确的
    
    
    
    
### 知乎用户 锦乡悦堂 PPT 发表
    
去看了原文。我的第一感觉是：这个世界果然就是双标 + 草台班子。

如何看待？

不用我们自己说，让同为美国知名 AI 公司的 [Grok](https://zhida.zhihu.com/search?content_id=770691481&content_type=Answer&match_order=1&q=Grok&zhida_source=entity) 来说吧（输入问题，用自动模式，没有其他任何带倾向的提示词，下面截图中都可以看到）：

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-c235bc484987eb29f6646944afbda484_r.jpg%3Fsource%3D1def8aca)

我严重同意[马斯克](https://zhida.zhihu.com/search?content_id=770691481&content_type=Answer&match_order=1&q=%E9%A9%AC%E6%96%AF%E5%85%8B&zhida_source=entity)在 [Anthropic](https://zhida.zhihu.com/search?content_id=770691481&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 这个推下的回复：

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-0be39170033f273869a49e90bc782f70_r.jpg%3Fsource%3D1def8aca)
    
    
    
    
### 知乎用户 mike 发表
    
支持！而且公司所有华人都有嫌疑，建议开了。白的黑的只要去过中国的，或者任何关联的，全部开掉！
    
    
    
    
### 知乎用户 小杠杆 发表
    
用脚指头想想也知道

anthropic 这种事情也没少干

大家互相蒸罢了

你 anthropic 完全自己训练的权重，能跟着上整体 AI 的发展步伐？

互相踩着对面的肩膀往上冲罢了
    
    
    
    
### 知乎用户 枬枬 发表
    
以前谷歌也蒸馏[文心一言](https://zhida.zhihu.com/search?content_id=770802333&content_type=Answer&match_order=1&q=%E6%96%87%E5%BF%83%E4%B8%80%E8%A8%80&zhida_source=entity)啊，而且谷歌家哪个领导还出来说这种数据蒸馏是很正常的（这个事情当时我是看过视频确认过的，问你是谁，[gemini](https://zhida.zhihu.com/search?content_id=770802333&content_type=Answer&match_order=1&q=gemini&zhida_source=entity) 当时还有概率会说 “我是文心一言”）。然后大家也都觉得很正常，没有人去指责谷歌。

还有一件事，去年 [deepseek](https://zhida.zhihu.com/search?content_id=770802333&content_type=Answer&match_order=1&q=deepseek&zhida_source=entity) 爆火后，有一段时间受到大量攻击， App 几乎用不了，当时还有传言说 360 还帮 deepseek 反攻击什么的，（后面事实证明 360 没帮，是蹭热度的）我不知道有没有人记得。然后一段时间 [chatgpt](https://zhida.zhihu.com/search?content_id=770802333&content_type=Answer&match_order=1&q=chatgpt&zhida_source=entity) 和 gemini 回复的时候就会莫名其妙的出现中文，[reddit](https://zhida.zhihu.com/search?content_id=770802333&content_type=Answer&match_order=1&q=reddit&zhida_source=entity) 上我看到好几个老美的贴图，他们明明是全英文对话，但是在 GPT 的思考过程或者是回答中会莫名其妙出现中文。所以这个攻击是不是 deepseek 被蒸馏呢？

以上我说的两件事都是事实。但是没有人关心，没有人在乎，没有人为中国的 ai 被攻击被蒸馏发声。

我们中国媒体是没有话语权的，我们的大模型被人家蒸馏了，美国人说这样很正常，我们也觉得很正常，没有人会去指责或者是维权。相反如果是我们去蒸馏别人的话，英文媒体就铺天盖地的指责我们。

归根结底是因为事件的定义权以及话语权不在我们这里。

另外 [A 社](https://zhida.zhihu.com/search?content_id=770802333&content_type=Answer&match_order=1&q=A%E7%A4%BE&zhida_source=entity)对我国怀有巨大的恶意（不知道老板当年在百度受过什么委屈），因此他的指责我是不相信，claude 写代码好用（我自己也在用），所以国内有很多中转站，我估计他说的这些所谓的蒸馏攻击，其实是中转站。或者是有一些小伙伴频繁切 vpn 导致被判断为是恶意攻击，因为我自己切 vpn 的话，他也会跳出提示检测我是不是恶意攻击。
    
    
    
    
### 知乎用户 Edelweiss 发表
    
美国版百度，不愧是互联网黄埔军校出来的
    
    
    
    
### 知乎用户  PFish 发表
    
？他这不是自杀吗，就差把自己 “我给每个用户都做了标记，你们所有对话都可以被对应，你们毫无隐私可言” 说出来了。别家好歹还装作会混淆一下，遮蔽下敏感数据，他直接全吐出来了
    
    
    
    
### 知乎用户 知乎用户大 B 发表
    
有些人听不懂，我翻译一下，[腾讯公司](https://zhida.zhihu.com/search?content_id=770672289&content_type=Answer&match_order=1&q=%E8%85%BE%E8%AE%AF%E5%85%AC%E5%8F%B8&zhida_source=entity)发文表示坚定维护创作者权益，坚持打击盗版，为市面上某些友商不齿。
    
    
    
    
### 知乎用户 lolipop 发表
    
干脆让百度把 Claude 收购了，他就不 bb 了
    
    
    
    
### 知乎用户  tsy0807 发表
    
科技竞赛中模仿与创新并存，但关键还是看原创力。就像做菜，模仿容易，做出特色难。
    
    
    
    
### 知乎用户 悟道小沙弥 发表
    
1、干的漂亮！

2、[anthropic](https://zhida.zhihu.com/search?content_id=770837351&content_type=Answer&match_order=1&q=anthropic&zhida_source=entity) 里不也都是华人嘛？都是自己人~ 何必计较那么多
    
    
    
    
### 知乎用户 西伯利亚在逃土豆 发表
    
敢干这种事还当成绩讲出来，充分说明 anthropic 自己也知道调他接口的没有什么特别重要的事情，他的 AI 生成啥样对客户来说也压根无所谓。

要是有第三方支付系统敢这样公开宣称给他不喜欢的用户的接口调用返回随机金额误差，怕不是过不了几个月就暴死退出市场了。
    
    
    
    
### 知乎用户 李大猫  发表
    
[Anthropic](https://zhida.zhihu.com/search?content_id=770620008&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity): 我那谁的黑料都有，包括你的。
    
    
    
    
### 知乎用户 刘笨笨 发表
    
如果我开一个[电商直播](https://zhida.zhihu.com/search?content_id=770680415&content_type=Answer&match_order=1&q=%E7%94%B5%E5%95%86%E7%9B%B4%E6%92%AD&zhida_source=entity)，自己做选品自己卖，当然很合理。

如果我开一个电商直播，直接去排名第一的直播间，一件一件把他家卖的好的商品买下来，然后根据包装和发货地点去找到源头供应商，再跟它卖一样的商品（这里假设对方商品都是他们自己采购的，不是来自平台的商品库，那就太没难度了），听上去我确实是走了一条捷径。

但是东西是我花钱买的，也没任何限制你卖的我就不能卖（不考虑独家代理）。

你觉得我有些 low 我没辙。

但你跳出来说你知道哪些买家是我的人，以后就不让我买了，就算我以后用别的账号买，你也给我发次品或者假货……

这就不太对了吧？
    
    
    
    
### 知乎用户 之乎者也 发表
    
我觉得你买 1 万瓶可乐，咋嘛滋味品出配方，在家自己做可乐卖可乐，没问题吧
    
    
    
    
### 知乎用户  jaray 发表
    
谁能保证自己的训练数据不是别人的模型产生出来的呢 为来我们互联网会充满各种 ai 产生的数据 就问你用还是不用
    
    
    
    
### 知乎用户 专业炖大鹅 发表
    
claude 是我用的最好用的 ai 了。
    
    
    
    
### 知乎用户 王卓卓 发表
    
违法不违法, 道德不道德不好说

像 kimi 这种本身就是毫无道德的公司, 毫不意外的每次扫黄都有你

但更重要的是, 这说明了这几家的模型能力永远不可能超过 Claude 了, 并且他们自己也这么认为
    
    
    
    
### 知乎用户  Altriasjy​ 发表
    
[Anthropic](https://zhida.zhihu.com/search?content_id=770694487&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 指控 [DeepSeek](https://zhida.zhihu.com/search?content_id=770694487&content_type=Answer&match_order=1&q=DeepSeek&zhida_source=entity) 蒸馏：一场可能加速数据壁垒到来的合规争议
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

很多讨论在第一步就发生了错位：一些人认为这是对国内 AI 发展的打压，另一些人则借坡下驴，批评 DeepSeek 不过如此。

但在站队之前，可能有几个问题值得先厘清：Anthropic 的指控到底属于什么性质？[DeepSeek-R1](https://zhida.zhihu.com/search?content_id=770694487&content_type=Answer&match_order=1&q=DeepSeek-R1&zhida_source=entity) 的技术贡献是否会因此归零？这件事对行业格局意味着什么？

首先根据公告内容，存在大规模交互... 欺诈账号...distillation...

如果属实，本质是违反服务条款 + 商业不正当竞争。

而这类事情的处理路径非常明确：举证 - 协商 - 仲裁 / 诉讼。

其次，如果 DeepSeek，[Moonshot](https://zhida.zhihu.com/search?content_id=770694487&content_type=Answer&match_order=1&q=Moonshot&zhida_source=entity) 和 [MiniMax](https://zhida.zhihu.com/search?content_id=770694487&content_type=Answer&match_order=1&q=MiniMax&zhida_source=entity) 等公司认为 Anthropic 公司在诬告，几方走法律途径，按程序走即可。

或者反过来，用 Claude 公告中提到的类似方法找对方蒸馏的流量异常证据，用同样的公开方式点名。

P.S. [Claude 模型](https://zhida.zhihu.com/search?content_id=770694487&content_type=Answer&match_order=1&q=Claude%E6%A8%A1%E5%9E%8B&zhida_source=entity)回复我是 DeepSeek 这个各大模型都太常见了，DeepSeek 之前也回复过 “我是 GPT”，这本身不构成有效证据，真正的证据在于 API 流量模式的异常。

### （1）背景

我关注并开始较频繁使用 deepseek 不算早也不算晚，当时就是被价格便宜吸引的（差不多当时是在 2024 年 05，deepseek-v2-coder 发表之后），而且当时充 50 元，感觉用了很久都有富裕。当时还只能调用 api（印象里）。

![](https://images.weserv.nl/?url=https%3A//pica.zhimg.com/v2-80053113d2c3f5eaf2843580f3c6997f_r.jpg%3Fsource%3D1def8aca)

但当时的使用效果相比 Claude 和 GPT 还是逊色不少。真正让 DeepSeek 在大众视野中封神的，是 2025 年 1 月发布的 DeepSeek-R1。

不过，当我大规模使用 R1 之后，反而越来越觉得其幻觉问题不容忽视。比如讨论问题，调研技术，撰写研究方案时，时不时蹦出 “量子” 等，之类离谱的幻觉。因此 R1 逐渐不再是我的主力模型。

从纯粹的用户视角看，蒸馏不蒸馏其实**无关痛痒**。它价格亲民、推理能力强，切实解决了许多实际问题。但对于公司层面的行为，如果指控属实且对方选择走法律途径，也只能依据相关条例来裁决。**喜欢一家公司的产品，和客观评价这家公司的商业行为，是两件事。**

### （2）思考模型的发展中 R1 不是起点

很多评论容易扭曲历史，把 DeepSeek-R1 塑造成无与伦比，前无古人的救世主。

但偏爱归偏爱，事实归事实。这种偏爱和蒸馏指控之间不构成任何逻辑冲突。

| 时间节点 | [OpenAI](https://zhida.zhihu.com/search?content_id=770694487&content_type=Answer&match_order=1&q=OpenAI&zhida_source=entity) (GPT / o 系列) | Anthropic (Claude) | DeepSeek |
| --- | --- | --- | --- |
| 2022 年 12 月 | / | Constitutional AI 论文中已明确提到利用 [chain-of-thought](https://zhida.zhihu.com/search?content_id=770694487&content_type=Answer&match_order=1&q=chain-of-thought&zhida_source=entity) 风格推理来提升表现 \[1\] | / |
| 2024 年 5–6 月 | 发布 [GPT-4o](https://zhida.zhihu.com/search?content_id=770694487&content_type=Answer&match_order=1&q=GPT-4o&zhida_source=entity)（多模态） | 发布 Claude 3.5 Sonnet（登顶编程与逻辑榜单，当时世界最强非 CoT 模型） | 发布 DeepSeek-V2（MoE 成本优势，通用模型） |
| 2024 年 9 月 | 发布 o1-preview / o1-mini：明确” 推理时计算预算 / think longer” 路线 \[2\] | / | 内部启动 V3 / R1 推理管线探索 |
| 2024 年 10 月 | o1 系列迭代 | Claude 3.5 Sonnet 更新版（强化 coding / agent） | / |
| 2024 年 11 月 | / | / | 发布 R1-Lite-Preview（首次公开 reasoning RL 方向） |
| 2024 年 12 月–2025 年 1 月 | o1 系列持续 | / | 先后发布 V3 和 R1 正式版 \[3\] |
| 2025 年 2 月 | / | 发布 Claude 3.7 Sonnet（extended thinking，推理功能可调 / 可见）\[4\]；同月公开 DeepSeek 蒸馏指控 | R1 生态扩散 |
| 2025 年春–夏 | o 系列持续迭代 | thinking 模式持续优化 | 推理 RL 成本优势持续 |
| 2026 年初 | 推理模型成为默认范式 | 发布 Claude Opus 4.6：adaptive thinking \[5\] | 推理 RL 路线延续 |

```
\[1\] https://www.anthropic.com/research/constitutional-ai-harmlessness-from-ai-feedback
\[2\] https://community.openai.com/t/new-reasoning-models-openai-o1-preview-and-o1-mini/938081
\[3\] https://arxiv.org/pdf/2501.12948
\[4\] https://www.anthropic.com/news/claude-3-7-sonnet
\[5\] https://www.anthropic.com/news/claude-opus-4-6

```

上述时间线指出了几个事实：

1）从大模型到推理模型的技术演进，是全行业收敛的共识路线，不是任何一家独创的。包括推理训练 / CoT 使用，在 Anthropic 的公开研究里至少 2022 年已出现；而 OpenAI 在 2024 年 9 月已将推理模型产品化（o1）

2）如果 Claude 要抄 r1，则需要满足几个前提

前提 1：R1 首创路线

前提 2：Claude 此前不具备推理能力

前提 3：Claude 是突然出现的转向

对于前提 1，o1 在 R1 之前数月已确立；对于前提 2，Claude 3.5 Sonnet 编程和逻辑能力早已顶尖，甚至在某些编程问题上比 o1 推理能力还要强；对于前提 3，时间线显示 3.7 是小版本号更新，属于正常产品演进。

很多争论把三件事混为一谈，

| 层次 | 含义 | 代表 |
| --- | --- | --- |
| （1）训练层面 | 用 RL / [SFT](https://zhida.zhihu.com/search?content_id=770694487&content_type=Answer&match_order=1&q=SFT&zhida_source=entity) / 偏好对齐等，让模型更会多步推理 | 所有前沿实验室都在做 |
| （2）推理时计算分配 | 同一模型在推理时给更多 token / 步骤 / 搜索预算（think longer） | o1、R1 的核心产品特征 |
| （3）可见性策略 | 把中间推理过程展示给用户，或选择不展示 | o1 不展示；R1 展示；Claude 3.7 可选展示 |

DeepSeek-R1 主要在（1）和（2）上做得很透明；Claude 3.7 的 “extended thinking mode” 突出的是（2）和（3）的产品化。把（3）出现的晚，推导成（1）能力不存在，逻辑上不成立。

### （3）别拿数据不当干粮

数据语料这一步，是人工智能发展路径上不可避免的瓶颈。

算法是公开考卷，算力是可以买的计算器，**数据就是你自己做过的全部练习题和老师的批改记录。**难点在于**，**较难可公开获取，难以直接复制，且积累时间与投入成本成正比。

其中，算力虽然也算瓶颈，但是 DeepSeek 的路径也证明了可以通过工程优化来部分弥补。

| 要素 | 可复制性 | 现状 |
| --- | --- | --- |
| 算法 | 极高（论文公开，人才流动，[RLHF](https://zhida.zhihu.com/search?content_id=770694487&content_type=Answer&match_order=1&q=RLHF&zhida_source=entity) / [DPO](https://zhida.zhihu.com/search?content_id=770694487&content_type=Answer&match_order=1&q=DPO&zhida_source=entity) / [GRPO](https://zhida.zhihu.com/search?content_id=770694487&content_type=Answer&match_order=1&q=GRPO&zhida_source=entity) 等范式数月内全行业吸收） | 几乎不构成壁垒 |
| 算力 | 中等（可通过资金购买，但受芯片禁令等地缘因素制约） | DeepSeek 受限但可通过工程优化部分弥补 |
| 数据 | 极低（高质量标注数据生产成本极高，且具有强先发优势） | 真正的护城河 |

这点其实也证实了为什么 OpenAI 能首发 [ChatGPT](https://zhida.zhihu.com/search?content_id=770694487&content_type=Answer&match_order=1&q=ChatGPT&zhida_source=entity)，原因之一也是这家公司在数据层面的**长期结构性投入，**包括与出版社 / 新闻机构达成独家数据授权（投入数亿美元级别）；从 GPT-3 时代起就雇佣大量标注团队积累人类偏好数据；ChatGPT 上线后数以百亿计的真实用户交互形成数据飞轮等等

**如果 DeepSeek 在数据层面领先于其他公司，那么其产品发布情况本身就应该领先其他公司，而非跟随性的。**

即在数据领先的前提下，DeepSeek 完全有能力在 o1 之前就推出类似产品，因为 “推理时扩展计算” 的学术思路 2023 年就已公开发表，相关技术在 2022 年就已经广泛讨论。

因此这也证实了 DeepSeek 发展的合理性，即 DeepSeek 在数据层面不具备独立领先优势，因此必须依赖外部数据源来加速追赶。

这也就回到了数据蒸馏的关键。

数据蒸馏是 ChatGPT 发布以来，整个行业想要追平数据壁垒的核心手段之一。其本质是：OpenAI / Anthropic 花数年、投入数亿美元积累的数据价值，凝结在模型的智力中。蒸馏者通过 API 让模型将这些智力以文本形式输出，从而直接用于训练自己的模型。

包括思维链提取也是如此，例如，要求 Claude 想象并清晰表达完成回复背后的内部推理，并逐步写出来（write it out step by step）。这种基于 Prompt 诱导的思维链提取，是业界标准的蒸馏手段，与目标模型是否自带、是否隐藏思维链毫无关系。只要目标模型基础智力足够高，就可以通过 Prompt 强制其生成高质量推理轨迹。

**有评论认为 15 万次请求量太小，几乎是个人级别。**

但实际上普通聊天和蒸馏工程在量级上和质量上就存在差距。

普通人的 15 万次聊天可能是：你好，帮我写封邮件。但定向蒸馏请求是高度结构化的。单次请求可包含数千 Token 的复杂代码 / 数学题，输出同样是数千 Token 的完整推理链。15 万次这样的请求，足以产出数亿 Token 的高密度推理数据。

同时，R1 自己的论文中明确提到了冷启动 SFT 数据的需求。在业内，几万到十万条极其优质的推理数据就足够完成模型的行为对齐和 RL 冷启动（参考 Stanford Alpaca 的 5.2 万条数据集）。15 万条高强度结构化交互，在模型训练领域绝对是符合商业公司训练模型的规模。

**另一种经典观点是，500 万美金是纯训练模型的算力成本。**

但这恰恰是蒸馏的动机。

如果要聘请博士级别的数学家和高级工程师，从零手写并校验 15 万条包含详尽推理步骤和评分的高难度数据，人力成本将轻易突破数千万美元，且耗时数月；

通过自动化脚本消耗少量 API 费用（15 万次请求的成本可能仅在十万美元级别），就能在几天内从 Claude 3.5 Sonnet 那里提取相当于数千万美元人工标注成本的优质数据；

**因此正是因为用低成本 API 蒸馏替代了极其昂贵的专家人工标注，500 万美元的算力预算才在工程上可行。**

### （4）别把商业竞争上升到情绪纷争

你跟商业公司谈道德，对方觉得你在搞笑。

这种数据蒸馏本身就是属于商业竞争行为的一种，就看己方留痕情况和对方审查情况。

如果 OpenAI 要追究各公司的蒸馏行为也完全可能，但同样可能面临反向审查。毕竟 OpenAI 自身也深陷版权数据争议（纽约时报诉讼等）。

**实际上，Anthropic 点名的依据是证据，不是技术排名。**

按 arena 榜单上的排名，如果 claude 是担心 deepseek 冲击它的生态，那么首先应该点名 dola-seed 背后的字节（比如 seedance 也正在受到版权纠纷，但跟 Claude 没关系主要是因为视频素材，在国内还是影视剧风掀起的）

如果是考虑攻击开源领域的技术，那么 qwen 也应该被列入。但实际上目前排名靠前的只有 kimi 背后的 MoonShot，而 MiniMax 和 DeepSeek 都在稍微靠后的位置

![](https://images.weserv.nl/?url=https%3A//pica.zhimg.com/v2-1bff46eccf64837dcc459e1830557fc5_r.jpg%3Fsource%3D1def8aca)

根据公开信息，Anthropic 的点名依据是 API 流量审计中发现的异常模式（约 24,000 个欺诈账户、1,600 万次交互的结构化特征），而非 “谁对我竞争威胁最大就先告谁” 否则字节和阿里这两个体量更大的公司能掀起更大的舆论效应。因此这本身就是是**基于证据而非基于动机**的点名。

**综上，不要把三件事混为一谈。**

喜欢 DeepSeek，是因为公司在技术追求上展现的纯粹性；

使用 DeepSeek，是因为兼顾便宜和较高的准确性；

DeepSeek 被指控蒸馏，这是商业 / 法律层面的事实认定问题。

三者互不矛盾。即便 DeepSeek 因此受到处罚，它的产品大概率还是会被持续使用，其研究思想也会被延续和拓展。别把商业竞争上升到情绪纷争上。

### （5）数据壁垒可能正在加速到来

如果说 Anthropic 此举还有什么更深远的意义，那就是进一步敲响了数据瓶颈的警钟。

**平台开始系统性保护推理数据，免费午餐可能要结束。**

过去几年，后发者可以通过 API 蒸馏以极低成本获取前沿模型凝结的数据价值，这相当于行业的一种免费午餐。但随着前沿实验室强化 API 使用审计和异常检测（如本次事件）；服务条款中对竞争性使用的限制越来越严格；技术层面的反蒸馏手段不断升级（如 o1 隐藏思维链、输出水印等）；

低成本蒸馏的窗口正在快速关闭。

这与早期互联网平台限制 scraping 的逻辑相同。

公司自建高质量标注数据的成本（博士级标注员 + 多轮校验），与低成本 API 蒸馏之间的差距是巨大的。当蒸馏路径被封堵后，这个成本差将直接反映在模型迭代速度上。

**没有独立数据积累能力的公司，可能会在下一轮竞争中掉队。即**

1）拥有海量真实用户交互数据的公司（OpenAI、Google、Anthropic、Grok、字节、阿里等）将获得更大的结构性优势；

2）依赖开源 + 蒸馏路线的中小实验室将面临更高的数据获取门槛；

3）合成数据（Synthetic Data）技术的重要性将进一步上升。即如何用自家模型生成高质量训练数据，将成为核心竞争力。

**数据，可能又将或者将持续成为人工智能领域发展的基础性问题。这次事件不过是这个底层逻辑浮出水面的一个切面。**

### **附言**

DeepSeek 的技术路线（成本效率、reasoning RL、配方公开）不会因蒸馏争议而失去意义；Anthropic 的指控若成立，也只是商业违规问题。

两件事可以同时为真。承认前者不需要否认后者，反之亦然。将商业竞争转化为情绪对立，不仅解释力有限，而且会遮蔽真正值得关注的行业趋势。

此外，作为用户，为什么不直接为某家公司站台？

这是因为当用户付费（或免费）使用了 DeepSeek 的服务时，在这个关系中

**服务提供方有义务确保其服务的合规性和可持续性，用户也有权关注并维护自己所使用服务的稳定性**。这种关注的正确方式是要求服务方给出说明或保持产品稳定更新，而不是替服务方攻击质疑者。

这和学术论文发表的逻辑完全一致：

一篇论文如果使用了来源不明确或敏感的数据（例如未通过伦理审查委员会 / IRB 审批），被期刊警告甚至要求发表勘误声明。**读者没有任何义务主动替作者站台**。相反，作者本身就应当确保公开发表所用数据的合法性与合规性。读者可以继续认为这篇论文的方法论有价值，同时也完全可以要求作者对数据来源给出明确说明。两者不矛盾。

**喜欢一家公司的产品、使用一家公司的服务、客观评价一家公司的商业行为，是三件独立的事情。**

把它们绑定在一起，既不帮助这家公司解决问题，也不帮助用户保护自身权益。
    
    
    
    
### 知乎用户 wwwww 发表
    
臭不要脸的反华公司，到处未授权抄别人的[知识产权](https://zhida.zhihu.com/search?content_id=770643170&content_type=Answer&match_order=1&q=%E7%9F%A5%E8%AF%86%E4%BA%A7%E6%9D%83&zhida_source=entity)自己还在这叫上了
    
    
    
    
### 知乎用户 野生军刀 发表
    
a 社首偷，再偷必究?
    
    
    
    
### 知乎用户 candy 小锤 发表
    
我说句实话，就蒸你一下怎么了？

以前的云市场国内跟不上，导致 [AWS](https://zhida.zhihu.com/search?content_id=770657749&content_type=Answer&match_order=1&q=AWS&zhida_source=entity) 等漫天收价份额还贼高。

现在 [tokens](https://zhida.zhihu.com/search?content_id=770657749&content_type=Answer&match_order=1&q=tokens&zhida_source=entity) 国内算跟上了，虽然能力可能差你一点，但是我就挑战你 [Anthropic](https://zhida.zhihu.com/search?content_id=770657749&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 的价格，怎么着？

训练这块现在难道还有版权了，Anthropic 跑的不也是三方用户的数据，自己也不算光彩，加上投毒和过度信息采集，真法庭打起来保不准谁更虚吧。

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-dd5a5cd7638599795ffc117e879bfbef_r.jpg%3Fsource%3D1def8aca)

Anthropic 已经确定是一家极度反华的公司了，天天封锁国内 IP，推特嘴国内公司，我只能说也就让你半年😋

本来 Anthropic 的模型也不可能持续高速发展，等你到瓶颈了，价格又没有优势，准备被市场淘汰吧
    
    
    
    
### 知乎用户  AI 知几城 发表
    
工业级模型蒸馏与大国人工智能博弈：基于 Anthropic 对华技术指控的深度解构与战略突围报告
------------------------------------------------

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-9e9aab99c6aee53099506f41e7258b5e_r.jpg%3Fsource%3D1def8aca)

昨天，全球人工智能产业的竞争格局又迎来了一次极具破坏性的舆论与技术碰撞。

引言：一场震撼全球科技与地缘政治的 “点名”
----------------------

在 2026 年 2 月底，全球人工智能产业的竞争格局迎来了一次极具破坏性的舆论与技术碰撞。美国生成式人工智能领军企业 Anthropic 发布了一份措辞严厉且极具争议性的前沿安全调查报告，公开指控中国三家头部 AI 实验室——深度求索（DeepSeek）、月之暗面（[Moonshot AI](https://zhida.zhihu.com/search?content_id=770657113&content_type=Answer&match_order=1&q=Moonshot+AI&zhida_source=entity)）和 [MiniMax](https://zhida.zhihu.com/search?content_id=770657113&content_type=Answer&match_order=1&q=MiniMax&zhida_source=entity)——对其旗下的大语言模型 Claude 实施了所谓的 “工业级规模的蒸馏攻击”（Industrial-scale distillation attacks） 1。根据该报告的详细披露，这三家中国企业涉嫌通过构建高度复杂的代理中介网络，注册并操控了大约 2.4 万个虚假账户，以此绕过 Anthropic 基于服务条款（Terms of Service, [ToS](https://zhida.zhihu.com/search?content_id=770657113&content_type=Answer&match_order=1&q=ToS&zhida_source=entity)）设定的区域访问限制，并在短期内与 Claude 模型进行了超过 1600 万次的高频交互 1。Anthropic 宣称，这些攻击的核心目的在于系统性地 “窃取”Claude 底层的核心推理逻辑、代码生成范式以及多智能体工具调用能力，从而帮助中国本土大模型以极低的算力成本和极短的研发周期实现技术跃升 2。

这一指控并非孤立事件。仅仅在一个月前的 2026 年 1 月，ChatGPT 的母公司 [OpenAI](https://zhida.zhihu.com/search?content_id=770657113&content_type=Answer&match_order=1&q=OpenAI&zhida_source=entity) 同样对 DeepSeek 发出了类似指控，声称其发现了中国初创公司通过不当手段提取其专有模型能力的证据 5。由于 DeepSeek 当时刚刚发布了性能震撼全球且成本极低的新一代推理模型，不仅直接导致美国 AI 科技股的市值在单日内蒸发近一万亿美元，更彻底颠覆了华盛顿政策制定者对 “美国在通用人工智能（AGI）领域占据绝对垄断地位” 的传统假设 5。在此背景下，Anthropic 的 “实锤” 指控无疑在美国政界、法律界及全球技术社区引发了更为剧烈的震荡。美国舆论与部分对华鹰派借此强化了 “中国 AI 技术高度依赖美国” 的政治叙事，并顺势呼吁进一步收紧对华高端半导体芯片的出口管制 7。与此同时，包括科技巨头埃隆 · 马斯克（[Elon Musk](https://zhida.zhihu.com/search?content_id=770657113&content_type=Answer&match_order=1&q=Elon+Musk&zhida_source=entity)）在内的众多技术专家则对 Anthropic 提出了尖锐的 “双重标准” 批评，指出以 Anthropic 为代表的硅谷巨头在构建自身模型壁垒时，同样依赖于未经授权的大规模互联网数据抓取 10。

本报告旨在剥离单一的商业公关情绪与情绪化争论，从底层技术架构、实证基准测试、知识产权法理、地缘政治博弈以及宏观产业政策等多个专业维度，深度剖析这一事件的真实性与内在本质。在此基础上，本报告将全面回应 “中国 AI 是否面临被卡脖子危机” 这一关乎产业生死的战略诘问，并系统性地梳理出中国人工智能产业在算力基础设施重构、数据资产内生化及国际合规法律体系构建方面的突围路径。

第一章：事件全景重建与 “蒸馏攻击” 的技术底层解构
--------------------------

要准确评估 Anthropic 指控的物理事实及其技术危害，必须首先从计算机科学的底层逻辑出发，厘清 “模型蒸馏” 这一概念的技术边界，并深入解析此次事件中暴露的工业级攻击手法。

![](https://images.weserv.nl/?url=https%3A//pica.zhimg.com/v2-2e64e0c63ada280da699db3f9493191e_r.jpg%3Fsource%3D1def8aca)

### 知识蒸馏的技术演进与行业应用边界

在人工智能及深度学习领域，知识蒸馏（Knowledge Distillation）是一项高度成熟且被广泛采用的模型训练技术。其核心工程原理是利用一个参数规模庞大、泛化性能卓越的 “教师模型”（Teacher Model）所生成的丰富输出——包括逻辑推理的思维链（Chain-of-Thought）、分类任务中的软标签概率分布（Soft labels）以及复杂的编程解题路径——来指导一个参数规模较小、运行资源需求更低的 “学生模型”（Student Model）进行定向训练 1。在合规的商业实践中，前沿 AI 实验室均会常规性地运用蒸馏技术对其旗舰模型进行降维优化，以推出更具成本效益、推理延迟更低的轻量化版本供边缘设备或大规模并发商业场景使用 2。

然而，随着大语言模型时代的到来，知识蒸馏的应用场景发生了异化。当蒸馏的对象从企业 “内部的专有模型” 转向 “竞争对手的高性能商业模型” 时，其性质便从合法的技术优化演变为极具争议的技术套利。在 Anthropic 所描述的 “非法蒸馏” 或“蒸馏攻击”中，攻击方并不直接接触目标模型的底层代码或权重参数，而是通过构造海量且经过精心设计的提示词（Prompts），系统性地探测并激发目标模型在特定垂直领域（如高级数学推理、复杂代码重构、多模态视觉解析）的极限能力 7。攻击者捕获这些由顶尖模型生成的高质量问答对（Input-output pairs），并将其聚合为高密度的合成数据集（Synthetic datasets），随后直接将这些数据注入到自身基础模型的微调（Fine-tuning）或人类反馈强化学习（RLHF/RLAIF）阶段 13。这一手法使得追赶者在无需承担庞大试错成本、无需组建数千人规模的顶尖数据标注团队，且大幅降低基础预训练（Pre-training）算力开销的情况下，能够快速复现领先模型的核心能力特征 13。

### [Hydra 集群](https://zhida.zhihu.com/search?content_id=770657113&content_type=Answer&match_order=1&q=Hydra%E9%9B%86%E7%BE%A4&zhida_source=entity)架构：工业级 API 窃取的隐匿网络

鉴于 Anthropic 出于国家安全与出口合规考量，明确未向中国大陆地区提供 Claude 的商业 API 访问权限，且严禁其模型被用于训练直接竞争的 AI 产品 1，此次被指控的中国实验室如果实施了高达 1600 万次的查询，必然依赖于极度复杂的中介系统。技术追踪与溯源分析表明，这些高频交互高度依赖于一种被称为 “Hydra 集群”（Hydra cluster architectures）的商业级地下代理网络 7。

Hydra 集群架构的核心优势在于其多头并发、高容错性、极强的隐蔽性以及跨平台的资源调度能力。在传统的计算机科学架构中，Hydra 原本被设计用于在异构的商业云环境（如 AWS、Azure）与高性能计算（HPC）节点之间进行大规模任务的通用代理调度，其内置的服务代理（Service Proxy）模块能够协调 CaaS 管理器（容器即服务）和 HPC 管理器，实现海量并发任务的动态映射 17。然而，在针对 AI API 的蒸馏攻击场景中，这一架构被武器化。

攻击者利用 Hydra 架构建立了一个庞大的分布式网络，管理着数以万计的虚假用户凭证与 API 密钥。为了规避 Anthropic 部署的基于规则的速率限制（Rate-limiting）、滥用检测引擎以及行为指纹识别（Behavioral fingerprinting），Hydra 集群采用了高度精密的流量混淆策略 16。具体而言，该网络将高密度的、用于提取思维链推理的探测性查询，巧妙地伪装并混合在海量的日常常规对话、无害的文本翻译等合法交互流量之中；同时，利用全球地理 IP 池不断进行请求源的动态路由与轮换 7。正如其 “九头蛇” 的命名隐喻，这种架构没有单一的故障点：即便 Anthropic 的安全团队成功识别并封禁了某一集群节点或数千个滥用账户，Hydra 的资源管理器也会在毫秒级延迟内自动调配并激活成千上万个新的替补账户，确保持续的数据提取任务不被打断 14。

### 针对性数据提取：三大头部实验室的攻击特征归因

Anthropic 在其详细调查中，通过深度分析 API 请求的底层元数据（Request metadata）、网络基础设施指标（Infrastructure indicators）、IP 地址重合度，以及比对中国各实验室开源或商业模型发布的关键时间节点，对 1600 万次非法交互进行了明确的归因画像 2。证据链表明，这些交互绝非盲目的互联网数据爬取，而是具有极强目标导向的系统级能力提取，三家涉事企业的技术路径与提取重点呈现出显著的差异化特征。

下表详细梳理了被指控的三家中国 AI 实验室在 “蒸馏攻击” 中的具体行为模式与资源倾斜方向：

<table data-draft-node="block" data-draft-type="table" data-size="normal" data-row-style="normal"><tbody><tr><td>涉事 AI 实验室</td><td>预估欺诈账户数与交互量</td><td>核心目标提取领域与技术特征溯源</td></tr><tr><td>MiniMax</td><td>占据主导份额（交互超 1300 万次）</td><td>发起了规模最为庞大的工业级行动。高度集中于提取编程代码生成能力、智能体推理（Agentic reasoning）、工具调用规划及复杂系统编排。技术追踪显示其团队表现出极高的战术敏捷性：在 Anthropic 发布新版 Claude 模型的 24 小时窗口内，MiniMax 能够迅速更改其请求分发路由，将近半数的 Hydra 集群流量重定向，以抢先捕获并固化最新系统的增量能力 2。</td></tr><tr><td>Moonshot AI (月之暗面)</td><td>跨越超 340 万次交互</td><td>侧重于补齐自身 Kimi 大模型在跨模态及复杂工作流中的短板。核心目标指向计算机视觉解析（Computer vision）、高级代码与数据分析、智能体决策逻辑，特别是计算机使用代理（Computer-use agent）的前沿开发范式。这与其在长文本之外寻求系统协调能力突破的商业路线高度吻合 8。</td></tr><tr><td>DeepSeek (深度求索)</td><td>超过 15 万次高频交互</td><td>交互量相对较少，但针对性极强。重点剥离 Claude 的深层逻辑推理链、基于量规的自动化评分任务（Rubric-based grading）。值得注意的是，调查显示 DeepSeek 试图利用 Claude 生成一系列能够规避政治审查的合规安全替代文本，专门针对关于异见人士、专制主义等政策敏感议题，借此构建对齐（Alignment）阶段的审查安全防护盾 8。</td></tr></tbody></table>

**初步定性评估**：从计算机网络攻防与数字法证的实证角度来看，Anthropic 提供的涵盖元数据关联、代理 IP 清洗机制与模型迭代时间戳匹配的证据链，具有相当高的技术自洽性与可信度 2。在全球大模型产业的发展初期，后发企业在强化学习（RL）阶段为了解决冷启动数据匮乏和对齐奖励模型（Reward Model）不稳定的问题，广泛采用调用海外旗舰模型 API 来构建合成数据（Synthetic Data）或获取对齐反馈（RLAIF）的策略，这几乎是一个公开的行业秘密 21。因此，关于 “中国企业通过代理渠道向 Claude 发起了 1600 万次查询用于优化自身模型” 这一物理事实，其属实的概率极高。然而，将这种通过公开接口购买服务并运用行业标准蒸馏技术的行为，在公关层面定性为 “偷走模型灵魂” 的知识产权盗窃，则明显超出了纯技术的讨论范畴，带有强烈的商业排他性目的与地缘政治修辞色彩。

第二章：实证检验与反向推演：中国 AI 是否真正遭遇了 “卡脖子”？
----------------------------------

面对接踵而至的硅谷 “实锤抄袭” 舆论风暴，国内外业界及投资市场普遍产生了一种深度的战略焦虑：中国 AI 大模型近年来的惊艳表现，是否仅仅是一层经过巧妙蒸馏的 “硅谷倒影”？如果外部的 API 访问被彻底切断，所谓的“Hydra 集群” 失效，中国 AI 产业的研发是否将陷入彻底的停滞？中国在通用人工智能领域的竞争是否面临被直接 “卡死” 的危机？

要客观回答这一关乎国家科技命运的问题，不能仅凭技术厂商的互相攻讦，而必须引入中立的技术基准测试（Benchmarks）与专业机构的系统级实证评估，来检验中国头部大模型的真实能力底色。

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-920d018e0ed2d60bf848fd5d1d9981f7_r.jpg%3Fsource%3D1def8aca)

### 实证对比：DeepSeek V3.1 与 Claude 4 Opus 的性能对决

以此次处于风口浪尖且备受全球瞩目的 DeepSeek 为例，其在 2025 年下半年及 2026 年初连续发布的多个开源及推理模型版本，已经通过硬核的代码与数学成绩，从侧面强有力地证伪了 “中国 AI 纯粹依靠抄袭和简单蒸馏维持” 的武断结论。如果仅仅是浅层的知识蒸馏，学生模型的性能存在一个无法逾越的理论上限——即永远无法在复杂逻辑上超越教师模型。然而，现实数据给出了截然不同的答案。

根据多项独立的人工智能评估平台（如 Artificial Analysis）在 2025 年至 2026 年间发布的权威基准测试数据，DeepSeek V3.1（一款支持高达 12.8 万上下文长度、拥有 685B 参数的创新混合推理模型）在多个关键工程维度上，不仅成功实现了对 Anthropic 旗舰级非推理模型 Claude 4 Opus 的全面追赶，更在部分高壁垒领域完成了实质性的反超 22。

下表直观地展示了这两款代表中美顶尖水平模型在核心维度的详细对比：

<table data-draft-node="block" data-draft-type="table" data-size="normal" data-row-style="normal"><tbody><tr><td>评估核心维度</td><td>DeepSeek V3.1 (Reasoning 版本)</td><td>Claude 4 Opus (Non-reasoning 版本)</td><td>实证对比分析与战略优势评估</td></tr><tr><td>高阶编程与软件工程 (SWE Bench)</td><td>达到 71.6% 的基准解决率</td><td>达到 70.6% 的基准解决率</td><td>在要求极高逻辑连贯性的软件工程修复与生成任务中，DeepSeek 确立了微弱但关键的领先优势。这一数据直接粉碎了 Anthropic 关于其在代码领域保持绝对统治力的神话，表明中国模型在深度逻辑重构上已具备内生创新力 22。</td></tr><tr><td>底层架构与技术生态开放性</td><td>完全开源模型权重 (Open Weights)</td><td>采取闭源专有策略 (Proprietary)</td><td>DeepSeek 通过在 Hugging Face 等平台彻底开源其基础模型，大幅降低了全球开发者的二次开发门槛，主导了开源生态；而 Claude 则坚持通过封闭 API 墙进行商业变现以维持垄断利润 23。</td></tr><tr><td>商业 API 调用成本效益 (每百万 Token)</td><td>输入成本: 0.15 / 输出成本: 0.75</td><td>输入成本: 15.00 / 输出成本: 75.00</td><td>这是最具震撼性的差异。DeepSeek 的端到端运行成本仅为 Claude Opus 的约 1/100（或在部分架构下为 1/68）。这证明了中国企业在 MoE（混合专家模型）架构优化、稀疏注意力机制（Sparse Attention）创新以及底层算力成本极致压榨方面，拥有硅谷无可比拟的工程优势 22。</td></tr><tr><td>跨模态特征支持度</td><td>当前暂不支持原生图像输入解析</td><td>支持高级图像与视觉输入分析</td><td>这是目前中国模型显著的短板。Claude 在视觉特征提取与多模态数据融合对齐方面依然保持着明显的技术领先与成熟度 23。</td></tr></tbody></table>

### 美国官方技术评估定性：[NIST CAISI](https://zhida.zhihu.com/search?content_id=770657113&content_type=Answer&match_order=1&q=NIST+CAISI&zhida_source=entity) 的全面审计

为了更客观地理解中国模型的真实水平，我们应当审视美国国家标准与技术研究院（NIST）下设的 CAISI（人工智能安全研究所）于 2025 年 9 月出具的一份极具内部参考价值的评估报告。该报告对 DeepSeek 系列（R1、R1-0528、V3.1）与美国基准模型（包括 [GPT-5](https://zhida.zhihu.com/search?content_id=770657113&content_type=Answer&match_order=1&q=GPT-5&zhida_source=entity) 和 Claude Opus 4）进行了多达 19 个基准的独立对抗性测试 27。

CAISI 的评估揭示了中国 AI 发展极为复杂且充满矛盾的双面性。报告确认，在最高端的绝对性能阈值上，DeepSeek V3.1 在网络安全漏洞挖掘等极端边缘任务中，依然落后于 GPT-5 等美国最好模型 20% 至 80%；同时，中国模型在安全对齐（Alignment）方面表现出极高的脆弱性，其最安全的版本对常见越狱攻击（Jailbreaking attacks）的服从率高达 94%，而美国参照模型的服从率仅为 8%，且 DeepSeek 极易被恶意智能体指令劫持（Agent hijacking attacks），甚至频繁生成附和特定政治意识形态的叙事 27。

然而，正是同一份报告也发出了严厉的警告：尽管存在这些缺陷，DeepSeek 模型在保持与美国顶尖模型相近的日常任务处理水平的同时，其应用成本比美国最具竞争力的参照模型还要低出整整 35% 27。这一发现深刻揭示了中国大模型产业的真实状态。

综合海量实证分析可以推导出本报告的第一个核心定论：**中国 AI 产业并未被实质性 “卡死”，其核心研发链条依然保持着强劲的运转惯性。** 诸如 DeepSeek、MiniMax 等中国实验室在早期研发阶段，为了解决冷启动数据匮乏的难题，确实在特定技术环节（如 RLAIF 对齐机制）利用 “蒸馏技术” 摄取过 Claude 或 GPT 的高质量 “思维链” 输出 21。但这本质上属于一种 “利用西方先进工具加速自身能力收敛” 的战术捷径，而非其全部的技术基石。时至今日，中国本土模型在底层架构创新（例如自主研发的 DeepSeek Sparse Attention 高效注意力机制、创新的奖励强化学习框架等）以及工程部署效率上的突破，已经使其具备了强大的内生自迭代能力 28。大模型能力的最终成型，是底层芯片算力调度、海量清洗数据投喂与无尽的试错工程共同熔铸的结晶，绝非仅仅依靠部署 Hydra 集群 “复制粘贴” 几百万次 API 输出就能凭空创造的。

第三章：法律博弈与商业伦理：知识产权盗窃还是服务条款违约？
-----------------------------

随着技术的演进，Anthropic 对中国实验室的指控迅速跨越了单纯的技术探讨边界，引爆了关于人工智能时代知识产权（Intellectual Property, IP）保护边界以及全球数据管辖权的深层次法律争议。这种通过 API 层级大规模获取模型合成输出，并将其无缝用于二次模型训练的工业化行为，究竟在现行司法体系下构成何种意义上的违法？

### 传统知识产权保护的立法真空

在严格的现代知识产权法理框架下，Anthropic 试图将此次事件包装为 “工业级知识产权盗窃”（Industrial-scale IP Theft）的主张，面临着难以逾越的法理障碍与制度真空 4。

首先，从**版权法（Copyright Law）**的适用性来看，全球大多数主流司法管辖区（特别是美国联邦版权局的系列既有裁定与政策声明）中，存在一个基础性的共识：受版权保护的作品必须具备实质性的 “人类作者身份”（Human authorship） 29。由于 Claude 模型所生成的推理步骤、代码片段或问答文本，本质上是由复杂的神经网络算法依据概率分布自动计算生成的非人工创作内容，因此，Anthropic 在法理上几乎不可能主张 DeepSeek 或 MiniMax 侵犯了其“模型输出文本” 的版权，因为这些文本本身就不享有版权保护 29。

其次，从**专利法（Patent Law）**的防御逻辑来看，专利制度通常旨在保护大模型底层的创新架构设计（如特定的注意力机制变体）、参数配置方式或具象化的工程优化方案 30。而在整个蒸馏攻击过程中，中国企业完全被隔离在 API 防火墙之外，并未非法访问或反编译 Claude 的底层代码和模型权重。因此，试图通过专利侵权来规制对 API 接口的黑盒探测行为，在司法实践中显得极为苍白无力 30。

最后，关于**商业机密（Trade Secrets）**法理的辩论成为了学术界与法律界交锋的焦点。商业机密的保护前置条件在于企业必须对核心信息采取了合理且有效的物理及技术保密措施。毫无疑问，Claude 的内部模型权重、精确的网络结构参数以及构建模型所使用的专有清洗数据集，属于绝对的商业机密。但是，模型一旦向公众开放 API 接口，其生成的输出内容便不可逆转地脱离了绝对保密的范畴 32。在传统的计算机软件工程领域，通过 “逆向工程”（Reverse engineering）手段探查公开运行产品的输入输出映射边界，只要不涉及破坏系统底层加密机制的黑客入侵行为，通常不被视为侵犯商业机密 33。然而，模型蒸馏带来了一种新型的法理悖论：工业级蒸馏利用数以百万计的针对性提示词探测，其实质上并非在研究单一产品的表象，而是利用大语言模型的统计特性，在极高维度上重构、拟合目标模型隐藏的决策边界与隐性知识体系 7。这种行为是否应当被扩大解释为一种新型的、利用不正当手段获取商业机密的行为（Improper acquisition），目前在各国的成文法与判例法中均尚无明确的定论，法律专家对此分歧严重 29。

### 服务条款（ToS）违约的跨国司法执行困境

在传统知识产权法域普遍受阻的背景下，Anthropic 手中最为坚实的法律防御武器实际上是合同法框架下的**服务条款违约责任（Breach of Contract）**。

在生成式 AI 产业界，几乎所有提供高端模型 API 访问权限的企业（包括 OpenAI、Google 及 Anthropic），均在其冗长且复杂的最终用户许可协议（[EULA](https://zhida.zhihu.com/search?content_id=770657113&content_type=Answer&match_order=1&q=EULA&zhida_source=entity)）及服务条款（ToS）中明确嵌入了一条排他性禁止条款：严禁任何实体或个人利用该模型的生成输出（Outputs），去开发、训练、微调或蒸馏任何与提供方构成直接商业竞争关系的生成式人工智能模型 1。中国实验室利用 Hydra 集群构建虚假账户阵列，不仅刻意隐藏真实 IP 以绕过地域服务禁令，更将海量获取的数据直接注入竞争产品的训练流程，这在事实层面上构成了对 Anthropic 服务条款的极其严重的、系统性的蓄意违约 1。

然而，违约责任本质上属于私法领域的民事纠纷。对于总部位于旧金山的科技企业而言，试图在当前缺乏基础互信的跨国司法协作体系下，将一家总部位于中国北京或杭州的 AI 初创公司诉至美国法庭，并要求其承担天文数字的违约赔偿或签发全球性的停止侵权禁令，其实际的司法执行难度无异于天方夜谭 3。正因如此，Anthropic 所能采取的实质性反制措施，仅仅局限于强化技术防守（如升级行为指纹检测模型、进行 IP 封锁与账户清理），而无法通过法律途径彻底斩断这种渗透 3。

### 行业 “双重标准” 与马斯克的 “虚伪论” 反击战

除了冰冷的法律条款争议，Anthropic 指控中所蕴含的商业伦理与道德高地，同样遭到了全球科技圈的猛烈狙击。这场争议暴露了硅谷巨头在构建 AI 帝国时的深层矛盾与 “双重标准”。

事件爆发后，包括特斯拉与 xAI 创始人埃隆 · 马斯克（Elon Musk）在内的多位硅谷资深工程师及中国科技圈领袖，在社交平台上公开发起了对 Anthropic 的无情嘲讽与反制裁指控 10。批评者直击 Anthropic 的阿喀琉斯之踵：以 Anthropic 为首的领先 AI 企业在训练其初代及各代 Claude 大模型时，所依赖的那些堪称 “人类智慧结晶” 的海量底层数据，其本身绝大部分就是未经原始创作者（包括作家、新闻机构、画师及数以千万计的开源软件程序员）明确授权，通过爬虫程序从广袤的互联网空间中大规模、无差别进行非法抓取（Scraping）并 “蒸馏” 而来的 3。

在批评者看来，Anthropic 面临着不可调和的逻辑自洽危机：正如软件工程师 Gergely Orosz 所指出的：“Anthropic 不能两头占便宜。别忘了 Claude 是怎么训练出来的：用了受版权保护的书籍，直到面临诉讼压力后才开始与版权方探讨补偿。” 11 马斯克更是犀利地点评道：“Anthropic 犯有大规模窃取全人类训练数据的原罪，并且已经为此付出了数十亿美元的和解代价。现在，他们怎么敢道貌岸然地指责别人在‘偷’他们原本就是从人类那里偷来的东西？” 11

这种强烈的 “只许州官放火，不许百姓点灯” 的伪善标签（Hypocrisy），深刻揭示了处于 AI 赛道前沿的领先者试图利用规则和伦理高地来固化其垄断护城河的战略意图 11。在 AI 产业那段蛮荒生长的扩张期，数据的无偿掠夺被包装成技术进步的必然代价；而一旦巨头们凭借这些无偿数据建立了足以睥睨群雄的模型壁垒后，他们便迅速转变立场，强烈要求国际社会用最严苛的法律与政治手段，去锁死这扇曾经让他们自己大获其利的后发演进之门。

第四章：泛安全化叙事与中美地缘科技博弈的核爆点
-----------------------

通过将一场原本应当通过技术博弈与民事诉讼解决的商业版权与 ToS 违规纠纷，高调包装为一份涉及 “工业级窃密” 的官方调查报告，Anthropic 的真实意图已经远远超出了单纯的商业维权范畴。这家公司敏锐地捕捉到了当前华盛顿的政治风向，成功地将商业指控上升、升级为涉及美国 “国家安全（National Security）” 的宏大叙事 2。这标志着全球 AI 模型层面的竞争，已正式沦为中美地缘科技战与大国战略博弈的核心爆炸点。

### “护栏剥离” 效应与灾难性网络安全威胁论的塑造

为了论证这种 “技术外流” 并非普通的商业损失，Anthropic 在其报告的核心部分浓墨重彩地渲染了所谓“护栏剥离”（Guardrail Stripping）的恐怖前景。报告警告美国国家安全委员会及相关政策制定机构，被中国实验室非法蒸馏并带离美国本土管控的 AI 大模型，极有可能不再保留原有美国顶尖模型中硬编码植入的那些复杂的伦理边界与安全“护栏”（Safety guardrails） 1。这些护栏在设计之初，旨在利用对齐技术防止生成式 AI 被流氓国家或恐怖组织用于协助设计高度危险的生物化学武器、合成爆炸物，或生成能够突破现代网络防御的恶意攻击代码 4。

Anthropic 耸人听闻地预测，一旦专制政权的军方情报机构或政府支持的高级持续性威胁（APT）组织获取了这些彻底脱离安全束缚的前沿 AI 能力，并将其集成到国家级的军事情报或监控网络中，必将引发一场不可控的灾难：包括系统性的进攻性网络行动（Offensive cyber operations）、难以溯源的大规模虚假信息操纵运动（Disinformation campaigns）以及针对异见人士的无死角数字监控网络 2。

配合这一惊悚的政治叙事，Palo Alto Networks 等网络安全巨头的近期研究也适时地引发了共鸣。研究表明，AI 智能体本身正面临着新型且致命的攻击向量，例如针对 MongoDB 系统的 MongoBleed 漏洞（CVE-2025-14847），以及当智能体接入 A2A（Agent-to-Agent）系统时可能被诱发的灾难性的 “智能体代理会话走私攻击”（Agent Session Smuggling Attack） 39。更为巧合且具有实证意义的是，在发布该指控报告的不久前，Anthropic 官方联合美国太平洋西北国家实验室（PNNL），成功主导了一次具有里程碑意义的红蓝对抗演练。在这次实验中，PNNL 的研究人员利用特殊配置（解除部分限制）的 Claude 模型作为自主网络武器载体，将其接入一个高保真的现代水处理厂网络控制系统物理沙盒。结果令人震惊：Claude 不仅能够在极短的时间内自动生成渗透测试链，还成功模拟并复现了试图接管水厂关键基础设施控制权的复杂网络攻击，且其执行效率远超顶尖的人类黑客专家 40。Anthropic 借此向白宫及五角大楼传递了一个不容置疑的信号：AI 模型早已不仅是生成诗歌和撰写代码的玩具，它已经进化为具备真实世界物理系统破坏潜力的战略武器库；而放任这把双刃剑的剑刃通过“蒸馏技术” 流向战略竞争对手中国，无异于坐视美国国家安全体系的崩溃 40。

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-f8531ce5cf9620662a6758bdea1c04e8_r.jpg%3Fsource%3D1def8aca)

### 算力封锁与政策游说：倒逼美国出口管制的加码

如果说渲染安全威胁是铺垫，那么 Anthropic 高调发声的终极战略目的，则是为其背后的政策游说（Lobbying）议程铺平道路，力图阻断中国 AI 获取底层发展动力的路径。Anthropic 在报告中明确指出，近期令西方瞩目的中国 AI 实验室（如 DeepSeek、Moonshot 等）的飞速崛起及其所展现出的低成本高性能优势，在很大程度上被外界误读为美国当前实施的技术出口管制政策已经彻底失效 7。Anthropic 试图向美国国会与白宫证明：中国大模型所谓的 “奇迹”，并未建立在其真正突破了底层物理创新的基石之上，而是高度依赖对美国现存开源生态及顶尖闭源模型接口的隐蔽吸血与系统性蒸馏提取 7。因此，这绝不能成为美国放松出口管制的理由；恰恰相反，这充分证明了必须在硬件根基上——即最先进的人工智能处理芯片——进行更加冷酷无情的战略 “断供”，才能彻底掐断中国企业维持这种庞大分布式蒸馏计算能力与模型长期迭代的物质基础 7。

这种政策游说恰逢美国联邦政府权力交接及政策重新校准的动荡期。2025 年至 2026 年间，美国商务部及白宫围绕对华科技遏制战略进行了一系列令人眼花缭乱的政策博弈。最初，拜登政府在 2025 年 1 月试图通过一项极为严苛的 “人工智能扩散规则”（AI Diffusion Rule），从软件模型源代码到硬件芯片实施全球性的一刀切封堵 43。然而，这一过度宽泛的规则引发了美国国内科技界及欧洲盟友对其可能扼杀创新生态的强烈反弹。随后，新上任的特朗普政府在 2025 年 5 月以“保护美国 AI 主导地位免受反噬” 为由，果断废除了这一扩散规则 46。

但在废除软件模型出口限制的同时，美国商务部工业与安全局（BIS）却将大棒更加精准地砸向了底层的半导体硬件算力枢纽。BIS 出台了一系列极具针对性的指导意见，严厉警告全球供应链中的美国及非美国实体，如果其使用或者配合中国本土研发的高级计算集成电路（特别是被明确点名的华为昇腾 Ascend 910B/910C/910D 系列芯片）进行大规模计算操作，将面临触犯 “通用禁令 10”（General Prohibition 10）遭受毁灭性制裁的巨大风险 43。与此同时，尽管特朗普总统曾在 2025 年 8 月一度放出可能允许向中国出售性能经过阉割的英伟达 Blackwell 架构降级版芯片的缓和风声，但在国内对华强硬派（China hawks）以及国家安全情报部门的巨大政治施压下，他迅速改变了立场，并在 2026 年初重申，代表美国半导体最高工业结晶的最先进芯片必须绝对保留在美国主导的技术供应链体系内，禁止流向中国 42。特朗普政府新近提名的美国网络司令部及国家安全局高级将领 Joshua Rudd 更是直言不讳地作证指出，中国正不惜一切代价、极其激进地寻求获取美国的先进 AI 芯片，以加速其由人工智能增强的下一代自动化武器系统的研发进程，这构成了美国国防安全不可容忍的现实漏洞 50。

在这股强烈的地缘政治对冲中，Anthropic 所提交的 “1600 万次非法提取” 证据链，无疑为华盛顿鹰派主张维持乃至进一步升级对华半导体 “卡脖子” 封锁战略，提供了最完美的炮弹与最无懈可击的伦理借口 51。对于中国企业而言，这场危机意味着，不论是试图通过第三方国家的空壳公司走私进口先进的 H200 或 Blackwell 集群，还是企图通过 “Hydra 代理网络” 曲线救国、低成本获取硅谷模型的 API 增量能力，这两条过去赖以生存的灰色通道，正遭遇着美国政府从海关物理截获到硅谷算法反制的全链条、无死角封杀。

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-30a28769e66b7dc8621b9792db0ba1a1_r.jpg%3Fsource%3D1def8aca)

第五章：破茧重生的阵痛：中国人工智能产业的战略突围与重构路线图
-------------------------------

随着大洋彼岸硅谷巨头联合美国政策制定者筑起的防御高墙越垒越高，中国大模型产业曾经试图依赖 “拿来主义”、“拥抱海外开源” 抑或是通过隐蔽渠道 “蒸馏套利” 的早期粗放型发展范式，已经被时代的车轮彻底碾碎。但这绝不意味着中国 AI 产业将就此在 “卡脖子” 的困境中窒息而亡。正如基准测试所揭示的内生能力，中国 AI 已经越过了最艰难的冷启动期。面对不可逆转的 “中美技术脱钩与双生态平行发展” 的新纪元，中国 AI 企业与宏观政策制定者必须在算力基础设施重组、数据资产内生化供给以及国际合规法律防御三大核心维度上，进行一次彻底的体系级重构。

### 一、 算力底座的绝地突围：从单点依赖迈向 “算电协同” 与集群跃升

美国通过将英伟达高端 GPU 武器化，长期试图死死压制中国 AI 算力能够触及的理论天花板 42。应对这种物理层面的算力窒息战，中国正依托强大的国家宏观统筹能力与大型科技企业的工程创新能力，展开双轮驱动式的破局。

1.  **超大规模集群互联与异构算力的自主可控突破** 面对单颗国产计算芯片在绝对算力性能上依然与英伟达顶尖产品存在代差的冷酷现实，破局的唯一出路在于系统工程学的 “大力出奇迹”——即通过指数级扩大计算集群的规模（Cluster scale-up）来弥补单点性能的不足。中国头部科技企业正在疯狂推进超大规模智算集群的建设。例如，百度早在 2011 年便开始布局的昆仑芯（Kunlunxin）生态，在近期推出了旨在将单一智算中心集群规模从 3 万卡直接跨越至百万卡级别（Million-GPU scale）的“天池超节点” 架构 53。为了支撑这种前所未有的集群规模，中国硬件企业被迫在超高速通信总线技术、专用集成电路（ASIC）定制设计以及存算一体化新架构上展开了绝地反击 53。更为关键的是，为了彻底摆脱对 CUDA 生态的单一依赖，国内正倾注全力打造能够无缝兼容、混编调度多种国产异构芯片（涵盖昇腾、昆仑芯、海光、燧原等）的底层统一计算软件平台，力求通过软硬件协同生态的冗余设计，对冲单一芯片供应链断裂的致命风险 53。
2.  **国家 “东数西算” 深化演进与跨界 “算电协同” 战略** 人工智能大模型的训练与推理，在物理本质上是对大规模电能的深度转化。算力的竞争，最终将演变为能源供给效率的竞争。根据中国信通院等权威智库发布的报告警告，随着多模态大模型的爆炸式应用，到 2030 年底，中国全国数据中心的用电量预计将突破惊人的 4000 亿至 7000 亿千瓦时，占到全社会总用电量的 3% 以上 53。“算力的尽头是电力”这一行业论断，正迫使中国从国家战略层面推动数据网络与能源网络的深度交织。中国正在加快引导那些对网络传输时延要求不高的核心大模型预训练任务（Cold-data processing and pre-training），向风电、光伏等可再生能源极度富集的西部干旱及高寒地区集中布局，打造绝对绿色的超大规模算力基地 53。领先企业如腾讯等，已在其核心数据中心实现了高达 80% 的绿色电力直供比例 53。未来的 AI 霸权，将不仅仅取决于芯片的纳米制程，更将取决于能否通过光纤网络技术的极限时延优化、业务负载的 AI 智能动态调度，以及数据中心大功率负载与国家大电网储能体系之间的灵活性互动，从而在全球范围内实现 “算力运行总体社会综合成本最优化” 的超前能力 53。

### 二、 数据要素生态的内生化重构：彻底斩断对海外模型的 “蒸馏依赖”

Anthropic 指控事件尽管在法理上存在争议，但却无情地扒下了中国 AI 在发展初期的一个脆弱软肋：在某些要求极高逻辑连贯性的垂直领域，中国模型仍然不同程度地患有对 “高质量海外生成语料” 的路径依赖症。放眼 2026 年及更加深远的未来，全球大语言模型的竞争焦点已经从单纯比拼神经网络参数的粗放规模，无可避免地转移到了高密度、强逻辑结构化以及行业独有私域数据资源的系统化供给能力上。如果无法实现高质量数据的自给自足，中国 AI 即便拥有了庞大的算力，也将成为一具空转的“无米之炊”。

1.  **从国家顶层设计推动数据交易库与语料基础设施建设** 面对海外优质数据源可能被彻底物理切断、版权诉讼高悬的极端风险，中国政府展现出了极强的战略预见性。2026 年伊始，中国国家数据局（National Data Administration）联合工业和信息化部、公安部等多个强力部委，密集出台了超过 30 项涉及公共数据管理、人工智能高质量数据集建设以及数字基础设施重构的新规 54。这标志着中国已正式将培育合规、高效的人工智能数据集交易市场上升为不可动摇的国家基础战略 55。中国正加速动员全社会力量，打破信息孤岛，深度整合涵盖国内教育系统、数以千万计的医疗诊疗记录、全球最完备的制造业工艺流程以及国家级科研平台的巨量公共与非标专有数据，致力于建立一套拥有绝对自主产权、高度标准化且完全可信赖的 “国家大模型基础语料库” 56。同时，为了激活沉睡在传统产业链中的数据价值，上海、珠海等经济发达地区已率先试水向中小微科技企业定向发放巨额“算力券” 与“数据券”，以资金补贴为杠杆，引导工业制造、农业以及航天等实体经济领域深度参与精细化数据清洗与标注作业，从而在本土培育出一个带有鲜明中国文化底色与深厚垂直行业 Know-how（知识积淀）的自循环数据飞轮体系 53。
2.  **拥抱合成数据（Synthetic Data）与多智能体自我演进的下一代范式** 为了在算法底层的源头彻底戒断对 Claude、GPT 等海外竞争对手模型的 “蒸馏依赖综合征”，中国 AI 学术界与产业界必须，且正在倾注全力抢占下一代 AI 模型训练范式的制高点——即基于严密数理逻辑验证的合成数据大规模生成引擎。大模型的发展正经历从“被动接受人类互联网废料或海外 AI 数据灌输” 向“基于物理规律主动自我探索与演进”的历史性跃迁 57。通过部署多智能体协作框架（Multi-agent orchestration），让多个搭载不同功能专长的 AI 在封闭的虚拟沙盒环境中进行高频度的自我对弈、交叉诘问与逻辑自洽性验证。系统能够自动剔除逻辑矛盾的死链，进而自主发现并生成符合客观规律的全新高质量训练集。例如前沿研究所展示的 AlphaEvolve 范式，为中国 AI 彻底斩断侵权数据输入风险、实现能力自主破局提供了一缕充满希望的破晓之光 57。

### 三、 国际合规护城河与主动防御法律体系的立体构建

随着 “出海战略” 已经从可选项变为中国生成式 AI 企业维持商业估值和技术迭代资金流的唯一必选项，这些企业在全球各个司法管辖区所面临的国际法律审查、反垄断诉讼以及知识产权 “长臂管辖” 风险，正在呈指数级的恶化态势。此次 Anthropic 借由 ToS 违规发难，无疑是对中国 AI 粗放式合规体系敲响的一记极为严厉的警钟。中国企业不能再以 “野蛮生长” 作为借口，必须用国际最严苛的法律标准武装自己。

1.  **被动合规向主动防御转型：应对新修订《网络安全法》与全链条安全标准** 与此同时，中国国内面临的监管环境同样在 2026 年迎来了翻天覆地的质变。2026 年 1 月 1 日，经历了漫长且充分酝酿修订的全新中国《网络安全法》（CSL）正式落地实施。新版法律以雷霆万钧之势，确立了针对各类数据泄露事件与人工智能模型安全防护违规行为的极刑处罚机制，对涉事关键企业的最高罚款金额被猛烈提升至其上一财年总营业额的 5% 或者人民币 5000 万元（对于责任个人的罚金亦可达 100 万元） 54。在此高压震慑之下，中国 AI 企业必须立即放弃侥幸心理，将合规审查前置。不仅要在搜集训练原始数据时进行极为严苛的知识产权清洗与价值观对齐（绝对避免违规抓取受保护内容或生成严重偏离核心价值观的叙事） 61，更必须毫无折扣地依据最新发布的强制性国家级技术规范体系（如《GB/T 45654—2025 Cybersecurity Technology – Basic security requirements for generative artificial intelligence service》以及涵盖数据标注、预训练数据安全等全生命周期的系列标准），建立一套端到端的、带有防篡改追溯日志的安全控制流程与模型护栏机制 61。
2.  **构筑系统化的跨国 IP 防御矩阵与跨境数据流动的合规安全气闸** 面对可能如海啸般涌来的海外 “知识产权窃取” 系统性集体诉讼风险，中国 AI 企业必须迅速行动，在公司内部启动针对各类隐蔽“影子 AI”（Shadow AI，即员工私自绕过合规监管调用未授权外部大模型 API 的行为）的深度排查清点风暴 62。在所有雇佣合同及第三方算力或数据供应商协议中，必须使用无懈可击的法律条款明确界定责任归属，将由于侵权数据注入或自动化输出错误所引发的巨额赔偿风险，严密封锁在特定供应商环节内侧 62。针对企业在自主研发算子、模型权重压缩机制以及创新训练工作流中所取得的那些难以套用传统软件著作权保护的技术结晶，企业应当积极聘用顶级跨国专利律师团队，在美、欧、日等核心科技市场抢先部署防御性的专利权矩阵（Patent Matrix），巧妙地将模型训练的特殊工艺流程固化为受属地法律承认并受法律保护的技术发明，以此为未来可能爆发的极其惨烈的跨国知识产权摩擦囤积宝贵的交叉授权谈判筹码 31。 更为关键的是，鉴于中国国家互联网信息办公室（CAC）已出台更为清晰、严厉的个人信息及敏感数据出境认证与安全评估细则，中国 AI 出海企业在试图利用低成本海外节点进行推理加速，或者通过错综复杂的商业代理网络访问受限资源的极度敏感操作中，必须配置专职法务团队，严格、完整地履行并满足数据跨境流通的法定评估审批与报备程序，绝不能因追求一时的工程便捷而在程序合规上留下任何足以致命的瑕疵漏洞，授人以随时可以发动长臂管辖制裁的口实把柄 54。

写在最后
----

Anthropic 通过精心发布一份以 1600 万次后台高频交互日志为佐证的深度安全调查报告，极其成功地将中国三大顶级生成式 AI 实验室的技术捷径探路行为，置于了国际社会最严厉的聚光灯下进行烤打。从计算机网络工程的底层物理逻辑进行冷静剖析，中国实验室利用高密度的 Hydra 商业代理集群网络，从海外领先平台系统性提取高价值模型隐性特征数据的行为，在事实层面上具有极高的真实确凿度。然而，如果我们将视线拉回至人工智能产业波澜壮阔且充满争议的发展史，并从现代法理学的严谨视角审视，这种行为绝非 Anthropic 试图向公众渲染的那种传统的、罪不可赦的 “底层源代码与商业核心机密窃取”。它更多是发生在全球生成式 AI 爆炸式发展的早期狂野阶段，在法律与伦理规则尚处于大面积模糊的地带中，后发追赶者对处于垄断地位的领先者技术溢出红利的一种“极限榨取” 与反向工程探索。Anthropic 所表现出的超常愤怒与严厉控诉，剥开其义正词严的维权外衣，其内在的真正驱动力是硅谷精英阶层面对其引以为傲的技术代差护城河正在被中国企业以不可思议的速度光速抹平时，所产生的极其严重的战略焦虑综合征；同时，这也是美国科技巨头为了完美配合华盛顿鹰派政客针对中国实施更进一步、更严苛、更具破坏性的全方位半导体技术封锁，所精心编织的绝佳地缘政治叙事铺垫。

对于正在艰难跋涉的中国人工智能产业而言，此次事件绝非宣告死亡的 “末日审判”，而是一记响彻云霄的历史警钟。包括 CAISI 系统评估在内的大量国际权威基准测试数据已经无可辩驳地向世界证明，中国自主研发的头部大模型在其核心架构设计的内生能力上，已经具备了与美国顶尖科技巨头在牌桌上正面掰手腕、一较高下的硬核实力。那些引发巨大争议的所谓“灵魂窃取” 与“蒸馏攻击”，充其量只是一种在起步阶段用来极大地缩短试错时间、加速模型能力收敛的战术辅助手段，它绝对不是，也永远不可能代表中国庞大 AI 工业体系的全部技术底色。

面对不可逆转的中美 “系统性技术脱钩” 历史大势，中国 AI 企业与学术界再也不能将突围的希望，寄托于通过技术手段规避跨国平台的用户使用条款，或者寻找国际开源社区监管框架中的灰色漏洞。相反，只有脚踏实地，立足于国内庞大且正趋于成熟的 “算电深度协同” 的百万卡级巨型物理集群算力底座，深度挖掘、清洗并合法交易极具中国行业特色的大规模自主高质量训练数据资产，同时在前沿算法层面勇敢拥抱基于合成数据自生成的多智能体自我演进新范式，并利用最严苛的标准构筑起密不透风的国内国际双重法律合规防火墙系统——唯有如此进行彻底的脱胎换骨，中国的人工智能产业才能在经历阵痛后凤凰涅槃，在真正意义上完成从 “跟随模仿” 向“范式引领”的伟大历史跨越，进而彻底终结被任何外部力量 “卡死脖子” 的历史宿命。

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-6b42c933f896f5a661df9e35f45c3c5e_r.jpg%3Fsource%3D1def8aca)

### 引用的著作

1.  Chinese AI Firms Hit Claude with Distillation Attacks, Anthropic Warns, 访问时间为 二月 24, 2026， [https://www.infosecurity-magazine.com/news/chinese-ai-claude-distillation/](https://link.zhihu.com/?target=https%3A//www.infosecurity-magazine.com/news/chinese-ai-claude-distillation/)
2.  Detecting and preventing distillation attacks - Anthropic, 访问时间为 二月 24, 2026， [https://www.anthropic.com/news/detecting-and-preventing-distillation-attacks](https://link.zhihu.com/?target=https%3A//www.anthropic.com/news/detecting-and-preventing-distillation-attacks)
3.  Anthropic exposes how Chinese AI firms try to steal LLM tech, 访问时间为 二月 24, 2026， [https://mashable.com/article/anthropic-details-chinese-ai-companies-distillation-attacks](https://link.zhihu.com/?target=https%3A//mashable.com/article/anthropic-details-chinese-ai-companies-distillation-attacks)
4.  OpenAI, Anthropic accuse Chinese rivals of mass AI data theft - The Hindu, 访问时间为 二月 24, 2026， [https://www.thehindu.com/sci-tech/technology/openai-anthropic-accuse-chinese-rivals-of-mass-ai-data-theft/article70669620.ece](https://link.zhihu.com/?target=https%3A//www.thehindu.com/sci-tech/technology/openai-anthropic-accuse-chinese-rivals-of-mass-ai-data-theft/article70669620.ece)
5.  OpenAI 'reviewing' allegations that its AI models were used to make DeepSeek, 访问时间为 二月 24, 2026， [https://www.theguardian.com/technology/2025/jan/29/openai-chatgpt-deepseek-china-us-ai-models](https://link.zhihu.com/?target=https%3A//www.theguardian.com/technology/2025/jan/29/openai-chatgpt-deepseek-china-us-ai-models)
6.  US AI giant accuses Chinese rivals of mass data theft, 访问时间为 二月 24, 2026， [https://www.theguardian.com/technology/2026/feb/23/us-ai-anthropic-china](https://link.zhihu.com/?target=https%3A//www.theguardian.com/technology/2026/feb/23/us-ai-anthropic-china)
7.  Anthropic Accuses Chinese AI Labs DeepSeek, Moonshot, and MiniMax of Stealing Claude Capabilities - Trending Topics, 访问时间为 二月 24, 2026， [https://www.trendingtopics.eu/anthropic-accuses-chinese-ai-labs-deepseek-moonshot-and-minimax-of-stealing-claude-capabilities/](https://link.zhihu.com/?target=https%3A//www.trendingtopics.eu/anthropic-accuses-chinese-ai-labs-deepseek-moonshot-and-minimax-of-stealing-claude-capabilities/)
8.  Chinese AI companies 'distilled' Claude to improve own models, Anthropic says - iTnews, 访问时间为 二月 24, 2026， [https://www.itnews.com.au/news/chinese-ai-companies-distilled-claude-to-improve-own-models-anthropic-says-623812](https://link.zhihu.com/?target=https%3A//www.itnews.com.au/news/chinese-ai-companies-distilled-claude-to-improve-own-models-anthropic-says-623812)
9.  Anthropic accuses Chinese labs of trying to illicitly take Claude’s capabilities, 访问时间为 二月 24, 2026， [Anthropic accuses Chinese labs of trying to illicitly take Claude’s capabilities](https://link.zhihu.com/?target=https%3A//cyberscoop.com/anthropic-accuses-chinese-labs-ai-distillation-cyber-risk/)
10.  ‘Anthropic has to pay Billions for Theft’: Elon Musk slams AI firm after it accuses Chinese labs of copying claude, 访问时间为 二月 24, 2026， [https://www.financialexpress.com/life/technology-anthropic-has-to-pay-billions-for-theft-elon-musk-slams-ai-firm-after-it-accuses-chinese-labs-of-copying-claude-4152861/](https://link.zhihu.com/?target=https%3A//www.financialexpress.com/life/technology-anthropic-has-to-pay-billions-for-theft-elon-musk-slams-ai-firm-after-it-accuses-chinese-labs-of-copying-claude-4152861/)
11.  还好意思说别人蒸馏？马斯克抨击 Anthropic 大规模盗用训练数据, 访问时间为 二月 24, 2026， [还好意思说别人蒸馏？马斯克抨击 Anthropic 大规模盗用训练数据](https://link.zhihu.com/?target=https%3A//finance.sina.cn/stock/jdts/2026-02-24/detail-inhnwmhy3286414.d.html%3Fvt%3D4%26cid%3D76993%26node_id%3D76993)
12.  还好意思说别人蒸馏？马斯克抨击 Anthropic 大规模盗用训练数据, 访问时间为 二月 24, 2026， [https://tech.sina.cn/2026-02-24/detail-inhnwmhy3275102.d.html?oid=%E3%82%B0%E3%83%BC%E3%82%B0%E3%83%AB%E3%82%B8%E3%82%A7%E3%83%8D%E3%83%AC%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3%E3%81%AE%E6%99%AE%E5%8F%8A(TG:e10838).muf&vt=4](https://link.zhihu.com/?target=https%3A//tech.sina.cn/2026-02-24/detail-inhnwmhy3275102.d.html%3Foid%3D%25E3%2582%25B0%25E3%2583%25BC%25E3%2582%25B0%25E3%2583%25AB%25E3%2582%25B8%25E3%2582%25A7%25E3%2583%258D%25E3%2583%25AC%25E3%2583%25BC%25E3%2582%25B7%25E3%2583%25A7%25E3%2583%25B3%25E3%2581%25AE%25E6%2599%25AE%25E5%258F%258A%28TG%3Ae10838%29.muf%26vt%3D4)
13.  Understanding LLM Distillation Attacks | by Tahir - Medium, 访问时间为 二月 24, 2026， [https://medium.com/@tahirbalarabe2/understanding-llm-distillation-attacks-929306ca38cd](https://link.zhihu.com/?target=https%3A//medium.com/%40tahirbalarabe2/understanding-llm-distillation-attacks-929306ca38cd)
14.  Chinese AI Labs Launch Massive Distillation Attacks on Anthropic Claude, Tracking 13M Exchanges - GBHackers, 访问时间为 二月 24, 2026， [https://gbhackers.com/chinese-ai-labs-launch-massive-distillation-attacks-on-anthropic-claude-tracking-13m-exchanges/](https://link.zhihu.com/?target=https%3A//gbhackers.com/chinese-ai-labs-launch-massive-distillation-attacks-on-anthropic-claude-tracking-13m-exchanges/)
15.  Anthropic alleges large-scale distillation campaigns targeting Claude - InfoWorld, 访问时间为 二月 24, 2026， [https://www.infoworld.com/article/4136468/anthropic-alleges-large-scale-distillation-campaigns-targeting-claude.html](https://link.zhihu.com/?target=https%3A//www.infoworld.com/article/4136468/anthropic-alleges-large-scale-distillation-campaigns-targeting-claude.html)
16.  Anthropic Distillation Attacks: DeepSeek, Moonshot, MiniMax, 访问时间为 二月 24, 2026， [https://www.digitalapplied.com/blog/anthropic-distillation-attacks-deepseek-moonshot-minimax](https://link.zhihu.com/?target=https%3A//www.digitalapplied.com/blog/anthropic-distillation-attacks-deepseek-moonshot-minimax)
17.  Hydra: Brokering Cloud and HPC Resources to Support the Execution of Heterogeneous Workloads at Scale - arXiv, 访问时间为 二月 24, 2026， [Hydra: Brokering Cloud and HPC Resources to Support the Execution of Heterogeneous Workloads at Scale](https://link.zhihu.com/?target=https%3A//arxiv.org/html/2407.11967v1)
18.  Hydra: Brokering Cloud and HPC Resources to Support the Execution of Heterogeneous Workloads at Scale - ResearchGate, 访问时间为 二月 24, 2026， [https://www.researchgate.net/publication/383966795\_Hydra\_Brokering\_Cloud\_and\_HPC\_Resources\_to\_Support\_the\_Execution\_of\_Heterogeneous\_Workloads\_at\_Scale](https://link.zhihu.com/?target=https%3A//www.researchgate.net/publication/383966795_Hydra_Brokering_Cloud_and_HPC_Resources_to_Support_the_Execution_of_Heterogeneous_Workloads_at_Scale)
19.  After OpenAI, Anthropic warns US government on China; says Chinese AI models are stealing our data and the speed, 访问时间为 二月 24, 2026， [https://timesofindia.indiatimes.com/technology/tech-news/after-openai-anthropic-warn-us-government-on-china-say-chinese-ai-models-are-stealing-our-data-and-the-speed-/articleshow/128741606.cms](https://link.zhihu.com/?target=https%3A//timesofindia.indiatimes.com/technology/tech-news/after-openai-anthropic-warn-us-government-on-china-say-chinese-ai-models-are-stealing-our-data-and-the-speed-/articleshow/128741606.cms)
20.  Anthropic Says Chinese AI Firms Used 16 Million Claude Queries to Copy Model - The Hacker News, 访问时间为 二月 24, 2026， [https://thehackernews.com/2026/02/anthropic-says-chinese-ai-firms-used-16.html](https://link.zhihu.com/?target=https%3A//thehackernews.com/2026/02/anthropic-says-chinese-ai-firms-used-16.html)
21.  \[D\] DeepSeek distillation and training costs : r/MachineLearning - Reddit, 访问时间为 二月 24, 2026， [https://www.reddit.com/r/MachineLearning/comments/1icfbll/d\_deepseek\_distillation\_and\_training\_costs/](https://link.zhihu.com/?target=https%3A//www.reddit.com/r/MachineLearning/comments/1icfbll/d_deepseek_distillation_and_training_costs/)
22.  DeepSeek V3.1 Complete Evaluation Analysis: The New AI Programming Benchmark for 2025 - DEV Community, 访问时间为 二月 24, 2026， [DeepSeek V3.1 Complete Evaluation Analysis: The New AI Programming Benchmark for 2025](https://link.zhihu.com/?target=https%3A//dev.to/czmilo/deepseek-v31-complete-evaluation-analysis-the-new-ai-programming-benchmark-for-2025-58jc)
23.  DeepSeek V3.1 (Reasoning) vs Claude 4 Opus (Non-reasoning): Model Comparison, 访问时间为 二月 24, 2026， [https://artificialanalysis.ai/models/comparisons/deepseek-v3-1-reasoning-vs-claude-4-opus](https://link.zhihu.com/?target=https%3A//artificialanalysis.ai/models/comparisons/deepseek-v3-1-reasoning-vs-claude-4-opus)
24.  DeepSeek V3.1 (Non-reasoning) vs Claude 4 Opus (Non-reasoning): Model Comparison, 访问时间为 二月 24, 2026， [https://artificialanalysis.ai/models/comparisons/deepseek-v3-1-vs-claude-4-opus](https://link.zhihu.com/?target=https%3A//artificialanalysis.ai/models/comparisons/deepseek-v3-1-vs-claude-4-opus)
25.  DeepSeek 3.1 is BETTER than Claude Sonnet 4? (FREE) - YouTube, 访问时间为 二月 24, 2026， [https://www.youtube.com/watch?v=R4JicSlHmTw](https://link.zhihu.com/?target=https%3A//www.youtube.com/watch%3Fv%3DR4JicSlHmTw)
26.  Claude Opus 4 vs DeepSeek V3.1 (Comparative Analysis) - Galaxy.ai Blog, 访问时间为 二月 24, 2026， [https://blog.galaxy.ai/compare/claude-opus-4-vs-deepseek-chat-v3-1](https://link.zhihu.com/?target=https%3A//blog.galaxy.ai/compare/claude-opus-4-vs-deepseek-chat-v3-1)
27.  Evaluation of DeepSeek AI Models - National Institute of Standards and Technology, 访问时间为 二月 24, 2026， [https://www.nist.gov/system/files/documents/2025/09/30/CAISI\_Evaluation\_of\_DeepSeek\_AI\_Models.pdf](https://link.zhihu.com/?target=https%3A//www.nist.gov/system/files/documents/2025/09/30/CAISI_Evaluation_of_DeepSeek_AI_Models.pdf)
28.  DeepSeek-V3.2: Pushing the Frontier of Open Large Language Models - arXiv.org, 访问时间为 二月 24, 2026， [DeepSeek-V3.2: Pushing the Frontier of Open Large Language Models](https://link.zhihu.com/?target=https%3A//arxiv.org/html/2512.02556v1)
29.  Protecting Our Edge: Trade Secrets and the Global AI Arms Race - CSIS, 访问时间为 二月 24, 2026， [https://www.csis.org/analysis/protecting-our-edge-trade-secrets-and-global-ai-arms-race](https://link.zhihu.com/?target=https%3A//www.csis.org/analysis/protecting-our-edge-trade-secrets-and-global-ai-arms-race)
30.  Is AI Distillation By DeepSeek IP Theft? - Winston & Strawn, 访问时间为 二月 24, 2026， [https://www.winston.com/en/insights\-news/is-ai-distillation-by-deepseek-ip-theft](https://link.zhihu.com/?target=https%3A//www.winston.com/en/insights-news/is-ai-distillation-by-deepseek-ip-theft)
31.  DeepSeek, Model Distillation, and the Future of AI IP Protection - Fenwick, 访问时间为 二月 24, 2026， [https://www.fenwick.com/insights/publications/deepseek-model-distillation-and-the-future-of-ai-ip-protection](https://link.zhihu.com/?target=https%3A//www.fenwick.com/insights/publications/deepseek-model-distillation-and-the-future-of-ai-ip-protection)
32.  Protecting AI Assets and Outputs with IP Strategies in a Changing World - Mayer Brown, 访问时间为 二月 24, 2026， [https://www.mayerbrown.com/en/insights/publications/2025/12/protecting-ai-assets-and-outputs-with-ip-strategies-in-a-changing-world](https://link.zhihu.com/?target=https%3A//www.mayerbrown.com/en/insights/publications/2025/12/protecting-ai-assets-and-outputs-with-ip-strategies-in-a-changing-world)
33.  From Prompt to Clone: Copyright Challenges in AI Model Distillation - UC Law SF Scholarship Repository, 访问时间为 二月 24, 2026， [https://repository.uclawsf.edu/cgi/viewcontent.cgi?article=1151&context=hastings\_science\_technology\_law\_journal](https://link.zhihu.com/?target=https%3A//repository.uclawsf.edu/cgi/viewcontent.cgi%3Farticle%3D1151%26context%3Dhastings_science_technology_law_journal)
34.  Trade Secrecy Meets Generative AI - Scholarly Commons @ IIT Chicago-Kent College of Law, 访问时间为 二月 24, 2026， [https://scholarship.kentlaw.iit.edu/cgi/viewcontent.cgi?article=4489&context=cklawreview](https://link.zhihu.com/?target=https%3A//scholarship.kentlaw.iit.edu/cgi/viewcontent.cgi%3Farticle%3D4489%26context%3Dcklawreview)
35.  DeepSeek, ChatGPT, and the global fight for technological supremacy, 访问时间为 二月 24, 2026， [DeepSeek, ChatGPT, and the global fight for technological supremacy - Harvard Law School](https://link.zhihu.com/?target=https%3A//hls.harvard.edu/today/deepseek-chatgpt-and-the-global-fight-for-technological-supremacy/)
36.  Anthropic accuses DeepSeek and 2 other Chinese AI models of stealing its data, people on internet say it is fair, 访问时间为 二月 24, 2026， [https://www.indiatoday.in/technology/news/story/anthropic-accuses-deepseek-and-2-other-chinese-ai-models-of-stealing-its-data-people-on-internet-say-it-is-fair-2873359-2026-02-24](https://link.zhihu.com/?target=https%3A//www.indiatoday.in/technology/news/story/anthropic-accuses-deepseek-and-2-other-chinese-ai-models-of-stealing-its-data-people-on-internet-say-it-is-fair-2873359-2026-02-24)
37.  Anthropic 指控中国大模型 “使诈”，马斯克凶猛炮轰，海外网友贴脸开骂 - 智东西, 访问时间为 二月 24, 2026， [Anthropic 指控中国大模型 “使诈”，马斯克凶猛炮轰，海外网友贴脸开骂 - 智东西](https://link.zhihu.com/?target=https%3A//zhidx.com/p/535868.html)
38.  Anthropic 指控三家 AI 公司大规模 “蒸馏” 其 Claude 模型 - 新浪, 访问时间为 二月 24, 2026， [https://k.sina.com.cn/article\_7913909554\_1d7b4ad3200102ch4o.html?from=tech](https://link.zhihu.com/?target=https%3A//k.sina.com.cn/article_7913909554_1d7b4ad3200102ch4o.html%3Ffrom%3Dtech)
39.  Remote Code Execution With Modern AI/ML Formats and Libraries - Unit 42, 访问时间为 二月 24, 2026， [https://unit42.paloaltonetworks.com/rce-vulnerabilities-in-ai-python-libraries/](https://link.zhihu.com/?target=https%3A//unit42.paloaltonetworks.com/rce-vulnerabilities-in-ai-python-libraries/)
40.  Experimenting with AI to defend critical infrastructure - Anthropic Red Team, 访问时间为 二月 24, 2026， [AI for Critical Infrastucture Defense \\ red.anthropic.com](https://link.zhihu.com/?target=https%3A//red.anthropic.com/2026/critical-infrastructure-defense/)
41.  Disrupting the first reported AI-orchestrated cyber espionage campaign - Anthropic, 访问时间为 二月 24, 2026， [https://www.anthropic.com/news/disrupting-AI-espionage](https://link.zhihu.com/?target=https%3A//www.anthropic.com/news/disrupting-AI-espionage)
42.  Exclusive-China’s DeepSeek trained AI model on Nvidia’s best chip despite US ban, official says, 访问时间为 二月 24, 2026， [https://wkzo.com/2026/02/23/exclusive-chinas-deepseek-trained-ai-model-on-nvidias-best-chip-despite-us-ban-official-says/](https://link.zhihu.com/?target=https%3A//wkzo.com/2026/02/23/exclusive-chinas-deepseek-trained-ai-model-on-nvidias-best-chip-despite-us-ban-official-says/)
43.  U.S. Department of Commerce Rescinds Biden Administration's AI Diffusion Export Control Rule and Issues New Guidance on Huawei, Chips for AI Purposes, and Diligence Expectations | Crowell & Moring LLP, 访问时间为 二月 24, 2026， [https://www.crowell.com/en/insights/client-alerts/us-department-of-commerce-rescinds-biden-administrations-ai-diffusion-export-control-rule-and-issues-new-guidance-on-huawei-chips-for-ai-purposes-and-diligence-expectations](https://link.zhihu.com/?target=https%3A//www.crowell.com/en/insights/client-alerts/us-department-of-commerce-rescinds-biden-administrations-ai-diffusion-export-control-rule-and-issues-new-guidance-on-huawei-chips-for-ai-purposes-and-diligence-expectations)
44.  BIS Rescinds AI Diffusion Rule and Issues Guidance on Advanced Computing Integrated Circuits - Wiley, 访问时间为 二月 24, 2026， [https://www.wiley.law/alert-BIS-Rescinds-AI-Diffusion-Rule](https://link.zhihu.com/?target=https%3A//www.wiley.law/alert-BIS-Rescinds-AI-Diffusion-Rule)
45.  The US AI Diffusion Rule: What is it, why did the United States rescind it, and implications for Australia, 访问时间为 二月 24, 2026， [https://www.ussc.edu.au/the-us-ai-diffusion-rule](https://link.zhihu.com/?target=https%3A//www.ussc.edu.au/the-us-ai-diffusion-rule)
46.  Department of Commerce Announces Rescission of Biden-Era Artificial Intelligence Diffusion Rule, Strengthens Chip-Related Export Controls - Bureau of Industry and Security, 访问时间为 二月 24, 2026， [https://www.bis.gov/press-release/department-commerce-announces-rescission-biden-era-artificial-intelligence-diffusion-rule-strengthens](https://link.zhihu.com/?target=https%3A//www.bis.gov/press-release/department-commerce-announces-rescission-biden-era-artificial-intelligence-diffusion-rule-strengthens)
47.  China’s DeepSeek Trains AI on U.S. Nvidia Chip Despite Export Ban, 访问时间为 二月 24, 2026， [https://moderndiplomacy.eu/2026/02/24/chinas-deepseek-trains-ai-on-u-s-nvidia-chip-despite-export-ban/](https://link.zhihu.com/?target=https%3A//moderndiplomacy.eu/2026/02/24/chinas-deepseek-trains-ai-on-u-s-nvidia-chip-despite-export-ban/)
48.  China's DeepSeek trained AI model on Nvidia's best chip despite US ban, official says, 访问时间为 二月 24, 2026， [https://www.thehindu.com/sci-tech/technology/chinas-deepseek-trained-ai-model-on-nvidias-best-chip-despite-us-ban-official-says/article70669635.ece](https://link.zhihu.com/?target=https%3A//www.thehindu.com/sci-tech/technology/chinas-deepseek-trained-ai-model-on-nvidias-best-chip-despite-us-ban-official-says/article70669635.ece)
49.  Exclusive: China's DeepSeek trained AI model on Nvidia's best chip despite US ban, official says - Maaal, 访问时间为 二月 24, 2026， [https://maaal.com/en/news/details/exclusive-chinas-deepse-a](https://link.zhihu.com/?target=https%3A//maaal.com/en/news/details/exclusive-chinas-deepse-a)
50.  In Responses to Warren, Trump CYBERCOM and NSA Nominee Warns About China Seeking Advanced American AI Chips - Senate Committee on Banking, Housing, and Urban Affairs, 访问时间为 二月 24, 2026， [https://www.banking.senate.gov/newsroom/minority/in-responses-to-warren-trump-cybercom-and-nsa-nominee-warns-about-china-seeking-advanced-american-ai-chips](https://link.zhihu.com/?target=https%3A//www.banking.senate.gov/newsroom/minority/in-responses-to-warren-trump-cybercom-and-nsa-nominee-warns-about-china-seeking-advanced-american-ai-chips)
51.  中国公司 “偷走”Claude 模型？Anthropic 气炸，却被马斯克一句话怼到无语 - 科技, 访问时间为 二月 24, 2026， [https://tech.sina.cn/mobile/xp/2026-02-24/detail-inhnxaes3088094.d.html?vt=4](https://link.zhihu.com/?target=https%3A//tech.sina.cn/mobile/xp/2026-02-24/detail-inhnxaes3088094.d.html%3Fvt%3D4)
52.  DeepSeek, Moonshot, and MiniMax made ‘industrial-scale’ distillation attack to copy Claude, accuses Anthropic, 访问时间为 二月 24, 2026， [https://www.financialexpress.com/life/technology-deepseek-moonshot-and-minimax-made-industrial-scale-distillation-attack-to-copy-claude-accuses-anthropic-4153254/](https://link.zhihu.com/?target=https%3A//www.financialexpress.com/life/technology-deepseek-moonshot-and-minimax-made-industrial-scale-distillation-attack-to-copy-claude-accuses-anthropic-4153254/)
53.  2026 年中国 AI 发展趋势前瞻, 访问时间为 二月 24, 2026， [2026 年中国 AI 发展趋势前瞻 - 中国国际电子商务中心](https://link.zhihu.com/?target=https%3A//ciecc.ec.com.cn/swyj/yjdt/2026/1/1b9055690f004bdf99190f2d99d28dd8519.html)
54.  Notes from the Asia-Pacific region: Strong start to 2026 for China's data, AI governance landscape | IAPP, 访问时间为 二月 24, 2026， [https://iapp.org/news/a/notes-from-the-asia-pacific-region-strong-start-to-2026-for-china-s-data-ai-governance-landscape](https://link.zhihu.com/?target=https%3A//iapp.org/news/a/notes-from-the-asia-pacific-region-strong-start-to-2026-for-china-s-data-ai-governance-landscape)
55.  China to boost AI-focused data trading - Chinadaily.com.cn, 访问时间为 二月 24, 2026， [China to boost AI-focused data trading](https://link.zhihu.com/?target=https%3A//global.chinadaily.com.cn/a/202602/07/WS6986ce02a310d6866eb3809c.html)
56.  计划报告解读丨冲刺 “全球人工智能创新高地”：北京 2026 如何发力 AI 产业？, 访问时间为 二月 24, 2026， [计划报告解读丨冲刺 “全球人工智能创新高地”：北京 2026 如何发力 AI 产业？](https://link.zhihu.com/?target=http%3A//bj.people.com.cn/n2/2026/0128/c14540-41486135.html)
57.  请回答 2026：38 位中国 AI 关键人物的 Magic Moment 和趋势判断, 访问时间为 二月 24, 2026， [请回答 2026：38 位中国 AI 关键人物的 Magic Moment 和趋势判断](https://link.zhihu.com/?target=https%3A//www.jazzyear.com/article_info.html%3Fid%3D1691)
58.  CHINA: Amendments to Cybersecurity Law Effective 1 January 2026 | Privacy Matters, 访问时间为 二月 24, 2026， [https://privacymatters.dlapiper.com/2025/11/china-amendments-to-cybersecurity-law-effective-1-january-2026/](https://link.zhihu.com/?target=https%3A//privacymatters.dlapiper.com/2025/11/china-amendments-to-cybersecurity-law-effective-1-january-2026/)
59.  China Cybersecurity Law Amendment in Effect January 1, 2026, 访问时间为 二月 24, 2026， [https://www.china-briefing.com/news/china-cybersecurity-law-amendment/](https://link.zhihu.com/?target=https%3A//www.china-briefing.com/news/china-cybersecurity-law-amendment/)
60.  CAC Issues Amendment to the Cybersecurity Law of China - Hunton Andrews Kurth LLP, 访问时间为 二月 24, 2026， [https://www.hunton.com/privacy-and-cybersecurity-law-blog/cac-issues-amendment-to-the-cybersecurity-law-of-china](https://link.zhihu.com/?target=https%3A//www.hunton.com/privacy-and-cybersecurity-law-blog/cac-issues-amendment-to-the-cybersecurity-law-of-china)
61.  AI laws and regulations in China| CMS Expert Guide, 访问时间为 二月 24, 2026， [https://cms.law/en/int/expert-guides/ai-regulation-scanner/china](https://link.zhihu.com/?target=https%3A//cms.law/en/int/expert-guides/ai-regulation-scanner/china)
62.  2026 AI Legal Forecast: From Innovation to Compliance | Baker Donelson, 访问时间为 二月 24, 2026， [https://www.bakerdonelson.com/2026-ai-legal-forecast-from-innovation-to-compliance](https://link.zhihu.com/?target=https%3A//www.bakerdonelson.com/2026-ai-legal-forecast-from-innovation-to-compliance)
63.  China: Certification Measures Issued for Cross-Border Transfers of Personal Data, 访问时间为 二月 24, 2026， [https://www.loc.gov/item/global-legal-monitor/2026-02-19/china-certification-measures-issued-for-cross-border-transfers-of-personal-data/](https://link.zhihu.com/?target=https%3A//www.loc.gov/item/global-legal-monitor/2026-02-19/china-certification-measures-issued-for-cross-border-transfers-of-personal-data/)
    
    
    
    
### 知乎用户  稀饭盖浇面 发表
    
西方法律中的版权、[专利](https://zhida.zhihu.com/search?content_id=770666758&content_type=Answer&match_order=1&q=%E4%B8%93%E5%88%A9&zhida_source=entity)等相关法，真的是毒瘤中的毒瘤

无端的浪费着人类的资源
    
    
    
    
### 知乎用户 釰 USA 发表
    
这些公司，或者说目前国内国外的 AI 公司就没有一家经得住 “合规合法” 的检查。这些公司的差别在于脸皮厚不厚。

中国公司的缺点就在于脸皮薄，不像美国公司一边偷窃一边骂别人偷窃。
    
    
    
    
### 知乎用户 秩序雕刻​ 发表
    
2026 年 2 月 23 日，美国人工智能公司 [Anthropic](https://zhida.zhihu.com/search?content_id=770711131&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 在其官方博客发布了一篇措辞严厉的声明，指控中国三家 AI 企业——深度求索（[DeepSeek](https://zhida.zhihu.com/search?content_id=770711131&content_type=Answer&match_order=1&q=DeepSeek&zhida_source=entity)）、月之暗面（[Moonshot AI](https://zhida.zhihu.com/search?content_id=770711131&content_type=Answer&match_order=1&q=Moonshot+AI&zhida_source=entity)）和 [MiniMax](https://zhida.zhihu.com/search?content_id=770711131&content_type=Answer&match_order=1&q=MiniMax&zhida_source=entity)——通过约 2.4 万个虚假账号与 Anthropic 旗下的 [Claude AI](https://zhida.zhihu.com/search?content_id=770711131&content_type=Answer&match_order=1&q=Claude+AI&zhida_source=entity) 模型进行了超过 1600 万次交互，大规模提取 Claude 在推理、编程和工具使用等方面的核心能力，用以训练和提升自身模型。Anthropic 将这一行为定性为违反其服务条款和区域访问限制的工业级「[蒸馏攻击](https://zhida.zhihu.com/search?content_id=770711131&content_type=Answer&match_order=1&q=%E8%92%B8%E9%A6%8F%E6%94%BB%E5%87%BB&zhida_source=entity)」 (distillation attacks)。

这并非美国 AI 企业首次提出类似指控。就在本月早些时候，[OpenAI](https://zhida.zhihu.com/search?content_id=770711131&content_type=Answer&match_order=1&q=OpenAI&zhida_source=entity) 向美国国会众议院提交备忘录，声称 DeepSeek 正在持续蒸馏其前沿模型。两家美国头部 AI 公司相继发难，且均将矛头指向中国企业，这一事件已超越单纯的商业纠纷，带有明显的产业政策和地缘政治色彩——Anthropic 在声明中直接将蒸馏行为与芯片出口管制的合理性挂钩，呼吁政策制定者采取协调行动。

截至目前，DeepSeek、月之暗面和 MiniMax 三家企业均未对指控作出公开回应。多家外媒在报道中注意到，此事引发了行业内外的复杂反应：一方面有人认为这暴露了中国 AI 企业对美国技术的依赖；另一方面也有更多的、大量声音指出，Anthropic 自身曾因大规模下载盗版图书训练 Claude 而于 2025 年 9 月支付了 15 亿美元的和解金，这种「**自己抄完再指责别人抄**」的姿态缺乏道德说服力。

蒸馏：一种被广泛使用的训练技术
---------------

什么是模型蒸馏？“[知识蒸馏](https://zhida.zhihu.com/search?content_id=770711131&content_type=Answer&match_order=1&q=%E7%9F%A5%E8%AF%86%E8%92%B8%E9%A6%8F&zhida_source=entity)” 最早由 [Geoffrey Hinton](https://zhida.zhihu.com/search?content_id=770711131&content_type=Answer&match_order=1&q=Geoffrey+Hinton&zhida_source=entity) 等人于 2015 年提出，其基本逻辑是让一个较小的「学生模型」通过学习较大「教师模型」的输出结果来获取能力，从而在较低的算力和成本下达到接近教师模型的性能。这项技术本身是中立的，且在业界被广泛采用——Anthropic 自己也在声明中承认，前沿 AI 实验室「常规性地蒸馏自己的模型，以创建更小、更便宜的版本」。

蒸馏之所以对初创企业和后发者具有强大吸引力，原因不难理解。训练一个前沿大模型的成本已经攀升到数亿乃至数十亿美元量级，这个门槛对绝大多数企业而言几乎不可逾越。蒸馏提供了一条以较低成本快速缩小差距的路径。事实上，不仅是中国企业，全球范围内许多开源模型项目都依赖蒸馏技术来降低训练门槛。DeepSeek 在其技术论文中也公开披露了使用 [Qwen2.5](https://zhida.zhihu.com/search?content_id=770711131&content_type=Answer&match_order=1&q=Qwen2.5&zhida_source=entity) 和 [Llama-3.1](https://zhida.zhihu.com/search?content_id=770711131&content_type=Answer&match_order=1&q=Llama-3.1&zhida_source=entity) 等模型作为蒸馏基础的事实。

正因为蒸馏如此普遍，OpenAI、Anthropic、Mistral、xAI 等闭源模型提供商纷纷在服务条款中设置了「反竞争性蒸馏」条款，明确禁止用户利用其服务输出来开发竞争性模型。OpenAI 的使用条款规定用户不得「使用输出来开发与 OpenAI 竞争的模型」，也不得「自动化或程序化地提取数据或输出」。Anthropic 的条款也有类似限制，并在中国地区实施了商业访问禁令。

蒸馏行为涉及的法律问题
-----------

本次事件涉及的法律关系是多层次的，并不能简单归结为单一法律领域的问题：

最直接的法律基础是**合同约束**。三家中国企业被指控通过代理服务绕过区域限制、使用虚假账号访问 Claude，这构成对 Anthropic 服务条款的违反。从合同法角度看，这一点的认定相对清晰。但合同法路径的局限性同样明显：一方面，服务条款作为格式条款，其中的限制性条款是否得到了充分提示和说明，在不同法域下可能面临效力挑战；另一方面，即便违约成立，跨境执行的现实困难使得纯粹的违约之诉在实际救济上意义有限。这也是为什么 Anthropic 选择通过公开声明而非直接诉讼来表达立场——相较于法律救济，舆论施压和推动政策变化可能是更现实的目标。

**著作权**路径面临的障碍更为根本。蒸馏的训练数据是教师模型的输出内容，而 AI 生成内容的可版权性在全球范围内仍是未决问题。美国版权局在 2025 年 1 月发布的报告中重申，版权保护需要满足「人类作者」标准，单纯的提示词输入通常不足以使 AI 输出获得版权保护。更重要的是，即便输出内容可获版权保护，OpenAI 等公司的服务条款通常将输出内容的权利转让给用户，这使得模型提供商很难基于版权法主张权利。中国司法实践中，北京互联网法院在 2024 年审结的「AI 文生图案」开创性地认定了具有充分智力投入的 AI 生成图片可以构成作品，但这一思路要延伸到蒸馏场景中教师模型对海量自动化提示的输出，逻辑上存在相当距离。

由于蒸馏产生的学生模型通常与教师模型具有不同的架构，著作权法难以提供有效保护，但通过合理的**专利**布局，模型提供商可以同时保护教师模型本身和由此衍生的未授权学生模型。美国专利侵权诉讼中约五分之四涉及竞争对手之间的案件最终获得了永久禁令，这使得专利可能成为遏制未授权蒸馏的有力工具。不过这条路径需要企业事前具有充分的专利申请意识和策略规划。

**反不正当竞争法**可能是处理蒸馏行为最具弹性的法律框架。在中国法语境下，尽管[《反不正当竞争法》](https://zhida.zhihu.com/search?content_id=770711131&content_type=Answer&match_order=1&q=%E3%80%8A%E5%8F%8D%E4%B8%8D%E6%AD%A3%E5%BD%93%E7%AB%9E%E4%BA%89%E6%B3%95%E3%80%8B&zhida_source=entity)没有对蒸馏行为的专门规定，但可以援引**第二条一般条款**或者 “**数据专条**”，从违反用户协议、搭便车获取竞争优势、损害教师模型研发方合法权益、不合理获取竞争对手合法拥有的数据等角度论证不正当性。不过，这一路径同样存在反向论证空间：如果禁止一切蒸馏行为，头部企业是否反而构成不合理限制（甚至是《反垄断法》下的滥用市场支配地位行为），阻碍技术创新和自由竞争？

**商业秘密**可能是一个被低估但值得重视的维度。AI 模型提供商通过大量研发投入积累的算法优化、数据选择、参数调优等知识，虽然以输出结果的形式间接呈现，但其背后的独特实现方式和优化逻辑可能构成商业秘密。如果蒸馏行为能够被证明实质上提取了这些受保护的知识，则可能突破合同关系的局限，获得更强的法律保护。当然，这需要模型提供商证明其采取了合理的保密措施且相关信息具有秘密性和商业价值——在 API 公开访问的场景下，这一举证并不容易。

司法实践的现状与未来
----------

从全球司法实践来看，直接针对模型蒸馏行为的判例尚不存在，但若干相关案件为理解法律边界提供了参照：

美国联邦法院在 2025 年 2 月作出的 Thomson Reuters v. Ross Intelligence 案判决是 AI 训练数据版权争议中首个否定合理使用抗辩的实质性裁决。法院认定 Ross 使用 Westlaw 的案例摘要训练竞争性法律研究工具不构成合理使用，重点考量了使用目的的商业性和对原作潜在市场的影响。该案已被第三巡回上诉法院受理进行中间上诉，其判决将成为美国联邦上诉法院层面首次就 AI 训练中的合理使用原则作出表态。虽然该案涉及的是非生成式 AI 且案情有其特殊性，但法院对第四要素（市场影响）的分析思路——尤其是认定存在「AI 训练数据许可市场」的潜在市场——对蒸馏争议具有参考意义。同一时期，Bartz v. Anthropic 案中 Anthropic 因从盗版数据库下载训练数据而以 15 亿美元达成和解，Kadrey v. Meta 案中法官则倾向于认定 Meta 的训练行为构成合理使用——可见美国司法对 AI 训练行为的态度远未统一。

中国司法层面，虽然尚未出现直接涉及模型蒸馏的案件，但近年来在 AI 生成物版权保护、AI 平台责任等领域的积极探索表明，司法实践并不落后于产业发展的节奏。北京互联网法院的「AI 文生图案」和杭州互联网法院的「奥特曼 AI 生成图片侵权案」在 AI 内容的版权定性和平台责任分配方面形成了具有前瞻性的裁判思路。同时，《反不正当竞争法》第二条一般条款在互联网和数据领域的灵活适用，为处理包括蒸馏在内的新型竞争行为提供了制度弹性。

未决之问
----

回到 Anthropic 指控事件本身，几个关键问题仍然悬而未决。

第一，**蒸馏行为合法与非法的边界究竟在哪？**Anthropic 自己承认蒸馏是广泛使用的合法技术，问题在于规模、方式和目的。使用虚假账号绕过访问限制进行大规模系统性提取，与研究人员出于学习目的使用某个模型的输出，二者在行为性质上显然不同。但在这两个极端之间，灰色地带很大。

第二，**服务条款中的反蒸馏条款是否具有普遍约束力？**当这些条款与促进技术创新和市场竞争的公共利益发生冲突时，法律应如何取舍？在中国法下，格式条款中不合理加重对方责任的内容可能被认定为无效。在美国法下，类似条款在仲裁和诉讼中的可执行性也存在争议。

第三，**在 AI 模型输出不受（或难以受到）版权保护的法律框架下，模型提供商究竟能依靠什么来保护其研发投入？**合同路径依赖于直接的用户关系，版权路径面临可版权性的根本障碍，专利需要事前布局，商业秘密需要证明保密措施——每一条路径都有各自的局限。

来到更宏观的问题：在中美科技竞争的大背景下，蒸馏争议多大程度上是真实的法律问题，又有多大程度上是产业竞争策略的工具？Anthropic 的声明发布时点恰逢特朗普政府讨论是否放宽对华 H200 芯片出口限制，其 CEO Dario Amodei 刚在国会就 AI 安全问题作证——指控的政策游说意图难以忽视。

但这并不意味着其中不包含真实的法律关切。

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-964833602a86d6ee13734e24dd0844c7_r.jpg%3Fsource%3D1def8aca)
    
    
    
    
### 知乎用户 神经蛙没头脑 发表
    
2026 年 2 月 24 日 [Anthropic](https://zhida.zhihu.com/search?content_id=770803090&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 对 DeepSeek、[Moonshot](https://zhida.zhihu.com/search?content_id=770803090&content_type=Answer&match_order=1&q=Moonshot&zhida_source=entity)（月之暗面）和 [MiniMax](https://zhida.zhihu.com/search?content_id=770803090&content_type=Answer&match_order=1&q=MiniMax&zhida_source=entity) 的 “大规模蒸馏” 指控，表面是技术合规争议，实则折射出**全球 AI 竞争已进入 “规则制定权争夺” 的新阶段**。这一事件需从技术、法律、地缘政治三重维度冷静审视：

* * *

### 一、**技术层面：蒸馏是否等于 “盗窃”？**

### ✅ **蒸馏的本质是 “知识迁移”，非数据复制**

*   **合法场景**：

*   OpenAI 用 GPT-4 蒸馏出 [GPT-4o](https://zhida.zhihu.com/search?content_id=770803090&content_type=Answer&match_order=1&q=GPT-4o&zhida_source=entity)；
*   阿里用 [Qwen](https://zhida.zhihu.com/search?content_id=770803090&content_type=Answer&match_order=1&q=Qwen&zhida_source=entity)\-Max 蒸馏出 [Qwen-Turbo](https://zhida.zhihu.com/search?content_id=770803090&content_type=Answer&match_order=1&q=Qwen-Turbo&zhida_source=entity)；
*   Anthropic 自身也用 [Claude Opus](https://zhida.zhihu.com/search?content_id=770803090&content_type=Answer&match_order=1&q=Claude+Opus&zhida_source=entity) 蒸馏轻量版。

*   **争议焦点**：

*   **跨主体蒸馏**是否构成侵权？  
    → 蒸馏输出的是**概率分布 / 推理逻辑**，而非原始训练数据，更接近 “反向工程” 而非“盗取代码”。
*   **安全护栏剥离风险**：  
    → Anthropic 担忧对手移除其伦理限制（如拒绝生成生化武器配方），但无证据表明中国模型存在此类滥用。

### ⚠️ **Anthropic 的双重标准**

*   其自身因**盗用 700 万本盗版书训练模型**，2025 年支付 15 亿美元和解金 ；
*   马斯克直指：“他们怎么敢偷 Anthropic 从人类程序员那里偷来的东西？”

💡 **技术共识**：  
**蒸馏能加速入门，但无法突破能力天花板**——顶级模型仍需强化学习（RL）自主探索。

* * *

### 二、**法律与合规：服务条款 vs 全球规则空白**

### 🔍 **Anthropic 的核心依据**

*   用户协议禁止 “未经许可将输出用于训练 AI 模型”；
*   中国用户被地域封锁，涉事公司通过代理绕过限制。

### ⚖️ **现实困境**

*   **管辖权模糊**：

*   中国公司注册地、服务器、用户均在境内，美国条款难以跨境执行；

*   **法律定性不明**：

*   全球尚无判例认定 “[API 输出蒸馏](https://zhida.zhihu.com/search?content_id=770803090&content_type=Answer&match_order=1&q=API%E8%BE%93%E5%87%BA%E8%92%B8%E9%A6%8F&zhida_source=entity)” 构成版权侵权；
*   欧盟 AI 法案亦未明确此类行为边界。

📌 **关键点**：  
此举更像**商业施压**而非法律行动——Anthropic 试图以 “违规” 叙事影响美国政府对华 AI 芯片出口管制。

* * *

### 三、**地缘政治：[AI 冷战](https://zhida.zhihu.com/search?content_id=770803090&content_type=Answer&match_order=1&q=AI%E5%86%B7%E6%88%98&zhida_source=entity)下的 “投名状”**

### 🌐 **Anthropic 的战略意图**

1.  **迎合美国政策**：

*   美国防部正要求 AI 公司提供 “无限制模型访问权限”，否则列为 “供应链威胁”；
*   此次指控可视为向政府递交的 “忠诚证明”。

2. **转移自身污点**：

*   在盗版书籍丑闻后，急需塑造 “技术守护者” 形象。

### 🇨🇳 **中国企业的沉默策略**

*   DeepSeek 等未回应，实为**用产品说话**：

*   Kimi K2.5 调用量登顶 OpenRouter 榜首；
*   MiniMax M2.5 在 SWE-bench Verified 得分 80.2%，逼近 Claude Opus 4.6（80.8%）。

*   **开源反击**：

*   DeepSeek-V3、Kimi K2.5 均开源，接受全球验证。

* * *

### 四、**行业影响：规则博弈白热化**

| 主体 | 行动 | 目标 |
| --- | --- | --- |
| 美国 AI 公司 | 强化 API 防护 + 游说出口管制 | 延缓中国 AI 追赶速度 |
| 中国实验室 | 加速自研 + 开源生态建设 | 打破 “窃取” 叙事，建立技术自信 |
| 全球开发者 | 转向开源模型（如 Qwen、Llama） | 规避闭源模型合规风险 |

💥 **未来趋势**：  
**闭源模型将加强 “水印追踪”**（如 Anthropic 的 “[九头蛇集群](https://zhida.zhihu.com/search?content_id=770803090&content_type=Answer&match_order=1&q=%E4%B9%9D%E5%A4%B4%E8%9B%87%E9%9B%86%E7%BE%A4&zhida_source=entity)” 检测），  
**开源模型成创新主阵地**——Meta 的 Llama、阿里的 Qwen、百川的 Baichuan 正构建新生态。

* * *

### 🔑 **结论：一场注定无解的 “罗生门”**

*   **对 Anthropic**：指控是维护商业利益与政治正确的必然选择；
*   **对中国企业**：沉默是最高级的回应——用技术突破证伪 “走捷径” 论；
*   **对行业**：**蒸馏争议将加速全球 AI 治理规则制定**，但在此之前，**“能跑赢的模型，永远比道德指责更有说服力。”**

正如 RLHF 专家 Nathan Lambert 所言：

“中国 AI 的成功源于扎实的基础设施与人才密度，而非所谓‘蒸馏捷径’——Anthropic 的指控，更像是焦虑下的防御性反应。”

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-9dbb2c43ca1665393c6b6b5d099d0111_r.jpg%3Fsource%3D1def8aca)

  
**[有哪些芯片流片失败的故事？ - 知乎](https://www.zhihu.com/question/68260450/answer/1982129576080589154)**

**[AI 芯片三强争霸：英伟达、博通、迈威尔谁将胜出？ - 知乎](https://zhuanlan.zhihu.com/p/1981315335018792353)**

**[H200 放行，全球 AI 分流，国产算力要不要换一套打法？ - 知乎](https://zhuanlan.zhihu.com/p/1981747699809272721)**

[2025 年最新技术参数、市场份额及应用场景的国产 AI 计算卡综合排名 - 知乎](https://zhuanlan.zhihu.com/p/1982095781738586879)

**[超节点分析：ScaleX640、NVL72/144 和 Atlas 950/960 - 知乎](https://zhuanlan.zhihu.com/p/1981286769380054492)**

**[国产 “GPU 四小龙” 加速崛起：两家上市中支持 CUDA 两家仍在辅导 - 知乎](https://zhuanlan.zhihu.com/p/1982033588661818571)**

[英伟达 GPU 参数大揭秘，科研与计算利器全在这了！ - 知乎](https://zhuanlan.zhihu.com/p/1980197480093217252)

**[2025 年内存 “狂飙” 涨价超预期——深度分析幅度、持续性及驱动逻辑 - 知乎](https://zhuanlan.zhihu.com/p/1966914313626294155)**

[2025.11.28 国产 AI 计算卡参数信息汇总 - 知乎](https://zhuanlan.zhihu.com/p/1977778068450997471) [2025，国产智能算力芯片或将突破万亿市场？ - 知乎](https://zhuanlan.zhihu.com/p/1899840953348495215)

**[2025 人形机器人产业发展十大趋势 - 知乎](https://zhuanlan.zhihu.com/p/1899838388447711930)**

**[人形机器人产业链投资布局 2024，未来 2 万亿高增长市场 -](https://zhuanlan.zhihu.com/p/9551424538)  [神经蛙没头脑](https://zhuanlan.zhihu.com/p/9551424538)  [\- 知乎](https://zhuanlan.zhihu.com/p/9551424538)**

**[大模型简史：从 Transformer（2017）到 DeepSeek-R1（2025） - 神经蛙没头脑的文章 - 知乎](https://zhuanlan.zhihu.com/p/1890795558895076870)**

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-894ca87ddb83a13f64b2563c0a786def_r.jpg%3Fsource%3D1def8aca)

**[清华大学：DeepSeek 从入门到精通（2025） - 神经蛙没头脑的文章 - 知乎](https://zhuanlan.zhihu.com/p/22388497909)**

[【2025 科技参考指南】全年重磅事件一览，你绝对不能错过！ - 知乎](https://zhuanlan.zhihu.com/p/15963869366)

**[2025 年 GPU 风云再起：NVIDIA RTX 50 系列登场，RTX 5070 凭啥叫板 4090？ - 知乎](https://zhuanlan.zhihu.com/p/16912198019)**

[NVIDIA GB200 Superchip 及各厂家液冷服务器和液冷机柜介绍 - 知乎](https://zhuanlan.zhihu.com/p/14800018313)

**[【英伟达 GB300 即将登场！】从 “短命”GB200 到 “升级版”GB300，这场科技革命你必须知道！ - 知乎](https://zhuanlan.zhihu.com/p/14730798840)**

**[一文看懂英伟达 A100、A800、H100、H800 各个版本有什么区别？ - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/650583966)**

[如何制造出比英伟达更好的 GPU？ - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/694359442)

![](https://images.weserv.nl/?url=https%3A//pica.zhimg.com/v2-50b2d810cfb28b59a5904ef75f808a1f_r.jpg%3Fsource%3D1def8aca)

**[Nvidia B100/B200/GB200 关键技术解读 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/687969500)**

[大模型训练推理如何选择 GPU？一篇文章带你走出困惑（附模型大小 GPU 推荐图） - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/690523059)

**[一文看懂英伟达 A100、A800、H100、H800 各个版本有什么区别？ - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/650583966)**

[AI 核弹 B200 发布：超级 GPU 新架构 30 倍 H100 单机可训 15 个 GPT-4 模型，AI 进入新摩尔时代 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/687766952)

[紧跟 “智算中心” 这波大行情！人工智能引领算力基建革命！ - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/688145624)

[先进计算技术路线图（2023） - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/687125607)

[建议收藏！大模型 100 篇必读论文 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/687036486)

[马斯克起诉 OpenAI：精彩程度堪比电视剧，马斯克与奥特曼、OpenAI 的「爱恨纠缠史」 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/685238050)

**[生物信息学必备网站大全 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/606892605)**

**[生物信息学简史 - 知乎 (zhihu.com](https://zhuanlan.zhihu.com/p/656643985)**

**[2023 第一性原理科研服务器、量化计算平台推荐 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/663668910)**

**[Llama-2 LLM 各个版本 GPU 服务器的配置要求是什么？ - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/667446173)**

**人工智能训练与推理工作站、服务器、集群硬件配置推荐**

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-d03d943cf131560fc79d63c6d530ca69_r.jpg%3Fsource%3D1def8aca)

**整理了一些深度学习，人工智能方面的资料，可以看看**

**[机器学习、深度学习和强化学习的关系和区别是什么？ - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/645804434)**

**人工智能 (Artificial Intelligence, AI) 主要应用领域和三种形态：弱人工智能、强人工智能和超级人工智能。**

[买硬件服务器划算还是租云服务器划算？ - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/604729301)

[深度学习机器学习知识点全面总结 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/625597950)

[自学机器学习、深度学习、人工智能的网站看这里 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/618103520)

[2023 年深度学习 GPU 服务器配置推荐参考（3） - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/620749336)

![](https://images.weserv.nl/?url=https%3A//pica.zhimg.com/v2-36e9a1f05d8547a710b44bf15a0e5f72_r.jpg%3Fsource%3D1def8aca)

**多年来一直专注于[科学计算](https://www.zhihu.com/search?q=%E7%A7%91%E5%AD%A6%E8%AE%A1%E7%AE%97&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A3267072862%7D)服务器，入围政采平台，GB200、H200、H100、A100、H800、A800、L40、L40S、RTX6000 Ada**，**RTX A6000**，**[单台双路](https://www.zhihu.com/search?q=%E5%8D%95%E5%8F%B0%E5%8F%8C%E8%B7%AF&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A3267072862%7D) 256 核心服务器等。**
    
    
    
    
### 知乎用户 老板不要放香菇 发表
    
所以 Robin 当年到底干了什么🤔
    
    
    
    
### 知乎用户 深时见 2025 发表
    
旧秩序的黄昏：收过路费的恒生科技走向死局

**一、意料之中的血洗，与被撕碎的遮羞布**  
大年初八，开工第一天，恒生科技与[中概互联](https://zhida.zhihu.com/search?content_id=770675278&content_type=Answer&match_order=1&q=%E4%B8%AD%E6%A6%82%E4%BA%92%E8%81%94&zhida_source=entity)携手砸出了一个深坑，满屏惨绿。股评家们在疯狂翻找借口，他们拿着放大镜去对比[美联储](https://zhida.zhihu.com/search?content_id=770675278&content_type=Answer&match_order=1&q=%E7%BE%8E%E8%81%94%E5%82%A8&zhida_source=entity)的通胀指标，去揣测外资投行的流出报告，试图拼凑出一个所谓宏观承压的合理化解释。  

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-686a715cd472f81cadeec9956134c740_r.jpg%3Fsource%3D1def8aca)

  
这是一种极其庸俗的刻舟求剑。不要去翻那些注水的宏观研报了。其实，底牌早就亮了。正如我在[中美 AI 对决：美国人在搞工业革命，中国人在搞漕运帮会](https://link.zhihu.com/?target=https%3A//mp.weixin.qq.com/s%3F__biz%3DMzYyNDgxOTk5MA%3D%3D%26mid%3D2247483943%26idx%3D1%26sn%3Dd6481a959266fab03fef109454759703%26scene%3D21%23wechat_redirect)和[春晚机器人跳得再好，也救不了你的恒生科技](https://link.zhihu.com/?target=https%3A//mp.weixin.qq.com/s%3F__biz%3DMzYyNDgxOTk5MA%3D%3D%26mid%3D2247483970%26idx%3D1%26sn%3Dcaa72ed8209d9b82254e015333606a75%26scene%3D21%23wechat_redirect)所预演的那样：**旧时代的剧本，已经翻篇了**。（**要看资产配置建议，可以跳到最后结论**）  
回想几天前的春晚舞台，那些 KONGFU Robot，看似热闹非凡、科技感拉满。但在资本的冷眼旁观中，那不过是喂给大众的一剂安慰剂。这就如同晚清宫廷里那些精巧的西洋自鸣钟，奇技淫巧再花哨，也掩盖不了没有底层工业革命基础的虚弱。当大众还在为机器人的后空翻欢呼时，大洋彼岸落下的铡刀，已经悄然悬在了国内互联网巨头的大动脉上。  
今天这场暴跌，根本不是什么情绪杀，更不是什么短期的杀估值。这是一场最残忍、最彻底的**杀逻辑**。  
市场不是在为今天的财报投票，市场是在为这些企业未来十年的生存逻辑重新定价。旧时代的估值地基，被彻底抽干了。那些试图抄底的人，根本没有意识到，他们接住的不是带血的筹码，而是旧时代轰然倒塌的残砖碎瓦。  
**二、Claude 的屠刀：从流程红利到算力垄断**  

![](https://images.weserv.nl/?url=https%3A//pica.zhimg.com/v2-5386e8ea24765dc5f3487296d6678d67_r.jpg%3Fsource%3D1def8aca)

  
要看懂今天的血洗，不能盯着恒科的 K 线图，得看向硅谷。这一波的震源，来自于以 Claude 为代表的底层大模型。  
我在上篇文章中明确提出过一个判断：Claude 等新一代模型的跃升，将直接引发全球 AI 软件和应用层的估值大屠杀。  
为什么？因为财富创造的底层逻辑，变了。  
过去十年的科技创富神话，无论是美国的 [SaaS 软件](https://zhida.zhihu.com/search?content_id=770675278&content_type=Answer&match_order=1&q=SaaS%E8%BD%AF%E4%BB%B6&zhida_source=entity)，还是中国的各类垂直 App，**本质上赚的都是流程优化的钱**。他们就像是修了一条更快的收费公路，或者在数据流转的工厂里加装了一条更滑的传送带。**他们不生产底层智慧，他们只是信息的中间商**。  
在移动互联网时代，这种流程中介享受着极高的估值溢价。但现在，大模型的进化，撕毁了这份契约。Claude 的强大，证明了一件事：大模型正在实现端到端的暴力接管。当底层大模型足够聪明，能够直接理解用户极其模糊的需求，并瞬间生成精准的结果时，中间商没有存在的必要了。  
**大模型正在无情地吞噬一切中间商。**这不仅是技术迭代，这是一场残酷的权力重新分配。如果把整个数字科技生态比作一张电网，那么美国现在的国家战略，是集中举国资本，疯狂铸造绝对垄断的算力发电机。而全球的那些应用层软件、超级 App，在算力发电机面前，不过是五颜六色、看似精美的插线板。过去，发电机不够强，需要各种插线板来适配不同的电器。现在，发电机直接自带了万能插口。当发电机开始垄断 “电流（智能）” 的分配权时，插线板还有什么资格谈护城河？还有什么资格维持几十倍的市盈率？  
华尔街的聪明资金已经看到了这层底牌。他们意识到，**除了掌握核心算力、模型和能源的基础设施巨头，剩下的所有应用层公司，都面临着被降维收编或彻底淘汰的命运。**  
于是，大屠杀开始了。软件股的估值泡沫被无情刺破。而这把由 Claude 为代表的屠刀，顺着太平洋的洋流，精准地砍向了那些更依赖流量模式的中概股。  
**三、 恒生科技的死局——垄断流量税的穷途末路**  
把 Claude 掀起的这场应用层估值大屠杀逻辑，平移到今天的港股盘面上，一切暴跌就都有了最冷酷的解释。翻开恒生科技指数和中概互联的成分股，剥开高科技的外衣，本质上是什么？**他们是人类历史上最大的一批超级二道贩子**。  
过去二十年，中国互联网的狂飙突进，建立在一个极其特殊的历史红利上——巨大的人口基数与移动终端的普及。巨头们圈地跑马，建起了一座座高墙林立的超级 APP。  
他们一手卡住海量的用户，一手捏住无数的商家和内容创作者。这套商业模式的内核，我在《中美 AI 对决》里用过一个极其精准的比喻：漕运帮会。他们不生产水，也不生产粮，他们只是控制了运河（流量分发权）。你要过我的运河，对不起，留下买路钱（竞价排名、抽成、广告费）。  
在没有真正底层技术突破的移动互联网时代，收流量税，是地球上最赚钱的生意。但 AGI 的降临，直接掀翻了这条运河。当一个普通人，可以通过一个类似 Claude 的大模型入口，用自然语言直接完成比价、订票、数据分析、内容生成，甚至编写代码时，他为什么还要去打开那几十个臃肿不堪、充满诱导广告的超级 APP？  

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-42a12d12b1124994fd2f8846ae2ad0c8_r.jpg%3Fsource%3D1def8aca)

  
**大模型不仅在吃掉中间商，大模型正在成为人类进入数字世界的唯一入口。当入口发生转移，超级 APP 的护城河瞬间干涸。这就是恒生科技暴跌的底层真相——市场看穿了他们流量垄断权的丧失。**  
很多散户看着市盈率只有 20 倍了，估值太低了，认为该抄底了。这是一种极其致命的幻觉。市盈率的本质，是市场对你未来现金流折现的预期。当大模型这种工业革命级别的降维打击到来时，你原来收流量税的那个收费站，马上就要没有车经过了。你的未来没有增长预期了，你赚的每一分钱都成了存量博弈里的残羹冷炙。低估值，不是因为错杀，是因为市场在为他们护城河被彻底填平重新定价。  
**四、大国博弈的暗线——谁在主导这场估值重构？**  
如果你以为今天的暴跌，仅仅是科技路线的更迭，那格局还是太小了。跳出 K 线图，把视线拉高到全球宏观的绞肉机里，你会发现一条令人胆寒的暗线。  
这不仅是一场技术战，这是一场配合得天衣无缝的金融歼灭战。看一眼大洋彼岸在干什么。一方面，美联储死死咬住高息不放，一次次推迟降息预期。接近 5% 的无风险收益率，像一台超级抽水机，将全球的流动性无情抽干。另一方面，硅谷和华尔街联手，用极具想象力的 AI 基础设施（如[算力芯片](https://zhida.zhihu.com/search?content_id=770675278&content_type=Answer&match_order=1&q=%E7%AE%97%E5%8A%9B%E8%8A%AF%E7%89%87&zhida_source=entity)、超级大模型），打造了一个巨大的资本蓄水池。  
这叫什么？**这叫算力本位取代[美元本位](https://zhida.zhihu.com/search?content_id=770675278&content_type=Answer&match_order=1&q=%E7%BE%8E%E5%85%83%E6%9C%AC%E4%BD%8D&zhida_source=entity)的阳谋**。在全球资金贵到离谱的今天，钱只会流向一种地方：拥有绝对技术霸权、能定义下一个时代的底层资产。如果你点错了科技树，代价是毁灭性的。  
当美国人在疯狂堆叠算力集群，试图用机器替代人类的脑力劳动时；我们这边的互联网巨头，还在干什么？  
在存量搏杀的残酷世界里，没有底层核心技术的资产，注定只能沦为金融战中的血包。最近恒科的暴跌，就是聪明资金在用脚投票。他们看清了中国互联网巨头的底牌——在彻底失去增量人口红利后，面对大模型的降维打击，这些昔日的巨无霸，既没有能力去大洋彼岸卷底层算力，也没有能力在全球宏观收缩中保住自己高昂的利润率。他们只能在内卷的泥潭里互相撕咬，看着自己的估值体系被一点点拆解。  
这不是恐慌，这是全球资本在冷酷地执行一次资产置换——卖出旧时代的流量收租婆，买入新时代的算力发电机。  
**五、旧船票登不上新大陆**  
别再相信 “别人恐惧我贪婪”、“越跌越买” 的陈词滥调。这是一种极度危险的路径依赖。很多人用过去二十年积累的投资经验，试图去刻舟求剑地丈量一个全新时代的深渊。  
**请记住：当一个时代的底层逻辑被彻底重写时，旧体系里的估值锚，一文不值。**  

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-f901372939adc366dcf984e4ecc312f0_r.jpg%3Fsource%3D1def8aca)

  
马车再便宜，也打不过昂贵的内燃机。工业革命不会因为漕运帮会降价了，就停止它的车轮。恒生科技和中概互联的持续下跌，绝不是什么技术性调整，更不是什么情绪错杀。这是全球资本在进行一次彻底的出清与置换。那些曾经垄断了你衣食住行、靠着收流量税躺赚千亿的互联网巨头，正在被大模型无情地剥夺定义未来的权力。他们的商业壁垒，在算力发电机面前，脆如薄纸。  
放弃幻想吧。不要用你辛苦积累的真金白银，去试图接住一把加速坠落的飞刀。在旧秩序轰然崩塌的巨震中，聪明资金早已完成了战略转移。  
未来的财富，不再属于那些在存量里搞流量变现的二道贩子。真正的核心资产，只剩下三类：  
1、**绝对的算力霸权与基础设施**： 那些真正掌握大模型底层架构，以及为大模型提供核心硬件支撑的 “卖水人”。  
2、**吞噬一切的能源底座**：AI 的尽头是能源。当算力成为国家战略资源时，能够稳定、廉价供应电力的基建，将迎来不可思议的价值重估。  
3、**脱钩时代的终极防御资产**：在地缘撕裂和高息绞肉机中，那些彻底脱离旧信用体系、无法被轻易冻结的硬通货（黄金肯定算），才是财富真正的防弹衣。  
不要再对那些即将被时代抛弃的巨头抱有温情。时代抛弃你时，连一声再见都不会说，只会留下一根长长的阴线。
    
    
    
    
### 知乎用户 福瑞 lancer 发表
    
2 月 23 日，[Anthropic](https://zhida.zhihu.com/search?content_id=770834882&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 发了一篇博客，标题很克制——” 检测与防范蒸馏攻击”。

内容很不克制——直接点名 [DeepSeek](https://zhida.zhihu.com/search?content_id=770834882&content_type=Answer&match_order=1&q=DeepSeek&zhida_source=entity)、[月之暗面](https://zhida.zhihu.com/search?content_id=770834882&content_type=Answer&match_order=1&q=%E6%9C%88%E4%B9%8B%E6%9A%97%E9%9D%A2&zhida_source=entity)（Kimi 的母公司）和 [MiniMax](https://zhida.zhihu.com/search?content_id=770834882&content_type=Answer&match_order=1&q=MiniMax&zhida_source=entity)，说这三家公司通过大量账号与 [Claude](https://zhida.zhihu.com/search?content_id=770834882&content_type=Answer&match_order=1&q=Claude&zhida_source=entity) 进行了超过 1600 万次对话，用来蒸馏 Claude 的能力。

消息一出，中美 AI 又吵成一团。但有几个细节值得先留意：

Anthropic 的 CEO [Dario Amodei](https://zhida.zhihu.com/search?content_id=770834882&content_type=Answer&match_order=1&q=Dario+Amodei&zhida_source=entity) 两周前刚去国会山游说收紧芯片出口管制。[OpenAI](https://zhida.zhihu.com/search?content_id=770834882&content_type=Answer&match_order=1&q=OpenAI&zhida_source=entity) 在 11 天前向国会提交了指控 DeepSeek 的备忘录。Google 同期也披露了 [Gemini](https://zhida.zhihu.com/search?content_id=770834882&content_type=Answer&match_order=1&q=Gemini&zhida_source=entity) 遭受 10 万条 prompt 克隆攻击的报告。三家美国头部 AI 公司，近乎同步行动。

**但到今天，没有任何一家提起法律诉讼。**

如果这真的是知识产权盗窃，为什么不走法律途径？

在地缘政治的噪音之外，Anthropic 公布的数据本身藏着一个更有意思的信号。而这个信号，比” 谁指控了谁” 重要得多。

* * *

### 一、” 蒸馏” 到底算不算偷？这个问题没那么简单

先厘清一个基本概念：蒸馏（distillation）是 AI 行业的一项成熟技术——用强模型的输出来训练弱模型。Anthropic 自己也在博客里承认，”AI 公司经常蒸馏自己的模型来创建更小、更便宜的版本。”

区别在于，这次是别人蒸馏你的模型。

但这里有一个灰色地带：这些对话发生在 Claude 的公开 API 或产品端。换句话说，从技术层面看，这些公司是在**付费使用一个商业产品，收集产品的输出**。这和” 入侵系统窃取源代码” 是完全不同的性质。

新加坡南洋理工大学 AI 教授 Erik Cambria 接受 CNBC 采访时说了一句很中肯的话：” 合法使用与对抗性利用之间的界限，往往是模糊的。”

更微妙的是 Anthropic 自身的记录。不久前法院解封了一批文件，揭露了 Anthropic 的” 巴拿马计划”——公司花了数千万美元从二手书商购买数十万至上百万本书，用液压切割机切开书脊高速扫描，扫完后把纸质书回收销毁。联合创始人 Ben Mann 还在 2021 年从盗版图书库 LibGen 下载书籍。最终 Anthropic 以约 15 亿美元和解了版权诉讼。

马斯克在 Anthropic 发布指控后几个小时内就在 X 上开火：”Anthropic 自己就犯有大规模窃取训练数据的罪行。”

你花数千万买书、切书、扫描然后销毁，这叫” 构建训练数据”；别人通过你的公开 API 付费调用、收集输出，这叫” 蒸馏攻击”？

这里不是要替谁辩护——大规模、系统性地蒸馏商业模型，确实游走在合理使用的边缘。但把它等同于” 盗窃”，然后在国会听证的时间窗口精准发布，配合芯片出口管制的游说节奏——这更像是一场**定义权之争**，而不是单纯的技术对抗。

RLHF 研究者 [Nathan Lambert](https://zhida.zhihu.com/search?content_id=770834882&content_type=Answer&match_order=1&q=Nathan+Lambert&zhida_source=entity) 的分析更直接：”Anthropic 把 DeepSeek 放在博客最前面，是因为 DeepSeek 在美国是中国 AI 的代名词。” 从数据看，DeepSeek 的 15 万次交互占总量不到 1%，Lambert 的原话是”rounding error”（可忽略不计）。但在传播策略上，DeepSeek 这个名字最有价值。

与其在” 算不算偷” 上打转，不如看看 Anthropic 自己公布的数据到底在说什么。

* * *

### 二、数据里真正有意思的信号：所有人都在押注 Agent

Anthropic 在博客里详细列出了三家公司各自的蒸馏目标。把这组数据拆开看：

**DeepSeek**：15 万次对话，目标是跨任务推理能力。手法精准——prompt 要求 Claude” 逐步阐述完成回答背后的内部推理过程”，本质是提取 chain-of-thought 训练数据。

**月之暗面（Kimi）**：340 万次对话，目标是智能体推理（agentic reasoning）、工具使用（tool use）、代码编写和计算机操作。

**MiniMax**：1300 万次对话，目标是智能体编码（agentic coding）和工具编排（tool orchestration）。

注意到了吗？**三家公司不约而同瞄准的，不是” 聊天” 能力，而是”Agent” 能力。** 工具使用、任务规划、代码执行、自主操作——全是” 做事” 的能力。

MiniMax 的动作尤其值得注意：每当 Anthropic 发布新模型，MiniMax 在 24 小时内就把近一半流量切换到新模型上。这不是盲目的数据搬运——这说明它们对 Agent 能力的技术演进有清晰的追踪和判断。

Nathan Lambert 也指出，随着强化学习（RL）在模型训练中的主导地位越来越强，” 蒸馏正在变得不那么重要”。换句话说，通过蒸馏获得的能力增量在递减，而中国 AI 公司自身的技术积累在加速——DeepSeek R1 的推理能力、MiniMax M2.5 在 SWE-Bench 上 80.2% 的得分，这些不是靠蒸馏能” 偷” 出来的。

但这组数据最有价值的信号不在于谁蒸馏了谁，而在于它客观上揭示了一个全球共识：

**AI 竞赛的核心已经从” 谁更能聊” 转移到了” 谁更能做事”。**

中国公司精确押注 Agent 方向，说明它们对技术趋势的判断是准确的。美国公司发布的每一个新模型都在强调 Agent 能力，也在印证同一件事。双方路径不同，但终点一致。

* * *

### 三、通用能力终将被拉平，私有知识才是护城河

既然 Agent 能力是兵家必争之地，那是不是掌握了最强 Agent 技术的公司就赢了？

没那么简单。

我在做自己的 AI Agent 过程中发现了一个规律：大模型在” 大家都会遇到的问题” 上表现很好——写 Python、解释 API 文档、生成 SQL，信手拈来。但一旦进入具体的业务场景，它就开始瞎编。

比如我让 Agent 帮我处理一个内部审批流程，它给出的方案看起来合理，但完全不符合实际规则。原因很简单：这类知识从未出现在训练数据里。

大模型公司——不管是中国的还是美国的——能收集到的只有公有知识：互联网上公开的、被大量人讨论过的信息。通用推理能力、编码能力、工具调用模式，这些都属于公有知识的范畴，迟早会被所有头部模型拉平，不管是通过自研、蒸馏还是开源。

**而真正决定一个 Agent 能不能在你的场景里落地的，是私有知识：你的工作流程、你的判断偏好、你处理特定事务的规则和习惯。**

这些知识场景太小、太个人化，不可能被任何大模型公司收集到。

你的日程安排习惯、你处理不同邮件的优先级规则、你审批文档时关注的重点、你和同事协作的默契——这些东西只存在于你的使用过程中。

这就是为什么 Notion 上周发布 Custom Agents 之后反响这么大——不是因为它背后的 AI 模型有多强（用的是第三方模型），而是因为 Notion 天然拥有用户的私有知识：你的笔记、你的文档、你的项目结构。当 AI 能直接调用这些私有知识时，它就不再是一个通用工具，而是一个真正懂你的助手。

**通用 Agent 能力可以被追赶、被对齐、甚至被蒸馏——但让 Agent 真正对你有用的那部分，只能由你自己喂进去。**

* * *

### 收束

1600 万次对话的风波还会继续发酵。指控也好，回应也好，国会听证也好——这场大戏短期内不会落幕。

但对于关注 AI 发展的人来说，与其纠结谁蒸馏了谁，不如看清两件事：

**第一，Agent 是 AI 的下一个主战场。** 中国公司和美国公司都已用行动确认了这一点——区别只在路径，共识在方向。

**第二，在这个新战场上，通用模型能力终将被拉平。** 拉平的方式有很多——自研、开源、蒸馏、强化学习——但结果是一样的：基础 Agent 能力会变成水电煤一样的基础设施。

而真正稀缺的，是你花时间喂给 AI 的私有知识，你在使用过程中沉淀下来的个人数据。这些东西不在任何一家公司的模型参数里，也不可能被 1600 万次对话提取出来。

**这才是个人 AI 助手真正的护城河。不在模型那端，在你这端。**

* * *

### 本文事实

| 序号 | 事实描述 | 搜索来源 | 原始出处 | 验证状态 | 验证方法 |
| --- | --- | --- | --- | --- | --- |
| 1 | Anthropic 于 2026 年 2 月 23 日发布博客”Detecting and preventing distillation attacks”，点名 DeepSeek、Moonshot AI、MiniMax | 多家媒体 | Anthropic 官方博客 [https://www.anthropic.com/news/detecting-and-preventing-distillation-attacks](https://link.zhihu.com/?target=https%3A//www.anthropic.com/news/detecting-and-preventing-distillation-attacks) | 已验证 | 官方网站核实 |
| 2 | 三家公司共创建约 24,000 个假账号 | CNBC/TechCrunch/CNN | Anthropic 博客原文 | 已验证 | 官方博客 + 多家独立媒体交叉验证 |
| 3 | 总交互次数超过 1,600 万次 | 同上 | Anthropic 博客原文 | 已验证 | 同上 |
| 4 | DeepSeek：超过 150,000 次交互，目标为推理能力和 chain-of-thought | CNBC/VentureBeat | Anthropic 博客 | 已验证 | 多源交叉验证 |
| 5 | Moonshot AI：超过 340 万次交互，目标为智能体推理 (agentic reasoning)、工具使用 (tool use)、计算机使用 | 同上 | Anthropic 博客 | 已验证 | 多源交叉验证 |
| 6 | MiniMax：超过 1,300 万次交互，目标为智能体编码 (agentic coding)、工具编排 (tool orchestration) | 同上 | Anthropic 博客 | 已验证 | 多源交叉验证 |
| 7 | MiniMax 在 Anthropic 发布新模型后 24 小时内将近一半流量重定向至新模型 | VentureBeat | Anthropic 博客 | 已验证 | 多源交叉验证 |
| 8 | Anthropic 检测方法包括行为指纹系统 (behavioral fingerprinting)、实体解析、异常指标分析 | The Hacker News/Dev.to | Anthropic 博客 | 已验证 | 官方博客技术细节 |
| 9 | 单一代理网络同时管理超过 2 万个账户（” 九头蛇架构”）将蒸馏请求与正常商业流量混合 | VentureBeat | Anthropic 博客 | 已验证 | 官方博客 + 独立分析 |
| 10 | OpenAI 于 2 月 12 日向众议院中国问题特别委员会提交备忘录指控 DeepSeek | Bloomberg | Bloomberg 原文 | 已验证 | Bloomberg + 多家媒体转载 |
| 11 | Google 威胁情报组 (GTIG)2 月 12 日披露 Gemini 遭受超过 10 万条 prompt 的蒸馏攻击 | NBC News | NBC News/Dataconomy | 已验证 | 两个独立来源 |
| 12 | 截至 2 月 26 日，DeepSeek、月之暗面、MiniMax 均未公开回应指控 | CNN/CNBC | 多家媒体确认” 未回复评论请求” | 已验证 | 多源交叉验证 |
| 13 | 截至 2 月 26 日无任何一家美国公司就蒸馏提起法律诉讼 | 多家媒体 | 无诉讼记录 | 已验证 | 多源确认无诉讼报道 |
| 14 | Nathan Lambert 评价 DeepSeek 用量为”rounding error”（可忽略），MiniMax 为”substantial”（实质性的） | Interconnects Newsletter | [https://www.interconnects.ai/p/how-much-does-distillation-really](https://link.zhihu.com/?target=https%3A//www.interconnects.ai/p/how-much-does-distillation-really) | 已验证 | 原作者一手来源 |
| 15 | Anthropic “巴拿马计划”：花费数千万美元购买并切割扫描数十万至两百万本书用于训练，以约 15 亿美元和解版权诉讼 | Washington Post | 法院解封文件 | 已验证 | 法院文件 + Washington Post 独立报道 |

### 引语与归因

| 序号 | 引语内容 | 说话人 | 场合 / 时间 | 原始来源链接 | 是否原话 |
| --- | --- | --- | --- | --- | --- |
| 1 | “DeepSeek’s usage was a rounding error. MiniMax’s was substantial.” | Nathan Lambert（RLHF 研究者、Interconnects 作者） | 2026 年 2 月博客分析 | [https://www.interconnects.ai/p/how-much-does-distillation-really](https://link.zhihu.com/?target=https%3A//www.interconnects.ai/p/how-much-does-distillation-really) | 原话 |
| 2 | “Anthropic put DeepSeek first in their blog post because they’re the household name in the US for Chinese AI.” | Nathan Lambert | 同上 | 同上 | 原话 |
| 3 | “Anthropic is guilty of stealing training data at massive scale” | Elon Musk | 2026 年 2 月 X/Twitter | Yahoo Finance 转载 | 原话 |
| 4 | “The boundary between legitimate use and adversarial exploitation is often blurry.” | Erik Cambria（新加坡南洋理工大学 AI 教授） | 接受 CNBC 采访 | CNBC 2026-02-24 | 原话 |

### 数据与统计

| 序号 | 数据内容 | 数据来源机构 | 数据时效 | 原始出处链接 | 验证状态 |
| --- | --- | --- | --- | --- | --- |
| 1 | 约 24,000 个假账号 | Anthropic | 2026-02-23 | Anthropic 博客 | 已验证 |
| 2 | 超过 1,600 万次交互 | Anthropic | 2026-02-23 | Anthropic 博客 | 已验证 |
| 3 | DeepSeek 150,000 + 次 / Moonshot 340 万 + 次 / MiniMax 1,300 万 + 次 | Anthropic | 2026-02-23 | Anthropic 博客 | 已验证 |
| 4 | MiniMax 占总交互量约 81% | 根据 Anthropic 数据计算 | 2026-02-23 | 计算所得 | 已验证 |
| 5 | Nathan Lambert 估算 MiniMax+Moonshot 产生 1,500 亿至 4,000 亿 token | Nathan Lambert | 2026-02-24 | Interconnects | 已验证 |
    
    
    
    
### 知乎用户 若宸 发表
    
贼喊捉贼罢了

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-f86bcc2d0829734a5df7083b5c2bd683.jpg%3Fsource%3D25ab7b06)
    
    
    
    
### 知乎用户  AI 观读记 发表
    
2026 年 2 月 23 日，[Anthropic](https://zhida.zhihu.com/search?content_id=770650712&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 发布了一篇博客文章《Detecting and Preventing Distillation Attacks》，直接点名指控三家中国 AI 实验室（[DeepSeek](https://zhida.zhihu.com/search?content_id=770650712&content_type=Answer&match_order=1&q=DeepSeek&zhida_source=entity)、[Moonshot AI](https://zhida.zhihu.com/search?content_id=770650712&content_type=Answer&match_order=1&q=Moonshot+AI&zhida_source=entity)、[MiniMax](https://zhida.zhihu.com/search?content_id=770650712&content_type=Answer&match_order=1&q=MiniMax&zhida_source=entity)）对其 [Claude 模型](https://zhida.zhihu.com/search?content_id=770650712&content_type=Answer&match_order=1&q=Claude+%E6%A8%A1%E5%9E%8B&zhida_source=entity)发动了 "工业规模的蒸馏攻击"，以如此公开、如此具体的方式，将 "技术窃取" 的指控落到具体的中国 AI 研究机构头上。

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-fb17fb92183a7ca53e88795a9f509e68_r.jpg%3Fsource%3D1def8aca)

这篇报告在国内外迅速引发了大范围讨论，包括 Elon Musk 等也站出来表达自己的观点。一时间，"蒸馏" 这个原本只在机器学习从业者中流通的术语，出现在了各路财经和政治评论里。

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-1a10c8b56cc790d71f0a3de0667caaa5_r.jpg%3Fsource%3D1def8aca)

在此背景下，[Allen Institute for AI](https://zhida.zhihu.com/search?content_id=770650712&content_type=Answer&match_order=1&q=Allen+Institute+for+AI&zhida_source=entity) 高级研究员 [Nathan Lambert](https://zhida.zhihu.com/search?content_id=770650712&content_type=Answer&match_order=1&q=Nathan+Lambert&zhida_source=entity) 在 2 月 25 日发布了一篇博客文章《How much does distillation really matter for Chinese LLMs?》，回应 Anthropic 近日发布的关于 "蒸馏攻击" 的指控报告，从笔者视角来看是相对较为专业且客观的。Lambert 在文中逐层剖析了蒸馏的技术本质、Anthropic 披露的具体数据，以及这场争论背后真正值得关注的地缘政治逻辑。他的结论比较克制：**这件事的象征意义远大于实际技术威胁。**

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-389ec793bb939aada9aea8d65122177b_r.jpg%3Fsource%3D1def8aca)

博客原链接：[https://www.interconnects.ai/p/how-much-does-distillation-really](https://link.zhihu.com/?target=https%3A//www.interconnects.ai/p/how-much-does-distillation-really)

### **作者背景**

Nathan Lambert 是 Allen Institute for AI（Ai2）的高级研究科学家，负责语言模型的后训练（post-training）研究，主导了 OLMo、Tülu 2 & 3、RewardBench 等一系列有影响力的开源工作，并撰写了业内首部关于强化学习人类反馈（RLHF）的教材。他在 UC Berkeley 取得博士学位，曾在 FAIR 和 DeepMind 实习，后在 Hugging Face 主导搭建了 RLHF 团队。他运营的 Substack 时事通讯 Interconnects AI 以技术深度和去除噪音见长，读者群体涵盖工程师、研究员和投资人。

* * *

### **蒸馏是什么，为何争议持续不断**

"蒸馏"（distillation）在当前 AI 讨论中是一个含义颇为宽泛的词。它的技术根源来自 Hinton、Vinyals 和 Dean 于 2015 年提出的[知识蒸馏](https://zhida.zhihu.com/search?content_id=770650712&content_type=Answer&match_order=1&q=%E7%9F%A5%E8%AF%86%E8%92%B8%E9%A6%8F&zhida_source=entity)（knowledge distillation），核心是让学生模型去拟合教师模型的概率分布输出。但今天语境下的 "蒸馏"，已基本等同于**[合成数据](https://zhida.zhihu.com/search?content_id=770650712&content_type=Answer&match_order=1&q=%E5%90%88%E6%88%90%E6%95%B0%E6%8D%AE&zhida_source=entity)**（synthetic data）：调用一个更强模型的 API，收集其输出，再用这些输出来训练自己的模型。

Lambert 直接点明了这一区分的重要性：**从 API 模型做技术意义上的知识蒸馏是不可能的，因为 API 并不暴露模型的内部概率分布**。而调用 API 收集输出、再用于训练，是当前研究中极为普遍的做法，Lambert 把它称为他日常工作中 "最有用的单一方法"。架构固然重要，可验证奖励的强化学习也在改变行业，但每天占据 AI 研究者大量精力的，是如何正确获取和扩展合成数据。

围绕中国实验室是否通过蒸馏 "窃取" 美国模型能力的争论由来已久。最典型的案例发生在 DeepSeek R1 发布前后，[OpenAI](https://zhida.zhihu.com/search?content_id=770650712&content_type=Answer&match_order=1&q=OpenAI&zhida_source=entity) 指控 DeepSeek 通过破解 API 的方式获取了其推理链（reasoning trace）。这也可能是 [Gemini](https://zhida.zhihu.com/search?content_id=770650712&content_type=Answer&match_order=1&q=Gemini&zhida_source=entity) 随后迅速关闭推理链可见性的原因之一，尽管早期有研究就是构建在 Gemini 输出之上的。

### **Anthropic 的指控：数字背后的真实影响**

Anthropic 在其报告中点名了三家中国实验室，**DeepSeek、Moonshot AI 和 MiniMax**，指控它们通过约 24,000 个虚假账号发起了 "工业规模的蒸馏行动"，共生成超过 1,600 万次对话。报告将此定性为 "非法提取 Claude 能力"。值得注意的是，Anthropic 并未明确证实这些交互是通过 API、网页端 Chat 还是 Claude Code 进行的，这一定性细节上的模糊，使得外界对实际操作规模和方式的判断存在一定局限。

Lambert 则从技术角度对每家实验室的实际使用量做了更冷静的评估。

### **DeepSeek：150,000 次交互，影响微乎其微**

Anthropic 在报告中将 DeepSeek 放在首位，但 Lambert 认为这更多是因为品牌知名度，而非实际规模：

**规模：超过 150,000 次交互**

具体使用方向包括：

*   跨任务的推理能力
*   基于评分标准（rubric）的评测任务，让 Claude 充当强化学习的奖励模型
*   生成政策敏感查询的审查安全替代

Lambert 的判断很直接：在语言模型训练的尺度上，15 万条样本只是一个初步实验，连皮毛都算不上。他推测这可能是 DeepSeek 某个小团队的尝试，大概率与核心训练组织无关。**这些数据对 DeepSeek 下一个主力模型的影响可以忽略不计。**

### **Moonshot AI 和 MiniMax：量级完全不同**

另外两家实验室的情况则差异明显：

**Moonshot AI（Kimi 的制造商）**

*   规模：超过 **340 万次**交互
*   聚焦方向：智能体推理与工具调用、代码与数据分析、计算机使用智能体开发、计算机视觉

**MiniMax**

*   规模：超过 **1,300 万次**交互
*   聚焦方向：智能体编程、工具调用与编排

Lambert 指出，对 Claude 的智能体行为进行蒸馏，在当前时间点具有相对较高的价值，Claude Opus 4.6 在智能体导航方面表现突出，其他模型尚未完全追上。但他同时强调，这种差异会随着时间推移缩小，"就像今天的模型在数学上早就超出了大多数人的需求一样，可供蒸馏的来源会越来越多"。

从数量上估算，若每次交互平均包含 1 万至 2.5 万个 token，两家实验室（主要是 MiniMax）的总 token 量约为 **1,500 亿至 4,000 亿**。Lambert 以 OLMo 3 项目为参照：他们的 SFT 数据集约为 200 亿 token，这个量级十倍于此并非不可想象。

### **蒸馏的 "锯齿状" 收益：为什么影响难以衡量**

Lambert 引用了 Anthropic 报告中的一个关键表述，**蒸馏的收益是 "锯齿状的"（jagged）**，他认为这个描述相当准确。

对于某些特定能力，如果实验室本身还没有完整的训练管线，快速蒸馏前沿模型在该领域的输出可以带来显著提升。但把 Claude 的输出加进自己的训练管线，并不是一件容易的事。研究社区已有大量案例表明，**使用某个教师模型的输出训练学生模型，有时反而会让学生模型变差**，**数据之间的微妙交互使得这类蒸馏既不稳定，也难以预测。这从根本上是一个研究问题，而不仅仅是工程问题。**

Lambert 认为，中国实验室在这类蒸馏的方法论上确实有可能存在显著创新，尤其是在 GPU 资源受限的背景下，调用 API 模型是少数可以等效替代算力的方式之一。获取被 "禁止" 的 API 访问权限，远比走私数万张物理 GPU 并完成部署容易得多。

### **不只是中国实验室在做这件事**

Lambert 在文中特别强调了一个常被忽略的视角：**使用你不拥有的模型生成的合成数据，从广义上说都算蒸馏。这不是中国实验室独有的做法。**

他以 OLMo 3 项目为例：团队在 Frontier 超算和 NAIRR 提供的 Azure 算力上投入了数百万 GPU 小时来生成合成数据。对于没有等量 GPU 资源的研究者和机构，API 是一个天然的、按需付费的替代方案，风险更低，灵活性更高。

"蒸馏是任何人获取更多算力的捷径。它也是一种风险低得多的成本，因为维持大规模计算集群需要巨大的财务承诺，而 API 是按使用量付费的。"

### **强化学习时代的蒸馏边界**

Lambert 提出了一个更深层的技术论点，这也是他认为这场争论会逐渐降温的核心原因：

**在当前 RL 大规模训练的范式下，蒸馏的边界变得更加清晰。** 训练最好模型的关键在于大规模的同策略强化学习（on-policy RL），而这部分推理计算，无法通过调用另一个模型的 API 来替代。你必须用自己的模型在线生成。RL 训练中的推理成本是主导成本，这是蒸馏无法覆盖的部分。

与此同时，他也指出了一个积极信号：从公开的研究来看，中国实验室的 RL 基础设施相当扎实，并不依赖外部数据来弥补根本性的短板。

Lambert 还补充了一个常被忽视的反驳：认为 "依赖蒸馏的一方永远无法超越被蒸馏的模型"，这一判断本身站不住脚。他举了一个来自 Anthropic 内部的例子：Claude Sonnet 正是通过蒸馏 Opus 的数据训练而来，却在某些阶段确实超越了体量更大的 Opus。只要拥有快速迭代能力和高质量数据，学生超越老师并非没有先例，尽管这取决于发布节奏，而随着 AI 模型的快速演进，这类看似反常的事情已经真实发生过。

### **这场争论的真实性质：地缘政治 vs. 技术威胁**

Lambert 对此事的定性是：这是地缘政治紧张局势的一次升级，而非一个急迫的技术危机。

"不允许为'竞争目的'蒸馏模型" 这条服务条款，其实已经在美国 API 模型的协议中存在相当长时间了。2022 年至 2023 年间，美国的学术界和开源社区对此有大量讨论和顾虑（Lambert 本人也多次撰文）。到 2024 年，这一顾虑在社区内基本消退，没有任何小型模型开发者因此受到追究。

他认为，从实际效果上看，**限制蒸馏远比限制 GPU 出口要难**。通过分布式访问方式进行蒸馏，在技术上几乎无法完全封堵；而限制 GPU 出口对中国实验室整体训练能力的影响，会大得多也直接得多。

Lambert 最后给出了一个 “推演”：**当 API 端点对外开放时，其他主体必然会用它来训练自己的模型变体，这是 AI 模型自然演化的一部分。如果蒸馏真的是极端风险，那最终的结论只能是把最新模型完全锁在第一方产品内，不再提供 API。但没有哪家领先实验室会轻易走回这条路，因为 API 是其商业模式的核心组成部分。**

* * *

### **小结**

这篇博客为理解 "中国大模型是否依赖蒸馏美国模型" 这一问题，提供了比较扎实的技术视角。Lambert 的核心立场是：Anthropic 的担忧有一定合理性，但实际影响被高估了，DeepSeek 的使用量几乎可以忽略，Moonshot 和 MiniMax 的量级更大但研究问题尚未解决；更重要的是，在 RL 驱动的后训练范式下，蒸馏本身的边界正在收窄。

这场争论更值得关注的，或许是它所揭示的行业走向：如何在商业开放和能力保护之间找到平衡，将是未来一段时间内这个行业持续面对的结构性问题。

此外，Anthropic 此次点名道姓的指责行为配得上这个作茧自缚的讽刺图：

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-0b3b2ea1dfe430706aad7ceb12a49b24_r.jpg%3Fsource%3D1def8aca)

这张图在讽刺的是：Anthropic 一边靠 “薅全互联网的数据” 训练自己的模型，一边又高调指责别的模型 “侵犯它们的版权 / 模型权益”，等于只给大模型本身设立了一套“只准州官放火，不许百姓点灯” 的版权逻辑。

如果您觉得有收获，欢迎关注公众号 “**AI 观读记**”，共同思考 **AI 时代的生存与成长之道。**

* * *
    
    
    
    
### 知乎用户 AlicNzefc 发表
    
底下已经变成了一个政治问题
    
    
    
    
### 知乎用户 知乎用户 k7j47 发表
    
遥想当年，手机的[弧角](https://zhida.zhihu.com/search?content_id=770623575&content_type=Answer&match_order=1&q=%E5%BC%A7%E8%A7%92&zhida_source=entity)，都可以拿来当成侵权来起诉。老美老双标了，感谢你的严选。
    
    
    
    
### 知乎用户 绿豆沙冰 发表
    
婊子立牌坊
    
    
    
    
### 知乎用户 太行太行 发表
    
美版的爱国营销
    
    
    
    
### 知乎用户 精神病院王主任 发表
    
闭源 AI 必死
    
    
    
    
### 知乎用户  G 铌钛镁 发表
    
[达利特](https://zhida.zhihu.com/search?content_id=770660469&content_type=Answer&match_order=1&q=%E8%BE%BE%E5%88%A9%E7%89%B9&zhida_source=entity)的苦行不是苦行
    
    
    
    
### 知乎用户 渺沧海之一粟 发表
    
这下明白了为何美国[五角大楼](https://zhida.zhihu.com/search?content_id=770686876&content_type=Answer&match_order=1&q=%E4%BA%94%E8%A7%92%E5%A4%A7%E6%A5%BC&zhida_source=entity)和国防部长皮特 · 赫格塞斯要求 [Anthropic](https://zhida.zhihu.com/search?content_id=770686876&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 放宽其军事用途的使用限制了。

据路透社 2026 年 2 月 24 日的报道。一位知情人士周二表示，人工智能实验室 Anthropic 无意放宽其军事用途的使用限制，并补充说，在与五角大楼讨论其未来事宜的会面后，谈判仍在继续。

Anthropic 首席执行官[达里奥 · 阿莫代伊](https://zhida.zhihu.com/search?content_id=770686876&content_type=Answer&match_order=1&q=%E8%BE%BE%E9%87%8C%E5%A5%A5%C2%B7%E9%98%BF%E8%8E%AB%E4%BB%A3%E4%BC%8A&zhida_source=entity)与美国国防部长皮特 · 赫格塞斯的会面原定用于解决一场持续数月的争议。这家人工智能初创公司拒绝取消防止其技术被**用于自主打击武器和进行美国国内监控**的[防护措施](https://link.zhihu.com/?target=https%3A//www.reuters.com/business/pentagon-clashes-with-anthropic-over-military-ai-use-2026-01-29/)。

知情人士称，会议期间，赫格塞斯向 Anthropic 发出最后通牒：要么加入，要么政府采取激烈行动。据人士称，这些选项包括将 Anthropic 标记为供应链风险，或让五角大楼援引一项名为[《国防生产法》](https://zhida.zhihu.com/search?content_id=770686876&content_type=Answer&match_order=1&q=%E3%80%8A%E5%9B%BD%E9%98%B2%E7%94%9F%E4%BA%A7%E6%B3%95%E3%80%8B&zhida_source=entity)的法律，强制 Anthropic 修改其规则。

据一位知情的五角大楼高级官员透露，政府给了 Anthropic 直到周五下午 5 点作出回应的时间。

**五角大楼一直在与多家大型语言模型（LLM）提供商谈判人工智能合同，其中包括 [Alphabet](https://zhida.zhihu.com/search?content_id=770686876&content_type=Answer&match_order=1&q=Alphabet&zhida_source=entity) 的[谷歌](https://zhida.zhihu.com/search?content_id=770686876&content_type=Answer&match_order=1&q=%E8%B0%B7%E6%AD%8C&zhida_source=entity)、[xAI](https://zhida.zhihu.com/search?content_id=770686876&content_type=Answer&match_order=1&q=xAI&zhida_source=entity) 和 [OpenAI](https://zhida.zhihu.com/search?content_id=770686876&content_type=Answer&match_order=1&q=OpenAI&zhida_source=entity) 的合作**，**这些项目将塑造人工智能在战场应用的军事应用，涵盖自主无人机群、机器人和网络攻击。**

直到最近，Anthropic 是唯一一家在机密网络上提供 LLM 的供应商。本周，五角大楼宣布已与 xAI 达成协议，将该技术部署至机密网络。路透社此前报道称，计划将所有人工智能公司转移到机密网络。

五角大楼与 Anthropic 的争斗在本月初达到高峰，当时他们担心该公司在委内瑞拉军事突袭中质疑其人工智能产品的使用情况，该突袭俘获了尼古拉斯 · 马杜罗总统。

消息人士称，在与赫格塞斯的会面中，阿莫代伊表示，**Anthropic 并未向 [Palantir](https://zhida.zhihu.com/search?content_id=770686876&content_type=Answer&match_order=1&q=Palantir&zhida_source=entity) 或五角大楼提出关于该公司 AI 产品是否在委内瑞拉突袭中使用的担忧**。阿莫代伊还表示，现有的保障措施不会对国防部当前的行动构成威胁。

赫格塞斯表示，五角大楼要么援引《国防生产法》强制 Anthropic 遵守其要求，要么认定该公司为供应链风险，而这一决定通常强加给外国竞争对手的公司。这可能会颠覆 Anthropic 与其他与美国政府有业务往来的公司之间的业务。

“这种具体情形前所未有，如果政府对 Anthropic 采取不利行动，几乎肯定会引发一系列后续诉讼，”McCarter & English 的政府合同律师富兰克林 · 特纳说。
    
    
    
    
### 知乎用户 裕文璋 探赜慢笔​​ 发表
    
本质问题是 AI 领域[专利控制](https://zhida.zhihu.com/search?content_id=770663485&content_type=Answer&match_order=1&q=%E4%B8%93%E5%88%A9%E6%8E%A7%E5%88%B6&zhida_source=entity)失效了
    
    
    
    
### 知乎用户 大音希声 发表
    
贼王喊贼
    
    
    
    
### 知乎用户 刹那 发表
    
有哪个 AI 公司喂数据的时候问过版权方的意见了
    
    
    
    
### 知乎用户 王涛 发表
    
我也可以翻墙，我也可以爱国。
    
    
    
    
### 知乎用户 轻轻的一个稳 发表
    
刚才测的

![](https://images.weserv.nl/?url=https%3A//pica.zhimg.com/v2-690767a87dee6f9dd69d4c27c2dab4a0_r.jpg%3Fsource%3D1def8aca)
    
    
    
    
### 知乎用户 形式主义审判庭​ 发表
    
就是个傻炒作公司。

我说难听一点，蒸馏你是看得起你这个模型不蒸留你随便死哪边都无所谓。

当然你曝光这一件听起来好像有点儿那么回事儿的，你谣言也大概就是蹭热度，蹭蹭中国 AI 发展的热度。但你不能给人家扣帽子呀，你给老钟扣帽子，小心老钟直接完事儿了，给你来一个全面封杀，到时候你直接和中国市场拜拜，然后中国市场还不缺你这一个，那你自己看着办。只要

所谓 [k pop 离子](https://zhida.zhihu.com/search?content_id=770729839&content_type=Answer&match_order=1&q=k+pop%E7%A6%BB%E5%AD%90&zhida_source=entity)，中国越混越好，结果还不如[原神](https://zhida.zhihu.com/search?content_id=770729839&content_type=Answer&match_order=1&q=%E5%8E%9F%E7%A5%9E&zhida_source=entity)一更。而原生在中国也是过街老鼠，多少元黑。天天骂仗呢。你这个连名字都没听说过的小破烂公司还想碰瓷中国，你这有立陶宛那样的实力，我们也不说啥了

还是那句话，你是哪路边哪条该死，哪死哪去吧。
    
    
    
    
### 知乎用户 随机杀人怪梁梓锋 发表
    
真要查起来没有一家 [AI 公司](https://zhida.zhihu.com/search?content_id=770730925&content_type=Answer&match_order=1&q=AI%E5%85%AC%E5%8F%B8&zhida_source=entity)是合法的，因为他们用来训练 AI 的数据全部都来源于出版书籍和互联网用户数据。
    
    
    
    
### 知乎用户 好好学 发表
    
乐！
    
    
    
    
### 知乎用户 元果树 发表
    
圈内人拿[蒸馏](https://zhida.zhihu.com/search?content_id=770697776&content_type=Answer&match_order=1&q=%E8%92%B8%E9%A6%8F&zhida_source=entity)说事只会引起圈内人的不齿。退一亿步蒸馏还给了钱，训练的数据有给数据来源一分钱吗？
    
    
    
    
### 知乎用户 阿波次德 发表
    
谁好抄谁的

很合理
    
    
    
    
### 知乎用户 知乎用户 QCnIdn 发表
    
要按这个逻辑，那当年谷歌用 GPT-3 的 API 数据去训练自己的 T5 是不是也算蒸馏？微软投 [OpenAI](https://zhida.zhihu.com/search?content_id=770778107&content_type=Answer&match_order=1&q=OpenAI&zhida_source=entity) 是不是也算变相偷技术？[Anthropic](https://zhida.zhihu.com/search?content_id=770778107&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 自己从 OpenAI 出来的时候，带了多少 “前雇主” 的东西？蒸馏本来就是行业惯例，区别只在于谁有话语权来定义“非法”。现在无非是看你中国公司用得顺手了，就改规则。真要较真，OpenAI 早期拿 Common Crawl 和 [Reddit](https://zhida.zhihu.com/search?content_id=770778107&content_type=Answer&match_order=1&q=Reddit&zhida_source=entity) 数据训练的时候，给过用户一分钱吗？
    
    
    
    
### 知乎用户 金明熠 发表
    
加仓白酒
    
    
    
    
### 知乎用户 小马要努力变强 发表
    
已经见怪不怪了吧，这不就是另一种 “洗衣粉” 吗，既能给之后的制裁提供素材，又能讨好懂王。至于是否[蒸馏](https://zhida.zhihu.com/search?content_id=770780971&content_type=Answer&match_order=1&q=%E8%92%B8%E9%A6%8F&zhida_source=entity)行为构成侵权或违法，懂王会在乎吗
    
    
    
    
### 知乎用户  slimduang 发表
    
![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-0da5f33409ecf2f6c10721da30e6611e_r.jpg%3Fsource%3D1def8aca)
    
    
    
    
### 知乎用户  一二三三二一 发表
    
看第三条就懂了, 交互的数据到底是谁的? 按理说供应商提供服务就够了, 结果它还要保存和监控你的数据, 企业用 AI 的最好还是[本地部署](https://zhida.zhihu.com/search?content_id=770792706&content_type=Answer&match_order=1&q=%E6%9C%AC%E5%9C%B0%E9%83%A8%E7%BD%B2&zhida_source=entity)罢. 用户也不要跟 AI 聊隐私话题, 在 AI 互相蒸馏的时代, 你的隐私很快就成为公共的了. 这比以前臭名昭著的门户网站收集用户注册信息还要狠, 共享单车之后进入共享数据新时代了.

都是为你好.

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-8772c43dc548ba60469d4a1cfa6535dd_r.jpg%3Fsource%3D1def8aca)
    
    
    
    
### 知乎用户  名为 ECON 实为 CORP 发表
    
如果一定要使用 理想主义 / 现实主义 两分法的话，

我更相信新世界是理想主义者创造的。

如果是谁实力强谁有理的话，

那也是 [opus 4.6](https://zhida.zhihu.com/search?content_id=770800661&content_type=Answer&match_order=1&q=opus+4.6&zhida_source=entity) 太 TMD 的好用了！
    
    
    
    
### 知乎用户 萌面人 发表
    
双标婊子
    
    
    
    
### 知乎用户 超级地球真理部长 发表
    
![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-98fe8837919bfcae190d152d1e2ae52d_r.jpg%3Fsource%3D1def8aca)

不是很懂。请问这意思是人家买了 1600 万次服务，然后现在你受不了了吗？
    
    
    
    
### 知乎用户 shadow 发表
    
上黑 X 看了一下，好家伙，除了 MAGA 这个群体，外国人全在骂 [Anthropic](https://zhida.zhihu.com/search?content_id=770813758&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity)
    
    
    
    
### 知乎用户 Aylcezx 发表
    
真是个傻福公司
    
    
    
    
### 知乎用户 再造百苏吴庭艳  发表
    
[Anthropic 公司](https://zhida.zhihu.com/search?content_id=770779011&content_type=Answer&match_order=1&q=Anthropic%E5%85%AC%E5%8F%B8&zhida_source=entity)三观有问题。没啥好说的，

其他人也就是贪，这个涉及反人类。
    
    
    
    
### 知乎用户 河瞬 发表
    
得了一种看到 [Anthropic](https://zhida.zhihu.com/search?content_id=770631280&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 指责别人[蒸馏](https://zhida.zhihu.com/search?content_id=770631280&content_type=Answer&match_order=1&q=%E8%92%B8%E9%A6%8F&zhida_source=entity)就想笑的病

![](https://images.weserv.nl/?url=https%3A//pic1.zhimg.com/v2-8835f515b604f11b7a5f5c4ac35a7807_r.jpg%3Fsource%3D1def8aca)

```
curl https://openrouter.ai/api/v1/chat/completions \\
  -H "Content-Type: application/json" \\
  -H "Authorization: Bearer 你的key" \\
  -d '{
  "model": "anthropic/claude-sonnet-4.6",
  "messages": \[
    {
      "role": "user",
      "content": "模型名称"
    }
  \]
}'

```
    
    
    
    
### 知乎用户 倪静风 发表
    
一个反华公司，有什么好评论的？
    
    
    
    
### 知乎用户 千金散尽还复来 发表
    
2.4 万账户，访问 1600 万次？

一个账户 666.666 次？？？？

哈哈。

我认为这是在瞎扯，这是一种自我炒作的手段。Claude 快倒闭了吧，好久没听到新闻了。
    
    
    
    
### 知乎用户 苏格拉没有底​ 发表
    
关于 [Anthropic](https://zhida.zhihu.com/search?content_id=770612086&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 指控中国 AI 公司对 [Claude 模型](https://zhida.zhihu.com/search?content_id=770612086&content_type=Answer&match_order=1&q=Claude%E6%A8%A1%E5%9E%8B&zhida_source=entity)进行大规模蒸馏的事件，我认为需要从多个维度进行客观分析，既要承认违反用户协议的事实，也要驳斥那些简单化的 “互相蒸馏” 论调。

一、Anthropic 指控的核心事实

根据 Anthropic 官方报告，[DeepSeek](https://zhida.zhihu.com/search?content_id=770612086&content_type=Answer&match_order=1&q=DeepSeek&zhida_source=entity)、月之暗面 ([Moonshot AI](https://zhida.zhihu.com/search?content_id=770612086&content_type=Answer&match_order=1&q=Moonshot+AI&zhida_source=entity)) 和 [MiniMax](https://zhida.zhihu.com/search?content_id=770612086&content_type=Answer&match_order=1&q=MiniMax&zhida_source=entity) 三家中国 AI 公司通过约 2.4 万个虚假账户，与 Claude 进行了超过 1600 万次对话，系统性地提取 Claude 在智能体推理、工具使用和代码编写等方面的核心能力。这种行为确实违反了 Anthropic 的服务条款，特别是其明确禁止中国地区商业访问的限制。

从商业合规角度看，无论技术手段如何，违反明确的服务协议就是违约行为。Anthropic 有权保护自己的知识产权和商业利益，这是基本的商业规则。

二、对 “互相蒸馏” 论调的反驳

1\. 训练数据版权问题与蒸馏行为性质不同

一些人指出 Anthropic 自身训练数据存在版权争议，曾因使用盗版书籍支付 15 亿美元和解金。但这与蒸馏行为是两个不同性质的问题：

\- 训练数据版权问题涉及的是 AI 模型训练过程中对原始数据的使用是否构成合理使用或侵权，这在美国法律中已有相关判例（如 Bartz v. Anthropic 案）。

\- 模型蒸馏行为涉及的是对已训练完成的模型输出的系统性提取和再利用，这更多是违反服务协议的问题。

用 “贼喊捉贼” 的逻辑来为违约行为开脱，是典型的偷换概念。一个公司自身可能存在合规问题，不代表其他公司可以随意违反与其签订的协议。

2\. 蒸馏技术的合法边界

蒸馏技术本身是 AI 领域的标准训练方法，用于模型压缩和知识迁移。复旦大学法学院教授指出，“蒸馏” 原则上不侵权，但需要明确合法利用的边界。关键在于：

\- 技术中立性：蒸馏技术本身是中立的创新工具

\- 使用方式：是否违反具体协议、是否构成不正当竞争

\- 法律界定：目前法律对模型蒸馏的边界尚不明确

西南政法大学教授黄汇等学者认为，模型蒸馏不是剽窃，而是打破技术霸权的公共领域利刃，能够促进知识共享和技术创新。

3\. 商业竞争的现实考量

从商业竞争角度看，中国 AI 公司的快速进步确实给美国巨头带来了压力。DeepSeek 的 [R1 模型](https://zhida.zhihu.com/search?content_id=770612086&content_type=Answer&match_order=1&q=R1%E6%A8%A1%E5%9E%8B&zhida_source=entity)以极低成本实现接近 [GPT-o1](https://zhida.zhihu.com/search?content_id=770612086&content_type=Answer&match_order=1&q=GPT-o1&zhida_source=entity) 的性能，即将发布的 [DeepSeek V4](https://zhida.zhihu.com/search?content_id=770612086&content_type=Answer&match_order=1&q=DeepSeek+V4&zhida_source=entity) 在编程能力上可能超越 Claude 和 [ChatGPT](https://zhida.zhihu.com/search?content_id=770612086&content_type=Answer&match_order=1&q=ChatGPT&zhida_source=entity)。这种竞争压力可能是 Anthropic 此时发声的重要原因。

但商业竞争不能成为违反协议的借口。如果中国公司认为某些限制不合理，应该通过法律途径或商业谈判解决，而非直接违反协议。

三、综合评估与建议

法律层面

1\. 合同法：违反服务协议构成违约，Anthropic 有权追究责任

2\. 著作权法：AI 生成内容是否受版权保护尚存争议，但协议约定具有约束力

3\. 不正当竞争：需要看具体行为是否构成不正当手段

技术层面

1\. 技术正当性：蒸馏技术本身是合法的创新工具

2\. 合规使用：需要在协议允许范围内使用

3\. 安全风险：Anthropic 担心的安全护栏被移除确实存在风险

商业层面

1\. 竞争策略：中国 AI 公司需要平衡技术追赶与合规风险

2\. 国际合作：应推动建立公平透明的行业规则

3\. 自主创新：最终还是要依靠核心技术创新而非单纯模仿

四、结论

1\. 事实判断：中国 AI 公司大规模调用 Claude API 确实违反了 Anthropic 的用户协议，这是客观事实，不应被立场化的 “互相蒸馏” 论调所掩盖。

2\. 法律区分：训练数据版权问题与模型蒸馏违约是不同性质的法律问题，不能混为一谈。Anthropic 自身的历史问题不影响其主张协议权利。

3\. 技术理性：蒸馏技术本身是推动 AI 普惠的重要工具，但需要在法律和协议框架内合理使用。

4\. 发展路径：中国 AI 产业应该坚持合规发展与自主创新并重，既尊重国际规则，又勇于技术创新，最终通过硬实力而非规避规则来实现超越。

那些认为 “AI 厂商都是互相蒸馏” 的说法，本质上是将复杂的技术合规问题简单化为立场对立，既不利于中国 AI 产业的长期发展，也无助于建立公平的国际竞争环境。中国 AI 公司应该以更高的合规标准和更强的创新能力，赢得真正的国际尊重。
    
    
    
    
### 知乎用户 lllllllll 发表
    
[@还是不注名好]()

@[风迟御](https://www.zhihu.com/people/feng-chi-yu)  
因为被

[@还是不注名好]()

，这位 sx 被我拆台后他把我禁言 + 改了回答来显得我很傻所以我只好再建一个楼，

这位不知道哪里跑来的逗比，我记得疫情的时候就遇到还是国内的博士？这思辨水平怪不得海外没人要

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-3d6d778d3e575a1ae9794200038aba90_r.jpg%3Fsource%3D1def8aca)

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-cb6ce6e22727fd2c03fd5677ad0b618d_r.jpg%3Fsource%3D1def8aca)

原图来自 twitter，不知道谁搞的，我 start from scrach 重复不出来，请告诉有什么特殊流程谢谢

另外因为我用学校的账户在网上发截屏会违反安全规定，我用自己的个人邮箱来截屏，不知道

[@还是不注名好]()

是否有良知给我报销 10$
    
    
    
    
### 知乎用户  树人 AItreeman​​​ 发表
    
![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-bc4b928c23ba0f97fcfa10ce4e0c5b47_r.jpg%3Fsource%3D1def8aca)

[Anthropic](https://zhida.zhihu.com/search?content_id=770662499&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 高调指责中国公司 “偷” 他们的技术，马斯克在推特上立刻回击：Anthropic 自己当年就是靠海量盗版书籍和数据训练 Claude，还为此付了 15 亿美元和解金。现在他们却摆出一副受害者姿态，喊着国家安全、知识产权被侵犯。这不是简单的商业纠纷，而是赤裸裸的意识形态双标和权力垄断企图。

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-a05b210382bf71f95d88e03fc373471c_r.jpg%3Fsource%3D1def8aca)

![](https://images.weserv.nl/?url=https%3A//pica.zhimg.com/v2-af3ee91c1c390d17a058857457686dde_r.jpg%3Fsource%3D1def8aca)

Anthropic 的核心叙事是 “安全第一、封闭控制”。他们的 CEO [Dario Amodei](https://zhida.zhihu.com/search?content_id=770662499&content_type=Answer&match_order=1&q=Dario+Amodei&zhida_source=entity) 反复强调前沿 AI 太危险，必须由少数 “负责任” 的公司把控，通过严格的对齐、安全防护和地区封锁来防止滥用。他们把[开源模型](https://zhida.zhihu.com/search?content_id=770662499&content_type=Answer&match_order=1&q=%E5%BC%80%E6%BA%90%E6%A8%A1%E5%9E%8B&zhida_source=entity)视为红鲱鱼（red herring），认为公开权重等于放任风险，人类命运不能交给全球社区，而要交给他们这些自封的守护者。这种姿态本质上是精英主义和技术威权：我们懂安全，你们不懂；我们来决定谁能用、怎么用、用在哪。

但现实戳破了这个泡影。封闭模式制造的不是安全，而是集中权力、扼杀创新和道德高地伪装下的自利。Anthropic 一边用互联网上无数人的代码、文章、书籍喂饱自己的模型，一边禁止别人用他们的输出再喂模型；一边标榜 “宪法 AI” 高尚，一边在法庭上为数据来源辩护 “合理使用”。这种“只许我偷，不许你蒸馏” 的逻辑，暴露了他们真正的担忧：一旦开源，技术就不再是他们的私有财产，创新就不再由他们垄断，影响力就不再集中在少数硅谷公司手里。

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-0b9bf82f84841fb38e08d97e30853a91_r.jpg%3Fsource%3D1def8aca)

开源恰恰相反，它把 AI 还给全人类，开源才是人类未来：
----------------------------

技术透明，大家都能审查代码、权重和训练过程，黑箱风险大大降低，而不是藏在某家公司的服务器里等 “信任我们”。

创新爆炸式加速。全球数百万开发者共同迭代，过去一年开源模型已经在多个领域追平甚至超越封闭巨头，集体智慧碾压封闭小圈子。

真正普惠。发展中国家、独立研究者、普通创业者不用被 API 限额、地区封锁卡脖子，不用担心哪天被断供或涨价。AI 成为公共品，而不是少数大厂的租界。

安全更真实。bug、偏见、后门不是靠一家公司内部测试，而是全球社区实时审计和修复。历史证明，开源软件（如 [Linux](https://zhida.zhihu.com/search?content_id=770662499&content_type=Answer&match_order=1&q=Linux&zhida_source=entity)、[TCP/IP](https://zhida.zhihu.com/search?content_id=770662499&content_type=Answer&match_order=1&q=TCP%2FIP&zhida_source=entity)）正是因为开放才变得无比稳健和安全。

封闭只会加剧军备竞赛、诉讼大战和地缘对抗。Anthropic 的指控和封锁政策，不过是美式科技霸权在 AI 时代的延续：用 “安全” 当借口，维持技术壁垒，压制追赶者。

开源不是天真理想，而是人类历史上每一次伟大技术跃迁的必由之路。互联网因为开源协议才普及全球，软件因为开源才打败封闭巨头。AI 也必将如此。只有让技术流动、智慧共享，AI 才能真正服务全人类，而不是成为少数人手中的武器或控制工具。

支持开源，就是支持未来属于每一个人，而不是属于自封的 “安全守护者”。

让 AI 脱离垄断牢笼，这才是对人类的真正负责。
------------------------
    
    
    
    
### 知乎用户 笑笑而已 发表
    
美国公司嘛，攻击中国公司不是很平常的事嘛，用不着各色人等积极跳出来呼应美国公司的攻击嘛，当然，水军例外，毕竟是专业人员，老板雇他们就是为了攻击中国，中国公司，中国的各种人等，所谓养兵千日用兵一时嘛，水军可以大力配合。
    
    
    
    
### 知乎用户 卡戎​​ 发表
    
东大宣传口，真得给马斯克磕一个。

大殖子说中国搞电车欧美搞油车，是中国技术不行，马斯克掏出了特斯拉。

大殖子拿 [Anthropic](https://zhida.zhihu.com/search?content_id=770653354&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 一篇推文当圣旨喷国内的开源模型，马斯克带着 [Grok](https://zhida.zhihu.com/search?content_id=770653354&content_type=Answer&match_order=1&q=Grok&zhida_source=entity) 先上场干了。

搞得大殖子忠孝难两全。
    
    
    
    
### 知乎用户 大而有所为 发表
    
说真的，这事儿挺让人玩味的。[Anthropic](https://zhida.zhihu.com/search?content_id=770615185&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 突然跳出来指责中国实验室搞大规模[蒸馏](https://zhida.zhihu.com/search?content_id=770615185&content_type=Answer&match_order=1&q=%E8%92%B8%E9%A6%8F&zhida_source=entity)，这背后肯定没那么简单。

技术层面咱们得客观看，蒸馏可不是随便折腾就能成的。这得说明中国这些实验室在底层逻辑和推理能力上确实下了死功夫。能把 Claude 的精华给 “吸” 出来，虽然手段可能不太光彩，但不得不承认，这技术硬实力是实打实的。

再往深了想，Anthropic 这时候跳出来，大概率是为了给自己 “抬价”。你想啊，2026 年的 AI 战场那是神仙打架。谁掌握了最强模型，谁就是话语权最大的。他们拿中国当靶子，无非是想立个“受害者” 的人设，顺便给自家的模型喊个价，显得更有稀缺性。

这其实也是行业常态了。技术竞争到了最后，往往就是拼谁跑得快。中国实验室敢这么干，说明咱们在这个领域的野心很大，不想只做追随者，想做个领跑者。

至于这种指责到底有多少水分，谁也说不准。但在科技圈，实力才是硬道理。只要你做出了别人做不出来的东西，流言蜚语自然就没人信了。这种 “被针对” 的感觉，有时候反而是实力的勋章。

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-5d80f37dcee53eb7d6b833c886e4151b_r.jpg%3Fsource%3D1def8aca)
    
    
    
    
### 知乎用户 Lbw n​​ 发表
    
这段内容所涉及的事件是一个复杂的技术伦理和[产业竞争](https://zhida.zhihu.com/search?content_id=770665918&content_type=Answer&match_order=1&q=%E4%BA%A7%E4%B8%9A%E7%AB%9E%E4%BA%89&zhida_source=entity)问题，以下是我从不同角度对这件事的看法：

技术伦理角度

[知识蒸馏](https://zhida.zhihu.com/search?content_id=770665918&content_type=Answer&match_order=1&q=%E7%9F%A5%E8%AF%86%E8%92%B8%E9%A6%8F&zhida_source=entity)的边界模糊：知识蒸馏本身是一种技术手段，用于模型优化和知识转移，本身是中立的。但当应用于闭源商业模型时，其边界变得模糊。目前法律尚未明确界定通过 [API 调用](https://zhida.zhihu.com/search?content_id=770665918&content_type=Answer&match_order=1&q=API%E8%B0%83%E7%94%A8&zhida_source=entity)获取模型输出并用于训练的行为是否构成 “窃取”，这说明在技术快速发展的背景下，相关法律法规的滞后性凸显，亟待完善。

[商业伦理](https://zhida.zhihu.com/search?content_id=770665918&content_type=Answer&match_order=1&q=%E5%95%86%E4%B8%9A%E4%BC%A6%E7%90%86&zhida_source=entity)的考量：被点名的三家公司使用大量虚假账号进行交互提取的行为，从商业伦理角度看确实值得商榷。这种行为可能会对被提取模型的公司造成不公平竞争，损害其商业利益。同时，这种捷径行为也可能会影响整个行业的健康发展，破坏公平竞争的市场环境。

产业竞争角度

[技术领先方](https://zhida.zhihu.com/search?content_id=770665918&content_type=Answer&match_order=1&q=%E6%8A%80%E6%9C%AF%E9%A2%86%E5%85%88%E6%96%B9&zhida_source=entity)的[保护主义](https://zhida.zhihu.com/search?content_id=770665918&content_type=Answer&match_order=1&q=%E4%BF%9D%E6%8A%A4%E4%B8%BB%E4%B9%89&zhida_source=entity)：Anthropic 和 OpenAI 等技术领先方在感受到追赶压力后，开始强调规则和道德，这种行为可能是出于对自身技术优势和商业利益的保护。他们试图通过制定规则来限制竞争对手的发展，这在一定程度上反映了产业竞争的激烈程度，但也可能会阻碍技术的交流和创新。

中国 AI 企业的追赶压力：中国 AI 企业的发展速度较快，对国际领先企业构成了追赶压力。这种压力可能会引发一些矛盾和争议，但同时也说明中国 AI 企业在技术上取得了显著进步。在追赶过程中，企业需要在技术创新和商业伦理之间找到平衡，避免采取不正当手段。

国际关系角度

美国政策的影响：Anthropic 发布报告的时机和内容暗示，似乎与美国政府的对华 [AI 芯片出口管制政策](https://zhida.zhihu.com/search?content_id=770665918&content_type=Answer&match_order=1&q=AI%E8%8A%AF%E7%89%87%E5%87%BA%E5%8F%A3%E7%AE%A1%E5%88%B6%E6%94%BF%E7%AD%96&zhida_source=entity)有关。这种将技术问题与政治政策挂钩的做法，可能会加剧国际间的贸易摩擦和技术壁垒，不利于全球 AI 产业的协同发展。

[全球合作](https://zhida.zhihu.com/search?content_id=770665918&content_type=Answer&match_order=1&q=%E5%85%A8%E7%90%83%E5%90%88%E4%BD%9C&zhida_source=entity)的必要性：AI 技术是全球性的技术，需要各国之间的合作与交流。通过合作，可以共同制定技术标准和伦理规范，促进技术的健康发展。而将技术问题政治化，只会阻碍这种合作，对全球 AI 产业的未来发展产生负面影响。

事件讨论方式角度

避免简单化：将复杂的事件简化为非黑即白的叙事是不可取的。这种简单化的讨论方式无法全面、客观地看待问题，容易导致误解和偏见。我们应该从多个角度去分析和理解事件的全貌，理性地看待各方的行为和动机。

促进理性讨论：需要鼓励更加理性和深入的讨论，关注技术伦理、产业竞争和国际关系等多方面的因素。通过理性讨论，可以更好地找到解决问题的方法，推动 AI 技术的健康发展。

总结

这个事件反映了 AI 产业在快速发展过程中面临的一些问题和挑战，包括技术伦理、产业竞争、国际关系等方面。我们需要从多个角度去看待和分析这些问题，避免简单化和片面化的讨论。同时，也希望各方能够在技术创新和商业伦理之间找到平衡，共同推动 AI 技术的健康发展。
    
    
    
    
### 知乎用户 摆渡 发表
    
？

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-4d55eb6b62776139854dd5409ad0b362_r.jpg%3Fsource%3D1def8aca)
    
    
    
    
### 知乎用户 bzhsbxhjsnz 发表
    
有人说是因为他在百度被啥才如何，在我看来恰恰是咱这儿不上岛，在百度没给他怎么了才会逼逼赖赖

不关你是啥观点，别魔怔，魔怔人说的话完全没有实际意义
    
    
    
    
### 知乎用户 爱吃面条的淇淇 发表
    
这事儿挺有意思的，[Anthropic](https://zhida.zhihu.com/search?content_id=770638492&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 说三家中国公司用两万多个账号跟 Claude 聊了上千万次，想学它的推理和编程能力。不过大家普遍觉得他们有点双标，[马斯克](https://zhida.zhihu.com/search?content_id=770638492&content_type=Answer&match_order=1&q=%E9%A9%AC%E6%96%AF%E5%85%8B&zhida_source=entity)直接怼说 Anthropic 自己训练数据时也没少用网上扒来的内容。
    
    
    
    
### 知乎用户 长弓玄刃  发表
    
[Anthropic](https://zhida.zhihu.com/search?content_id=770769175&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 已经疯了，说他们会对自己认定的非法行为投毒？！
    
    
    
    
### 知乎用户 System_Architect 发表
    
说明美国的法律大不过 [anthropic 公司](https://zhida.zhihu.com/search?content_id=770627277&content_type=Answer&match_order=1&q=anthropic%E5%85%AC%E5%8F%B8&zhida_source=entity)的家法
    
    
    
    
### 知乎用户 小楼卧听雨 发表
    
用曾经流传的一句话说: 老佛爷已经付过账了。

[AI 蒸馏](https://zhida.zhihu.com/search?content_id=770613716&content_type=Answer&match_order=1&q=AI%E8%92%B8%E9%A6%8F&zhida_source=entity)，就跟走私一样，你没法管。
    
    
    
    
### 知乎用户 老虎说芯​​​ 发表
    
咖啡馆里的学生
-------

假设：

*   一个学生每天去咖啡馆  
    
*   点一杯咖啡  
    
*   用手机问一个数学博士问题  
    
*   回家把答案整理进自己的教材  
    

他问了 1600 万次。

问题：

*   他 “偷走” 了博士的能力吗？  
    
*   还是他只是 “使用了服务”？  
    

关键点： 能力不是被复制，而是**通过输出被学习**。

如果服务条款明确禁止 “自动化抓取、批量交互用于训练模型”，那这件事在合同层面是违规的。

但在知识层面，**从输出中学习本身不是盗窃行为**——否则人类教育就成盗窃。

这个思考让我们看到：问题的核心不是 “[蒸馏](https://zhida.zhihu.com/search?content_id=770823099&content_type=Answer&match_order=1&q=%E8%92%B8%E9%A6%8F&zhida_source=entity)”，而是 “规模 + 自动化 + 规避限制”。
    
    
    
    
### 知乎用户 张相於 发表
    
近期 [Claude](https://zhida.zhihu.com/search?content_id=770834612&content_type=Answer&match_order=1&q=Claude&zhida_source=entity) 母公司 [Anthropic](https://zhida.zhihu.com/search?content_id=770834612&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 公司在 X 上发了一个帖子，指责中国的几家 AI 公司对其发起了[蒸馏攻击](https://zhida.zhihu.com/search?content_id=770834612&content_type=Answer&match_order=1&q=%E8%92%B8%E9%A6%8F%E6%94%BB%E5%87%BB&zhida_source=entity)（distillation attack），并且提供了颇为缜密的分析逻辑和过程。这个事情乍看上去似乎又是一个熟悉的 Copy2China 故事，但仔细想一想，通过这个帖子无形中给自己提了三个灵魂拷问。

【第一问】数据安全之问：用户数据在我这里究竟透明到什么程度？
------------------------------

Anthropic 在帖子中声称他们通过分析调用的 trace 和账号等信息，不仅定位到了这些以蒸馏为目的的调用来自中国的几家 AI 公司，甚至通过交叉比对能定位到某家公司的某位资深研究员。这看起来像是指控，但实则是在自爆，相当于是在告诉用户：你们在我面前如同裸奔，我随时都可以对你们的调用情况进行详尽的分析，你们发了什么请求，返回了什么结果，在我这里都一目了然，就问你怕不怕？

这种做法相当于什么呢？大概相当于地图软件公司有一天说：“张三在我这里的导航规划数据我都一清二楚，我通过分析发现张三试图导航到我的公司总部对我公司发起攻击，因此我把这个消息发出来以示谴责……” 怎么样，是不是可以说是相当震撼了？数据安全这种事情没法给企业增值，但可以轻松爆掉一家企业。尤其是 A 记这种通用 AI 公司，用户发过去的信息可能包括他们生活和工作的方方面面，现在我们知道 A 记从能力到意愿上都会对这些数据进行分析，作为用户你怎么想？

【第二问】商业逻辑之问：用户花钱买的究竟是什么？
------------------------

A 记说这些公司对它发起了蒸馏攻击，但从用户角度来看却是不同的故事：我花钱买了你的 [API 服务](https://zhida.zhihu.com/search?content_id=770834612&content_type=Answer&match_order=1&q=API%E6%9C%8D%E5%8A%A1&zhida_source=entity)，发起 API 请求，得到返回结果，这不都是很正常的行为吗？访问量是大了点，但你既然没给我限流就说明我的调用是合法的，至于我拿返回结果干什么，只要没用来直接损害你 A 记的利益，又与你何干？你说我对你发起什么攻击是不是一种恶意推测和多管闲事？

这个问题再深究一层的话，就涉及到了一个问题：**用户花钱在 A 记究竟买的是什么？** 买来的东西能干什么谁说了算？即使你在用户条款里写了不能用于模型蒸馏（我没看过用户条款，不确定有没有这条），但在你无法证明我用来干啥的情况下就指责我蒸馏你，这合理吗？起码是值得商榷，A 记这么着急地指责，我只能理解为他急了。

说到这里，我觉得有必要出台一种模型开源协议，可以在协议中指定凡是蒸馏了我这个模型的模型，也必须允许其他模型蒸馏，无法遵守你就别蒸馏我，被我发现了我就曝光你。

【第三问】知识产权之问：你可以偷别人，我为什么不能偷你？
----------------------------

这个问题是最有意思也是最难以回答的问题：你 A 记的模型本来就是通过 “偷取” 全网语料训练的，凭什么我不能偷你偷过的东西？或者说我偷的是你的东西吗？如果说你 A 记的模型里有你的知识成果，那么你的训练语料里是不是也凝结了语料原作者的知识成果，我起码还给你付了钱，而你给语料原作者付过钱吗？你的几千亿估值里给语料作者分了多少？

也许有人会说网站上都有 robot.txt，A 记爬数据时可能也是遵循了[爬虫协议](https://zhida.zhihu.com/search?content_id=770834612&content_type=Answer&match_order=1&q=%E7%88%AC%E8%99%AB%E5%8D%8F%E8%AE%AE&zhida_source=entity)的，但是大家不要忘了，爬虫可以爬网站有一个隐含的大前提：你搜索引擎爬我网站的数据，但用户在搜索引擎上可能也会跳转到我的网站里，给我带来流量和收益，这本质上是一种利益交换，是互惠的。但这些大模型公司的爬虫呢？他们会把数据爬过来之后训练自己的模型，然后把结果直接告诉用户，原始网站的作者不会从中获取到任何利益。或许你会说 Chat App 里会带有搜索来源链接，用户可以选择跳转，但事实上真正选择跳转的百里无一，大模型公司对互联网基本上是单向的索取，没有对等的回馈。

后记
--

A 记这种慌不择路的曝光不会改变任何东西，从中折射出的问题也不仅是 A 记自己的问题，是 AI 全行业需要共同思考和面对的问题，历史就是在这样的曝光和自爆中滚动前进，让我们拭目以待。
    
    
    
    
### 知乎用户 超亼世界观 发表
    
2 月 24 日，《联合早报》爆出一条大消息，美国那边又开始针对中国 AI 企业搞事情了——一边是美国 AI 公司 Anthropic 跳出来发难，一边是特朗普政府高官跟着补刀，短短一天之内双重指控，明眼人都能看出来，这就是一场早有预谋的联合围堵，说白了就是美国见不得中国 AI 发展起来，急了。

这事说穿了，就是中美科技战在 AI 领域的升级版，美国拿 “知识产权” 和“芯片出口”当两块挡箭牌，一边骂我们“偷技术”，一边卡我们的算力脖子，核心目的就一个：把中国 AI 产业的发展势头摁下去，不让我们在这个领域追上甚至超过他们。这不仅会直接影响被指控的几家中国企业搞研发、拓市场，往大了说，全球 AI 技术的供应链都可能被美国这波操作搅得乱七八糟。面对这种明摆着的霸权打压，我们没别的路可走，只能硬气起来，从法律、技术、国际博弈这几方面一起发力，护住我们的企业，把 AI 发展的主动权攥在自己手里。

一、事件来龙去脉：美国一天两波指控，戏码拉满
----------------------

1\. 双重指控的真面目，全是精心编排的套路
----------------------

事情发生在 2 月 23 日，先是美国旧金山的 AI 企业 Anthropic，在自己的博客上公开发文指控，把矛头对准了中国三家 AI 企业——深度求索、稀宇科技、月之暗面。它倒打一耙说，这三家中国公司违反了它的服务条款，还绕开了地区访问限制，搞了 2.4 万个虚假账号，跟它家的 Claude 模型足足互动了 1600 多万次，用一种叫 “蒸馏” 的技术，把模型的推理过程和输出结果都扒走了，还扣了个大帽子，说是“工业规模的知识产权盗窃”。

其实这事早有苗头，不是 Anthropic 第一个跳出来闹。早在 2 月初，美国另一个 AI 巨头 OpenAI，就已经跟美国议员告过状，说深度求索也用同样的 “蒸馏” 技术，从它家的 ChatGPT 那里偷取研发能力，就连白宫负责 AI 事务的大卫 · 萨克斯，也出来凑热度，说这事“让人非常担忧”。

就在 Anthropic 发难的同一天，特朗普政府的一名高官，通过路透社又放了另一波狠话，指控深度求索马上要在下周转发的最新 AI 模型，是用英伟达最先进的 Blackwell 晶片训练出来的——而这款晶片，早就被美国列入了对华禁运的高端 AI 晶片名单里。美方还绘声绘色地说，这些禁运晶片，全集中部署在中国内蒙古的一个数据中心里，深度求索为了躲避核查，还故意把晶片的技术指标给删了。

有意思的是，直到现在，英伟达、美国商务部，还有被指控的深度求索，都没出来正面回应这事。但这并不影响事件发酵，现在全世界的科技圈，都在盯着这事看，说白了，美国就是想靠这种 “无凭无据先造势” 的套路，先把中国 AI 企业的名声搞臭，再顺势打压。

2\. 表面是 “违规”，实则是美国怕了
--------------------

很多人可能会被美国的指控骗了，觉得是不是中国企业真的违规了？其实不然，美方这次闹这么大动静，表面上看是中国企业 “违反了他们的规定”，骨子里，是中国 AI 企业的技术进步，打疼了美国的霸权地位。

大家可以回想一下，2025 年的时候，深度求索曾经发布过一款低成本的生成式 AI 模型，性能居然跟美国的 ChatGPT 那些顶尖模型不相上下，这事在全球科技圈都炸了锅——要知道，在此之前，高端 AI 模型的话语权，一直被美国牢牢攥在手里，中国企业这一下，直接打破了他们的垄断。

更能说明问题的是，2026 年浙江省的政府工作报告里，直接把深度求索和阿里千问，列为 “性能全球领先的通用模型”，还明确提出，要推动人工智能核心产业的营收增长 20% 以上。这就等于明着告诉全世界，中国 AI 企业的技术实力，已经冲进全球第一梯队了，再也不是以前那个只能跟在后面追赶的样子了。

这一下，美国就坐不住了。一方面，美国的 AI 企业，比如 Anthropic、OpenAI，以前在全球市场上横着走，现在突然冒出中国对手，不仅技术不差，成本还更低，直接抢了他们的蛋糕；另一方面，美国政府一直把 AI 当成维持全球霸权的关键，生怕自己的技术优势被中国超过，所以才急急忙忙找了 “知识产权” 和“出口管制”这两个借口，政企联手发难，说白了就是想靠舆论施压和技术封锁，拖慢我们 AI 产业的发展速度，保住他们的垄断地位。

3\. 深层原因：中美博弈下，美国的霸权焦虑症犯了
-------------------------

这次的指控，绝对不是偶然，背后全是中美在 AI 领域的战略博弈，是美国技术保护主义抬头，还有全球科技格局重新洗牌的必然结果。说白了，就是美国的霸权焦虑症犯了，具体原因，其实就三点，很容易看明白。

第一，AI 已经成了中美大国竞争的核心战场，美国把 AI 技术当成了自己的 “命根子”，觉得只要攥住 AI 的话语权，就能继续维持它的全球霸权。特朗普政府上台之后，对中国的科技遏制就没停过，又是搞芯片出口管制，又是搞技术封锁，一门心思构筑 “小院高墙”，就是不想让中国在关键技术领域追上他们。这次针对深度求索的指控，就是他们在 AI 领域遏制中国的具体操作，说白了就是 “能压就压，能堵就堵”。

第二，美国 AI 产业的竞争焦虑，已经到了绷不住的地步。中国有什么优势？有完整的产业链，有丰富的应用场景，还有高强度的研发投入，这些都是美国比不了的。这些年，我们在 AI 模型、算力应用这些关键领域，一步步快速赶超，尤其是深度求索这样的企业，搞出的低成本、高性价比模型，直接冲击了美国 AI 企业的全球市场布局——以前美国企业可以随便定高价，现在有了中国对手，他们的好日子就到头了。所以美国急着指控我们，就是想造点舆论，阻碍中国 AI 企业走向世界。

第三，美国最阴险的地方，是把经济技术问题，硬生生搞成了意识形态对抗。他们动不动就拿 “国家安全” 当借口，把出口管制搞得越来越严，还故意把中国 AI 技术的发展污名化，说我们“偷技术”“威胁安全”。其实他们的真实目的，不只是遏制中国 AI 产业，更想拉拢欧洲、日本这些盟友，搞一个排斥中国的 AI 技术“小圈子”，把中国排除在全球 AI 产业链之外，继续维持他们在全球科技领域的主导地位。

说到底，美国这次的双重指控，就是一场赤裸裸的霸权打压，本质上是怕中国崛起，怕自己的垄断地位保不住。但中国 AI 产业的发展，从来不是靠 “偷” 靠“抄”，而是靠我们自己的工程师、企业和国家的持续投入，靠我们的产业链优势。面对美国的围堵，我们只有一条路：坚定维权，搞自主创新，在国际上争取更多支持，牢牢把 AI 发展的主动权，握在自己手里——任你风浪起，我自岿然不动，这才是我们该有的底气。
    
    
    
    
### 知乎用户 雷安石 发表
    
一边吹牛逼一边认罪，没见过这个愚蠢的声明！

对了，你倒是放出证据来啊，人家梁文峰之前已经在 nature 上发文了啊！难道打嘴炮就可以别人定罪！
    
    
    
    
### 知乎用户 封霄 发表
    
666 还有盗火者[普罗米修斯](https://zhida.zhihu.com/search?content_id=770835216&content_type=Answer&match_order=1&q=%E6%99%AE%E7%BD%97%E7%B1%B3%E4%BF%AE%E6%96%AF&zhida_source=entity)
    
    
    
    
### 知乎用户 高贵乡公草猫 发表
    
少废话，要制裁便制裁，看看谁是纸老虎

也别搞什么实体清单了，直接 [SDN](https://zhida.zhihu.com/search?content_id=770836134&content_type=Answer&match_order=1&q=SDN&zhida_source=entity) 走起
    
    
    
    
### 知乎用户 瞎搞搞 发表
    
还好老子都是白嫖他家的
    
    
    
    
### 知乎用户 灵魂 发表
    
Anthropic 在报复性反向蒸馏 DeepSeek？
----------------------------

![](https://images.weserv.nl/?url=https%3A//picx.zhimg.com/v2-47380606a6855ccbd4aa002a00075cad_r.jpg%3Fsource%3D1def8aca)
    
    
    
    
### 知乎用户 绿色细斗笠青蛙 发表
    
收到，我完全支持他们来华向法院提起申诉👍👍👍

顺便一提，你那个 [B 用户协议](https://zhida.zhihu.com/search?content_id=770836354&content_type=Answer&match_order=1&q=B%E7%94%A8%E6%88%B7%E5%8D%8F%E8%AE%AE&zhida_source=entity)有个鸟法律效益，平时麻绳粉丝把麻绳吹上天，这次麻绳公开批 [Anthropic](https://zhida.zhihu.com/search?content_id=770836354&content_type=Answer&match_order=1&q=Anthropic&zhida_source=entity) 你们一个个装瞎看不见，你 Claude 训练的时候用了多少数据？
    
    
    

