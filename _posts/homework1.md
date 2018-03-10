﻿---
layout: post
title: 系统分析与设计作业一
date: 2018-3-10 22:00:10+00:00
categories: 日志
tags: 博客
---

1.简单题
• 软件工程的定义
答： 软件工程：(1)将系统化、规范化、可度量的 方法应用与软件的开发、运行和维护的过程， 即将工程化应用于软件中。(2)对(1)中所述方法 的研究。——IEEE[IEE93]。是指导计算机软件开发和维护的 工程学科。采用工程的概念、原理、技术和方 法来开发与维护软件，把经过实践考验而证明 正确的管理技术和当前能够得到的最好的技术 方法结合起来，这就是软件工程。

•阅读经典名著“人月神话”等资料，解释 software crisis、COCOMO 模型。
答： software crisis：软件危机是指落后的软件生产方式无法满足迅速增长的计算机软件需求，从而导致软件开发与维护过程中出现一系列严重问题的现象。在《人月神话》中作者谈论到大型软件开发的成本随着规模指数性增加，在缺乏一定的方法论的情况下开发大型软件可能会导致难以预料的后果，可能导致软件极端复杂，难以按时交付，问题百出等情况，而加入更多的人力往往是火上浇油，非但不能使开发难度下降，还可能会让进度变得更加延后。
COCOMO 模型：COCOMO，英文全称为constructive cost model，中文为构造性成本模型。它是一种精确、易于使用的，基于模型的成本估算方法，最早由勃姆 （Boehm） 于 1981 年提出。从本质上说是一种参数化的项目估算方法，参数建模是把项目的某些特征作为参数，通过建立一个数字模型预测项目成本（类似于居住面积作为参数计算的整体的住房成本）。

•软件生命周期
答： 从时间角度，把整个周期划分为若干个阶段。划分的原则：各阶段的任务彼此间尽可能相对独立，同一个阶段各项任务的性质尽可能相同，从而降低每个阶段任务的复杂性，简化不同阶段之间的联系，有利于软件开发过程的组织管理。受软件规模、性质、种类、开发方法等因素的影响。 

•按照SWEBok的KA划分，本课程关注哪些KA或知识领域？
答： 本课程关注软件需求、软件设计、软件构造、软件工程工具和方法这几个知识域。

•解释 CMMI 的五个级别。例如：Level 1 - Initial：无序，自发生产模式。
答： Level 2 -Managed：可管理级。建立了基本的项目管理过程来跟踪费用、进度和功能特性。制定了必要的过程纪律，能重复早先类似应用项目取得的成功经验。
Level 3 -Defined：已定义级。已将软件管理和工程两方面的过程文档化、标准化，并综合成该组织的标准软件过程。所有项目均使用经批准、剪裁的标准软件过程来开发和维护软件，软件产品的生产在整个软件过程是可见的。
Level 4 -Quantitatively Managed：量化管理级。分析对软件过程和产品质量的详细度量数据，对软件过程和产品都有定量的理解与控制。管理有一个作出结论的客观依据，管理能够在定量的范围内预测性能。
Level 5 -Optiming 优化管理级。过程的量化反馈和先进的新思想、新技术促使过程持续不断改进。

•用自己语言简述 SWEBok 或 CMMI （约200字）
答： CMMI全称是Capability Maturity Model Integration，即能力成熟度模型集成，是美国国防部的一个设想。就是想把现在所有现存实施的与即将被发展出来的各种能力成熟度模型，集成到一个框架中去，申请此认证的前提条件是该企业具有有效的软件企业认定证书。目的是帮助软件企业对软件工程过程进行管理和改进，增强开发与改进里，从而能按时的、不超过预算的开发出高质量的软件。其所依据的想法是：只要集中精力持续努力去建立有效的软件工程过程的基础结构，不断进行管理的实践和过程的改进，就可以克服软件开发中的困难。在我看来就是在软件开发出气，大家都是毫无目的毫无管理的去做软件，效率低下，费时费力费资金。然后一些人发现，这样不行呀，所以就想出来CMMI，这样一步一步的去完善开发软件的过程。CMMI为改进一个组织的各种过程提供了一个单一的集成化框架，新的集成模型框架消除了各个模型的不一致性，减少了模型间的重复，增加透明度和理解，建立了一个自动的、可扩展的框架。因而能够从总体上改进组织的质量和效率。CMMI主要关注点就是成本效益、明确重点、过程集中和灵活性四个方面。

解释 PSP 各项指标及技能要求：
•阅读《现代软件工程》的 PSP: Personal Software Process 章节。 

•按表格 PSP 2.1，了解一个软件工程师在接到一个任务之后要做什么，需要哪些技能，解释你打算如何统计每项数据？ （期末考核，每人按开发阶段提交这个表）
PSP 2.1 : ![](https://github.com/LTimmy/LTimmy.github.io/tree/master/_posts/PSP2.1.png)

答：要统计每项数据的时间要计算真实的工作时间，要去除休息吃饭的时间。测试报告要把测试的过程和结果写成文档，对发现的问题和缺陷进行分析。还需要注意一些阶段并不是连续的，比如测试可能和具体的编码工作是同时展开，需要具体进行区分。






