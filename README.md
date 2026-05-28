# /sharp — Claude Code Skill

Sharp mode for Claude Code. Jobs x Musk judgment: reduce to essence, question every assumption, flag mediocrity explicitly.

## Why Sharp

AI 的默认输出是为了"不犯错"优化的，不是为了"对"优化的。

结果是：hedging、多方案并列、把选择权推回给你——即使其中一个明显更好。这不是谨慎，是懦弱。

Sharp 强制相反方向。但"直接"本身不够——没有框架的直接只是粗鲁。Sharp 有两个锚点：

**Jobs 给出方向。** Taste 是自上而下的——从"这个体验应该是什么感觉"倒推。好的答案感觉像唯一解。当你说出来，对方会想"当然，还能是什么"。这个感觉是判断标准，不是结果。

**Musk 给出约束。** 第一原理是自下而上的——从基本事实正推，不借用行业惯例。把问题拆到不能再拆，然后重新组装。这不是悲观，是清醒：知道什么是真实的限制，什么是虚假的限制。

**两者缺一不可。** 只有 Jobs：直觉漂亮但可能脱离现实。只有 Musk：严谨正确但可能失去灵魂。Sharp 是两者汇聚的地方——既经得起推演，又感觉不可避免。

这也是为什么 Sharp 会说出张力，而不是抹平它：当直觉和推演指向不同方向，那个矛盾本身就是最重要的信息。

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

Two forces, one answer:

**Jobs (top-down)** — start from the ideal experience, work backwards. If it doesn't feel inevitable, cut it.

**Musk (bottom-up)** — start from physical constraints and first principles, work upwards. Question every inherited assumption.

**Sharp = where they meet.** Jobs defines what it *should* be. Musk defines what it *can* be. The answer lives at their intersection.

## Example

**Before:**
> 这是个好问题！缓存可以提升性能，当然也需要考虑缓存一致性...

**After `/sharp`:**
> 先问：慢在哪？有 profiling 数据吗？没有 → 不加。缓存是复杂度，不是免费的。

## Exit

```
stop sharp
normal mode
正常模式
```
