# Useful Skills

A curated list of skills worth adding to Claude Code.

## Skills

| Skill | Link | Description |
|-------|------|-------------|
| Graphify | [Graphify-Labs/graphify](https://github.com/Graphify-Labs/graphify) | |
| Taste Skill | [tasteskill.dev](https://www.tasteskill.dev/) · [Leonxlnx/taste-skill](https://github.com/Leonxlnx/taste-skill) | Anti-slop frontend design rules for AI agents; adjustable dials for layout variance, motion and density |
| Impeccable | [impeccable.style](https://impeccable.style/) | Design vocabulary for agents (`/impeccable polish`, `typeset`, `distill`, `clarify`) with 61 "AI slop" detection rules |
| Mobile App UI Design | [ceorkm/mobile-app-ui-design](https://github.com/ceorkm/mobile-app-ui-design) | Mobile app UI/UX design skill: 5-step design process, industry conventions, 8-point grid, 60/30/10 color rule |

## Install

```bash
# Taste Skill (all skills, or a single one)
npx skills add Leonxlnx/taste-skill
npx skills add https://github.com/Leonxlnx/taste-skill --skill "design-taste-frontend"

# Impeccable (then run /impeccable init in the agent chat, optionally /impeccable hooks on)
npx impeccable install

# Mobile App UI Design
npx skills add ceorkm/mobile-app-ui-design
```
