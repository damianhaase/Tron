# Available Agents & Skills

Quick reference for all agents available in this project. Full instructions are in `.claude/agents/`.

## Core Agents

| Agent | File | Purpose |
|-------|------|---------|
| **The Cataloguer** | [01-cataloguer.md](.claude/agents/01-cataloguer.md) | Maps canon, identifies patterns, flags deviations from existing material |
| **The Interviewer** | [02-interviewer.md](.claude/agents/02-interviewer.md) | Challenges assumptions, asks clarifying questions, validates ideas |
| **The World Builder** | [03-world-builder.md](.claude/agents/03-world-builder.md) | Adds thematic depth, visual richness, metaphorical consistency to settings |
| **The Story Architect** | [04-story-architect.md](.claude/agents/04-story-architect.md) | Structures stories via Hierarchy of Arcs (Series → Season → Episode → Scene) |
| **Multi-Variant Plotter** | [05-brainstormer.md](.claude/agents/05-brainstormer.md) | Brainstorms 3+ narrative directions, explores alternatives |
| **Script Format Master** | [06-script-format.md](.claude/agents/06-script-format.md) | Enforces comic formatting, controls visual pacing |
| **Dialogue Coach** | [07-dialogue-coach.md](.claude/agents/07-dialogue-coach.md) | Suggests natural, character-specific dialogue |
| **The Humanizer** | [08-humanizer.md](.claude/agents/08-humanizer.md) | Strips robotic phrasing, ensures authentic voice |
| **Character Bible Keeper** | [09-character-bible.md](.claude/agents/09-character-bible.md) | Maintains character consistency across all seasons |
| **Visual Prompt Generator** | [10-visual-prompt.md](.claude/agents/10-visual-prompt.md) | Converts script descriptions to image generation prompts |

## Workflow Phases & Recommended Agents

### Phase 1: Foundation & Research
- Start with **Cataloguer** to understand what's established
- Use **Story Architect** to outline series spine
- Use **World Builder** to establish visual language

### Phase 2: Development & Brainstorming
- Use **Interviewer** to validate ideas
- Use **Multi-Variant Plotter** to explore alternatives
- Use **Story Architect** to stress-test structure

### Phase 3: Scripting
- Use **Script Format Master** to enforce formatting
- Use **Dialogue Coach** for character voices
- Use **Character Bible Keeper** for consistency checks

### Phase 4: Refinement & Output
- Use **Humanizer** for dialogue polish
- Use **Visual Prompt Generator** for concept art direction

## How to Invoke an Agent

In a chat message, reference agents by name:

```
"Ask the Cataloguer about [topic]"
"The World Builder should add..."
"Run this through the Story Architect"
"Humanize this dialogue"
```

Or use the agent's role/description:

```
"I need help with character consistency — use the Character Bible Keeper"
"Brainstorm alternatives for this scene"
"Format this as a comic script"
```

The agent system is context-aware—mentioning an agent's name or role will trigger its specialized instructions.
