# mkdocs-material-stem-template

GH pages static site using MKDocs + Material UI theme with the additions of some Science and Engineering extensions

# Quickstart

```sh
python3 -m venv .venv
.venv/bin/python3 -m pip install -U pip pip-tools
.venv/bin/python3 -m piptools compile --generate-hashes requirements.in --output-file requirements.txt
.venv/bin/python3 -m pip install -r requirements.txt --require-hashes --no-deps
```

```sh
.venv/bin/python3 -m mkdocs build
.venv/bin/python3 -m mkdocs serve
```


# Resources


# TODO

 - ~Locally build MKDocs~
 - Locally build MKDocs + extensions
    - ~Draw.io architecture diagrams~
    - Notebooks
    - Plotly diagrams in Markdown
 - Publish example website
 - Github Actions should work without the need for local developement
    - https://github.com/LukeCarrier/mkdocs-drawio-exporter/blob/main/docs/github-actions.md
 - Should work as a GH Template Repo