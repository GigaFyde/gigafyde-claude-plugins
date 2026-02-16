# GigaFyde Claude Plugins

A plugin marketplace for Claude Code. Browse available plugins and install them directly.

## Available Plugins

### project-orchestrator

Ship multi-service features without losing context. Orchestrates parallel agent teams from brainstorming through wave-based implementation and dual-model code review.

**Install:**

```
/plugin marketplace add gigafyde/gigafyde-claude-plugins
/plugin install project-orchestrator@gigafyde-claude-plugins
```

**Features:**
- Full lifecycle orchestration: brainstorm, design, implement, review, verify, finish
- Parallel agent teams with wave-based task execution
- Two-stage code review with confidence scoring (spec compliance + quality)
- Living state documents that survive context clears
- Git worktree isolation for parallel implementation
- Optional MCP integration with graceful fallbacks

[View documentation](https://github.com/gigafyde/project-orchestrator)

## Adding This Marketplace

Run inside Claude Code:

```
/plugin marketplace add gigafyde/gigafyde-claude-plugins
```

Then browse and install any plugin listed above.

## License

MIT — see [LICENSE](LICENSE).
