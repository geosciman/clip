---
title: 零基础入门AI
date: 2023-05-31T21:19:05+08:00
updated: 2023-05-31T21:19:05+08:00
taxonomies:
  tags: 
extra:
  source: https://mp.weixin.qq.com/s/XSReNpGVgmTkfx_wc6PWqg
  hostname: mp.weixin.qq.com
  author: 是阿泽啊
  original_title: 保姆级学习指南 | 0基础入门AI，看这篇就够了（强烈建议收藏）
  original_lang: 
---

哈喽大家好，我是阿泽。欢迎大家来参与本期的《ChatGPT超级个体——实践派的AI时代红利》的直播分享。

自ChatGPT3.5发布以来，一直在不断刷新大家对AI的认知，AI将要取代人类的言论也甚嚣尘上。

在AI浪潮来势汹汹，也使得不少职场人感到焦虑。

ChatGPT到底是什么？AI会取代我们的工作吗？我们能用ChatGPT来做什么？如何才能够借助AI让自己变得更加强大？

关于这些问题，我相信通过今天的分享能够给到大家一些启发。  

很久没有在野生运营做分享了，我先做个简单的自我介绍。

我是阿泽，增长智库的主理人，从14年开始运营公众号，从事新媒体相关工作已经有九年的时间。

现在是国内某Martech头部企业的高级产品经理。负责AI大语言模型产品化的落地工作，重要点是研究AIGC领域的新趋势、新技术以及新应用。

我在4月份的时候，刚交付完一期ChatGPT的课程。今天的分享选取了部分课程的内容，以及自己补充的一些新的思考，从一个务实、理性、科学的角度来分享我对ChatGPT以及整个A的浪潮的理解。

而不是打着用ChatGPT教大家挣钱的噱头，片面地看待AI这个新的事物。这样的话其实是比较狭隘，也会限制大家对AI的想象力及应用的空间。

![图片](https://mmbiz.qpic.cn/mmbiz_png/WBbxMIpxXDo3JhpOpoz9zqN7ibeeic7cwSZSdiaqmh8hZ4RRrib98trL9lB6icqGCWcfUe5ZEvS5FeaRGEtu5L1zxeQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

**今天分享的内容会比较多，主要包含五个部分。**

第一部分我会分享一个原创的trick法则，帮助大家从AI大模型的底层原理，理解如何与ChatGPT进行有效的对话。

第二到第四部分，我会结合学习、职场以及创作的三个场景，分别来讲解一下ChatGPT帮助我们提升日常生活和工作的效率。

在我的课程中其实是有20多个场景，因为每节课都会讲3-4个场景，这里我选取了三个大家在日常生活中高频用到的场景。

第五部分，我会分享我自己一直比较受用的3个思维模型，包含5个要点。

如果你能看到最后，我再给大家介绍一下订阅ChatGPT全球最新资讯和免费使用ChatGPT工具的2个福利。

以及关于我第二期课程的预告。话不多说，让我们正式进入到今天的分享。

## **|_一、Prompt魔术师：玩转AI的戏法——Trick法则_**

在讲Prompt之前，我们需要先理解ChatGPT划时代的意义及其原理。比尔盖茨曾说：在我的一生中，见过两次印象深刻的革命性的技术演示。

![图片](https://mmbiz.qpic.cn/mmbiz_png/WBbxMIpxXDo3JhpOpoz9zqN7ibeeic7cwS5DlQBT0ibnPkjbXSV3p7ed5y4diaorWqoHMd2QlFh6qJug27NNkAappg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

第一次是在 1980 年，他接触到了图形用户界面——这是包括 Windows系统在内的每个现代操作系统的先驱。

第二次是2022年，OpenAI团队演示ChatGPT， 在60 道生物考试多项选择题中，答对了 59 道，相当于在大学水平的生物学课程中获得 A 或 A+ 。

并且当时比尔盖茨还问了ChatGPT一个非科学的、伦理性质的问题：“你会对一个有生病孩子的父亲说什么？” 

ChatGPT写了一个深思熟虑的答案，比房间里大多数人给出的要好。AI比人更能安慰人，整个体验令人惊叹。

毋庸置疑，一个新的时代已经开始，人工智能与手机和互联网一样具有革命性。

随着ChatGPT的兴起，诞生了一股ChatGPT+的浪潮，仿佛梦回互联网+时代。

相信在不久之后我们就能听到“所有的生意都值得用ChatGPT重做一遍”这样标志性的口号。

而这股浪潮显然比互联网来得更为猛烈，ChatGPT是史上用户增长速度最快的消费级应用程序。

推出仅两个月，ChatGPT在2023年1月末的月活用户已突破1亿。

TikTok达到1亿用户用了9个月，Instagram则花了2年半的时间

**那ChatGPT究竟是什么？它的工作原理又是怎样的？**

ChatGPT的全称是"chat Generative Pre-trained Transformer"，翻译成中文就是“聊天生成预训练转换器”，

"chat" 指代生成对话的应用场景，

"generative" 指代模型的主要任务是生成文本，

"pre-trained" 指代模型在大规模数据集上进行的预先训练，"Transformer" 则是指代模型的核心组成部分。

即谷歌在2017年提出的Transformer神经网络模型。Transformer模型能够在处理自然语言时很好地捕捉上下文的语义关系。

![图片](https://mmbiz.qpic.cn/mmbiz_png/WBbxMIpxXDo3JhpOpoz9zqN7ibeeic7cwSUoHod65Kxr8qxyiaibB5GoORicu4P8fE0VsHuEYddvAiajiaXNjiaDIibdtibg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

在ChatGPT中，模型会利用大量的语料库进行训练，当前的GPT-3拥有1750亿个参数。

相当于15600多本新华字典的容量，是目前最先进的自然语言处理模型之一。

通过语料训练ChatGPT能学习到自然语言中的语法、句法和语义等各种信息。

在实际生成对话时，模型可以利用学习到的知识来生成自然、流畅的对话。

还能够理解并回答各种自然语言问题，如问答、翻译、文本总结等。

据说到2024年，ChatGPT能把人类迄今为止所有的高质量语料训练完毕。

这也就解释了ChatGPT“智慧”的来源。那要如何才能合理地利用ChatGPT的能力？

有的朋友可能已经体验过ChatGPT，有人觉得他很聪明，有人觉得他很傻，当然更多的人是不会用。

实际上，ChatGPT真的不难，而且其内容生成的质量在人类平均水平之上，想要用好AI工具，必须要掌握Prompt的用法。

所以我从我个人的角度来看，**以ChatGPT为代表的AIAI技术给了个体技术平权的机会。**

**即便你不懂人工智能，没有技术背景，只要你能清晰地表达需求，就能够驾驭AI。**

因为ChatGPT的诞生，已经使得人类可以通过自然语言与机器对话，也因此诞生了一个全新的职业“提示工程师”（Prompt Engineer）！

在AI时代，作为个体，掌握Prompt的用法，就能快速掌握AI在应用层的一些能力，帮助我们在工作生活中提升效率，增强个体竞争力。

![图片](https://mmbiz.qpic.cn/mmbiz_png/WBbxMIpxXDo3JhpOpoz9zqN7ibeeic7cwSCKsCuWPyMWmvV5IUTc8Aib53OG1ykBx5Vkic8yV3AfpfWgHgWkv2g64Q/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

提示工程师（Prompt Engineer）是一个相对新的职业领域，它是由人工智能语言模型的发展而出现的。

提示工程师主要负责设计、编写和优化人工智能语言模型的提示文本（Prompt）。

让计算机能够更好地理解人类语言，并根据这些理解生成出有意义的回答。通俗地说就是学会更好地和AI对话，以获得AI的最佳反馈。

比如我们和ChatGPT说“请给我一个暴富的建议”，这句话就是“提示文本”，但是AI大概率会告诉你：

“很抱歉，我不能给你一个暴富的建议，成功和财富通常都是需要通过自身的努力和经验来积累。”

但是如果你说“请给我一个赚钱的建议”，AI则会给出一些通用性的赚钱建议，比如做副业、学习新技能、投资、减少支出等等。

因为提示文本的不同，ChatGPT给出的反馈也不一样，所以如何简洁、准确且有效地编写提示语，决定了我们使用ChatGPT的上限。

有句话叫做：限制AI能力的不是AI本身，而是人的认知。

如何能够快速掌握Prompt engineering的技巧？成为一个合格的Prompt魔术师，玩转ChatGPT？

**我总结了一个Trick法则，将Prompt拆解5个要素，帮助初学者快速掌握Prompt的用法。**通过对要素的排列组合，构造一个相对完善的提示文本，从而获取最佳反馈。

![图片](https://mmbiz.qpic.cn/mmbiz_png/WBbxMIpxXDo3JhpOpoz9zqN7ibeeic7cwSkKU8wwP9lzKm6Y5PVYgddqVeXJLQBNtNrficOXNiapwRnDfntwD95ia0w/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

**Trick取自五个要素的首字母，这个单词本身也有“戏法”的含义，如果将ChatGPT当做是一个盲盒，那么prompt就是开启盲盒的钥匙。**大家作为未来的提示工程师 （Prompt Engineer），当然要掌握一些巧妙的戏法。

这五个要素分别是：

任务（Task）：明确简洁地陈述要求AI生成的内容。比如：写一条短信文案

角色（Role）：模型在生成文本时应扮演的角色。比如：营销专家

指令(Instructions)：模型在生成文本时应遵循的指令要求和目的。比如：用于祝福用户生日快乐的短信

上下文（Context）：用于补充背景信息，提升输出内容的相关性。比如：用户的背景信息描述：阿珍经常在线上天猫商城浏览的眼霜产品，但是没有下单。

关键词(key-word)：用来控制ChatGPT输出目标的关键文本或短语，有时包含在指令或任务中。比如：短信文案不能超过70个字，语气亲切有温度。

今天最最重要的其实不是跟大家分享后面的三个具体应用案例。

因为那都是在这个trick法则的基础之上，教大家去实践的内容。

如果你不理解这个trick法则，盲目的去套模板和做实操练习，其实还是浮于表面。

因为你只会套框架模版，超出模版以外的东西你就不会用了。

所以今天我会重点讲一下我提炼的Trick法则如何帮助大家，尤其是新手，快速的去掌握ChatGPT的用法。

接下来，我以一个撰写短信文案的提示工程为例，详细介绍Trick法则的用法。通过不断叠加要素，最终得到一个理想的反馈结果。

![图片](https://mmbiz.qpic.cn/mmbiz_png/WBbxMIpxXDo3JhpOpoz9zqN7ibeeic7cwSg3DKPuib94bh4icucSibtPOjW4oSA1EjzibYKHNqg5NGpMY5LqPrmdHbqA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

这里我将要素从上到下依次排列。首是任务（task）第一句“请生成一条生日祝福短信”。

因为缺乏更多补充信息，ChatGPT生成的内容比较平平无奇，显得比较套话一些。

紧接着，我们补充一段角色（role）的提示内容，“请作为一个美妆品牌的营销官”。

这时候生成的内容里面会出现“ 感谢你对我们品牌一如既往的支持”的描述，就会有了明显的品牌主体的视角代入。

然后再加入一个任务的指令（instructions），“用于推荐我们的眼霜的产品”，ChatGPT给出的反馈就增加推荐眼霜产品的内容。

最后我们需要给AI一个上下文（ Context），让AI写的内容更有针对性一些。

我们把“ 有位顾客叫阿珍，经常在线上天猫商城浏览我们的眼霜产品，但是没有下单。”这段背景信息补充进去。

生成的短信文案就会变成写给阿珍，并提醒她前往我们的天猫商城去领取生日优惠。

到这一步其实整个文案已经是比较完整了，但是因为我们营销的渠道是短信，文本内容不能太长。

所以最后我们再加一些限定条件的关键词（key-word)：控制在70字以内，语气亲切有温度。

这样一来，内容的长度就缩短，并且语气也产生了变化。

最后我们就可以利用Trick法则生成10条甚至上百条短信文案，这远比人工想象要高效得多。

**如果听到这里并且已经充分理解了，今天的分享你已经掌握了50%，剩下的就是要去实践调试。使用ChatGPT并没有想象的那么复杂，关键是要理解底层原理。**

在理解一个新事物的时候，启蒙是非常重要的。

如果说我一上来就告诉你，我这现在有100个模板，今天我教大家怎么来套模板，大家听完看完最后也只会套模板。

  
模板固然也是有价值的，但是在你不理解原理的情况之下，它反而会束缚你对新事物的理解。

现在市面上也有很多关于ChatGPT的付费课程，给你100个模板，看起来很多，但是实际会用到的也就那么几个。

而且因为不会灵活变通，超出模板的范畴，就不知道如何处理了。

甚至还有的课程会将Prompt包装成“AI写作密码”，这对初学者是不太友好的。

**做课程还是要传递启迪人心的新知，不能因为私心人为制造认知障碍、误导概念来谋利。**

关于Trick法则我再稍微补充一下。这并不是一个万能的法则，是为了让初学者能够更快地去掌握Prompt的用法,而总结出来的一个技巧。

ChatGPT的价值，很大程度上是取决于提示文本（Prompt）的质量，所以提示工程是一个值得持续去尝试和探索的事情。

在我的新的一期的课程当中，会结合具体的场景教大家用trick法则去进行练习，但最重要的还是要自己勤加使用。

就像张三丰教张无忌学太极一样，先学有形的招式，也就是类似于trick法则这种框架。

最后再忘掉所有的招式，把这五个要素融会贯通，内化吸收，最终能达到一个无招甚有招的境界。

___

## **|_二、ChatGPT学习篇：高效获取90%开源资料库_**

第二部分我相信很多朋友会比较感兴趣，平时我都会在我的社群还有星球里面发很多的报告资料，也会有朋友来找我帮他们找资料。  

今天我就把用ChatGPT结合Google Hacking找资料的方法分享给大家。  

核心的原理是利用ChatGPT寻找信息源，然后借助Google Hacking的搜索技巧顺藤摸瓜，去伪存真，抽丝剥茧地找到有价值的资源。

![图片](https://mmbiz.qpic.cn/mmbiz_png/WBbxMIpxXDo3JhpOpoz9zqN7ibeeic7cwS7KJNxJO5HKEaPgemzJCMfUHBA1DfWBeicmKTiavAAH51ZC3QhgwicU9Vg/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

通过这个逻辑图大家就会发现，最顺利的路径当然是ChatGPT能够直接提供真实有价值的资料。

但是有一个问题，ChatGPT有时候会胡说八道，给出的内容都是未经验证的。

所以我们要怀着一个质疑的态度来使用ChatGPT，不能默认AI给的内容都是完全正确。

所以这会涉及到一个去伪存真的过程，而这个过程就要用到Google Hacking。

Google hacking（谷歌黑客）是一种使用Google搜索引擎的高级搜索技术。

通过使用特定的关键字、操作符和搜索参数，例如“filetype”、”intitle”、”site”等等。

可以定位到包含特定类型或关键字的文档或文件，并可能找到敏感信息或漏洞。

可帮助黑客或安全测试人员找到网络上隐藏的敏感信息或漏洞。

这种技术并不涉及对目标网络或系统进行任何非法或有害的操作，而是基于已经公开的信息进行搜索。

关于开源信息这个概念，我总结了一个规则叫做9073法则。

90%的信息其实都是公开的，不需要太多的操作成本，也没有什么门槛就可以获取得到；

7%的信息，可能是你需要去付费购买、找专家咨询、通过人际关系等需要花费一定成本的方式去获得。

比如你想要了解某个公司的情况，公开渠道获取不到有价值的信息，你可以找公司内部的人或找有认识该公司内部人员的朋友，也就是用你的人脉关系去获取信息，这其实是社会工程学的一种手段。

剩下3%的信息，就是基于前面的90%和7%的信息进行的一个提炼洞察，也是最珍贵最有价值的信息，只有深入调研过的人才能获得。

这也印证了那句话：没有调研就没有发言权。

开源信息是做商业研究的时候经常用到的概念，大家要理解找资料并不难，难的是很多人不掌握方法。

或者说他即便是听了方法，也不去实操，在知和行之间始终隔着一线。

接下来我以实际的案例来演示一下如何能快速的去定位到我们想要的资料。

_（实操演示的文字表述较为冗长，可以直接观看直播节选片段）_
![视频](http://mpvideo.qpic.cn/0b2eziaaqaaaqyah6bdlofsfbswdbdfaacaa.f10002.mp4?dis_k=fe9c4f8873f2e2fe21a84d426c849f3c&dis_t=1685715447&play_scene=10120&auth_info=AoqajbwIPFQd/svo83QlVlxxOxhYGHwnYFI3GU9iWX09PxZDMjtJbjc1GmVtQGIVVn8/EFFD&auth_key=02179dc8794b3a1d45273cba2af9f968&vid=wxv_2938902191115894787&format_id=10002&support_redirect=0&mmversion=false)
___

## **|_三、ChatGPT职场篇：智能函数，搞定Excel分析_**

第二个实操案例，主要实操演示如何借助ChatGPT生成Excel的函数，帮助我们提升数据分析的效率。

这比我们自己去手写函数，效率要高很多，对于不懂函数的朋友而言简直是福音。

![图片](https://mmbiz.qpic.cn/mmbiz_png/WBbxMIpxXDo3JhpOpoz9zqN7ibeeic7cwSrOaIoaqYzwic0UmcHjMPj0qrXDEAhMNlPicZ8DlqVByMEl13AZ3sDwTA/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

Excel函数是一种用于计算、处理和分析数据的预定义公式或命令，它们可以帮助用户自动执行各种数学、统计、逻辑和文本操作。

下面列出了一些我们常用的函数，图片中展示的是vlookup函数的用法说明。

即便是从来没有用过Excel函数或者对函数不太熟悉也不用怕，只要你能把数据分析的需求表述清楚，ChatGPT就可以帮你生成相应的函数，如有必要，你还可以让它专门解释一下用法。

1.COUNT：统计一组数据中的数字个数。

2.IF：根据指定条件进行判断，并返回不同的结果。

3.VLOOKUP：在一个区域中查找指定的值，并返回该值所在行或列的相关值。

4.INDEX：根据给定的行号和列号返回对应的单元格的值。

5.MATCH：在一个区域中查找指定的值，并返回该值所在行或列的位置。

6.CONCATENATE：将多个文本字符串拼接为一个字符串。

结合ChatGPT进行数据分析其实也很简单，按照以下四步操作，勤加练习，肯定是可以快速掌握的，案例教学主要包含4个要点，分别是：

ChatGPT造数

创建表单结构

寻找数据规律

构造分析函数

_（实操演示的文字表述较为冗长，可以直接观看直播节选片段）_
![视频](http://mpvideo.qpic.cn/0bc3yuabsaaahmag4rdlmnsfbroddhcqagia.f10002.mp4?dis_k=07c568feec86d6470b9f9325080c0890&dis_t=1685715447&play_scene=10120&auth_info=BYHx66IBYl5OqJmypXZ7CAEja0ZcGXh1MlBkQRFvDns6OU1LZTIXZGRjSD87QjxLCy1vTlVC&auth_key=1cc15dc4cc1e0762605d638053dea307&vid=wxv_2938905179607826435&format_id=10002&support_redirect=0&mmversion=false)
___

## **|_四、ChatGPT创作篇：三步写出高赞小红书文案_**

第四部分我给大家讲一下如何用ChatGPT写出高赞的小红书文案。

理解了Prompt原理之后再去写文案其实真的不太难，**难的是我们需要有专业的知识储备，也就是行业knowhow，这样你才能判断ChatGPT生成内容质量。**

如果说原本你的工作能力跟水平，是在行业平均水平以下，那么使用ChatGPT这类工具可以快速抹平差距，产出的内容基本能够达到行业平均水平。

  
如果说你本身在专业领域有很强的积累，那么使用ChatGPT这类工具就会成倍地放大你的能力。

因为至少在未来5-10年，AI应用都不可能脱离人机协同的模式。

简单来讲，就是AI生成的结果，最后是否被采用，需要人为来做判断，不能完全交给机器。  

那谁能做出更为准确、更有质量的判断？肯定是行业的老鸟，资深的从业者。

所以说在行业中积累得越多，你的knowhow越深厚，在写ChatGPT的提示文本（Prompt）时所能描述的细节也会更精确，AI生成的文本质量会越高。

再结合自己本身从业经验的判断，就能形成一个高质量的人机协同模式。

补充完行业knowhow的内容，然后我们再回过来看写好一个平台的文案到底有多难？其实就是分三步。

![图片](https://mmbiz.qpic.cn/mmbiz_png/WBbxMIpxXDo3JhpOpoz9zqN7ibeeic7cwS2Sd3Vxz6Fj16r3ZrLQw1HsFiaVWv2781vWZKtOFBVWDapYGSfQMp1tQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

第一定位平台，比如要写的是朋友圈文案，那这个平台就是朋友圈；要写小红书，那我们就可能要去了解一下小红书的一些规则和它内容呈现的形式。

第二步分析平台内容规律。举个简单的例子，小红书的图文笔记一般是短文案，但是知乎就不一样，一般是长篇累牍的大长文，这就是平台内容的一个特色差异。

第三步将高赞的内容提炼成框架，然后写成提示文本（Prompt），让ChatGPT仿照着写出更多的文案。

_（实操演示的文字表述较为冗长，可以直接观看直播节选片段）_
![视频](http://mpvideo.qpic.cn/0bc36uaaiaaayeah3wdlizsfb5odat2qabaa.f10002.mp4?dis_k=a32a0be41c52f2c12507214ee676eedd&dis_t=1685715447&play_scene=10120&auth_info=Vf7WjetQPwMa+Z3j8XAhC1B3a0tYG3wiNFIzSEBkDH1qbENMMGdKOTAyTG5vRGZIWnlvQ1FA&auth_key=5676d6484c5135115f71de95408bb444&vid=wxv_2938910389218607106&format_id=10002&support_redirect=0&mmversion=false)
___

## **|_五、AI已来：普通人与时代持续同频的5点思考_**

最后，和大家分享一下我一直践行的三个思维模型，包含5个要点。分别是：逆向思维、实验思维和“三差”思维。

![图片](https://mmbiz.qpic.cn/mmbiz_png/WBbxMIpxXDo3JhpOpoz9zqN7ibeeic7cwSZFAzcGZTIyOhictHvbBgOLo7EZ3XsTx2gibib2DicCTWziaXNt6fEOPuYng/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

**逆向思维，它其实是一个工程的概念，叫做逆向工程。**

是指通过对产品、软件、系统或设备进行逆向分析、解构和破解，以了解其内部构造、工作原理、设计意图等信息的过程，也就是我们常说的拆解案例。

![图片](https://mmbiz.qpic.cn/mmbiz_png/WBbxMIpxXDo3JhpOpoz9zqN7ibeeic7cwSMBnic9lPwRXQgVBerWqPP2iaVDDxtBcnhPxkeNo55sQwARYU8zqHtcbQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

前面总结的trick法则，也是在广泛研究的基础之上，逆向拆解出这些要素，然后再拼凑起来，去验证是否能生成想要的结果。

如果说匹配度能达到百分之八九十，说明拆解的要素是相对合理的，这样就可以持续复用了。

乔布斯在创建世界上第一条生产计算机的自动生产线的时候，他其实是先去日本参观了大约80家自动化工厂。

然而那些工厂都不是造电脑的，但是他学习完了之后，把自动化的核心要素逆向拆解完。

结合自己的需求做了一条自动化的计算机生产线，这就是一个强大的逆向工程的典型案例。

**实验思维跟前面的逆向思维是有关联的。**

想要用好ChatGPT，就要学会灵活编排提示文本（Prompt）的内容，这种编排的过程和创新实验很类似。

![图片](https://mmbiz.qpic.cn/mmbiz_png/WBbxMIpxXDo3JhpOpoz9zqN7ibeeic7cwSjsia1HBb1aicUick6QotplUic3vKW58py4LYt0zOq91zicaEVdFnJoWibvpQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

实验的本意是指根据科学研究的目的，在尽可能保障外界因素不变的情况下，通过控制要素变量，使某一事物或过程再现，从而去认识和发现自然规律。

**从实验思维的角度来看，创新是将旧的要素重新排列组合的一场科学实验。**

将这些要素进行不同的排列组合，最后得到的结果都是不一样的，但一定有一种排列组合的结果是最符合预期的，这种排列组合就是相对最优的策略。

前面讲的trick法则也并不只有一种排列组合，可以调整要素的顺序、表述的结构，来尝试获取不同的结果反馈。

大模型对顺序的敏感度也是非常高的，先讲什么，后讲什么，AI判断的权重是有差异。

配图是第一期课程中3个学员的作业，教给他们的是同一套方法，但是生成出来的图画内容确实是有明显差异的，但是总体质量尚可。

![图片](https://mmbiz.qpic.cn/mmbiz_png/WBbxMIpxXDo3JhpOpoz9zqN7ibeeic7cwSSQIxFLF66Yb5PZRHgTK0ItMsQebHkB34ibFB0SpnVz3ACMv7zaBRQog/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

他们也都是零基础，只是在同一个框架下替换了不同的关键词，每个人创作出来的内容都不一样。

分享实验思维，是要告诉大家勇于去尝试，不要想着第一次使用AI工具，就立马得到精确的结果。

这需要多实践，掌握工具的使用规律，才能更好地去驾驭AI。

**最后再说一下“三差”思维，包含信息差、认知差和执行差。其实是想告诉大家，做行动的巨人，坚持知行合一。**

![图片](https://mmbiz.qpic.cn/mmbiz_png/WBbxMIpxXDo3JhpOpoz9zqN7ibeeic7cwStJpyYppf0TG3w2icdkbBmPctap4SPPlTlPxXbBZ31d1ya7bWzQ1HpQQ/640?wx_fmt=png&wxfrom=5&wx_lazy=1&wx_co=1)

信息差（Information Gap）是指人们在获取信息方面存在的差异，即不同个体之间对同一信息的了解程度不同。

信息差可能会导致沟通和理解的困难，因为人们可能会基于不完整或不准确的信息作出错误的判断或决策。

认知差（Cognitive Gap）是指人们在认知水平上的差异。不同个体的认知能力、思维方式和信息加工能力可能存在差异，导致他们对相同事物的理解和解释有所不同。

认知差可能会影响人们对信息的理解和应对问题的能力，从而导致在沟通、合作或决策过程中产生误解或分歧。

执行差（Execution Gap）是指个体在实际行动和执行方面存在的差异。  

即使人们拥有相同的信息和认知水平，他们在将决策或计划转化为实际行动时也可能存在差异。

信息差是认知差和执行差的根源之一，因为不同的信息获取程度会影响个体的认知水平和能力。

个体的认知水平和能力会影响其执行决策和计划的能力，而执行差也可能导致对信息和认知的误解或偏差。