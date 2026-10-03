# 信息处理

**[Haoge Truth · 浩哥的真话圈](https://x.com/haogetruth)** · [返回总目录](../../README.md)

我是 [浩哥 / @haogetruth](https://x.com/haogetruth)。我把平时常用的信息处理、研究分析框架和具体要求，都整理成了这些 skill。这样每次都能直接复用，不用重新解释一遍，也能让产出的结构和质量更稳定。

你可以搭配自己的 AI Agent 来用。做信息处理时，把自己的材料和对应的 skill 一起给 AI。目前的信息处理技能主要用于研报，建议优先用正规机构发布、内容完整清晰的报告，方便 AI 提取观点、数据和证据。

做研究分析时，可以给一个想研究的 idea、想了解的行业，或者一家公司，再把对应的 skill 一起交给 AI，让它按框架查找资料、展开分析。

## 这一组做什么

这里先放两个处理研报的技能。手里已经有报告，想把观点、证据和关键数字读明白，或者把英文研报整理成中文，就选这一组。

它们只处理你提供的报告，不从一个公司名或行业名开始独立研究。想让 AI 找资料并形成研究，去 [研究分析](../research-analysis/README.md)。

## 选哪个

| 技能 | 名称 | 适合的报告 |
|---|---|---|
| [公司研报处理](hgs-company-report-summary/SKILL.md) | `hgs-company-report-summary` | 公司深度、首次覆盖、评级调整、财报点评等已有公司研报 |
| [行业研报处理](hgs-industry-report-summary/SKILL.md) | `hgs-industry-report-summary` | 行业入门、技术路线、产业链专题、景气跟踪等已有行业研报 |

公司版整理：主要观点、事实依据、陈述总结、关键数据、推荐资产标的、专业名词及重要事件。

行业版整理：一句话结论、核心观点、行业全景与产业链拆解、竞争格局与谁能赢、趋势与拐点、事实依据、关键数据、陈述总结、涉及标的、专业名词及重要事件。

报告里没写的内容，AI 应该直接说明没披露，不能为了凑齐章节编答案。一次给多份报告时，默认分别整理，避免把不同机构的判断混在一起。

## 直接用

下载对应 `SKILL.md`，与研报 PDF 放进同一个 AI 对话，发送：

> 请按这份 SKILL.md 的要求处理附件研报，输出完整中文摘要。

不一定要先安装。平台不支持上传 Markdown，直接粘贴文件全文也行；AI 读不了 PDF，可以补充可读的正文和关键图表截图。没有安装技能时，换一个新对话要重新提供文件。

## 英文研报与其他语言

不只限于外资或英文报告。默认是读懂原文，再整理成简体中文摘要；你也可以指定其他输出语言，但要看 AI 能不能准确理解原报告和技能要求。

例如，给它一份英文研报，拿到的是按章节整理好的中文摘要，不是整个 PDF 的逐字译文，也不会照搬原 PDF 的排版。评级、名称、数字、币种、数据所属期间，以及预测的语气都要保留清楚，方便回查原文；不会自动换算汇率。

## 会输出什么

| 要求 | 交付 |
|---|---|
| 未指定格式 | 对话中的完整中文 Markdown 摘要，不包在代码块里 |
| 指定其他语言 | 同样的完整结构，使用指定语言 |
| 要 Markdown 文件 | 能生成附件时交付 `.md`，否则提供完整正文并说明限制 |
| 要 HTML | 包含完整摘要的单文件 `.html`，否则提供完整源码 |

HTML 可以在浏览器里打开，但不会自动变成在线网站。两份摘要默认都不加我的广告、署名、二维码或社群邀请。只有你要求说明所用技能时，才另行注明，而且不能替代原研报的作者和来源。

## 下载与安装

到 [最新下载页](https://github.com/haogetruth/haoge-skills/releases/latest)，选你需要的独立 ZIP。文件名里的版本号以下载页为准：

- 公司版：`hgs-company-report-summary`
- 行业版：`hgs-industry-report-summary`

每个 ZIP 里只有一个技能目录，包含 `SKILL.md` 和 `LICENSE`，按你用的工具导入即可。只想先试一下，下载单个 `SKILL.md` 就够了；想一次拿到全部文件，用仓库首页的 `Code > Download ZIP`。

Codex 的 skill-installer 可以按以下路径安装：

```text
仓库：https://github.com/haogetruth/haoge-skills
公司版：skills/information-processing/hgs-company-report-summary
行业版：skills/information-processing/hgs-industry-report-summary
```

安装后可以说：“使用 hgs-company-report-summary 处理附件公司研报。”行业版换成对应名称就行。不同工具选择技能的方式不一样，按它的说明操作；只上传 PDF，不一定会自动启用这份技能。

如果之前已经安装过，技能名称没变，可以继续用；从仓库新安装或重新安装时，用上面的路径。

## 有几个地方要注意

- 摘要默认只依据你提供的报告，不自动补充实时行情或新的投资观点。评级、目标价和预测都属于报告发布时的判断。
- 识别和翻译可能出错，关键图表与数字请回查原报告。
- 只提供有权使用的资料，也留意你所用 AI 的隐私规则。材料交给自己的 AI 就好，不需要上传到这个仓库，也不需要把账号、密码或 API Key 发给我。

作者：[浩哥 / @haogetruth](https://x.com/haogetruth) · [Discord：浩哥的真话圈](https://discord.gg/QzSrHk3Rsf) · [小红书：浩哥的真话圈](https://xhslink.cn/o/8LW3ZvQOqWR)。这些只是文档里的作者介绍，不会加进默认摘要，也不影响使用。

技能指令和文档采用 [CC BY-NC 4.0](../../LICENSE)，商业用途需要另外授权。用的时候遇到问题，欢迎到 [Issues](https://github.com/haogetruth/haoge-skills/issues) 留言，记得不要上传私密信息。
