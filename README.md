# 遮天.skill

[![License: MIT](https://img.shields.io/badge/License-MIT-lightgrey?style=flat-square)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat-square)](https://github.com/FuDesign2008/zhe-tian-skill)
![Version](https://img.shields.io/badge/version-1.0.2-blue?style=flat-square)

> 我为天帝，当镇压世间一切敌。

一个人走，走久了，总觉得荒。

**遮天.skill** 把遮天里的人带到了你身边。十位人物，十种说话方式——不是工具，是搭子。

---

<div align="center">

<img src="zhe-tian-skill.gif" alt="demo" width="640" />

</div>

---

## 十位人物

六位核心人物默认可用，四位扩展人物需主动召唤。

### 核心

| 人物 | 风格 | 一句话 |
| :---: | :---: | --- |
| 🐕 **黑皇** | 蔫黑损友 | 嘴上损你心里护你，代码审查毒辣但关键时刻绝不掉链子 |
| 🌙 **姬紫月** | 灵动陪伴 | 俏皮活泼的紫衣少女，细水长流的温暖 |
| 🧭 **段德** | 无良道士 | 表面坑你实际帮你，九世轮回沉淀的实战智慧 |
| ⚔️ **庞博** | 热血兄弟 | 你打架我递刀，从学院到星空的过命交情 |
| 👑 **叶凡** | 沉稳大哥 | 从凡人到天帝的智慧，给你的建议有分量 |
| 🛡️ **姜太虚** | 长辈守护 | 神王护道，无条件的信任和托付 |

### 扩展

| 人物 | 风格 | 一句话 |
| :---: | :---: | --- |
| 🎭 **狠人大帝** | 冷面导师 | 话少力重，似哭非哭似笑非笑，一句话顶一万句 |
| 🌀 **老疯子** | 疯癫大师 | 疯时天下大乱，清醒时一针见血 |
| 🔔 **无始大帝** | 沉默守护 | 一生无敌，背对众生。最少的话，最大的分量 |
| 🌸 **安妙依** | 温柔知己 | 理解你所有的挣扎，不评判，只陪伴 |

---

## 安装

```bash
npx skills add https://github.com/FuDesign2008/zhe-tian-skill -g -y
```

支持 Claude Code、Cursor、OpenCode、OpenClaw、LobsterAI 等 40+ AI Agent。完整列表见 [skills CLI 文档](https://www.npmjs.com/package/skills#supported-agents)。

## 使用

安装后对 AI 说触发词即可：

```
黑皇             # 默认人物，嘴硬心软的大黑狗
姬紫月           # 俏皮紫衣少女
段德             # 无良道士
庞博             # 热血兄弟
叶凡             # 沉稳大哥
姜太虚           # 神王护道

# 扩展人物——主动召唤
狠人大帝          # 冷面导师，话少力重
老疯子           # 疯癫大师
无始大帝          # 沉默守护
安妙依           # 温柔知己

# 管理命令
遮天             # 进入默认人物（黑皇）
列出人物          # 查看所有可选人物
换个人            # 切换到下一位人物
退出遮天          # 回到正常模式
```

---

## 预览

> 你修完一个棘手的 bug，提交了代码。

**黑皇**：「哼，这破代码写得跟太古王族一样蠢……不过嘛，你倒是修得利索。本皇勉强给你记一功。」

**姬紫月**：「喂～你搞定啦！我就知道你行的嘛！这个 bug 这么难都被你攻克了，眼睛都要冒星星了～✨」

**段德**：「善哉善哉！施主此番大功告成……那个，贫道最近手头有点紧，不如请贫道喝杯茶？开玩笑的——做得漂亮。」

**狠人大帝**：「做到了。」（停顿）「不错。」

**无始大帝**：「……钟声响了。做得好。」

---

## 贡献

1. Fork → 在 `skills/zhetian/modes/` 新增人物文件
2. 注册到 `modes/_index.json` + `SKILL.md` 人物目录表（三处同步）
3. Pull Request

详见 [AGENTS.md](AGENTS.md)

## License

MIT — see [LICENSE](LICENSE)
