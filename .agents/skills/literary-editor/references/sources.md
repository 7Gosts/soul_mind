# 来源与适配记录

查阅与整理日期：2026-09-17。

本项目版本由现成编辑 skill 和本项目的作者反馈共同形成。它不是某家文学杂志的官方审稿规范；将提示词保存为 skill 也不等同于训练模型或获得编辑资历。

## 实际引入：Calliope 的 line-editor

- 仓库：[Calliope-Editor/writing-skills](https://github.com/Calliope-Editor/writing-skills)。
- 固定版本：`2fad031982cbbcb00c4da14c2fc9712d2daa78da`。
- [line-editor 原始文件](https://github.com/Calliope-Editor/writing-skills/blob/2fad031982cbbcb00c4da14c2fc9712d2daa78da/skills/editorial/line-editor/SKILL.md)，通过 skill-installer 下载，原文保存在 [upstream-line-editor.md](upstream-line-editor.md)。
- 同次查阅了 [copy-editor](https://github.com/Calliope-Editor/writing-skills/blob/2fad031982cbbcb00c4da14c2fc9712d2daa78da/skills/editorial/copy-editor/SKILL.md) 与 [developmental-editor](https://github.com/Calliope-Editor/writing-skills/blob/2fad031982cbbcb00c4da14c2fc9712d2daa78da/skills/editorial/developmental-editor/SKILL.md)。
- 采用的方法：保护声音；以原句支持意见；识别反复出现的问题；区分机械错误和有意的非标准表达；按作品的意图调整评价标准。
- 本地调整：允许落实作者授权的修改；使用中文小说的表达与标点习惯；去掉订阅/MCP 接入、长篇市场字数和固定情节节点的要求。
- 许可证：MIT，版权声明保存在 [LICENSE.txt](../LICENSE.txt)。原始文件用于查阅，本项目运行入口已另行改写为中文。

## 方法参考：novel-writing 的风格保护

- 仓库：[wgwtest/novel-writing](https://github.com/wgwtest/novel-writing)。
- 固定版本：`c57b5c6b35d30d692a06c7fe9cc030bd4ea7af14`。
- 实际阅读：[style-fidelity.md](https://github.com/wgwtest/novel-writing/blob/c57b5c6b35d30d692a06c7fe9cc030bd4ea7af14/novel-writing/references/style-fidelity.md)。
- 采用的方法：不把压缩等同于改进；检查删除对人物、声音、信息、节奏、张力和气氛的影响；优先局部修正。
- 未安装该仓库的其他创作规则或脚本。许可证为 MIT，保留其版权声明。

## 比较阅读：creative-writing-skills 的分层审稿

- 仓库：[haowjy/creative-writing-skills](https://github.com/haowjy/creative-writing-skills)。
- 固定版本：`fd7a3ad9cd7697a0645ff6ff4bd5e809cf7673a3`。
- 实际阅读：[story-review](https://github.com/haowjy/creative-writing-skills/blob/fd7a3ad9cd7697a0645ff6ff4bd5e809cf7673a3/skills/story-review/SKILL.md)、[editorial-review](https://github.com/haowjy/creative-writing-skills/blob/fd7a3ad9cd7697a0645ff6ff4bd5e809cf7673a3/skills/story-review/resources/editorial-review.md)、[line-edit](https://github.com/haowjy/creative-writing-skills/blob/fd7a3ad9cd7697a0645ff6ff4bd5e809cf7673a3/skills/story-review/resources/line-edit.md)。
- 比较了整体审稿、结构编辑、句子编辑与校对的范围。该仓库按 Apache-2.0 发布；本项目只链接上述资料，不复制、安装或调用该项目的文件及脚本。

以上资料所列的写作书籍仅属于其自身的参考书目；此处不表示已经阅读全文或逐项核实其引用。

## 项目发现位置

[OpenAI 官方 Skills 文档](https://developers.openai.com/codex/skills/)说明项目 skill 放在 `.agents/skills/` 下，必需入口为 `SKILL.md`。本项目使用 `.agents/skills/literary-editor/`，没有全局安装，也没有引入外部服务依赖。
