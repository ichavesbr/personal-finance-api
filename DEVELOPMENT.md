# Development Notes

## Commit Convention

This project follows the [Conventional Commits](https://www.conventionalcommits.org/) pattern.

### Format
```
<prefix>: short description
```

### Prefixes

| Prefix | When to use |
|--------|-------------|
| `feat:` | New feature (new route, new module, etc.) |
| `fix:` | Bug fix |
| `docs:` | README or any documentation changes |
| `refactor:` | Code change that's not a feature nor a bug fix |
| `chore:` | Config files, dependencies, `.env.example`, `tsconfig`, etc. |
| `test:` | Adding or fixing tests |
| `ci:` | GitHub Actions or pipeline configuration |

### Examples
```
feat: add transaction creation endpoint
fix: correct balance calculation on monthly summary
docs: update README tech stack
refactor: extract auth logic into middleware
chore: add .env.example
```
