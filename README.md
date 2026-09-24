# CodeRabbit Central Configuration

This repository houses the central configuration file (`.coderabbit.yaml`) for [CodeRabbit](https://coderabbit.ai) across all repositories owned by [@JWEB0689](https://github.com/JWEB0689).

## How It Works

1. **Global Defaults**: Any repository under `@JWEB0689` without its own `.coderabbit.yaml` automatically inherits the settings defined in this repository.
2. **Repository Overrides**: Repositories can define their own `.coderabbit.yaml` file to customize path instructions or tools. Setting `inheritance: true` in a repository's local configuration merges its settings with these central defaults.
3. **Interactive Control**: You can interact with CodeRabbit on any Pull Request:
   - `@coderabbitai review` — Triggers a manual full review.
   - `@coderabbitai summary` — Generates a PR summary.
   - `@coderabbitai configuration` — Displays the resolved configuration for that PR.
