<div align="center">

# 🔍 competitive-analysis-skill
### *Four ancient strategists walk into a product meeting. This is what they'd say.*
### *四位智者联手，帮你看穿任何竞品。*

</div>

<div align="center">

**[English](#english) · [中文](#chinese)**

</div>

---

<a name="english"></a>

## What is this?

A Claude Skill that turns competitive research from a weekend chore into a 10-minute report. Give it 2 or more product names, and it auto-researches official sites, user reviews, and market positioning — then outputs a structured analysis through the lens of four strategic frameworks: Fan Li's market intuition, Hu Xueyan's competitive instinct, Peter Drucker's user-value lens, and Michael Porter's Five Forces.

It doesn't write PR copy. It tells you what's actually good, what's actually broken, and who should actually use what.

## ✨ Features

- 🏛️ **Four-strategist framework** — Fan Li, Hu Xueyan, Drucker, and Porter each contribute their angle to the analysis
- 🔎 **Auto web research** — fetches official sites + external reviews (少数派, 知乎, 36kr, etc.) per product
- 📊 **Side-by-side comparison table** — structured Markdown table across 10+ dimensions
- 🎯 **Buyer persona matrix** — tells individual users, developers, enterprises, and budget-conscious buyers exactly which product fits them
- ⚠️ **Risk-first honesty** — every product's weaknesses and failure modes are named explicitly
- 🦞 **Merchant Sage closing** — a 2-4 sentence closing insight written in Fan Li's voice, pointing out the market's hidden trap

## 🚀 How to Use

**Step 1 — Install the skill**

Copy `SKILL.md` into your Claude skills directory:

```
/mnt/skills/user/competitive-analysis-skill/SKILL.md
```

**Step 2 — Trigger it**

Just mention 2+ products with any comparison intent:

```
帮我对比一下 Notion、Obsidian 和 Roam Research
Which is better for teams: Linear, Jira, or Asana?
分析这几个 AI 写作工具：Jasper、Copy.ai、秘塔写作猫
```

**Step 3 — Get your report**

The skill outputs in this order:
1. Per-product deep dive (8 dimensions each)
2. Side-by-side comparison table
3. Buyer persona recommendations
4. Merchant Sage closing insight

## 📋 Output Structure

```
Per product:     Positioning · Company background · Target users
                 Core advantages · Who should/shouldn't use it
                 Value-for-money · Real user feedback

Comparison:      10+ dimension Markdown table

Recommendations: User type → Best fit → Reasoning

Closing:         Fan Li's market wisdom in classical style
```

## 📬 Contact

- GitHub: [@Timelovers](https://github.com/Timelovers)
- Website: [lijiaxing.com.cn](https://lijiaxing.com.cn/)

---

<a name="chinese"></a>

## 这是什么？

一个 Claude Skill——输入 2 个以上的产品名称，它会自动抓取官网内容和外部口碑，用四位智者的视角做完整分析，最后输出单品深度报告 + 横向对比表 + 选型建议 + 商圣点评。

不写广告稿。说清楚哪个好、哪个有坑、你到底该用哪个。

## ✨ 功能亮点

- 🏛️ **四维智者框架** — 范蠡的市场直觉、胡雪岩的竞争嗅觉、德鲁克的用户价值思维、波特五力模型，四个视角同时上
- 🔎 **自动调研** — 每个产品自动抓取官网 + 少数派、知乎、36kr 等外部评价，信息不靠猜
- 📊 **横向对比表** — 10+ 维度 Markdown 表格，一眼看出差异
- 🎯 **选型建议矩阵** — 按用户类型（个人、开发者、企业、预算有限、注重隐私）分别给出推荐和理由
- ⚠️ **风险不回避** — 每个产品的缺点和风险必须写清楚，不做 PR
- 🦞 **商圣点评** — 以范蠡口吻总结市场本质规律，点出最值得警惕的竞争陷阱

## 🚀 快速开始

**第一步 — 安装 Skill**

将 `SKILL.md` 复制到你的 Claude skills 目录：

```
/mnt/skills/user/competitive-analysis-skill/SKILL.md
```

**第二步 — 触发**

说出 2 个以上产品名称 + 比较意图即可触发：

```
帮我对比一下 Notion、Obsidian 和 Roam Research
分析这几个 AI 写作工具：Jasper、Copy.ai、秘塔写作猫
Linear、Jira、Asana 哪个适合小团队？
```

**第三步 — 获得报告**

按顺序输出：
1. 每个产品的 8 维度深度分析
2. 横向对比表
3. 用户类型选型建议
4. 商圣点评（范蠡风格收尾）

## 📋 输出结构

```
单品分析：  定位 · 背后公司 · 目标用户
           核心优势 · 适合 / 不适合的人
           性价比评估 · 真实用户口碑

横向对比：  10+ 维度 Markdown 表格

选型建议：  用户类型 → 推荐产品 → 理由

商圣点评：  范蠡古典商业智慧语言收尾
```

---

> 「知彼知己，百战不殆；不知彼而知己，一胜一负；不知彼，不知己，每战必殆。」
>
> *Know your enemy and yourself, and you will win every battle.*

---

<div align="center">

Made with 💜 by [Sara](https://lijiaxing.com.cn/) · [@Timelovers](https://github.com/Timelovers)

</div>
