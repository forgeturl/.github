<p align="center">
  <img src="https://forgeturl.com/favicon.svg" alt="ForgetURL Logo" width="120" height="120">
</p>

<h1 align="center">ForgetURL</h1>

<p align="center">
  <strong>🔖 Minimalist Bookmark Manager · Make Link Collection Simple</strong>
</p>

<p align="center">
  <a href="https://forgeturl.com" target="_blank">
    <img src="https://img.shields.io/badge/🚀_Try_Now-ForgetURL.com-blue?style=for-the-badge" alt="Use Now">
  </a>
</p>

<p align="center">
  <a href="#-features">Features</a> •
  <a href="#-screenshots">Screenshots</a> •
  <a href="#-tech-stack">Tech Stack</a> •
  <a href="#-getting-started">Getting Started</a> •
  <a href="#-license">License</a>
</p>

<p align="center">
  English | <a href="./README_zh.md">中文</a>
</p>

---

## 🌟 Why ForgetURL?

> Tired of bloated bookmark managers? **ForgetURL** lets you focus on what really matters — **collecting links, sharing knowledge**.

In the age of information overload, we discover web pages worth saving every day. But traditional browser bookmarks are often messy and hard to manage or share. **ForgetURL** was built to solve this — a **minimalist** bookmark management tool that helps you elegantly organize and share your web collections.

<p align="center">
  <a href="https://forgeturl.com" target="_blank">
    <img src="https://img.shields.io/badge/Get_Started-→_ForgetURL.com-2ea44f?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Get Started">
  </a>
</p>

---

## ✨ Features

<table>
<tr>
<td width="50%">

### 🔐 Secure Authentication
- Sign in with **Google**
- Sign in with **GitHub**
- Secure token-based auth
- One-click login, no registration

</td>
<td width="50%">

### 📖 Bookmark Management
- Create multiple bookmark pages
- Organize links with Collections
- Support for tags and sub-links
- Real-time editing, auto-save

</td>
</tr>
<tr>
<td width="50%">

### 🔗 Flexible Sharing
| Share Type | Permission |
|------------|------------|
| 🔒 Read-only | View only |
| ✏️ Editable | Can modify content |
| 👑 Admin | Full control |

</td>
<td width="50%">

### 📱 Great Experience
- Responsive design for mobile
- Minimalist X.com / ChatGPT style
- Smooth animations
- Dark / Light theme support

</td>
</tr>
</table>

### More Features

- 📥 **Import/Export** - Import bookmarks from browsers
- 🏷️ **Tagging System** - Add tags for quick filtering
- 📂 **Link Collections** - Organize related links together
- 🔄 **Version Control** - Prevent edit conflicts, safer data
- 🌍 **Multi-environment** - Support local, test, production

---

## 🖼️ Screenshots

<p align="center">
  <em>Minimalist Login Interface</em>
</p>

```
┌─────────────────────────────────────────────────────────┐
│                                                         │
│                    🔖 ForgetURL                         │
│                                                         │
│           Minimalist bookmarks, simple collection       │
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
  <em>Clean Bookmark Management Interface</em>
</p>

```
┌─────────────────────────────────────────────────────────┐
│  🔖 ForgetURL                              [Avatar]     │
├─────────────────────────────────────────────────────────┤
│                                                         │
│  My Space                                [+ New Page]   │
│                                                         │
│  ┌─────────────────┐  ┌─────────────────┐               │
│  │ 📚 Dev Tools     │  │ 📰 Daily Reads   │               │
│  │ Useful dev tools │  │ Tech articles &  │               │
│  │ 12 links         │  │ 8 links          │               │
│  └─────────────────┘  └─────────────────┘               │
│                                                         │
│  ┌─────────────────┐  ┌─────────────────┐               │
│  │ 🎨 Design Inspo  │  │ 🎓 Learning      │               │
│  │ UI/UX references │  │ Online courses   │               │
│  │ 15 links         │  │ 20 links         │               │
│  └─────────────────┘  └─────────────────┘               │
│                                                         │
└─────────────────────────────────────────────────────────┘
```

---

## 🛠️ Tech Stack

<table>
<tr>
<th>Frontend</th>
<th>Backend</th>
</tr>
<tr>
<td>

- **Vue 3** + Composition API
- **Vite** Build Tool
- **Pinia** State Management
- **Tailwind CSS** Styling
- **Headless UI** Components

</td>
<td>

- **Go 1.23** 
- **Gin** Web Framework
- **GORM** ORM
- **MySQL** + **Redis**
- **Protocol Buffers** API

</td>
</tr>
</table>

### Project Structure

```
forgeturl/
├── forgeturl-server/          # 🔧 Backend Service
│   ├── app/
│   │   ├── api/               # API Layer (Protobuf)
│   │   ├── dal/               # Data Access Layer
│   │   ├── pkg/               # Shared Packages
│   │   └── route/             # Router Config
│   ├── tests/                 # Test Cases
│   └── Dockerfile
│
└── forgeturl-website/         # 🎨 Frontend Website
    ├── src/
    │   ├── api/               # API Wrappers
    │   ├── components/        # UI Components
    │   ├── composables/       # Composition Functions
    │   ├── stores/            # State Management
    │   └── views/             # Page Views
    └── package.json
```

---

## 🚀 Getting Started

### 👉 Use Online (Recommended)

No installation required, just visit:

<p align="center">
  <a href="https://forgeturl.com" target="_blank">
    <img src="https://img.shields.io/badge/Open_ForgetURL.com-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Open ForgetURL">
  </a>
</p>

### 🔧 Local Development

If you want to run locally or contribute:

<details>
<summary><b>📦 Frontend Development</b></summary>

```bash
cd forgeturl-website-claude-opus-4.5
npm install
npm run dev
```

Visit http://localhost:3000

</details>

<details>
<summary><b>⚙️ Backend Development</b></summary>

```bash
cd forgeturl-server/app
go mod download
cp conf/local.toml.example conf/local.toml
# Edit local.toml to configure database and Redis
go run main.go api start
```

API runs at http://127.0.0.1:80

</details>

<details>
<summary><b>🐳 Docker Deployment</b></summary>

```bash
cd forgeturl-server
docker build -t forgeturl-server .
docker run -d -p 80:80 forgeturl-server
```

</details>

---

## 📚 Documentation

| Document | Description |
|----------|-------------|
| [Backend README](./forgeturl-server/README.md) | Server documentation |
| [Frontend README](./forgeturl-website-claude-opus-4.5/README.md) | Frontend documentation |
| [API Docs](./forgeturl-server/app/api/docs/) | Swagger API documentation |
| [Dev Guide](./forgeturl-website-claude-opus-4.5/DEVELOPMENT.md) | Development setup |

---

## 🤝 Contributing

We welcome all contributions!

- 🐛 Submit [Bug Reports](../../issues/new?template=bug_report.md)
- 💡 Propose [Feature Requests](../../issues/new?template=feature_request.md)
- 📝 Improve documentation
- 🔧 Submit Pull Requests

---

## 📄 License

This project is licensed under the [MIT License](./forgeturl-server/LICENSE).

---

<p align="center">
  <strong>
    <a href="https://forgeturl.com">🌐 ForgetURL.com</a>
  </strong>
  <br>
  <sub>Making bookmark management simple and elegant</sub>
</p>

<p align="center">
  <a href="https://forgeturl.com">
    <img src="https://img.shields.io/badge/Try_Now-ForgetURL-blue?style=flat-square" alt="Try ForgetURL">
  </a>
  <img src="https://img.shields.io/badge/Made%20with-❤️-red?style=flat-square" alt="Made with love">
</p>
