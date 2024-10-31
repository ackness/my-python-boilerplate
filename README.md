# My Python Boilerplate

## package manager

```bash
curl -sSf https://rye.astral.sh/get | bash

rye sync
rye sync --update-all


rye add package-name
```

## test

```bash
rye run tests
```

## reformat

```bash
rye fmt
```

## precommit check

```bash
git add .
pre-commit
```

## build docker

```bash
# not `rye init --virtual`
rye build --wheel --clean
docker build . --tag your-image-name
```
