# What this is

It's an example design for a landing page to explain the dangers of AI.

# Prereqs

This repo is built with hugo. I used 'v0.149.0+extended+withdeploy', but a later version is probably fine, I think it requires an 'extended' build though, which is true for the one from MacOS's Homebrew as of 2025.

It uses a git submodule for the Hugo theme, `ananke`, checked out in `themes/ananke`. To get the submodule, first clone the repo, then do `git submodule update --init`.

# Running Locally

`hugo server` from the repo root should do the trick, then visit the local url it provides on the command line.

# Organization

The choice of Hugo was overkill since I don't really use much of the Hugo features (yet) although I was expecting to. I ended up putting all the code of the root html file into `layouts/index.html`, which includes its content. The css overrides are in `assets/ananke/css/custom.css`. The page title is in `hugo.toml`.

