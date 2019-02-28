# Mac 鼠须管 Rime 输入法 安装五笔输入法 教程

## 前言

Rime 是一款跨平台的优秀输入法的内核。
该输入法在不同平台的名字也不同

- Windows - 小狼毫
- macOS - 鼠须管
- Linux - ibus-rime

Rime 输入法的优势在于它高度的可自定义化，不单单可以定义输入法码表，还可以定义输入法翻译码表的方式，标点对应等等等等。
高度自定义的特性也使得入门的门槛比较高一些。如果想自定义方案，需要有一定的编程基础，至少有一定的程序语言基础。


## 用极点输入法的原因

用久了五笔的都知道，喜欢五笔的因为是五笔的重码率少，如果码表太多重码就体验很差了。

这里导入的极点版是重码很少的，打起字来很爽的。而且对标点的支持也很好。之前用的 `清歌输入法`，但该输入法有个弊端，对于我这种前端工程师来说，会在工作中用到数字左边那个键 `~`，而清歌输入法把这个键作为临时拼音输入的入口，用起来就各种麻烦。现在换成 RIME 简直爽翻了。 好久没有这么爽的打过字了。

![Rime五笔输入法](media/15513481027613/Rime%E4%BA%94%E7%AC%94%E8%BE%93%E5%85%A5%E6%B3%95.gif)




## 安装 鼠须管

去 [官网下载](https://rime.im/download/)，或者直接点这里下载文章发布时的 [鼠须管 最新版 `0.11`](https://dl.bintray.com/rime/squirrel/Squirrel-0.11.0.zip)
- 官网下载 (https://rime.im/download/)
- 鼠须管 最新版 `0.11` (https://dl.bintray.com/rime/squirrel/Squirrel-0.11.0.zip)

下载后按照步骤安装即可


## 下载 五笔配置文件

为了方便朋友们下载，我新建了一个 github 配置文件仓库，可以直接下载

> 五笔输入法-极点版： https://github.com/KyleBing/rime-wubi86-jidan

其中的文件列表有：

```bash
.
├── README.md                   # 当前说明文档
├── default.custom.yaml         # 用记自定义的一些输入方式或方向
├── pinyin_simp.dict.yaml       # 简体拼音码表 - 五笔中拼音输入需要的
├── pinyin_simp.schema.yaml     # 简体拼音解释器
├── squirrel.custom.yaml        # 输入法候选词界面
├── wubi86.dict.yaml            # 官方五笔码表
├── wubi86.schema.yaml          # 五笔解释器
├── wubi86_jidian.dict.yaml     # 极点 - 五笔码表
├── wubi86_jidian.schema.yaml   # 极点 - 五笔码表解释器
├── wubi_pinyin.schema.yaml     # 五笔拼音混输
└── wubi_trad.schema.yaml       # 五笔简入繁出
```

## 目前的功能特点

- control + 1 呼出设置菜单（在有些应用中可能会失效，换个应用就好）
- 显示 3 个候选词
- 分号`；` 和 引号`‘` 作为二三候选的快捷键
- 4 码唯一时直接上屏

## 设置五笔输入法

Rime 输入法的设置方式：
把配置文件放到配置目录，在状态栏的输入法中选择 `鼠须管`，执行一下 `部署` 就好了。

macOS 上的 刀须管 设置目录是 `~/Library/Rime`

把上面下载的文件移到该目录中，点击 `部署` 即可。



# 关于自定义一些功能

< 这个等有时间再写吧 >