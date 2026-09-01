# JobRok

Bring your personalised JobRok career, job, and application context into AI conversations.

The plugin connects ChatGPT and Codex to JobRok's hosted, read-only MCP server. After signing in, it can retrieve your authorised CV, career goals, ideal-job preferences, private context, Coach memory, jobs, evaluations, and applications.

## Install

Add this repository as a plugin marketplace:

```bash
codex plugin marketplace add JobRok/jobrok-plugin --ref main
codex plugin add jobrok@jobrok
```

You can also add `https://github.com/JobRok/jobrok-plugin` from **Plugins → Add → Add marketplace** in the ChatGPT desktop app.

## Service

- Website: <https://jobrok.com>
- Plugin: <https://plugin.jobrok.com>
- MCP server: <https://api.jobrok.com/mcp>

JobRok only exposes data authorised by the signed-in user. The current plugin and MCP tools are read-only.
