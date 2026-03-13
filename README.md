# Beyond7 Claude Plugin Marketplace

Curated Claude Code plugins by [Hendrik Hemken / Beyond7](https://beyond7.ai).

---

## Installation

### 1. Marketplace hinzufuegen

```
/plugin marketplace add hendrikhemken/claude-marketplace
```

### 2. Plugins browsen und installieren

```
/plugin                    # Discover-Tab zeigt alle Beyond7-Plugins
/plugin install productivity-kit@beyond7-tools
```

---

## Available Plugins

### Productivity Kit

OKR tracking + daily routines for solo entrepreneurs and small teams.

**Install:**
```
/plugin install productivity-kit@beyond7-tools
```

**Skills:** setup, good-morning, okr-monday, okr-friday, journal, okr-expert

**What it does:**
- Morning routine that reviews yesterday and plans today
- Weekly Monday/Friday OKR check-ins (Wodtke method)
- Daily journal tracking
- OKR expert advisor (Wodtke + Klau + Cagan)

[Repository](https://github.com/hendrikhemken/claude-plugin-productivity-kit)

### Workshop Tools

Skills for workshop facilitation: Recaps, Icebreaker, Session-Management.

**Install:**
```
/plugin install workshop-tools@beyond7-tools
```

[Repository](https://github.com/hendrikhemken/claude-plugin-workshop-tools)

---

## Alternative Installation (npx skills CLI)

All plugins can also be installed via the community `npx skills` CLI:

```bash
npx skills add hendrikhemken/<plugin-repo> --agent "Claude Code" --copy --yes
```

This installs skills into your project's `.claude/skills/` directory.

---

*Built with Claude Code by [Beyond7](https://beyond7.ai)*
