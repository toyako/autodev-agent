# 贡献指南

欢迎为AI全栈开发助手项目贡献代码！以下是参与贡献的指南。

## 🎯 贡献方式

### 1. 报告问题
- 使用GitHub Issues报告bug或提出功能建议
- 在报告前请先搜索是否已有类似问题
- 提供详细的问题描述和复现步骤

### 2. 提交代码
- Fork本仓库
- 创建功能分支 (`git checkout -b feature/amazing-feature`)
- 提交更改 (`git commit -m 'Add some amazing feature'`)
- 推送到分支 (`git push origin feature/amazing-feature`)
- 创建Pull Request

### 3. 改进文档
- 修正拼写错误或语法问题
- 补充缺失的文档
- 翻译文档到其他语言

## 📋 开发环境设置

### 前置要求
- Node.js >= 18.0.0
- npm >= 8.0.0 或 yarn >= 1.22.0
- Git

### 安装步骤
```bash
# 克隆仓库
git clone https://github.com/toyako/autodev-agent.git
cd autodev-agent

# 安装依赖
npm install

# 启动开发服务器
npm run dev
```

## 🧪 测试

### 运行测试
```bash
# 运行所有测试
npm test

# 运行特定测试文件
npm test -- src/core/ai-engine/engine.test.js

# 查看测试覆盖率
npm run test:coverage
```

### 测试规范
- 每个功能模块都应有对应的单元测试
- 测试覆盖率应达到80%以上
- 使用Jest作为测试框架

## 📝 代码规范

### 代码风格
- 使用ESLint进行代码检查
- 遵循JavaScript Standard Style
- 使用Prettier进行代码格式化

### 提交信息规范
使用约定式提交（Conventional Commits）：
- `feat:` 新功能
- `fix:` bug修复
- `docs:` 文档更新
- `style:` 代码格式调整
- `refactor:` 代码重构
- `test:` 测试相关
- `chore:` 构建过程或辅助工具变动

示例：
```
feat: 添加AI需求分析功能
fix: 修复部署脚本路径问题
docs: 更新快速开始指南
```

### 分支命名
- `feature/` - 新功能开发
- `bugfix/` - bug修复
- `hotfix/` - 紧急修复
- `release/` - 版本发布
- `docs/` - 文档更新

## 🏗️ 项目架构

### 核心模块
1. **AI引擎** (`src/core/ai-engine/`)
   - 与大模型交互
   - 需求分析和代码生成

2. **代码生成器** (`src/core/code-generator/`)
   - 项目结构生成
   - 代码文件生成

3. **部署工具** (`src/tools/deploy/`)
   - 服务器部署
   - Docker容器化
   - 云平台集成

### 开发流程
1. 需求分析 → 2. 技术设计 → 3. 代码实现 → 4. 测试验证 → 5. 文档更新

## 🔧 开发工具

### 推荐工具
- **编辑器**: VS Code
- **终端**: Windows Terminal / PowerShell
- **Git客户端**: Git CLI / GitHub Desktop
- **API测试**: Postman / Insomnia

### VS Code扩展推荐
- ESLint
- Prettier
- GitLens
- Code Spell Checker
- JavaScript (ES6) code snippets

## 🚀 发布流程

### 版本管理
使用语义化版本（SemVer）：
- `MAJOR` - 不兼容的API修改
- `MINOR` - 向下兼容的功能新增
- `PATCH` - 向下兼容的问题修复

### 发布步骤
1. 更新版本号 (`package.json`)
2. 更新CHANGELOG.md
3. 创建发布分支 (`release/v1.0.0`)
4. 运行完整测试套件
5. 构建生产版本
6. 创建GitHub Release
7. 发布到npm仓库

## 📚 文档编写

### 文档结构
- `docs/` - 项目文档
- `examples/` - 示例项目
- `API.md` - API参考文档
- `CHANGELOG.md` - 版本变更日志

### 文档规范
- 使用Markdown格式
- 包含代码示例
- 提供清晰的步骤说明
- 保持文档与代码同步更新

## 🤝 社区交流

### 沟通渠道
- GitHub Issues: 问题讨论和功能建议
- GitHub Discussions: 技术讨论和想法分享
- Pull Requests: 代码审查和合并

### 行为准则
我们遵循[贡献者公约](CODE_OF_CONDUCT.md)，请确保：
- 使用友好和尊重的语言
- 接纳不同的观点和经验
- 建设性地接受批评
- 关注社区的整体利益

## 🏆 参赛项目特别说明

本项目参加"中关村北纬龙虾大赛"生产力赛道，作为参赛作品：
- 所有代码开源，遵循MIT许可证
- 欢迎社区贡献和改进
- 参赛期间会持续更新和完善
- 赛后将继续维护和发展

## 📞 联系方式

- **项目负责人**: Your Name
- **GitHub**: [@toyako](https://github.com/toyako)
- **邮箱**: contact@autodev.ai
- **大赛页面**: [中关村北纬龙虾大赛]()

感谢你的贡献！🎉