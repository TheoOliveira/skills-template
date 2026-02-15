# Skills Template

This repository serves as a starting point for projects using [skills.sh](https://skills.sh).

## Structure

- `.agents/skills`: Place your agent skills here.
- `.agents/knowledge`: Store knowledge items for your agents here.
- `.agent/workflows`: Define agent workflows here.
- `src`: Source code for your project.
- `docs`: Documentation.

## Usage

1.  Clone this repository.
2.  Add skills using the `skills` CLI:
    ```bash
    npx skills add https://github.com/vercel-labs/skills --skill <skill-name>
    ```
3.  Customize `.agent/workflows` to define your agent's behavior.

## Installed Skills

- **[find-skills](https://github.com/vercel-labs/skills/tree/main/skills/find-skills)**: Search for available skills.
