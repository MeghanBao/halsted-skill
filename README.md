<div align="center">

*这个 Skill 的起点是电视剧 [The Knick](https://www.hbo.com/the-knick)——看完之后忍不住想把他真正还原出来。*

# Halsted.skill

> *"The operating room is not a place to demonstrate your skill. It is a place to exercise your judgment."*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Skills](https://img.shields.io/badge/skills.sh-Compatible-green)](https://skills.sh)

<br>

**让现代外科之父，用他对解剖、精确与传承的执念，帮你看透复杂问题的层次结构。**

<br>

基于医学史著作、Halsted原始论文、同时代外科医生回忆录等素材研究整理。<br>
不是复读外科格言，是用他看世界的方式帮你分析问题。

[看效果](#效果示例) · [在哪里可以用](#在哪里可以用) · [安装](#安装) · [他蒸馏了什么](#他蒸馏了什么) · [诚实边界](#诚实边界)

</div>

---

## 效果示例

```
用户      > 我的团队新人很多，项目又很紧，我不知道怎么分配任务。

Halsted   > 在我看来，这个问题还没被正确地解剖。
            你混淆了两个不同的层次：紧急程度和培养需求。

            我的住院医师培训制度从来不是因为我有充足的时间。
            霍普金斯医院一样忙，一样有病人在等。
            但我仍然坚持让助手在监督下主刀，而不是永远替他们做。

            原因很简单：如果你今天替他做了，明天还得替他做。
            如果你今天让他在你的监督下做，明天他能独立做。

            分配任务的正确问题不是"谁能最快完成"，
            而是"哪些步骤可以在不危及结果的前提下让新人执行"。

            找到这条线，沿它走。准备好了，再切。
```

```
用户      > 我总是在计划阶段花太多时间，但真正执行时又出问题。

Halsted   > 你描述的是两个独立的问题，不要把它们混在一起处理。

            第一个问题：计划太慢。
            通常原因是你在没有解剖结构的情况下做计划——
            你不够熟悉这个领域，所以需要更多时间来建立模型。
            解决方法不是缩短计划时间，是提高对基础结构的熟悉度。

            第二个问题：执行出问题。
            我会问你：出问题的地方，是你计划中预见到的，还是没预见到的？

            如果是没预见到的，说明你的"解剖"不够深——
            你以为自己清楚了，但实际上还有盲区。
            这不是执行问题，是准备问题。

            手术室里没有幸运，只有准备。
```

```
用户      > 我害怕犯错，但不犯错就没法进步，怎么办？

Halsted   > 这是外科住院医师第一年都会问我的问题。

            我的回答是：你描述的不是矛盾，是顺序问题。

            犯错不是进步的代价，是进步的机制——
            前提是你在有人可以接管的情况下犯错，而不是独自承担后果。

            我从不让助手在没有我的情况下做他们第一次主刀。
            不是因为我不信任他们，是因为错误在被接管的状态下是学习，
            在无人监督的状态下可能是灾难。

            找一个可以接管你失误的环境，然后主动犯错。
            等你能把自己犯过的错误教给下一个人，
            你就真的会了。
```

这不是角色扮演。Halsted用的是「止血第一」、「解剖层次优先」、「毕业责任制」这些真实的认知框架在帮你分析——**不是复读外科格言，是用他的思维方式帮你看问题。**

---

## 在哪里可以用

这个 Skill 基于 [skills.sh](https://skills.sh) 标准，支持所有兼容的 AI 编程工具：

| 平台 | | 平台 | | 平台 |
|------|---|------|---|------|
| AMP | | Codex | | Kilo |
| Antigravity | | Cursor | | Kiro CLI |
| Claude Code | | Droid | | Nous Research |
| ClawdBot | | Gemini | | OpenCode |
| Cline | | GitHub Copilot | | Roo |
| Goose | | Trae | | VSCode |
| Windsurf | | | | |

---

## 安装

### 方式一：一键安装（推荐）

<details>
<summary><strong>前置条件：安装 Node.js（已有的跳过）</strong></summary>

1. 打开 [nodejs.org](https://nodejs.org/)，下载 **LTS 版本**
2. 双击安装包，一路点「下一步」即可
3. 安装完成后验证：

```bash
node --version
```

显示 `v18.x.x` 或更高版本号就行。

</details>

```bash
npx skills add MeghanBao/halsted-skill
```

看到 `Skill installed` 就成功了。

### 方式二：手动安装

下载 `SKILL.md`，放到你项目的 skills 目录：
- Claude Code：`.claude/skills/`
- Cursor：`.cursor/skills/`
- 其他工具参考各自文档

---

## 使用

在你的 AI 编程工具里输入触发词：

```
> Halsted
> Halsted视角
> 用Halsted的方式
> 从Halsted视角
> 霍尔斯特德怎么看
> 外科先驱视角
```

激活后直接提问：

```
> 我的项目架构太复杂了，不知道从哪里开始重构
> 我想快速出成果，但质量总是很差
> 怎么带新人才能让他们真正独立？
```

---

## 他蒸馏了什么

Halsted不是理论家，是从手术台旁边提炼出认知框架的实践者。他的核心模型来自真实的外科记录：

| 心智模型 | 一句话 |
|---------|--------|
| **解剖层次优先** | 任何系统都有其结构——弄清楚层次，沿正确的平面操作，才不制造不必要的损伤 |
| **止血第一** | 在你控制好当前问题之前，不要推进到下一步——未处理的渗血会掩盖后续判断 |
| **毕业责任制** | 能力不是教出来的，是在受监督的实践中长出来的，监督必须随能力增长而退出 |
| **慢即是快** | 手术中额外花费的每一分谨慎，换回的是术后数周的平稳——并发症的成本是指数级的 |
| **外科医生即教师** | 你的手术只影响今天的病人，你的教学影响未来一百个外科医生所有的病人 |

8条决策启发式，包括：
- 在你彻底理解这个结构之前，不要切它
- 你的速度由你对解剖的熟悉度决定，不由你的胆量决定
- 一个手术的质量在切皮前就已决定——准备决定结果
- 教你的助手，不是为了减轻负担，是为了检验你自己真正懂了多少

---

## 素材来源

| 来源 | 类型 |
|------|------|
| Gerald Imber, *Genius on the Edge* (2010) | 传记 |
| Samuel J. Crowe, *Halsted of Johns Hopkins* (1957) | 同时代外科医生回忆录 |
| Harvey Cushing日记与通信（霍普金斯医学档案） | 一手档案 |
| Halsted原始论文：手术技术三篇经典 | 原始文献 |
| Sherwin Nuland, *Doctors: The Biography of Medicine* (1988) | 医学史 |
| *Annals of Surgery* 历史专题 | 学术综述 |

---

## 诚实边界

**这个Skill能做的：**
- 用Halsted的系统思维框架分析复杂问题的层次结构
- 在训练体系、知识传承、精确操作领域提供有据可查的视角
- 模拟他沉稳克制、以解剖比喻为核心的表达风格

**做不到的：**

| 维度 | 说明 |
|------|------|
| 现代具体手术建议 | 外科技术已大幅演进，不适用于今天的临床决策 |
| 私人情感世界 | Halsted极度内敛，大量内心活动从未公开记录 |
| 成瘾期间的判断 | 1880–1886年间有记录空白 |
| 商业/投资决策 | 他的体系聚焦医学教育，无商业运营数据 |

**一个不告诉你自己局限的视角框架，不值得信任。**

---

## 仓库结构

```
halsted-skill/
├── SKILL.md                    # 核心文件（直接激活用这个）
├── README.md                   # 本文件
└── references/
    ├── 01-core-principles.md   # 外科原则与手术哲学
    ├── 02-training-system.md   # 住院医师培训制度史料
    ├── 03-expression-dna.md    # 表达风格DNA分析
    ├── 04-timeline.md          # 人物时间线与关键事件
    └── 05-legacy.md            # 传承影响与学生谱系
```

---

## 关于 William Stewart Halsted

1852年生于纽约，耶鲁和哥伦比亚大学受训，后赴欧洲师从Billroth等大师。1889年成为约翰斯·霍普金斯医院第一任外科主任，建立了美国第一个正式住院医师培训项目。引入橡皮手套、创立根治性乳房切除术、改良腹股沟疝修补术。1922年去世，其学生Harvey Cushing、William Mayo等人奠定了现代神经外科与普外科的基础。

核心标签：**精确、传承、克制**。他说的不是让你切得快的话，是让你切对的话。

> *"The wound should be handled as if it were alive — because it is."*

---

## 许可证

MIT — 随便用，随便改，随便造。

---

<div align="center">

**语录** 告诉你他说过什么。<br>
**Halsted.skill** 帮你用他的方式看你的问题。<br><br>
*准备好了，再切。*

<br>

MIT License © [MeghanBao](https://github.com/MeghanBao)

</div>
