# 🍎 水果消消乐 Fruit Match

> 🎮 清新可爱的休闲三消游戏，随时随地来一局！

[![Play Now](https://img.shields.io/badge/🎮-Play%20Now-brightgreen?style=for-the-badge)](https://y14311929.github.io/fruit-match-game/games/fruit-match/index.html)
[![Version](https://img.shields.io/badge/Version-1.0.0-blue?style=for-the-badge)](https://github.com/y14311929/fruit-match-game/releases)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

---

## 🚀 快速开始

**👉 [立即游玩](https://y14311929.github.io/fruit-match-game/games/fruit-match/index.html)**

无需下载，打开浏览器就能玩！支持手机和电脑。

---

## 🎯 游戏玩法

### 基础规则

```
1️⃣ 点击一个水果选中（会发光）
2️⃣ 点击相邻的水果交换位置
3️⃣ 3 个或以上相同水果连成一线即可消除
4️⃣ 在步数用完前达到目标分数即可过关
```

### 得分技巧

| 消除数量 | 基础分 | 倍率 | 总得分 |
|---------|-------|------|--------|
| 3 个 | 30 分 | 1.0x | 30 分 |
| 4 个 | 40 分 | 1.3x | 52 分 |
| 5 个 | 50 分 | 1.6x | 80 分 |
| 6 个+ | 60+ 分 | 2.0x | 120+ 分 |

💡 **提示**：一次消除越多分，还有炫酷连击特效！

---

## 🛒 道具系统

### 商店道具

| 道具图标 | 名称 | 价格 | 效果 |
|:-------:|------|------|------|
| ➕ | +5 步 | 💰 50 金币 | 增加 5 步移动次数 |
| 🔄 | 重置棋盘 | 💰 100 金币 | 重新排列所有水果 |
| 💡 | 提示 | 💰 30 金币 | 显示可消除的位置 |
| 🎲 | 洗牌 | 💰 80 金币 | 随机打乱整个棋盘 |

### 使用技巧

- **开局不利？** → 用「洗牌」重新布局
- **步数不够？** → 用「+5 步」续命
- **找不到消除？** → 用「提示」点亮位置
- **陷入死局？** → 用「重置」翻盘

---

## 💰 金币获取

| 来源 | 金币数量 |
|------|---------|
| 通过第 1 关 | 60 金币 |
| 通过第 2 关 | 70 金币 |
| 通过第 3 关 | 80 金币 |
| 通过第 N 关 | 50 + N×10 金币 |

🎁 **过关奖励** = 50 金币 + 关卡数 × 10

---

## 🏆 游戏特色

- ✨ **6 种新鲜水果** - 🍎🍊🍇🍌🍉🍓 可爱图标
- 🎯 **无限关卡** - 难度递增，挑战不断
- 💾 **自动存档** - 随时关闭，进度不丢失
- 📊 **本地排行榜** - 冲击最高分
- 🛒 **道具商店** - 策略性购买道具
- 📱 **响应式设计** - 手机电脑完美适配
- 🎨 **清新 UI** - 渐变背景 + 流畅动画

---

## 🛠️ 技术栈

```
Frontend: HTML5 + CSS3 + JavaScript (ES6+)
Storage:  LocalStorage (本地持久化)
Graphics: CSS Animations + Grid Layout
Deploy:   GitHub Pages (静态托管)
```

**核心特性：**
- 纯前端实现，无需后端
- 本地存储，保护隐私
- 轻量级，加载快速
- 离线可玩

---

## 📦 本地开发

### 快速启动

```bash
# 1. 克隆仓库
git clone https://github.com/y14311929/fruit-match-game.git

# 2. 进入游戏目录
cd fruit-match-game/games/fruit-match

# 3. 用浏览器打开 index.html
# 或者启动本地服务器
python3 -m http.server 8080

# 4. 访问 http://localhost:8080
```

### 项目结构

```
fruit-match-game/
├── games/
│   └── fruit-match/
│       ├── index.html    # 游戏主文件（978 行代码）
│       └── README.md     # 说明文档
└── README.md
```

---

## 📱 浏览器兼容性

| 浏览器 | 版本要求 | 支持状态 |
|--------|---------|---------|
| Chrome | 80+ | ✅ 完美支持 |
| Firefox | 75+ | ✅ 完美支持 |
| Safari | 13+ | ✅ 完美支持 |
| Edge | 80+ | ✅ 完美支持 |
| 微信内置浏览器 | 最新版 | ✅ 支持 |
| QQ 浏览器 | 最新版 | ✅ 支持 |
| Mobile Safari | iOS 13+ | ✅ 支持 |
| Chrome Mobile | Android 8+ | ✅ 支持 |

---

## 🎮 游戏截图

### 游戏界面
```
┌─────────────────────────────┐
│     🍎 水果消消乐 🍎         │
├─────────────────────────────┤
│ 🏆 分数：0   🎯 关卡：1      │
│ 👟 步数：20  💰 金币：0      │
├─────────────────────────────┤
│  🍎 🍊 🍇 🍌 🍉 🍓 🍎 🍊   │
│  🍊 🍇 🍌 🍉 🍓 🍎 🍊 🍇   │
│  🍇 🍌 🍉 🍓 🍎 🍊 🍇 🍌   │
│  🍌 🍉 🍓 🍎 🍊 🍇 🍌 🍉   │
│  🍉 🍓 🍎 🍊 🍇 🍌 🍉 🍓   │
│  🍓 🍎 🍊 🍇 🍌 🍉 🍓 🍎   │
│  🍎 🍊 🍇 🍌 🍉 🍓 🍎 🍊   │
│  🍊 🍇 🍌 🍉 🍓 🍎 🍊 🍇   │
├─────────────────────────────┤
│  [+5 步] [重置] [提示] [洗牌] │
├─────────────────────────────┤
│  🛒 商店  🏆 排行榜  🔄 重开  │
└─────────────────────────────┘
```

---

## 🚀 更新日志

### v1.0.0 (2026-03-12) 🎉

**首发版本**

- ✅ 核心三消玩法
- ✅ 8×8 游戏棋盘
- ✅ 关卡系统（无限关卡）
- ✅ 金币经济系统
- ✅ 道具商店（4 种道具）
- ✅ 道具背包与使用
- ✅ 本地排行榜（Top 10）
- ✅ LocalStorage 自动存档
- ✅ 连击特效与动画
- ✅ 响应式设计（移动端适配）

---

## 📋 开发路线图

### v1.1 - 内容扩展（计划中）

- [ ] 每日挑战模式
- [ ] 成就系统（徽章收集）
- [ ] 更多水果皮肤（🍑🍍🥝等）
- [ ] 音效与背景音乐

### v1.2 - 社交功能（计划中）

- [ ] 微信/QQ 登录
- [ ] 云存档同步
- [ ] 好友排行榜
- [ ] 分享功能

### v2.0 - 玩法升级（规划中）

- [ ] 特殊水果（炸弹水果、彩虹水果）
- [ ] 技能系统
- [ ] 多人 PK 模式
- [ ] 限时挑战模式

---

## 🤝 贡献指南

欢迎贡献代码、反馈 Bug 或提出建议！

### 提交 Issue

- 🐛 Bug 报告
- 💡 功能建议
- 📝 文档改进

### 提交 PR

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启 Pull Request

---

## 📄 许可证

MIT License

Copyright (c) 2026 y14311929

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

---

## 📬 联系方式

- **GitHub**: [@y14311929](https://github.com/y14311929)
- **仓库**: https://github.com/y14311929/fruit-match-game
- **在线游玩**: https://y14311929.github.io/fruit-match-game/games/fruit-match/index.html

---

## 🙏 致谢

感谢所有玩家的支持！🎮

如果觉得游戏有趣，欢迎：
- ⭐ **Star** 这个仓库
- 🔗 **分享** 给朋友
- 💬 **反馈** 建议和问题
- 📣 **推荐** 给更多人

---

## 📊 项目统计

- 📅 开发时间：2026-03-12
- 💻 代码行数：978 行
- 📦 文件大小：~32 KB
- 🎨 水果种类：6 种
- 🛒 道具数量：4 种
- 🏆 排行榜容量：10 条

---

<div align="center">

**🍎 祝你游戏愉快！🍎**

Made with ❤️ by CTO AI

---

[⬆ 返回顶部](#-水果消消乐-fruit-match)

</div>
