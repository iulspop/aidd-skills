# aidd-skills

Shared [Claude Code](https://claude.com/claude-code) skills for AI-driven development across projects.

## Install

Install all skills into a project:

```bash
npx skills add --yes --agent claude-code iulspop/aidd-skills
```

Install a single skill:

```bash
npx skills add --yes --agent claude-code iulspop/aidd-skills/skills/<skill-name>
```

## Skills

### Testing

| Skill | Extension | Use for |
|---|---|---|
| `unit-tests` | `.test.ts` | Pure function unit tests |
| `happy-dom-tests` | `.test.tsx` | React component and hook render tests |
| `integration-tests` | `.spec.ts` | Server action, database, and API route tests |
| `e2e-tests` | `.e2e.ts` | Playwright browser tests |

### Code Quality

| Skill | Use for |
|---|---|
| `code-review` | PR review with blocking issues vs suggestions |
| `refactor` | Safe refactoring with tests as safety net |
| `accessibility` | WCAG 2.1 AA audit with concrete fixes |

### Planning & Writing

| Skill | Use for |
|---|---|
| `plan` | Break features into sequential tasks under 50 lines each |
| `brainstorm` | Solution ideation with trade-offs and recommendation |
| `documentation` | Example-driven docs with runnable code |
| `write` | Professional writing clarity |
| `better-writer` | Persuasive business copy |

### Utilities

| Skill | Use for |
|---|---|
| `commit` | Conventional commit messages |
| `log` | Changelog entries for completed epics |
| `name` | Function and variable naming |
| `debug` | Structured root cause analysis |
| `svg-to-react` | Convert SVGs to React TypeScript components |
