# Competitive Programming Pro Skill

这是一个为算法竞赛选手量身定制的 AI Agent Skill。它不仅能帮你写题，还能深度模仿你的代码风格，并提供完整的解题思维报告。

## ✨ 核心特性

- **主动交互**：启动时会询问爬题需求、认证信息及任务范围，确保不偏离目标。
- **影子学习 (Style Shadowing)**：自动扫描你的本地代码，学习你的空格、缩进、变量命名及算法实现习惯（极大降低代码的 AI 感）。
- **模板支持**：自动寻找并使用你习惯的 `template.cpp` 等文件。
- **自动验证**：提取题目样例并进行本地编译运行，验证通过后再提交。
- **思维模拟**：以第一人称撰写 `THOUGHTS.md`，记录解题时的心路历程、瓶颈及优化思路。
- **工具联动**：支持一键生成题目讲解演示文稿（需配合相关 PPT 插件/Skill）。

## 🚀 快速上手

### 安装方式

你可以将此仓库导入到你支持 Skill/Plugin 的 AI Agent 目录中。

对于支持 Git 安装的 Agent：
```bash
git clone https://github.com/CheemsaDoge/myco!!!!!.skill.git
```

### 使用示例

- **场景 A：爬取新题**
  > "帮我处理这道题：https://example.com/problem/1001"
- **场景 B：处理本地题目**
  > "把这个目录下的所有算法题按我的风格重写一遍。"
- **场景 C：生成讲解文档**
  > "为这道题写一个思维导图式的解题报告，并准备好讲解 PPT。"

## 📂 目录结构

执行后，Skill 会自动创建如下结构：
```text
solutions/
└── Platform/
    └── ProblemID/
        ├── solution.cpp    (你的个性化代码)
        ├── sample.in       (样例输入)
        ├── sample.ans      (样例输出)
        ├── THOUGHTS.md     (做题心路历程)
        └── presentation.pptx (演示文稿)
```
