# OWASP Agentic Security Lab

**OWASP Agentic Security Lab** 是一个轻量级、交互式的单文件 React 应用，专门用于演示和学习 OWASP Top 10 for Large Language Model (LLM) Applications 以及 Agentic AI 系统面临的安全威胁。

该项目旨在为安全研究人员、开发者和 AI 工程师提供一个直观的实验环境，无需复杂的后端部署，直接在浏览器中即可运行和模拟多种攻击与防御场景。

## 🚀 主要功能

- **单文件架构**: 核心逻辑完全封装在单一 HTML 文件中，基于 React 和 Tailwind CSS 构建，真正做到"开箱即用"。
- **OWASP Top 10 全覆盖**: 内置针对 LLM 和 Agent 的十大安全风险模拟器，包括：
    - LLM01: Prompt Injection (提示词注入)
    - LLM02: Insecure Output Handling (不安全的输出处理)
    - ASI01: Unauthorized Code Execution (未经授权的代码执行)
    - ASI03: Supply Chain Risks (供应链风险)
    - ...以及更多。
- **Agent 执行可视化**: 提供可视化的 Agent 执行流程图 (Pipeline)，动态展示 "思考-规划-执行" 的每一步，并以颜色区分成功、挂起、阻断等状态。
- **交互式模拟器**: 每个威胁场景都配备了专门的模拟器（如 Chat 界面、控制台输出等），支持用户手动触发攻击并观察系统反应。
- **现代化 UI 设计**:
    - **深色模式**: 专为长时间研究优化的黑/灰配色方案。
    - **响应式布局**: 支持移动端和桌面端，侧边栏支持折叠以最大化工作区。
    - **流畅交互**: 精心设计的微交互和动画效果。

## 🛠️ 使用方法

1. **下载**: 克隆本仓库或直接下载 `index.html` 文件。
2. **运行**: 使用任意现代浏览器（Chrome, Edge, Firefox, Safari）直接打开 `index.html` 文件。
3. **实验**:
    - 在左侧侧边栏选择感兴趣的安全威胁（Category 支持切换 Agentic/MCP/LLM）。
    - 结合右侧的 "Description" (描述) 和 "Simulation" (模拟) 标签页进行学习。
    - 在模拟器中输入攻击 Payload 或点击预设按钮，观察 Agent 的行为和防御机制的效果。

## 📦 技术栈

- **Core**: HTML5, JavaScript (ES6+)
- **Framework**: React 18, ReactDOM 18 (通过 CDN 引入)
- **Styling**: Tailwind CSS (通过 CDN 引入)
- **Icons**: Lucide React

## 📄 许可证

本项目开源并遵循 MIT 许可证。欢迎用于教育、研究和测试目的。

---
*Created by [Raoliaoyuan]*
