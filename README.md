# Hugo + GitHub Pages + GitHub Actions = ❤️

This repository is a self-contained template for how to deploy a
Hugo static site, hosted on GitHub, and deployed to GitHub Pages hosting,
using the continuous integration available through GitHub Actions.

## Current Versions

- `Hugo`: v0.124.1 extended
- [`Hugo-Book` theme](https://github.com/alex-shpak/hugo-book/): commit [`2dffe0b`](https://github.com/alex-shpak/hugo-book/commit/2dffe0bc7a5caac3e49bf2abe943ca412d5f4333)
- Hugo-Encrypt with modifications
- GitHub Actions: Ubuntu 22, Node.js 16 (for now)

## Getting Started

After instantiating this template as a repository of your own, make sure to edit `config.yaml` to update `baseURL` to reflect your own GitHub Pages URL (usually `username.github.io/repo-name` unless you're using a custom domain).
