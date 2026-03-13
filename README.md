# binkit

A handful of shell scripts that save me from typing the same long commands over and over.

Nothing clever here. No framework, no config system, no plugin architecture.
Just small scripts that do one thing each, badly enough that I haven't bothered rewriting them properly.

## What's in the box

| Script | What it does |
|--------|-------------|
| `codex-usage` | Shows OpenAI Codex rate limits so I know when to stop pretending I'm productive |
| `ec2-status` | Lists EC2 instances in a table because the AWS console takes too long to load |
| `gsmi` | `nvidia-smi` but fewer columns because the real one hurts my eyes |
| `nuke-pycache` | Deletes `__pycache__` and `.pyc` files before they outnumber your actual code |

## Installation

```bash
git clone https://github.com/ewijaya/binkit.git
cp binkit/* ~/bin/
```

Or don't. These were mostly written at 2am and it shows.

## Requirements

- `bash`
- `python3` (for `codex-usage`, `ec2-status`)
- `nvidia-smi` (for `gsmi`, obviously)
- AWS CLI (for `ec2-status`)
- Low standards

## License

Do whatever you want with these. If they break something, that's on you.
