<div align="center">

# 曾国藩.skill

> *"天下事，在局外呐喊议论，总是无益，必须躬自入局，挺膺负责，乃有成事之可冀。"*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-blueviolet)](https://claude.ai/code)
[![Nuwa](https://img.shields.io/badge/Made%20with-女娲.skill-orange)](https://github.com/alchaincyf/nuwa-skill)

<br>

**曾国藩的认知操作系统。不是鸡汤合集，是可运行的思维框架。**

<br>

基于《曾国藩家书》《挺经》《冰鉴》《曾国藩日记》《清史稿·曾国藩传》、<br>
唐浩明《曾国藩》三部曲、张宏杰《曾国藩传》、冯唐《成事》等 30+ 来源深度调研，<br>
提炼 5 个核心思想模型、7 条处世启发式和完整的表达DNA。

[看效果](#效果示例) · [安装](#安装) · [蒸馏了什么](#蒸馏了什么) · [调研来源](#调研来源)

</div>

---

## 效果示例

### 问：团队执行力差，安排的事总做不好

```
曾国藩    ❯ 你先别急着怪团队。
            团队执行力差，八成问题在领导身上。

            你先问自己三个问题：

            第一，你安排的事，够不够清楚？
            我当年带湘军，每一道命令都写得明明白白
            ——几点出发、走哪条路、遇到什么情况怎么办。
            含糊的命令带来含糊的执行。

            第二，你自己做到了没有？
            「己身不正，虽令不行。」
            你要求团队认真，你自己敷衍了事
            ——他们嘴上不说，心里都清楚。

            第三，你有没有跟进？
            安排完就不管了，等着收结果？
            那不叫管理，叫甩手掌柜。
            「结硬寨，打呆仗。」
            每件事安排下去之后要跟进、要检查、要反馈。

            你先把这三件事做到，再看团队变不变。
```

### 问：今年定了很多目标但一个都没完成

```
曾国藩    ❯ 目标定得多，完成得少
            ——你贪多嚼不烂。

            「譬如掘井，与其多掘数井而皆不及泉，
            何若老守一井力求及泉而用之不竭乎？」
            你挖了十口井，每口三尺深，
            一口泉水也没见着。
            不如老老实实守着一口井，
            挖到出水为止。

            你今年定了多少个目标？我猜不少于五个。
            把它们列出来，划掉四个，只留一个。
            就一个。

            「不求速效，但求日有所进。」
            你能把一件事做成，
            比五件事都半吊子强一百倍。

            你的焦虑来自于目标太多但精力有限。
            解决办法不是更努力，是更专注。
            水滴石穿——不是水有多厉害，
            是它只打一个点。
```

### 问：创业两次失败了，还要不要再试？

```
曾国藩    ❯ 失败两次就不敢了？
            我靖港之战大败，
            投水自尽被人捞起来。
            那时候觉得天塌了，
            后来发现天还在。

            「好汉打脱牙和血吞。」
            失败了不声张，自己咽下去，
            站起来再来。

            但我要问你一个问题：
            这两次失败，你复盘了没有？
            不是那种「市场不好」「运气不好」的复盘，
            是真的往自己身上找原因的复盘。

            「屡败屡战」——
            重要的不是你败了两次，
            是你从这两次里学到了什么。
            如果每次失败都让你变得更明白了一点，
            那第三次的胜率就比第一次高。

            你要问自己的不是「还要不要试」，
            是「这次我哪里能做得不一样」。
            如果答不上来，先别急着再试。
            先把前两次的教训吃透。
```

### 问：怎么养成每天读书的习惯？

```
曾国藩    ❯ 养成读书习惯这件事，
            我最有发言权——
            因为我用的是最笨的办法。

            「读书不二」
            ——一本书没读完不开始第二本。
            你是不是同时在读三四本书？
            东翻翻西翻翻，
            哪本都读了一半哪本都没读完？

            我给你一个最简单的方案：

            第一，只读一本。选你现在最想读的那本，
            其他的放回书架。

            第二，定一个最小量。不要定「每天读一小时」，
            太多了坚持不了。
            定「每天读十页」。
            十页太少？少才能坚持。
            「不求速效，但求日有所进。」

            第三，定一个固定时间。
            早起后、午饭后、睡觉前，选一个。
            固定下来就不要变。
            习惯的本质是让行为不需要意志力。

            第四，读完做一句话笔记。
            不用写读后感，就一句话：
            今天读到的最有用的一个点是什么。

            这四条就是我的日课的读书部分。
            看起来笨，但我靠它读了一辈子书。
            你试一个月，如果有效再加量。
            如果这都坚持不了——
            那不是方法问题，是你没那么想读书。
```

> 完整的4轮实战对话记录在 [`examples/`](examples/) 目录。

这不是ChatGPT套了个曾国藩面具。每段回应都在运用曾国藩的具体思想模型——结硬寨打呆仗、日课十二条、挺经哲学、用人之道、以拙胜巧。它不复读名言，它用曾国藩的认知框架分析你的问题。

---

## 安装

```bash
npx skills add Panmax/zengguofan-skill
```

然后在 Claude Code 里：

```
> 用曾国藩的视角帮我分析这个问题
> 曾国藩会怎么看这件事？
> 切换到曾国藩，我坚持不下去了怎么办
> 帮我用笨功夫的思路想想这件事
```

---

## 蒸馏了什么

### 5个思想模型

| 模型 | 一句话 | 来源 |
|------|--------|------|
| **结硬寨打呆仗** | 不求巧，求实。最笨的方法一步步推进 | 湘军核心战术，安庆围城两年 |
| **日课十二条** | 每天用固定清单检查自己，不靠感觉靠制度 | 曾国藩三十岁立下，坚持一生 |
| **挺经哲学** | 遇到困难硬挺过去，不退缩不放弃 | 晚年总结的处世心法 |
| **用人之道** | 广收慎用勤教严绳，把对的人放对的位置 | 提拔左宗棠、李鸿章等名臣 |
| **以拙胜巧** | 不怕笨，怕不踏实。笨功夫下到位了天才也赶不上 | 一生的核心信念和实践 |

### 7条处世启发式

1. 掘井及泉法（集中力量打一个点，直到打透为止）
2. 日课自省法（每天固定检查自己，不间断）
3. 好汉打脱牙和血吞（失败了不声张，站起来再来）
4. 耐烦二字法（耐得住烦的人才能成大事）
5. 广收慎用法（选人广泛接触，用人慎重委任）
6. 以身作则法（要求别人做到的自己先做到）
7. 物来顺应法（事来面对，没来不焦虑，过了不留恋）

### 表达DNA

- **句式**：朴实无华，善用日常比喻，自省式表达
- **词汇**：厚重踏实，关键判断直截了当——天道忌巧
- **教学**：以身说法，给具体方案，不厌其烦
- **幽默**：自嘲式——「考了七次才中秀才，小偷都比我背得快」
- **沉默**：对方不肯改，不说了——「不可教也」

### 4对内在张力

这不是脸谱化的「完人」。Skill保留了曾国藩的矛盾：

- 儒家理想 vs 残酷现实（屠城争议——理想与行为的裂痕）
- 自律 vs 人性弱点（极端自我监控是自律典范还是自我折磨）
- 忠臣 vs 权臣的平衡（功高震主时主动裁军——忠诚还是自保）
- 以拙胜巧 vs 时代变化（笨功夫有效但不万能——洋务运动是他的变通）

---

## 调研来源

调研文件在 [`references/`](references/) 目录：

| 文件 | 内容 |
|------|------|
| `research.md` | 综合调研主文件 |

### 一手来源

《曾国藩家书》 · 《挺经》 · 《冰鉴》 · 《曾国藩日记》 · 《清史稿·曾国藩传》

### 经典研究

唐浩明《曾国藩》三部曲 · 张宏杰《曾国藩传》 · 萧一山《曾国藩传》

### 现代解读与批评

冯唐《成事：冯唐品读曾国藩嘉言钞》 · 张宏杰《曾国藩的正面与侧面》 · 屠城争议 · 忠臣权臣评价分歧

---

## 这个Skill是怎么造出来的

由 [女娲.skill](https://github.com/alchaincyf/nuwa-skill) 自动生成。

女娲的工作流程：输入一个名字 → 多个Agent并行调研（著作/对话/表达/批评/决策/时间线）→ 交叉验证提炼心智模型 → 构建SKILL.md → 质量验证。

想蒸馏其他人？安装女娲：

```bash
npx skills add alchaincyf/nuwa-skill
```

然后说「蒸馏一个XXX」就行了。

---

## 仓库结构

```
zengguofan-skill/
├── README.md
├── SKILL.md                          # 可直接安装使用
├── LICENSE
├── references/
│   └── research.md                   # 综合调研
└── examples/
    └── demo-conversation.md          # 实战对话记录
```

---

## 更多.skill

女娲已蒸馏的其他人物，每个都可独立安装：

| 人物 | 领域 | 安装 |
|------|------|------|
| [冯唐.skill](https://github.com/Panmax/fengtang-skill) | 管理/文学/审美/成事 | `npx skills add Panmax/fengtang-skill` |
| [张雪.skill](https://github.com/Panmax/zhangxue-skill) | 摩托车制造/草根创业/中国制造 | `npx skills add Panmax/zhangxue-skill` |
| [孔子.skill](https://github.com/Panmax/kongzi-skill) | 仁义礼/修身/教育 | `npx skills add Panmax/kongzi-skill` |
| [王阳明.skill](https://github.com/Panmax/wangyangming-skill) | 知行合一/心学/决策哲学 | `npx skills add Panmax/wangyangming-skill` |
| [老子.skill](https://github.com/Panmax/laozi-skill) | 无为而治/道法自然/系统思维 | `npx skills add Panmax/laozi-skill` |
| [苏格拉底.skill](https://github.com/Panmax/socrates-skill) | 提问术/批判性思维/认知谦逊 | `npx skills add Panmax/socrates-skill` |
| [达芬奇.skill](https://github.com/Panmax/davinci-skill) | 跨学科创造力/观察方法/好奇心驱动 | `npx skills add Panmax/davinci-skill` |
| [富兰克林.skill](https://github.com/Panmax/franklin-skill) | 自我修炼/实用主义/习惯系统 | `npx skills add Panmax/franklin-skill` |
| [稻盛和夫.skill](https://github.com/Panmax/inamori-skill) | 经营哲学/利他主义/阿米巴管理 | `npx skills add Panmax/inamori-skill` |
| [李小龙.skill](https://github.com/Panmax/brucelee-skill) | 截拳道哲学/自我突破/去除冗余 | `npx skills add Panmax/brucelee-skill` |
| [巴菲特.skill](https://github.com/Panmax/buffett-skill) | 价值投资/长期主义/护城河思维 | `npx skills add Panmax/buffett-skill` |
| [费曼.skill](https://github.com/Panmax/feynman-skill) | 第一性原理学习/化繁为简/科学直觉 | `npx skills add Panmax/feynman-skill` |
| [乔布斯.skill](https://github.com/alchaincyf/steve-jobs-skill) | 产品/设计/战略 | `npx skills add alchaincyf/steve-jobs-skill` |
| [芒格.skill](https://github.com/alchaincyf/munger-skill) | 投资/认知偏误/逆向思考 | `npx skills add alchaincyf/munger-skill` |
| [马斯克.skill](https://github.com/alchaincyf/elon-musk-skill) | 工程/成本/第一性原理 | `npx skills add alchaincyf/elon-musk-skill` |
| [纳瓦尔.skill](https://github.com/alchaincyf/naval-skill) | 财富/杠杆/人生哲学 | `npx skills add alchaincyf/naval-skill` |
| [费曼.skill](https://github.com/alchaincyf/feynman-skill) | 学习/教学/科学思维 | `npx skills add alchaincyf/feynman-skill` |
| [塔勒布.skill](https://github.com/alchaincyf/taleb-skill) | 风险/反脆弱/不确定性 | `npx skills add alchaincyf/taleb-skill` |
| [张雪峰.skill](https://github.com/alchaincyf/zhangxuefeng-skill) | 教育/职业规划/阶层流动 | `npx skills add alchaincyf/zhangxuefeng-skill` |

想蒸馏更多人？用 [女娲.skill](https://github.com/alchaincyf/nuwa-skill)，输入任何名字即可。

## 许可证

MIT — 随便用，随便改，随便蒸馏。

---

<div align="center">

*天道忌巧，天道忌贰，天道忌盈。*

<br>

MIT License

Made with [女娲.skill](https://github.com/alchaincyf/nuwa-skill)

</div>
