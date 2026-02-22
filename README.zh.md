[English](README.md) | [繁體中文](README.zh.md)

# playground

Create interactive single-file HTML explorers with live preview and prompt output.

## 說明

Playground Builder generates self-contained HTML files with interactive controls on one side, a live preview on the other, and a copy-ready prompt at the bottom — for visually exploring large input spaces.

## 功能特色

- Generates self-contained, zero-dependency HTML playground files
- Interactive controls panel with live preview pane
- Copy-ready prompt output at the bottom
- Three template types: design, data explorer, concept map
- Ideal for inputs that are visual, structural, or hard to express as text
- Works offline — pure HTML/CSS/JS, no server required

## 使用方式

透過以下觸發語句呼叫 Claude Code 來使用此技能：

- "make a playground"
- "interactive explorer"
- "visual tool"
- "interactive playground"

## 相關技能

- [`frontend-design`](https://github.com/joneshong-skills/frontend-design)
- [`spec-kit`](https://github.com/joneshong-skills/spec-kit)
- [`diagram-gen`](https://github.com/joneshong-skills/diagram-gen)

## 安裝

將技能目錄複製到 Claude Code 技能資料夾：

```
cp -r playground ~/.claude/skills/
```

放置在 `~/.claude/skills/` 的技能會被 Claude Code 自動發現，無需額外註冊。
