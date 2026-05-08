# homebrew-recliq

Homebrew tap for [recliq](https://recliq.dev) — natural language search for your shell history.

## Install

```bash
brew tap recliq-sh/recliq
brew install recliq
```

## Usage

```bash
recliq "kubectl drain a node"
recliq "postgres migration last week"
recliq "git rebase on the feature branch"
```

## Verify

```bash
recliq --version
recliq --dry-run "your query"   # see what would be sent, no request made
```

Issues and source: [github.com/recliq-sh/recliq](https://github.com/recliq-sh/recliq)
