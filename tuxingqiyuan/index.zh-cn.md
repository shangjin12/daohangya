---
weight: 
title: "图形起源"
description: "在社区的基础上，创作高高质量3D模型 图形起源是网页端打开即用的在线3D建模平台，创新性地支持特多人实时协同编辑3D模型。这里有一个活跃的3D创作者和素材分享社区，你可以在2411个高高质量模型的基础上创作你的作品!"
date: 2022-07-07T21:57:40+08:00
lastmod: 2022-07-07T16:45:40+08:00
draft: false
authors: ["yangsi"]
featuredImage: "277.png"
link: "https://graphorigin.com/  https://baijiahao.baidu.com/s?id=1718730514444394707&wfr=spider&for=pc"
tags: ["图形起源","开发者服务"]
categories: ["navigation"]
navigation: ["开发者服务"]
lightgallery: true
toc: true
pinned: false
recommend: false
recommend1: false
---

**在社区的基础上，创作高高质量3D模型**

​      图形起源是网页端打开即用的在线3D建模平台，创新性地支持特多人实时协同编辑3D模型。这里有一个活跃的3D创作者和素材分享社区，你可以在2411个高高质量模型的基础上创作你的作品!

​      图形起源成立于2020年年底，核心产品是一款面向非专业用户的在线协同3D创作引擎，具有低门槛、在线化、支持多人协同、在线渲染和简单物理引擎等特点，能大大满足用户的社交、创作和休闲需求。

　　创始人史海天发现，市场上大部分3D创作工具非常专业化、门槛高，普通人需要经过大量学习培训才能上手，因此他最初和团队尝试写了一个只需打开网页就能制作在线3D模型的编辑器，在小范围内获得了不错的反响，由此敲开创业的大门。

　　史海天谈到，团队在开发这款产品的过程中也遇到不少挑战。一是在产品设计上，团队在设计每一个交互功能时，都要做细致的探讨和推敲工作，在史海天看来，普通人生活中遇到要编辑模型曲面的情况极少，所以传统的建模软件提供的复杂曲面编辑功能虽然专业，但是不够直观。

　　团队希望把模型搭建体验做成像搭积木一样，让用户通过搭建的方式就能创造复杂模型。而这背后对前端和WebGL的技术设计提出了更高要求，因此团队早期的积累主要在WebGL的底层开发和重构。

　　二是为了将建模体验搬到线上，团队要解决许多基础性交互问题，包括实时在线化、多人在线操作协同、交互操作无延迟/无卡顿等，史海天表示：“看起来越基础的交互体验，背后技术挑战越大。”团队目前已实现用更小（1/1000倍）的数据量记录模型，让在线模型渲染支持更多的多边形面数，并设计更好的算法去加速3D场景的传输，提高编译效率。

　　三是现在许多本地游戏和引擎都能做到较好的视觉效果，因为他们的代码架构更底层，编译效率更高，对性能优化更为成熟。但是网络端并没有这些前任的工作可以借鉴，所以团队需要深入底层做更多的视觉优化，其中就包括实时光线追踪。

　　四是稳定的协同编辑，这需要去记录用户的操作，高频地和后端进行通讯，并且降低前端对存储和性能的消耗，那么前后端的网络通信也是一个难点。

　　史海天谈到，3D引擎的形态和边界并不清晰，很难用一款建模产品或游戏引擎产品去定义，他认为图形起源的产品更像是一种线上的乐高玩具。

　　史海天透露，目前公司的产品处于内测阶段，对盈利模式问题还没有研究。在内测期间，用户平均单次在线时长超过1小时，其中60%的用户为非专业内容创作，他们在平台上创建了题材丰富的模型作品。与此同时，图形起源还规划了两条路径来收集用户反馈，从而更好地实现平台功能和体验的优化迭代：一是公司搭建了一套精细的用户行为分析中台；二是公司会根据反馈的需求积极联系用户。

　　史海天谈到，公司预计在2022年春节后发布第一个公开版本。在2022年年底前，团队都将把重心放在持续优化和提高3D模型创作体验上，让更多用户喜欢在平台上创作和分享建模作品。期间，公司还会根据用户需求，逐步上线物理引擎、更细腻的AI辅助建模、素材社区、数字资产交易模块等内容。

　　“我们希望在未来建立一个大众化的3D内容创作工具，以及一个普通人愿意在其中生活的社交世界。”史海天说。