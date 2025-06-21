# Priya Soneji Portfolio Website

This repository contains the source code for Priya Soneji's personal portfolio website, built with [Jekyll](https://jekyllrb.com/).

## Features
- Project showcase
- Resume and about section
- Clean, responsive design

## Development
**It is strongly recommended to always use the provided devcontainer for development.** This ensures a consistent environment and avoids the need to install Ruby, Jekyll, or other dependencies on your local machine.

To start the development server with live reload inside the devcontainer, run:

```
jekyll serve --livereload
```

Then open [http://localhost:4000](http://localhost:4000) in your browser to view the site.

## Dev Container
A [devcontainer](https://containers.dev/) is set up for this repository. Devcontainers allow you to work on the project in a fully configured development environment. All you need is Docker installed.

To use the devcontainer, open the project in [Visual Studio Code](https://code.visualstudio.com/) and select "Reopen in Container" when prompted. This will automatically set up everything you need to start developing and previewing the site.

## Requirements
- Docker (for the devcontainer)

If you are using the provided dev container, all dependencies are pre-installed. Manual installation of Ruby, Bundler, or Jekyll is not necessary or recommended.

## Directory Structure
- `index.html`, `projects.html`, `resume.html`: Main site pages
- `_layouts/`: Jekyll layout templates
- `assets/`: Images, CSS, and data files

## License
This project is for personal and educational use.
