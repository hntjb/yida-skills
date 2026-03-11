# 贡献指南

感谢你对 yida-skills 项目的兴趣！我们欢迎任何形式的贡献。

## 如何贡献

### 报告 Bug

1. 搜索现有 Issue 确认是否已报告
2. 使用 Issue 模板创建新 Issue
3. 包含复现步骤和环境信息

### 提出新功能

1. 搜索现有 Issue 和 PR
2. 使用 Feature Request 模板描述功能
3. 说明使用场景和预期行为

### 提交代码

1. Fork 本仓库
2. 创建功能分支：`git checkout -b feature/xxx`
3. 进行修改并确保 CI 通过
4. 提交 PR 描述修改内容

## 开发环境

```bash
# 克隆仓库
git clone https://github.com/openyida/yida-skills.git

# 安装依赖
npm install

# 本地测试
node --check skills/*/scripts/*.js
```

## 代码规范

- JavaScript 使用 ES6+ 语法
- 提交信息使用中文，描述清晰
- PR 需要描述修改目的和内容

## PR 审核标准

- [ ] CI 检查通过
- [ ] 代码符合项目风格
- [ ] 文档已更新（如需要）
- [ ] 测试通过（如有）

## 行为准则

请阅读 [CODE_OF_CONDUCT.md](./CODE_OF_CONDUCT.md) 了解社区行为标准。
