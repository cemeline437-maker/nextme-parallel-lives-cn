# 更多安装方式

README 中的复制文字是推荐入口。这里适用于支持插件管理或需要项目级安装的用户。

## Codex 项目级安装

```bash
npx skills add https://github.com/cemeline437-maker/nextme-parallel-lives-cn --skill nextme-parallel-lives-cn -a codex --copy -y
```

不加 `-g` 时仅安装到当前项目。安装完成后确认当前项目的 `.agents/skills/nextme-parallel-lives-cn/SKILL.md` 存在。

## Claude Code 项目级安装

```bash
npx skills add https://github.com/cemeline437-maker/nextme-parallel-lives-cn --skill nextme-parallel-lives-cn -a claude-code --copy -y
```

安装完成后确认当前项目的 `.claude/skills/nextme-parallel-lives-cn/SKILL.md` 存在。

## ChatGPT Work / Codex 插件市场

本仓库提供 `.agents/plugins/marketplace.json` 和 `plugins/nextme-parallel-lives-cn/`。在有对应功能的本地环境添加市场：

```bash
codex plugin marketplace add cemeline437-maker/nextme-parallel-lives-cn
```

添加市场不等于安装插件。按当前客户端提示刷新或重新打开应用，在插件目录选择“NextMe平行人生探索”，再安装“NextMe三条平行人生探索教练”。

这个入口是独立仓库市场，不表示已经进入 OpenAI 官方公共插件目录。没有这些功能的界面，使用 README 中的 Markdown 提示词入口。

## Claude Code 插件市场

```text
/plugin marketplace add cemeline437-maker/nextme-parallel-lives-cn
/plugin install nextme-parallel-lives-cn@nextme-parallel-lives
```

插件中只有本 Skill，没有 MCP 服务或自动执行脚本。

## 已有探索材料

可以带着课堂画面开始；也可以在新对话中上传自己的第一份报告，并说：

```text
请沿用我提供的第一份报告，从报告后的新发现继续。不要重新展开三条人生。母题解释仍可修改，完整报告输出后结束。
```

Skill 不会主动读取其他对话或个人文件。换到新对话时，原对话的个人材料不会自动随安装包迁移。

## 格式和限制

通用 ZIP 与 SkillHub ZIP 都保留单个顶层目录 `nextme-parallel-lives-cn/`。通用包使用 Agent Skills 元数据；SkillHub 包额外包含平台需要的中文、英文简介、版本和作者字段，两份教练正文一致。

SkillHub 当前上传规则只接受支持的文本文件扩展名，因此该包仅含 `SKILL.md`，图标单独上传。MIT 许可证保留在 GitHub 和通用包中，SkillHub 元数据也注明 MIT。

安装、发现和启用的入口随产品和账号能力变化，以当前平台界面为准。Skills CLI 支持 `-g`、`-a`、`--copy` 和 `-y`，其行为可在[维护方文档](https://github.com/vercel-labs/skills)中核对。
