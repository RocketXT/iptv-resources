# IPTV Resources

一个用于整理和分享 IPTV 台标资源的公开仓库。

本仓库目前主要收录 IPTV 频道台标，适用于 M3U 播放列表、EPG 节目单匹配、媒体服务器直播电视、电视盒子播放器等场景。

## 项目特点

* 台标尺寸统一为 **768 × 768**
* 图片清晰度高，适合电视端、大屏端显示
* 文字风格尽量统一，减少不同来源台标混杂带来的观感差异
* 部分台标为手工绘制、重绘、修复或 AI 辅助绘制
* 适合搭配 GitHub / jsDelivr 作为在线台标源使用

## 目录说明

台标文件统一放在：

```text
/logo
```

示例：

```text
/logo/CCTV1.png
/logo/CGTN纪录.png
/logo/山东卫视.png
/logo/齐鲁频道.png
```

## 使用方式

推荐使用 jsDelivr 链接引用台标：

```text
https://cdn.jsdelivr.net/gh/RocketXT/iptv-resources@main/logo/文件名.png
```

例如：

```text
https://cdn.jsdelivr.net/gh/RocketXT/iptv-resources@main/logo/山东卫视.png
```

在 M3U 播放列表中可以这样使用：

```m3u
#EXTINF:-1 tvg-logo="https://cdn.jsdelivr.net/gh/RocketXT/iptv-resources@main/logo/山东卫视.png",山东卫视
```

## 命名规则

为了方便中文用户识别，本仓库台标文件名会尽量保持直观易懂。

常见命名方式：

```text
CCTV1.png
CCTV5+.png
CCTV4欧洲.png
CGTN纪录.png
北京卫视.png
山东卫视.png
山东齐鲁.png
山东新闻.png
```

文件名以实际仓库中的名称为准，引用时需要与文件名完全一致。

## 适用场景

这些台标可以用于：

* IPTV 播放列表
* M3U / M3U8 频道列表
* EPG 节目单匹配
* APTV、电视直播、酷9、等 IPTV 播放器

## 说明

本仓库仅分享 IPTV 台标资源，不提供直播源、不提供播放地址、不提供节目源。

台标主要用于频道识别、媒体库整理和个人 IPTV 播放列表美化。
如有不合适的图片、错误频道名或需要补充的台标，欢迎反馈。

## 免责声明

本仓库中的台标资源仅用于学习、研究、个人媒体库整理和 IPTV 播放列表美化用途。

部分频道名称、标识、Logo 可能属于对应电视台、频道或相关权利方所有。
如果相关权利方认为本仓库中的内容存在不当使用，请联系删除或调整。

本仓库不提供任何直播信号、不提供任何节目源、不参与任何内容分发。
