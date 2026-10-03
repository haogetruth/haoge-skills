# haoge-skills

**[Haoge Truth · 浩哥的真话圈](https://x.com/haogetruth)**

[许可：CC BY-NC 4.0](LICENSE)

我是 [浩哥 / @haogetruth](https://x.com/haogetruth)。我把平时常用的信息处理、研究分析框架和具体要求，都整理成了这些 skill。这样每次都能直接复用，不用重新解释一遍，也能让产出的结构和质量更稳定。

你可以搭配自己的 AI Agent 来用。做信息处理时，把自己的材料和对应的 skill 一起给 AI。目前的信息处理技能主要用于研报，建议优先用正规机构发布、内容完整清晰的报告，方便 AI 提取观点、数据和证据。

做研究分析时，可以给一个想研究的 idea、想了解的行业，或者一家公司，再把对应的 skill 一起交给 AI，让它按框架查找资料、展开分析。

现在先分享下面这四个，后面还会继续加。

## 先选你要做的事

### [信息处理](skills/information-processing/README.md)

手里已有公司或行业研报，想读清楚、翻译并整理，选这一组。

**默认拿到：** 对话中的完整中文 Markdown 摘要。

### [研究分析](skills/research-analysis/README.md)

给一个公司名或行业主题，希望 AI 查资料、分析与比较，选这一组。

**默认拿到：** 中文 HTML 研究报告；行业版另附简短聊天摘要。

简单说，**手里有研报、想把它读明白，选信息处理；有研究想法、希望 AI 查资料做分析，选研究分析。**

Haoge Skills is a collection of independent AI skills for report processing and research. Output defaults to Simplified Chinese; request another language if your AI supports it.

## 目前有哪些

| 分类 | 技能 | 安装与调用名称 |
|---|---|---|
| 信息处理 | [公司研报处理](skills/information-processing/hgs-company-report-summary/SKILL.md) | `hgs-company-report-summary` |
| 信息处理 | [行业研报处理](skills/information-processing/hgs-industry-report-summary/SKILL.md) | `hgs-industry-report-summary` |
| 研究分析 | [公司深度研究](skills/research-analysis/hgs-company-deep-research/SKILL.md) | `hgs-company-deep-research` |
| 研究分析 | [行业深度研究](skills/research-analysis/hgs-industry-deep-research/SKILL.md) | `hgs-industry-deep-research` |

每个技能都能单独使用，选你需要的就好，不用全部安装。`hgs-` 是 Haoge Skills 的前缀，两组目录只是方便查找。想看详细用法、会整理哪些章节、最后拿到什么，点进对应分类的 README 就行。

## 先试一下

1. 选一个技能，下载对应的 `SKILL.md`。
2. 把文件放进自己的 AI 对话。处理研报就附上 PDF；做研究就写清公司、行业或想研究的问题，有相关资料也可以一起附上。
3. 告诉 AI：“请按这份 SKILL.md 的要求执行”，再说你希望它做什么。

例如：“按公司研报处理要求整理附件 PDF，输出中文摘要。”或者：“按公司深度研究要求研究【公司与代码】，生成 HTML 报告。”

不一定要先安装才能用。如果平台不支持上传 Markdown，直接粘贴文件全文也行。没有安装技能时，换一个新对话要重新提供文件；支持安装的 AI Agent，也可以安装后反复调用。

能做到哪一步，也取决于你用的 AI：处理 PDF 要能读取文件，独立研究要能查资料，或者有你提供的材料。如果它不能生成附件，就让它给出完整正文或 HTML 源码，不应该给一个不存在的下载链接。HTML 报告可以在浏览器里打开，但不会自动变成在线网站。

## 下载与安装

- **只试一个**：打开上面的技能文件，下载 `SKILL.md`。
- **长期安装一个**：去 [最新下载页](https://github.com/haogetruth/haoge-skills/releases/latest) 选对应的独立 ZIP，按你用的工具导入。
- **一次下载全部文件**：首页 `Code > Download ZIP`，或 `git clone https://github.com/haogetruth/haoge-skills.git`。

下载页里有四个独立 ZIP，一份对应一个技能，选自己需要的即可；包名里的版本号以下载页为准。GitHub 自动提供的 `Source code` 是整个仓库，不是单个技能安装包。平时看用法，就看首页和分类 README；要安装，就去最新下载页。

Codex 使用 skill-installer 时，提供仓库地址与具体路径，例如：

```text
请使用 skill-installer，从 https://github.com/haogetruth/haoge-skills 安装 skills/research-analysis/hgs-company-deep-research。
```

不同工具的安装入口和调用方式不一样，按你所用工具的说明操作。两组 README 都列出了各技能的完整路径。

## 输出和署名

信息处理默认是聊天中的 Markdown 摘要，也可指定 Markdown 文件、HTML 或其他语言，**默认不附品牌宣传**。

研究分析默认是 HTML 报告，也可指定 Markdown、长文或其他语言。HTML 最后默认有一行低调的 `Powered by @haogetruth`，没有顶部落款、二维码或社群广告；你可以要求去掉这行。它只说明所用技能来源，不代表报告经我审阅或背书。

能否生成附件、查到哪些资料、翻译是否准确，还是要看你用的 AI 和工具。不需要专门购买某个数据终端，也不是所有模型都能达到同样的效果。

## 反馈与贡献

用了之后觉得某个章节不顺、数字口径有问题，或者安装时遇到了麻烦，欢迎到 [Issues](https://github.com/haogetruth/haoge-skills/issues) 留言，也欢迎提 Pull Request。告诉我用了哪个技能、原本希望得到什么、实际哪里不对。能用脱敏片段说明的，就不用上传整份报告。

不要在公开 Issue、PR 或提交里放密钥、密码、私人路径、未公开报告或私人账户信息。AI 产出的重要数字仍要回查原材料，研究不是收益保证，也不是个性化交易建议。

想贡献新技能，可以在对应分类下新建独立目录，入口文件用 `SKILL.md`，同时更新总 README、分类 README 和 `.gitignore` 白名单。不要把真实研报、个人数据或生成的报告一起提交。

## 作者与支持

作者：**[浩哥 / Haoge Truth](https://x.com/haogetruth)** · [X：@haogetruth](https://x.com/haogetruth) · [小红书：浩哥的真话圈](https://xhslink.cn/o/8LW3ZvQOqWR)

想交流研报处理、研究分析和 AI 工具，可以来 [Discord：浩哥的真话圈](https://discord.gg/QzSrHk3Rsf)。

![浩哥的真话圈 Discord 社群二维码](docs/hgs-discord-community-qr.png)

不关注、不进群，也能照常使用。你用自己的 AI 和材料就好，不需要把账号、密码或 API Key 发给我，也不会自动把报告发到这些平台。商业授权可以通过 [X](https://x.com/haogetruth) 联系我。

## 许可证

技能指令和文档采用 [CC BY-NC 4.0](LICENSE)。在许可允许的非商业用途下，可以使用、修改和分享。对外分享原文或改编版时，请注明 Haoge Truth / 浩哥的真话圈与项目来源，附上许可链接；有修改就说明修改，不要暗示作者为改编内容背书。商业用途需要另外授权。

完整条件以 [Creative Commons 许可正文](https://creativecommons.org/licenses/by-nc/4.0/legalcode) 为准。这个许可不包含第三方材料的版权，也不要求每份生成报告都带品牌。这里是带非商业限制的公开分享，不是允许自由商用的软件开源许可。
