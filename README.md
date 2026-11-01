# 30 Day Map Challenge 2026

A retro, 90s-pastel static site for the #30DayMapChallenge (November 2026).
Built with Jekyll for GitHub Pages.

## Run locally

```bash
bundle install
bundle exec jekyll serve
```

Open http://localhost:4000/30daymapchallenge2026byspl/

## GitHub Pages setup

1. Repository **Settings**, then **Pages**.
2. Source: **Deploy from a branch**. Branch: **main**. Folder: **/ (root)**. Save.
3. The site appears at https://sweetpepperlabs-eu.github.io/30daymapchallenge2026byspl/

## Daily workflow

Everything routine lives in `_data/challenge.yml`.

- **Publish a day:** set its `status` to `published` and add the image at `assets/maps/NN-slug.png`.
- **Add a note:** edit the `notes` field for that day.
- **Update the date:** change `last_updated` in `_config.yml`.

The grid, the badges, and the day pages update from that file. No HTML edits are needed.

## User site or project site

This repository is a project site, so `_config.yml` has:

```yaml
baseurl: "/30daymapchallenge2026byspl"
```

If you later move the site to a user site (a repository named `sweetpepperlabs-eu.github.io`), set `baseurl: ""` and update `url`.

## Map style guide

Use the palette colours, a duotone or muted treatment, optional grain, and a framed border. Keep the map readable first.
