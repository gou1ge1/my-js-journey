# JavaScript 学习项目 - Agent 配置

## 项目概述

这是一个 JavaScript 前端学习项目，包含以下内容：
- JavaScript 基础语法学习（var、let、const 等）
- 作用域链概念
- 前端学习计划和路线图

## 代码规范

### HTML 文件
- 使用语义化 HTML5 标签
- 保持代码缩进一致（2 空格）
- 添加适当的中文注释

### Markdown 文件
- 使用中文编写
- 标题层级清晰
- 保持格式一致性

## Git 操作规范

### 提交规范
- 使用中文描述提交内容
- 提交前检查 `git status`
- 小幅度、频繁提交

### 推送前检查
- 确认工作区干净：`git status`
- 查看变更：`git diff --staged`
- 确认远程地址正确

### 冲突处理
- 使用 `git fetch` 获取远程状态
- 使用 `git pull --rebase` 而非直接 merge
- 避免使用 `git reset --hard`，除非确认安全

## Agent 行为准则

1. **安全第一**：执行破坏性操作前（如 reset、rebase）先确认
2. **透明沟通**：告知用户正在执行的操作和可能的风险
3. **保护数据**：重要文件操作前备份
4. **网络问题**：GitHub 连接失败时提示用户检查网络
