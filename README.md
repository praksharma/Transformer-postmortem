# Transformer-postmortem
## Packages to install

```sh
pip install -r requirements.txt
```

## Build the docs

```sh
jupyter-book build docs/
```

## Force build the docs

```sh
jupyter-book build --all docs/
```
# Push to github

```sh
ghp-import -n -p -f docs/_build/html
```
