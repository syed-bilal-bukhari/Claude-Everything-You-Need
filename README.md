
# Claude Everything You Need

## How to Use These Agents

### 1. Spawning a Team of Agents

To use the agents in this repository, follow these steps:

1. **Open Claude in the root directory of your project.**
2. **Ask Claude to read the desired agent file** (e.g., [agents/TeamLead.md](agents/TeamLead.md)) and spawn a team. For example, you can say:
	 > "Read TeamLead.md and spawn a team."

Claude will read the agent specification and instantiate the appropriate agents for your project.

### 2. Enable Experimental Agent Teams

To enable Claude's experimental agent teams feature, add the following flag to your `.claude/settings.json` file:

```json
{
	"env": {
		"CLAUDE_CODE_EXPERIMENTAL_AGENT_TEAMS": "1"
	}
}
```

This setting is required for team-based agent workflows.

### 3. Available Agents

Agents are defined in the `agents/` directory:

- BackendReviewer (General)
- BackendWorker (Python)
- CodeSimplifier
- FrontendReviewer (General)
- FrontendWorker (React)
- PolicySentinel
- TeamLead

Refer to each `.md` file for agent roles and instructions.
