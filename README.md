# Showcase: Publish slidev presentation from subfolder to Github Pages

- Folder `presentation-demo` contains the default [Slidev](https://sli.dev/) presentation. This is our `<subfolder>`.
- File [`.github/workflows/deploy.yml`](.github/workflows/deploy.yml) contains the github actions for publishing to github pages. In
  addition to the [official documentation](https://sli.dev/guide/hosting.html#github-pages), there
  are some extra `cd <subfolder>` instructions in the `run` statements. The `build-dir` assignment is also prepended by the `<subfolder>`.

## Prerequisites

Web UI of Github Repo

- Settings -> Pages -> Branch: Choose "gh-pages" branch and "/ (root)" in drop-down menus, and save.

![screenshot1](./screenshot-github-settings1.png)

- Ensure that GH-Actions has the required permissions: Settings -> Actions -> General -> Workflow permissions: Read and **Write** permissions

![screenshot2](./screenshot-github-settings2.png)
