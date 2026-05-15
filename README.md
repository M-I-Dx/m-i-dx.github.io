# Mandeep Portfolio

Personal portfolio built with Jekyll and GitHub Pages.

## Local Setup

Install the locked Ruby dependencies:

```bash
bundle install
```

Run the site locally:

```bash
bundle exec jekyll serve
```

Build the static site:

```bash
bundle exec jekyll build
```

## Content

Most homepage content is data-driven:

- `_config.yml` controls site metadata, hero copy, links, and current-focus items.
- `_data/experience.yml` controls the work timeline.
- `_data/projects.yml` controls project case-study cards. Project links are optional.
- `_data/publications.yml`, `_data/skills.yml`, `_data/metrics.yml`, and `_data/education.yml` control the remaining homepage sections.

External profile links should stay limited to GitHub and LinkedIn.

## Deployment

The repository is configured for GitHub Pages through the `github-pages` gem. Push changes to the publishing branch used by the repository, then let GitHub Pages build and deploy the site.
