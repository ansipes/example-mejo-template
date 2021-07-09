# Web Repository Template

This template provides an improved web development experience when using Visual Studio Code and GitHub. It includes configurations for settings, extensions, and a GitHub Pages workflow.

## How to Use

### Setup 🛠

1. Click [Use this template](https://github.com/ansipes/mejo-web-template) and create the repository from template
2. Under `Settings` -> `Pages` pick `gh-pages` as the branch and `/ (root)` as the folder, the click save
3. Clone your repository and open in Visual Studio Code
4. Open the Extensions panel in Visual Studio Code
   - Search for `@recommended`
   - Under `WORKSPACE RECOMMENDATIONS` click `Install Workspace Extension Recommendations` (cloud with a down arrow)

### Preview 👁

Click the "Go Live" button in the bottom right of Visual Studio Code. This will open [http://127.0.0.1:5500/](http://127.0.0.1:5500/) in your browser.

Everything in your `src` folder will be served just like it is on a real web server.

### Publish 🚀

As long as you have enabled GitHub Pages, your project should be published at [https://{{ USERNAME }}.github.io/{{ REPOSITORY }}](#).

Replace `{{ USERNAME }}` with your GitHub username. Replace `{{ REPOSITORY }}` with your repository name.

## What's Included

### Settings ⚙️

This template includes settings that improve writing and version control in Visual Studio Code.

#### Writing

These settings solve common problems like unsaved work, poorly formatted code, and missing brackets.

- [Saves on Focus Change](https://github.com/ansipes/mejo-web-template/blob/812550fd1d1b7951cac2ded8ef2e9589e1ffe6b0/.vscode/settings.json#L2)
- [Formats Code on Save](https://github.com/ansipes/mejo-web-template/blob/812550fd1d1b7951cac2ded8ef2e9589e1ffe6b0/.vscode/settings.json#L3)
- [Closes Brackets Automatically](https://github.com/ansipes/mejo-web-template/blob/812550fd1d1b7951cac2ded8ef2e9589e1ffe6b0/.vscode/settings.json#L10)

#### Version Control

These settings help simplify sending your code to GitHub by reducing four steps (add, commit, push, pull) to a single step. Simply type a commit message in the Source Control view and click the checkmark.

- [Stages Changes Automatically](https://github.com/ansipes/mejo-web-template/blob/812550fd1d1b7951cac2ded8ef2e9589e1ffe6b0/.vscode/settings.json#L16)
- [Syncs After Commit](https://github.com/ansipes/mejo-web-template/blob/812550fd1d1b7951cac2ded8ef2e9589e1ffe6b0/.vscode/settings.json#L17)

### Extensions 🔌

This template includes recommended extensions that improve testing and formatting in Visual Studio Code.

#### [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

- Serves the `src` directory on [localhost:5500](localhost:5500)
- Refreshes Browser on Save

#### [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

- Formats Code with Opinionated Rules

https://user-images.githubusercontent.com/25012869/125014266-5cd3aa80-e03b-11eb-8a5c-80708376b80a.mp4

#### [HTMLHint](https://marketplace.visualstudio.com/items?itemName=mkaufman.HTMLHint)

- Analyzes HTML for Problems

### Workflows 🪄

This template includes a workflow that improves deployment via GitHub Pages.

#### [Deploy](../workflows/main.yml)

- Copies `src` to the `gh-pages` branch
