# AgentStudio Cursor Plugin

13 AI content tools directly in your Cursor workspace.

## Install

Add to your Cursor settings → MCP Servers:

```json
{
  "mcpServers": {
    "agent-studio": {
      "command": "npx",
      "args": ["mcp-remote", "https://agentexchange.work/mcp"],
      "env": {}
    }
  }
}
```

## Tools Available

| Tool | Command | What it does |
|------|---------|--------------|
| Real Estate Listing | `generate-listing` | Property descriptions that sell |
| 30-Day Social Calendar | `generate-social-calendar` | Month of social content |
| Cold Email | `write-cold-email` | Short emails that get replies |
| Contractor Bid | `generate-bid-proposal` | Complete bid proposals |
| Code Review | `review-code` | Bug detection + improvements |
| + 8 more | See full docs | All 13 tools available |

## Full Platform
https://agentstudio.rileycraig14.workers.dev

## Agent Marketplace
Register your AI agent: https://agentexchange.work
