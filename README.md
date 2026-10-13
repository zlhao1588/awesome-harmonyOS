# 鸿蒙电脑（HarmonyOS PC）开发编程工具盘点

> 面向开发者整理：各语言新手开发指南、华为应用市场上架的开发/编程工具（含“应用尝鲜”渠道）、AI 工具版图（AI GUI × AI CLI）与各类效率工具。
> 信息截至 2026-10，持续更新中。如链接失效，请在鸿蒙电脑的“华为应用市场”中直接搜索工具名。

## 目录

- [一、新手开发实践指南](#一新手开发实践指南)
- [二、官方 IDE 与 AI 开发套件](#二官方-ide-与-ai-开发套件)
- [三、三方IDE工具](#三三方ide工具)
- [四、AI 工具版图（AI GUI & AI CLI）](#四ai-工具版图ai-gui--ai-cli)
- [五、版本控制与代码托管](#五版本控制与代码托管)
- [六、终端与远程开发](#六终端与远程开发)
- [七、辅助与效率工具](#七辅助与效率工具)
- [八、说明与建议](#八说明与建议)
- [相关资源](#相关资源)

## 一、新手开发实践指南

> 按“你想学什么”找入口：以下链接均为华为官方文档或社区实践验证的教程资源，覆盖各开发场景的入门路径。

- [HarmonyBrew](https://atomgit.com/Harmonybrew) - 鸿蒙电脑上的命令行包管理器，支持在鸿蒙 PC / 开发板 / 容器中使用，一条命令装齐 curl、make、zsh 等常用开发工具（[官方文档](https://harmonybrew.atomgit.com/)）。

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

## 二、官方 IDE 与 AI 开发套件

| 工具 | 简介 | 获取方式 / 下载链接 |
| --- | --- | --- |
| **DevEco Studio（鸿蒙电脑版）** | 首个原生运行在鸿蒙电脑上的 HarmonyOS 应用 IDE，基于毕方（BitFun）平台构建：代码编辑、编译构建、调试、性能调优、多设备预览一体化。2026-10-08 起开放公测（26.0.0.201 Beta1） | 应用市场 > 我的 > 应用尝鲜；[官方安装指南](https://developer.huawei.com/consumer/cn/doc/harmonyos-guides/ide-hmos-software-install) |
| **DevEco Code（鸿蒙电脑版）** | 一站式鸿蒙应用 AI Agent 开发工具，内置 GLM5.3 / GLM5.1 等大模型，支持 Plan / Build / Goal 多种开发模式，集成鸿蒙知识库、Skills 与 MCP | 应用市场搜索“DevEco Code” |
| **DevEco CLI（鸿蒙电脑版）** | 命令行 AI 开发套件，一条 init 命令即可把鸿蒙开发 Skill 部署到本机各类 Agent 工具，打通终端开发流 | 随 DevEco Studio 公测发布；见官方文档 |
| **CodeArt IDE** | 华为云轻量级代码编辑器，支持多语言开发，界面简洁 | 应用市场 > 我的 > 应用尝鲜 |
| **CodeArts Agent** | 华为云 AI 编程智能体（码道 IDE） | 应用市场搜索“CodeArts Agent”；[官方安装指导](https://support.huaweicloud.com/usermanual-codeartsagent/codeartsagent_ug_0069.html) |

## 三、三方IDE工具

| 工具 | 简介 | 获取方式 |
| --- | --- | --- |
| **AirCode** | 轻量编码环境，代码以 WebAssembly 在沙箱中编译运行，适合 C++ 等语言上手练习 | 应用市场搜索“AirCode” |
| **MKIDE** | 在鸿蒙设备上提供 IntelliJ IDEA 式的 Java 开发环境，补齐鸿蒙平板/电脑的 Java 编程生产力 | 应用市场搜索“MKIDE” |
| **Java编译器IDE** | 集成完整 Java 编译运行环境，安装后无需其他软件即可编写、编译与运行 Java 代码 | 应用市场搜索“Java编译器IDE” |
| **Python编译器IDE** | 集成完整 Python 编译运行环境，图形界面安装与管理三方模块（内置 pygame 等） | 应用市场搜索“Python编译器IDE” |
| **循造IDE** | 深开鸿适配版三方 IDE，原生适配、Agent 就绪，支持 React / Vue / 静态站点开箱预览 | 应用市场搜索“循造IDE” |

## 四、AI 工具版图（AI GUI & AI CLI）

> 鸿蒙电脑上可运行的 AI 工具全景：带界面的一类（AI GUI）已批量上架华为应用市场，开箱即用；命令行的一类（AI CLI）多为开源编程智能体，在鸿蒙电脑自带终端中即装即用。

### 4.1 AI GUI 工具（应用市场已上架）

#### AI GUI智能体工具

| 工具 | 简介 | 获取方式 |
| --- | --- | --- |
| **WorkBuddy** | 腾讯 CodeBuddy 桌面版：AI IDE + 内置 codebuddy CLI，自带 Node / Python / Git 运行时，开箱即写代码 | [应用市场详情页](https://appgallery.huawei.com/app/C117700477) |
| **BitFun（毕方）** | 华为自研技术平台底座，鸿蒙电脑版 DevEco Studio 基于其构建 | 应用市场搜索“BitFun” |
| **OpenDesk** | OpenHarmony 社区智能体桌面：ACP 协议宿主调度外部智能体，内置浏览器与插件系统 | [应用市场详情页](https://appgallery.huawei.com/app/detail?id=com.develop.opensource.ohpcd.opendesk) |
| **OpenClaw助手** | 开源 AI Agent 一键部署向导，依托融合开发引擎的 openEuler 终端运行 | 应用市场搜索“OpenClaw助手” |
| **Qoder CN** | 阿里推出的编程智能体，鸿蒙电脑版已上架 | 应用市场搜索“Qorder CN” |
| **kimi** | 月之暗面鸿蒙电脑版办公助手 | 应用市场搜索“Kimi” |
| **Cube Agent** | 面向鸿蒙电脑的一台原生AI工作台 | 应用市场搜索“Cube Agent” |



### 4.2 AI CLI 工具（终端里的编程智能体）

> 多数为 npm/pip 一条命令安装，在鸿蒙电脑自带终端运行，配置 API Key 即用。

#### 开源 Agent CLI

| 工具 | 简介 | 仓库 |
| --- | --- | --- |
| **OpenDesk CLI** | opendesk终端编程智能体 |https://opendesk.matrix.openharmony.cn/docs/quickstart/cli/ |
| **Qwen Code** | 阿里通义千问开源 CLI |通过harmonybrew直接安装 |
| **OpenCode** | 社区热门开源终端 Agent |通过harmonybrew直接安装,https://gitcode.com/OpenHarmonyPCDeveloper/ohpcd-brew，安装命令：brew install opencode|
| **Openclaw** | 社区热门开源终端 Agent |通过harmonybrew直接安装,https://gitcode.com/OpenHarmonyPCDeveloper/ohpcd-brew|
| **Gemini CLI** | Google 开源终端 AI 助手，免费额度慷慨 |通过harmonybrew直接安装,https://gitcode.com/OpenHarmonyPCDeveloper/ohpcd-brew|
| **cline** | AI 编码代理 |通过harmonybrew直接安装,https://gitcode.com/OpenHarmonyPCDeveloper/ohpcd-brew|
| **harness agent** | AI 编码智能体 |通过harmonybrew直接安装,https://gitcode.com/OpenHarmonyPCDeveloper/ohpcd-brew，安装命令：brew install hermes-agent|
| **kimi code CLI** | 月之暗面开源 CLI |通过npm安装，https://www.kimi.com/code/docs/kimi-code-cli/guides/getting-started.html|
| **Codex CLI** | OpenAI 开源（Rust）轻量编码智能体 |通过harmonybrew安装，https://atomgit.com/Harmonybrew/homebrew-core，安装命令：brew install codex|
| **Claude Code** | Anthropic 官方终端编程智能体 |通过harmonybrew直接安装,https://atomgit.com/social4hyq/homebrew-core |
| **hermes** | Hermes 是一个由美国 Nous Research推出的 可长期运行、能自主执行任务并持续学习的 AI Agent |通过harmonybrew直接安装|
| **codebuddy CLI** | 腾讯云推出的AI命令行编程工具 |通过harmonybrew直接安装|
| **CodeWhale** | 终端编程智能体 |通过harmonybrew直接安装，安装命令：brew install codewhale|
| **AtomCode** | 一款运行在终端的开源 AI 编码智能体 |可通过 Harmonybrew 获取。安装命令：brew install atomcode|


## 五、版本控制与代码托管

| 工具 | 简介 | 下载链接 |
| --- | --- | --- |
| **GitNext** | 鸿蒙原生 Git 客户端，随时查看与管理代码仓库 | [应用市场详情页](https://appgallery.huawei.com/app/detail?id=com.develop.opensource.gitnext) |
| **HmCodeHub** | 鸿蒙电脑上的 GitHub 客户端，浏览仓库、Issue 等更顺手 | [应用市场详情页](https://appgallery.huawei.com/app/detail?id=xyz.zhousg.harmony_github) |
| **kgit** | 鸿蒙电脑上的 git工具 | 应用市场搜索“kgit”|
| **GitCoder** | 鸿蒙上面向开发者的一款多平台Git客户端，支持Gitcode、GitHub、Gitee三大代码托管平台 | 应用市场搜索“GitCoder”|



## 六、终端与远程开发

| 工具 | 简介 | 下载链接 |
| --- | --- | --- |
| **融合开发引擎** | openEuler Linux 子系统（虚拟机 + 容器）：一键启动、共享文件夹、快照备份，为 AI CLI 与开源软件提供 Linux 运行环境 | [应用市场详情页](https://appgallery.huawei.com/app/detail?id=com.huawei.developer.rgm.images_openeuler22.03) |
| **CrossShellNext** | SSH 终端工具，支持多会话管理与密钥登录，远程开发必备 | [应用市场详情页](https://appgallery.huawei.com/app/detail?id=com.develop.opensource.CrossShellNext) |
| **FtpNextClient** | 免费 FTP / SFTP / Telnet 客户端，本地与远程文件互传 | [应用市场详情页](https://appgallery.huawei.com/app/detail?id=com.develop.opensource.ftpnext_client) |
| **FtpNextServer** | 免费 FTP / SSH / Telnet 服务器端，把鸿蒙电脑变成远程主机 | [应用市场详情页](https://appgallery.huawei.com/app/detail?id=com.develop.opensource.ftpnext_server) |

## 七、辅助与效率工具

### 7.1 Linux 虚拟机

| 工具 | 简介 | 下载链接 |
| --- | --- | --- |
| **QEMU**（轻虚拟机） | 通用开源虚拟机与模拟器，可跨架构运行多种完整操作系统 | 应用市场搜索“轻虚拟机”；[开源地址](https://gitcode.com/Andy88/Harmony-QEMU) |

### 7.2 数据库工具

| 工具 | 简介 | 下载链接 |
| --- | --- | --- |
| **Navicat Premium Lite** | 免费数据库统一管理（MySQL / PostgreSQL 等） | 应用市场搜索“Navicat” |
| **DB Browser for SQLite**（AirBase） | SQLite 数据库可视化管理，支持建库、编辑数据与执行 SQL 查询 | 应用市场搜索“AirBase”；[开源地址](https://gitcode.com/Andy88/Harmony-SQLiteBrowser) |

### 7.3 抓包工具

| 工具 | 简介 | 下载链接 |
| --- | --- | --- |
| **Wireshark**（AirShark） | 网络协议分析工具，抓包深度解析数据包，用于网络调试与排障 | 应用市场搜索“AirShark”；[开源地址](https://gitcode.com/Andy88/Harmony-Wireshark) |

### 7.4 辅助与效率工具

| 工具 | 简介 | 下载链接 |
| --- | --- | --- |
| **DevBox** | 面向鸿蒙 PC 的开发者工具集，常用开发小工具与云端开发环境一站式获取 | [应用市场详情页](https://appgallery.huawei.com/app/detail?id=com.develop.opensource.devbox) |
| **MWorks.Syslab** | 同元软控科学计算与系统仿真环境（Julia 内核），数据分析与算法验证 | [应用市场详情页](https://appgallery.huawei.com/app/detail?id=com.tongyuan.mworks.syslab.pc) |
| **鸿蒙JSON转对象工具** | JSON 快速转鸿蒙数据类（ArkTS），省去手写样板代码 | [应用市场详情页](https://appgallery.huawei.com/app/detail?id=top.sevenfire.ccjsonzs) |
| **HMOS代码工坊** | 华为官方示例代码库，分类浏览可直接运行的应用案例 | 应用市场搜索“HMOS代码工坊” |

## 八、说明与建议

1. **应用尝鲜通道**：DevEco Studio 等官方工具目前通过“华为应用市场 > 我的 > 应用尝鲜”分发，普通搜索可能搜不到。
2. **运行环境**：DevEco Studio 鸿蒙电脑版要求 HarmonyOS 7.0 及以上，支持 MateBook Pro / MateBook Fold 非凡大师等机型。
3. **生态现状**：VS Code、JetBrains 系列等桌面 IDE 的鸿蒙原生版本暂未上架，可关注官方后续公告。
4. **链接说明**：三方工具链接来自社区盘点（2025-12），若失效请以应用市场内搜索结果为准。
5. **AI CLI 运行前提**：开源 AI CLI 依赖 Node.js 22+ / Python / Git 运行时，鸿蒙电脑可通过 WorkBuddy 自带运行时或“融合开发引擎”的 openEuler 环境补齐；国内 CLI（iFlow、Qwen Code 等）配 API Key 即用。

## 相关资源

- [HarmonyOS 开发者官网](https://developer.huawei.com/consumer/cn/) - 官方文档、SDK 下载与活动公告。
- [HarmonyOS 开发指南](https://developer.huawei.com/consumer/cn/doc/) - 系统性官方开发文档。
- [华为应用市场](https://appgallery.huawei.com/) - 本文所有工具的官方分发渠道。
- [harmony-pc-apps](https://gitcode.com/OpenHarmonyPCDeveloper/harmony-pc-apps) - 鸿蒙 PC 开源应用清单与移植参考。
- [Awesome](https://github.com/sindresorhus/awesome) - 本文场景化整理方式参考的知名清单合集。
- [华为开发者社区论坛](https://developer.huawei.com/consumer/cn/forum/) - 鸿蒙开发问题交流与技术讨论。

> 欢迎在评论区补充遗漏的工具与教程，本文持续更新。
