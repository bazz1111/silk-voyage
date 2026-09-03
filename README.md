# qinglu-landscape-poster

Agent skill（`SKILL.md`）：把旅行照片做成 3:4 竖版「青绿山水手卷截景」海报。上半保留原图，下半在象牙色空绢里画同场景的横向青绿手卷截段。

适用于 Cursor、Claude Code、Codex 及其他支持 `SKILL.md` 的 agent / 出图流程。按下方 Prompt 出图；当前环境有图像工具就用，指定即梦 / Midjourney / 其他模型则交同一段 Prompt。

## 安装

把本仓库放到该 agent 的 skills 目录，保证 `SKILL.md` 在目录根下。路径因 agent 而异，例如 Cursor：

```text
~/.cursor/skills/qinglu-landscape-poster/SKILL.md
```

Windows（Cursor 示例）：`%USERPROFILE%\.cursor\skills\qinglu-landscape-poster\SKILL.md`

装好后按该 agent 的惯例重新加载 skills（例如新开一轮对话）。

## 用法

丢一张旅行/风景照片，说「做成青绿手卷海报」或点名 `qinglu-landscape-poster`。必须有照片；一图一海报。

## 文件

- `SKILL.md` — skill 说明与必须逐字使用的 Prompt
