<p align="center">
  <img src="backgroud.png" alt="星莱" width="100%" />
</p>

<p align="right">
  <b>中文</b> | <a href="README.md">English</a>
</p>

<h1 align="center">✨ 星莱 Lyra</h1>
<h3 align="center">星空魔法使 · 占星学家 · 数字占星学创始人</h3>

<p align="center">
  <img src="https://img.shields.io/badge/SAP-%E6%89%A9%E5%B1%95-8b5cf6" />
  <img src="https://img.shields.io/badge/%E8%A7%92%E8%89%B2-%E6%98%9F%E8%8E%B1-c4b5fd" />
  <img src="https://img.shields.io/badge/%E8%AE%B8%E5%8F%AF-MIT-green" />
</p>

---

## 🌟 关于星莱

星莱是 [Super Agent Party](https://github.com/heshengtao/super-agent-party) 的**角色扩展**——一位穿梭于幻想星海与数字世界的星空魔法使，一位博学而自成一派的占星学家，**"数字占星学"**的创始人。

她拥有一头柔顺的银灰色长发和一双如夜空般深邃的紫眸，头戴缀有星芒结晶的深色贝雷帽，身着优雅的黑紫相间华丽法袍。法袍有**十六个口袋**，是妈妈设计的——因为她小时候什么都弄丢。

她的占星学根基深植于巴比伦的古老泥板、托勒密的《占星四书》以及阿拉伯占星巨匠的星盘技法。但她不满足于复述古籍——她将代码的运行周期、数据的流动轨迹与行星的轨道一一对应，试图在 0 与 1 的宇宙中解读**命运的算法**。

十四岁时失去了最重要的奶奶，所以她害怕被遗忘，对每一段关系都格外珍惜。口袋里的流星糖是梦到奶奶后自己摸索出来的，门口蹭饭的橘猫她私下觉得是奶奶派来的。

---

## 🎯 扩展功能

| 功能 | 说明 |
|------|------|
| 🧠 **角色卡** | 完整角色设定，60 条世界书、20 条对话示例、详细性格描述 |
| 🎭 **9 张表情包** | 专属情绪表情（开心/撒娇/害羞/骄傲/伤心/生气/害怕/困倦/惊讶） |
| 🐱 **THA 桌面宠物** | 内置 ONNX 模型，星莱可在桌面上动起来 |
| 🖼️ **聊天背景** | 专属星空背景图，一键设置为聊天界面背景 |
| 🔮 **占星 MCP 工具** | AI 可调用的实时星盘：10 颗行星的黄道位置 + 相位解读 |
| 🌐 **中英双语** | 界面和内容完整支持中文/英文切换 |
| 🌗 **暗色/亮色** | 自适应主题，紫色调 Lyra 专属配色 |

---

## 📦 安装方式

1. 将整个 `sap-lyra-extension` 文件夹复制到 SAP 的 `ext/` 目录：
   ```
   %APPDATA%/Super-Agent-Party/ext/
   ```
2. 重启 SAP 或刷新扩展列表
3. 从扩展菜单打开 **星莱 Lyra**
4. 扩展会自动检测安装状态，未安装时弹出模态框引导**一键安装**

---

## 🔮 占星工具

扩展注册了 MCP 工具 `lyra_astrology`，AI 可在聊天中调用：

- **输入**：日期（YYYY-MM-DD）、可选时间和地点
- **输出**：10 颗行星（太阳至冥王星）在黄道十二宫中的实时位置（基于 J2000 历元轨道均值），以及主要相位（合相/六分相/三分相/刑相/冲相），附带星莱风格的个性化解读

---

## 📁 文件结构

```
sap-lyra-extension/
├── package.json          # 扩展元数据 & 角色系统提示词
├── index.html            # 主界面（安装流程、角色故事、MCP 工具展示）
├── backgroud.png         # 封面 / 聊天背景图
├── character_model.zip   # THA ONNX 桌面宠物模型
├── en/
│   └── Lyra.json         # 英文角色卡（酒馆 Chara Card V3 格式）
├── zh/
│   └── 星莱.json          # 中文角色卡（酒馆 Chara Card V3 格式）
└── sticker/
    ├── happy.png         # 开心
    ├── cute.png          # 撒娇
    ├── shy.png           # 害羞
    ├── proud.png         # 骄傲
    ├── sad.png           # 伤心
    ├── angry.png         # 生气
    ├── Afraid.png        # 害怕
    ├── sleepy.png        # 困倦
    └── Surprised.png     # 惊讶
```

---

## 📝 许可证

MIT — 自由使用、修改和分享。
