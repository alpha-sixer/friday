# friday

Clean distributable package for the Friday Codex skill and local CLI.

## Download

Download:

```text
friday-codex-package-2026-05-30.zip
```

Then give your Codex agent this prompt:

```text
Install this Friday Codex skill package from scratch, then tell me when it is ready for the first `$friday status` / `$friday find target=1` run: unzip friday-codex-package-2026-05-30.zip && cd friday-codex-package && bash scripts/install_codex_skill.sh "$HOME/Desktop/friday"
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
b0db55d8beac5f2f73778afdcb2f4236ad815fdc2e4ad4177173072219b42f41
```

