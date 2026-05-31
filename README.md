# friday

Clean distributable package for the Friday Codex skill and local CLI.

## Download

Download:

```text
friday-codex-package-2026-05-31.zip
```

Then give your Codex agent this prompt:

```text
Install this Friday Codex skill package from scratch, then tell me when it is ready for the first `$friday status` / `$friday find target=1` run: unzip friday-codex-package-2026-05-31.zip && cd friday-codex-package && bash scripts/install_codex_skill.sh "$HOME/Desktop/friday"
```

The installer initializes the local SQLite database and installs the Codex skill at:

```text
~/.codex/skills/friday/SKILL.md
```

## Requirements

- Python 3.9+
- `uv`
- Codex Desktop/App with browser capability
- Dropship Calendar login
- Network access to Dropship Calendar and eBay

No eBay API key is required.

## Package Verification

SHA256:

```text
5ec63f22f7a970ccfb2e1fe0129314ad74c9652d9fc9ac707547aca7e7ffc106
```
