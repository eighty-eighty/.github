# 8080

Central configuration and community health files for [8080](https://github.com/eighty-eighty).

## What's inside

| File                 | Purpose                                 |
| -------------------- | --------------------------------------- |
| `CODE_OF_CONDUCT.md` | Standards for community interactions    |
| `SECURITY.md`        | Security vulnerability reporting policy |
| `SUPPORT.md`         | How to get help                         |
| `CONTRIBUTING.md`    | Contribution guidelines                 |
| `profile/README.md`  | Organization profile README             |
| `workflows/`         | Reusable GitHub Actions workflows       |

## Reusable Workflows

Workflows in `workflows/` can be referenced by any repository in the organization:

```yaml
jobs:
  ci:
    uses: eighty-eighty/.github/workflows/ci.yml@main
```

See each workflow's header comment for configuration options.
