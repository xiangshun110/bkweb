# 百科软件 - 公司官网

这是百科软件公司的官方网站，使用 Vue 3 + Vite 构建。

## 功能特性

- 🏠 **首页英雄区域** - 吸引人的渐变背景和公司介绍
- 💼 **服务展示** - 四大核心业务服务展示
- 👥 **关于我们** - 公司介绍和成就统计
- 📞 **联系方式** - 完整的联系信息
- 📱 **响应式设计** - 支持桌面和移动设备
- 🎨 **现代化UI** - 简洁美观的界面设计

## 技术栈

- **Vue 3** - 渐进式 JavaScript 框架
- **Vite** - 现代前端构建工具
- **CSS3** - 现代样式设计
- **响应式布局** - 移动端适配

## 开发环境设置

### 前置要求

- Node.js (v16 或更高版本)
- npm 或 yarn

### 安装依赖

```bash
npm install
```

### 启动开发服务器

```bash
npm run dev
```

访问 [http://localhost:5173](http://localhost:5173) 查看网站。

### 构建生产版本

```bash
npm run build
```

构建文件将输出到 `dist/` 目录。

### 预览生产版本

```bash
npm run preview
```

## 项目结构

```
bkweb/
├── public/              # 静态资源
├── src/
│   ├── assets/         # 样式和图片资源
│   ├── components/     # Vue 组件
│   ├── App.vue        # 主应用组件
│   └── main.js        # 应用入口文件
├── index.html         # HTML 模板
├── package.json       # 项目配置
└── vite.config.js     # Vite 配置
```

## 网站截图

### 桌面版
![桌面版网站](https://github.com/user-attachments/assets/bd2ea571-3ace-4863-8371-c3c37c906a43)

### 移动版
![移动版网站](https://github.com/user-attachments/assets/c484f129-8afe-403e-b1a2-34555debcad6)

## 部署

项目可以部署到任何支持静态文件托管的平台：

- **Vercel**: `npm run build` 后上传 `dist` 目录
- **Netlify**: 连接 Git 仓库自动部署
- **GitHub Pages**: 使用 GitHub Actions 自动构建部署

## 许可证

© 2024 百科软件. 保留所有权利.
