《全境封锁2配装工具》是为游戏[《全境封锁2》](https://www.ubisoft.com/en-us/game/the-division/the-division-2)
开发的第三方工具软件，采用.NET MAUI框架，在Android、Windows、iOS、macOS上构建并发布应用。

## 主要功能

1.  模拟配装与数据计算 
2.  游戏相关数据展示（包括武器数据、品牌加成、天赋列表、装备搜索、玩家数据查询等功能） 

## 软件界面
![桌面端界面](/img/screenshot.png) 

## [软件使用🔗](https://division2buildtool.github.io/introduction)

## 软件下载
- [蓝奏云](https://wwbb.lanzout.com/b03vesg4h)     密码：3z9a

    移动端下载apk/ipa文件时可能会提示需要会员才能分享，将手机浏览器的界面切换为桌面模式，即可跳过限制下载文件。

## 系统要求

系统           | 最低版本要求                     | 推荐版本要求 (部分功能需求)            
--------------|--------------------------------|---------------------
Windows(x64)  | Windows 10 版本 1809            |Windows 10 版本 1809 
Android       | Android 5.0                    |Android 7.0
iOS           | iOS 11                         |iOS 14
macOS         | macOS 10.15                    |macOS 11

## 软件安装

### iOS系统
软件ipa安装包未签名，需要自签后进行安装。

### [Windows系统安装🔗](https://division2buildtool.github.io/installation)


## 已知问题

1.  安卓CollectionView在ScrollView中卡顿 [MAUI#17326](https://github.com/dotnet/maui/issues/17326)、[#18505](https://github.com/dotnet/maui/issues/18505)
    - 临时方法：安卓平台使用.NET7
1.  安卓使用CommunityToolkit.Maui的Popup时Label文字显示、断行错误 [MCT#1532](https://github.com/CommunityToolkit/Maui/issues/1532)、[#1592](https://github.com/CommunityToolkit/Maui/issues/1592)、[#1664](https://github.com/CommunityToolkit/Maui/issues/1664)、[#1717](https://github.com/CommunityToolkit/Maui/issues/1717)、[#1724](https://github.com/CommunityToolkit/Maui/issues/1724)
    - 临时方法：安卓平台使用Mopups和旧版本CommunityToolkit.Maui(v5.2.0)
1.  Windows平台存在安装后不能打开的问题
    - 未确定原因，可能相关[#21744](https://github.com/dotnet/maui/issues/21744)



## 开发环境
### [Visual Studio 2022](https://visualstudio.microsoft.com/zh-hans/vs/)
- 工作负荷
    - 桌面应用和移动应用
        - [.NET Multi-platform App UI 开发](https://learn.microsoft.com/zh-cn/dotnet/maui/what-is-maui?view=net-maui-8.0)


## 数据参考和图片素材来源
- [Division 2 Build Making Tool (TU16)](https://docs.google.com/spreadsheets/d/1gdiqJGR0U9yiSX90mVA4bruWfUyWpmsmWsYz4wY7t3Q)
- [Division 2 Gear Spreadsheet](https://docs.google.com/spreadsheets/d/1nrPBmOrtpkEW1j5fbcRT7L-AXgsGOqMqxXoVtopsiGM)
- [Division 2 Gear Attribute Sheet](https://docs.google.com/spreadsheets/d/e/2PACX-1vTJEX5DerCvOj3a_m36TRy1gPBAUvrduOIdmXI9j1Y0MpQk1wIXaZ9KOcPa7HzXzp_N5qGmjDj6yEfL/pubhtml)
- [全境封锁2 TU17敌怪【血量统计】](https://www.bilibili.com/video/BV1C84y1P7Cr)
- [TU19猎头者伤害公式](https://tieba.baidu.com/p/8809994501)
- [The Division 2: Weekly Vendor Reset - Ruben Alamina](https://rubenalamina.mx/the-division-weekly-vendor-reset/)
- [The Division 2 Stats](https://tracker.gg/division-2)
- [Ubisoft Help](https://www.ubisoft.com/zh-cn/help/game/the-division-2)

## 感谢以下开源项目
* [.NET MAUI - MIT License](https://github.com/dotnet/maui)
* [ASP.NET Core Blazor - MIT License](https://github.com/dotnet/aspnetcore)
* [CommunityToolkit.Maui - MIT License](https://github.com/CommunityToolkit/Maui)
* [CommunityToolkit.Mvvm - MIT License](https://github.com/CommunityToolkit/dotnet)
* [LocalizationResourceManager.Maui - MIT License](https://github.com/SirJohnK/LocalizationResourceManager.Maui)
* [Mopups - BSD-3-Clause License](https://github.com/LuckyDucko/Mopups)
* [Newtonsoft.Json - MIT License](https://github.com/JamesNK/Newtonsoft.Json)
