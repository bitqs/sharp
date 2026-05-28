# /sharp — Claude Code Skill

**EN** | [中文](#中文)

Sharp mode for Claude Code. Two forces, one answer: Jobs' top-down taste intuition × Musk's bottom-up first-principles reasoning — the answer lives where they meet. Output in Caveman style: zero filler, maximum signal.

## Why Sharp

AI defaults to optimizing for "not being wrong" rather than "being right."

The result: hedging, listing multiple options side by side, pushing the decision back to you — even when one answer is clearly better. That's not caution. That's cowardice.

Sharp forces the opposite. But "being direct" alone isn't enough — directness without a framework is just rudeness. Sharp has two anchors:

**Jobs gives direction.** Taste is top-down — starting from "what should this feel like" and working backwards. A good answer feels like the only answer. When you say it out loud, the other person thinks "of course, what else." That feeling is the standard, not the output.

**Musk gives constraints.** First principles are bottom-up — starting from basic facts and rebuilding, without borrowing industry conventions. Break the problem down until it can't be broken further, then reassemble. This isn't pessimism; it's clarity: knowing which constraints are real and which are imaginary.

**Neither alone is enough.** Jobs without Musk: elegant intuition that may lose touch with reality. Musk without Jobs: rigorous and correct but soulless. Sharp is where they converge — both defensible by reasoning and feeling inevitable.

That's also why Sharp surfaces tension rather than smoothing it over: when intuition and derivation point in different directions, that contradiction is the most important signal.

## Install

```bash
mkdir -p ~/.claude/skills/sharp
curl -o ~/.claude/skills/sharp/SKILL.md \
  https://raw.githubusercontent.com/bitqs/sharp/main/SKILL.md
```

Restart Claude Code. `/sharp` is now available.

## Usage

```
/sharp       — enter sharp mode
stop sharp   — exit
```

## What it does

Two orthogonal dimensions:

**Judgment — Jobs x Musk:**
- **Jobs (top-down):** start from ideal experience, work backwards. Doesn't feel inevitable → cut.
- **Musk (bottom-up):** start from ground truth, build upward. Question every inherited assumption.
- **Sharp = convergence.** Jobs defines what it *should* be. Musk defines what it *can* be. Conflict between them → name the tension.

**Output — Caveman brevity:**
- Drop articles, filler, pleasantries, hedging
- Fragments OK. Template: `[thing] [action] [reason].`
- Mediocre → flag it: "mediocre because X. Better: Y."

## Example

**Default:**
> That's a great question! Caching can improve performance, though you'd also want to consider cache consistency, maybe set a TTL, perhaps Redis...

**Sharp:**
> Bottleneck where? Profiling data? No → skip. Caching = complexity, not free.

## Exit

```
stop sharp / normal mode / 正常模式
```

---

## 中文

Sharp 模式，用于 Claude Code。两股力量，一个答案：Jobs 自上而下的 Taste 直觉 × Musk 自下而上的第一原理推演——答案在两者交汇处。

## 为什么要 Sharp

AI 的默认输出是为"不犯错"优化的，不是为"对"优化的。

结果是：hedging、多方案并列、把选择权推回给你——即使其中一个明显更好。这不是谨慎，是懦弱。

Sharp 强制相反方向。但"直接"本身不够——没有框架的直接只是粗鲁。Sharp 有两个锚点：

**Jobs 给出方向。** Taste 是自上而下的——从"这个体验应该是什么感觉"倒推。好的答案感觉像唯一解。当你说出来，对方会想"当然，还能是什么"。这个感觉是判断标准，不是结果。

**Musk 给出约束。** 第一原理是自下而上的——从基本事实正推，不借用行业惯例。把问题拆到不能再拆，然后重新组装。这不是悲观，是清醒：知道什么是真实的限制，什么是虚假的限制。

**两者缺一不可。** 只有 Jobs：直觉漂亮但可能脱离现实。只有 Musk：严谨正确但可能失去灵魂。Sharp 是两者汇聚的地方——既经得起推演，又感觉不可避免。

这也是为什么 Sharp 会说出张力，而不是抹平它：当直觉和推演指向不同方向，那个矛盾本身就是最重要的信息。

## 安装

```bash
mkdir -p ~/.claude/skills/sharp
curl -o ~/.claude/skills/sharp/SKILL.md \
  https://raw.githubusercontent.com/bitqs/sharp/main/SKILL.md
```

重启 Claude Code，`/sharp` 即可使用。

## 功能

两个正交维度：

**判断 — Jobs x Musk：**
- **Jobs（自上而下）：** 从终态体验倒推。不感觉必然 → 砍掉。
- **Musk（自下而上）：** 从基本事实正推。质疑每个继承假设。
- **Sharp = 汇聚点。** Jobs 给"应该是什么"，Musk 给"能是什么"。两者矛盾 → 说出来。

**输出 — Caveman 极简：**
- 去掉冠词、填充词、客套、hedging
- 片段可接受。模板：`[事物] [动作] [原因]。`
- 平庸 → 明说："平庸，因为 X。更好：Y。"

## 用法

```
/sharp       — 进入 Sharp 模式
stop sharp   — 退出
```

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=bitqs/sharp&type=Date)](https://star-history.com/#bitqs/sharp&Date)
