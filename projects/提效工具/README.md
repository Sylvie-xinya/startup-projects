# 提效工具清单

> 这些工具可以帮我们用 AI 提效。不花钱提效 = 赚钱。

---

## ClawTeam - 多智能体协作框架 ⭐最近很火

**数据来源**: GitHub Trending  
**仓库**: https://github.com/HKUDS/ClawTeam  
**Stars**: 4,840  
**Fork**: 661  
**语言**: Python  
**协议**: MIT

### 是什么
让多个 AI Agent 像团队一样协作的工具。

**核心理念**: Solo 🤖 → Swarm 🦞🤖🤖🤖

### 核心特性
1. **🦞 Agent 生育** - Leader Agent spawn 出多个子 Agent
2. **📋 智能任务分配** - 自动任务依赖链管理
3. **💬 Agent 间通信** - CLI 消息传递协调
4. **👀 可视化监控** - tmux 分屏 / Web UI
5. **🔄 动态适应** - 实时重新分配资源

### 支持的 Agent
Claude Code、Codex、OpenClaw、nanobot、Cursor 等任何 CLI Agent

### 三大用例
1. **🧬 AI 自动研究** - 8 Agent × 8 GPU，2430 次 ML 实验
2. **🏗️ 全栈开发** - 5 Agent 自动分工完成 Web App
3. **💰 AI 对冲基金** - 7 Agent 投资分析团队

### 怎么用
```bash
# 安装
pip install clawteam

# 启动
clawteam start

# 配置 Agent
clawteam config --add-agent claude --api-key xxx
```

### 适用场景
- 同时做多个项目
- 需要多角度研究一个问题
- 团队协作时分工

---

## n8n - 工作流自动化

**链接**: https://github.com/n8n-io/n8n  
**Stars**: 46.3k  
**语言**: TypeScript  
**协议**: Apache 2.0

### 是什么
开源的工作流自动化平台，把各种工具串起来自动跑。

### 怎么用
- 收到邮件 → 自动回复 → 记录到表格
- 社交媒体发帖 → 自动同步到多个平台
- 数据抓取 → 整理 → 发送报告
- 定时任务 → 自动执行

### 部署方式
- 云端版 (n8n.cloud)
- Docker 部署
- 自托管

### 价格
- 云端版: 有免费额度
- 自托管: 完全免费

---

## Claude Code - AI 编程

**官网**: https://claude.com/claude-code  
**是什么**: 用自然语言写代码，AI 帮你完成

### 功能
- 写代码
- 调试
- 代码审查
- 解释代码
- 重构

### 价格
- 有免费额度
- Pro 版 $20/月

---

## Cursor - AI 代码编辑器

**链接**: https://github.com/getcursor/cursor  
**官网**: https://cursor.com  
**是什么**: AI 代码编辑器，比传统 IDE 快很多

### 功能
- AI 自动补全
- 自然语言写代码
- 代码解释
- Bug 修复

### 价格
- 有免费额度
- Pro 版 $20/月

---

## OpenClaw / claw-code

**链接**: https://github.com/ultraworkers/claw-code  
**Stars**: 18k  
**是什么**: Rust 重写的 Claude Code，性能更好

---

## 其他提效工具

### Excalidraw
- **链接**: https://github.com/excalidraw/excalidraw
- **Stars**: 61.9k
- **是什么**: 手绘风格图表，可嵌入任何地方
- **用途**: 画架构图、流程图、演示文稿

### draw.io
- **链接**: https://github.com/jgraph/drawio
- **Stars**: 9.7k
- **是什么**: 在线图表工具
- **用途**: UML 图、流程图

### LanguageTool
- **链接**: https://github.com/languagetool
- **Stars**: 13.4k
- **是什么**: 语法检查工具
- **用途**: 检查英文语法错误

---

## 提效场景

### 场景1: 内容创作
1. 用 Claude 写文章大纲
2. 用 Claude 生成初稿
3. 用 Excalidraw 画配图
4. 用 n8n 自动发布到各平台

### 场景2: 开发项目
1. 用 Claude Code 写代码
2. 用 Cursor review 代码
3. 用 ClawTeam 多 Agent 协作
4. 用 GitHub 管理代码

### 场景3: 运营推广
1. 用 Claude 写营销文案
2. 用 MoneyPrinterTurbo 生成视频
3. 用 n8n 自动发布到社交媒体
4. 用数据分析工具看效果

---

*最后更新: 2026-04-19*
