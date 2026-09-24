# Video Skills

视频与封面制作 Skill 的完整目录备份。以下三个 Skill 最新完整包更新于 **2026-09-24**。

## 最新完整包下载

| Skill | 用途 | 文件数 | 下载 |
| --- | --- | ---: | --- |
| xilo-knowledge-video | 绿皮 A-roll 角色小剧场与 B-roll 知识视频，含原文提示词、角色参考、脚本及连续图片帧样图 | 54 | [下载完整 ZIP](https://github.com/ckkaskak-collab/video-skills/releases/download/skills-2026-09-24/xilo-knowledge-video.zip) |
| artifact-template-green-ip-cover | 绿色墨镜 IP 封面，含角色三视图、横竖参考和提示词规范 | 9 | [下载完整 ZIP](https://github.com/ckkaskak-collab/video-skills/releases/download/skills-2026-09-24/artifact-template-green-ip-cover.zip) |
| paper-outline-video | 米白纸感彩色描边知识视频，含 Remotion 工程模板、脚本、字体和参考素材 | 41 | [下载完整 ZIP](https://github.com/ckkaskak-collab/video-skills/releases/download/skills-2026-09-24/paper-outline-video.zip) |

[查看 2026-09-24 完整发布说明](https://github.com/ckkaskak-collab/video-skills/releases/tag/skills-2026-09-24) · [SHA-256 校验值](https://github.com/ckkaskak-collab/video-skills/releases/download/skills-2026-09-24/SHA256SUMS.txt) · [104 个文件的完整清单](https://github.com/ckkaskak-collab/video-skills/releases/download/skills-2026-09-24/file-manifest.json)

**请从上表下载最新版。** 完整包以 Release 附件保存，因此不会自动出现在上方的仓库文件列表。仓库根目录的同名 ZIP 是 2026-09-15 历史备份；绿色 Code 按钮和 Release 自动生成的 Source code 包也不包含上述最新附件。

## 使用

下载所需 ZIP 并解压，将其中同名文件夹放入 Codex skills 目录（通常为 `~/.codex/skills/`）。已有同名 Skill 时先备份，避免覆盖个人改动。

三个最新 ZIP 保留完整原文件及目录结构，仅排除依赖、缓存、Git 元数据和系统杂项。已逐文件比对，GitHub 显示的压缩包 SHA-256 与本地一致；xilo 的六段原文指纹校验与 55 项离线工作流检查通过。

## 外部依赖

- xilo 按任务配置 HyperFrames/Remotion、video-shotcraft、配音服务或 ChatCut；绿皮固定片尾从项目配置读取，视频文件不在本 Skill 目录内。
- 绿皮封面需要 imagegen 生图能力。
- paper-outline-video 的笨鸡封面使用关联 Skill `artifact-template-benji-paper-cover`，需单独安装。

目录外工具、服务、其他 Skill 和项目音视频需单独配置，详见各 Skill 说明。

## 其他历史备份

[anything2explainer.zip（2026-09-15）](https://github.com/ckkaskak-collab/video-skills/blob/main/anything2explainer.zip)：黑底 MG 科普讲解视频，含模板、脚本、参考和样例。
