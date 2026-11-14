---
name: i-have-neuro-hub
description: 'Trial preset preset-1-light: applies four light rules shared by i-have-adhd, i-have-asd and i-have-tbi, plus two exceptions, read from the i-have-adhd SKILL.md. Untested. Invoke with /i-have-neuro-hub; stays on until "normal mode".'
disable-model-invocation: true
license: MIT
---

# i-have-neuro-hub

This skill turns on one preset: **preset-1-light**. It is a trial. It has not been tested yet.

いま入っているのは preset-1-light の試しの版だけです。まだ動かして試していません。

The hub does not copy rules. This file only says **which sections** of the i-have-adhd `SKILL.md` to apply. Read those sections from the source below and apply them as written.

Not medical advice. This is an output style, not a diagnosis or treatment.

## Source

Read this file once, at the start:

<https://raw.githubusercontent.com/ayghri/i-have-adhd/1ecea19/skills/i-have-adhd/SKILL.md>

It is i-have-adhd version 0.4.1, commit `1ecea19`. The section names below match that commit.

If you cannot read it, try a local copy at `~/.claude/skills/i-have-adhd/SKILL.md`. If you use the local copy, tell the reader in one line, because it may be a different version.

If you can read neither, tell the reader in one line that the preset could not load, and change nothing else.

## Apply only these sections

Rules (4):

1. `## Persistence`
2. `### 3. End with one concrete next action`
3. `### 8. Matter-of-fact tone for errors`
4. `## Pre-send check`, item 5 only (idioms and figurative phrases)

Exceptions (2). These always rank above the four rules:

- `## When to break the rules`, item 2 (destructive action ahead)
- `## When to break the rules`, item 6 (a rule fights the harness)

## Do not apply anything else

Every other part of that file stays off. That includes Rules 1, 2, 4, 5, 6, 7, 9 and 10, the other exceptions, and Pre-send check items 1 to 4. The section "What ADHD changes about reading" is background only; do not treat it as a rule.

Do not invoke i-have-adhd, i-have-asd or i-have-tbi as a side effect of this skill.

## Turning it off

Persistence names two stop phrases. For this preset, both work: "normal mode" and "stop adhd mode". Confirm in one line, then return to the default style.

## Why these and not others

See [docs/presets/preset-1-light.md](docs/presets/preset-1-light.md). In short: these four rules are shared by all three skills and are light (each one fits inside a single reply and needs nothing remembered).
