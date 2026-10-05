# NextMe三条平行人生探索教练

NextMe第二曲线实验室的课后 Life Design Coach。一次只问一个问题，陪你把三条平行人生想得更深入，找到反复出现的母题，再一起形成一个目前愿意先了解的方向。完整报告生成后结束，不自动进入商业模式分析。

## 选择你的工具

| 你使用的工具 | 最短入口 |
| --- | --- |
| ChatGPT / Codex | [复制一段安装或使用说明](#chatgpt--codex) |
| Claude | [复制一段安装说明，或下载上传包](#claude) |
| WorkBuddy | [到 SkillHub 选择安装](https://skillhub.cn/skills/user_ef208136/nextme-parallel-lives-cn) |

材料全部可选：课堂笔记、同伴反馈、有能量的片段、Knowing Why / Knowing How / Knowing Whom。可以上传，也可以口述。没有材料或没有参加课堂，也能从头开始，不用专门准备。

## ChatGPT / Codex

### 把下面一段发给 AI

```text
请帮我安装并使用 NextMe三条平行人生探索教练，仓库是：
https://github.com/cemeline437-maker/nextme-parallel-lives-cn

Skill 标识是 nextme-parallel-lives-cn。
如果当前工具支持操作本地文件和安装 Skills，请安装到当前用户的 Codex skills 目录：
npx skills add https://github.com/cemeline437-maker/nextme-parallel-lives-cn --skill nextme-parallel-lives-cn -g -a codex --copy -y

安装前检查是否已有同名 Skill；如果已有，不要直接覆盖，先告诉我。安装后检查 SKILL.md 中的 name 为 nextme-parallel-lives-cn，版本为 4.1.0，确认文件存在后再说安装成功。

如果当前聊天界面不支持本地安装，请明确告诉我，然后完整读取下面的提示词，只在本次对话中使用，不要声称已经永久安装：
https://raw.githubusercontent.com/cemeline437-maker/nextme-parallel-lives-cn/main/docs/coach-prompt.md
如果无法读取链接，请让我上传这个 Markdown 文件，不要凭简介开始对话。

准备好后，按教练规则从当前材料进度继续；我没有材料就从头开始。一次只问一个问题，完整报告输出后停止，不自动进入实干家阶段。
```

### 一行安装命令

```bash
npx skills add https://github.com/cemeline437-maker/nextme-parallel-lives-cn --skill nextme-parallel-lives-cn -g -a codex --copy -y
```

有插件管理能力的 ChatGPT Work / Codex 也可使用本仓库的插件市场。参见 [更多安装方式](docs/installation.md)。

## Claude

### 把下面一段发给 AI

```text
请帮我安装并使用 NextMe三条平行人生探索教练，仓库是：
https://github.com/cemeline437-maker/nextme-parallel-lives-cn

Skill 标识是 nextme-parallel-lives-cn。
如果当前是 Claude Code，或支持终端和本地 Skills 安装的环境，请安装到当前用户的 Claude Code skills 目录：
npx skills add https://github.com/cemeline437-maker/nextme-parallel-lives-cn --skill nextme-parallel-lives-cn -g -a claude-code --copy -y

安装前检查是否已有同名 Skill；如果已有，不要直接覆盖，先告诉我。安装后检查 SKILL.md 中的 name 为 nextme-parallel-lives-cn，版本为 4.1.0，确认文件存在后再说安装成功。

如果当前是不能替我修改技能设置的 Claude 聊天界面，不要虚报安装成功。请给我这个 ZIP 下载链接，并提示我在当前账号的 Skills 设置中上传并启用：
https://github.com/cemeline437-maker/nextme-parallel-lives-cn/raw/main/dist/nextme-parallel-lives-cn.zip

如果当前账号不支持上传，也可以完整读取本仓库 docs/coach-prompt.md，在本次对话中使用；无法读取时请让我上传 Markdown。

准备好后，按教练规则从当前材料进度继续；我没有材料就从头开始。一次只问一个问题，完整报告输出后停止，不自动进入实干家阶段。
```

### 一行安装命令

```bash
npx skills add https://github.com/cemeline437-maker/nextme-parallel-lives-cn --skill nextme-parallel-lives-cn -g -a claude-code --copy -y
```

### Claude 上传包

[下载 Skill ZIP](https://github.com/cemeline437-maker/nextme-parallel-lives-cn/raw/main/dist/nextme-parallel-lives-cn.zip)，在账号支持的 Skills 设置中上传并启用。ZIP 第一层是 `nextme-parallel-lives-cn/`，其中包含 `SKILL.md`。

## WorkBuddy / SkillHub

[打开 SkillHub 技能页面](https://skillhub.cn/skills/user_ef208136/nextme-parallel-lives-cn)。在 WorkBuddy 技能库选择 SkillHub 来源，搜索“NextMe三条平行人生探索教练”或 `nextme-parallel-lives-cn`，核对标识 `@user_ef208136/nextme-parallel-lives-cn` 后点击安装。

SkillHub 上架需要经过平台审核；若暂时还搜不到，使用 [WorkBuddy 上传包](https://github.com/cemeline437-maker/nextme-parallel-lives-cn/raw/main/dist/nextme-parallel-lives-cn-skillhub.zip) 在支持上传技能的界面导入。本包不需要 API 密钥或连接器授权。

安装后直接说：

```text
请用 NextMe三条平行人生探索教练陪我探索第二曲线。我可以先说课堂上记得的画面；没有材料时，请从头引导。
```

## 会得到什么

第一轮报告包括三条人生深化版、核心母题及解释、重要差异与尚未想清楚的地方。之后继续聊你的新发现，形成你目前愿意先了解的方向。

第二轮报告把两轮内容合并为完整的 1–7：前三部分加上方向草稿、它的来由与其他路径的关系、值得先了解的原因、留给下一步商业模式推演和用户访谈的未知问题。最后一句后结束，不再追问。

这不是职业测评或商业可行性结论，也不要求放弃其他路径。没有形成方向时，会如实记录进度和缺口。

## 隐私

这个仓库不包含作者或学员的个人报告、试用对话、私人联系方式、本机路径和账号凭证。仅包含通用教练规则与分发文件。

你提供的材料仍会由所用 AI 平台处理，请按需匿名化，遵循该平台的隐私设置。详见 [隐私说明](docs/privacy.md)。

## 下载与版本

- 对话规则：v4.1；分发版本：4.1.0。
- [通用 Skill ZIP](https://github.com/cemeline437-maker/nextme-parallel-lives-cn/raw/main/dist/nextme-parallel-lives-cn.zip)
- [WorkBuddy / SkillHub ZIP](https://github.com/cemeline437-maker/nextme-parallel-lives-cn/raw/main/dist/nextme-parallel-lives-cn-skillhub.zip)
- [校验和](dist/SHA256SUMS)
- [可直接用于聊天的完整提示词](docs/coach-prompt.md)

`npx skills` 是第三方开源安装工具，不是 OpenAI 或 Anthropic 的官方安装命令。本仓库也提供平台插件包装和 ZIP。

## 平台依据

- [OpenAI 插件打包](https://developers.openai.com/plugins/build/plugins)：插件市场与本地分发。
- [Claude 自定义 Skills](https://claude.com/docs/skills/how-to)：Skill 目录和 ZIP 上传。
- [WorkBuddy 技能结构](https://open.workbuddy.cn/docs/skill)：技能元数据与目录。
- [Skills CLI](https://github.com/vercel-labs/skills)：按目标 Agent 安装。

## License

MIT，作者为 NextMe。见 [LICENSE](LICENSE)。
