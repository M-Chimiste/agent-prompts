# Agent Prompts Repository

This repository contains a curated collection of agent prompts tailored for various AI applications and workflows. Rather than traditional code, this repository is designed as a structured archive for easily managing, versioning, and referencing prompts used across different AI agent-based projects.

## Purpose

- **Centralized Management:** Keep agent prompts organized in a single location to simplify version tracking and ensure consistency.
- **Easy Reference:** Quickly access, reuse, and iterate on prompts without needing to remember their individual locations or contexts.
- **Collaboration & Versioning:** Facilitate prompt sharing and improvements across projects and team members using Git-based workflows.

## Repository Structure

The repository is organized into directories based on agent or application context. Each agent or workflow-specific directory contains prompt files in Markdown format (`.md`) clearly defining instructions, roles, and interaction guidelines for AI agents.

Example structure:
```
agent-prompts/
├── cursor/
│   └── cursor_rules.md
├── agent_x/
│   ├── prompt_v1.md
│   └── prompt_v2.md
└── agent_y/
    └── general_guidelines.md
```

## How to Use

1. **Cloning the repository:**

```bash
git clone https://github.com/yourusername/agent-prompts.git
```

2. **Adding New Prompts:**
   - Create a new directory if needed (e.g., `agent_z`).
   - Add prompt files clearly named to reflect their version or purpose.

3. **Updating Existing Prompts:**
   - Modify existing prompt files directly.
   - Commit and push changes with meaningful commit messages for easy version tracking.

## Best Practices

- **Clear Naming Conventions:** Use descriptive filenames (e.g., `debugger_mode_v1.md`, `planner_guidelines.md`).
- **Regularly Commit:** Frequently commit changes with clear commit messages to track prompt evolution.
- **Review and Reflect:** Periodically review and improve prompts based on application performance and usability feedback.

## License

This repository is licensed under the Apache License 2.0. See [LICENSE](LICENSE) for more details.

