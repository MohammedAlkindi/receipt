# Receipt — project context for Claude Code

## What it does
Your bank app tells you how much you spent. **receipt** tells you what actually happened — semantic clustering, seven behavioral detectors, and an AI narrative that thinks like a sharp friend with an accounting degree: specific dollar amounts, named merchants, non-obvious patterns, and none of the generic budget-app moralizing.

## Stack
python

## Commands
```powershell
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
pytest
```

## Conventions
- Conventional Commits, one logical change per commit, Mohammed as sole author with no AI trailers. No secrets in the repo. External calls go through a service layer that normalizes errors.
- Python: virtualenv always, `requirements.txt` pinned, deterministic logic split from I/O.

