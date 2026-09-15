# OceanCT 的 Humanize Skill

自己用 AI 写技术文章时，我常觉得内容虽然列齐了，读起来却不太像自己会说的话。试过一些现成的 Humanize Skill 之后，我把改稿时反复在意的地方整理成了这份规则。

这份 skill 适用于中文学习笔记和技术博客。指令用英文编写，默认输出中文；有自己的写作样稿时，可以一起提供，让改写更贴近自己的表达习惯。

## 下载与使用

[下载 SKILL.md](https://raw.githubusercontent.com/OceanCT/oceanct-humanize/main/SKILL.md)，保存到所用工具支持的 skill 目录，目录名为 `oceanct-humanize`：

```text
oceanct-humanize/
  SKILL.md
```

也可以直接将 [SKILL.md](SKILL.md) 的内容与原稿一起交给 AI，不依赖特定工具。使用时可以这样说明：

> 按 OceanCT Humanize Skill 改写下面这篇学习笔记。保留技术事实、适用条件和引用，先解释问题，再自然引出概念。我自己的写作样稿附在后面，请参考它的语气与句子节奏。

## 我在意的几个地方

讲解要让读者跟得上。引入陌生概念时，先找一个理解它不需要提前掌握新知识的例子。讨论系统设计时，可以从已有流程出发，说明换成新系统后哪些经验还能借用，哪些机制需要重新设计。

句子也需要保留展开的空间。“从宏观上看”这样的过渡，如果能说明讨论的层次，就有保留的价值。相关分句可以放在同一句里；需要解释因果和来龙去脉的内容，优先写成连贯段落，比较参数时再用表格。

改写仍要保留事实边界。整理口述时可以去掉重复起头和转写错误，但不能补造经历，也不能为了读起来顺畅而删掉技术条件。

完整规则见 [SKILL.md](SKILL.md)，设计背景和改稿例子见[博客介绍](https://oceanct.github.io/blog/2026/09/14/useful-tools-humanizer/)。

## License

[MIT License](LICENSE)，Copyright (c) 2026 OceanCT。
