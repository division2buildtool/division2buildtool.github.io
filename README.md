《全境封锁2配装工具》是为游戏[《全境封锁2》](https://www.ubisoft.com/en-us/game/the-division/the-division-2)
开发的第三方工具软件，采用.NET MAUI框架，在Android、Windows、iOS、macOS上构建并发布应用。

[![.NET MAUI](https://img.shields.io/badge/.NET-MAUI-000000?labelColor=512bd4)](https://dotnet.microsoft.com/zh-cn/apps/maui)
![Windows](https://img.shields.io/badge/-Windows10-0078D6?labelColor=0078D6&logo=Windows)
![Android](https://img.shields.io/badge/-Android-000000?labelColor=000000&logo=Android)
![iOS&macOS](https://img.shields.io/badge/-iOS_&_macOS-000000?labelColor=000000&logo=Apple)  

## 主要功能

1.  模拟配装与数据计算 

桌面配装界面：
![桌面界面](https://img2.imgtp.com/2024/03/27/8NUNSt6O.png) 
安卓配装界面：
![安卓界面](https://img2.imgtp.com/2024/03/27/B6Y6ovZ6.png)

2.  游戏数据展示（武器数据、品牌加成、天赋列表、物品搜索等功能）  

![安卓界面](https://img2.imgtp.com/2024/03/27/DlifWOlb.png)
![安卓界面](https://img2.imgtp.com/2024/03/27/VxMyOt9B.png)

## 下载
- [蓝奏云](https://wwbb.lanzout.com/b03vesg4h)     密码:3z9a

## 系统要求

系统           | 最低版本要求                     | 推荐版本要求             
--------------|--------------------------------|---------------------
Windows(x64)  | Windows 10 版本 1809            |Windows 11
Android       | Android 5.0 (API 21)           |Android 7.0 (API 24) 
iOS           | iOS 11                         |iOS 14 或更高版本    
macOS         | macOS 10.15                    |macOS 11 或更高版本

## 安装
### Windows
- 如果之前安装过软件，直接双击安装包文件.msix 以安装应用。

- 对于第一次安装，以下方式二选一：

- 自动安装
  1. 打开【设置】
  1. Win11 请打开【系统】页面，Win10 请打开【更新和安全】页面
  1. 选择【开发者选项】选项，打开【开发人员模式】，等待系统安装一些必要组件
  1. 对 Win10，还需要再单独勾选【从任意源(包括松散文件)安装应用】选项
  1. 向下找到【PowerShell】分区，勾选【更改执行策略，以允许本地PowerShell脚本在未签名的情况下运行。远程脚本需要签名】
  1. 右键 Install.ps1文件，选择使用【PowerShell运行】，会自动安装依赖包并安装软件。
  1. 在初次运行时，安装脚本会在安装证书时提示你提升权限，请按回车(Enter)键继续;在安装证书时，请输入 Y 以继续
  1. 等待安装完成，就可以在开始菜单中找到【全境封锁2配装工具】，如果找不到请使用系统的搜索功能进行查找。
     <details>
       <summary>PowerShell 运行详情</summary>
         <pre><code>
         找到了捆绑:  Division2BuildTool_**.*.*.0_x64.msix  
         找到证书:  Division2BuildTool_**.*.*.0_x64.cer  
         在安装此应用程序之前，需要执行以下操作:  
         -安装签名证书  
         需要具有管理员凭据才能继续。  请接受 UAC 提示并在请求时提供管理员密码。    
         按 Enter 键继续...:  
         正在安装证书...  
         您要将数字证书安装到计算机的受信任人员证书存储区中。这样做有严重的安全风险，只有在信任此数字证书的建立者时才应执     行此操作。  
         当您使用完此应用程序时，应手动移除关联的数字证书。以下网址提供了相关操作说明:  
         http://go.microsoft.com/fwlink/?LinkId=243053  
         是否确实要继续?  
         [Y] 是(Y)  [N] 否(N)  [?] 帮助 (默认值为“N”):  
         正在安装应用程序...  
         找到依赖项包:  
         Microsoft.WindowsAppRuntime.1.*.msix  
         成功: 成功安装了应用程序。  
         按 Enter 键继续...:
         </code></pre>
     </details>

- 手动安装
  1. 双击\Dependencies\x64文件夹下的“Microsoft.WindowsAppRuntime.1.*.msix”依赖项安装包进行安装
  1. 双击“Division2BuildTool_1.*.*.0_x64.cer”打开证书文件
  1. 选择 “安装证书...”
  1. 选择 “本地计算机 ”，然后选择“ 下一步”。
  1. 如果“用户帐户控制”提示“是否允许此应用对设备进行更改？”，请选择“ 是”。
  1. 在 “证书导入向导” 窗口中，选择“将所有证书放入以下存储区”。
  1. 选择“浏览...”，然后选择“受信任人”。 依次选择“确定”“下一步”“完成”。
  1. 双击“Division2BuildTool_1.*.*.0_x64.msix”安装包以安装应用。如果提示无法验证此应用包的发布者证书，说明前面证书安装不成功。 

## 常见问题
- Q：安装时提示：无法验证此应用包的发布者证书。请与系统管理员或应用开发人员联系，以获取具有验证证书的新应用包。必须验证应用包中签名的根证书和所有直接证书

  - A：未安装.cer证书文件，按第2步第一次安装方法操作
  - A：证书文件过期，如果软件未发布新版本，可以手动将系统时间更改到证书生效时间范围后再安装软件（当前证书有效期为2023年11月1日到2024年11月1日），安装完成后即可将时间改回，不影响软件使用。

- Q：双击.msix文件后不能打开，提示选择应用以打开文件
  - A：缺少系统组件【应用安装程序】，可以打开应用商店安装该组件，也可以采用自动安装方法进行安装（推荐）

- Q：安装界面提示“无法安装应用包相关项”，请向开发人员索要应用包
  - A：未安装依赖项安装包，按说明流程进行安装或采用自动安装方法进行安装

- Q：点击图标后程序没有打开
  - A：安装后首次启动可能需要以管理员身份运行（开始菜单中右键应用图标->更多）


## 已知问题

1.  安卓CollectionView在ScrollView中卡顿 [MAUI#17326](https://github.com/dotnet/maui/issues/17326)、[#18505](https://github.com/dotnet/maui/issues/18505)
    - 临时方法：安卓平台使用.NET7
1.  安卓使用CommunityToolkit.Maui的Popup时Label文字显示、断行错误 [MCT#1532](https://github.com/CommunityToolkit/Maui/issues/1532)、[#1592](https://github.com/CommunityToolkit/Maui/issues/1592)、[#1664](https://github.com/CommunityToolkit/Maui/issues/1664)、[#1717](https://github.com/CommunityToolkit/Maui/issues/1717)、[#1724](https://github.com/CommunityToolkit/Maui/issues/1724)
    - 临时方法：安卓平台使用CommunityToolkit.Maui5.2.0，使用Mopups替代



## 开发环境
### [Visual Studio 2022](https://visualstudio.microsoft.com/zh-hans/vs/)
- 工作负荷
    - 桌面应用和移动应用
        - [.NET Multi-platform App UI 开发](https://learn.microsoft.com/zh-cn/dotnet/maui/what-is-maui?view=net-maui-8.0)


## 数据参考和图片素材来源
- [Division 2 Build Making Tool (TU16)](https://docs.google.com/spreadsheets/d/1gdiqJGR0U9yiSX90mVA4bruWfUyWpmsmWsYz4wY7t3Q)
- [Division 2 Gear Spreadsheet](https://docs.google.com/spreadsheets/d/1nrPBmOrtpkEW1j5fbcRT7L-AXgsGOqMqxXoVtopsiGM)
- [Division 2 Gear Attribute Sheet](https://docs.google.com/spreadsheets/d/e/2PACX-1vTJEX5DerCvOj3a_m36TRy1gPBAUvrduOIdmXI9j1Y0MpQk1wIXaZ9KOcPa7HzXzp_N5qGmjDj6yEfL/pubhtml)

## 感谢以下开源项目
* [.NET MAUI - MIT License](https://github.com/dotnet/maui)
* [CommunityToolkit.Maui - MIT License](https://github.com/CommunityToolkit/Maui)
* [CommunityToolkit.Mvvm - MIT License](https://github.com/CommunityToolkit/dotnet)
* [LocalizationResourceManager.Maui - MIT License](https://github.com/SirJohnK/LocalizationResourceManager.Maui)
* [Mopups - BSD-3-Clause License](https://github.com/LuckyDucko/Mopups)
* [Newtonsoft.Json - MIT License](https://github.com/JamesNK/Newtonsoft.Json)
