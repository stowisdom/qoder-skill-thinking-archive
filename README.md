# Thinking Archive

> Qoder Skill for minimalist thinking management and deep research tracking

## Philosophy

**One topic at a time.** The system handles all the tedious operations for you.

No complex menus, no frequent choices. Automatic conclusion extraction, automatic connection building. Focus on thinking itself, not on managing tools.

## What is this?

Thinking Archive is a Qoder Skill designed for deep, continuous research on single topics. It uses an ASCII card format to capture:

- **The problem** you're trying to solve
- **Current understanding** with key insights
- **Thinking journey** - how you got here
- **Open questions** - what remains unclear

## Installation

```bash
# Via skills.sh
npx skills add stowisdom/qoder-skill-thinking-archive

# Or manual install
cd ~/.qoderwork/skills
git clone https://github.com/stowisdom/qoder-skill-thinking-archive.git thinking-archive
```

## Commands

| Command | Action |
|---------|--------|
| `/think new <topic>` | Start a new thinking archive |
| `/think <topic>` | Continue an ongoing topic |
| `/think conclusion` | Archive current topic (generate ASCII card) |
| `/think show` | Show all topics (in-progress / completed) |
| `/think continue <topic>` | Reopen completed topic |
| `/think md` | Export to standard Markdown |
| `/think clean` | Recycle bin management |

## ASCII Card Format

```
╔══════════════════════════════════════════════════════════════╗
║                      📋 Decision Fatigue                       ║
║                                                              ║
║  Status: Completed | Created: 2026-03-01 | Updated: 2026-03-08║
║                                                              ║
║  ┌─────────────────────────────────────────────────────┐    ║
║  │  Problem: Why do small decisions feel so draining?  │    ║
║  ├─────────────────────────────────────────────────────┤    ║
║  │  Current View:                                       │    ║
║  │  • The drain isn't the decision, it's the second-   │    ║
║  │    guessing that follows                             │    ║
║  │  • Self-doubt comes from unclear "good enough" std  │    ║
║  │  • Action: Establish decision thresholds             │    ║
║  ├─────────────────────────────────────────────────────┤    ║
║  │  Journey:                                            │    ║
║  │  Decision volume → Post-decision monitoring →        │    ║
║  │  Self-doubt → Unclear standards                      │    ║
║  ├─────────────────────────────────────────────────────┤    ║
║  │  Still Unclear:                                      │    ║
║  │  • How to set "good enough" standards specifically   │    ║
║  │  • Do money/time/energy decisions share thresholds?  │    ║
║  └─────────────────────────────────────────────────────┘    ║
╚══════════════════════════════════════════════════════════════╝
```

## Three-Step Guidance

The Skill uses a unique conversation style:

1. **Understand your framework** - Grasp what you're saying, why, and to whom
2. **Add one dimension** - Precisely add one thinking variable to expand perspective
3. **Converge to focus** - Present 2-3 directions, let you choose one to go deeper

## Storage Structure

```
~/.qoderwork/thinking-archive/
├── index.md              # Topic list with status
├── decision-fatigue.md   # Individual topic files
├── deep-work-research.md
└── exports/              # Markdown exports
```

## Why This Works

- **Compounding effect**: Each session builds on previous insights
- **No context loss**: The ASCII card captures everything at a glance
- **Conversation, not interrogation**: Natural dialogue with strategic guidance
- **150-300 word responses**: Forces focus, creates rhythm

## License

MIT
