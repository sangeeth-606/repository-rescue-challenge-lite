# Workflow Notes

## Branching Strategy

All development happens on feature branches. Never push directly to `main`.

```bash
git checkout -b feature/<description>
```

## Commit Guidelines

Write clear, descriptive commit messages. Each commit should represent a single logical change.

## Code Review

All changes require a code review before merging. No exceptions.

## Merging

Use pull requests to merge feature branches into `main`. Never force push.

## Environment Configuration

Keep `.env.example` and `config/environment.md` in sync before changing any environment values.
