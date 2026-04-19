# 内容自动化项目

> 用 AI 批量生产内容，通过 YouTube、广告、联盟变现。

---

## MoneyPrinterTurbo - AI 短视频生成

**数据来源**: GitHub 热门项目  
**原项目**: https://github.com/harry0703/MoneyPrinterTurbo  
**Stars**: 56k（爆发式增长）  
**语言**: Python  
**协议**: MIT

### 是什么
利用 AI 大模型，一键生成高清短视频的工具。

输入一个主题 → AI 自动生成：
1. **文案脚本** - 自动编写短视频文案
2. **配音** - TTS 语音合成
3. **画面** - AI 生成配图/视频素材
4. **字幕** - 自动生成字幕
5. **背景音乐** - 可选配乐

### 支持的 AI 模型
- GPT (OpenAI)
- Gemini
- Claude
- 多种 TTS 提供商

---

## 变现方式

### 1. YouTube 广告分成（最推荐）
- 发布到 YouTube Shorts
- 靠广告分成赚钱
- 一个视频 2-3 分钟，适合批量跑量

### 2. TikTok 矩阵
- 批量生产短视频
- 引流到独立站或联盟链接
- 矩阵打法（多账号）

### 3. 工具站变现
- 搭一个 Web 界面
- 别人可以用这个工具生成视频
- 付费生成或订阅

### 4. 卖教程
- 教别人怎么用 MoneyPrinterTurbo
- 搭建自己的自动化流水线
- 付费课程

---

## 快速开始

### 本地部署

```bash
# Clone 项目
git clone https://github.com/harry0703/MoneyPrinterTurbo.git
cd MoneyPrinterTurbo

# 安装依赖
pip install -r requirements.txt

# 配置 API key（需要 OpenAI 或 Gemini）

# 运行
python main.py
```

### Web UI 部署

```bash
# 进入 webui 目录
cd webui

# 安装依赖
pip install -r requirements.txt

# 运行
python app.py
```

### Docker 部署

```bash
# 构建
docker build -t money-printer-turbo .

# 运行
docker run -p 8080:8080 money-printer-turbo
```

---

## 具体操作步骤

### 第1步：本地体验
1. Clone 项目到本地
2. 配置好 API key
3. 跑一个视频试试效果

### 第2步：确定方向
- YouTube 短视频（娱乐/科技/教育）
- TikTok 内容
- 帮人定制视频

### 第3步：批量生产
1. 收集热门话题
2. 批量生成视频
3. 批量发布

### 第4步：扩大规模
1. 多账号矩阵
2. 不同领域内容
3. 优化变现

---

## SEO 关键词
- AI short video generator
- YouTube shorts automation
- AI video creation tool
- text to video AI

---

## 预计投入
- 域名: $10-15/年（如果做工具站）
- 主机: 可以本地跑，也可以云服务器
- API 费用: TTS + 图像生成（按量付费）

---

## 下一步
- [ ] 本地部署体验
- [ ] 确定主要方向（油管 vs TikTok）
- [ ] 批量生成测试视频
- [ ] 建立发布流水线

---

## 其他内容自动化工具

### 视频生成
- Runway
- Pika Labs
- Sora
- Stable Video

### 音频处理
- ElevenLabs（语音克隆）
- Suno（音乐生成）
- Murf（配音）

### 工作流自动化
- n8n（连接各种工具）

---

*最后更新: 2026-04-19*
