# claude-uk-spinners

Заміна стандартних фраз завантаження Claude Code на 100+ розмовних українських виразів.

A customization tool for Claude Code's CLI that replaces default spinner/processing phrases with 100+ colloquial Ukrainian phrases.

## Installation

### Via Claude Code (recommended)

1. Clone this repo and open it in Claude Code
2. Run `/install-spinner`

That's it — Claude will copy the phrases into your `~/.claude/settings.json`.

### Manual

Copy the `spinnerVerbs` field from `spinners.json` into your `~/.claude/settings.json`:

```json
{
  "spinnerVerbs": {
    "mode": "replace",
    "verbs": ["..."]
  }
}
```
