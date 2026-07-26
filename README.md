# 抖仙人

<img src="https://raw.githubusercontent.com/1zzzzzlll/douyim/master/docs/douxianren-icon.png" alt="抖仙人图标" width="160">

面向抖音 Android 客户端的 LSPosed Modern API 102 纯净播放模块。

## 功能

- 播放视频时隐藏视频画面以外的抖音界面和系统栏。
- 暂停视频时立即恢复完整界面，继续播放后再次进入纯净模式。
- 暂停后在右侧操作栏顶部显示下载按钮，将当前无水印视频保存到系统 `Download` 目录。
- 识别广告、图文、长文章及其他非视频条目，并自动切换到下一条内容。
- 安装并启用作用域后默认生效，无需额外配置。

## 兼容范围

| 项目 | 当前支持 |
| --- | --- |
| LSPosed API | Modern API 102 |
| 已验证抖音版本 | 39.7.0（versionCode 390701） |
| Android | 9（API 28）及以上 |
| 作用域 | `com.ss.android.ugc.aweme` |

模块针对抖音 39.7.0 的运行时结构进行适配。抖音升级后，播放器类、数据模型或界面层级可能变化，
届时需要重新适配。

## 安装与使用

1. 在 LSPosed 模块仓库中下载并安装“抖仙人”。
2. 在 LSPosed 中启用模块并勾选默认作用域“抖音”。
3. 强制停止后重新打开抖音。
4. 正常播放时自动进入纯净模式；暂停后恢复界面并显示下载按钮。

## 源码

[1zzzzzlll/douyim](https://github.com/1zzzzzlll/douyim)

## 交流与支持

- Telegram 机器人：[@DDxianren_bot](https://t.me/DDxianren_bot)
- Telegram 交流群：[加入抖仙人交流群](https://t.me/+Owih82lTnaVmNzFl)
