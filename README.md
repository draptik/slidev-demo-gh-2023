# Showcase: Publish slidev presentation in subfolder to Github Pages

- Folder `presentation-demo` contains the default slidev presentation
- File `.github/workflows/deploy.yml` contains the github actions for publishing to github pages. In
  addition to the [official documentation](https://sli.dev/guide/hosting.html#github-pages), there
  are some extra `cd <subfolder>` instructions in the `run` statements. The `build-dir` assignment is
  also prepended by the `<subfolder>`.

## Prerequisites

Web UI of Github Repo

- Settings -> Pages -> Branch: Choose "gh-pages" branch and "/ (root)" in drop-down menues, and save.

![screenshot1](./screenshot-github-settings1.png)

