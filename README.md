# 鸿蒙电脑（HarmonyOS PC）开发编程工具盘点

> 面向开发者整理：华为应用市场上架的开发/编程工具（含“应用尝鲜”渠道）、开源社区移植的开源应用、AI 工具版图（GUI 应用 × 开源 CLI），以及各语言新手开发指南。
> 信息截至 2026-10，持续更新中。如链接失效，请在鸿蒙电脑的“华为应用市场”中直接搜索工具名。

## 目录

- [一、官方 IDE 与 AI 开发套件](#一官方-ide-与-ai-开发套件)
- [二、版本控制与代码托管](#二版本控制与代码托管)
- [三、终端与远程开发](#三终端与远程开发)
- [四、辅助与效率工具](#四辅助与效率工具)
- [五、开源社区鸿蒙应用](#五开源社区鸿蒙应用)
- [六、新手开发实践指南](#六新手开发实践指南)
- [七、AI 工具版图（GUI 应用 × 开源 CLI）](#七ai-工具版图gui-应用--开源-cli)
- [八、说明与建议](#八说明与建议)
- [相关资源](#相关资源)

## 一、官方 IDE 与 AI 开发套件

| 工具 | 简介 | 获取方式 / 下载链接 |
| --- | --- | --- |
| **DevEco Studio（鸿蒙电脑版）** | 首个原生运行在鸿蒙电脑上的 HarmonyOS 应用 IDE，基于毕方（BitFun）平台构建：代码编辑、编译构建、调试、性能调优、多设备预览一体化。2026-10-08 起开放公测（26.0.0.201 Beta1） | 应用市场 > 我的 > 应用尝鲜；[官方安装指南](https://developer.huawei.com/consumer/cn/doc/harmonyos-guides/ide-hmos-software-install) |
| **DevEco Code（鸿蒙 PC 版）** | 一站式鸿蒙应用 AI Agent 开发工具，内置 GLM5.3 / GLM5.1 等大模型，支持 Plan / Build / Goal 多种开发模式，集成鸿蒙知识库、Skills 与 MCP | 应用市场搜索“DevEco Code” |
| **DevEco CLI（鸿蒙 PC 版）** | 命令行 AI 开发套件，一条 init 命令即可把鸿蒙开发 Skill 部署到本机各类 Agent 工具，打通终端开发流 | 随 DevEco Studio 公测发布；见官方文档 |
| **CodeArt IDE** | 华为云轻量级代码编辑器，支持多语言开发，界面简洁 | 应用市场 > 我的 > 应用尝鲜 |

## 二、版本控制与代码托管

| 工具 | 简介 | 下载链接 |
| --- | --- | --- |
| **GitNext** | 鸿蒙原生 Git 客户端，随时查看与管理代码仓库 | [应用市场详情页](https://appgallery.huawei.com/app/detail?id=com.develop.opensource.gitnext) |
| **HmCodeHub** | 鸿蒙电脑上的 GitHub 客户端，浏览仓库、Issue 等更顺手 | [应用市场详情页](https://appgallery.huawei.com/app/detail?id=xyz.zhousg.harmony_github) |

## 三、终端与远程开发

| 工具 | 简介 | 下载链接 |
| --- | --- | --- |
| **CrossShellNext** | SSH 终端工具，支持多会话管理与密钥登录，远程开发必备 | [应用市场详情页](https://appgallery.huawei.com/app/detail?id=com.develop.opensource.CrossShellNext) |
| **FtpNextClient** | 免费 FTP / SFTP / Telnet 客户端，本地与远程文件互传 | [应用市场详情页](https://appgallery.huawei.com/app/detail?id=com.develop.opensource.ftpnext_client) |
| **FtpNextServer** | 免费 FTP / SSH / Telnet 服务器端，把鸿蒙电脑变成远程主机 | [应用市场详情页](https://appgallery.huawei.com/app/detail?id=com.develop.opensource.ftpnext_server) |

## 四、辅助与效率工具

| 工具 | 简介 | 下载链接 |
| --- | --- | --- |
| **DevBox** | 面向鸿蒙 PC 的开发者工具集，常用开发小工具一站式获取 | [应用市场详情页](https://appgallery.huawei.com/app/detail?id=com.develop.opensource.devbox) |
| **鸿蒙JSON转对象工具** | JSON 快速转鸿蒙数据类（ArkTS），省去手写样板代码 | [应用市场详情页](https://appgallery.huawei.com/app/detail?id=top.sevenfire.ccjsonzs) |
| **HMOS代码工坊** | 华为官方示例代码库，分类浏览可直接运行的应用案例 | 应用市场搜索“HMOS代码工坊” |

## 五、开源社区鸿蒙应用

> 以下应用由开源社区移植贡献，均已在华为应用市场上架（括号内为上架名）。清单来源：[OpenHarmonyPCDeveloper/harmony-pc-apps](https://gitcode.com/OpenHarmonyPCDeveloper/harmony-pc-apps)，欢迎参与共建。

### 音视频与多媒体

| 应用（上架名） | 功能简介 | 开源地址 |
| --- | --- | --- |
| **Audacity**（AirAudio） | 多轨音频录制与编辑工具，可完成录音、剪辑、降噪及音频混音处理 | [Harmony-Audacity](https://gitcode.com/Andy88/Harmony-Audacity) |
| **Ardour**（AirDaw） | 数字音频工作站，支持多轨录音、MIDI 编曲、混音与母带处理 | [Harmony-Ardour](https://gitcode.com/Andy88/Harmony-Ardour) |
| **MuseScore Studio**（AirScore） | 乐谱制作软件，支持创建、编辑与播放乐谱，可输出乐谱或音频 | [Harmony-MuseScore](https://gitcode.com/Andy88/Harmony-MuseScore) |
| **Neothesia**（AirMidi） | MIDI 练琴可视化工具，音符以彩色瀑布流在虚拟钢琴上展示，辅助快速学琴 | [Harmony-Neothesia](https://gitcode.com/Andy88/Harmony-Neothesia) |
| **OBS Studio**（AirCast） | 录屏与直播推流软件，支持多场景采集、画面合成与实时音视频推流 | [Harmony-OBS-Studio](https://gitcode.com/Andy88/Harmony-OBS-Studio) |
| **VLC**（AirPlayer） | 全能多媒体播放器，支持几乎所有音视频格式及网络流媒体播放 | [Harmony-VLC](https://gitcode.com/Andy88/Harmony-VLC) |
| **HandBrake**（AirBrake） | 视频转码压缩工具，支持将多种格式视频批量转换为 MP4/MKV | [Harmony-HandBrake](https://gitcode.com/Andy88/Harmony-HandBrake) |
| **kdenlive**（AirLive） | 多轨非线性视频编辑软件，支持剪辑、特效、字幕与音频混合处理 | [Harmony-kdenlive](https://gitcode.com/Andy88/Harmony-kdenlive) |
| **Shotcut**（轻剪辑） | 跨平台视频编辑器，支持多格式时间线剪辑、滤镜特效与成片导出 | [Harmony-Shotcut](https://gitcode.com/Andy88/Harmony-Shotcut) |

### 图形图像与设计

| 应用（上架名） | 功能简介 | 开源地址 |
| --- | --- | --- |
| **GIMP**（AirPS / AirPhoto） | 跨平台图像编辑器，提供图层、蒙版、滤镜等专业修图能力 | [Harmony-Gimp-OHOS](https://gitcode.com/Andy88/Harmony-Gimp-OHOS) |
| **Krita**（AirDraw） | 数字绘画软件，专业笔刷引擎与笔压感应，适用于插画、漫画与概念设计创作 | [Harmony-krita](https://gitcode.com/Andy88/Harmony-krita) |
| **Inkscape**（AirScape） | 矢量图形编辑软件，用于绘制 SVG 图标、插画与版式设计 | [Harmony-Inkscape-OHOS](https://gitcode.com/Andy88/Harmony-Inkscape-OHOS) |
| **PixiEditor**（轻像素） | 通用 2D 图像编辑器，集像素画、绘画与矢量工具于一体，支持逐帧动画制作 | [PixiEditor](https://github.com/PixiEditor/PixiEditor) |
| **Friction**（AirFx） | 二维动效图形软件，支持矢量与位图动画创作，可输出网页及视频动画 | [Harmony-Friction](https://gitcode.com/Andy88/Harmony-Friction) |
| **digiKam**（AirKam） | 照片库管理软件，支持批量整理、标签检索、人脸识别及 RAW 照片编辑 | [Harmony-digiKam](https://gitcode.com/Andy88/Harmony-digiKam) |
| **RawTherapee**（AirRT） | RAW 照片处理软件，提供色彩、曝光、降噪等精细暗房调整能力 | [Harmony-RawTherapee](https://gitcode.com/Andy88/Harmony-RawTherapee) |
| **darktable**（AirRaw） | 摄影后期暗房软件，支持 RAW 冲图、非破坏性编辑与色彩管理 | [Harmony-darktable](https://gitcode.com/Andy88/Harmony-darktable) |

### CAD 与工程制图

| 应用（上架名） | 功能简介 | 开源地址 |
| --- | --- | --- |
| **FreeCAD**（AirCad） | 参数化 3D CAD 建模软件，用于机械产品设计与工程建模 | [Harmony-freecad](https://gitcode.com/Andy88/Harmony-freecad) |
| **LibreCAD**（AirDraft） | 二维工程制图软件，用于绘制与标注机械、建筑等设计图纸 | [Harmony-LibreCAD](https://gitcode.com/Andy88/Harmony-LibreCAD) |
| **OpenSCAD**（AirSCAD） | 代码式 3D 建模软件，通过编写脚本创建精确的参数化实体模型 | [Harmony-OpenSCAD](https://gitcode.com/Andy88/Harmony-OpenSCAD) |
| **KiCad**（AirEDA） | 电子设计自动化（EDA）套件，支持原理图绘制、PCB 布线与 3D 板级预览 | [Harmony-KiCad](https://gitcode.com/Andy88/Harmony-KiCad) |

### 办公与阅读

| 应用（上架名） | 功能简介 | 开源地址 |
| --- | --- | --- |
| **LibreOffice**（AirWord） | 办公套件，包含文字处理、电子表格、演示文稿等完整办公模块 | [Harmony-LibreOffice](https://gitcode.com/Andy88/Harmony-LibreOffice) |
| **ONLYOFFICE Desktop Editors**（AirOffice） | 办公文档套件，支持编辑文字、表格与演示文稿并兼容 Office 格式 | [Harmony-ONLYOFFICE](https://gitcode.com/Andy88/Harmony-ONLYOFFICE) |
| **Scribus**（AirPress） | 桌面排版软件，用于设计海报、杂志等出版物并输出专业级 PDF | [Harmony-Scribus](https://gitcode.com/Andy88/Harmony-Scribus) |
| **Okular**（AirReader） | 文档阅读器，支持 PDF、EPUB 等多种格式查看与批注 | [Harmony-Okular](https://gitcode.com/Andy88/Harmony-Okular) |
| **calibre**（AirShelf） | 电子书管理工具，支持书库整理、格式转换、元数据编辑与阅读同步 | [Harmony-calibre](https://gitcode.com/Andy88/Harmony-calibre) |
| **Zotero**（轻学术） | 文献管理工具，支持收集整理论文、自动抓取元数据并生成规范引用 | [Harmony-zotero](https://gitcode.com/Andy88/Harmony-zotero) |
| **TeXstudio**（AirTex） | LaTeX 写作环境，提供语法高亮、自动补全与内置预览，用于科技文档排版 | [Harmony-TeXstudio](https://gitcode.com/Andy88/Harmony-TeXstudio) |

### 开发与网络工具

| 应用（上架名） | 功能简介 | 开源地址 |
| --- | --- | --- |
| **DB Browser for SQLite**（AirBase） | SQLite 数据库可视化管理工具，支持创建、浏览和编辑数据库并执行 SQL 查询 | [Harmony-SQLiteBrowser](https://gitcode.com/Andy88/Harmony-SQLiteBrowser) |
| **QEMU**（轻虚拟机） | 通用开源虚拟机与模拟器，可跨架构运行多种完整操作系统 | [Harmony-QEMU](https://gitcode.com/Andy88/Harmony-QEMU) |
| **Wireshark**（AirShark） | 网络协议分析工具，可抓取并深度解析网络数据包，用于故障排查与安全分析 | [Harmony-Wireshark](https://gitcode.com/Andy88/Harmony-Wireshark) |
| **Firefox / Gecko**（AirWeb） | 开源网页浏览器，注重隐私保护与追踪防护 | [AirWeb](https://gitcode.com/Andy88/AirWeb) |

### 科学与教育

| 应用（上架名） | 功能简介 | 开源地址 |
| --- | --- | --- |
| **QGIS**（AirGis） | 开源地理信息系统（GIS）软件，支持地图制作、空间数据分析与多格式地理数据处理 | [Harmony-QGIS](https://gitcode.com/Andy88/Harmony-QGIS) |
| **GeoGebra Classic**（AirMath） | 动态数学软件，集函数绘图、几何作图与代数计算于一体 | [Harmony-GeoGebra](https://gitcode.com/Andy88/Harmony-GeoGebra) |
| **Stellarium**（AirSky） | 虚拟天文馆软件，实时模拟星空、星座与天体运行，辅助天文观测 | [Harmony-Stellarium](https://gitcode.com/Andy88/Harmony-Stellarium) |

## 六、新手开发实践指南

> 按“你想学什么”找入口：以下链接均为华为官方文档或社区实践验证的教程资源，覆盖各开发场景的入门路径。

### 鸿蒙应用开发（ArkTS / ArkUI）

- [HarmonyOS 第一课](https://developer.huawei.com/consumer/cn/training/study-path/101667550095504391) - 官方系统化学习路径，从零基础到进阶的课程体系。
- [应用开发快速入门 Codelab](https://developer.huawei.com/consumer/cn/codelabsPortal/carddetails/tutorials_tutorials_QuickStart_ide) - 零基础约 2 小时完成第一个鸿蒙应用“手持弹幕”。
- [HarmonyOS Codelabs 专区](https://developer.huawei.com/consumer/cn/codelabsPortal/serviceTypes) - 官方实操教程合集，覆盖 UI、网络、媒体、AI 等场景，按难度分级。
- [应用开发指南文档](https://developer.huawei.com/consumer/cn/doc/harmonyos-guides/application-dev-guide) - 官方完整开发文档，开发过程中的权威参考。

### Python / Java 通用编程

- [华为官方支持说明](https://consumer.huawei.com/cn/support/content/zh-cn16051020/) - 鸿蒙电脑 Python/Java 支持现状：可在 CodeArts IDE 中体验编程。
- [CodeArts IDE 帮助文档](https://support.huaweicloud.com/codeartside/index.html) - Python、Java 等语言的 IDE 官方使用文档。
- [鸿蒙 PC 部署 Python 环境](https://blog.csdn.net/g310773517/article/details/156549733) - 通过“Python 安装器”一键部署 Python 3.12，跑通第一个程序与 pip 三方库。
- [Python C 扩展库编译指南](https://blog.csdn.net/qq8864/article/details/163024355) - 进阶：在鸿蒙 PC 上编译安装带 C 扩展的三方库（含踩坑记录）。

### 开源软件移植

- [三方软件移植指南](https://blog.csdn.net/yyz_1987/article/details/154794871) - 鸿蒙 PC 开发环境搭建与三方库移植全流程。
- [harmony-pc-apps 应用清单](https://gitcode.com/OpenHarmonyPCDeveloper/harmony-pc-apps) - 参考已移植开源应用的源码与构建方式。

### 社区与生态

- [OpenHarmony 官网](https://www.openharmony.cn/) - 开源鸿蒙项目官网，了解社区动态与版本发布。
- [OpenHarmony Gitee 主仓库](https://gitee.com/openharmony) - 开源鸿蒙全部代码仓库。
- [GitCode OpenHarmonyPCDeveloper 组织](https://gitcode.com/OpenHarmonyPCDeveloper) - 鸿蒙 PC 开发者开源组织，PC 应用移植与共建。

## 七、AI 工具版图（GUI 应用 × 开源 CLI）

> 鸿蒙电脑上可运行的 AI 工具全景：带界面的一类已批量上架华为应用市场，开箱即用；另一类是开源社区的 AI CLI（命令行编程智能体），在鸿蒙电脑自带终端或“融合开发引擎”的 openEuler 终端中即装即用。

### 7.1 带 GUI 的 AI 应用（应用市场已上架）

#### AI 编程平台

| 工具 | 简介 | 获取方式 |
| --- | --- | --- |
| **WorkBuddy** | 腾讯 CodeBuddy 桌面版：AI IDE + 内置 codebuddy CLI，自带 Node / Python / Git 运行时，开箱即写代码 | 应用市场搜索“WorkBuddy” |
| **Qoder CN** | 阿里 Agent 式 AI 编程平台：Quest 任务引擎 + RepoWiki 项目记忆，配套 Qoder CLI | 应用市场搜索“Qoder” |
| **CodeArts Agent** | 华为云 AI 编程智能体，可联动 CodeArts IDE 进行远程 AI 开发 | 应用市场搜索“CodeArts” |
| **BitFun（毕方）** | 华为自研技术平台底座，鸿蒙电脑版 DevEco Studio 基于其构建 | 应用市场搜索“BitFun” |
| **DevBox** | 开发者工具箱：云端开发环境与 AI 开发助手一站式获取（另见第四节） | [应用市场详情页](https://appgallery.huawei.com/app/detail?id=com.develop.opensource.devbox) |

#### AI 智能体工作台

| 工具 | 简介 | 获取方式 |
| --- | --- | --- |
| **OpenDesk** | OpenHarmony 社区智能体桌面：ACP 协议宿主调度外部智能体，内置浏览器与插件系统 | [应用市场详情页](https://appgallery.huawei.com/app/detail?id=com.develop.opensource.ohpcd.opendesk) |
| **Kimi** | 月之暗面 AI 助手桌面版：对话、写作、编程问答 | 应用市场搜索“Kimi” |
| **OpenClaw 助手** | 开源 AI Agent 一键部署向导，依托融合开发引擎的 openEuler 终端运行 | 应用市场搜索“OpenClaw” |

#### 数据与科学计算

| 工具 | 简介 | 获取方式 |
| --- | --- | --- |
| **MWorks.Syslab** | 同元软控科学计算与系统仿真环境（Julia 内核），支持 AI 辅助建模 | 应用市场搜索“MWorks” |
| **Navicat Premium Lite** | 免费数据库统一管理（MySQL / PostgreSQL 等），AI 辅助查询 | 应用市场搜索“Navicat” |

#### 系统与运行底座

| 工具 | 简介 | 获取方式 |
| --- | --- | --- |
| **融合开发引擎** | openEuler Linux 子系统（虚拟机 + 容器）：一键启动、共享文件夹、快照备份——AI CLI 工具在鸿蒙电脑上的运行底座 | 应用市场搜索“融合开发引擎” |
| **小艺 / 盘古底座** | 系统级 AI 助手与端云大模型能力 | 系统内置 |

### 7.2 开源社区 AI CLI 工具（终端里的编程智能体）

> 多数为 npm/pip 一条命令安装（或 Go/Rust 单二进制），在鸿蒙电脑自带终端或融合开发引擎 openEuler 终端运行，配置 API Key 即用。

#### 海外开源 Agent CLI

| 工具 | 简介 | 仓库 |
| --- | --- | --- |
| **Claude Code** | Anthropic 官方终端编程智能体，业界事实标准 | [anthropics/claude-code](https://github.com/anthropics/claude-code) |
| **Codex CLI** | OpenAI 开源（Rust）轻量编码智能体 | [openai/codex](https://github.com/openai/codex) |
| **Gemini CLI** | Google 开源终端 AI 助手，免费额度慷慨 | [google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli) |
| **Copilot CLI** | GitHub 官方 Agent 命令行，issue → PR 全流程 | [github/copilot-cli](https://github.com/github/copilot-cli) |
| **Aider** | 经典 AI 结对编程 CLI，与 Git 深度结合 | [Aider-AI/aider](https://github.com/Aider-AI/aider) |
| **OpenCode / Crush** | 社区热门开源终端 Agent（双发行版） | [sst/opencode](https://github.com/sst/opencode) · [charmbracelet/crush](https://github.com/charmbracelet/crush) |
| **Goose** | Block 开源可扩展 AI Agent | [block/goose](https://github.com/block/goose) |

#### 国内开源 / 免费 CLI

| 工具 | 简介 | 仓库 |
| --- | --- | --- |
| **Qwen Code** | 阿里通义千问开源 CLI（Gemini CLI 分支） | [QwenLM/qwen-code](https://github.com/QwenLM/qwen-code) |
| **iFlow CLI** | 阿里心流免费终端智能体，免费用 Qwen3-Coder / Kimi K2 / GLM 等模型 | [iflow-ai/iflow-cli](https://gitee.com/iflow-ai/iflow-cli)（官网 [cli.iflow.cn](https://cli.iflow.cn/)） |
| **Kimi CLI** | 月之暗面开源 CLI | [MoonshotAI/kimi-cli](https://github.com/MoonshotAI/kimi-cli) |
| **CodeBuddy Code** | 腾讯 CodeBuddy 配套 CLI，WorkBuddy 内置同款 | 随 WorkBuddy / CodeBuddy 安装 |
| **Qoder CLI** | 阿里 Qoder 配套 CLI | Qoder 官网下载 |
| **Trae Agent** | 字节跳动开源研究型软件工程 Agent | [bytedance/trae-agent](https://github.com/bytedance/trae-agent) |

#### 本地模型与效率工具

| 工具 | 简介 | 仓库 |
| --- | --- | --- |
| **Ollama** | 本地大模型一键运行与管理 | [ollama/ollama](https://github.com/ollama/ollama) |
| **llama.cpp** | 纯 C/C++ 本地推理引擎，CPU 可跑 | [ggml-org/llama.cpp](https://github.com/ggml-org/llama.cpp) |
| **Open Interpreter** | 终端里用自然语言执行代码 | [openinterpreter/open-interpreter](https://github.com/openinterpreter/open-interpreter) |
| **llm / AIChat** | 轻量多模型 CLI 双雄 | [simonw/llm](https://github.com/simonw/llm) · [sigoden/aichat](https://github.com/sigoden/aichat) |
| **OpenHands** | 原 OpenDevin，全流程自主开发 Agent | [All-Hands-AI/OpenHands](https://github.com/All-Hands-AI/OpenHands) |
| **SWE-agent** | 普林斯顿大学软件工程 Agent | [SWE-agent/SWE-agent](https://github.com/SWE-agent/SWE-agent) |

## 八、说明与建议

1. **应用尝鲜通道**：DevEco Studio 等官方工具目前通过“华为应用市场 > 我的 > 应用尝鲜”分发，普通搜索可能搜不到。
2. **运行环境**：DevEco Studio 鸿蒙电脑版要求 HarmonyOS 7.0 及以上，支持 MateBook Pro / MateBook Fold 非凡大师等机型。
3. **生态现状**：VS Code、JetBrains 系列等桌面 IDE 的鸿蒙原生版本暂未上架，可关注官方后续公告。
4. **链接说明**：三方工具链接来自社区盘点（2025-12），若失效请以应用市场内搜索结果为准。
5. **开源应用说明**：开源社区应用多为知名开源软件的鸿蒙移植版（上架名多为 “Air*” 或 “轻*” 系列），源码与构建脚本见各开源地址。
6. **AI CLI 运行前提**：开源 AI CLI 依赖 Node.js 22+ / Python / Git 运行时，鸿蒙电脑可通过 WorkBuddy 自带运行时或“融合开发引擎”的 openEuler 环境补齐；国内 CLI（iFlow、Qwen Code 等）配 API Key 即用。

## 相关资源

- [HarmonyOS 开发者官网](https://developer.huawei.com/consumer/cn/) - 官方文档、SDK 下载与活动公告。
- [HarmonyOS 开发指南](https://developer.huawei.com/consumer/cn/doc/) - 系统性官方开发文档。
- [华为应用市场](https://appgallery.huawei.com/) - 本文所有工具的官方分发渠道。
- [harmony-pc-apps](https://gitcode.com/OpenHarmonyPCDeveloper/harmony-pc-apps) - 鸿蒙 PC 开源应用清单（本文开源应用章节来源）。
- [Awesome](https://github.com/sindresorhus/awesome) - 本文场景化整理方式参考的知名清单合集。
- [华为开发者社区论坛](https://developer.huawei.com/consumer/cn/forum/) - 鸿蒙开发问题交流与技术讨论。

> 欢迎在评论区补充遗漏的工具与教程，本文持续更新。
