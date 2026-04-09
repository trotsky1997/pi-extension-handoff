# pi-extension-handoff

Install with:

```bash
pi install git:github.com/trotsky1997/pi-extension-handoff
```

You can pass a goal directly:

```text
/handoff continue implementing the team support work
```

Or configure a default handoff target in `~/.pi/agent/handoff.json` or `.pi/handoff.json`:

```json
{
  "defaultGoal": "continue the current implementation task"
}
```

`defaultTarget` is also accepted as a backward-compatible alias.

If you do not pass an argument and do not provide any config,
`/handoff` falls back to `continue the current implementation task`.
