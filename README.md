# 鸿蒙电脑（HarmonyOS PC）开发编程工具盘点

> 面向开发者整理：当前已在华为应用市场上架（含“应用尝鲜”渠道）的鸿蒙电脑原生开发/编程工具。
> 信息截至 2026-10，持续更新中。如链接失效，请在鸿蒙电脑的“华为应用市场”中直接搜索工具名。

## 目录

- [一、官方 IDE 与 AI 开发套件](#一官方-ide-与-ai-开发套件)
- [二、版本控制与代码托管](#二版本控制与代码托管)
- [三、终端与远程开发](#三终端与远程开发)
- [四、辅助与效率工具](#四辅助与效率工具)
- [五、按场景选工具](#五按场景选工具)
- [六、说明与建议](#六说明与建议)
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

## 五、按场景选工具

> 参考 [Awesome](https://github.com/sindresorhus/awesome) 的场景化整理思路：按你要做的事，直接选工具组合。

| 开发场景 | 推荐工具组合 | 场景说明 |
| --- | --- | --- |
| **从零开发一个鸿蒙应用** | DevEco Studio + GitNext | IDE 覆盖编码、预览、调试、调优全流程，Git 客户端负责版本管理 |
| **AI 辅助 / 氛围编程** | DevEco Code + DevEco CLI | Agent 模式自动生成与修改代码，CLI 把鸿蒙开发 Skill 部署到本机各 Agent 工具 |
| **从 Windows / macOS 迁移过来** | CrossShellNext + FtpNextClient + HmCodeHub | 终端、文件传输、代码托管“三件套”，补齐迁移后的日常开发体验 |
| **远程 / 服务器开发** | CrossShellNext + FtpNextClient + FtpNextServer | SSH 多会话 + 双向文件传输，把鸿蒙 PC 接入现有服务器体系 |
| **团队协作与代码审查** | GitNext + HmCodeHub | 一边管理 Git 仓库，一边浏览 GitHub Issue 与仓库动态 |
| **JSON 数据建模** | 鸿蒙JSON转对象工具 + HMOS代码工坊 | 快速生成 ArkTS 数据类，再参考官方示例直接落地 |
| **日常效率与调试** | DevBox + CodeArt IDE | 轻量编辑器写脚本，DevBox 一站式获取常用开发小工具 |

## 六、说明与建议

1. **应用尝鲜通道**：DevEco Studio 等官方工具目前通过“华为应用市场 > 我的 > 应用尝鲜”分发，普通搜索可能搜不到。
2. **运行环境**：DevEco Studio 鸿蒙电脑版要求 HarmonyOS 7.0 及以上，支持 MateBook Pro / MateBook Fold 非凡大师等机型。
3. **生态现状**：VS Code、JetBrains 系列等桌面 IDE 的鸿蒙原生版本暂未上架，可关注官方后续公告。
4. **链接说明**：三方工具链接来自社区盘点（2025-12），若失效请以应用市场内搜索结果为准。

## 相关资源

- [HarmonyOS 开发者官网](https://developer.huawei.com/consumer/cn/) - 官方文档、SDK 下载与活动公告。
- [HarmonyOS 开发指南](https://developer.huawei.com/consumer/cn/doc/) - 系统性官方开发文档。
- [华为应用市场](https://appgallery.huawei.com/) - 本文所有工具的官方分发渠道。
- [Awesome](https://github.com/sindresorhus/awesome) - 本文场景化整理方式参考的知名清单合集。
- [华为开发者社区论坛](https://developer.huawei.com/consumer/cn/forum/) - 鸿蒙开发问题交流与技术讨论。

> 欢迎在评论区补充遗漏的工具，本文持续更新。
