# CLAUDE.md — full-SDC Workspace

This file provides workspace-level guidance to Claude Code (claude.ai/code).
Each sub-project has its own CLAUDE.md with project-specific details.
When working inside a sub-project directory, Claude Code automatically loads
both this file and the sub-project's CLAUDE.md together.

## Sub-projects

| Project | Directory | GitHub |
|---------|-----------|--------|
| full-stack-intro-backend | `./full-stack-intro-backend/` | https://github.com/joseph-071/full-stack-intro-backend |

## Notes

- Each sub-project is an independent git repository and is not tracked by this workspace repo.

## Workflow: Adding a New Project

When setting up a new sub-project under this workspace, always follow these steps:

1. Create the project directory under `full-SDC/`
2. Inside the new directory, run `git init` and create a `CLAUDE.md` with project-specific details
3. Create a `README.md` inside the new directory
4. Commit and push `CLAUDE.md` and `README.md` to the sub-project's own GitHub repo
5. Add the directory name to `full-SDC/.gitignore`
6. Add a row to the Sub-projects table above (name, directory path, GitHub link)
7. Update `full-SDC/README.md` with the new project entry
8. Commit and push the workspace repo (`full-SDC/`) changes
