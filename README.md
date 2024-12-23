# `onsonr/docs` 

> Public technical documentation for the Sonr Blockchain. Found at [onsonr.dev](https://onsonr.dev).

## Usage

### Local Development

1. Clone the repository

```bash
git clone https://github.com/onsonr/docs.git
```

2. Mkdocs serves the documentation site locally at `http://localhost:8000`.

```bash
cd docs
mkdocs serve
```

3. Open `http://localhost:8000` in your browser.

### Deployment

1. Install [Mkdocs](https://www.mkdocs.org/user-guide/installation/).

2. Build the documentation site.

```bash
cd docs
mkdocs build
```

3. Deploy the documentation site to the `gh-pages` branch.

```bash
cd docs/site
git add .
git commit -m "Deploy"
git push origin gh-pages
```
