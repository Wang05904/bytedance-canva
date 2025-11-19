# Vue 3 + TypeScript + Vite

本项目基于 Vue 3、TypeScript 和 Vite 构建，使用 `<script setup>` 语法糖，实现画布功能。

## 快速启动

### 1. Fork 仓库
在开始之前，请先将本仓库 Fork 到自己的 GitHub 账号下。点击右上角的 **Fork** 按钮即可完成。

### 2. 克隆项目
将 Fork 后的仓库克隆到本地：
```bash
git clone <your-forked-repo-url>
```
### 3. 安装依赖
进入项目目录后，运行以下命令安装依赖：
```bash
pnpm install
```

### 4. 启动开发服务器
运行以下命令启动开发服务器：
```bash
pnpm dev
```

### 5. 构建生产环境
运行以下命令构建生产环境：
```bash
pnpm build
```

### 6. 预览生产环境
运行以下命令预览生产环境：
```bash
pnpm preview
```
## Git提交规范
为了保持代码库的整洁和一致性，请遵循以下提交规范：

- feat: 新功能
- fix: Bug 修复
- docs: 文档变更
- style: 代码样式调整（不影响代码逻辑的变更，例如格式化、空格等）
- refactor: 重构（既不修复 bug 也不增加功能）
- test: 测试相关（添加、修改测试用例等）
- chore: 构建或工具变更（如依赖更新、脚手架配置等）

**提交示例**
```bash
git commit -m "feat: 添加工具栏"
git commit -m "fix: 修复工具栏样式问题"
git commit -m "docs: 更新 README 文档"
git commit -m "style: 调整代码缩进"
git commit -m "refactor: 优化登录逻辑"
git commit -m "test: 添加登录功能的单元测试"
git commit -m "chore: 升级依赖到最新版本"
```
## 提交代码与 PR 流程
1. 创建新分支
在开发新功能或修复 Bug 时，请先从 main 分支拉取最新代码，并创建一个新的分支：
```bash
git checkout -b feat/your-feature-name
```

2. 提交代码
在完成开发后，按照提交规范提交代码：
```bash
git add .
git commit -m "feat: 描述你的功能"
```
3. 推送到远程仓库
将本地分支推送到远程仓库：
```bash
git push origin feat/your-feature-name
```

4. 创建 Pull Request
在 GitHub 上打开你的 Fork 仓库，找到刚刚推送的分支，点击 Compare & Pull Request，填写 PR 描述并提交。

5. Code Review
等待项目维护者进行 Code Review。如果有需要修改的地方，请根据评论进行调整，并重新提交代码。

6. 合并 PR
PR 通过审核后，维护者会将代码合并到主分支。