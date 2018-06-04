---
layout:     post
title:      "ExoPlayer利用自定义DataSource实现直接播放AES加密音频"
subtitle:   " \"ExoPlayer自定义DataSource\""
date:       2018-06-04 15:55:55
author:     "zhouhaoo"
header-img: "img/post-bg-2015.jpg"
tags:
    - Android
    - ExoPlayer
    - AES
---
## 使用方式
本文的适用范围是使用ExoPlayer框架时，直接解密播放已经经过AES加密过（或者类似需求）的音频或者视频，是利用官方demo内DefaultDataSourceFactory与DefaultDataSource改造而来。