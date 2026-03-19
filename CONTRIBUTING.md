# Contributing to ReqCatcher

感谢您对需求捕手（ReqCatcher）的兴趣！我们欢迎所有形式的贡献。

## 🎯 项目愿景

ReqCatcher 致力于成为 OpenClaw 生态系统中**最专业的需求澄清专家**。我们的目标是让每一次 AI 协作都建立在充分理解的基础上。

---

## 🤝 如何贡献

### 1. 报告问题 (Bug Reports)

如果您发现了问题，请通过 GitHub Issues 报告：

- 使用清晰的标题描述问题
- 提供复现步骤
- 说明期望行为 vs 实际行为
- 附上相关日志或截图

### 2. 功能建议 (Feature Requests)

有新想法？欢迎提交 Feature Request：

- 描述该功能解决的问题
- 说明目标用户场景
- 如果可能，提供实现思路

### 3. 代码贡献 (Code Contributions)

#### 开发环境设置

```bash
# 克隆仓库
git clone https://github.com/yourusername/requirement-clarifier.git
cd requirement-clarifier

# 创建分支
git checkout -b feature/your-feature-name
```

#### 提交规范

我们使用 [Conventional Commits](https://www.conventionalcommits.org/) 规范：

```
<type>(<scope>): <description>

[optional body]

[optional footer]
```

**类型 (Type)**：
- `feat`: 新功能
- `fix`: Bug 修复
- `docs`: 文档更新
- `style`: 代码格式调整
- `refactor`: 重构
- `test`: 测试相关
- `chore`: 构建/工具链

**示例**：
```
feat(domain): 添加医疗行业需求模板

docs: 更新 README 中的安装说明

fix(template): 修复参数化建模中的边界条件描述
```

### 4. 文档贡献 (Documentation)

文档是我们的核心资产！欢迎改进：

- **SKILL.md**: 核心工作流改进
- **references/**: 新增行业案例
- **README.md**: 使用说明完善

---

## 📋 贡献清单

提交 PR 前，请确认：

- [ ] 代码符合项目风格
- [ ] 新增功能有相应文档
- [ ] 复杂变更更新了 references/case-studies.md
- [ ] 提交信息符合规范
- [ ] 如有新增领域模板，更新 domain-templates.md

---

## 🏗️ 项目结构指南

```
requirement-clarifier/
├── SKILL.md              # 核心工作流（谨慎修改）
├── README.md             # 项目介绍
├── LICENSE               # 许可证
├── CONTRIBUTING.md       # 本文件
├── assets/               # 静态资源
├── references/           # 参考资料
│   ├── domain-templates.md   # 领域模板库
│   ├── case-studies.md       # 案例集
│   └── case-study-*.md       # 特定案例
└── scripts/              # 工具脚本
```

---

## 🎨 领域模板贡献指南

如果您想为特定行业添加需求澄清模板：

1. 在 `references/domain-templates.md` 中添加模板
2. 模板结构：
   ```markdown
   ## [行业名称]

   ### 触发条件
   - 关键词识别
   - 上下文特征

   ### 核心问题清单
   1. **业务目标**：...
   2. **技术约束**：...
   3. **质量要求**：...

   ### 参数化抽象维度
   - 变量1：...
   - 变量2：...

   ### 典型边界条件
   | 实体A | 实体B | 关系 |
   ```

3. 附上真实案例（脱敏处理）

---

## 📝 案例研究贡献

优秀的案例研究应包含：

1. **背景**：用户原始需求描述
2. **挑战**：为什么需要澄清
3. **过程**：使用了哪些技术
4. **结果**：最终规格文档
5. **复盘**：可复用的经验

参考格式见 `references/case-study-ansys.md`

---

## 💬 交流渠道

- **GitHub Issues**: Bug 报告、功能建议
- **GitHub Discussions**: 一般性讨论
- **邮件**: your-email@example.com

---

## ⚖️ 行为准则

参与本项目即表示您同意：

1. **尊重他人**：友善、包容、专业
2. **建设性反馈**：批评针对问题，而非个人
3. **乐于帮助**：新手的"简单问题"也值得认真对待
4. **关注成果**：以项目目标为导向

---

## 🙏 致谢

感谢所有贡献者让这个 Skill 变得更好！

特别感谢：
- 中关村北纬龙虾大赛组委会
- OpenClaw 社区
- 每一位提出宝贵意见的用户

---

## 📜 许可

通过贡献代码，您同意将其授权为 [MIT License](LICENSE)。
