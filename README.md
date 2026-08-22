# 🎯 BigLead · 精准客户线索挖掘

按行业/产品/地区搜索目标公司，多渠道交叉验证，提取联系方式（如有），管理客户线索库。B2B 销售、市场调研、竞品分析。

> English: B2B lead generation: search target companies, cross-validate, extract contacts, manage pipeline.

## ✨ 功能

详见 [SKILL.md](SKILL.md) 完整说明。

## 🔧 环境依赖

Python 3 + 联网搜索能力（web search 工具）。

## 📥 安装（DeepSeek Harness / dsh）

本技能遵循 **Agent Skills 开放标准**（SKILL.md + YAML frontmatter），适用于 DeepSeek Harness (dsh)、OpenClaw、Claude Code 等支持 Agent Skills 的框架。

```bash
# 方式一：放入用户级共享目录（推荐）
mkdir -p ~/.agents
git clone https://github.com/kobenfang/biglead.git ~/.agents/biglead

# 方式二：放入项目目录
mkdir -p .agents
cp -r biglead .agents/
```

dsh 启动后即可在技能列表中找到 `biglead`。

## 🔍 搜索关键词

客户线索, 销售, B2B, 获客, 市场调研, lead generation, sales prospecting

## 📄 目录结构

```
biglead/
├── SKILL.md          # 技能定义（Agent Skills 标准）
├── scripts/biglead.py
```

## ⚖️ License

MIT

---
© 2026 [kobenfang](https://github.com/kobenfang) · 更多技能见 [dsh-skills](https://github.com/kobenfang/dsh-skills)

## 📦 Also on ClawHub (OpenClaw)

This skill is also published on [ClawHub](https://clawhub.ai) for OpenClaw users:

```bash
npx clawhub install biglead
```

Search it: `npx clawhub search biglead`
