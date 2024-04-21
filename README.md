## Build

```
python3.10 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Lint
```
source .venv/bin/activate
black . && isort --profile black . && pylint
```