# MC AI Builder

AI 驱动的 Minecraft 建筑生成器，用自然语言描述你想要的建筑，AI 帮你实现。

## ✨ 功能特点

- 🗣️ **自然语言生成** - 中英文描述都支持，说"日式神社"就能生成
- 🎨 **实时 3D 预览** - 边生成边看，所见即所得
- 🔄 **并发生成** - 同时生成多个方案，选最喜欢的
- 🖼️ **视觉模式** - 上传参考图，AI 照着建
- 📦 **多格式导出** - WorldEdit、Litematica、Axiom、数据包、单指令
- 🎮 **全版本支持** - MC 1.8 到 1.21+ 自动转换方块名

## 🚀 快速开始

### 下载使用（推荐）

1. 从 [Releases](../../releases) 下载最新版本
2. 解压后双击 `启动.bat`
3. 浏览器自动打开 `http://localhost:3001`
4. 在设置中填入你的 AI API Key
5. 开始创作！

### 从源码运行

```bash
# 克隆仓库
git clone https://github.com/你的用户名/mc-ai-builder.git
cd mc-ai-builder

# 安装依赖
npm install

# 启动开发服务器
npm run dev

# 另开一个终端，启动后端
node server.js
```

## 🔑 支持的 AI API

- OpenAI (GPT-4, GPT-4o)
- Anthropic (Claude 3.5)
- DeepSeek
- 其他兼容 OpenAI 格式的 API

## 📖 使用说明

### 快速模式（推荐）

默认就是快速模式，质量最好、速度最快，直接用就行。

### 高级模式

在全局设置里可以切换到"自定义模式"或"自主模式"，适合想深入研究的玩家。

### 导出格式

| 格式 | 用途 |
|------|------|
| WorldEdit (.schem) | 服务器使用 |
| Litematica (.litematic) | 单机投影 |
| Axiom (.bp) | Axiom 模组 |
| 数据包 | 原版命令 |
| 单指令 | 复制粘贴即用 |

## 📁 项目结构

```
mc-ai-builder/
├── src/
│   ├── components/     # React 组件
│   ├── store/          # 状态管理
│   ├── utils/          # 工具函数
│   ├── skills/         # AI 技能知识库
│   ├── versions/       # 版本更新日志
│   └── structures/     # 预设结构
├── server.js           # 后端服务
├── public/             # 静态资源
└── docs/               # 文档
```

## 🛠️ 技术栈

- **前端**: React + Vite + TailwindCSS
- **3D 渲染**: Three.js + React Three Fiber
- **状态管理**: Zustand
- **后端**: Node.js + Express

## 📜 开源协议

本项目采用 [GPL-3.0](LICENSE) 协议开源。

你可以自由使用、修改、分发本软件，但需要：
- 保留原作者信息
- 修改后的代码也必须开源
- 使用相同的 GPL-3.0 协议

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

## 📞 联系

- B站：[你的B站ID]
- QQ群：[群号]（可能会变动）

---

如果这个项目对你有帮助，欢迎 Star ⭐
