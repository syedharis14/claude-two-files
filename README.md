# claude-two-files

Claude Code forgets everything between sessions. These two files are how it remembers a project.

- **`CLAUDE.md`** holds your rules, each with the date you gave it and why. Claude Code loads it at the start of every session.
- **`NOW.md`** says where everything stands. `CLAUDE.md` tells Claude to read it first and update it before it stops.

Copy both into the root of your project and fill in the `<...>` parts. Keep `NOW.md` short (current state only); move finished history into a separate archive file you search, not read.

From the Agentwright video "33 Ways I Actually Use Claude Code (All Shown Working)", number 33: the one that makes the other 32 work.

MIT licence. Free to copy.
