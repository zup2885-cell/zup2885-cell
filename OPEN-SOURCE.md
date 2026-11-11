# 阿祖的开源适配工具导航

只收录用途不同、来源清楚的项目。以下四项均保留 GitHub Fork 关系，不删除或替换原作者许可证。核对日期：2026-11-11。

| 项目与原作者 | 用途 | 最近主分支提交（UTC） | 已归档 | 许可 | 推荐方式与部署成本 |
| --- | --- | --- | --- | --- | --- |
| [LocalSend / localsend](https://github.com/localsend/localsend) | 局域网传文件 | 2026-11-11 | 否 | Apache-2.0 | **阿祖快传 Mac 适配版**：[下载我的版本](https://github.com/zup2885-cell/localsend/releases/latest)；收发设备需网络互通，无需自建服务器 |
| [BentoPDF / alam00000](https://github.com/alam00000/bentopdf) | PDF 工具箱 | 2026-11-09 | 否 | AGPL-3.0；另有商业许可 | **已适配部署**：[阿祖 PDF 工具](https://zup2885-cell.github.io/bentopdf/)，使用 GitHub Pages 与上游 Simple Mode；保留完整公开 AGPL 源码，部分工具按需加载 WASM |
| [Czkawka / qarmin](https://github.com/qarmin/czkawka) | 重复文件和相似图片查找 | 2026-11-10 | 否 | Czkawka GTK/CLI 为 MIT；Krokiet/Cedinia 为 GPL-3.0-only；图片与音频为 CC BY 4.0 | **阿祖素材查重 Mac 适配版**：[下载我的版本](https://github.com/zup2885-cell/czkawka/releases/latest)。首版面向 Apple Silicon，软件渲染；先看结果，再由本人确认处理 |
| [draw.io Desktop / jgraph](https://github.com/jgraph/drawio-desktop) | 流程图与结构图 | 2026-11-05 | 否 | GPL-3.0 | **已增加网页适配**：[阿祖画图工具](https://zup2885-cell.github.io/drawio-desktop/)。网页复用本 Fork 所指向的 draw.io 核心，核心代码为 Apache-2.0，图标与模板另有条款；桌面外壳仍为 GPL-3.0 |

## 为什么这样选

四个项目分别覆盖文件传输、文档处理、文件整理和画图，不与主页里的便签、拍摄计划、创作台反复收录同一功能。四项都使用阿祖自己的部署或下载入口。Fork 用于保留来源和比较上游更新；适配修改与原作者版权分别说明。

暂未收录：

- Upscayl：功能有价值，但核验时桌面稳定版仍为 2024-12-25 发布的 v2.15.0，主分支最近提交为 2026-03-27；另有显卡兼容要求，本轮优先更新更近、使用门槛更低的项目。
- Immich：持续维护，但相册管理需要自建服务与长期存储，不适合这一轮的轻量工具入口。
- IT-Tools：偏开发场景，且与普通生活需求相比，当前四项更容易直接使用。

## 当前发布状态

- **阿祖 PDF 工具**：已部署自己的静态版本，改名、标识、来源与源码入口均已保存。2026-11-11 电脑端用两份各一页的测试 PDF 合并并下载，核对输出 2 页、A/B 顺序与文字均通过。未逐项测试全部上游工具，不承诺完全离线或所有格式都可转换。
- **阿祖画图工具**：已部署自己的静态编辑器文件，内层画布由本账号提供，不是嵌入原作者网页。已测试插入图形、输入中文、导出并解析 XML。没有云盘登录、多人协作或服务器转换服务；上游公共构建定位为评估版，PDF 需使用浏览器打印。
- **阿祖快传**：独立 Mac 应用标识、图标、默认简体中文和适配源码入口；不包含本人文件或收发记录。验证范围以 Release 记录为准。
- **阿祖素材查重**：独立配置目录、阿祖图标与中文默认界面；首次不预选扫描目录。已用三个测试文件找出预期的一组重复文件，没有执行删除。相似视频等扩展功能仍受上游依赖限制。
- **数据分析平台**：是本机运行项目的新展示名称，源码和启动说明可公开查看；公开预览仅展示空白布局；作品、评论、素材和分析 API 返回空数据，不连接本人电脑。

没有新增服务器、密钥或独立计费服务；GitHub Pages 使用现有账号。第三方项目修改按各自许可提供源码，保留版权与上游来源。

## 核验来源

- 各项目 GitHub 仓库、主分支最新提交及 Releases。
- [LocalSend LICENSE](https://github.com/localsend/localsend/blob/main/LICENSE)
- [BentoPDF 许可说明](https://github.com/alam00000/bentopdf/blob/main/docs/licensing.md)
- [Czkawka README 许可段](https://github.com/qarmin/czkawka#license)
- [draw.io Desktop README](https://github.com/jgraph/drawio-desktop#readme)

## 公开内容边界

工作台公开页只展示空白界面、功能和使用说明。本人项目、脚本、账号数据、评论及私人素材不打包发布；分享具体内容时另行设置受限访问。当前页面与下载包的清空，不等于收回过往公开历史或访客已保存的副本。
