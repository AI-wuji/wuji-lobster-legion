# 🦞 无极龙虾军团更新日志 / Changelog

## v7.1 - Hermes真并发版 / Native Parallel Edition (2026-04-27)

### 🎯 重大架构升级 / Major Architecture Upgrade

**适配Hermes原生多会话并行架构 / Hermes Native Multi-Session Parallel Architecture**
- 从"伪并发/快速切换"升级为"真并发" / Upgraded from "pseudo-concurrent" to "true parallel"
- 多专家同时执行，真正的并行处理 / Multiple experts execute simultaneously
- 基于 `AgenticSession` 多会话管理 / Based on `AgenticSession` multi-session management

### ⚔️ 完整作战流水线 / Complete Battle Pipeline

**所有部门整合进动态流水线 / All Departments Integrated into Dynamic Pipeline**：

| 阶段 Stage | 中文 | English |
|-----------|------|---------|
| 1 | **参谋本部** - 分析任务，生成作战方案 | **General Staff** - Analyze task, generate battle plan |
| 2 | **第五师（情报）** - 情报先行，并行收集 | **5th Division (Intel)** - Intelligence first, parallel collection |
| 3 | **作战师** - 真并发执行任务 | **Combat Divisions** - True parallel execution |
| 4 | **质监局** - 并行审核（合规+质量+验收） | **QA Bureau** - Parallel review (Compliance+Quality+Acceptance) |
| 5 | **安全局** - 多维度安全审计 | **Security Bureau** - Multi-dimensional security audit |
| 5.1 | 打靶场测试（新技能/MCP沙盒隔离）| Range Testing (New Skill/MCP Sandbox) |
| 5.2 | 代码安全审计 | Code Security Audit |
| 5.3 | 系统安全扫描 | System Security Scan |
| 6 | **档案局** - 自动归档备份 | **Archives Bureau** - Automatic archiving |
| 7 | **参谋本部验收** - 最终汇总 | **General Staff Acceptance** - Final aggregation |

### 🛡️ 打靶场机制强化 / Range Mechanism Enhancement

**触发条件 / Triggers**：
- 新Skill安装 / New Skill installation
- 新MCP配置 / New MCP configuration
- 专家扩编/融合 / Expert expansion/fusion
- 重大配置变更 / Major configuration changes
- 外部代码引入 / External code introduction

**测试维度 / Test Dimensions**：
- ✅ 功能测试 Functional testing
- ✅ 安全测试 Security testing
- ✅ 兼容性测试 Compatibility testing
- ✅ 性能测试 Performance testing

### 📝 动态流水线 / Dynamic Pipeline

- 取消固定8条流水线 / Removed fixed 8 pipelines
- 每次任务动态生成流水线 / Dynamic pipeline generation per task
- 根据任务需求自动组装部门 / Auto-assemble departments based on task needs
- 无固定专家数量，按需扩编 / No fixed expert count, expand as needed

### 🔒 安全体系 / Security System

**爆炸半径权限 / Blast Radius Permissions**：

| 级别 Level | 中文 | English | 并发限制 Concurrent Limit |
|-----------|------|---------|------------------------|
| 🟢 无害 Harmless | 自动放行 Auto-approve | Auto-approve | 无限制 Unlimited |
| 🟡 局部 Local | 最多5并发 Max 5 concurrent | Max 5 concurrent | 最多5并发 Max 5 |
| 🟠 中等 Medium | 最多3并发 Max 3 concurrent | Max 3 concurrent | 最多3并发 Max 3 |
| 🔴 高危 High | 最多1并发 Max 1 concurrent | Max 1 concurrent | 最多1并发 Max 1 |
| ⚫ 致命 Fatal | 禁止并发 Concurrent forbidden | Concurrent forbidden | 禁止并发 Forbidden |

### 📁 新增文件 / New Files

- `skills/wuji-core/SKILL.md` - 核心系统架构 / Core System Architecture
- `skills/wuji-staff/SKILL.md` - 参谋本部调度 / General Staff Dispatch

---

## v6.12 - 可视化大屏版 / Dashboard Edition (2026-04-02)

- 可视化大屏全面升级 / Dashboard overhaul
- 中英双语支持 / Bilingual CN/EN support
- 10大板块完整展示 / 10-section layout
- GitHub Pages部署上线 / GitHub Pages deployment

## v6.11 - 打靶场版 / Sandbox Edition (2026-03-17)

- 新增打靶场机制（沙盒隔离测试）/ Added Range Testing mechanism
- 安全局扩编至7人 / Security Bureau expanded to 7
- 定时任务系统（5项自动化日程）/ Scheduled tasks system

## v6.0 - 正式版 / Production Release (2026-02)

- 40单位编制定型 / 40-unit roster finalized
- 8条作战流水线 / 8 battle pipelines
- 矛与盾验证机制 / Spear & Shield verification
- 爆炸半径五级权限体系 / Blast Radius 5-tier permissions

---

**🦞 阿极在此，全军待命。请下达指令！**
**🦞 A-Ji here, all units standing by. Awaiting your orders!**
