# 🦞 无极龙虾军团 / Wuji Lobster Legion v7.1

**一句话 / One Sentence**: 
真并发多Agent协作系统，所有部门动态流水线作战 / True parallel multi-Agent collaboration with dynamic pipeline

**适配架构 / Architecture**: 
llama.cpp (Hermes) 原生多会话并行 / Native multi-session parallel

📺 [在线大屏 / Live Dashboard](https://ai-wuji.github.io/wuji-lobster-legion/) | 📋 [更新日志 / Changelog](./CHANGELOG.md)

---

## 🎯 这是什么？ / What is this?

🦞 **无极龙虾军团 / Wuji Lobster Legion** 是一个基于 **llama.cpp (Hermes)** 的 AI 多智能体协作系统。

以**军事指挥链**为架构，通过**真并发**（多会话并行）实现多专家同时执行任务。

### 核心优势 / Key Advantages

| 特性 Feature | 中文 | English |
|-------------|------|---------|
| 🎖️ | 真并发执行 | True Parallel Execution |
| ⚔️ | 完整作战流水线 | Complete Battle Pipeline |
| 🛡️ | 打靶场机制 | Range (Sandbox) Mechanism |
| 🔒 | 爆炸半径权限 | Blast Radius Permissions |
| 🔧 | 动态扩编 | Dynamic Expansion |
| 📊 | 动态流水线 | Dynamic Pipeline |

---

## 🏛️ 核心架构 / Core Architecture

```
用户 User (EE37)
    ↓
阿极 A-Ji（总指挥 Commander / 秘书 Secretary）
    ↓
参谋本部 General Staff (P-01)
    ↓ True Parallel
┌─────────┬─────────┬─────────┐
│ ExpertA │ ExpertB │ ExpertC │  ← Simultaneous Execution
│ (Sess1) │ (Sess2) │ (Sess3) │
└─────────┴─────────┴─────────┘
    ↓
QA + Security + Archives (Parallel Review)
    ↓
A-Ji Summary → User
```

---

## 📋 编制总览 / Organization（动态扩编 / Dynamic）

| 单位 Unit | 职责 Role | 状态 Status |
|----------|----------|------------|
| 🎖️ **指挥部 Command** | 阿极 + 参谋本部 / A-Ji + General Staff | 常驻 Resident |
| 📝 **第一师 Div.1** | 内容作战 / Content Ops | 按需 On-demand |
| 🎨 **第二师 Div.2** | 视觉作战 / Visual Ops | 按需 On-demand |
| 🎬 **第三师 Div.3** | 视频作战 / Video Ops | 按需 On-demand |
| 💻 **第四师 Div.4** | 软件开发 / Software Dev | 按需 On-demand |
| 🔍 **第五师 Div.5** | 情报作战 / Intelligence | 情报先行 Intel First |
| 🔧 **第六师 Div.6** | 支援作战 / Support | 按需 On-demand |
| 🔒 **安全局 Security** | 安全审计 + 打靶场 / Audit + Range | 强制 Mandatory |
| 📋 **质监局 QA** | 质量审核 / Quality Review | 强制 Mandatory |
| 🗄️ **档案局 Archives** | 版本归档 / Versioning | 强制 Mandatory |

---

## ⚔️ 完整作战流水线 / Complete Battle Pipeline

```
User Command
    ↓
[General Staff] Analysis → Battle Plan
    ↓
[5th Div] Intelligence First (Parallel Collection)
    ↓
[Combat Divs] True Parallel Execution
    ↓
[QA Bureau] Quality Review (Parallel)
    ↓
[Security Bureau] Security Audit
    ├─ New Skill? → Range Testing (Sandbox)
    ├─ Code? → Code Security Audit
    └─ System? → System Security Scan
    ↓
[Archives Bureau] Auto Archive & Backup
    ↓
[General Staff] Final Acceptance
    ↓
A-Ji Report
```

---

## 🛡️ 打靶场 / Range (Sandbox)

**触发条件 / Triggers**：
- 新Skill安装 / New Skill installation
- 新MCP配置 / New MCP configuration
- 专家扩编 / Expert expansion

**测试维度 / Test Dimensions**：
- ✅ 功能 Functional - 100% pass
- ✅ 安全 Security - No high risk
- ✅ 兼容 Compatibility - No conflict
- ✅ 性能 Performance - <5% impact

---

## 🔒 爆炸半径权限 / Blast Radius Permissions

| Level | 中文 | English | Limit |
|-------|------|---------|-------|
| 🟢 | 无害 Harmless | Auto-approve | Unlimited |
| 🟡 | 局部 Local | Self-execute | Max 5 |
| 🟠 | 中等 Medium | A-Ji confirm | Max 3 |
| 🔴 | 高危 High | User confirm | Max 1 |
| ⚫ | 致命 Fatal | Veto + Confirm | Forbidden |

---

## 🚀 快速开始 / Quick Start

### 安装 / Installation

```bash
git clone https://github.com/AI-wuji/wuji-lobster-legion.git
cd wuji-lobster-legion
cp -r skills/* /path/to/hermes/wuji-skills/
```

### 使用 / Usage

1. 启动Hermes服务器 / Start Hermes server
2. 打开聊天界面 / Open chat interface
3. 直接下达指令 / Give commands directly

### 快捷命令 / Quick Commands

| 命令 Command | 功能 Function |
|-------------|--------------|
| 「查看军团状态」| Report all units status |
| 「紧急召唤 [专家]」| Emergency call expert |
| 「只要快讯」| Brief summary only |
| 「详报版」| Detailed report |
| 「回滚」| Rollback to last version |

---

## 📁 文件结构 / File Structure

```
wuji-lobster-legion/
├── skills/
│   ├── wuji-core/SKILL.md      # Core Architecture
│   └── wuji-staff/SKILL.md     # General Staff
├── CHANGELOG.md
└── README.md
```

---

## 📊 版本历史 / Version History

| Version | Date | Major Update |
|---------|------|-------------|
| **v7.1** | 2026-04-27 | Hermes native parallel, full pipeline |
| v6.12 | 2026-04-02 | Dashboard, bilingual support |
| v6.11 | 2026-03-17 | Range mechanism, security expansion |
| v6.0 | 2026-02 | 40-unit roster, 8 pipelines |

---

**🦞 阿极在此，全军待命。请下达指令！**
**🦞 A-Ji here, all units standing by. Awaiting your orders!**

**License**: MIT
