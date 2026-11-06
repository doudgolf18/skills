# skills

Project-local Claude Code skills.

## Instagram agent skills

The 13 `ig-*` skills in `.claude/skills/` come from
[Jakeschincariol/instagram-agent-skill](https://github.com/Jakeschincariol/instagram-agent-skill)
(MIT, see `LICENSE-instagram-agent-skill`).

To use them in every project, copy them globally:

```bash
cp -r .claude/skills/ig-* ~/.claude/skills/
```

Voice profile: copy `templates/voice.md` to `~/.claude/instagram/voice.md` and fill it in.
Every skill reads it.
