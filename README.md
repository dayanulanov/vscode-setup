# VS Code Setup

A minimal and opinionated **Visual Studio Code configuration** focused on productivity, clean UI, and a smooth developer experience.

This repository contains:

- curated VS Code settings
- recommended extensions
- editor and UI optimizations
- linting and formatting preferences

The goal is to provide a **clean, fast and distraction-free development environment**.

---

# Features

### Editor

- Fira Code font with ligatures
- Smooth scrolling and cursor animation
- Compact UI
- Sticky hover and sticky scroll
- Bracket pair guides
- Auto format on save

### Formatting & Linting

- ESLint integration
- Prettier formatting rules
- Consistent code style

### Git

- GitLens integration
- Git autofetch enabled
- Smart commits

### UI

- Minimal interface
- Compact tabs
- File Icons theme
- Hidden minimap

### Terminal

- Clean terminal cursor
- Persistent session disabled
- Tabs enabled

---

# Installation

### 1. Clone repository

```bash
git clone https://github.com/dayanulanov/vscode-setup.git
```

---

### 2. Copy settings

Copy settings into your VS Code user settings folder.

**Linux / macOS**

```
~/.config/Code/User/settings.json
```

**Windows**

```
%APPDATA%\Code\User\settings.json
```

---

### 3. Install extensions

Install extensions from the list below:

```bash
code --install-extension dbaeumer.vscode-eslint
code --install-extension donjayamanne.githistory
code --install-extension eamodio.gitlens
code --install-extension esbenp.prettier-vscode
code --install-extension file-icons.file-icons
code --install-extension jock.svg
code --install-extension johnsoncodehk.vscode-tsconfig-helper
code --install-extension ms-vscode.vscode-typescript-next
code --install-extension rvest.vs-code-prettier-eslint
code --install-extension streetsidesoftware.code-spell-checker
code --install-extension streetsidesoftware.code-spell-checker-russian
code --install-extension vue.volar
code --install-extension yoavbls.pretty-ts-errors
```

---

# Extensions

```json
[
  "dbaeumer.vscode-eslint@3.0.24",
  "donjayamanne.githistory@0.6.20",
  "eamodio.gitlens@17.11.0",
  "esbenp.prettier-vscode@12.3.0",
  "file-icons.file-icons@1.1.0",
  "jock.svg@1.5.4",
  "johnsoncodehk.vscode-tsconfig-helper@0.4.4",
  "ms-vscode.vscode-typescript-next@6.0.20260305",
  "rvest.vs-code-prettier-eslint@6.0.0",
  "streetsidesoftware.code-spell-checker@4.5.6",
  "streetsidesoftware.code-spell-checker-russian@2.2.4",
  "vue.volar@3.2.5",
  "yoavbls.pretty-ts-errors@0.8.3"
]
```

---

# Structure

```
.
├── extensions.json
├── settings.json
└── README.md
```

---

# Recommended Font

Install **Fira Code** for best experience.

https://github.com/tonsky/FiraCode

---

# License

MIT
