---
title: 如何管理开源项目中的即兴贡献者
date: 2019-08-09 14:26:05
authors:
    - cynbarby
categories:
    - Article
tags:
    - contributor
    - management
---

> **名词解释:**
>
> **Casual contributors**，也被称为是“**episodic volunteering**”，意指那些开源社区中，没有担任特别的职责，偶尔零星的会对社区和项目做出贡献的志愿者们。和像演员的非正式训练，将生活中的某个有趣的片段当做艺术来演绎。故开源之道翻译为即兴。

## 引言

开源是如此的重要，以至于美国政府禁止美国公司和华为进行贸易的事件，让国内的软件界的人倍感压力，甚至就美国政府是否会干涉开源基金会这事，开源社、CSDN 等还专门撰文澄清，也是洋洋软件大国的一大奇观了。

但是毋庸置疑的是，虽然开源软件使用了不少，但是开源社区在国内的发展确实是差了非常多，至今没有一个像样的社区，更加不用提基金会的事情了。**开源之道**还是坚持一贯的主张，努力的去提高认知，掌握开源背后的思想、知识和价值，或许能够在较可预见的期限内能够找到一条成功的路径来。否则，只有倒退。

<!-- more -->

## 正文

> 本文由作者 **Ann Barcomb** 发表在 **Opensource.com 上：https://opensource.com/article/17/10/managing-casual-contributors**。经授权，在开源之道翻译共享。本文在**Creative Commons BY-SA 4.0**许可证下发布。欢迎转载！

![](casual-contributors-management/1tej1likyqh.png)

### 01 - 过客志愿者同样重要

越来越多的人希望是很随意的为项目做出贡献，而不是非得正儿八经的像传统朝九晚五上班的样子。这一现象其实不仅是软件界，在很多志愿者组织以及政府都意识到了这一“**情景化的志愿**”大的趋势，其中的缘由，不能简单的归之于劳动力所发生的变化，这里指的是人们做志愿者的时间在变少，而且人们对待志愿者的态度也在发生着变化。因为它不再被视为是一项**社区义务**，而是成为了一项**有条件的活动**，志愿者是可以从中获得一些利益的。此外，伴随着分布式版本控制系统的成熟，以及 GitHub 所带来的将贡献标准化的网络效应，使得人们很随意的对自由/开源软件（FLOSS）做出贡献。

尽管有充足的理由让社区经理们去重点关注那些可以为社区/项目长期做出贡献的人，以及可能成为长期贡献者的人，但是我这里可能要说点不一样的，那些**过客般的志愿者是同样重要**的。

-   **首先**，事实研究表明，**过客贡献者**的活跃程度对于自由/开源软件项目是有益的，他们可以创新，提高软件质量，并通过社交网络传播项目知识。即使是非代码的贡献者，也可以将项目的内容传播的更为久远。

-   **第二**，尽管很多的社区管理者们都希望将即兴的贡献者转化为长期的贡献者，但是往往遇到的困难重重。很多即兴贡献者都对社区贡献非常的大，但是就是无法为社区贡献过多时间。是不是如果好好的规划的话，他们的工作可能会更为出色。虽然甄别这些贡献值非常的难，除非是改名成员自己做了其它的提交的，但是聊胜于无，拥有一个**管理的战略计划**是非常必要的。本文中推荐的刴实践是蛮适合营收和习惯性贡献者的，因此，想获得他们，并是一件困难的事情。

-   **第三**，这些即兴的贡献者，可能已经成为社区的一部分了，但是却对他们却视而不见，没有做到有效管理。能够意识到即兴贡献者并非是一次性的参与者是非常重要的。和那些长期的持续贡献者一样，他们的留存就可能在未来会返回继续承接新的任务。我们知道对于社区的新晋人员来说，需要更多的**帮助以及时间**培养，方能提高转换为贡献者，再退一不讲，即使是他们不能做到持久的贡献，但是他们已经对社区现有的工作方式非常的熟悉了，这本身就难能可贵。

### 02 - 吸引并留存即兴贡献者的五大因素

经过多年的研究，我们以为吸引并留存即兴贡献者有五块重大的因素，下图所展示的是基于论文： Hyde, Dunn, Bax and Chambers (2016)，该示意图描述了这些因素，以及因素之间的关系的**简化模型**，以及从个人出发的路径图。

![](casual-contributors-management/2muxj9g4j68.png)

这些因素整体上可以区分为两个大类：前提和体验。前提是在该人开始参与之前存在的因素，并且更倾向于影响新的贡献者。经验是参与的结果，对长期临时参与者来说是一个更加明显的因素。所有五个因素 —— **动机、社会规范、心理社区意识、满意度、组织承诺** —— 都会影响到最后的留存率。志愿者的留存率是其未来参与的唯一最佳预测因素，因此这里作为最终的衡量。

-   **动机**：预测即兴贡献者的留存，**个人利益**、**享受**、以及**社交**等项是最为重要的动机，那些想要给自己简历添上一笔精彩，或者是寻找更具挑战性的程序漏洞，一旦满足了他们的需求，他们就有可能对项目兴趣索然了，相比之下，那些想要在其中找到乐趣或者是社交互动的人，如果口味对了，那么他们更有可能继续；但是这些人也会出现问题，那就是他们很可能会被项目中高深的技术所吓倒，尤其是那些确定在何处更改代码以修复错误的挑战。

-   **社会规范**：在这里，社会规范指的是参与者是否认为其他人赞成或反对该活动。由于普通公众不太可能对提供 FLOSS **(Free/Libre and Open Source Software)** 有强烈的意见，与其他类型的志愿者活动相比，这不是 FLOSS 的一个因素。然而，与任何类型的志愿者一样，FLOSS 参与者（尤其是非代码贡献者）很可能会响应个人邀请，让他们认识的人做出贡献。

-   **心理社区意识**：这指的是一个人在 FLOSS 社区中获得的支持和被接受时的感受程度。很多情况下，在社区受到欢迎的人更有可能留下来。在我们的研究中，许多人将**包容性**描述为热情氛围的重要组成部分，因为包容性有助于人们对社区产生更为积极的情感。

-   **满意度**：该因素描述了人们的期望与实际贡献经验之间的匹配程度。满意度来自于是否**受到欣赏**、**拥有充实的关系**、**能在工作中找到乐趣**、**以及知道自己的劳动成果是有实际用处的**。当人们谈论他们留下的理由时，他们多数是在谈论着满意度。

-   **组织承诺**：在长期贡献者中最常见的是对 FLOSS 社区的忠诚度和认同度。即兴贡献者可以像长期持续的贡献者一样投入到社区中来的，这就是为什么使用 **“偶发性 (episodic)”**一词，因为他们并不会不负责任。就我对 FLOSS 社区的调查当中，发现喜欢谈论参与的人更有可能想留下来。当然，这未必一定会发生，即强烈的因果关系，但是这有助于寻找潜在的目标。

### 03 - 创建管理即兴贡献者的战略

有了上述的五个因素的梳理，我们就明确了参与和留存的重要衡量指标，那么社区就可以基于这些来制定管理即兴贡献者的具体策略了。志愿者的策略应该包括如下内容：

-   **预期的输出结果**

-   **适合于即兴贡献者的任务**

-   **确定并推广支持这些目标的做法**

-   **对结果的衡量**

同时还要计算，对于这些即兴贡献者的投入费用，不得超过他们能够带来的益处。（赔本的买卖似乎没有人干:-)）

在刚开始的时候，对于社区的即兴贡献者来说似乎是没有那么难以理解的，但是过上一阵子之后，你就需要特别的对待他们了，因为想充分的利用起来他们，当然也想让他们留下来，长久、持续的为社区做出贡献。

为了找到合适的任务，我们可以将即兴贡献者区分为两种类型：多面手和专家。能充分发挥他们的能力是难以做到的，虽然有些人拥有特定的技能，我们称之为“专家”。应该为他们寻找、归类适合他们自身的任务。

最适合多面手的任务有：

-   **需要较少的努力，能够快速完成**

-   **是较小的聚焦细节**

-   **需要很少的前期投资**

-   **可以分成更小的部分**

-   **不要求熟练劳动力**

-   **让那些长期的持续贡献者去做更大型、更重要的任务**

对于专家来说，只有一个建议：

> **将专家的领域知识与项目特定的细节分开**

注意到即兴贡献者可以在社区内开展许多种不同的活动，这点蛮重要的。不要将他们限定于某一类型的工作，最好是让他们自己进行选择，这是更有效率的一种方式。此外，各个社区是不一样的，社区管理者必须考虑他们自身，以针对性、变通性的方式来将上述的任务安排妥当。

### 04 - 管理即兴贡献者的实践

关于如何管理即兴贡献者的实践，或者叫做可能的路径，我已经有了明确的答案，将这些实践与其对即兴贡献者的影响联系起来，可以明确使用上面谈到的五大因素，进而实现即兴贡献者的参与和留存。

并非所有社区的理想或实践都是理想的或实用的，这个列表当然不是详尽无遗的。其实很多社区都已经实施了针对贡献者的各种实践，但是目前来看还很少有针对即兴贡献者的，以下所列，不仅适用于即兴贡献者，也适用于长期的、持续的贡献者。

当然，我也并不能保证这些实践适合所有的社区，但是至少可以为大家提供一个可以参考的模型，从而说明为即兴贡献者提供管理的策略是一件明智的事情。

![](casual-contributors-management/2k3cc1ip58o.png)

即兴的贡献者长久以来一直都在 FLOSS 社区中大量的存在，但是很少被特别的关照到。我们现在已经看到了这些贡献者的诸般好处了，如果能够让他们做到更多的“即兴”，那么我们就需要去思考一个更能吸引历史贡献者的策略。有效的利用起来即兴贡献者的五个因素（动机、社会规范、社区心理意识、满意度，以及组织承诺），进而思考社区如何做才能够影响到他们，从而找到一个合理的、量身定制的即兴贡献者。

## 进一步的信息

以上这些还是作者正在进行的博士研究当中所摘取的简化版，有兴趣的看官，想进一步了解论文的全部的话，可以在作者的个人站点上进行浏览。

### 关于作者

![](casual-contributors-management/2ra4chrt5y.png)

Ann Barcomb 是爱尔兰利默里克大学 Lero 的研究助理和在读博士。她在过去研究过一阵子关于自由软件和社会运动的内容，现在则聚焦于开源中的情景化的管理或者是临时的志愿者，而当下的工作是建立在过去的基础之上的。在成为研究员之前，Barcomb 曾担任软件开发人员，之后担任 RIPE NCC 的社区经理。她帮助组织了欧洲 Perl Hackathon 2007，Gnash Hackathon 2007 和 YAPC :: Europe 2001，此外还在 2002 - 2011 年期间在 YAPC :: Europe Foundation 董事会任职。她曾在 OpenSym，OSS，NaMeX，FRnOG，荷兰 Perl 研讨会，斯洛文尼亚 Linux Konferenca，YAPC :: Europe 和 OSCON 等会议上发表过演讲。
