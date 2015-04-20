DanmakuFlameMaster
==================

android上开源弹幕解析绘制引擎项目。[![Build Status](https://travis-ci.org/ctiao/DanmakuFlameMaster.png?branch=master)](https://travis-ci.org/ctiao/DanmakuFlameMaster)

### DFM Inside: 
[![bili](https://raw.github.com/ctiao/ctiao.github.io/master/images/apps/bili.png?raw=true)](https://play.google.com/store/apps/details?id=tv.danmaku.bili)

如果你的项目使用了DFM,并且希望在此处留下链接,请使用官方邮箱与我联系:chenhui@bilibili.com

### Features

- 使用多种方式(View/SurfaceView/TextureView)实现高效绘制

- A站json弹幕格式解析

- B站xml弹幕格式解析

- 基础弹幕精确还原绘制

- 支持mode7特殊弹幕

- 多核机型优化，高效的预缓存机制

- 支持多种显示效果选项实时切换

- 实时弹幕显示支持

- 换行弹幕支持/运动弹幕支持

- 支持自定义字体

- 支持多种弹幕参数设置

- 支持多种方式的弹幕屏蔽

### TODO:

- 继续精确/稳定绘帧周期

- 增加OpenGL ES绘制方式

- 改进缓存策略和效率


### Download
Download the [latest version][1] or grab via Maven:

```xml
<dependency>
  <groupId>com.github.ctiao</groupId>
  <artifactId>dfm</artifactId>
  <version>0.3.1</version>
</dependency>
```

or Gradle:
```groovy
dependencies {
    compile 'com.github.ctiao:dfm:0.3.0'
}
```
Snapshots of the development version are available in [Sonatype's snapshots repository][2].


### License
    Copyright (C) 2013 Chen Hui <calmer91@gmail.com>
    Licensed under the Apache License, Version 2.0 (the "License");


[1]:https://oss.sonatype.org/#nexus-search;gav~com.github.ctiao~dfm~~~
[2]:https://oss.sonatype.org/content/repositories/snapshots/
