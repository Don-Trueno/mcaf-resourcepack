# Minecraft愚人节中文翻译包

*嗨，愚人节中文翻译包更新了，来测。*

## 项目背景

从2024年愚人节快照起，愚人节快照的完成度已相当于一个小型模组。但历年愚人节快照所有字符串均不会通过Crowdin进行本地化，导致Wiki相关条目易出现共识问题。由此本人搭建这一项目以期望促进Wiki相关页面共识讨论工作，同时进行“与Wiki相一致的游戏内中文翻译包”的分发工作。

*人话：字符串太多，一个人啃不动。*

## 项目特色

- 尽可能快速、准确的愚人节快照的中文本地化支持。
- 尽可能修复愚人节快照中发现的本地化键名缺失及错别字问题（例如2024年马铃薯牧羊人的纹理文件`shepherd_potato.png`错误拼写为`shepard_potato.png`等）。

## 如何使用

请在[最新Releases](https://github.com/Don-Trueno/mcaf-resourcepack/releases/latest)中下载需要的版本，然后安装到你的游戏。

如果不会安装资源包，请见[这篇条目](https://zh.minecraft.wiki/?curid=10215#%E4%BD%BF%E7%94%A8%E8%B5%84%E6%BA%90%E5%8C%85)。

正在使用**2019年及以前的愚人节快照**？[看看这里吧](#2019年及以前的愚人节快照)。

## 贡献方法

### 参与翻译

Crowdin：[https://crowdin.com/project/mcaf-resourcepack](https://crowdin.com/project/mcaf-resourcepack)

[![zh-CN translation](https://img.shields.io/badge/dynamic/json?color=blue&label=zh-CN&style=flat&logo=crowdin&query=%24.progress.1.data.translationProgress&url=https%3A%2F%2Fbadges.awesome-crowdin.com%2Fstats-15691355-777584-update.json)](https://crowdin.com/project/mcaf-resourcepack)
[![zh-HK translation](https://img.shields.io/badge/dynamic/json?color=blue&label=zh-HK&style=flat&logo=crowdin&query=%24.progress.2.data.translationProgress&url=https%3A%2F%2Fbadges.awesome-crowdin.com%2Fstats-15691355-777584-update.json)](https://crowdin.com/project/mcaf-resourcepack)
[![zh-TW translation](https://img.shields.io/badge/dynamic/json?color=blue&label=zh-TW&style=flat&logo=crowdin&query=%24.progress.3.data.translationProgress&url=https%3A%2F%2Fbadges.awesome-crowdin.com%2Fstats-15691355-777584-update.json)](https://crowdin.com/project/mcaf-resourcepack)
[![lzh translation](https://img.shields.io/badge/dynamic/json?color=blue&label=lzh&style=flat&logo=crowdin&query=%24.progress.0.data.translationProgress&url=https%3A%2F%2Fbadges.awesome-crowdin.com%2Fstats-15691355-777584-update.json)](https://crowdin.com/project/mcaf-resourcepack)

### 反馈问题

若游玩过程中出现英文文本：

- 到Crowdin参与贡献（见[上一段](#参与翻译)）。
- 如果在Crowdin也没发现此文本，大概率为硬编码所致，资源包无法修复此问题。

若游玩过程中出现本地化键名（类似`rule.food_restriction.air_block`）：

- 一般是语言文件中的缺失，可在本仓库[Issues](https://github.com/Don-Trueno/mcaf-resourcepack/issues)中反馈。

## 2019年及以前的愚人节快照

自香港繁体和文言加入后，向前支持直至2019年8月22日发布的快照19w34a。其晚于2019年愚人节快照3D Shareware v1.34的发布时间。对此：

- Crowdin项目和自动打包的资源包中仍会包含相关语言文件，方便Wiki编写时参考。
- 上述两种语言不会出现在语言列表，正常游戏内不可用，使用方法见[下方](#自15w14a至3d-shareware-v134)。
  - 2013年及以前的愚人节快照除外。由于尚未加入简体中文，暂不在本项目计划内。

### 自15w14a至3D Shareware v1.34

若有使用需求，请自行修改压缩包中的`pack.mcmeta`：

```jsonc
{
    "pack": { 
        // 无需修改此段内容
    },
    "language": {
        "zh_hk": {
            "name": "繁體中文",
            "region": "香港特別行政區"
        },
        "lzh": {
            "name": "文言",
            "region": "華夏"
        }
    }
}
```

## 声明

本项目内容采用[CC BY-NC-SA 3.0](https://creativecommons.org/licenses/by-nc-sa/3.0/)授权，可在Minecraft Wiki上使用。

本项目与Mojang和微软亦无从属关系。
