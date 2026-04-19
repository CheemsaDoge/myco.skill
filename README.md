# Competitive Programming Pro Skill

这是一个为算法竞赛选手量身定制的通用 AI Agent Skill。它可以自动爬题、深度模仿你的代码风格，并提供完整的解题思维过程。

## ✨ 核心特性

- **主动确认**：在执行前主动询问爬题需求、认证信息（如 Cookie）及任务范围。
- **影子模仿 (Style Shadowing)**：自动分析你本地现有的代码文件，学习你的缩进、括号放置、变量命名及算法逻辑（大幅降低生成代码的 AI 感）。
- **模板优先**：自动寻找并应用你的 `template.cpp` 等模板文件。
- **自动化验证**：抓取题目样例并在本地编译运行，验证通过后再最终交付。
- **思维模拟**：以第一人称生成 `THOUGHTS.md`，记录解题时的心路历程、瓶颈及优化决策。
- **跨工具联动**：支持生成演示文稿（需配合相关的 PPT 插件或 Skill）。

## 🚀 快速上手

### 1. 安装

将此仓库克隆或导入到你 AI Agent 的 Skill/Plugin 目录中。

```bash
git clone https://github.com/CheemsaDoge/myco-.skill.git
```

### 2. 使用方法

直接在对话中触发（取决于你的 Agent 实现）：

- **场景 A：爬取并解决新题**
  > "处理这道题：https://example.com/problem/1001"
- **场景 B：批量处理本地文件**
  > "分析这个目录下的题目并按我的代码风格重写。"
- **场景 C：生成讲解文档**
  > "为这道题写一个深度的解题报告，并准备好讲解用的 PPT 内容。"

## 📂 目录结构

执行后，Skill 会在题目文件夹内创建以下结构：
```text
solutions/
└── [Platform]/
    └── [ProblemID]/
        ├── solution.cpp    (符合你个人风格的代码)
        ├── sample.in       (自动抓取的样例输入)
        ├── sample.ans      (自动抓取的样例输出)
        ├── THOUGHTS.md     (做题心路历程报告)
        └── presentation.pptx (可选的讲解PPT)
```

---
*Powered by AI Agent Orchestration.*
