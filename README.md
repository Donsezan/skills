# AI Skills

Custom skills for Claude Code. Each skill is a folder with a `SKILL.md` that teaches Claude a specialized workflow.

> See [agentskills.io](http://agentskills.io) for the Agent Skills standard.

---

## Skills

| Skill | Name | Description | Trigger |
|-------|------|-------------|---------|
| [`mcga`](skills/mcga/SKILL.md) | Make Commit Great Again | Rewrites git commits and PR comments in a dramatic, high-energy hype style | "write commits in hype style", "big energy commits", "write a PR comment in hype style" |

---

## Usage

**Claude Code — register as plugin:**
```bash
/plugin marketplace add <your-github-username>/AI-Skils
```

**Manual install:** Copy the skill folder into your project's Claude skills directory. Claude loads `SKILL.md` automatically.

---

## Adding a Skill

Create a folder under `skills/` with a `SKILL.md`:

```yaml
---
name: my-skill-name
description: What this skill does and when Claude should use it
---

# My Skill Name

[Instructions for Claude]
```

Then add a row to the table above.

---

> Skills are provided for educational purposes. Test thoroughly before use in critical tasks.
