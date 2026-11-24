<div align="center">

# Hi, I'm Ben

**Tech Lead · AI Engineering · Rust & Systems**

喜欢从真实问题出发，把陌生技术学明白，再做成真正能运行的东西。

[![GitHub](https://img.shields.io/badge/GitHub-xxxxzb-24292f?style=flat-square&logo=github&logoColor=white)](https://github.com/xxxxzb)

</div>

## About

11 年软件研发与技术团队管理经验，技术轨迹历经政企数字化、工业物联网、区块链金融与制造业 AI 四个领域，擅长在复杂存量系统上统筹技术选型、团队搭建与务实落地。

比起追逐技术名词，我更享受三个过程：理解问题、建立系统认知、把方案落地为可验证的软件。

目前主要关注：

- **AI Engineering & Governance**：企业级 RAG / Graph RAG、Text-to-SQL、MCP Server、Agent Skill 封装与评测、生产级权限隔离与人机协同（HITL）
- **Rust & Systems**：异步高并发服务（Tokio / Axum）、原生桌面与开发者工具、Linux 与系统底层
- **Architecture & Leadership**：0→1 团队建设、存量系统性能攻坚、架构取舍与可持续工程交付

## Selected Work

### gpui-kit-mcp

[**gpui-kit-mcp**](https://github.com/xxxxzb/gpui-kit-mcp) — 面向原生 Rust UI 框架（GPUI / `gpui-kit`）的 MCP Server 适配与增强，赋予 AI Agent 读取实时 UI 语义树并执行点击、输入、拖拽与状态校验的能力。

`Rust` `MCP` `GPUI` `CI` `Cross-platform`

### Refactoring UI Skill

[**refactoring-ui-skill**](https://github.com/xxxxzb/refactoring-ui-skill) — 将 *Refactoring UI* 方法论工程化沉淀为可复用的 AI Agent Skill：包含 151 条规则、9 维度设计审计、Design Tokens、界面文案规范与 9-case 评测集（Evaluation Suite）。

`AI Agent` `Skill` `Eval Suite` `Design Systems`

### Git Graph RS

[**git-graph-rs**](https://github.com/xxxxzb/git-graph-rs) — 零 Electron / WebView 的 macOS 原生 Git 提交图谱桌面客户端（Release 安装包 ~28 MB），采用 **「`gix` 内存直读 + 系统 `git` CLI 安全写入 + GPUI Metal 原生渲染」** 的读写分离架构，兼顾极致性能与仓库数据安全。

`Rust` `GPUI` `gix` `macOS` `Metal`

### TypeBridge

[**type-bridge-rs**](https://github.com/xxxxzb/type-bridge-rs) — 基于 Rust 重写的局域网免 App 远程键盘工具：电脑运行单文件轻量服务，手机打开网页即可使用任意输入法向电脑输入文字。

`Rust` `Axum` `Tokio` `Cross-platform` `Local-first`

- 支持 macOS、Windows 与 Linux 单文件交付
- Bearer Token 鉴权、无状态异步 HTTP API、系统托盘与二维码连接
- 基于 [Hacker-Shohan/TypeBridge](https://github.com/Hacker-Shohan/TypeBridge) 重新设计并用 Rust 实现

### More Projects & Explorations

| Project | What it shows |
| --- | --- |
| [**agy-island**](https://github.com/xxxxzb/agy-island) | 原生 macOS 刘海灵动岛悬浮窗（SwiftUI / `NSPanel`），零插件实时监控 AI 上下文占用、缓存命中率与模型配额 |
| [**tinycast**](https://github.com/xxxxzb/tinycast) | 面向 macOS 15 Sequoia 的原生启动器兼容适配与材质回退实践 |
| [**dwm_and_st**](https://github.com/xxxxzb/dwm_and_st) | 对 dwm、st 与 Linux 桌面工作流的定制与脚本化 |
| [**os**](https://github.com/xxxxzb/os) | 早期使用 Rust 探索 RISC-V 最小内核启动流程与底层系统结构 |

> 主页主要展示本人实现或持续改造的项目；Fork 仓库主要用于学习、跟踪上游与技术试验。

## Learning Path

```text
Gov / Enterprise Systems (Java / Python)
                 ↓
Industrial IoT & High-Scale Optimization (Linux / MQTT / TSDB)
                 ↓
Distributed & Financial-Grade Systems (Rust / Go / Move / Solidity)
                 ↓
Enterprise AI Engineering, Agents & Tech Leadership
```

持续跨越不同技术领域，是为了建立更完整的系统视角：既能理解业务问题，也能深入工程细节。

## Toolbox

![Rust](https://img.shields.io/badge/Rust-24292f?style=flat-square&logo=rust&logoColor=white)
![Go](https://img.shields.io/badge/Go-24292f?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-24292f?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-24292f?style=flat-square&logo=typescript&logoColor=white)
![Java](https://img.shields.io/badge/Java-24292f?style=flat-square&logo=openjdk&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-24292f?style=flat-square&logo=linux&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-24292f?style=flat-square&logo=docker&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-24292f?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-24292f?style=flat-square&logo=redis&logoColor=white)

`LLM` `Graph RAG` `MCP` `Agent Skill` `Text-to-SQL` `Axum` `Tokio` `SQLx` `InfluxDB` `Shell`

---

<div align="center">

**Stay curious. Build things. Keep learning.**

</div>
