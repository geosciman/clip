---
title: 谷歌我们没有护城河，OpenAI 也没有
date: 2023-06-02T21:50:16+08:00
updated: 2023-06-02T21:50:16+08:00
taxonomies:
  tags: 
extra:
  source: https://www.semianalysis.com/p/google-we-have-no-moat-and-neither
  hostname: www.semianalysis.com
  author: Dylan Patel, Afzal Ahmad
  original_title: Google "We Have No Moat, And Neither Does OpenAI"
  original_lang: en
---

Leaked Internal Google Document Claims Open Source AI Will Outcompete Google and OpenAI
泄露的谷歌内部文件声称开源人工智能将胜过谷歌和 OpenAI

###### _The text below is a very recent leaked document, which was shared by an anonymous individual on a public Discord server who has granted permission for its republication. It originates from a researcher within Google. We have verified its authenticity. The only modifications are formatting and removing links to internal web pages. The document is only the opinion of a Google employee, not the entire firm. We do not agree with what is written below, nor do other researchers we asked, but we will publish our opinions on this in a separate piece for subscribers. We simply are a vessel to share this document which raises some very interesting points.  
下面的文本是最近泄露的文档，由一位匿名人士在公共 Discord 服务器上共享，该服务器已授予其重新发布的许可。它起源于谷歌内部的一名研究员。我们已经验证了它的真实性。唯一的修改是格式化和删除指向内部网页的链接。该文件仅代表谷歌员工的意见，并非整个公司的意见。我们不同意下面写的内容，我们询问的其他研究人员也不同意，但我们将在单独的一篇文章中为订阅者发表我们的意见。我们只是分享这份文件的工具，这份文件提出了一些非常有趣的观点。_

We’ve done a lot of looking over our shoulders at OpenAI. Who will cross the next milestone? What will the next move be?  
我们在 OpenAI 做了大量的工作。谁将跨越下一个里程碑？下一步将是什么？

But the uncomfortable truth is, _we aren’t positioned to win this arms race and neither is OpenAI_. While we’ve been squabbling, a third faction has been quietly eating our lunch.  
但令人不安的事实是，我们没有能力赢得这场军备竞赛，OpenAI 也没有。在我们吵架的时候，第三派一直在悄悄地吃我们的午餐。

I’m talking, of course, about open source. Plainly put, they are lapping us. **Things we consider “major open problems” are solved and in people’s hands today.** Just to name a few:  
当然，我说的是开源。说白了，他们在舔我们。我们认为是“主要开放问题”的事情今天已经解决并掌握在人们手中。仅举几个：

-   **LLMs on a Phone:** [People are running foundation models on a Pixel 6](https://twitter.com/thiteanish/status/1635678053853536256) at 5 tokens / sec.  
    LLMs on a Phone：人们在 Pixel 6 上以每秒 5 个代币的速度运行基础模型。
    
-   **Scalable Personal AI:** [You can finetune a personalized AI on your laptop in an evening.](https://github.com/tloen/alpaca-lora)  
    可扩展的个人 AI：您可以在晚上在笔记本电脑上微调个性化 AI。
    
-   **Responsible Release:** This one isn’t “solved” so much as “obviated”. [There are entire websites full of art models with no restrictions whatsoever](https://civitai.com/), and text is [not far behind.](https://medium.com/geekculture/list-of-open-sourced-fine-tuned-large-language-models-llm-8d95a2e0dc76)  
    负责任的发布：与其说是“解决”，不如说是“避免”。整个网站充满了艺术模型，没有任何限制，文字也不甘落后。
    
-   **Multimodality:** [The current multimodal ScienceQA SOTA was trained in an hour](https://arxiv.org/pdf/2303.16199.pdf).  
    多模态：当前的多模态 ScienceQA SOTA 在一个小时内完成训练。
    

While our models still hold a slight edge in terms of quality, the [gap is closing astonishingly quickly](https://arxiv.org/pdf/2303.16199.pdf). Open-source models are faster, more customizable, more private, and pound-for-pound more capable. They are [doing things with $100 and 13B params](https://lmsys.org/blog/2023-03-30-vicuna/) that we struggle with at $10M and 540B. And they are doing so in weeks, not months. This has profound implications for us:  
虽然我们的模型在质量方面仍然略有优势，但差距正在以惊人的速度缩小。开源模型更快、更可定制、更私密且功能更强大。他们用 100 美元和 13B 的参数做事，而我们在 1000 万美元和 540B 的参数下苦苦挣扎。他们在几周内完成，而不是几个月。这对我们有深远的影响：

-   **We have no secret sauce.** Our best hope is to learn from and collaborate with what others are doing outside Google. We should prioritize enabling 3P integrations.  
    我们没有秘方。我们最大的希望是学习 Google 以外其他人正在做的事情并与之合作。我们应该优先考虑启用 3P 集成。
    
-   **People will not pay for a restricted model when free, unrestricted alternatives are comparable in quality.** We should consider where our value add really is.  
    当免费的、不受限制的替代品在质量上具有可比性时，人们不会为受限制的模型付费。我们应该考虑我们真正的增值在哪里。
    
-   **Giant models are slowing us down.** In the long run, the best models are the ones  
    巨型模型正在减慢我们的速度。从长远来看，最好的模型是那些
    
    which can be iterated upon quickly. We should make small variants more than an afterthought, now that we know what is possible in the <20B parameter regime.  
    可以快速迭代。既然我们知道在 <20B 参数范围内有什么可能，我们应该做一些小的变体而不是事后才想到。
    

[

![](https://substackcdn.com/image/fetch/w_1456,c_limit,f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F241fe3ef-3919-4a63-9c68-9e2e77cc2fc0_1366x588.png)

](https://substackcdn.com/image/fetch/f_auto,q_auto:good,fl_progressive:steep/https%3A%2F%2Fsubstack-post-media.s3.amazonaws.com%2Fpublic%2Fimages%2F241fe3ef-3919-4a63-9c68-9e2e77cc2fc0_1366x588.png)

https://lmsys.org/blog/2023-03-30-vicuna/

At the beginning of March the open source community [got their hands on](https://www.vice.com/en/article/xgwqgw/facebooks-powerful-large-language-model-leaks-online-4chan-llama) their first really capable foundation model, as Meta’s LLaMA was leaked to the public. It had no instruction or conversation tuning, and no RLHF. Nonetheless, the community immediately understood the significance of what they had been given.  
3 月初，随着 Meta 的 LLaMA 被泄露给公众，开源社区得到了他们第一个真正有能力的基础模型。它没有说明或对话调整，也没有 RLHF。尽管如此，社区立即理解了他们所获得的东西的重要性。

A tremendous outpouring of innovation followed, with just days between major developments (see The Timeline for the full breakdown). Here we are, barely a month later, and there are variants with [instruction tuning](https://crfm.stanford.edu/2023/03/13/alpaca.html), [quantization](https://github.com/ggerganov/llama.cpp), [quality improvements](https://lmsys.org/blog/2023-03-30-vicuna/), [human evals](https://arxiv.org/pdf/2303.16199.pdf), [multimodality](https://arxiv.org/pdf/2303.16199.pdf), [RLHF](https://drive.google.com/file/d/10iR5hKwFqAKhL3umx8muOWSRm7hs5FqX/view), etc. etc. many of which build on each other.  
随之而来的是巨大的创新涌现，主要发展之间的间隔只有几天（完整细目请参见时间表）。仅仅一个月后，我们就在这里，并且有指令调整、量化、质量改进、人工评估、多模态、RLHF 等的变体，其中许多是相互构建的。

Most importantly, [they have solved the scaling problem](https://github.com/tloen/alpaca-lora) to the extent that anyone can tinker. Many of the new ideas are from ordinary people. The barrier to entry for training and experimentation has dropped from the total output of a major research organization to one person, an evening, and a beefy laptop.  
最重要的是，他们已经解决了任何人都可以修补的扩展问题。许多新想法都来自普通人。培训和实验的门槛已经从一个主要研究机构的总产出下降到一个人、一个晚上和一台功能强大的笔记本电脑。

In many ways, this shouldn’t be a surprise to anyone. The current renaissance in open source LLMs comes hot on the heels of a renaissance in image generation. The similarities are not lost on the community, with many calling this the “[Stable Diffusion moment](https://simonwillison.net/2023/Mar/11/llama/)” for LLMs.  
在许多方面，这对任何人来说都不应该是一个惊喜。开源 LLM 的当前复兴紧随图像生成的复兴之后。社区并没有失去相似之处，许多人称这是法学硕士的“稳定扩散时刻”。

In both cases, low-cost public involvement was enabled by a vastly cheaper mechanism for fine tuning called [low rank adaptation](https://arxiv.org/abs/2106.09685), or LoRA, combined with a significant breakthrough in scale ([latent diffusion](https://arxiv.org/abs/2112.10752) for image synthesis, [Chinchilla](https://arxiv.org/abs/2203.15556) for LLMs). In both cases, access to a sufficiently high-quality model kicked off a flurry of ideas and iteration from individuals and institutions around the world. In both cases, this quickly outpaced the large players.  
在这两种情况下，低成本的公众参与都是通过一种成本低得多的微调机制实现的，称为低秩适应或 LoRA，并结合了规模上的重大突破（图像合成的潜在扩散，LLM 的 Chinchilla）。在这两种情况下，获得足够高质量的模型都引发了世界各地个人和机构的一系列想法和迭代。在这两种情况下，这都很快超过了大型企业。

These contributions were pivotal in the image generation space, setting Stable Diffusion on a different path from Dall-E. Having an open model led to [product integrations](https://github.com/AbdullahAlfaraj/Auto-Photoshop-StableDiffusion-Plugin), [marketplaces](https://civitai.com/), [user interfaces](https://github.com/AUTOMATIC1111/stable-diffusion-webui), and [innovations](https://stablediffusionweb.com/ControlNet) that didn’t happen for Dall-E.  
这些贡献在图像生成领域至关重要，使 Stable Diffusion 走上了与 Dall-E 不同的道路。拥有一个开放的模型导致了 Dall-E 没有发生的产品集成、市场、用户界面和创新。

The effect was palpable: [rapid domination](https://trends.google.com/trends/explore?date=2022-08-01%202023-04-10&q=Stable%20Diffusion,Dall-E&hl=en) in terms of cultural impact vs the OpenAI solution, which became increasingly irrelevant. Whether the same thing will happen for LLMs remains to be seen, but the broad structural elements are the same.  
效果是显而易见的：与 OpenAI 解决方案相比，在文化影响方面迅速占据主导地位，后者变得越来越无关紧要。法学硕士是否会发生同样的事情还有待观察，但广泛的结构要素是相同的。

The innovations that powered open source’s recent successes directly solve problems we’re still struggling with. Paying more attention to their work could help us to avoid reinventing the wheel.  
推动开源最近取得成功的创新直接解决了我们仍在努力解决的问题。更多地关注他们的工作可以帮助我们避免重新发明轮子。

[LoRA](https://arxiv.org/abs/2106.09685) works by representing model updates as low-rank factorizations, which reduces the size of the update matrices by a factor of up to several thousand. This allows model fine-tuning at a fraction of the cost and time. Being able to personalize a language model in a few hours on consumer hardware is a big deal, _particularly_ for [aspirations that involve incorporating new and diverse knowledge in near real-time](http://www.internalgooglesitescrubbedbyus.com/). The fact that this technology exists is underexploited inside Google, even though it directly impacts some of our most ambitious projects.  
LoRA 通过将模型更新表示为低秩分解来工作，这将更新矩阵的大小减少了多达数千倍。这允许以一小部分成本和时间进行模型微调。能够在几个小时内在消费类硬件上个性化语言模型是一件大事，特别是对于涉及近实时整合新的和多样化的知识的愿望。事实上，这项技术的存在在谷歌内部并未得到充分利用，尽管它直接影响了我们一些最雄心勃勃的项目。

Part of what makes LoRA so effective is that - like other forms of fine-tuning - it’s stackable. Improvements like instruction tuning can be applied and then leveraged as other contributors add on dialogue, or reasoning, or tool use. While the individual fine tunings are low rank, their sum need not be, allowing full-rank updates to the model to accumulate over time.  
LoRA 如此有效的部分原因在于 - 与其他形式的微调一样 - 它是可堆叠的。可以应用指令调整等改进，然后在其他贡献者添加对话、推理或工具使用时加以利用。虽然单独的微调是低秩的，但它们的总和不需要，允许模型的全秩更新随着时间的推移而累积。

This means that as new and better datasets and tasks become available, the model can be cheaply kept up to date, without ever having to pay the cost of a full run.  
这意味着随着新的更好的数据集和任务的出现，模型可以以低廉的成本保持最新，而无需支付全面运行的成本。

By contrast, training giant models from scratch not only throws away the pretraining, but also any iterative improvements that have been made on top. In the open source world, it doesn’t take long before these improvements dominate, making a full retrain extremely costly.  
相比之下，从头开始训练巨型模型不仅会丢弃预训练，还会丢弃在顶部进行的任何迭代改进。在开源世界中，这些改进很快就会占据主导地位，这使得全面重新培训的成本极其高昂。

We should be thoughtful about whether each new application or idea really needs a whole new model. If we really do have major architectural improvements that preclude directly reusing model weights, then we should invest in more aggressive forms of distillation that allow us to retain as much of the previous generation’s capabilities as possible.  
我们应该考虑每个新应用程序或想法是否真的需要一个全新的模型。如果我们真的有重大的架构改进来阻止直接重用模型权重，那么我们应该投资于更积极的蒸馏形式，使我们能够尽可能多地保留上一代的功能。

LoRA updates are very cheap to produce (~$100) for the most popular model sizes. This means that almost anyone with an idea can generate one and distribute it. Training times under a day are the norm. At that pace, it doesn’t take long before the cumulative effect of all of these fine-tunings overcomes starting off at a size disadvantage. Indeed, in terms of engineer-hours, the pace of improvement from these models vastly outstrips what we can do with our largest variants, and the best [are already largely indistinguishable from ChatGPT](https://bair.berkeley.edu/blog/2023/04/03/koala/). **Focusing on maintaining some of the largest models on the planet actually puts us at a disadvantage.**  
对于最流行的模型尺寸，LoRA 更新的生产成本非常低（约 100 美元）。这意味着几乎任何有想法的人都可以产生一个想法并进行传播。一天之内的培训时间是常态。以这样的速度，所有这些微调的累积效应很快就会克服尺寸劣势。事实上，就工程师工时而言，这些模型的改进速度大大超过了我们使用最大变体所能做的，而且最好的已经在很大程度上与 ChatGPT 没有区别。专注于维护地球上一些最大的模型实际上使我们处于劣势。

Many of these projects are saving time by [training on small, highly curated datasets](https://bair.berkeley.edu/blog/2023/04/03/koala/). This suggests there is some flexibility in data scaling laws. The existence of such datasets follows from the line of thinking in [Data Doesn't Do What You Think](http://www.internalgooglesitescrubbedbyus.com/), and they are rapidly becoming the standard way to do training outside Google. These datasets are built using synthetic methods (e.g. filtering the best responses from an existing model) and scavenging from other projects, neither of which is dominant at Google. **Fortunately, these high quality datasets are open source, so they are free to use.**  
其中许多项目都通过在小型、高度精选的数据集上进行训练来节省时间。这表明数据缩放法则具有一定的灵活性。此类数据集的存在遵循了 Data Doesn't Do What You Think 中的思路，并且它们正迅速成为在 Google 之外进行培训的标准方式。这些数据集是使用合成方法（例如从现有模型中过滤最佳响应）和从其他项目中提取的，这两种方法在谷歌都不占主导地位。幸运的是，这些高质量的数据集是开源的，因此可以免费使用。

This recent progress has direct, immediate implications for our business strategy. **Who would pay for a Google product with usage restrictions if there is a free, high quality alternative without them?**  
这一最新进展对我们的业务战略具有直接、直接的影响。如果没有免费、高质量的替代品，谁会为有使用限制的 Google 产品付费？

And we should not expect to be able to catch up. The [modern internet runs on open source](https://openuk.uk/wp-content/uploads/2021/07/State-of-Open-Phase-Two.pdf) for a reason. Open source has some significant advantages that we cannot replicate.  
我们不应该期望能够赶上。现代互联网在开源上运行是有原因的。开源有一些我们无法复制的显着优势。

Keeping our technology secret was always a tenuous proposition. Google researchers are leaving for other companies on a regular cadence, so we can assume they know everything we know, and will continue to for as long as that pipeline is open.  
保守我们的技术秘密始终是一个脆弱的提议。谷歌研究人员正定期前往其他公司，因此我们可以假设他们知道我们所知道的一切，并且只要该渠道开放，他们就会继续这样做。

But holding on to a competitive advantage in technology becomes even harder now that cutting edge research in LLMs is affordable. Research institutions all over the world are building on each other’s work, exploring the solution space in a breadth-first way that far outstrips our own capacity. We can try to hold tightly to our secrets while outside innovation dilutes their value, or we can try to learn from each other.  
但是，由于法学硕士的尖端研究是负担得起的，因此保持技术竞争优势变得更加困难。世界各地的研究机构都在相互借鉴，以广度优先的方式探索解决方案空间，这远远超出了我们自身的能力。我们可以在外部创新削弱其价值的同时努力保守秘密，或者我们可以尝试相互学习。

Much of this innovation is happening on top of the leaked model weights from Meta. While this will inevitably change as [truly open models](https://bigscience.huggingface.co/blog/bloom) get better, the point is that they don’t have to wait. The legal cover afforded by “personal use” and the impracticality of prosecuting individuals means that individuals are getting access to these technologies while they are hot.  
这种创新的大部分发生在 Meta 泄露的模型权重之上。虽然随着真正开放的模型变得更好，这将不可避免地发生变化，但关键是他们不必等待。 “个人使用”提供的法律保护和起诉个人的不切实际意味着个人可以在这些技术炙手可热的时候使用它们。

Browsing through the models that people are creating in the image generation space, there is a vast outpouring of creativity, from anime generators to HDR landscapes. These models are used and created by people who are deeply immersed in their particular subgenre, lending a depth of knowledge and empathy we cannot hope to match.  
浏览人们在图像生成空间中创建的模型，从动漫生成器到 HDR 风景，创意源源不断。这些模型由深深沉浸在其特定子流派中的人们使用和创建，赋予我们无法企及的知识深度和同理心。

Paradoxically, the one clear winner in all of this is Meta. Because the leaked model was theirs, they have effectively garnered an entire planet's worth of free labor. Since most open source innovation is happening on top of their architecture, there is nothing stopping them from directly incorporating it into their products.  
矛盾的是，所有这一切的一个明显赢家是 Meta。因为泄露的模型是他们的，所以他们有效地获得了整个星球的免费劳动力。由于大多数开源创新都发生在他们的架构之上，因此没有什么能阻止他们将其直接整合到他们的产品中。

**The value of owning the ecosystem cannot be overstated.** Google itself has successfully used this paradigm in its open source offerings, like Chrome and Android. By owning the platform where innovation happens, Google cements itself as a thought leader and direction-setter, earning the ability to shape the narrative on ideas that are larger than itself.  
拥有生态系统的价值怎么强调都不为过。谷歌本身已在其开源产品（如 Chrome 和 Android）中成功使用了这种范例。通过拥有发生创新的平台，谷歌巩固了自己作为思想领袖和方向制定者的地位，获得了塑造比自身更宏大的想法的能力。

**The more tightly we control our models, the more attractive we make open alternatives.** Google and OpenAI have both gravitated defensively toward release patterns that allow them to retain tight control over how their models are used. But this control is a fiction. Anyone seeking to use LLMs for unsanctioned purposes can simply take their pick of the freely available models.  
我们对模型的控制越严密，我们做出开放替代方案的吸引力就越大。谷歌和 OpenAI 都倾向于防御性地倾向于发布模式，使他们能够严格控制其模型的使用方式。但这种控制是虚构的。任何想将 LLM 用于未经批准的目的的人都可以简单地选择免费提供的模型。

Google should establish itself a leader in the open source community, taking the lead by cooperating with, rather than ignoring, the broader conversation. This probably means taking some uncomfortable steps, like publishing the model weights for small ULM variants. This necessarily means relinquishing some control over our models. But this compromise is inevitable. We cannot hope to both drive innovation and control it.  
谷歌应该让自己成为开源社区的领导者，通过与更广泛的对话合作而不是忽视来带头。这可能意味着采取一些不舒服的步骤，比如发布小型 ULM 变体的模型权重。这必然意味着放弃对我们模型的一些控制。但这种妥协是不可避免的。我们不能希望既推动创新又控制创新。

All this talk of open source can feel unfair given OpenAI’s current closed policy. Why do we have to share, if they won’t? But the fact of the matter is, we are already sharing everything with them in the form of the steady flow of poached senior researchers. Until we stem that tide, secrecy is a moot point.  
考虑到 OpenAI 当前的封闭政策，所有这些关于开源的讨论都会让人觉得不公平。如果他们不愿意，我们为什么要分享？但事实是，我们已经以源源不断的挖角高级研究人员的形式与他们分享一切。在我们阻止这种趋势之前，保密是一个有争议的问题。

And in the end, _OpenAI doesn’t matter_. They are making the same mistakes we are in their posture relative to open source, and their ability to maintain an edge is necessarily in question. Open source alternatives can and will eventually eclipse them unless they change their stance. In this respect, at least, we can make the first move.  
最后，OpenAI 并不重要。他们在相对于开源的态度上犯了与我们相同的错误，他们保持优势的能力必然受到质疑。除非他们改变立场，否则开源替代品可以并且最终会使它们黯然失色。至少在这方面，我们可以迈出第一步。

[Meta launches LLaMA](https://ai.facebook.com/blog/large-language-model-llama-meta-ai/), open sourcing the code, but not the weights. At this point, LLaMA is not instruction or conversation tuned. Like many current models, it is a relatively small model (available at 7B, 13B, 33B, and 65B parameters) that has been trained for a relatively large amount of time, and is therefore quite capable relative to its size.  
Meta 推出 LLaMA，开源代码，但不开源权重。在这一点上，LLaMA 没有调整指令或对话。与当前的许多模型一样，它是一个相对较小的模型（可用于 7B、13B、33B 和 65B 参数），已经训练了相对较长的时间，因此相对于它的大小来说相当有能力。

Within a week, [LLaMA is leaked to the public](https://www.vice.com/en/article/xgwqgw/facebooks-powerful-large-language-model-leaks-online-4chan-llama). The impact on the community cannot be overstated. Existing licenses prevent it from being used for commercial purposes, but suddenly anyone is able to experiment. From this point forward, innovations come hard and fast.  
一周之内，LLaMA 就被泄露给了公众。对社区的影响不容小觑。现有许可证禁止将其用于商业目的，但突然之间任何人都可以进行试验。从这一点开始，创新来势汹汹。

A little over a week later, Artem Andreenko [gets the model working on a Raspberry Pi](https://github.com/ggerganov/llama.cpp/issues/58). At this point the model runs too slowly to be practical because the weights must be paged in and out of memory. Nonetheless, this sets the stage for an onslaught of minification efforts.  
一个多星期后，Artem Andreenko 让模型在 Raspberry Pi 上运行。此时模型运行速度太慢而不实用，因为权重必须分页进出内存。尽管如此，这为小型化的冲击奠定了基础。

The next day, Stanford releases [Alpaca](https://crfm.stanford.edu/2023/03/13/alpaca.html), which adds instruction tuning to LLaMA. More important than the actual weights, however, was Eric Wang’s [alpaca-lora](https://github.com/tloen/alpaca-lora) repo, which used [low rank fine-tuning](https://arxiv.org/abs/2106.09685) to do this training “within hours on a single RTX 4090”.  
第二天，斯坦福发布了 Alpaca，它为 LLaMA 添加了指令调优。然而，比实际重量更重要的是 Eric Wang 的 alpaca-lora 存储库，它使用低阶微调“在单个 RTX 4090 上数小时内”完成了此训练。

Suddenly, anyone could fine-tune the model to do anything, kicking off a race to the bottom on low-budget fine-tuning projects. Papers proudly describe their total spend of a few hundred dollars. What’s more, the low rank updates can be distributed easily and separately from the original weights, making them independent of the original license from Meta. Anyone can share and apply them.  
突然之间，任何人都可以微调模型来做任何事情，从而在低预算的微调项目中拉开了一场逐底竞争的序幕。论文自豪地描述了他们总共花费了几百美元。更重要的是，低等级更新可以轻松地与原始权重分开分发，从而使它们独立于 Meta 的原始许可。任何人都可以分享和应用它们。

Georgi Gerganov [uses 4 bit quantization](https://github.com/ggerganov/llama.cpp) to run LLaMA on a MacBook CPU. It is the first “no GPU” solution that is fast enough to be practical.  
Georgi Gerganov 使用 4 位量化在 MacBook CPU 上运行 LLaMA。它是第一个速度足够实用的“无 GPU”解决方案。

The next day, a cross-university collaboration releases [Vicuna](https://lmsys.org/blog/2023-03-30-vicuna/), and uses GPT-4-powered eval to provide qualitative comparisons of model outputs. While the evaluation method is suspect, the model is materially better than earlier variants. **Training Cost: $300.**  
第二天，跨大学合作发布了 Vicuna，并使用 GPT-4 驱动的 eval 来提供模型输出的定性比较。虽然评估方法值得怀疑，但该模型实际上比早期变体更好。培训费用：300 美元。

Notably, they were able to use data from ChatGPT while circumventing restrictions on its API - They simply sampled examples of “impressive” ChatGPT dialogue posted on sites like [ShareGPT](https://sharegpt.com/).  
值得注意的是，他们能够使用来自 ChatGPT 的数据，同时规避对其 API 的限制——他们只是对发布在 ShareGPT 等网站上的“令人印象深刻的”ChatGPT 对话示例进行了采样。

Nomic creates [GPT4All](https://github.com/nomic-ai/gpt4all), which is both a [model](https://s3.amazonaws.com/static.nomic.ai/gpt4all/2023_GPT4All_Technical_Report.pdf) and, more importantly, an [ecosystem](https://github.com/nomic-ai/gpt4all#gpt4all-compatibility-ecosystem). For the first time, we see models (including Vicuna) being gathered together in one place. **Training Cost: $100.**  
Nomic 创建了 GPT4All，它既是一个模型，更重要的是一个生态系统。我们第一次看到模型（包括 Vicuna）聚集在一个地方。培训费用：100 美元。

Cerebras (not to be confused with our own Cerebra) trains the GPT-3 architecture using the optimal compute schedule implied by Chinchilla, and the optimal scaling implied by [μ-parameterization](https://arxiv.org/abs/2203.03466). This outperforms existing GPT-3 clones by a wide margin, and represents the first confirmed use of μ-parameterization “in the wild”. These models are trained from scratch, meaning the community is no longer dependent on LLaMA.  
Cerebras（不要与我们自己的 Cerebra 混淆）使用 Chinchilla 隐含的最佳计算计划和 μ 参数化隐含的最佳缩放来训练 GPT-3 架构。这大大优于现有的 GPT-3 克隆，并且代表了“在野外”首次确认使用 μ 参数化。这些模型是从头开始训练的，这意味着社区不再依赖 LLaMA。

Using a novel Parameter Efficient Fine Tuning (PEFT) technique, [LLaMA-Adapter](https://arxiv.org/pdf/2303.16199.pdf) introduces instruction tuning and multimodality in one hour of training. Impressively, they do so with just 1.2M learnable parameters. The model achieves a new SOTA on multimodal ScienceQA.  
LLaMA-Adapter 使用一种新颖的参数高效微调 (PEFT) 技术，在一小时的训练中引入了指令调优和多模态。令人印象深刻的是，他们仅使用 120 万个可学习参数就可以做到这一点。该模型在多模态 ScienceQA 上实现了新的 SOTA。

Berkeley launches [Koala](https://bair.berkeley.edu/blog/2023/04/03/koala/), a dialogue model trained entirely using freely available data.  
伯克利推出了 Koala，这是一种完全使用免费数据训练的对话模型。

They take the crucial step of measuring real human preferences between their model and ChatGPT. While ChatGPT still holds a slight edge, more than 50% of the time users either prefer Koala or have no preference. **Training Cost: $100.**  
他们采取了关键步骤来衡量他们的模型和 ChatGPT 之间的真实人类偏好。虽然 ChatGPT 仍然略有优势，但超过 50% 的用户要么更喜欢 Koala，要么没有偏好。培训费用：100 美元。

[Open Assistant](https://open-assistant.io/) launches [a model and, more importantly, a dataset](https://drive.google.com/file/d/10iR5hKwFqAKhL3umx8muOWSRm7hs5FqX/view) for Alignment via RLHF. Their model is close (48.3% vs. 51.7%) to ChatGPT in terms of human preference. In addition to LLaMA, they show that this dataset can be applied to Pythia-12B, giving people the option to use a fully open stack to run the model. Moreover, because the dataset is publicly available, it takes RLHF from unachievable to cheap and easy for small experimenters.  
Open Assistant 启动了一个模型，更重要的是，启动了一个用于通过 RLHF 对齐的数据集。他们的模型在人类偏好方面与 ChatGPT 接近（48.3% 对 51.7%）。除了 LLaMA，他们还展示了这个数据集可以应用于 Pythia-12B，让人们可以选择使用完全开放的堆栈来运行模型。此外，由于数据集是公开可用的，因此对于小型实验者而言，RLHF 从无法实现变为廉价且容易。