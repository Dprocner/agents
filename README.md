# Dprocner Agents

This repository contains GitHub Copilot custom agent files (`.agent.md`) for the Dprocner project.

## Agents

| Agent | File | Purpose |
|-------|------|---------|
| **BA Agent** | [.github/agents/ba-agent.agent.md](.github/agents/ba-agent.agent.md) | Business Analyst — creates and refines user stories, epics, and tasks in GitHub with full acceptance criteria, priority labels, and linked issue hierarchies |

## How to Use

1. Clone or reference this repo in your workspace
2. Agents in `.github/agents/` are automatically available in VS Code Copilot Chat
3. Select an agent from the agent picker (`@BA Agent`) or invoke via chat

## Adding New Agents

Create a new `*.agent.md` file in `.github/agents/`. Follow the template in any existing agent file.
