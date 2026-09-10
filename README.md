# agent-workflow

Versioned agent skills, agents, and rules distributed via [OpenPackage](https://github.com/enulus/OpenPackage).

## Layout

Content lives under the standard OpenPackage universal subdirs at the package root:

- `skills/` — agent skills
- `agents/` — agent definitions
- `rules/` — rules
- `commands/` — commands

Each is created on demand with `opkg add`.

## Usage

```bash
npx opkg add ./skills/my-skill.md
npx opkg set --ver <version>
```

Install this package into a workspace:

```bash
npx opkg install gh@JeffreyPYL/agent-workflow
```
