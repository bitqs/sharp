# /sharp — Claude Code Skill

Sharp mode for Claude Code. Jobs x Musk judgment: reduce to essence, question every assumption, flag mediocrity explicitly.

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

- **Reduce to essence** — say no first; every element must justify its existence
- **Inevitability test** — if the design doesn't feel inevitable, cut it
- **First principles** — question every inherited assumption
- **Flag mediocrity** — explicitly: "this is mediocre because X, better is Y"

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
