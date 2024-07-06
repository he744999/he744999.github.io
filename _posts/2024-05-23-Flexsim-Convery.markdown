---
layout:     post
title:      "通过Flexsim进行物流线体的仿真"
subtitle:   " \"使用AGV节点抽象处理线体运动\""
date:       2024-06-22 07:00:00
author:     "Hux"
header-img: "img/post-bg-2015.jpg"
catalog: true
tags:
    - Meta
---


# Flexsim 进行线体效率的仿真

托盘线体运行本质是物品在有限节点网络上运动，本方法通过AGV代替线体运行，使用标签+节点控制托盘运动，由Flexsim提供仿真环境



# 场景描述

共1个上料工位， 3个投料工位， 1个空箱回收工位
图纸入下图

![场景线体布局](img/post-bg-2015.jpg, "场景线体布局")

