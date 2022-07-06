---
weight: 
title: "LINGO3D 是一个WEB原生的3D创建工具和开源 React"
description: "Lingo3D"
date: 2022-07-06T21:57:40+08:00
lastmod: 2022-07-06T16:45:40+08:00
draft: false
authors: ["yangsi"]
featuredImage: "286.jpg"
link: "https://lingo3d.com/  https://blog.csdn.net/BWater_monster/article/details/124680311"
tags: ["Lingo3D","开发者服务"]
categories: ["navigation"]
navigation: ["开发者服务"]
lightgallery: true
toc: true
pinned: false
recommend: false
recommend1: false
---

LINGO3D是一个WEB原生的3D创建工具和开源 React

Lingo3D 是一个 Web 端 3D 游戏开发工具链，能让开发者通过 React 和 JavaScript 开发出炫目的3D沉浸式体验。

**自动地图碰撞**

Lingo3D 对 CannonJS 物理引擎的增强允许自动计算角色、对象和游戏世界地图之间的高保真碰撞。

**高级字符系统**

Lingo3D 的虚拟系统可实现游戏和角色动画的快速原型制作。Dummy System 带有内置的反向运动学，并支持使用第三方工具创建的角色模型的动画重定向。

**智能摄像系统**

Lingo3D 的相机系统具有自动剪辑避免和不同相机之间的插值等功能，非常适合创建第一人称和第三人称游戏。

**智能性能**

Lingo3D 可以在运行时自动生成 3d 资产的低多边形版本，从而实现动态 LOD（细节层次）。结合 Lingo3D 对动态分辨率的内置支持，最终可以在 Web 上实现大规模的开放世界。

**所需相关技术：**
1、Vite
一款前端构建工具，跟着官方文档走一下，create一个项目即可，不需要了解很多
当然如果业务需求很多了，可能需要了解这个工具的配置项什么的，可能会有冲突

2、TS
支持TS，也支持JS，如果觉TS很搞，可以使用JS，但是还是建议使用TS，如果你要构建一个长久维护的项目的话。

3、状态机xstate
用来管理你的键盘事件与动画状态的关系

4、模型材质相关
建议使用blender进行模型处理，blender2.93LTS版本

- 人物模型：1、mixamo下载角色及动作动画；2、blender自己建模，导出fbx格式后上传至mixamo进行骨骼绑定后下载角色及动作动画；3、readyplayer.me用照片生成的人物模型，导入blender后导出fbx格式，上传至mixamo进行骨骼绑定后下载角色及动作动画。
- 场景模型：sketchfab、blendswap、模之屋。
- 环境光模型：熟悉建模的朋友应该知道光是建模当中很重要的一个概念。Lingo3D支持hdr的图片，可以用hdr进行光照模拟。
- 天空图：Google搜索关键字： equirectangular sky / skybox background ，也可直接用hdr图片当作天空图。