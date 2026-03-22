## Quickstart (local)

Install dependencies and serve locally:

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
mkdocs serve
```

Build the site:

```bash
mkdocs build
```

Deploy to GitHub Pages (CI will also deploy on push to `main`):

```bash
mkdocs gh-deploy --force
```
