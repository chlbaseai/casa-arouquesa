# Taste-Skill Reference

## Source
- **Repository:** https://github.com/Leonxlnx/taste-skill
- **File used:** `skills/taste-skill/SKILL.md`
- **Local copy:** `taste-skill.md` (in this folder)

## What It Does
A design-focused skill for AI coding assistants that enforces premium frontend aesthetics. It overrides default LLM biases toward generic UI and pushes output toward modern, high-end design.

## Baseline Config
| Parameter | Value | Scale |
|-----------|-------|-------|
| DESIGN_VARIANCE | 8 | 1=Symmetric, 10=Artsy Chaos |
| MOTION_INTENSITY | 6 | 1=Static, 10=Cinematic |
| VISUAL_DENSITY | 4 | 1=Airy/Gallery, 10=Packed/Cockpit |

These values can be overridden per-conversation by asking Claude to adjust them.

## How to Use in Other Projects
1. Copy `taste-skill.md` into the target project's `.claude/skills/` folder
2. Reference it in that project's `CLAUDE.md` so Claude knows to apply it

## Other Available Skills (from same repo)
| Skill | Description |
|-------|-------------|
| **taste-skill** | Core design guidance (this one) |
| **redesign-skill** | Audits and improves existing designs |
| **soft-skill** | Premium aesthetic with whitespace and spring animations |
| **output-skill** | Prevents incomplete outputs and placeholder code |
| **minimalist-skill** | Editorial-style interfaces (Notion/Linear-inspired) |
| **brutalist-skill** | Swiss typography meets terminal aesthetics |
| **stitch-skill** | Google Stitch-compatible semantic design rules |
