# skill-optimizer

Autoresearch optimization loop for building and iterating Claude skills.

## Structure

```
skills/ipak-dev/   — ipak.dev skill (built here)
evals/             — test prompts
results/           — loop output (gitignored)
scripts/           — optimization loop scripts
eval-viewer/       — HTML viewer for eval results
references/        — reference examples
agents/            — agent definitions
```

## Usage

```bash
export ANTHROPIC_API_KEY=...
python3 scripts/optimize.py skills/ipak-dev/SKILL.md
```
