# <Your project>

One paragraph: what this project is, who it is for, and where the main folders are.

## What to read, and when

- **Every session:** `NOW.md` (where things stand, what's next). Update it before the session ends. Keep it current-state only, under 80 lines.
- **Only when the task needs it:** list the long files here with the task that needs each one, so they are not read every time.

This file holds only rules in force. When a rule is replaced, rewrite it here; don't append.

## Rules

Write each rule with the date you gave it and why, so Claude (and you, later) can tell an old rule from a new one:

- **<The rule, in one line>** (<you>, <date>: "<what you said, in your words>"). <Why, in one sentence.>
- **Before any step that costs money, say what it costs** (<you>, <date>). Look for a free local way first.
- **Never print or commit `.env`** (<you>, <date>). It holds the API keys.

## How we work

- One task per session. When a part is done, update NOW.md.
- Step-by-step processes go in `.claude/skills/<name>/SKILL.md`, not here: a skill loads only when its task comes up.
