# Brutalist Pages Template

A simple personal website template for GitHub Pages.

It takes inspiration from the restraint and clarity of personal sites like [mitchellh.com](https://mitchellh.com/), but the layout and styling here are original and meant to be reused as your own starting point.

This repository serves two purposes:

- Use it as a template to create your own site
- Contribute improvements back to the template through fork and pull request

## Why this template

- No framework, no build step, no dependency install
- Works on GitHub user pages and project pages
- Plain multi-page structure with shared styling
- Includes a matching `404.html`
- Keeps template usage and OSS contribution workflows separate

## Use this template for your own site

Use `Use this template`, not `Fork`, when your goal is to launch your own homepage.

1. Click `Use this template` on GitHub
2. Create a new repository in your own account
3. If you want a user site, name the repository `<your-github-username>.github.io`
4. Edit `index.html`, `writing.html`, `misc.html`, and `styles.css`
5. Open `Settings` -> `Pages`
6. Set `Build and deployment` -> `Source` to `Deploy from a branch`
7. Select branch `main` and folder `/ (root)`
8. Push to `main`

## Contribute to this template

Use `Fork` when your goal is to improve this template itself.

1. Fork this repository
2. Create a feature branch in your fork
3. Make and test your changes
4. Open a pull request back to this repository

If you started by customizing your own site from `Use this template`, copy the relevant changes into a fork before opening a pull request. Repositories created from a template have independent history, so they should not be used as the contribution path back to the template.

See [CONTRIBUTING.md](./CONTRIBUTING.md) for the expected workflow.

## Project structure

```text
.
├── .nojekyll
├── 404.html
├── CONTRIBUTING.md
├── index.html
├── LICENSE
├── misc.html
├── styles.css
├── writing.html
└── README.md
```

## Customize it

1. Edit `index.html`, `writing.html`, and `misc.html`
2. Replace `Your Name`, the sample copy, and the contact links
3. Adjust spacing and typography in `styles.css`
4. Add more pages if you want, but keep links relative so the template works on project pages too

## Preview locally

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Publish this repository as a template

1. Push the repository to GitHub
2. Open `Settings` -> `General`
3. Enable `Template repository`
4. Add a short description and topics such as `github-pages`, `personal-site`, `template`, and `static-site`

## Publish a site made from this template

1. Create a new repository with `Use this template`
2. Open `Settings` -> `Pages`
3. Set `Build and deployment` -> `Source` to `Deploy from a branch`
4. Select branch `main` and folder `/ (root)`
5. Push to `main`

## Optional custom domain

If you want to use a custom domain, add a `CNAME` file at the repository root with your domain name.

## License

MIT
