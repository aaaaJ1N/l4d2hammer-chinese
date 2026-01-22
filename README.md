<h1 align="center">求生之路2 汉化版 Hammer++编辑器</h1>
<h4 align="center">只适用求生之路hammer++</h3>

<p align="center">
  附带已汉化L4D2-FGD-Edits-main可选择安装
</p>

<div align="center">

[![stars](https://img.shields.io/github/stars/Purple-CSGO/CSGO-Config-Presets.svg?style=flat&color=green)](https://github.com/Purple-CSGO/CSGO-Config-Presets)
[![fork](https://img.shields.io/github/forks/Purple-CSGO/CSGO-Config-Presets.svg?style=flat&color=critical)](https://github.com/Purple-CSGO/CSGO-Config-Presets)
![license](https://img.shields.io/badge/license-GPL%203-orange.svg?style=flat)
[![donate](https://img.shields.io/badge/$-donate-ff69b4.svg?style=flat)](https://github.com/Purple-CSGO/CSGO-Config-Presets#捐赠)
[![translation](https://img.shields.io/badge/$-translation-ff69b4.svg?style=flat&color=blueviolet)](https://github.com/Purple-CSGO/CSGO-Config-Presets#翻译)
[![release](https://img.shields.io/github/release/Purple-CSGO/CSGO-Config-Presets.svg?style=flat&color=blue)](https://github.com/Purple-CSGO/CSGO-Config-Presets/releases)

</div>

## 软件简介

项目始于2025年底，汉化hammerplusplus 附带汉化L4D2-FGD-Edits-main 文件：
Hammer 编辑器是 Valve 官方为 Source 引擎开发的地图制作工具，也是《求生之路2》（Left 4 Dead 2）自定义地图创作的核心工具。本版本基于官方最新版 Hammer Editor 及 Hammer++ 增强插件开发，对全部菜单、面板、参数说明及错误提示进行简体中文本地化，解决英文界面带来的操作门槛，让中文用户更高效地创作生存模式、战役模式等自定义地图。
 
核心汉化特色
 
1. 全量文本汉化：覆盖菜单栏、工具栏、属性面板、编译器设置、错误日志等所有界面元素，专业术语翻译精准（如“实体”“纹理”“光照烘焙”等），符合国内地图制作社区习惯。
​
2. UI 适配优化：调整中文字体大小与行间距，避免文本溢出或错位，兼容 1080P/2K 分辨率，保留原版操作逻辑与快捷键布局。
​
3. 增强功能集成：内置 Hammer++ 核心增强特性（如批量选中编辑、实时地形预览），汉化同步覆盖新增功能描述，无需额外安装插件。
​
4. 版本兼容保障：适配《求生之路2》2.2.2.3 及以上版本，支持官方 Authoring Tools 全功能，编译输出的 .bsp 地图文件可直接用于游戏联机。
 
前置依赖
 
1. 安装 Steam 客户端及《求生之路2》正版游戏（需完整下载游戏文件，确保 bin 目录完整）。
​
2. 安装 Steam 工具库中的  Left 4 Dead 2 Authoring Tools （求生之路2 创作工具集），需与游戏版本保持一致。
​
3. 系统需安装 .NET Framework 4.0 及以上运行库（解决汉化补丁运行依赖）。
 
安装步骤
 
1. 基础工具安装
 
1. 打开 Steam，进入「库」→「工具」，搜索「Left 4 Dead 2 Authoring Tools」，点击「安装」，等待下载完成（默认安装路径与游戏一致）。
​
2. 验证游戏文件完整性：右键《求生之路2》→「属性」→「本地文件」→「验证游戏文件的完整性」，修复缺失或损坏的核心文件。
 
2. 汉化版编辑器安装
 
1. 解压汉化包  L4D2_Hammer_Chinese_Pack.zip ，得到  hammer.exe （汉化主程序）、 hammerplusplus_settings.ini （配置文件）及  materials  文件夹（字体资源）。
​
2. 找到《求生之路2》安装目录下的  bin  文件夹（默认路径： Steam\steamapps\common\Left 4 Dead 2\left4dead2\bin ）。
​
3. 将解压后的所有文件复制到  bin  文件夹中，覆盖原有文件（建议先备份原版  hammer.exe  以防回滚）。
​
4. 双击  hammer.exe  即可启动汉化版编辑器，首次启动会自动加载字体配置，需等待 10-20 秒。
 
关键配置指南
 
1. 游戏目录关联
 
1. 启动汉化版 Hammer 后，点击顶部菜单栏「工具」→「选项」→「游戏配置」。
​
2. 在「游戏目录」栏中，选择《求生之路2》的主目录（默认路径： Steam\steamapps\common\Left 4 Dead 2\left4dead2 ）。
​
3. 复制原版 Authoring Tools 的「文件搜索路径」（可从官方 Hammer 中导出），粘贴至汉化版对应配置项，确保能读取游戏内置纹理、模型资源。
 
2. 编译器设置
 
1. 进入「工具」→「选项」→「编译程序」，核对以下参数（确保与游戏路径匹配）：
​
- VBSP 路径： bin\vbsp.exe 
​
- VVIS 路径： bin\vvis.exe 
​
- VRAD 路径： bin\vrad.exe 
​
2. 建议勾选「编译后自动保存」，设置自动保存间隔为 5 分钟，避免地图文件丢失。
 
3. 字体优化（可选）
 
若出现字体模糊或显示异常，可安装推荐字体「方正准圆」，并在「工具」→「选项」→「界面」中选择该字体，调整字号为 10-12 号。
 
常见问题解决
 
1. 编辑器启动闪退：
​
- 检查是否安装 .NET Framework 4.0，未安装则前往微软官网下载安装。
​
- 确认系统区域设置为「中国」，非中文区域需在控制面板中修改（避免编码冲突）。
​
- 验证  Left 4 Dead 2 Authoring Tools  安装完整性，重新安装创作工具集。
​
2. 汉化文本缺失/乱码：
​
- 确保未混合使用其他语言补丁，删除游戏目录下旧版汉化文件。
​
- 检查  bin  文件夹中  materials  字体资源文件夹是否完整，缺失则重新解压汉化包。
​
3. 地图编译失败：
​
- 核对游戏目录配置是否正确，确保「文件搜索路径」包含  left4dead2  主目录。
​
- 检查地图中是否存在未翻译的特殊字符实体名，建议使用英文命名实体与文件夹。
​
4. 联机地图兼容性问题：
​
- 编译时选择「兼容模式」，避免使用 Hammer++ 独家特性（如自定义光照参数）。
​
- 确保游戏版本与汉化编辑器版本匹配，过时补丁可能导致地图加载崩溃。
 
版本信息
 
- 汉化版本：v2.0
​
- 基于内核：Hammer Editor v3.5 + Hammer++ v1.12
​
- 适配游戏版本：Left 4 Dead 2 2.2.2.3 及以上
​
- 汉化完成度：99%（剩余少量第三方插件文本未汉化，不影响核心功能）
 
更新日志
 
- v2.0（2026-01）：
​
- 适配最新版游戏创作工具，修复部分实体属性翻译缺失问题。
​
- 优化编译器错误日志汉化，补充详细报错解决方案提示。
​
- 新增字体自适应功能，自动匹配系统分辨率调整显示效果。
​
- v1.0（2025-08）：
​
- 完成核心界面全量汉化，适配 Hammer++ 基础功能。
​
- 修复中文字体溢出问题，优化面板布局。
 
作者与反馈
 
- 汉化制作：[你的昵称/团队名]
​
- 技术支持：基于 Valve 官方文档及 Source 引擎社区资源
​
- 反馈渠道：[你的邮箱/论坛账号]（欢迎提交翻译错误、功能bug及优化建议，附截图更易排查）
 
免责声明
 
本汉化包仅用于个人学习与非商业地图创作，未经授权不得用于商业用途。汉化包基于官方工具二次开发，版权归 Valve Corporation 所有，如有侵权请联系删除。使用前建议备份游戏原始文件，因使用本汉化包导致的游戏异常，作者不承担相关责任。
