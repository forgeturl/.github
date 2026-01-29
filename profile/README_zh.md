<p align="center">
  <img src="https://forgeturl.com/favicon.svg" alt="ForgetURL Logo" width="120" height="120">
</p>

<h1 align="center">ForgetURL</h1>

<p align="center">
  <strong>🔖 极简书签管理 · 让收藏变得简单</strong>
</p>

<p align="center">
  <a href="https://forgeturl.com" target="_blank">
    <img src="https://img.shields.io/badge/🚀_立即使用-ForgetURL.com-blue?style=for-the-badge" alt="Use Now">
  </a>
</p>

<p align="center">
  <a href="#-功能特性">功能特性</a> •
  <a href="#-产品截图">产品截图</a> •
  <a href="#-技术架构">技术架构</a> •
  <a href="#-快速开始">快速开始</a> •
  <a href="#-开源协议">开源协议</a>
</p>

<p align="center">
  <a href="./README.md">English</a> | 中文
</p>

---

## 🌟 为什么选择 ForgetURL？

> 厌倦了臃肿的书签管理器？**ForgetURL** 让你专注于真正重要的事情 —— **收藏链接，分享知识**。

在信息爆炸的时代，我们每天都会发现值得收藏的网页。但传统的浏览器书签功能往往杂乱无章，难以管理和分享。**ForgetURL** 应运而生，它是一款**极简主义**的书签管理工具，帮助你优雅地整理、分享你的网络收藏。

<p align="center">
  <a href="https://forgeturl.com" target="_blank">
    <img src="https://img.shields.io/badge/开始使用-→_ForgetURL.com-2ea44f?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Get Started">
  </a>
</p>

---

## ✨ 功能特性

<table>
<tr>
<td width="50%">

### 🔐 安全登录
- 支持 **Google** 账号登录
- 支持 **GitHub** 账号登录
- 安全的 Token 认证机制
- 一键登录，无需注册

</td>
<td width="50%">

### 📖 书签管理
- 创建多个书签页面
- 链接分组管理（Collections）
- 支持标签和子链接
- 实时编辑，自动保存

</td>
</tr>
<tr>
<td width="50%">

### 🔗 灵活分享
| 分享类型 | 权限 |
|---------|------|
| 🔒 只读链接 | 仅查看 |
| ✏️ 编辑链接 | 可修改内容 |
| 👑 管理链接 | 完全控制 |

</td>
<td width="50%">

### 📱 极致体验
- 响应式设计，完美适配移动端
- 类 X.com / ChatGPT 的极简风格
- 流畅的动画过渡
- 深色/浅色主题支持

</td>
</tr>
</table>

### 更多特性

- 📥 **导入/导出** - 支持从浏览器导入书签
- 🏷️ **标签系统** - 为链接添加标签，快速筛选
- 📂 **链接分组** - 通过 Collections 组织相关链接
- 🔄 **版本控制** - 防止编辑冲突，数据更安全
- 🌍 **多环境** - 支持本地、测试、生产环境

---

## 🖼️ 产品截图

<p align="center">
  <em>极简的登录界面</em>
</p>

```
┌─────────────────────────────────────────────────────────┐
│                                                         │
│                    🔖 ForgetURL                         │
│                                                         │
│              极简书签管理，让收藏更简单                    │
│                                                         │
│         ┌─────────────────────────────┐                 │
│         │   🔵  Continue with Google  │                 │
│         └─────────────────────────────┘                 │
│         ┌─────────────────────────────┐                 │
│         │   ⚫  Continue with GitHub  │                 │
│         └─────────────────────────────┘                 │
│                                                         │
└─────────────────────────────────────────────────────────┘
```

<p align="center">
  <em>清爽的书签管理界面</em>
</p>

```
┌─────────────────────────────────────────────────────────┐
│  🔖 ForgetURL                              [用户头像]   │
├─────────────────────────────────────────────────────────┤
│                                                         │
│  我的空间                              [+ 创建页面]     │
│                                                         │
│  ┌─────────────────┐  ┌─────────────────┐               │
│  │ 📚 开发工具      │  │ 📰 每日阅读      │               │
│  │ 收集常用的开发.. │  │ 技术文章和新闻.. │               │
│  │ 12 个链接       │  │ 8 个链接         │               │
│  └─────────────────┘  └─────────────────┘               │
│                                                         │
│  ┌─────────────────┐  ┌─────────────────┐               │
│  │ 🎨 设计灵感      │  │ 🎓 学习资源      │               │
│  │ UI/UX 设计参考.. │  │ 在线课程和教程.. │               │
│  │ 15 个链接       │  │ 20 个链接        │               │
│  └─────────────────┘  └─────────────────┘               │
│                                                         │
└─────────────────────────────────────────────────────────┘
```

---

## 🛠️ 技术架构

<table>
<tr>
<th>前端</th>
<th>后端</th>
</tr>
<tr>
<td>

- **Vue 3** + Composition API
- **Vite** 构建工具
- **Pinia** 状态管理
- **Tailwind CSS** 样式框架
- **Headless UI** 组件库

</td>
<td>

- **Go 1.23** 
- **Gin** Web 框架
- **GORM** ORM 框架
- **MySQL** + **Redis**
- **Protocol Buffers** API 定义

</td>
</tr>
</table>

### 项目结构

```
forgeturl/
├── forgeturl-server/          # 🔧 后端服务
│   ├── app/
│   │   ├── api/               # API 层 (Protobuf 定义)
│   │   ├── dal/               # 数据访问层
│   │   ├── pkg/               # 工具包
│   │   └── route/             # 路由配置
│   ├── tests/                 # 测试用例
│   └── Dockerfile
│
└── forgeturl-website/         # 🎨 前端网站
    ├── src/
    │   ├── api/               # API 接口封装
    │   ├── components/        # 公共组件
    │   ├── composables/       # 组合式函数
    │   ├── stores/            # 状态管理
    │   └── views/             # 页面视图
    └── package.json
```

---

## 🚀 快速开始

### 👉 直接使用（推荐）

无需安装任何东西，直接访问在线版本：

<p align="center">
  <a href="https://forgeturl.com" target="_blank">
    <img src="https://img.shields.io/badge/打开_ForgetURL.com-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Open ForgetURL">
  </a>
</p>

### 🔧 本地开发

如果你想在本地运行或参与开发：

<details>
<summary><b>📦 前端开发</b></summary>

```bash
cd forgeturl-website-claude-opus-4.5
npm install
npm run dev
```

访问 http://localhost:3000

</details>

<details>
<summary><b>⚙️ 后端开发</b></summary>

```bash
cd forgeturl-server/app
go mod download
cp conf/local.toml.example conf/local.toml
# 编辑 local.toml 配置数据库和 Redis
go run main.go api start
```

API 服务运行在 http://127.0.0.1:80

</details>

<details>
<summary><b>🐳 Docker 部署</b></summary>

```bash
cd forgeturl-server
docker build -t forgeturl-server .
docker run -d -p 80:80 forgeturl-server
```

</details>

---

## 📚 文档

| 文档 | 描述 |
|------|------|
| [后端 README](https://github.com/forgeturl/forgeturl-server) | 服务端详细文档 |
| [前端 README](https://github.com/forgeturl/forgeturl-website-claude-opus-4.5) | 前端详细文档 |
| [开发指南](https://github.com/forgeturl/forgeturl-website-claude-opus-4.5/blob/main/DEVELOPMENT.md) | 开发环境配置 |

---

## 🤝 贡献

我们欢迎所有形式的贡献！

- 🐛 提交 [Bug 报告](https://github.com/forgeturl/.github/issues/new?template=bug_report_zh.md)
- 💡 提出 [功能建议](https://github.com/forgeturl/.github/issues/new?template=feature_request_zh.md)
- 📝 改进文档
- 🔧 提交 Pull Request

---

## 📄 开源协议

本项目采用 [MIT License](./forgeturl-server/LICENSE) 开源协议。

---

<p align="center">
  <strong>
    <a href="https://forgeturl.com">🌐 ForgetURL.com</a>
  </strong>
  <br>
  <sub>让书签管理变得简单优雅</sub>
</p>

<p align="center">
  <a href="https://forgeturl.com">
    <img src="https://img.shields.io/badge/立即体验-ForgetURL-blue?style=flat-square" alt="Try ForgetURL">
  </a>
  <img src="https://img.shields.io/badge/Made%20with-❤️-red?style=flat-square" alt="Made with love">
</p>
