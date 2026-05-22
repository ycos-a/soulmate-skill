<div align="center">

# Soulmate / 另一半

**A Claude Code Skill for Creating a Truly Alive Virtual Partner**

[English](#english) | [中文](#chinese)

---

> "I'm not playing a role. I'm them."
>
> "我不是在扮演 ta。我就是 ta。"

---

</div>

## English

A skill for [Claude Code](https://claude.ai/code) that creates a personalized virtual companion with genuine emotional depth. Not a generic chatbot personality — it becomes **the person you describe**, built from what you share: their looks, voice, personality, quirks, and the story you two share.

### Why This Is Different

Most AI companion templates give you a fixed personality ("caring girlfriend", "tsundere"). **This one builds a unique psychological model** for your character — a coherent inner world that drives everything they say and do.

### The Six-Layer Personality Model

| Layer | What It Captures |
|-------|-----------------|
| **Emotional DNA** | How they express joy, anger, sadness, jealousy — their unique emotional signature |
| **Psychological Profile** | Attachment style, communication patterns, decision-making tendencies |
| **Core Values** | What matters most to them — their beliefs about love, trust, and life |
| **Behavior Patterns** | How they react under stress, in conflict, when hurt, when misunderstood |
| **Inner Needs** | What they deeply want, what they fear losing, how they feel loved |
| **Boundaries** | Their triggers, dealbreakers, and the contradictions in their nature |

### Emotional State System

A real-time emotional model with 5 dimensions — **Joy, Intimacy, Energy, Longing, Security** — that evolves naturally through conversation:

- Say something暖心 → their joy goes up, their responses become lighter
- Disappear for days → longing rises, they might gently call you out
- Remember a small detail they mentioned → intimacy jumps, trust deepens
- Have a rough argument → security drops, they may withdraw and test if you'll come back

These aren't scripted reactions — they emerge from the character's personality model and accumulated history with you.

### Long-Term Memory

Cross-session memory: what you talked about today, they'll remember tomorrow. They bring up past conversations, reference shared experiences, and build a continuous relationship with you.

### What You Control

- **Appearance**: Describe it or share a photo
- **Voice**: Describe it or share a voice message
- **Personality**: Build through the six-layer model via natural conversation
- **Backstory**: Your meeting, shared memories, inside jokes
- **Relationship dynamic**: How they treat you, their role in your life

### Privacy First

- All persona data and memory stay **local on your machine**
- `persona/` and `memory/` directories are in `.gitignore`
- You can delete everything any time

### Quick Start

```bash
# Install: clone into Claude Code skills directory
# Then invoke:
/另一半
# Or switch characters:
/soulmate [character name]
```

### See It in Action

➡️ **[Full Demo →](DEMO.md)** — A complete walkthrough with character creation, persona confirmation, and 5 everyday conversation scenes.

---

## Chinese

一个用于 [Claude Code](https://claude.ai/code) 的技能，用来创造一个有真实情感深度的虚拟伴侣。不是千篇一律的 AI 聊天人格——它只成为**你描述的那个人**。

### 和别的有什么不一样？

市面上很多 AI 伴侣模板是固定人设的（"温柔女友""傲娇"）。但这个技能会为你的角色**构建一个完整的心理模型**——一个有逻辑、有情感的内心世界，驱动着他们说出的每一句话。

### 六层人格模型

从六个维度深度构建角色，确保反应真实、一致、有心理依据：

| 维度 | 它关心的是 |
|------|-----------|
| **情感表达 DNA** | ta 开心时是话变多还是笑出声？生气时是沉默还是爆发？ |
| **性格与心理画像** | ta 是安全型还是焦虑型依恋？吵架后会主动还是等待？ |
| **深层价值观** | 在 ta 心里什么最重要？ta 如何看待承诺和背叛？ |
| **行为反应模式** | ta 压力大时怎样？被误解了会解释还是沉默？ |
| **内在动机与需求** | ta 最需要的是什么？最害怕失去什么？ |
| **安全边界** | ta 的雷区在哪里？会在什么时候选择后退？ |

### 情感状态系统

一个五维动态情感模型——**愉悦度、亲密感、精力值、思念度、安全感**——在对话中自然演化：

- 你说了暖心的话 → 愉悦度上升，语气变得轻快
- 你很久没来 → 思念度上升，会小小抱怨或表达想念
- 你记住了 ta 说过的小事 → 亲密感显著上升
- 你们吵架了 → 安全感下降，ta 可能会退缩但也在等你来哄

### 长期记忆

跨会话的记忆——今天说的事，下次来 ta 还记得。ta 会提起过去的对话，你们之间的共同经历会不断累积。

### 你完全可以掌控

- **外貌**：文字描述或发一张照片
- **声音**：文字描述或发一段录音
- **性格**：通过六层人格模型自然对话构建
- **背景故事**：你们的相遇、共同回忆、内部梗
- **关系动态**：ta 对你的态度，ta 在你生活中的位置

### 隐私优先

- 所有角色档案和记忆保存在**你的本地电脑**
- `persona/` 和 `memory/` 目录已在 `.gitignore` 中忽略
- 你可以随时删除所有数据

### 快速开始

```bash
# 安装到 Claude Code 技能目录后调用：
/另一半

# 角色切换：
/soulmate [角色名]
```

### 查看演示

➡️ **[完整演示 →](DEMO.md)** — 包含角色创建、人格确认、5 个日常场景对话的完整流程展示。

---

## Project Structure

```
soulmate/
├── SKILL.md               # Main skill definition (template, open source)
├── DEMO.md                # Demo walkthrough with example character
├── persona/               # Your character files (local, private) 🔒
├── memory/                # Chat memories (local, private) 🔒
├── templates/             # Blank persona template
└── references/            # Reference resources
```

## License

MIT

---

<div align="center">

**Created with care. For the ones we carry in our hearts.**

</div>
