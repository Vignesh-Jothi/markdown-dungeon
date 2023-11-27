# Markdown Dungeon

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Open Source Helpers](https://www.codetriage.com/makecontributions/markdown-dungeon/badges/users.svg)](https://www.codetriage.com/makecontributions/markdown-dungeon)
[![CodeQL](https://github.com/MakeContributions/markdown-dungeon/actions/workflows/codeql-analysis.yml/badge.svg)](https://github.com/MakeContributions/markdown-dungeon/actions/workflows/codeql-analysis.yml)
[![codespell](https://github.com/MakeContributions/markdown-dungeon/actions/workflows/codespell.yml/badge.svg)](https://github.com/MakeContributions/markdown-dungeon/actions/workflows/codespell.yml)
[![Netlify Status](https://api.netlify.com/api/v1/badges/320e6533-33ab-402c-bfb9-ebac1881b260/deploy-status)](https://app.netlify.com/sites/markdown-dungeon/deploys)
[![Discord](https://img.shields.io/discord/863049619734790185?color=7389D8&logo=discord&logoColor=ffffff&label=&labelColor=6A7EC2)](https://discord.gg/ydWxdqbTyK)

<div align="center">
    <h1>⚔️ Markdown Dungeon ⚔️</h1>
    <i>A dungeon is a place or prison where people are held. Usually, they can be found underground</i>
</div>
<br>

Welcome to Markdown Dungeon, an example repository illustrating a dungeon using **Markdown** on GitHub. In this dungeon, readers choose options that lead them to different pages based on their decisions. It's collaborative, with multiple authors contributing to the various rooms.

| [Start a new game](./start-new-game.md) |
| --------------------------------------- |

## 📥 Installation

To get started, you need to install [yarn](https://www.npmjs.com/package/yarn). Follow these steps:

1. Clone the repo

```bash
git clone https://github.com/MakeContributions/markdown-dungeon.git
```

2. Navigate to the folder

```bash
cd markdown-dungeon
```

3. Install dependencies

```bash
yarn
```

4. Create a `.env.development` file in the project root folder, following the format of the `.env.example` file.
5. To start the development server, run:

```bash
yarn start
```

Make sure you are not using PowerShell.

6. 🎉 Open your browser and go to http://localhost:8000/ or http://localhost:8000/___graphql

## 👷‍♂️ Floor and Room Format

A **floor** is a folder, and each floor contains **rooms**, which are represented by Markdown files. Markdown links are used for navigation within the dungeon.

[Go to Github dungeon](https://github.com/)

```markdown
[Go to Github dungeon](https://github.com/)
```

## 👩‍💻 Contribution Guidelines

### 1. 📐 Make Adequately Sized Changes

- Keep changes small
- Always add a gate for readers who choose a new option to avoid dead links

#### Examples of appropriate changes:

- Add sentences to an existing "page" (file) in the room.
- Add a new option to an existing choice point, linking to an existing "room" or "floor."
- Add a new option, create a new "page," and provide content for the new option.

### 2. ⛩ Dungeon Structure

Structure should be `dungeon-name/floor-number/room-number`. Follow these guidelines:

- Dungeon name: alphanumeric with dashes separating words (e.g., **normal-dungeon-1**).
- Floor number: numeric without leading zeros.
- Room number: numeric or alphanumeric with dashes for sub-rooms.

### 3. 🔗 Use Relative Links

All links must be [relative links](https://www.coffeecup.com/help/articles/absolute-vs-relative-pathslinks/) for continued functionality.

### 4. 📏 Line Lengths

Keep lines 120 characters or less for readability.

### 5. 🪓 Blank Lines Between Options

Insert blank lines between different options for visual separation.

## 📝 License

[MIT](./LICENSE)
