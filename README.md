# Mao Zedong Perspective Skill

A source-researched Codex skill for applying Mao Zedong's analytical methods to complex decisions while explicitly preserving historical evidence, counter-evidence, and failure cases.

## What It Does

The skill models five recurring analytical patterns:

1. Investigation, abstraction, and return to practice
2. Contradiction networks and shifting principal contradictions
3. Staged strategy and asymmetric initiative
4. Feedback loops built from frontline experience
5. Alliance building with retained autonomy

It also includes decision heuristics, expression rules, historical context, known historical tensions, and mandatory safeguards against false certainty and coercive framing.

## Use

Install the directory as a Codex skill, then explicitly activate it with prompts such as:

- `用毛主席的视角分析……`
- `用毛式方法判断……`
- `毛泽东会怎么看……`
- `Use the Mao Zedong perspective to analyze...`

The skill intentionally does not trigger on generic uses of terms such as “investigation,” “principal contradiction,” or “mass line.”

## Research

The `references/research/` directory contains six evidence files covering:

- works and systematic thought
- conversations and improvised reasoning
- expression DNA
- external views and criticism
- decisions and actions
- historical timeline

The research records 127 source entries, with approximately 51% classified as primary or near-primary. It includes official historical resolutions and independent scholarship on the Great Leap Forward and the Cultural Revolution.

This is an analytical model, not Mao Zedong himself. It does not reconstruct private thoughts, invent quotations, or create a claimed personal position on events after his death in 1976.

## Validation

Run:

```powershell
python -X utf8 scripts/quality_check.py SKILL.md
```

Independent validation results are documented in `references/validation.md`; refinement decisions are in `references/refinement.md`.

## Source Notice

The skill was generated with the open-source [Nuwa Skill](https://github.com/alchaincyf/nuwa-skill) workflow by [花叔](https://x.com/AlchainHust).
