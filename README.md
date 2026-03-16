# andrewxu22.github.io

Personal academic website of **Hailu Xu**, Assistant Professor at California State University, Long Beach.

Built with [Jekyll](https://jekyllrb.com/) and hosted on [GitHub Pages](https://pages.github.com/).

## Structure

```
.
├── _config.yml          # Site configuration
├── _layouts/
│   └── default.html     # Main layout (nav + header + footer)
├── assets/
│   ├── css/main.css     # Stylesheet
│   └── favicon.svg      # Site icon
├── index.html           # Home page
├── research.html        # Research projects
├── publications.html    # Publications list
├── experience.html      # Work & education experience
├── teaching.html        # Teaching history
├── group.html           # Research group members
├── services.html        # Academic services
├── contact.html         # Contact information
└── Gemfile              # Ruby dependencies
```

## Local Development

```bash
bundle install
bundle exec jekyll serve
# Visit http://localhost:4000
```

## Deployment

Push to the `main` branch — GitHub Pages will build and deploy automatically.

Make sure GitHub Pages is set to deploy from **branch: main, root (/)** in the repository Settings → Pages.
