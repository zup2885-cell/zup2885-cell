# 阿祖的精选开源使用导航

只收录用途不同、来源清楚的项目。以下四项均保留 GitHub Fork 关系，不删除或替换原作者许可证。核对日期：2026-11-11。

| 项目与原作者 | 用途 | 最近主分支提交（UTC） | 已归档 | 许可 | 推荐方式与部署成本 |
| --- | --- | --- | --- | --- | --- |
| [LocalSend / localsend](https://github.com/localsend/localsend) | 局域网传文件 | 2026-11-11 | 否 | Apache-2.0 | **直接用**官方下载版；收发设备安装应用并处于同一可互通的局域网，无需自建服务器 |
| [BentoPDF / alam00000](https://github.com/alam00000/bentopdf) | PDF 工具箱 | 2026-11-09 | 否 | AGPL-3.0；另有商业许可 | **直接用**官方网页；如将来自建，可用静态托管或 Docker，部分工具涉及额外 WASM 配置 |
| [Czkawka / qarmin](https://github.com/qarmin/czkawka) | 重复文件和相似图片查找 | 2026-11-10 | 否 | Czkawka GTK/CLI 为 MIT；Krokiet/Cedinia 为 GPL-3.0-only；图片与音频为 CC BY 4.0 | **直接用**对应系统的官方桌面版；不需后端，支持情况与运行依赖按发布说明确认。先预览结果，不自动批量删除 |
| [draw.io Desktop / jgraph](https://github.com/jgraph/drawio-desktop) | 流程图与结构图 | 2026-11-05 | 否 | GPL-3.0 | **直接用**官方在线版或桌面安装包；在线版由原作者提供，本 Fork 为桌面版源码 |

## 为什么这样选

四个项目分别覆盖文件传输、文档处理、文件整理和画图，不与主页里的便签、拍摄计划、创作台反复收录同一功能。Fork 方便保存源码和以后比较上游更新；**正式下载仍指向原项目 Releases 或官网**，不会把 Fork 中不存在的安装包写成可下载。

暂未收录：

- Upscayl：功能有价值，但核验时桌面稳定版仍为 2024-12-25 发布的 v2.15.0，主分支最近提交为 2026-03-27；另有显卡兼容要求，本轮优先更新更近、使用门槛更低的项目。
- Immich：持续维护，但相册管理需要自建服务与长期存储，不适合这一轮的轻量工具入口。
- IT-Tools：偏开发场景，且与普通生活需求相比，当前四项更容易直接使用。

## 最简单的第一版

只做 GitHub 主页上的中文导航、四个保留原作者的 Fork，以及官方使用/下载入口。**不重新开发、不安装程序、不部署新服务器**。

将来如果要修改某个项目或独立部署，先确认具体用途，再按该项目许可证和部署文档处理。当前只核验了仓库状态、主分支提交、README、许可证与入口；未安装或逐项实测第三方应用，也不代表原作者会持续维护 Fork。

## 核验来源

- 各项目 GitHub 仓库、主分支最新提交及 Releases。
- [LocalSend LICENSE](https://github.com/localsend/localsend/blob/main/LICENSE)
- [BentoPDF 许可说明](https://github.com/alam00000/bentopdf/blob/main/docs/licensing.md)
- [Czkawka README 许可段](https://github.com/qarmin/czkawka#license)
- [draw.io Desktop README](https://github.com/jgraph/drawio-desktop#readme)
