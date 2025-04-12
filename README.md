# 🌐 Vue 3 + Vite 前端项目

本项目基于 Vue 3 和 Vite 构建，适用于后台管理系统、展示页面等场景，具备快速开发能力与良好扩展性。

---

## 📦 项目特性

- ⚡ 快速启动与热更新
- 🌍 内置 Vue Router 路由系统
- 🧠 集成 Pinia 状态管理
- 📱 响应式布局，适配多端设备
- 🔐 简易登录认证示例

---

## 🛠 技术栈

- [Vue 3](https://vuejs.org/)
- [Vite](https://vitejs.dev/)
- [Vue Router](https://router.vuejs.org/)
- [Pinia](https://pinia.vuejs.org/)
- [Tailwind CSS](https://tailwindcss.com/)

---

## 🔐 默认测试账号

> 可使用以下账号体验系统功能：

- **账号**：`admin`  
- **密码**：`admin`

⚠️ *该账号仅用于测试环境，正式部署请务必更换为安全的认证方式。*

---

## 🚀 快速开始

### 1. 克隆项目

```bash
git clone https://github.com/1dust134/The-second-project.git
cd The-second-project
```

### 2. 安装依赖

```bash
pnpm install
# 或者使用 npm / yarn
```

### 3. 启动项目

```bash
pnpm dev
```

---

## 📁 项目结构简述

```
├── public/          # 静态资源
├── src/             
│   ├── assets/      # 图片、样式等资源
│   ├── components/  # 公共组件
│   ├── views/       # 页面视图
│   ├── router/      # 路由配置
│   ├── store/       # 状态管理（Pinia）
│   └── App.vue      # 根组件
├── vite.config.ts   # Vite 配置
└── ...
```

---

## 📦 构建与部署

### 构建生产环境代码

```bash
pnpm build
```

构建完成后，产物位于 `dist/` 文件夹，可用于部署到生产环境。

### GitHub Pages 部署（可选）

若需将项目部署到 GitHub Pages，可使用以下命令：

```bash
pnpm run deploy
```

确保 `vite.config.ts` 中已正确配置 `base` 路径。

---

## 📮 反馈与支持

👏 感谢使用本项目！

如果您觉得本项目对您有帮助，欢迎点个 ⭐️ Star 支持一下！

如在使用过程中遇到问题，欢迎通过 [Issue](https://github.com/1dust134/The-second-project/issues) 提出建议或反馈问题。